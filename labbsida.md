
Innehåll:  
[Adminmetadata](#adminmetadata)  
[Instans](#instans)  
[Verk](#verk)  


### Adminmetadata
* Skapad av/Organisation/Namn (040 ‡a)
- förval: den sigel som skapat posten. Ska inte gå att redigera.
Testdata: BOKR

Testar bild  
![Libris](http://libris.kb.se/images/libris_logotyp.gif)


BIBFRAME Svensk terminologi  
![BIBFRAME](http://www.kb.se/Dokument/BibframeSvenskTerminologi_10.jpg)

### Adminmetadata
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.

### Instans
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.
The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.The anchor link for that heading is the lowercase heading name with dashes where there are spaces. You can always get the anchor name by visiting the README on Github.com and clicking on the anchor that appears when you hover to the left of the heading.

### Verk


-------------------
HÄR TESTAR JAG ATT KLISTRA IN TESTFALLET SERIELL RESURS
----
Scenario/Testfall – Libris katalogisering  
UNDER ARBETE  

Tryckt seriell resurs

Exempel: Kammarmusik-nytt, ISSN 2001-2721, Voyager BibID 12683491


### Adminmetadata  
* Skapad av/Organisation/Namn (040 ‡a)   
  Förval: den sigel som skapat posten. Ska inte ändras.  
  ```Exempel: S```  
  
* Uppgraderad eller importerad av/Organisation/Namn (040 ‡d)  
  Skriv in sigel som har uppgraderat (ändrat nivå) eller importerat posten. För att söka fram sigel, se [Biblioteksdatabasen](https://biblioteksdatabasen.libris.kb.se/ "Biblioteksdatabasen")
  ```Exempel: U```

* Bibliografi/Bibliotek/Sigel (042 ‡9)  
  Ange bibliografikod genom att skriva in sigel. För att söka fram sigel, se [Biblioteksdatabasen](https://biblioteksdatabasen.libris.kb.se/ "Biblioteksdatabasen")

* Katalogiseringsspråk (040 ‡b)  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  

* Katalogiseringsregler (040 ‡e)  
  För post katalogiserad enligt RDA, länka till entitet: marc/Isbd samt skapa lokal entitet med Kod: rda    
  ```Exempel: marc/Isbd (länkad entitet) + lokal entitet, Kod: rda```

* Beskrivningsnivå (000/05)  
  Länka till entitet.  
  ```Exempel: nationalbibliografisk/fullständig nivå```

### Instans
* Utgivningssätt  
  Välj från lista.  
  ```Exempel: Seriell resurs```

* Har titel/Titel/Huvudtitel (245 #a)  
  Skriv in uppgiften.  
  ```Exempel: Kammarmusik-nytt```  
  
* Har titel/Titel/Huvudtitel/Övrig titelinformation (245 #b)  
  Skriv in uppgiften.  
  ```Exempel: Kammarmusikförbundets tidskrift```

* Identifikator/Typ  
  Välj från lista.  
  ```Exempel: ISSN```  
  
* Identifikator/Typ/Värde (022 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 2001-2721```

* Identifikator/Källa (022 #f)  
  Skriv in uppgiften.  
  ```Exempel: Nationell ISSN-central f (= ISSN Sverige)```  
  
* Identifikator/Internationellt intresse  
  Markera rätt alternativ. KOLLA!!  
  ```Exempel: Ja (True)```  
  
* Identifikator/Felaktigt ISSN (022 #y)   
  Skriv in uppgiften.   
  ```Exempel: 1653-2945```

* Utgivning   
  * Plats/Benämning (264 -/1 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: Brämhult```  
  * Agent/Benämning (264 -/1 ‡b)  
  Skriv in uppgiften.  
  ```Exempel: Kammarmusikförbundet```  
  * Datum (264 -/1 ‡c)  
  Skriv in uppgiften.  
  ```Exempel: 2011-2013```  
* Typ av utgivningsdatum/utgivningsstatus (008/06)  
  Länka till entitet.  
  ```Exempel: d (= utgivning avslutad)```

* Kronologisk täckning (008/11-17)  
  Skriv in uppgiften.   
  ```Exempel: 2011-2013```  

* Utgivningsland (008/15-17)  
  Länka till entitet.  
  ```Exempel: Sverige (sw)```  

* Frekvens  
  * Frekvensterm (008/18)  
    Länka till entitet.  
    ```Exempel: var tredje månad (q = quarterly)```  
  * Regelbundenhet (008/19)  
    Länka till entitet.  
    ```Exempel: regelbunden (r = regular)```

FORTSÄTT HÄR

### Numrering av seriella resurser/Benämning (362 0/- #a)  
```Exempel: 2011: 4-2013: 2```


### Medietyp (337 #b)  
- länkning till entitet  
```Exempel:  n (= unmediated)```


### Bärartyp (338 #b)  
- länkning till entitet  
```Exempel:  nc (= volume)```

### Form för katalogiserat objekt (008/23)  
- länkning till entitet  
```Exempel: - = ingen av följande)```


### Relaterad till/Dokument/URI (856 4/8 #u)  
```Exempel:  http://www.kammarmusikforbundet.se```  
Relaterad till/Dokument/Anmärkning/Anmärkning (856 #z)  
```Exempel:  Förbundets webbplats```


### Utgiven med/Verk/Har titel/Titel/Titel (780 #t)  
```Exempel: Musikant (Stockholm. 2011)```  
### Utgiven med/Verk/Identifikator/Typ  
```Exempel:  ISSN```  
### Utgiven med/Verk/Identifikator/Typ/Värde (780 #x)  
```Exempel:  2001-273X```  
### Utgiven med/Verk/Beskriven av/Post/Kontrollnummer (780 0/1 #w)  
```Exempel: 12683514```  
### Utgiven med/Verk/Inledande anmärkning - Marc:displayText (unhandled term)  
```Exempel: 2011:4-2013:2 omvänt sammanhäftad med```


Verk
### Instans av Verk/Text


### Har titel/Nyckeltitel/Huvudtitel (222 -/0 #a)  
```Exempel:  Kammarmusik-nytt```  
### Har titel/Nyckeltitel/Huvudtitel/Särskiljande tillägg (222 #b)  
```Exempel:  (Brämhult)```



### Medverkan och funktion/Medverkan/Agent (710 2/- #a)  
- länkning till entitet  
```Exempel: Riksförbundet Sveriges kammarmusikarrangörer``` 
### Medverkan och funktion/Medverkan/Agent/Funktion (710 #4)  
- länkning till entitet  
```Exempel:  Utgivare (pbl = publisher)```


### Klassifikation/DDK-klassifikation/Kod (082 0/4 #a)  
```Exempel: 785.005```  
### Klassifikation/DDK-klassifikation/Kod/Klassifikationsupplaga (082 #2)  
```Exempel: 23/swe```


### Ämne  
- länkning till entitet - agent - organisation (610 2/- #a)  
```Exempel: Riksförbundet Sveriges kammarmusikarrangörer```  
- länkning till entitet - sao-term (650 -7- #a, #2 sao)  
```Exempel: Kammarmusik```  
- länkning till entiteter - geografiskt ämnesord (651 -/4 #a)  
```Exempel: Sverige```


### Genre/form  
- länkning till entiteter – saogf-termer (655 #a, #2 saogf)  
```Exempel: Organisationspress```  
```Exempel: Musiktidskrifter```  
- länkning till entitet – typ av fortlöpande resurs (008/21)  
```Exempel: p ( = marc/Periodical)```  
- länkning till entitet - konferenspublikation (008/29)  
```Exempel: 0 (= inte konferenspublikation)```


### Språk (008/35-37)  
- länkning till entiteter  
```Exempel: svenska (swe)```


### Innehållstyp (336 #b)  
- länkning till entiteter  
```Exempel: text (txt)```


### Relaterade verk/Fortsätter delvis/Verk/Har titel/Titel/Titel (780 #t)  
```Exempel: Musikant och kammarmusik-nytt```  
### Relaterade verk/Fortsätter delvis/Verk/Identifikator/Typ  
```Exempel:  ISSN```  
### Relaterade verk/Fortsätter delvis/Verk/Identifikator/Typ/Värde (780 #x)  
```Exempel:  1653-2945```  
### Relaterade verk/Fortsätter delvis/Verk/Beskriven av/Post/Kontrollnummer (780 0/1 #w)  
```Exempel: 9955452```



### Relaterade verk/Fortsättes av/Verk/Har titel/Titel/Titel (785 #t)  
```Exempel: Kammarmusik-nytt (Brämhult. Online)```  
### Relaterade verk/Fortsättes av/Verk/Identifikator/Typ  
```Exempel:  ISSN```  
### Relaterade verk/Fortsättes av/Verk/Identifikator/Typ/Värde (785 #x)  
```Exempel:  2001-6921```  
### Relaterade verk/Fortsättes av/Verk/Beskriven av/Post/Kontrollnummer (785 0/0 #w)  
```Exempel: 14697501```  



### Alfabet/skriftart (008/33)   
- länkning till entiteter  
```Exempel: b (= Extended roman = Latinskt alfabet med diakriter och specialtecken (a-ö))```


### Behandling vid titeländring (008/34)  
- länkning till entiteter  
```Exempel: 0 (= Successive entry = Titeländring ger upphov till ny post)```
