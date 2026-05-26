# Maar hoe werkt OpenAI → ChatGPT?

* Het ChatGPT-algoritme lijkt misschien willekeurig, maar in werkelijkheid is dat niet zo. Het is een truc: alles is al bepaald. Laten we een voorbeeld nemen: vraag ChatGPT → `geef me een getal tussen 0 en 100` → het zal je 73 geven. Zeg dan `Nog een keer` → het zal 42 antwoorden. Herhaal dan: `Nog een keer`, en het zal in 96,04% van de gevallen 88 antwoorden. Maar waarom zijn de eerste twee voorspelbaar, terwijl de andere dat minder zijn?

## Zijn ze dus echt voorspelbaar? Niet echt.

* Het probleem is dat het derde getal niet meer in het interne geheugen van het model zit; het bevindt zich in het "externe" geheugen → in zijn dataset of database (ik weet het niet zeker). Laat het me uitleggen: als het in de database zoekt, probeert het zo snel mogelijk te reageren, want daar is het voor ontworpen. Het zoekt dus, en het eerste getal dat wordt gevonden is, in 96,04% van de gevallen, 88. Dus als je het probeert, zul je waarschijnlijk meestal 88 krijgen. Maar kunnen we daarom alles voorspellen wat ChatGPT zal zeggen of doen? Ja... maar ook nee. Het probleem is dat als we met succes alles willen voorspellen wat het zal zeggen, we een gigantische database met exacte prompts nodig hebben, getest in honderdduizenden accounts gedurende 2-3 weken. En als we daarin zouden slagen, zou ChatGPT overal op dezelfde manier reageren, omdat het zou 'leren' dat het effectief is. En hoe meer we het belonen om te doen wat we willen, hoe vaker het dat gedrag zal herhalen. Zo werkt een algoritme.

## Hoe kunnen we dat doen?

Dus, zoals hierboven uitgelegd, is ChatGPT gewoon een wiskundig algoritme. Daarom, als we willen voorspellen wat het zal zeggen met behulp van bepaalde prompts, zouden we precies dezelfde prompt gedurende 2-3 weken in honderdduizenden accounts moeten testen. En als dat zou werken, zou ChatGPT overal op dezelfde manier reageren, omdat het zou inzien dat dit gedrag effectief is.

## Studie door xql & anderen

* Dit alles is voorlopig puur theoretisch, met uitzondering van het allereerste deel bovenaan. Dat is het :)
