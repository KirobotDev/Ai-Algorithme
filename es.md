# Pero ¿cómo funciona OpenAI → ChatGPT?

* El algoritmo de ChatGPT puede parecer aleatorio, pero en realidad no lo es. Es un truco: todo está ya determinado. Tomemos un ejemplo: dile a ChatGPT → `dame un número entre 0 y 100` → te dará 73. Luego dile `otra vez` → responderá 42. Luego repite: `otra vez`, y responderá 88 en el 96,04 % de los casos. Pero, ¿por qué los dos primeros son predecibles mientras que los demás lo son menos?

## Entonces, ¿realmente son predecibles? No realmente.

* El problema es que el tercer número ya no está en la memoria interna del modelo; está en la memoria “externa” → en su conjunto de datos o base de datos (no estoy seguro). Te explico: cuando realiza una búsqueda en la base de datos, intenta responder lo más rápido posible, porque está diseñado para eso. Entonces busca, y el primer número encontrado es, en el 96,04 % de los casos, 88. Por eso, si lo intentas, probablemente obtendrás 88 la mayoría de las veces. Pero, entonces, ¿podemos predecir todo lo que ChatGPT va a decir o hacer? Sí… pero no. El problema es que si queremos predecir todo lo que va a decir, necesitaríamos una base de datos gigantesca de prompts exactos, probados en cientos de miles de cuentas durante 2 o 3 semanas. Y si lo lográramos, ChatGPT respondería lo mismo en todas partes, porque “aprendería” que eso es eficaz. Y cuanto más se le recompensa por hacer lo que queremos, más repite ese comportamiento. Así funciona un algoritmo.

## ¿Cómo podemos hacerlo?

Entonces, como se explicó arriba, ChatGPT es solo un algoritmo matemático. Por lo tanto, si queremos predecir lo que dirá usando ciertos prompts, necesitaríamos probar el mismo prompt exacto en cientos de miles de cuentas durante 2 o 3 semanas. Y si eso funcionara, ChatGPT respondería lo mismo en todas partes, porque vería que ese comportamiento es eficaz.

## Estudio de xql y otros

* Todo esto es puramente teórico por ahora, excepto la primera parte de arriba. Eso es todo :)
