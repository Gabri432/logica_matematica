## Regole di inferenza
- `(= Intro)` la proposizione n = n è vera per qualsiasi costante n in qualsiasi contesto e circostanza, per cui la posso inferire in qualunque punto della prova.
- `(= Elim)` se nelle premesse o in passaggi precedenti ho ottenuto n = m, allora posso sostituire m al posto di qualche occorrenza di n in una proposizione P(n) già dimostrata, inferendo una nuova proposizione P(m).

## Vero-funzionalità
- Connettivo: costruisce enunciati composti a partire da enunciati più semplici, che chiameremo `componenti`.
- `Connettivo vero-funzionale`: il valore di verità di un enunciato composto è funzione solo dei valori di verità degli enunciati componenti, cioè è definibile mediante una **tavola di verità**.

## Formule ben Formate (FBF)
- Una formula ben formata associata ad un contesto è o una **proposizione atomica** del linguaggio oppure per costruzione ricorisiva, e quindi generata da uno o più **strati**.
- Se non è generabile per strati, non è una fbf. 

## Logica dei connettivi
- P è `logicamente vera` (in un contesto) se e solo se P è **vera in tutte le circostanze del contesto**.
- P è `tautologicamente vera` o `tautologia` se e solo se P è **vera in tutte le interpretazioni booleane** (in tutte le righe della tavola di verità).
- P è `logicamente possibile` (in un contesto) se e solo se **esiste una circostanza del contesto in cui P è vera**.
- P è `tautologicamente` (o proposizionalmente) `possibile` (o soddisfacibile) se e solo se **esiste una interpretazione booleana (esiste una riga della tavola) in cui P è vera**.
- P è `logicamente impossibile` (in un contesto) se e solo se P **è falsa in tutte le circostanze del contesto**.
- P è `tautologicamente` (o proposizionalmente) `impossibile` (o insoddisfacibile) se e solo se P **è falsa in tutte le interpretazioni booleane (in tutte le righe della tavola di verità)**.
- P è logicamente impossibile in un contesto C sse !P è logicamente vera in C.
- P è proposizionalmente impossibile sse !P è tautologicamente vera.

## Proprietà importanti
- Se P è una tautologia allora P è logicamente vera in ogni contesto, ma vi sono formule logicamente vere (ad es.) in TW, che non sono tautologie.
- Se P è possibile in un contesto allora è anche proposizionalmente possibile, ma vi sono formule proposizionalmente possibili ma impossibili.

[Prossimo](https://github.com/Gabri432/logica_matematica/blob/master/conseguenza_logica_e_tautologica.md)