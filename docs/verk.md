Denna hjälptext beskriver ett antal vanligt förekommande egenskaper, med utgångspunkt från exempel. För instruktioner om att länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion i inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  

### Innehåll  

| [Verk](#verk) |  |  | 
| ----------- |  ----------- |  ----------- |
| [Verkets titel](#verkets-titel) |  | [Ämne](#amne) | 
| [Medverkan och funktion](#medverkan-och-funktion) |  | [Målgrupp](#malgrupp) | 
| [Språk](#sprak) |  | [Innehållstyp](#innehallstyp) | 
| [Genre](#genre) |  | [Sammanfattning av innehåll](#sammanfattning-av-innehall) | 
| [Klassifikation](#klassifikation) |  | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) | 

### Verk   
 OM VERKSTYPER  
 TA BORT TEXT  
 EXEMPEL PÅ VERKSTYPER   
#### Instans av Verk/Text  
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

För att lägga till egenskaper under Instans av Verk/Text, klicka på plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text. Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
För översättningar och för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk, ska den föredragna titeln för verket anges.    

##### Verkets titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med primär medverkan anger du här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 
##### Verkets titel - huvuduppslag
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan primär medverkande anger du här.  
Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel.    
Skriv in uppgiften under Huvudtitel.  
```Exempel: Bibeln```
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
Skriv in uppgiften.  
```Exempel: Nya testamentet```
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket, motsvarande fält 730 0/2 (analytisk sökingång) i marc:  
Under Instans av Verk/Text, klicka på plustecknet vid Verk (lägg till egenskaper under: Verk) och välj Har del. Följ sedan stegen ovan, från ”Skapa verk som lokal entitet”.  

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 730 0/_ (icke-analytisk sökingång) i marc:   
Under Instans av Verk/Text, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till egenskaper under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Följ sedan stegen ovan, från ”Välj Skapa lokal entitet”.  

#### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  LÄNKA TILL CARINAS TEXT   
  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.
<br/>```Exempel:```
 * ```Lindgren, Astrid, 1907-2002```
 * ```Jöran Persson, ca 1530-1568```
  
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/author (= Författare)```
  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Skoglund, Svante, 1960-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: relator/trl (= översättare)```  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  För att ange att texten är på flera språk, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.   
 EVENTUELLT FLER EXEMPEL PÅ SPRÅK  
  
##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet längst ner i sidorutan till höger och lägg till Benämning (klicka på Lägg till egenskaper under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Text och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Texten delvis översatt  ARBETA OM DENNA TEXT    MER OM PARALLELLTEXT  
(041 0/- #a + 041 1/- #a #h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- #a)   
* Har del/Verk/Språk (hasPart/Work/language = 041 ‡a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Originalversion/Verk/Språk (originalVersion/Work/language = 041 ‡h)  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk/Text (se Språk ovan). Sök fram och länka till entiteten för det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk - Lägg till egenskap under: Text och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg sedan till Har del under Instans av Verk/Text. Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till resurs. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Verk och välj ++++ Verk.) Klicka på plustecknet vid den lokala entiteten Verk (Lägg till egenskaper under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till. Under den lokala entiteten Verk, lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del, lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  
 
##### Sammanfattningsspråk  
Se Sammanfattning av innehåll   
  
##### Språkanmärkning     
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Parallelltext på svenska och engelska```  
  Anmärkningen är under arbete och fungerar tyvärr ännu inte.  
  
#### Genre  
 Länka till entitet. 
För att söka efter entiteter inom Genre/form, klicka på plustecknet vid Genre/form (lägg till entitet). I Lägg till entitet (längst upp i sidorutan till höger), välj typ i listan över typer. Skriv in sökbegrepp. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj entitet genom att klicka på plustecknet vid entiteten (Lägg till). Vid behov, välj ytterligare entiteter i listan. Om sidorutan är stängd, klicka på plustecknet vid Genre/form (lägg till entitet) för att söka fram och välja fler entiteter.  

##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
 Välj Genre/form i listan över typer. Avgränsa till saogf-termer genom att skriva "saogf" efter söktermen. Länka till entitet.  
 Träfflistan vid sökning på entiteter är för närvarande inte sorterad. Var därför uppmärksam på att det finns liknande genre/form-termer med olika listkoder, till exempel sao, barngf, gmgpc/swe. Välj kod från rätt lista. Mer [information om listkoder](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/).  
 ```Exempel: Självbiografier```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  
  
GENERELLT OM OM GENRE - OLIKA TYPER  

#### Klassifikation  
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga (classification/ClassificationDdc/edition = 082 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
  ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 083 ‡2)  
  ```Exempel: 23/swe``` 
   
##### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text). Välj Klassifikation. Klicka på plustecknet vid Klassifikation (Lägg till klassifikation).  Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.   
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 ‡a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Termlista/Termlista/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 ‡2)  
 ```Exempel: kssb```  
* Klassifikation/Termlista/Termlista/Version (classification/Classification/inScheme/ConceptScheme/version = 084 ‡2)  
 ```Exempel: 8``` 
 
#### Amne  
* Ämne  
  Läs mer:  
  [Länka ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Sammansatt, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Kontrollerat, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Okontrollerat ämnesord](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)


GENERELLT OM ÄMNESORD + RUBRIKERNA, HÄNVISA TILL EVA-KARINS TEXT  
##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Säkerhetspolitik```

##### Allmänt ämnesord med underindelning   
Länka i första hand till färdiga sammansatta termer som entiteter. I övriga fall, skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```   
* Ämne/Sammansatt term/Termkomponenter/Allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 -/7 ‡a)      
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)      
  ```Exempel: Varumärken```    
* Ämne/Sammansatt term/Termkomponenter/Underindelning för allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 ‡x)   
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Underindelning för allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)  
  ```Exempel: juridik och lagstiftning```   
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Sök fram och länka till entitet.  
  ```Exempel: Sverige```
  
##### Geografiskt ämnesord med geografisk underindelning  
Skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```  
* Ämne/Sammansatt term/Termkomponenter/Geografiskt ämnesord/Föredragen benämning  
 (subject/ComplexSubject/termComponentList/Geographic/prefLabel)  
 Under Termkomponenter, skapa Geografiskt ämnesord som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I  rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Geografiskt ämnesord och välj det). Skriv in det geografiska ämnesordet under Föredragen benämning.    
  ```Exempel: Tyskland```  
* Ämne/Sammansatt term/Termkomponenter/Underindelning för geografisk term/Föredragen benämning   
 (subject/ComplexSubject/termComponentList/GeographicSubdivision/prefLabel)  
  Under Termkomponenter, skapa Underindelning för geografisk term som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Underindelning för geografisk term och välj det). Skriv in termen för den geografiska underindelningen under Föredragen benämning.  
  ```Exempel: Bonn``` 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
Länka till entitet. Om du inte får träff vid sökning på entiteter, pröva att söka på första ledet i ett sammansatt ord, t ex "1800" istället för "1800-talet".   
 ```Exempel: 1800-talet```  
  
##### Ämnesord Person  HÄNVISA TILL CARINAS TEXT    
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan till höger).  
```Exempel: Lindgren, Astrid, 1907-2002```  
Läs [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)  
 
##### Ämnesord Organisation  HÄNVISA TILL CARINAS TEXT   
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan till höger).    
```Exempel: Svenska Röda korset```  
Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)       
 
#### Malgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
  ```Exempel: text (txt)```  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av Verk, från plustecknet vid Text (Lägg till egenskaper under: Text). Skapa därefter Verk som lokal entitet genom att klicka på plustecknet vid Har del (Lägg till resurs). Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg därefter till Innehållstyp från plustecknet vid Verk (Lägg till egenskaper under: Verk). Sök fram och länka till entitet.  
  EXEMPEL PÅ OLIKA INNEHÅLLSTYPER HÄNVISAT TILL FORMATHANDBOKEN  
  
#### Sammanfattning av innehall    
 * Sammanfattning av innehåll/Sammanfattning/Benämning (summary/Summary/label = 520 ‡a)  
För att lägga till Sammanfattning av innehåll, klicka på plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text. Välj Sammanfattning av innehåll. Tryck Enter för att lägga till Samanfattning. Tryck Enter för att söka fram och lägga till Benämning (Lägg till egenskaper under: Sammanfattning).  
 Skriv in uppgiften under Benämning.  
  ```Exempel: Åtskilliga utdrag af framledne … Axel v. Fersens bref till f.d. konungen av Swerige, Gustaf Adolph, 1806```  
  
 * Typ av innehållsbeskrivning/sammanfattning (marc:summaryType = 520 ind1)  
 Sök fram och lägg till Typ av innehållsbeskrivning/sammanfattning (plustecknet vid Sammanfattning - lägg till egenskaper under: Sammanfattning). Välj typ från lista.  
 ```Exempel: Ej preciserad``` 
 
##### Sammanfattningsspråk  
* Sammanfattning av innehåll/Sammanfattning/Språk (summary/Summary/language = 041 ‡b)  
För att lägga till sammanfattningsspråk, klicka på plustecknet vid Instans av Verk/Text (lägg till egenskaper under: Text) och välj Sammanfattning av innehåll. Lägg till Sammanfattning (tryck Enter eller klicka på plustecknet vid Sammanfattning av innehåll - Lägg till Sammanfattning). Ta bort Benämning. Lägg till Språk genom att klicka på plustecknet vid Sammanfattning (Lägg till egenskaper under: Sammanfattning) och välj Språk. Sök fram och länka till entiteten för sammanfattningens språk.  
  ```Exempel: Engelska```