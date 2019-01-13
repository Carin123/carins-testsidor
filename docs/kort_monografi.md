---
section: Hjälptexter katalogisering
title: Tryckt monografi
order: 17
date: 2019-01-13
tags:
- under arbete
- monografi
--- 

## Tryckt monografi - bok

Beskrivningen av en tryckt monografi innefattar en beskrivning av instansen (kan också kallas utgåvan, upplagan, manifestationen) och en beskrivning av det verk som instansen är en instans av. Till varje beskrivning av instans och verk hör adminmetadata (administrativ data om beskrivningen).  

För mer utförlig information om de egenskaper som anges, se [Adminmetadata](https://libris.kb.se/katalogisering/help/adminmetadata), [Instans](https://libris.kb.se/katalogisering/help/instance) och [Verk](https://libris.kb.se/katalogisering/help/work). Här nedan listas egenskaperna i korthet.  

För instruktioner om att lägga till eller ta bort egenskap, länka till entitet, skapa lokal entitet och om hur formuläret fungerar i övrigt, se Redigering i vänstermenyn. För information om katalogregler, skrivregler och övriga katalogiseringsanvisningar, se [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Arbetsfloden/Tryckta-monografier/ "Anvisningar för katalogisering - RDA").

Se även [instruktionsfilmer](https://www.youtube.com/playlist?list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy) 

### Instans
För att lägga till egenskaper under Instans, klicka på plustecknet i redigeringsvyn (den stora runda plusikonen under Verktygsikonen - Lägg till egenskaper under: Instans). Sök fram egenskapen och välj den genom att klicka på plustecknet vid egenskapens namn.  

#### Utgivningssatt
* Utgivningssätt (issuanceType)   
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Länka till entitet.  
  ```Exempel: n (= omedierad)```
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Länka till entitet.  
  ```Exempel: nc (= volym)``
  
### Titel  

##### Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  

##### Övrig titelinformation (undertitel)
* Har titel/Titel/Övrig titelinformation (= Undertitel) (hasTitle/Title/subtitle = 245 ‡b)  
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

 
  
INSTANS:
UTGIVNINGSSÄTT: MONOGRAFISK RESURS  
ISBN
ISBN - INDIREKT IDENTIFIERAD AV  
FÖRFATTARSERIE  

VERK:
VERKSTYP: TEXT  
GENRER: KODNING: AKADEMISK AVHANDLING, FESTSKRIFT, LITTERÄR GENRE MM  
ANMÄRKNING OM AVHANDLING



  
  
