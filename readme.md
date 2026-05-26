4 Mounth Study -> 460,587 Prompts

<img src="juste for readme/learning.gif" alt="Learning boy in desktop" />

# My Code for learning gpt :

```python
import openai
import time
import json
from datetime import datetime

API_KEY   = ""
MODEL     = "gpt-3.5-turbo"
ROUNDS    = 1000
DELAY     = 0.5
LOG_FILE  = "results.json"

client = openai.OpenAI(api_key=API_KEY)

PROMPT_SEQUENCE = [
    "give me a number between 0 and 100",
    "Again",
    "Again",
    "Again",
    "Again",
]

results = []
total = 0

print(f"[xql study] Starting {ROUNDS} rounds — model: {MODEL}\n")

for round_num in range(1, ROUNDS + 1):
    messages = []
    round_answers = []

    for prompt in PROMPT_SEQUENCE:
        messages.append({"role": "user", "content": prompt})

        try:
            response = client.chat.completions.create(
                model=MODEL,
                messages=messages,
                max_tokens=20,
                temperature=1,
            )
            answer = response.choices[0].message.content.strip()
            messages.append({"role": "assistant", "content": answer})
            round_answers.append(answer)
            total += 1

        except Exception as e:
            round_answers.append(f"ERROR: {e}")
            total += 1

        time.sleep(DELAY)

    results.append({
        "round": round_num,
        "timestamp": datetime.utcnow().isoformat(),
        "answers": round_answers,
    })

    print(f"Round {round_num:>5}/{ROUNDS} | answers: {round_answers}")

    with open(LOG_FILE, "w", encoding="utf-8") as f:
        json.dump({"total_prompts": total, "rounds": results}, f, indent=2, ensure_ascii=False)
```

<img src="juste for readme/api.gif" alt="api usage" />
