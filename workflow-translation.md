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
Skapa verk som lokal entitet genom att klicka på plustecknet vid Uttryck av (Lägg till verk). Välj Skapa lokal entitet och välj Verk. Klicka på plustecknet vid Verk (Lägg till fält under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.  
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

### Anmärkningar?
