## Equivalenza Logica
- Due proposizioni sono `tautologicamente (o, proposizionalmente) equivalenti` , scritto P <=>(t) Q, se e solo se hanno lo **stesso valore di verità in tutte le interpretazioni booleane**.
- Sono `logicamente equivalenti` in un contesto C, scritto P <=>(c) Q se e solo se hanno lo **stesso valore di verità in tutte le interpretazioni possibili** nel contesto.
- Se P e Q sono tautologicamente equivalenti, allora sono logicamente equivalenti in ogni contesto.

## Rimpiazzamento Logico
- Il rimpiazzamento (o riscrittura), quando P <=> Q, permette di rimpiazzare P con Q in una formula F, ottenendo una formula G <=> F.
- Tale proprietà vale sia per l'equivalenza logica che tautologica in un contesto C.
- La riscrittura serve per dire una stessa cosa in modi diversi, se ritenuti più chiari o più adatti in un ragionamento o più convenienti.

## Equivalenze logiche notevoli
| Proprietà       | Regola 1                                    | Regola 2                                    |
| :---            | :---                                        | :---                                        |
|Doppia Negazione |                                             | !A <=>(t) A                                 |
|DeMorgan:        |!(A and B) <=>(t) !A or !B                   | !(A or B) <=>(t) !A and !B                  |
|Associatività:   |(A and B) and C <=>(t) A and (B and C)       | (A or B) or C <=>(t) A or (B or C)          |
|Commutatività:   |A and B <=>(t) B and A                       | A or B <=>(t) B or A                        |
|Idempotenza:     |A and A <=>(t) A                             | A or A <=>(t) A                             |
|Assorbimento:    |A <=>(t) A and (A or B)                      | A <=>(t) A and (A or B)                     |
|Distributività:  |A and (B or C) <=>(t) (A and B) or (A and C) | A or (B and C) <=>(t) (A or B) and (A or C) |