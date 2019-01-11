---
section: Hjälptexter katalogisering
title: Instans
order: 17
date: 2019-01-11
tags:
- under arbete
- instans
--- 

## Instans

En instans är en instans av ett verk, till exempel en viss utgåva av ett verk. Instans kallas manifestation i RDA. Instansen återspeglar information som utgivningsplats, utgivare och utgivningsår, bärartyp och omfång.  

En instans är av en viss instanstyp. Exempel på instanstyper är: instans, elektronisk, arkiv, handskrift, ljudinspelning. Det går för närvarande inte att byta beskrivningens instanstyp.  
Till verket knyts information som ämne, klassifikation, språk och innehållstyp. Verksbeskrivningen ligger för närvarande lokalt inom varje instansbeskrivning, under Instans av verk. Läs mer om [Verk](https://libris.kb.se/katalogisering/help/work).  

Denna hjälptext beskriver de vanligaste egenskaperna under Instans. För instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

I de flesta fall ska informationen delas upp i olika egenskaper (jfr fält) och underliggande egenskaper (jfr delfält). I några undantagsfall är det nödvändigt att använda ISBD-interpunktion inom en egenskap, för att separera uppgifter. Dessa fall visas genom exempel nedan. I övriga fall, lägg inte in ISBD-interpunktion för att avsluta en egenskap (fält). Använd vid behov klamrar inom egenskap (fält), enligt Anvisningar för katalogisering - RDA.

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy)  

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  

### Innehåll  

