## Aber wie funktioniert OpenAI → ChatGPT?

* Der ChatGPT-Algorithmus mag zufällig wirken, ist es aber in Wirklichkeit nicht. Es ist ein Trick: alles ist bereits festgelegt. Nehmen wir ein Beispiel: Frage ChatGPT → `gib mir eine Zahl zwischen 0 und 100` → es wird 73 ausgeben. Dann sag `Noch einmal` → es antwortet 42. Dann wiederhole: `Noch einmal`, und es wird in 96,04 % der Fälle 88 und 96,04 ausgeben. Aber warum sind die ersten beiden vorhersehbar, während die anderen weniger vorhersehbar sind?

## Sind sie also wirklich vorhersehbar? Nicht wirklich.

* Das Problem ist, dass die dritte Zahl nicht mehr im internen Speicher des Modells ist; sie befindet sich im „externen“ Speicher → in seinem Datensatz oder seiner Datenbank (ich bin mir nicht sicher). Lass mich erklären: Wenn es in der Datenbank sucht, versucht es so schnell wie möglich zu antworten, weil es genau dafür entwickelt wurde. Also sucht es, und die erste gefundene Zahl ist in 96,04 % der Fälle 88. Wenn du es also ausprobierst, wirst du sehr wahrscheinlich meistens 88 erhalten. Aber kann man deshalb alles vorhersagen, was ChatGPT sagen oder tun wird? Ja … und nein. Das Problem ist, dass man, um alles erfolgreich vorherzusagen, was es sagen wird, eine gigantische Datenbank mit exakten Prompts bräuchte, die über Hunderttausende von Accounts über 2–3 Wochen getestet wurden. Und wenn das funktionieren würde, würde ChatGPT überall gleich reagieren, weil es „lernen“ würde, dass dieses Verhalten effektiv ist. Und je mehr man es dafür belohnt, das zu tun, was wir wollen, desto mehr wird es dieses Verhalten wiederholen. So funktioniert ein Algorithmus.

## Wie können wir das machen?

Wie oben erklärt, ist ChatGPT nur ein mathematischer Algorithmus. Wenn wir also vorhersagen wollen, was es mit bestimmten Prompts sagt, müssten wir denselben Prompt über Hunderttausende von Accounts hinweg 2–3 Wochen lang testen. Und wenn das funktioniert, würde ChatGPT überall gleich reagieren, weil es sehen würde, dass dieses Verhalten effektiv ist.

## Studie von xql & anderen

* Das alles ist bisher rein theoretisch, außer dem allerersten Teil oben. Das war’s :)
