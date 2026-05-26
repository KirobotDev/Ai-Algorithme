# Mas como funciona o OpenAI → ChatGPT?

* O algoritmo do ChatGPT pode parecer aleatório, mas na realidade não é. É um truque: tudo já está determinado. Vamos dar um exemplo: peça ao ChatGPT → `me dê um número entre 0 e 100` → ele vai te dar 73. Então diga `De novo` → ele responderá 42. Então repita: `De novo`, e ele responderá 88 em 96,04% dos casos. Mas por que os dois primeiros são previsíveis enquanto os outros são menos?

## Então eles são realmente previsíveis? Na verdade não.

* O problema é que o terceiro número não está mais na memória interna do modelo; está na memória "externa" → em seu conjunto de dados ou banco de dados (não tenho certeza). Deixe-me explicar: quando ele pesquisa no banco de dados, ele tenta responder o mais rápido possível, porque é para isso que foi projetado. Então ele pesquisa, e o primeiro número encontrado é, em 96,04% dos casos, 88. Então, se você tentar, provavelmente obterá 88 na maioria das vezes. Mas podemos, portanto, prever tudo o que o ChatGPT dirá ou fará? Sim... mas também não. O problema é que se quisermos prever com sucesso tudo o que ele dirá, precisaríamos de um banco de dados gigantesco de prompts exatos, testados em centenas de milhares de contas ao longo de 2 a 3 semanas. E se tivéssemos sucesso, o ChatGPT responderia da mesma maneira em todos os lugares, porque ele "aprenderia" que isso é eficaz. E quanto mais o recompensamos por fazer o que queremos, mais ele repetirá esse comportamento. É assim que funciona um algoritmo.

## Como podemos fazer isso?

Então, como explicado acima, o ChatGPT é apenas um algoritmo matemático. Portanto, se quisermos prever o que ele dirá usando certos prompts, precisaríamos testar exatamente o mesmo prompt em centenas de milhares de contas por 2 a 3 semanas. E se isso funcionasse, o ChatGPT responderia da mesma maneira em todos os lugares, porque veria que esse comportamento é eficaz.

## Estudo por xql & outros

* Tudo isso é puramente teórico por enquanto, exceto pela primeira parte no topo. É isso :)
