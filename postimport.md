---
section: Redigering
title: Checklista Andra källor
date: 2019-04-24
tags:
- redigering
- postimport
order: 16
---


## Checklista vid postimport

Beroende på vilka katalogiseringsregler som har använts i den post man önskar importera bör olika anvisningar följas:  

*	För poster gjorda enligt AACR2, följ riktlinjerna för [Minimikrav på importerade bibliografiska poster](http://www.kb.se/katalogisering/Katalogisering/Minimikrav-pa-importerade-bibliografiska-poster/) i Katalogisatörens verktygslåda.   
* För poster gjorda enligt RDA, följ riktlinjerna för [Importerade poster](http://www.kb.se/rdakatalogisering/Postimport/) i Anvisningar för katalogisering (RDA)  
*	För preliminära poster, följ riktlinjerna för [Minimikrav vid uppgradering av förhandsposter och Förhandsposter från Bokinfo](http://www.kb.se/katalogisering/Katalogisering/Preliminara-poster/Uppgradering-Bokrondellen/) i Katalogisatörens verktygslåda. 

Eftersom anvisningarna inte är anpassade till det nya katalogiseringsverktyget eller det nya formatet följer här en lista på de viktigaste sakerna att tänka på.  

OBS! Innan den importerade posten sparas i Libris syns de länkade entiteterna med den engelska benämningen. De får automatiskt den svenska benämningen efter att posten sparats. 

### Adminmetadata

Läs mer om egenskaperna under [Adminmetadata](https://libris.kb.se/katalogisering/help/workflow-adminmetadata).

#### Beskrivningsnivå (000/17)
Vid postimport händer det att egenskapen saknar värde eller saknas helt.  
Om egenskapen finns men saknar värde:  
-	Välj värde från listan   

Om egenskapen saknas:  
-	Klicka på plustecknet Lägg till egenskaper under: Post  
-	Välj typ Beskrivningsnivå och välj värde från lista   

#### Skapad av/Organisation/Namn (040 #a)  
Förval: den sigel som skapat posten. Ska inte ändras.  
Vid postimport hamnar för närvarande det importerande bibliotekets sigel här. Detta kommer att ses över.  

#### Uppgraderad eller importerad av/Bibliotek/Sigel (040 #d)
Lägg alltid till uppgiften om ditt bibliotek är det första som importerar posten till Libris. Lägg även till sigel om ett annat bibliotek har importerat posten men du uppgraderar beskrivningsnivån.  

OBS! Egenskapen kan inte läggas till via funktionen Berika från mall.  

För att lägga till egenskapen: 
-	Klicka på plustecknet Lägg till egenskaper under: Post  
-	Lägg till entitet och välj Skapa lokal entitet.  
-	Välj Bibliotek och skriv in uppgiften under Sigel.  

#### Katalogiseringsregler (040 #e)
Vid postimport behöver katalogiseringsreglerna inte ändras till RDA men väljer man att göra det måste hela beskrivningen anpassas till RDA.  
OBS! Om egenskapen Katalogiseringsregler saknas och läggs till via funktionen Berika från mall, blir katalogiseringsreglerna automatiskt RDA.  
OBS! Läggs Katalogiseringsregler/RDA till för hand måste även egenskapen ”ISBD-interpunktion finns” läggas till.  

### Katalogiseringsspråk (040 #b)  
Anges vid katalogisering enligt RDA. Låt uppgiften stå.  
OBS! Om egenskapen läggs till med funktionen Berika från mall blir katalogiseringsspråket automatiskt angivet som svenska. Radera eller ändra vid behov.   

#### Katalogiserande instans (008/39)
Ändra inte postens ursprungliga kod.
Saknas egenskapen:
-	Klicka på plustecknet Lägg till egenskaper under: Post
-	Välj Katalogiserande instans
-	Lägg till entitet, sök fram och välj Annan verksamhet

#### Systemteknisk anmärkning (599 #a)
Låt anmärkningen ”Imported from” ligga kvar.  
OBS! Vid uppgradering av förhandsposter och preliminära poster (då Beskrivningsnivån uppgraderas), ta bort anmärkningen om att posten är maskinellt skapad.  

#### Entry map (000/20-23)
I vissa importerade poster förekommer Entry map. Radera uppgiften.    

#### Identifikator/Lokal identifikator/Värde (035 #a)
Systemnummer från andra bibliotek, bibliotekskonsortier eller system (till exempel Bokinfos systemnummer) kan förekomma. Låt uppgiften stå.  

#### marcuncompleted och marcfailedfixedfields
Data som inte hanteras av systemet visas som `_marcuncompleted` eller `_marcfailedfixedfields` i MARC21-format. Kontrollera om de innehåller information som bör vara med i beskrivningen och radera sedan uppgifterna.  


## Instans

Läs mer om egenskaperna under [Instans](https://libris.kb.se/katalogisering/help/workflow-instance).  

### Titel
Kontrollera att beskrivningen är korrekt.  
OBS! Korrekt egenskap för undertitel (245 #b) är hasTitle/Title/subtitle men i importerade poster ligger den ibland i stället i hasTitle/Title/titleRemainder.  
För att kontrollera om det är korrekt, ställ markören på Övrig titelinformation och om titleRemainder blir synligt istället för subtitle, ändra uppgiften:  
-	Klicka på Lägg till egenskaper under: Titel
-	Välj Övrig titelinformation/subtitle och skriv in undertiteln
-	Radera Övrig titelinformation/titleRemainder  

### Upphovsuppgift
Vid postimport saknas ibland upphovsuppgiften. Om egenskapen saknas:
-	Klicka på Lägg till egenskaper under: Instans
-	Välj Upphovsuppgift och fyll i uppgiften

### Utgivning
Vid postimport medföljer ibland två avsnitt: Primär utgivning med År och Land, och Utgivning med Plats, Agent och Datum.
Vid redigering kan man, om man bedömer det nödvändigt, flytta uppgifterna om Plats, Agent och Datum till Primär utgivning och ta bort Utgivning.   

Vid postimport förekommer ibland både År och Copyrightår inom Utgivning (008/06: t, 008/07-10: År och 008/11-14: Copyrightår).    Låt uppgiften ligga kvar oförändrad. Ej att förväxla med egenskapen Copyright/Copyright/Datum (264 -/4 #c).   

OBS! Om egenskapen Utgivning/Primär utgivning saknas och läggs till via funktionen Berika från mall, länkas utgivningslandet automatiskt till Sverige. Ändra vid behov.  

### Omfång, mått m.m.
Kontrollera att beskrivningen är korrekt.  

### Egenskaper som länkar till andra databaser och instanser som inte finns i Libris  
Låt uppgiften stå:  
-	Tillhörande media/Mediaobjekt (856 4/0)  
-	Annan relaterad resurs/Elektronisk (856 4/1)  
-	Relaterad beskrivning eller innehåll/Dokument (856 4/2)  

Radera uppgiften:  
-	Beskriven av/Post/Kontrollnummer (#w) som innehåller id:n för annan bibliografisk post i den databas man importerat från. Kan förekomma t.ex. i Annat bärarformat (776), i Seriemedlemskap (830). OBS! Kan även förekomma inom egenskaper i Instans av verk.  

### Identifikator/ISBN (020 #a) och Indirekt identifierad av/ISBN (020 #z)  
**OBS! Måste ses över! Anvisningarna nedan är upprättade med tanke på matchningsproblematik vid automatiska flöden. Behov av att kunna lägga felaktiga ISBN i Indirekt identifierad av finns.**

Vid import från Andra källor kan posterna ibland innehålla flera olika ISBN, både för tryckt och elektronisk utgåva. För att inte skapa problem i Libris importflöden är det viktigt att tänka på följande:  
-	Endast ISBN för den beskrivna utgåvan ska ligga i Identifikator/ISBN/Värde (020 #a). Låt endast värden för två utgåvor ligga kvar om det ena syftar på inbunden och det andra på häftad utgåva.  
-	För en tryckt bok får det inte finnas ISBN för en annan tryckt version i Indirekt identifierad av/ISBN/Värde (020 #z), utan enbart i Identifierad av/ISBN/Värde (020 #a). Flytta ISBN för tryckta versioner till Identifierad av och låt ISBN för elektroniska versioner ligga kvar under Indirekt identifierad av.  
-	För elektroniska resurser gäller samma sak, fast tvärtom: Det får inte ligga ISBN för en annan elektronisk version under Indirekt identifierad av, utan där får endast ISBN för olika tryckta versioner ligga.  
-	Om det är svårt att belägga de ISBN som ligger i en katalogpost är det bättre att radera dem. Låt endast de som hör till resursen som ska katalogiseras vara kvar.  
-	Ibland ligger samma ISBN, tiosiffrigt och/eller trettonsiffrigt, i både Identifikator/ISBN/Värde (020 a) och Indirekt identifierad av/ISBN/Värde (020 #z). Ta bort ISBN från Indirekt identifierad av och låt det ligga kvar under Identifikator/ISBN/Värde.  
-	Om det ligger ISBN till andra utgåvor i Indirekt identifierad av/ISBN/Värde (020 #z), kan det särskiljande tillägget (020 #q) ibland hamna fel, under Identifikator/Nothing/Särskiljande tillägg. Flytta det särskiljande tillägget till Indirekt identifierad av, så att det hamnar i anslutning till det ISBN det gäller.   

### Seriemedlemskap/Seriemedlemskap/Ingår i serie (490 #a och 830 #a)  
Om motsvarande fält 490 #a och 830 #a matchar, läggs de vid import i samma Seriemedlemskap.  

Om de inte matchar, skapas två Seriemedlemskap: ett med enbart Seriemedlemskap/Serieuppgift (490 #a) och ett med enbart Seriemedlemskap/Ingår i serie/Instans av Verk/Verk/Har titel/Titel/Huvudtitel (830 #a).  

När man redigerar importerade poster med två Seriemedlemskap kan man, om man bedömer det nödvändigt, slå ihop dem till ett.  

OBS! Om ISSN finns i både 490 och 830 och om volymbeteckningen är angiven på olika sätt i 490 och 830, dubbleras dessa inom Seriemedlemskapet. Radera en av de dubblerade ISSN- och/eller voIymbeteckningarna.  

## Instans av verk 

Läs mer om egenskaperna under [Verk](https://libris.kb.se/katalogisering/help/workflow-work). 

### Språk, litterär genre m.m.
Kontrollera att beskrivningen är korrekt.  

OBS! Om egenskapen Språk saknas och läggs till via funktionen Berika från mall, länkas den automatiskt till svenska. Ändra vid behov.  

### Agenter  
Validera namnformer (skapa auktoriteter vid behov, enligt [Riktlinjer för löpande auktoritetsarbete i Libris](http://www.kb.se/dokument/Riktlinjer%20f%C3%B6r%20det%20l%C3%B6pande%20auktoritetsarbetet%20i%20Libris.pdf)).

#### Funktionskoder (#4)  
Lägg till funktionskoder (#4) för medverkande agenter om de inte finns eller om endast funktionstermer (#e) finns.   Funktionstermerna kan ligga kvar oförändrade.  

### Uniforma titlar 
Kontrollera att titelformen för eventuella uniforma titlar stämmer med svensk praxis.  

### Svenska ämnesord och Genre/formtermer  
Lägg till Svenska ämnesord enligt [Riktlinjer för indexering med Svenska ämnesord](http://www.kb.se/dokument/Verktygsladan/Svenska%20%C3%A4mnesord/Riktlinjer/Riktlinjer%20SAO%202019-03-15.pdf) samt hjälptext för [Ämnesord i Libris](https://libris.kb.se/katalogisering/help/workflow-general-sh).  
Lägg till Genre/formtermer enligt anvisningar i hjälptexten för [Verk](https://libris.kb.se/katalogisering/help/workflow-work).

### Klassifikation
   
Läs mer om Klassifikation i hjälptexten för [Verk](https://libris.kb.se/katalogisering/help/workflow-work).

#### DDK-klassifikation
Lägg till klassifikationskod från DDK eller kontrollera att den befintliga koden är korrekt. Efter kontroll ändra Parallell upplagebeteckning/Upplagespecifik upphovsuppgift till ”23/swe”.  

OBS! Egenskapen Parallell upplagebeteckning går inte att lägga till manuellt. Om den saknas måste en ny DDK-kod läggas till:   
-	Klicka på Lägg till entitet (plustecknet vid Klassifikation)   
-	Välj Skapa lokal entitet och välj DDK-klassifikation.  
-	Fyll i uppgifterna och radera den ofullständiga DDK-klassifikationen.



