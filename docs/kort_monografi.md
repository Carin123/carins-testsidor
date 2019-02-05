---
section: Hjälptexter katalogisering
title: Tryckt monografi
order: 17
date: 2019-02-04
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
  ```Exempel: nc (= volym)```
  
#### Titel
Se Instans/Titel

#### Upphovsuppgift
Se Instans/Upphovsuppgift

#### Upplageuppgift
Se Instans/Upplageuppgift

#### Utgivning
Se Instans/Utgivning

#### Tillverkning
Se Instans/Tillverkning

#### Copyrightår
Se Instans/Copyrightår

#### Identifikator (ISBN)
Se Instans/Identifikator

#### Omfång
Se Instans/Omfång

#### Övriga fysiska detaljer
Se Instans/Övriga fysiska detaljer

#### Seriemedlemskap
Se Instans/Seriemedlemskap  

##### Författarserie
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Har titel/Titel/Huvudtitel  
(seriesMembership/inSeries/Instance/InstanceOf/Work/hasTitle/Title/mainTitle = 800 ‡t)  
  ```Exempel: Millenium```   
* Seriemedlemskap/Ingår i serie/Instans/Instans av Verk/Verk/Medverkan och funktion/Primär medverkan/Agent/Person     (seriesMembership/inSeries/Instance/InstanceOf/Work/contribution/PrimaryContribution/Agent/Person = 800 ‡a)  
Lägg till Medverkan och funktion under Verk (inom Seriemedlemskap) genom att klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk). Välj Medverkan och funktion. Välj Primär medverkan. Lägg till Agent.   
Följ dessa instruktioner:  
  [Relationer till Agent](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
 ```Exempel: Larsson, Stieg, 1954-2004```  
  Vid behov, skapa ny agent, se [Skapa ny agent](https://libris.kb.se/katalogisering/help/workflow-agent-person-new). I undantagsfall, skapa lokal entitet.    
  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 800 ‡v)  
  Skriv in uppgiften.  
  ```Exempel: 1```  
  
### Verk

Se Verk.

#### Instans av verk
* Instans av verk/Text (instanceOf/Work/Text)  
För en tryckt monografi är verkstypen Text.  

#### Verkets titel 
Se Verk/Verkets titel.

#### Medverkan och funktion
Se Verk/Medverkan och funktion.

#### Sprak
Se Verk/Språk.

#### Genre
Se Verk/Genre.

#### Klassifikation
Se Verk/Klassifikation. 

#### Amne
Se Verk/Ämne.

#### Malgrupp
Se Verk/Målgrupp.

#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
```Exempel: text (txt)```

 För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av verk. Skapa Verk som lokal entitet. Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg till Innehållstyp under Verk. Sök fram och länka till entitet.  

GENRER: KODNING: AKADEMISK AVHANDLING, FESTSKRIFT, LITTERÄR GENRE MM  
ANMÄRKNING OM AVHANDLING



  
  
