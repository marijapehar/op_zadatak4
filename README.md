# Vrtuljak (Ringišpil) - višedretveni program u C

Ovo je implementacija simulacije vrtuljka s pomoću dretvi i semafora u programskom jeziku C.

---

## Opis zadatka

Program simulira rad vrtuljka s ograničenim brojem mjesta (N).  
Postoje dva tipa dretvi/procesa:

- **Posjetitelj** — dretve koje predstavljaju posjetitelje koji žele ući na vožnju.
- **Vrtuljak** — dretva koja upravlja vrtuljkom i pokreće vožnju kada je vrtuljak pun.

---

### Pravila simulacije

- Na vrtuljak može stati najviše N posjetitelja.
- Posjetitelji čekaju da se oslobode mjesta ako je vrtuljak pun.
- Vrtuljak se pokreće samo kada je pun.
- Posjetitelji ne smiju izaći dok vožnja ne završi.
- Nakon završetka vožnje, svi posjetitelji silaze i oslobađaju mjesta za nove.
