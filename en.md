# But how does OpenAI → ChatGPT work?

* The ChatGPT algorithm may seem random, but in reality it is not. It’s a trick: everything is already determined. Let’s take an example: ask ChatGPT → `give me a number between 0 and 100` → it will give you 73. Then say `Again` → it will answer 42. Then repeat: `Again`, and it will answer 88 in 96.04% of cases. But why are the first two predictable while the others are less so?

## So are they really predictable? Not really.

* The issue is that the third number is no longer in the model’s internal memory; it is in “external” memory → in its dataset or database (I’m not sure). Let me explain: when it searches the database, it tries to respond as fast as possible, because that’s what it is designed to do. So it searches, and the first number found is, in 96.04% of cases, 88. So if you try it, you will likely get 88 most of the time. But can we therefore predict everything ChatGPT will say or do? Yes… but also no. The problem is that if we want to successfully predict everything it will say, we would need a gigantic database of exact prompts, tested across hundreds of thousands of accounts over 2–3 weeks. And if we succeeded, ChatGPT would respond the same way everywhere, because it would “learn” that it is effective. And the more we reward it for doing what we want, the more it will repeat that behavior. That is how an algorithm works.

## How can we do it?

So, as explained above, ChatGPT is just a mathematical algorithm. Therefore, if we want to predict what it will say using certain prompts, we would need to test the exact same prompt across hundreds of thousands of accounts for 2–3 weeks. And if that worked, ChatGPT would respond the same way everywhere, because it would see that this behavior is effective.

## Study by xql & others

* All of this is purely theoretical for now, except for the very first part at the top. That’s it :)
