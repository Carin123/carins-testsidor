UNDER ARBETE
Här testar jag att lägga in ett scenario/testfall och anpassa det till hjälptext.

Hjälptexten beskriver ett antal vanligt förekommande fält, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/ "Anvisningar för katalogisering - RDA").

## Skapa ny – Tryckt monografi

Exempel - hämtade från: Under cover, ISBN 9789188107213, Voyager BibID 19775078 samt  
Kjellström, Rolf: Nybyggarliv i Vilhelmina. 1. Träd och växter som resurs, Voyager BibID 13457927

[Adminmetadata](#adminmetadata)  
[Instans](#instans)  
[Verk](#verk)  


### Adminmetadata
* Skapad av/Organisation/Namn (040 ‡a)  
  Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: BOKR```

* Uppgraderad eller importerad av/Organisation/Namn (040 ‡d)  
  Skriv in sigel som har uppgraderat (ändrat nivå) eller importerat posten. För att söka fram sigel, se [Biblioteksdatabasen](https://biblioteksdatabasen.libris.kb.se/ "Biblioteksdatabasen")
  ```Exempel: S```

* Bibliografi/Bibliotek/Sigel (042 ‡9)  
  Ange bibliografikod genom att skriva in sigel. För att söka fram sigel, se [Biblioteksdatabasen](https://biblioteksdatabasen.libris.kb.se/ "Biblioteksdatabasen")

* Identifikator/Systemnummer/Värde  (035 ‡a)
  Om ett systemnummer finns i förhandspost, till exempel Bokinfos systemnummer, låt det vara kvar oförändrat.  
   ```Exempel: (BOKR)9789188107213```

* Katalogiseringsspråk (040 ‡b)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```

* Katalogiseringsregler (040 ‡e)  
  För post katalogiserad enligt RDA, länka till entitet: marc/Isbd samt skapa lokal entitet med Kod: rda    
  ```Exempel: marc/Isbd (länkad entitet) + lokal entitet, Kod: rda```

* Beskrivningsnivå (000/05)  
  Länka till entitet.  
  ```Exempel: CIP-post, ändra till biblioteksnivå```

### Instans
* Utgivningssätt  
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
* Har titel/Titel/Huvudtitel (245 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: Under cover```

* Har titel/Titel/Huvudtitel/Övrig titelinformation (245 ‡b)  
  Skriv in uppgiften.  
  ```Exempel: livet som underrättelseagent åt MI5```

* Upphovsuppgift  
  Skriv in uppgiften.  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```

* Identifikator/Typ  
  Välj från lista.    
  ```Exempel: ISBN```

* Identifikator/Typ/Värde (020 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```

* Identifikator/Bestämning (020 ‡q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```

* Upplageuppgift  
  Skriv in uppgiften.  
  ```Exempel: Första upplagan```

* Utgivning   
  * Plats/Benämning (264 -/1 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: [Göteborg]```  
  * Agent/Benämning (264 -/1 ‡b)  
  Skriv in uppgiften.  
  ```Exempel: NoNa```  
  * Datum (264 -/1 ‡c)  
  Skriv in uppgiften.  
  ```Exempel: 2017```  

* Typ av utgivningsdatum/utgivningsstatus (008/06)  OBS. FINNS DET MED?  
  Länka till entitet.  
  ```Exempel: s (= ett årtal)```

* Tillverkning   
  * Plats/Benämning (264 -/3 ‡a)  
  ```Exempel: Falun```  
  * Agent/Benämning (264 -/3 ‡b)  
  Skriv in uppgiften.   
  ```Exempel: Scandbook```

* Kronologisk täckning (008/11-17)  OBS. FINNS DET MED?  
  Skriv in uppgiften.  
  ```Exempel: 2017____```

* Utgivningsland (008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```  
  
* Serieuppgift  
  Skriv in uppgiften.  
  ```Exempel: Acta Academiae Regiae Gustavi Adolphi, 0065-0897 ; 119```  

* Har serie  ELLER SERIEMEDLEMSKAP ???????
  Länka till entitet. 
  I undantagsfall, skapa lokal entitet. Skriv in uppgiften. Skriv in uppgiften.  
  ```Exempel: ?????????????????????????? KOLLA - VAR HAMNAR SERIENS TITEL? HUR FÖRHÅLLER DET SIG TILL SERIEUPPGIFT? ISSN? NUMRERING INOM SERIE? LÄNKA TILL ENTITET?```  
  
* Medietyp (337 ‡b)  
  Länka till entitet.  
  ```Exempel:  n (= omedierad)```

* Bärartyp (338 ‡b)  
  Länka till entitet.  
```Exempel:  nc (= volym)```

* Form för katalogiserat objekt (008/23)  OBS. FINNS DET MED?  
  Länka till entitet.  
  ```Exempel: - (= ingen av följande)```

* Omfång/Benämning  
  Skriv in uppgiften.  
  ```Exempel: 319 sidor```

* Mått/Benämning  
  Skriv in uppgiften.  
  ```Exempel: 24 cm```

### Verk
* Instans av Verk/Text

* Har titel/Titel/Huvudtitel (240 1-/0 ‡a)  
  Skriv in uppgiften.  
  ```Exempel:  Soldier spy```

* Medverkan och funktion/Primär medverkan/Agent/Person (100 1/- ‡a)  
  Länka till entitet.
  I undantagsfall, skapa lokal entitet och skriv in uppgiften. 
* Medverkan och funktion/Primär medverkan/Agent/Person/Familjenamn  
  ```Exempel: Marcus```

* Medverkan och funktion/Primär medverkan/Agent/Person/Förnamn  
  ```Exempel: Tom```

* Medverkan och funktion/Medverkan/Agent/Funktion (100 ‡4)  
  Länka till entitet.  
  ```Exempel: relator/author (= författare)```

* Medverkan och funktion/Medverkan/Agent/Person (700 1/- ‡a)  
  Länka till entitet.  
  I undantagsfall, skapa lokal entitet och skriv in uppgiften.  
  ```Exempel: Skoglund, Svante, 1960-```

* Medverkan och funktion/Medverkan/Agent/Funktion (700 ‡4)  
  Länka till entitet.  
  ```Exempel: relator/trl (= översättare)```

* Klassifikation/DDK-klassifikation/Kod (082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```

* Klassifikation/DDK-klassifikation/Kod/Klassifikationsupplaga (082 ‡2)  
  Skriv in uppgiften.  
  ```Exempel: 23/swe```

* Klassifikation/Kod (084 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: Sei-e```

* Klassifikation/Termlista/Termlista/ID (084 ‡2)  
  Skriv in uppgiften. 
 ```Exempel: https://id.kb.se/term/kssb/8```

* Ämne/Agent/Person (600 1/- ‡a)  
  Länka till entitet. 
  I undantagsfall, skapa lokal entitet. Skriv in uppgiften. 

* Ämne/Agent/Person/Familjenamn  
  ```Exempel: Marcus```

* Ämne/Agent/Person/Förnamn  
  ```Exempel: Tom```

* Ämne/Agent/Jurisdiktion/Är del av/Jurisdiktion/Namn (610 1/4 ‡a)  
    Länka till entitet.  
    I undantagsfall, skapa lokal entitet. Skriv in uppgiften.  
    ```Exempel: Storbritannien```

* Ämne/Agent/Jurisdiktion/Namn på underordnad enhet (610 ‡b)  
  ```Exempel: MI5```  
  
* Ämne - sao-term (650 -7- ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Säkerhetspolitik```

* Ämne - sao-term (650 -7- ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Spionage```

* Ämne - sao-term (650 -7- ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Terrorismbekämpning```

* Geografiskt ämnesord (651 -/4 ‡a)  
  Skapa lokal entitet. Skriv in uppgiften.  
  ```Exempel: Storbritannien```

* Genre/form – saogf-termer (655 ‡a, ‡2 saogf)  
  Länka till entitet.  
  ```Exempel: Självbiografier```

* Genre/form – litterär genre (008/33)  
  Länka till entitet.  
  ```Exempel: 0 ( = Ej skönlitterärt verk)```

* Genre/form – biografiskt material (008/34)  
  Länka till entitet.  
  ```Exempel: a (= självbiografi)```

* Språk (008/35-37) (+ även i 041 ‡a, om relationen Översättning av finns)  KOLLA, EV ÄNDRA HÄR
  Länka till entitet.  
  ```Exempel: svenska (swe)```

* Översättning av/Verk/Språk (041 ‡h)  
  Länka till entitet.  
  ```Exempel: engelska (eng)```

* Innehållstyp (336 ‡b)  
  Länka till entitet.  
  ```Exempel: text (txt)```
