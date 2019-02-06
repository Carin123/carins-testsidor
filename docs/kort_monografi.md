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
Se [Instans/Titel](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Upphovsuppgift
Se [Instans/Upphovsuppgift](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Upplageuppgift
Se [Instans/Upplageuppgift](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Utgivning
Se [Instans/Utgivning](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Tillverkning
Se [Instans/Tillverkning](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Copyrightår
Se [Instans/Copyrightår](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Identifikator (ISBN)
Se [Instans/Identifikator](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Omfång
Se [Instans/Omfång](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Övriga fysiska detaljer
Se [Instans/Övriga fysiska detaljer](https://libris.kb.se/katalogisering/help/workflow-instance)

#### Seriemedlemskap
Se [Instans/Seriemedlemskap](https://libris.kb.se/katalogisering/help/workflow-instance)

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
Se [Verk/Titel](https://libris.kb.se/katalogisering/help/workflow-work).

#### Medverkan och funktion
Se [Verk/Medverkan och funktion](https://libris.kb.se/katalogisering/help/workflow-work).

#### Sprak
Se [Verk/Språk](https://libris.kb.se/katalogisering/help/workflow-work).

#### Genre
Se [Verk/Genre/form](https://libris.kb.se/katalogisering/help/workflow-work).

##### Exempel på användning av Genre/form
Under Genre/form, ange dels saogf-termer (genre/form-termer enligt Svenska ämnesord), dels termer som motsvarar marc-koder i 008.  
För att länka till saogf-termer, välj Genre/form i listan.  
För att länka till termer som motsvarar marc-koder i 008, se övriga rubriker. De vanligaste finns under rubriken Föreslagna.  
![Genre exempel](genre_exempel.png)  


**Roman**  
Haag, Martina: Det är något som inte stämmer  
Genre/form (saogf-term): Självbiografiska skildringar, Romaner  
Litterär genre (008): Roman  

**Diktsamling**  
Hallgren, Hanna: Vinterresan  
Genre/form (saogf-term): Poesi  
Litterär genre (008): Dikter

**Bilderbok för barn**  
Genre/form (saogf-term): Svenska barnboksinstitutet (Sbi) ansvarar  
Litterär genre (008): Skönlitterärt verk, genre ej angiven

**Fackbok för barn**  
Genre/form (saogf-term): Svenska barnboksinstitutet (Sbi) ansvarar  
Litterär genre (008): Ej skönlitterärt verk

**Biografi**  
Genre/form (saogf-term): Biografi  
Biografiskt material (008): Biografi över en individ  
Litterär genre (008): Ej skönlitterärt verk

**Självbiografi**  
Genre/form (saogf-term): Självbiografier  
Biografiskt material (008): Självbiografisk text, Självbiografi  
Litterär genre (008): Ej skönlitterärt verk

**Fackbok, ej biografi**  
Genre/form (saogf-term): Lämpliga saogf-termer.  
Se även [Svenska ämnesords översikt över Allmänna genreform-termer](http://www.kb.se/katalogisering/Svenska-amnesord/genrer-form/Allmanna-genreformtermer/).  
Litterär genre (008): Ej skönlitterärt verk  

#### Klassifikation
Se [Verk/Klassifikation](https://libris.kb.se/katalogisering/help/workflow-work).

#### Amne
Se Se [Verk/Ämne](https://libris.kb.se/katalogisering/help/workflow-work).

#### Malgrupp
Se [Verk/Malgrupp](https://libris.kb.se/katalogisering/help/workflow-work).

#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
```Exempel: text (txt)```

För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av verk. Skapa Verk som lokal entitet. Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg till Innehållstyp under Verk. Sök fram och länka till entitet.  

#### Anmarkning om akademisk avhandling    
Se Verk/Anmarkning om akademisk avhandling.  

 

GENRER: KODNING: AKADEMISK AVHANDLING, FESTSKRIFT, LITTERÄR GENRE MM  
ANMÄRKNING OM AVHANDLING



  
  
