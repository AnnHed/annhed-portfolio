---
Title: Kmom03
Description: Part 3
Template: kmom
---

Kursmoment 3
===================

###CSS-grid/Flexbox

Det har varit både svårt och lätt att jobba med grid och flexbox. Lätt när man följer enklare exempel från
W3C schools, svårare när man har en idé själv som sedan inte blir så responsiv som man hade tänkt. Jag har läst en del
artiklar av webbdesignern Rachel Andrews som hjälp för att förstå hur grid och flexbox kan samspela på en sida och
om längdenheten _**fr**_. Det samspelet har jag försökt testa. Jag har använt grid på report-sidan medan de enskilda kursmomenten har en enkel
grid-layout med en sidomeny och en innehållsdel. Det finns även ett grid-element med flexbox inuti längst ner som en test av hur det kan vara att blanda.

###Erfarenheter och åsikter om grid och flexbox

Jag tyckte att det blev roligare att designa en sida med grid och flexbox för det är mer kontroll över var elementen hamnar. Man behöver inte placera element på rätt
ställe med hjälp av att justera marginalstorlekar. Sedan har jag haft god hjälp av att se gridlinjerna i inspektörsverktyget i Firefox.
Trots att det är komplexa tekniker så är det väldigt spännande att lära sig. Jag har inte använt teknikerna tidigare, men ser fram mot att lära mig mer!

###SASS-kod i olika moduler, en ny modul för layout?

Jag har sedan tidigare delat in SASS-koden i moduler. Det som har tillkommit är en modul för sidomenyn samt en för kmom-sidorna. Det jag behöver göra är att se
över min layout-modul. Där skulle jag kunna samla mer kod som jag har på andra ställen.

###Ändrat sidans layout eller reportsidan?

Under förra kursmomentet så gjorde jag en liten ändring av hem-sidans layout. Jag har huvudsakligen jobbat med att ändra layout på reportsidan och tillhörande kursmomentsidor.
Jag kommer att se över sidans layout vid tillfälle. Det skulle bli mer enhetligt och lättare att underhålla med en bättre grundlayout för sidan.

###Til för Design kmom03

Under detta kursmoment så har jag grubblat mycket på breakpoints och responsivitet. Jag har funderat kring varför sidan fungerar bra på ipad men inte
på mobiler. Det är där det har kraschat för mig. Kan hända att jag har skrivit kod som skriver över annan kod eller så är det hur jag har satt breakpoints som
förstör. Min lösning på detta blev att börja med den minsta skärmstorleken. Inget jag kom på själv, utan jag hittade en artikel som tog upp mobile device first.
Kanske inte meningen att göra så nu, men jag fick en aha-känsla. Sedan så testade jag gridfunktionen minmax() och autofill. Att använda dem skulle ge en bättre flexibilitet.
En kunskap jag tar med mig från detta kursmoment är skillnaden mellan grid och flexbox som jag förstår nu. Även om jag har grid med två items på ett ställe så vet jag att
flexbox är för rader eller kolumner medan grid tar bägge.
