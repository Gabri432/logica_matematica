## Introduzione alla logica proposizionale
- Con la logica proposizionale si vuole definire la logica dei connettivi e delle lettere proposizionali.
- Viene detta `Logica delle proposizioni atomiche` la logica degli enunciati semplici insieme alla relazione di identità.
- Viene definito `Enunciato` una frase **interpretata come vera o falsa** in una data `circostanza`. Tale enunciato può essere `semplice` se non è composto da altri enunciati.

## Le proposizioni atomiche
- Le proposizioni atomiche sono le più semplici frasi interpretabili come vere o false in una data circostanza di un `contesto`. 
- Un contesto presenta un `linguaggio`, che è dato da un vocabolario e da una sintassi, e da una `semantica`, che è data dalle circostanze possibili e dalla interpretazione, cioè attribuzione di un valore di verità alla proposizione in una data circostanza.
- I `predicati` stabiliscono relazioni tra oggetti o loro proprietà.

## Il contesto
- Il contesto è un **insieme di circostanze**, la logica non si occupa di stabilirlo.
- La semantica è l'insieme delle circostanze possibili che dipendono dal contesto.
- In una circostanza la `costante` **denota un unico oggetto**. Una proposizione atomica è **vera** se la proprietà o relazione espressa dal predicato vale per gli oggetti indicati dalle costanti, altrimenti è **falsa**.

## Il ragionamento
- Un ragionamento è una serie di frasi riferite ad un contesto, in cui una, detto `conseguente`, segue dalle altre, dette `premesse`.
- Viene definito `logicamente valido` in un contesto se e solo se il conseguente è vero in *tutte* le circostanze del contesto in cui sono vere le premesse. Si dice anche che il conseguente è `conseguenza logica` delle premesse.
- Un ragionamento è `fondato in una circostanza` se e solo se è valido e le premesse sono vere in essa.
-  Per dimostrare che un ragionamento non è valido si mostra un `controesempio`, cioè una circostanza in cui il conseguente è **falso pur essendo vere le premesse**.
- Il metodo dei controesempi si può usare anche per dimostrare la validità di un ragionamento dimostrando che non ci sono controesempi.

## Le prove
- Una prova dimostra la conseguenza a partire dalle premesse attraverso una successione di passaggi la cui validità logica è evidente.
- Un `passaggio` introduce una nuova conseguenza logica delle premesse, utilizzabile in passaggi successivi. L’ultimo passaggio introduce la conseguenza desiderata.
- Le prove possono essere `formali`, cioè giustificati informalmente ma rigorosamente, o `informali`, ossia avvengono in un sistema formale costituito da un `linguaggio formale` per le formule e `regole d'inferenza` formali, cioè regole che governano i passaggi.

### Esempio di prova informale (nel contesto: parentele)
- Premesse: (i) Ugo e Ada non sono parenti (ii) Gigi è il padre di Ada;
- Conseguenza: Gigi non è il padre di Ugo;
- Dim.: Supponiamo per assurdo che Gigi sia il padre di Ugo. Siccome sappiamo (da (ii)) che Gigi è il padre di Ada, Gigi è il padre di Ugo e di Ada. Dunque Ugo e Ada sono fratello e sorella. Ma ciò è assurdo poiché sappiamo (da (i)) che Ugo e Ada non sono parenti.
Quindi Gigi non è il padre di Ugo.