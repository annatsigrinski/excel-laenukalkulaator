# Exceli pangalaenu kalkulaator

See on iseseisev Exceli portfoolio projekt, mille eesmärk on näidata laenuga seotud arvutusi, maksegraafiku koostamist ja stsenaariumianalüüsi.

## Projekti eesmärk

Failis on koostatud pangalaenu kalkulaator, mis arvutab laenu kuumakse, kogumakse, kogukulu, intressikulu, hinnangulise kulukuse määra ning maksekoormuse netosissetulekust.

## Faili struktuur

Exceli fail sisaldab järgmisi lehti:

- `Sisendid` – laenusumma, intressimäär, periood, lepingutasu, haldustasu, sissetulek ja muud kohustused
- `Maksegraafik` – kuupõhine maksegraafik koos intressi, põhiosa, haldustasu, lõppjäägi ja kumulatiivse intressiga
- `Stsenaariumid` – erinevate laenutingimuste võrdlus kuumakse, kogukulu ja kulukuse määra põhjal
- `Kokkuvõte` – projekti põhinäitajate ja visualiseeringute ülevaade

## Kasutatud Exceli oskused

- PMT funktsioon annuiteetmakse arvutamiseks
- RATE funktsioon hinnangulise kulukuse määra leidmiseks
- EDATE funktsioon maksekuupäevade arvutamiseks
- IF, MAX ja MIN loogikavalemid
- maksegraafiku koostamine
- stsenaariumianalüüs
- protsendi- ja valuutavormingud
- tabelite vormindamine
- andmete valideerimine kuupäeva sisestamiseks

## Arvutusloogika

Kuumakse arvutatakse annuiteetlaenu põhimõttel.

Kogumakse kuus:

```text
kogumakse kuus = kuumakse + igakuine haldustasu
