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

## Conseguenza logica e tautologica
- `Conseguenza logica`: Q segue logicamente da P1,…,Pn in un contesto C se e solo se Q è vera in tutte le interpretazioni nel contesto, in cui P1,…,Pn sono vere. Notazione: P1,…,Pn <=(c) Q.
- `Conseguenza tautologica`: Q segue tautologicamente da P1,…,Pn se e solo se Q è vera in ogni interpretazione booleana in cui P1,…,Pn sono vere. Notazione: P1,…,Pn <=(t) Q. Siccome le interpretazioni possibili in un contesto sono un sottoinsieme di quelle booleane: P1,…,Pn <=(t) Q implica P1,…,Pn <=(c) Q, ma non vale in genere il viceversa.

## Controesempio
1. Se non troviamo interpretazioni booleane in cui C è falsa e le premesse sono tutte vere , allora C è conseguenza tautologica delle premesse.
2. Se vi sono controesempi, ma nessuna di questi corrisponde ad una interpretazione possibile nel contesto, allora C è conseguenza logica delle premesse nel contesto ma non è conseguenza tautologica.
3. Se 1,2 non valgono, C non è neppure conseguenza logica nel contesto.

## Conseguenze fondamentali per i connettivi AND e OR
1. AND Intro 
- A, B <=(t) A AND B;
2. AND Elim 
- A AND B <=(t) A; 
- A AND B <=(t) B;
3. OR Intro
- A <=(t) A OR B;
- B <=(t) A OR B;

[Prossimo](https://github.com/Gabri432/logica_matematica/blob/master/implicazione_materiale.md)