| [Instans](#instans) | | |
| ------ | ------ | ------ |
| [Utgivningssätt](#utgivningssatt) | | [Omfång](#omfang) | 
| [Medietyp](#medietyp) | | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) | |
| [Bärartyp](#barartyp) | | [Mått](#matt) | |
| [Titel](#titel) | | [Bilagor](#bilagor) | |
| [Upphovsuppgift](#upphovsuppgift) | | [Seriemedlemskap](#seriemedlemskap) |  |
| [Upplageuppgift](#upplageuppgift) | | [Anmärkning](#anmarkning) | |
| [Utgivning](#utgivning) | | [Innehållsanmärkning](#innehallsanmarkning)  | |
| [Tillverkning](#tillverkning) | | [Målgruppsanmärkning](#malgruppsanmarkning) |
| [Copyrightår](#copyrightar) | | [Annat bärarformat](#annat-bararformat) |
| [Identifikator](#identifikator) | | [Annan relaterad resurs](#annan-relaterad-resurs) |

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Instans). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)   
  Välj från lista.
 <br/>```Exempel:```
  * ```Monografisk resurs```
  * ```Seriell resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.
 <br/>```Exempel:```
  * ```c (= dator)```
  * ```n (= omedierad)```
  * ```s (= audio)```
  * ```v (= video)```
<br>Läs mer om [medietyper](http://www.kb.se/katalogisering/Formathandboken/innehallstyper/medie/).
 
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  <br/>```Exempel:```
  * ```cr (= onlineresurs)```
  * ```nb (= ark)```
  * ```nc (= volym)```
  * ```sd (= ljudskiva) + d (= ljudskiva)```
<br>Läs mer om [bärartyper](http://www.kb.se/katalogisering/Formathandboken/innehallstyper/barar/).
 
#### Titel  

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
  Återge huvudtiteln från titelsidan eller annan föredragen källa så som den förekommer i källan. se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/#huvudtitel "Anvisningar för katalogisering - RDA").  
  Skriv in uppgiften.    
 ```Exempel: En arbetsdag i skriftsamhället```  
För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
```Exempel: ett etnografiskt perspektiv på skriftanvändning i vanliga yrken : småskrift utarbetad av Språkrådet```
  
  För att ange originaltitel, se Verk/Har titel/Titel/Huvudtitel.  

##### Varianttitel   
Används till exempel för felaktigheter. Kan specificeras med Typanmärkning.  
För att lägga till varianttitel, klicka på plustecknet vid Har titel (lägg till titel) och välj typ Varianttitel.  
* Har titel/Varianttitel/Huvudtitel (hasTitle/VariantTitle/mainTitle = 246 ‡a)   
  Skriv in uppgiften under Huvudtitel.    
  ```Exempel: Hierarchy in organizations```   
* Har titel/Varianttitel/Övrig titelinformation (= Undertitel) (hasTitle/VariantTitle/subtitle = 246 ‡b)  
  Skriv in uppgiften under Övrig titelinformation. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.   
* Har titel/Varianttitel/Typanmärkning (hasTitle/VariantTitle/typeNote = 246 1/_ ‡i)  
 Anmärkningstext som i ett sökgränssnitt ska föregå varianttiteln. Används också för att ange typ av varianttitel som inte finns i listan, t ex Titelrubrik. Lägg vid behov till Typanmärkning (plustecknet vid Varianttitel - lägg till egenskaper under: Varianttitel, välj Typanmärkning).  
  Skriv in uppgiften.  
  ```Exempel: Titeln felstavad, korrekt titel:```   
  
##### Omslagstitel, Ryggtitel, Rubriktitel  
* Omslagstitel, Ryggtitel, Rubriktitel etc - lägg till Har titel och välj typ, till exempel Omslagstitel. Ange Huvudtitel, eventuell Övrig titelinformation och Typanmärkning, enligt mönstret för Omslagstitel, se nedan.      

##### Omslagstitel   
* Har titel/Omslagstitel/Huvudtitel (hasTitle/CoverTitle/mainTitle = 246 1/4 ‡a)  
 Skriv in uppgiften under huvudtitel.      
 ```Exempel: Bergens väktare```  
* Har titel/Omslagstitel/Övrig titelinformation (= Undertitel) (hasTitle/CoverTitle/subtitle = 246 1/4 ‡b)  
För att lägga till Övrig titelinformation, klicka på plustecknet vid Omslagstitel (Lägg till egenskaper under: Omslagstitel), välj Övrig titelinformation (= subtitle).  
Återge övrig titelinformation som återfinns i annan källa än huvudtiteln som en varianttitel, till exempel som omslagstitel.    
  Skriv in uppgiften. Om det finns flera undertitlar, skriv in dessa efter varandra i samma fält, åtskilda av mellanslag, kolon, mellanslag.    
```Exempel: Djingis Khan – historiens störste erövrare```

  För att ange att omslagstiteln endast står på skyddsomslag, lägg till Typanmärkning (plustecknet vid Omslagstitel - lägg till egenskaper under: Omslagstitel, välj Typanmärkning).  
  Skriv in uppgiften.
  <br/>```Exempel:```
  * ```Typanmärkning (246 ‡i): Skyddsomslag:```
  * ```Omslagstitel/Huvudtitel (246 ‡a): På väg mot döden```
  * ```Övrig titelinformation (246 ‡b): en Cooper och Fry-deckare```  
    
##### Delbeteckning
* Har titel/Titel/Har del/Titeldel/Delbeteckning (hasTitle/Title/hasPart/TitlePart/partNumber = 245 ‡n)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Har del).  
Under Har del, skapa Titeldel (TitlePart) som lokal entitet (plustecknet vid Har del - Lägg till resurs, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel. Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.)   
Om Har del/Titeldel/Deltitel redan finns, lägg till Delbeteckning under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Delbeteckning (partNumber)).   
Skriv in uppgiften under Delbeteckning.  
```Exempel: 1```   

##### Deltitel  
* Har titel/Titel/Har del/Titeldel/Deltitel (hasTitle/Title/hasPart/TitlePart/partName = 245 ‡p)  
Lägg till Har del (hasPart) under Har titel/Titel (plustecknet vid Titel - Lägg till egenskaper under: Titel, välj Har del).   Under Har del, skapa Titeldel (TitlePart) som lokal entitet (plustecknet vid Har del - Lägg till resurs, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv "titeldel" i rutan Skapa lokal entitet och välj * Titeldel. Titeldel läggs till under Har del. Klicka på Titeldel och det fälls ut.)   
Om Har del/Titeldel/Delbeteckning redan finns, lägg till Deltitel under Titeldel (plustecknet vid Titeldel - Lägg till egenskaper under: Titeldel, välj Deltitel (partName)).   
Skriv in uppgiften under Deltitel.  
```Exempel: Träd och växter som resurs```  
För att ange Delbeteckning och Deltitel i en annan ordning, till exempel en deltitel som har efterföljande delbeteckningar, upprepa Titeldel och ange Delbeteckning och Deltitel som det passar i det aktuella fallet.  

#### Titel - alternativ stavning
* Relation/Relation/Entitet/Verk/Har titel/Titel/Huvudtitel   
(relationship/Relationship/entity/Work/hasTitle/Title/mainTitle = 740)  
Ange alternativa titlar här för att öka sökbarheten för titlar som innehåller exempelvis specialtecken, siffror eller oväntade stavningar av ord.  

  För att lägga till en alternativ sökingång för titeln, klicka på plustecknet Lägg till egenskaper under: Instans och välj Relation. Lägg till Entitet (plustecknet vid Relation - lägg till egenskaper under: Relation). Skapa verk som lokal entitet (plustecknet vid Entitet - lägg till verk). Klicka i rutan Skapa lokal entitet, längst ner i sidorutan till höger, och välj Verk. Lägg till Har titel (plustecknet vid Verk - lägg till egenskaper under: Verk). 
Skriv in uppgiften under Huvudtitel.  
```Exempel: Commentarii fratrum arvalium qui supersunt```  

  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde (plustecknet vid Titel - Lägg till egenskaper under: Titel) och ange en siffra.  
 ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 Se exempel i formathandboken för Libris/Voyager: 
[Fileringsindikator]( http://www.kb.se/katalogisering/Formathandboken/Fileringsindikator/)
  
##### Parallelltitel  
Ange parallelltitel här. Upprepa inte parallelltitel efter Har titel/Titel/Huvudtitel (245 ‡a) med interpunktion.   
* Har titel/Parallelltitel/Huvudtitel (hasTitle/ParallelTitle/mainTitle = 246 1/1 ‡a)   
Välj först Har titel, välj sedan typ Parallelltitel.      
Skriv in uppgiften under Huvudtitel.     
  ```Exempel: The Great Northern War explained```  
* Har titel/Parallelltitel/Övrig titelinformation (hasTitle/ParallelTitle/subTitle = 246 1/1 ‡b)   
Vid behov, klicka även på plustecknet vid Parallelltitel och lägg till Övrig titelinformation (subtitle).  
  ```Exempel: Charles XII and the ideological address```  
  
#### Upphovsuppgift
* Upphovsuppgift (responsibilityStatement = 245 ‡c)  
  För att lägga till upphovsuppgift, klicka på plustecknet Lägg till egenskaper under: Instans.  
  Vid postimport: i vissa importerade poster saknas upphovsuppgift. Lägg då till det.   
  Skriv in uppgiften.  
  ```Exempel: Tom Marcus ; översättning: Svante Skoglund```
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)  
  Skriv in upplagebeteckning här.  
  ```Exempel: Första upplagan```  
  
#### Utgivning  
* Utgivning (publication)  
  Välj typ från lista. För monografier, använd Primär utgivning.  
  I konverterade och maskininlästa poster finns det ibland två avsnitt: ett Primär utgivning med År och Land, och ett Utgivning med Plats, Agent och Datum. När man redigerar maskininlästa poster med två utgivningsavsnitt får man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till avsnittet Primär utgivning och ta bort avsnittet Utgivning.   
NB inväntar en maskinell ändring av dessa poster och ändrar inte manuellt.    
  Vid postimport: I importerade poster förekommer ibland både År och Copyrightår inom Utgivning (= 008/06: t, 008/07-10: År och 008/11-14: Copyrightår). Låt uppgiften ligga kvar oförändrad.      
Om posten är katalogiserad enligt RDA kan även Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c) finnas med.
 
##### Utgivningsplats
* Plats/Plats/Benämning (= Utgivningsort) (place/label = 264 -/1 ‡a)  
  För att lägga till Plats, klicka på plustecknet vid Primär utgivning (lägg till egenskaper under Primär utgivning) och välj Plats. Sök inte efter Plats som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Plats och välj det.   
  Skriv in uppgiften under Benämning.  
  ```Exempel: [Göteborg]```  
  
##### Utgivningsland  
* Land (country = 008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)``` 
  
##### Utgivarnamn
* Agent/Agent/Benämning (= Utgivarnamn) (agent/label = 264 -/1 ‡b)  
  För att lägga till Agent, klicka på Lägg till egenskaper under Primär utgivning och välj Agent. Sök inte efter Agent som entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Agent och välj det.       
  Skriv in uppgiften under Benämning.  
  ```Exempel: NoNa```   
  Om flera utgivare ska anges, lägg till Har del (hasPart) under Primär utgivning. Skapa Utgivning som lokal entitet (plustecknet vid Har del - Lägg till entitet). I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Utgivning och välj *** Utgivning. Upprepa Utgivning som lokal entitet genom att duplicera entiteten Utgivning.  
Ange Plats/Plats/Benämning och Agent/Agent/Benämning och vid behov Datum inom respektive utgivningsavsnitt (angående Datum, se anvisningar nedan). Samtliga utgivare med Plats och Agent ska ligga inom Har del/Utgivning.
Land, År och eventuellt Datum  ska ligga inom Primär utgivning.  
  Se [exempel](https://libris.kb.se/katalogisering/w4rp4hlwtr5lctjr#it).
  
##### År och datum 
  * År (= Utgivningstid) (date = 008/07-10, 264 -/1 ‡c)  
  År får endast innehålla siffror (0-9) och bokstaven u. År ska endast förekomma inom Primär utgivning.  
  Ange utgivningsår, utan klamrar eller andra tecken, endast fyra positioner. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, ange det endast här. Det kommer då att exporteras till både marcpostens 08/07-10 och 264 -/1 ‡c. För att ange årtal med klamrar eller andra tecken utöver fyra positioner, använd Datum.  
  ```Exempel: 2017```  
  * Datum (= Utgivningstid) (date = 264 -/1 ‡c)  
  Datum får innehålla text och interpunktionstecken.  
  För att ange ett utgivningsdatum med fler än fyra positioner, till exempel ett klamrat årtal, skriv in det här. Det kommer att exporteras till marcpostens  264 -/1 ‡c. Skriv in uppgiften.  
  För att ange ett år utan klamrar eller andra tecken, använd endast År.  
  Skriv in uppgiften.
  <br/>```Exempel:```
    * ```[2017]```
    * ```[mellan 1863 och 1866?]```
  
* Flera år (flerbandsverk)  
  Använd Startår och Slutår (inte År). För att lägga till Startår och Slutår, klicka på plustecknet vid Primär utgivning (Lägg till egenskaper under: Primär utgivning) och välj Startår respektive Slutår. Egenskaperna ska ligga i avsnittet Primär utgivning. Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här. De exporteras då både som 008 och 264 ‡c. Bindestreck sätts automatiskt. För att få rätt kod i 008/06 (Typ av utgivningsdatum/Utgivningsstatus) vid MARC-export: lägg till Typ av utgivningsdatum (marc:publicationStatus) (klicka på plustecknet vid Primär utgivning) och välj ”Flera årtal (monografisk resurs)".
 <br/>```Exempel:```
  * ```Startår: 1999```
  * ```Slutår: 2017```
  * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)```
  
 <br/>```Exempel:```
  * ```Startår: 1753```
  * ```Slutår: 1756```
  * ```Datum: [1732?]-1756```
  * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 

 Läs mer om [År och Datum](https://kundo.se/org/librisxl/d/falt-for-utgivningsar/)  
   
#### Tillverkning 
* Tillverkning (manufacture)  

##### Tillverkningsplats (Tillverkningsort) 
* Plats/Plats/Benämning (place/label = 264 -/3 ‡a)  
  ```Exempel: Falun```  
##### Tillverkningsnamn  
* Agent/Agent/Benämning (agent/label = 264 -/3 ‡b)  
  Skriv in uppgiften.   
  ```Exempel: Scandbook```   
##### Tillverkningstid   
* Datum (= Tillverkningstid) (date = 264 -/3 ‡c)  
  Skriv in uppgiften. Klamra vid behov.
  <br/>```Exempel:```
  * ```2017```
  * ```[2017]```
  
#### Copyrightar   
* Copyright/Copyright/Datum (copyright/Copyright/date = 264 -/4 ‡c)  
  Skriv in uppgiften. För att få fram copyrighttecknet, kopiera från exemplet nedan eller skriv Alt + 184.  
  Se också [Specialtecken](https://libris.kb.se/katalogisering/help/search-04-special-chars). Du kan t ex söka på teckenuppsättning i “Sök i windows” och öppna programmet, markera och kopiera tecknet och sedan klistra in det.  
  ```Exempel: ©2017``` 
  
#### Identifikator 
* Identifikator (identifiedBy)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Identifikator/ISBN/Värde (identifiedBy/Isbn/value = 020 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 9789188107213```
* Identifikator/Särskiljande tillägg (= Bestämning) (identifiedBy/qualifier = 020 ‡q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```  

För ogiltiga ISBN, använd Indirekt identifierad av, direkt under Instans. Använd inte Ogiltigt värde under Identifikator/ISBN (identifiedBy/marc:hiddenValue).  
För ISSN, se Tryckt seriell resurs. För andra identifikatorer, se respektive hjälptext.  

#### Indirekt identifierad av  
Ange ogiltiga ISBN här och inte under Identifikator/ISBN/Ogiltigt värde. För ISSN, se Tryckt seriell resurs. För andra identifikatorer, se respektive hjälptext.  

* Indirekt identifierad av/ISBN (indirectlyIdentifiedBy/ISBN = 020 ‡z)  
  Välj typ från lista.  
  ```Exempel: ISBN```
* Indirekt identifierad av/ISBN/Värde (indirectlyIdentifiedBy/Isbn/value = 020 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 97891881072```
* Indirekt identifierad av/Särskiljande tillägg (= Bestämning) (indirectlyIdentifiedBy/qualifier = 020 ‡q)  
  Skriv in uppgiften.  
  ```Exempel: inbunden```  
  
#### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)   
  Skriv in uppgiften under Benämning.  
  <br/>```Exempel:```
  * ```319 sidor```
  * ```2 teckningar på 1 ark```
  * ```1 karta i 4 segment ```
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)     
  Skriv in uppgiften.  
  ```Exempel: illustrationer```  

#### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 ‡c)  
  Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
  * ```24 cm```
  * ```34 x 27 cm och  37 x 27 cm, på ark 40 x 30 cm```
   
#### Bilagor
* Tillsammans med/Instans/Benämning (Bilagor) (accompaniedBy/Instance/label = 300 ‡e)   
För att lägga till Tillsammans med, klicka på plustecknet Lägg till egenskaper under: Instans och välj Tillsammans med. Skapa Instans som lokal entitet. (Plustecknet vid Tillsammans med, välj Skapa lokal entitet, längst ner i sidorutan till höger, skriv Instans och välj ** Instans.) Lägg till Benämning (plustecknet vid Instans - Lägg till egenskaper under: Instans).    
Skriv in uppgiften.  
  ```Exempel: 10 mönsterark```  

#### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  Avvakta med att skapa verk som länkade entiteter. Beskriv serien som lokal entitet, enligt följande instruktion.  
  *Nytt 2018-10-04:*   
  * Man måste inte längre fylla i två Seriemedlemskap för att vid export till MARC få ut både 490 och 830.  
  * Vid export till marc21 skapas både 490 och 830 (800/810) från Seriemedlemskap som saknar Serieuppgift (t ex gamla 440-fält). OBS. Hanteringen klarar de flesta fall bra, men det finns serier med deltitlar/delserier som kommer att exporteras fel (fel ordning mellan Delbeteckning och Deltitel, fel interpunktion). Om man stöter på sådana, och anser felet besvärande, får man gå in i posten och lägga till en korrekt Serieuppgift i rätt Seriemedlemskap. Då kommer 490 att skapas från det. (Finns det flera Seriemedlemskap behöver man komplettera alla, annars skapas bara 490 för den serien som har en ifylld Serieuppgift).  
  
Läs mer om [Seriemedlemskap](https://kundo.se/org/librisxl/d/uppgifter-om-seriemedlemskap-saknas-i-marc-export/)  
     
##### Seriens titel (auktoriserad sökingång för serie)  
* Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (seriesMembership/inSeries/InstanceofWork/Work/hasTitle/Title/mainTitle = 830 ‡a)  
  Ange den auktoriserade sökingången för serien här (gäller serier som har seriehuvudpost) i de fall den avviker från serieuppgiften. Om endast Serieuppgift men inte Ingår i serie/Instans av Verk/Verk finns, t ex i en förhandspost från Bokinfo, fungerar det för närvarande bäst att skapa ett helt nytt seriemedlemskap och flytta över Serieuppgift dit. Ange sedan den auktoriserade sökingången för serien under Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel. Ta bort det första seriemedlemskapet så att endast ett seriemedlemskap återstår.  
  Skriv in uppgiften.   
  ```Exempel: Årstasällskapets för Fredrika Bremer-studier skriftserie```  
##### ISSN  
* Seriemedlemskap/Ingår i serie/Instans/Identifikator/ISSN/Värde (seriesMembership/inSeries/Instance/identifiedBy/ISSN/Value) (490 ‡x, 830 ‡x) 
  Ange seriens ISSN. För äldre serier som saknar ISSN, men har ett LibrisIII-nummer ("99-nummer"), ange detta nummer här.  
  Skriv in uppgiften.  
  ```Exempel: 1103-498X```     
##### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 ‡a)  
  Skriv in uppgiften.  
   ```Exempel: Årstasällskapets skriftserie```   
##### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 ‡v, 830 ‡v)  
  Skriv in uppgiften.  
  ```Exempel: 8```  
##### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)  
  Ange indikator 0 om endast serieuppgift samt eventuellt ISSN och eventuell numrering inom serie ska anges (om det inte finns en seriehuvudpost).   
  Skriv in uppgiften.  
  ```Exempel: 0```   
  Ange indikator 1 om dessutom Instans/Instans av Verk/Verk (830) anges (om det finns en seriehuvudpost).   
  ```Exempel: 1```   
 
*Seriemedlemskap, vid postimport:* Om fält 490 ‡a och 830 ‡a matchar, läggs de vid import i samma Seriemedlemskap. Om de inte matchar, skapas två Seriemedlemskap: ett med Seriemedlemskap/Serieuppgift och ett med Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
När man redigerar importerade poster med två Seriemedlemskap får man, om man bedömer det nödvändigt, slå ihop dem till ett genom att lägga till Serieuppgift och Indikator för seriebiuppslag i det Seriemedlemskap som innehåller Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel.  
Om man försöker göra tvärt om och lägga till Instans av Verk i ett Seriemedlemskap så orsakar en bugg att detta kopplas till Instans av Verk/Text (överst i beskrivningen) och det går sedan inte att ändra. I dessa fall måste Seriemedlemskapet tas bort i sin helhet och ett nytt läggas till och fyllas i.  
OBS! Om ISSN finns i både 490 och 830 och om volymbeteckningen är angiven på olika sätt i 490 och 830, dubbleras dessa inom Seriemedlemskapet. Radera en av de dubblerade ISSN- och/eller voIymbeteckningarna.  

#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)  
  Skriv in allmänna anmärkningar här.  
  För att lägga till Anmärkning, klicka på plustecknet i redigeringsvyn (den stora runda ikonen under Verktygsikonen - Lägg till egenskaper under: Instans) och välj Anmärkning (hasNote). Tryck Enter för att lägga till Anmärkning.  
  Skriv in uppgiften under Benämning.  
   
#### Innehallsanmarkning  
* Har innehållsförteckning/Innehållsförteckning/Benämning (tableofContents = 505 8/_)  
  För en enkel innehållsanmärkning (505 ‡a), lägg till Har innehållsförteckning (från Lägg till egenskaper under: Instans). Lägg därefter till Innehållsförteckning (plustecknet under Har innehållsförteckning i vänstermenyn). Skriv in uppgiften under Benämning.     
  ```Exempel: Culture at home -- Culture and the global -- Global youth -- Global music -- Territories of global globalization.```  
  
* Har innehållsförteckning/Innehållsförteckning/Har del/Utökad innehållsanmärkning/Benämning/Upphovsuppgift (tableofContents = 505 8/0 ‡t, ‡r)  
För en utökad innehållsanmärkning med titlar och upphovsuppgifter, lägg till Har innehållsförteckning (från Lägg till egenskaper under: Instans). Klicka på plustecknet under Har innehållsförteckning i vänstermenyn (Lägg till innehållsförteckning). Ta bort Benämning. Lägg till Har del (plustecknet vid Innehållsförteckning - Lägg till egenskaper under: Innehållsförteckning). Skriv Har del i sökrutan och välj det. Klicka på plustecknet vid Har del (Lägg till resurs) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv Utökad innehållsanmärkning i rutan för Skapa lokal entitet och välj * Utökad innehållsanmärkning. Utökad innehållsanmärkning läggs till under Har del. Klicka på Utökad innehållsanmärkning och det fälls ut. Lägg in titel under Benämning. Lägg in upphovsuppgift under Upphovsuppgift. Vid behov, lägg in Kommentar (med valfri information).  
Upprepa, för ytterligare titel (Benämning) + upphovsuppgift, genom att lägga till ytterligare en Utökad innehållsanmärkning som lokal entitet (klicka på Duplicera entitet).  
 FLER EXEMPEL
  
#### Malgruppsanmarkning  
* Målgrupp/Målgrupp/Benämning (intendedAudience/IntendedAudience/label = 521 ‡a)  
För att lägga till målgruppsanmärkning, klicka på plustecknet Lägg till egenskaper under: Instans och välj Målgrupp.  
Skapa Målgrupp som lokal entitet (plustecknet vid Målgrupp - Lägg till målgrupp. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Målgrupp och välj det). Skriv in uppgiften under Benämning.  
  ```Exempel: För årskurs 1```  
Observera att kodning av målgrupp, motsvarande 008/22, ska registreras under Instans av Verk/Genre.  
 
#### Annat bararformat
* Annat bärarformat (otherPhysicalFormat = 776)  
  För att länka till en utgåva i annat format, till exempel en elektronisk utgåva, lägg till Annat bärarformat (Lägg till egenskaper, välj Annat bärarformat). Sök upp och länka till instansen. Klicka på plustecknet vid Annat bärarformat (Lägg till instans). I sidorutan under Lägg till entitet/Instans, skriv in id eller annat sökbegrepp. Välj instansen genom att klicka på plustecknet vid instansen eller på instansens titel. Om instansen som länken går till har identifikator (ISBN), skapas i marcexporten 776 #t (Titel) och #z (Identifikator). I webbsök ger detta en länk i högermenyn under rubriken Sök vidare/Andra versioner.   
* Annat bärarformat/Typanmärkning (776 ‡i)  
  Typanmärkning i samband med Annat bärarformat kan för närvarande inte läggas till.  
* Annat bärarformat/Beskriven av/Post/Kontrollnummer (776 ‡w)  
  Beskriven av/Post/Kontrollnummer, motsvarande delfält w, är för närvarande låst för redigering. Det går därmed inte att lägga till egenskapen eller redigera den i befintliga beskrivningar.  
  
#### Annan relaterad resurs
* Annan relaterad resurs/Elektronisk/URI (marc:versionOfResource/Electronic/URI = 856 4/1 ‡u)   
  För att länka till en resurs av resursen i annat format än instansbeskrivningens instanstyp, till exempel en länk till en elektronisk version av en tryckt resurs, lägg till Annan relaterad resurs. Om instansbeskrivningen gäller en elektronisk resurs (instanstyp: elektronisk), gör i första hand istället en beskrivning av den digitala resursen. Se instruktioner i hjälptexten för Digital resurs.   
Klicka på plustecknet vid Annan relaterad resurs och välj Lägg till elektronisk. Välj Skapa lokal entitet. Lägg till egenskapen URI. Klistra in aktuell URI. 
 * Annan relaterad resurs/Elektronisk/Offentlig anmärkning (marc:versionOfResource/Electronic/marc:publicNote = 856 4/1 ‡z)   
  Vid behov, lägg till egenskapen Offentlig anmärkning. Skriv in anmärkningen.  
 
  
