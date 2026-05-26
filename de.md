# Aber wie funktioniert OpenAI → ChatGPT?

* Der ChatGPT-Algorithmus mag zufällig erscheinen, ist es aber in Wirklichkeit nicht. Es ist ein Trick: Alles ist bereits festgelegt. Nehmen wir ein Beispiel: Fragen Sie ChatGPT → `gib mir eine Zahl zwischen 0 und 100` → er wird Ihnen 73 geben. Sagen Sie dann `Nochmal` → er wird 42 antworten. Wiederholen Sie dann: `Nochmal`, und er wird in 96,04 % der Fälle 88 antworten. Aber warum sind die ersten beiden vorhersehbar, während die anderen es weniger sind?

## Sind sie also wirklich vorhersehbar? Nicht wirklich.

* Das Problem ist, dass sich die dritte Zahl nicht mehr im internen Speicher des Modells befindet; sie befindet sich im „externen“ Speicher → in seinem Datensatz oder seiner Datenbank (ich bin mir nicht sicher). Lassen Sie es mich erklären: Wenn es die Datenbank durchsucht, versucht es so schnell wie möglich zu antworten, denn dafür ist es ausgelegt. Es sucht also, und die erste gefundene Zahl ist in 96,04 % der Fälle 88. Wenn Sie es also versuchen, werden Sie wahrscheinlich meistens 88 erhalten. Aber können wir deshalb alles vorhersagen, was ChatGPT sagen oder tun wird? Ja… aber auch nein. Das Problem ist, dass wir, wenn wir alles, was es sagen wird, erfolgreich vorhersagen wollen, eine gigantische Datenbank mit genauen Prompts benötigen würden, die über 2–3 Wochen hinweg an Hunderttausenden von Konten getestet wurden. Und wenn wir erfolgreich wären, würde ChatGPT überall gleich reagieren, weil es „lernen“ würde, dass dies effektiv ist. Und je mehr wir es dafür belohnen, dass es tut, was wir wollen, desto öfter wird es dieses Verhalten wiederholen. So funktioniert ein Algorithmus.

## Wie können wir das machen?

Wie oben erklärt, ist ChatGPT also nur ein mathematischer Algorithmus. Wenn wir also vorhersagen wollen, was er bei bestimmten Prompts sagen wird, müssten wir genau denselben Prompt über 2–3 Wochen hinweg an Hunderttausenden von Konten testen. Und wenn das funktionieren würde, würde ChatGPT überall gleich reagieren, weil er sehen würde, dass dieses Verhalten effektiv ist.

## Studie von xql & anderen

* Das alles ist vorerst rein theoretisch, mit Ausnahme des allerersten Teils oben. Das war's :)
