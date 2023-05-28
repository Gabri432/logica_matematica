## Uso delle condizioni tautologiche
1. Inferenza TAUT CON: Sia C1,…,Cn <=(t) D una conseguenza tautologica. Se fra le premesse o le conseguenze intermedie di una prova abbiamo C1,…,Cn, allora nella prova possiamo inferire D;
- Validità (o correttezza) di una regola. Una regola è valida in un contesto se e solo se le nuove conseguenze che introduce in una prova sono **conseguenze logiche** (contestuali) **delle premesse** della prova stessa;
- Teorema. TAUT CON (considerata come regola) è **valida in ogni contesto**;
2. Inferenza ANA CON: Sia C1 ,…,Cn <=(tw) D una conseguenza logica nel mondo dei blocchi. Se fra le premesse o le conseguenze intermedie di una prova abbiamo C1,…,Cn, allora nella prova possiamo inferire D. Tale prova è valida solo nel contesto TW.

## Implicazione materiale
- L’implicazione è un connettivo di centrale importanza: permette di costruire **asserzioni condizionali**;
- C’è un’**unica** tavola di verità che modella vero-funzionalmente l’implicazione;
1. P <- Q (P se Q), "affinché P sia vero è sufficiente che Q sia vero", esprime **condizione sufficiente**:
- (T;T -> T), (T;F -> T), (F;T -> F), (F;F -> T);
2. P -> Q (P solo se Q), "Affinché P sia vero è necessario che Q sia vero", esprime **condizione necessaria (ma non sufficiente)**:
- (T;T -> T), (T;F -> F), (F;T -> T), (F;F -> T);
3. P <-> Q (P se e solo se Q), "(P se Q) e (P solo se Q)":
- (T;T -> T), (T;F -> F), (F;T -> F), (F;F -> T).

## Condizione necessaria e sufficiente ed equivalenza logica (Teorema)
- P <=>(c) Q se e solo se <=(c) P <-> Q;
- P <=>(t) Q se e solo se <=(t) P <-> Q.

## Teorema di deduzione
- P1,…,Pn |= Q se e solo se |= (P1 AND ... AND Pn) → Q;
- Q è conseguenza delle premesse P1,...,Pn se e solo se le premesse implicano Q.

## Regole per -> e per <-> 
1. Regole di Introduzione:
- Servono per confezionare conoscenza (un enunciato) in forma implicativa;
- Sfruttano il Teorema di Deduzione, nella forma seguente: P <=(t) Q se e solo se <=(t) P -> Q;
2. Regole di Eliminazione:
- Servono per utilizzare conoscenza (un enunciato) in forma implicativa;
- Sfruttano il principio (conseguenza tautologica) detto Modus Ponens: P, P → Q <=(t) Q.

## Conseguenze logiche notevoli
1. Contrapposizione: 
- <=(t) (P -> Q) <-> (!Q -> !P)
2. Modus Tollens:
- !Q, P -> Q <=(t) !P;
3. Modus Tollens esteso a <->:
- !Q, P <-> Q <=(t) !P;
- !Q, Q <-> P <=(t) !P.

