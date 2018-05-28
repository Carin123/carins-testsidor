
# Verk och instans - ett nytt format

## Nytt format
Formatet i Nya Libris ger möjlighet att strukturera den bibliografiska informationen på ett nytt sätt. Istället för att upprepa uppgifter som klassifikation, ämnesord, genre, författarens namn för varje ny utgåva av en bok, så kan vi i fortsättningen samla denna information på ett ställe - verket - och sedan länka instanser till verket, när nya utgåvor kommer. Detta är en styrka med vårt nya Bibframe-baserade format.

## Verk som länkbar entitet eller lokal entitet
Men hur gör man? Hur fungerar det i praktiken? I Nya Libris finns det möjlighet att antingen skapa verk som lokala entiteter eller att skapa länkbara verksentiteter. När vi låter verket vara en lokal entitet i instansen, behåller vi samma struktur som i dagens marcposter. Verksinformationen upprepas i varje post, för varje utgåva, tillsammans med information om utgåvan. Om vi gör så, har vi inte utnyttjat det nya formatet fullt ut. 

INSTANS
  Instans av verk
  
INSTANS
  Instans av verk
  
INSTANS
  Instans av verk
  

Om vi i stället bryter ut verket till en egen länkbar entitet, kan vi i fortsättningen länka nya utgåvor (nya instanser) till denna verksentitet. 

VERK
  Instans
  Instans
  Instans

Vi kan också länka översättningar av ett verk till originalverket. Det finns många fler relationer som vi kan uttrycka, t ex bearbetning, verk som ämne och så vidare.

Att bryta ut verk och instanser till egna entiteter kommer till nytta framförallt för verk som kommer ut i många instanser, till exempel klassiker och andra verk som får en stor spridning. För många verk händer inte det utan verket kommer ut endast en gång. 

## Poster från Voyager
För de poster som förs över från Voyager till Nya Libris kommer verksinformationen att sparas som lokala entiteter. Man hittar verksinformationen under Instans av Verk. Verksinformation förs också över från Voyager till Nya Libris i form av de auktoritetsposter för verk och uttryck som har skapats i Voyager. Dessa kommer att sparas som rudimentära verksposter i Nya Libris. Ytterligare uppgifter behöver tillföras för att dessa verksposter ska kunna användas i det nya formatet. Libris-teamet kommer också att se över möjligheten att maskinellt skapa underlag som underlättar verkshantering. 

## Hur gör vi med verk i Nya Libris?
Det behövs riktlinjer och instruktioner om hur vi ska hantera verk i Nya Libris. Dessa riktlinjer kommer senare. När Nya Libris går i skarp drift ber vi er att avvakta med att bryta ut verk till länkbara verksentiteter. Under en första övergångstid fortsätter vi som förut, att upprepa verksinformationen i varje post. Verksinformationen får vara en lokal entitet i instansen. Fortsätt att ange författarens namn (primär medverkande/medverkande), klassifikation, ämnesord, genre, språk och så vidare, för varje utgåva som du katalogiserar. Du anger dessa uppgifter under Instans av Verk. 



# Till hjälptexten Bok - tryckt monografi


Skapa verket som lokal entitet eller bryt ut verket till en länkbar entitet. Vi rekommenderar att du skapar verket som lokal entitet under den första tiden som Nya Libris är i drift. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet.
