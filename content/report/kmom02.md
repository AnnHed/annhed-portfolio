---
Title: Kmom02
Description: Part 2
Template: kmom
---

Kursmoment 2
===================

###SASS

Jag har använt mig av variabler, nesting och funktionen calc(). Det underlättar verkligen med variabler, tycker jag.
För att hålla min hoppande footer på plats så använde jag calc() och det fungerade jättebra. Även att placera bilder har jag testat samma funktion med. Där fick
jag prova olika värden innan jag blev nöjd med placeringen av bilden. Tror det går att göra mer med den när det gäller responsivitet,
men det har jag inte hunnit med än.

###Node, nmp och npm scripts

Jag upprepar mig igen och får säga att jag hade ingen koll alls på Node, npm eller npm scripts. Efter att ha fått igång det så det
fungerar och jag har hyfsat koll på vad jag gör, så är det ett bra verktyg. Jag tycker npm run lint ger väldigt tydliga felanvisningar, enkla
att rätta till. För att vara helt ärlig så har jag inte full koll på exakt vad som sker, utan har följt anvisningar i artiklar och genomgångar.
Men jag har satt watch och watch-min och det tycker jag är smidigt att "programmet" håller koll på ändrinagr som är gjorda i scss/css.

###Kompilera scss till css
Det har gått smidigt att kompilera. Jag har testat att läsa den kompilerade filen för att se vad den innehåller. Först kändes det som allt
innehåll var Font Awesome. Men när jag kollade mer noga så hittade jag min kod för sidan. Det mesta i den kompilerade filen är Font Awesom, ca tre fjärdedelar, sedan finns ett stycke kompilerad sidkod. Det är otroligt vad fonter och ikoner tar plats!

###Mitt eget tema
Överlag så försöker jag göra ett tema som är ganska sparsmakat layoutmässigt, åt det minimalistiska hållet.**Hoodie** har jag döpt det till, och tänker då på ett plagg som passar både hemma och på kontoret. De fontstilar jag har valt är, Abril Fatface för titlar och Lato i brödtext. Jag tycker Abril Fatface har en mjukhet,
utan att vara en alltför lekfull font. _*Elegans*_ nämner beskrivningen på Google Fonts hemsida. Lato har designern  Łukasz Dziedzic tagit fram. Jag tycker den är åt det personliga hållet men utan snirklar och stora, vida bokstäver. Jag har en grund att stå på men är inte klar än med temat.

Designen kommer att växa ju fler tekniker jag lär mig. Jag tänker särskilt på grid, som jag testade allra först. Det tog jag bort för av den koden så var det många saker som jag
inte hade satt mig in i, och det kändes direkt tråkigt att sidan skulle ha ett snyggt utseende som jag inte hade fixat med själv.
Så det blev en två-kolumns-layout där jag har försökt använda flexbox.

###Uppdelning av kod
Jag har delat upp koden i följande moduler: _*base*_, _*variables*_, _*layout*_, _*responsive*_, _*header*_, _*footer*_ och __*typography*_. Än så länge är jag nöjd med
denna uppdelning, men det kan komma nya moduler framöver.  

###TIL för Kmom02
Förra TIL handlade om Github. Där känner jag att jag har pushat och taggat under tiden jag jobbar, så det tog jag till mig. Jag vill lära mig fler funktioner för uträkningar i SASS för att komma undan att jag upprepar mig och också styra saker med mer finess. Jag är glad att jag fick koll över flödet mellan den uppdelade koden och de olika twig-filerna. Jag hade svårt att se vad som höll ihop allt, därför gjorde jag ett helt nytt tema för att från grunden se att jag hade koll på de delarna själv. Det är jag mest nöjd med!
