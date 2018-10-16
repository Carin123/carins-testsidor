---
section: Arbetsflöden
title: 1.1.3 Översättning
order: 19
date: 2018-09-28
tags:
- tryckt monografi
- översättning
--- 

## Översättning   

### Översättningar som verk
Enligt BIBFRAME betraktas översättningar som egna verk. En verk kan vara en översättning av ett annat verk. Denna relation kan uttryckas genom en länk från det ena verket till det andra. I Libris har vi ännu inte börjat att länka verk. Beskriv istället översättningen som en lokal entitet.  

Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

### Titel

#### Instansens titel  
Ange instansens (det vill säga manifestationens eller utgåvans) titel under Instans/Har titel (Obs. Inte Instans av Verk utan Instans). Ange eventuella varianttitlar som till exempel omslagstitel, ryggtitel, parallelltitel.  

#### Verkets titel  
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
För översättningar och för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk, ska den föredragna titeln för verket anges. I övriga fall räcker det att ange instansens titel.  
  
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med primär medverkande anger du här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till delfältet fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
  
##### Verkets titel - huvuduppslag   
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan primär medverkande anger du här.  
Under Instans av Verk/Text, lägg till Uttryck av genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till fält under: Text) och välja Uttryck av.  
Skapa verk som lokal entitet genom att klicka på plustecknet vid Uttryck av (Lägg till verk). Välj Skapa lokal entitet (längst ner i sidorutan), Skriv "verk" i rutan Skapa lokal entitet. Klicka på * Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.  
Skriv in uppgiften.  
```Exempel: Bibeln```
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel genom att klicka på plustecknet vid Titel (lägg till fält under: Titel), välj Deltitel.  
Skriv in uppgiften.  
```Exempel: Nya testamentet```
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning genom att klicka på plustecknet vid Språk (Lägg till fält under: Språk) och välja Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

### Språk
För en översättning behöver man ange dels det språk som texten man beskriver är skriven på och dels originalets språk. Ange båda under Instans av Verk/Text.  

* Språk (language = 008/35-37)  
  Ange det språk som den text du beskriver är skriven på. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  

#### Originalets språk  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet) och lägg till Benämning (klicka på Lägg till fält under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning. Välj från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till fält under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet och välj Verk i listan. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
  
###### Texten delvis översatt  
(041 0/- #a + 041 1/- #a #h)  
* Har del/Verk/Språk (hasPart/Work/language) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote) +  
  Originalversion/Verk/Språk (originalVersion/Work/language)  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk/Text (se Språk ovan). Lägg sedan till Har del under Instans av Verk/Text. Välj Skapa lokal entitet och välj Verk. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till, till exempel engelska. Lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  
