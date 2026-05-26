# Ma come funziona OpenAI → ChatGPT?

* L'algoritmo di ChatGPT può sembrare casuale, ma in realtà non lo è. È un trucco: tutto è già stabilito. Facciamo un esempio: chiedi a ChatGPT → `dammi un numero tra 0 e 100` → ti darà 73. Poi di' `Ancora` → risponderà 42. Poi ripeti: `Ancora`, e risponderà 88 nel 96,04% dei casi. Ma perché i primi due sono prevedibili mentre gli altri lo sono meno?

## Quindi sono davvero prevedibili? Non esattamente.

* Il problema è che il terzo numero non è più nella memoria interna del modello; è nella memoria "esterna" → nel suo dataset o database (non ne sono sicuro). Lascia che ti spieghi: quando cerca nel database, cerca di rispondere il più velocemente possibile, perché è per questo che è stato progettato. Quindi cerca, e il primo numero trovato è, nel 96,04% dei casi, 88. Quindi, se ci provi, probabilmente otterrai 88 la maggior parte delle volte. Ma possiamo quindi prevedere tutto ciò che ChatGPT dirà o farà? Sì... ma anche no. Il problema è che se volessimo prevedere con successo tutto ciò che dirà, avremmo bisogno di un database gigantesco di prompt esatti, testati su centinaia di migliaia di account per 2-3 settimane. E se ci riuscissimo, ChatGPT risponderebbe allo stesso modo ovunque, perché "imparerebbe" che è efficace. E più lo ricompensiamo per aver fatto ciò che vogliamo, più ripeterà quel comportamento. È così che funziona un algoritmo.

## Come possiamo farlo?

Quindi, come spiegato sopra, ChatGPT è solo un algoritmo matematico. Pertanto, se vogliamo prevedere cosa dirà utilizzando determinati prompt, dovremmo testare esattamente lo stesso prompt su centinaia di migliaia di account per 2-3 settimane. E se funzionasse, ChatGPT risponderebbe allo stesso modo ovunque, perché vedrebbe che questo comportamento è efficace.

## Studio di xql e altri

* Tutto questo è puramente teorico per ora, tranne per la primissima parte in alto. Questo è tutto :)
