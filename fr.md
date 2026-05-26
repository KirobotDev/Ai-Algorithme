# Mais comment fonctionne OpenAI → ChatGPT

* L’algorithme de ChatGPT peut paraître aléatoire, mais en réalité ce n’est pas le cas. C’est une ruse : tout est prévu. Prenons un exemple : dites à ChatGPT → `donne-moi un numéro entre 0 et 100` → il va vous donner 73. Dites-lui `Encore` → il va vous répondre 42. Puis répétez : `Encore`, il va vous répondre 88 dans 96,04 % des cas. Mais pourquoi les deux premiers sont-ils prévisibles et les autres moins ?

## Alors, sont-ils vraiment prévisibles ? Pas vraiment.

* Le problème, c’est que le troisième chiffre n’est plus en mémoire interne du code, il est en mémoire « externe » → dans son dataset ou sa base de données (je ne sais pas exactement). Je vous explique : quand il fait une recherche dans la base de données, il veut répondre le plus vite possible, car il est fait pour ça. Alors il cherche, et le premier nombre trouvé est, dans 96,04 % des cas, 88. Donc si vous essayez, il apparaîtra 88 dans la plupart des cas. Mais du coup, peut-on prévoir tout ce que ChatGPT va dire ou faire ? Oui… mais non. Le problème, c’est que si on veut réussir à prévoir tout ce qu’il va dire, il faudrait une gigantesque base de données de prompts à l’exact près, puis les tester sur des centaines de milliers de comptes pendant 2 à 3 semaines. Et si on y arrivait, ChatGPT répondrait la même chose, car s’il donne la bonne réponse (celle qu’on veut via le prompt de prédiction), il “apprendrait” que c’est efficace. Et plus on lui donne de récompenses quand il fait ce qu’on veut, plus il reproduit ce comportement. C’est ainsi que fonctionne un algorithme.

## Comment peut-on faire ?

Alors, comme expliqué ci-dessus, ChatGPT est juste un algorithme mathématique. Donc si on veut pouvoir prévoir ce qu’il va dire via certains prompts, il faudrait tester un même prompt exact sur des centaines de milliers de comptes pendant 2 ou 3 semaines. Et si on y arrivait, ChatGPT répondrait la même chose partout, car il verrait que cela fonctionne bien.

## Étude by xql & others

* Tout cela est purement théorique pour le moment, sauf la première partie tout en haut. Voilà :)
