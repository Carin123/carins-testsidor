Här testar jag att lägga in ett scenario/testfall och anpassa det till hjälptext.

## Skapa ny – Tryckt monografi

Exempel: Under cover, ISBN 9789188107213, Voyager BibID 19775078


### Adminmetadata
* Skapad av/Organisation/Namn (040 ‡a)
  
  Förval: den sigel som skapat posten


* Uppgraderad eller importerad av/Organisation/Namn (040 ‡d)

*Exempel: S*

* Bibliografi/Bibliotek/Sigel (042 ‡9)

Ange sigel eller bibliografikod

* Identifikator/Systemnummer/Värde
Exempel: (BOKR)9789188107213
(Bokinfos systemnummer som följer med vid postimport, ska inte ändras)

* Katalogiseringsspråk (040 ‡b)
- länkning till entitet

*Exempel: svenska (swe)*

* Katalogiseringsregler (040 ‡e)
- länkning till entiteter + skapa lokal entitet. RDA finns inte som länkbar entitet.
Förval: länkning till entitet: marc/isbd + lokalt skapad entitet med Kod: rda

*Exempel: marc/Isbd (länkad entitet)*
+ Kod: rda

* Beskrivningsnivå (000/05)
- länkning till entiteter

Exempel:  *CIP-post, ändra till biblioteksnivå*

### Instans
* Utgivningssätt
- val från lista

*Exempel: Monografisk resurs*

* Har titel/Titel/Huvudtitel (245 ‡a)

*Exempel: Under cover*

Har titel/Titel/Huvudtitel/Övrig titelinformation (245 ‡b)

*Exempel: livet som underrättelseagent åt MI5*

* Upphovsuppgift
Exempel: Tom Marcus ; översättning: Svante Skoglund

* Identifikator/Typ

*Exempel: ISBN*

Identifikator/Typ/Värde (020 ‡a)

*Exempel: 9789188107213*

Identifikator/Bestämning (020 ‡q)

*Exempel: inbunden*

* Upplageuppgift

*Exempel: Första upplagan*

* Utgivning
- plats/Benämning (264 -/1 ‡a)

*Exempel: [Göteborg]*
- agent/Benämning (264 -/1 ‡b)

*Exempel: NoNa*
- datum (264 -/1 ‡c)

*Exempel: 2017*

Typ av utgivningsdatum/utgivningsstatus (008/06)
- länkning till entitet

*Exempel: s (= ett årtal)* 

* Tillverkning
- plats/Benämning (264 -/3 ‡a)

*Exempel: Falun*
- agent/Benämning (264 -/3 ‡b)

*Exempel: Scandbook*

* Kronologisk täckning (008/11-17)

*Exempel: 2017____* 

(jfr datum …)

* Utgivningsland (008/15-17)
- länkning till entitet

*Exempel: Sverige (sw)*

* Medietyp (337 ‡b)
- länkning till entitet

*Exempel:  n (= unmediated)*

* Bärartyp (338 ‡b)
- länkning till entitet

*Exempel:  nc (= volume)*

* Form för katalogiserat objekt (008/23)
- länkning till entitet

*Exempel: - (= ingen av följande)*

* Omfång/Benämning

*Exempel: 319 sidor*

* Mått/Benämning

*Exempel: 24 cm*

### Verk
* Instans av Verk/Text

* Har titel/Titel/Huvudtitel (240 1-/0 ‡a)

*Exempel:  Soldier spy*

* Medverkan och funktion/Primär medverkan/Agent/Person (100 1/- ‡a)
- lokal entitet
Medverkan och funktion/Primär medverkan/Agent/Person/Familjenamn

*Exempel: Marcus*

Medverkan och funktion/Primär medverkan/Agent/Person/Förnamn

*Exempel: Tom*

-Medverkan och funktion/Medverkan/Agent/Funktion (100 ‡4)
- länkning till entitet

*Exempel: relator/author (= författare)*

* Medverkan och funktion/Medverkan/Agent/Person (700 1/- ‡a)
- länkad entitet

*Exempel: Skoglund, Svante, 1960-*

-Medverkan och funktion/Medverkan/Agent/Funktion (700 ‡4)
- länkning till entitet

*Exempel: relator/trl (= översättare)*

* Klassifikation/DDK-klassifikation/Kod (082 0/4 ‡a)

*Exempel: 327.12092*

Klassifikation/DDK-klassifikation/Kod/Klassifikationsupplaga (082 ‡2)

*Exempel: 23/swe*

* Klassifikation/Kod (084 0/4 ‡a)

*Exempel: Sei-e*

Klassifikation/Termlista/Termlista (084 ‡2)

*Exempel: kssb*

Klassifikation/Termlista/Termlista/Version (084 ‡2)

*Exempel: 8*

Klassifikation/Termlista/Termlista/Samma sak som (084 ‡2)
- länkad entitet

*Exempel: term/kssb/8*

* Ämne/Agent/Person (600 1/- ‡a)
- lokal entitet
Ämne/Agent/Person/Familjenamn

*Exempel: Marcus*

Ämne/Agent/Person/Förnamn

*Exempel: Tom*

Ämne/Agent/Jurisdiktion/Är del av/Jurisdiktion/Namn (610 1/4 ‡a)
- lokal entitet

*Exempel: Storbritannien*

Ämne/Agent/Jurisdiktion/Namn på underordnad enhet (610 ‡b)

*Exempel: MI5*

- länkning till entitet - sao-term (650 -7- ‡a, ‡2 sao)

*Exempel: Säkerhetspolitik*

- länkning till entitet - sao-term (650 -7- ‡a, ‡2 sao)

*Exempel: Spionage*

- länkning till entitet - sao-term (650 -7- ‡a, ‡2 sao)

*Exempel: Terrorismbekämpning*

- länkning till entiteter - geografiskt ämnesord (651 -/4 ‡a)

*Exempel: Storbritannien*

* Genre/form
- länkning till entiteter – saogf-termer (655 ‡a, ‡2 saogf)

*Exempel: Självbiografier*

- länkning till entitet – litterär genre (008/33)

*Exempel: 0 ( = marc/NotFictionNotFurtherSpecified = Ej skönlitterärt verk)*

- länkning till entitet – biografiskt material (008/34)

*Exempel: a (= autobiography = självbiografi)*

* Språk (008/35-37) (+ även i 041 ‡a, om relationen Översättning av finns)
- länkning till entiteter

*Exempel: svenska (swe)*

* Översättning av/Verk/Språk (041 ‡h)
- länkning till entitet

*Exempel: engelska (eng)*

* Innehållstyp (336 ‡b)
- länkning till entiteter

*Exempel: text (txt)*
