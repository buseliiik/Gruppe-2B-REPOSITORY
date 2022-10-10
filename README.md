# Gruppe-2B
## Tabell for våre reps


| Navn  | Repository link |
| ------------- | ------------- |
| Mie Maxine Mjølstad Nord  | https://github.com/mienord  |
| Busenur Yilmaz  | https://github.com/buseliiik  |
|  Jeppe Stenstadvolden Strømberg  | https://github.com/Jeppess123  |
| Zaher Mordini  | https://github.com/Candle-fly  |
| Martin O Hovland  | https://github.com/MartinOHovland  |
| Stein Arild V.Danielsen  | https://github.com/SteinArildN |

## __IS-114 Flaggoppgave:__

For å løse flaggoppgaven valgte gruppen å lage det tyske, armenske og japanske flagget. Denne oppgaven er krevende og derfor måtte vi bruke GitHib projects til å fordele arbeidsoppgaver slik at det ble overkommelig og at alle bidro. Vi skrev koden for de tre flaggene i hver sin fil som ligger i repositorien vår her^. Deretter lagde vi en felles fil med alle tre flaggene som heter index.html og kan ses som en nettside i Github pages.

## __Dette er slik vi løste oppgaven:__

__Valg av relevante arbeidsoppgaver:__
Vi bruker Github Projects til å fordele arbeidsoppgavene. Vi bryter ned den store oppgaven og skriver detaljert ned hvilke deloppgaver som må gjøres. Vi fordeler de og "assigner" de til gruppemedlemmer i Projects. Selv har hver person ansvar for å flytte oppgaven videre når den jobbes med slik at hele gruppa kan se hvor langt i prosessen den deloppgaven er, eller om noen trenger hjelp. Vi syntes dette fungerer veldig godt og gir alle en god oversikt. 


__Hvordan bruke Github Projects?:__

__Buse:__
Jeg laget et nytt project i gruppe-repository for å planlegge oppgaven lettere. Deretter Mie og jeg delte oppgaver små deler i backlog og vi flyttet oppgaver hvis vi gjør noe endring. Backlog til in progress til in review og til done (Kanban board). Vi konvertert de oppgavene som står i backlog til issue. Deretter har valgt personer i gruppen  egne oppgaver. Jeg prøvde å forklare hvordan jeg bidratt med i readme filen. comitted changes.

### Gruppens bidrag:
__Mie:__
Det første jeg gjorde var å velge to flagg jeg ville lage. Jeg valgte Tyskland og Armenia. Deretter gjorde jeg research (kilder under) og kodet flaggene ved bruk av < p >-elementet og “style” attributt og < p >-elementet og ”class” attributter. Jeg lade disse i forkjellig filer som het det de skulle og pusha de til gruppe reps. 

__Flagg beskrivelse Mie:__
Når jeg skulle lage to flagg hjalp det veldig at Janis gikk gjennom hvordan man brukte de elementene til å kode det i timen. Jeg tok notater og dro hjem å se på det. Jeg brukte forskjellig kilder til å forstå koden og hva Janis hadde gått gjennom. Disse ligger i kildelista. Jeg brukte Wikipedia til å finne riktig fargekoder og dimensjoner på flaggene. Tyskland sitt flagg har størrelsesforholdet 3:5 derfor er flagget 300 px i width, størrelsesforholdet er derfor 300 x 0.6 = 180 - så flagget er 180px i height, og det må deles på de tre rektanglene så de er 60px hver.
Det armenske flagget har størrelsesforholdet 1:2 derfor er flagget 300px i width og 150px i height. Siden flagget består av 3 rektangler må de ha 50px hver i height. Når jeg skulle lage cssflagget valgte jeg å bruke "class" attributet fordi den kan skrives flere ganger på samme dokument og kan brukes i flere HTML elementer, men "id" kan bare identifisere et element og må ellers være unikt for forskjellige elementer i en HTML side (aishalichauhan3003, 2021). 


__Stein:__ Japan flagget har 2:3 dimensjoner, den røde prikken i midten har radius på 3/5 av høyden. Rød koden er BC002D, Hvite koden er FFFFFF. Jeg gikk inn på W3Schools og fant canvas seksjonen. Jeg lagde 'tegne brettet' med dimensjonene til flagget, høyden er 150 og bredden er 200. Fargen til 'tegne brettet' er automatisk hvit, så da gjorde jeg ingen ting der. Sirkelen skrev jeg inn "ctx.arc(100, 75, 45, 0, 2 * Math.PI, false);" og deretter "ctx.fillStyle = '#BC002D';". 100 og 75 er posisjon. 45 er radius. Usikker på hva resten av parametrene gjør. Uansett ctx er contexten til canvasen c, som er hentet fra HTML koden. All denne kodinga er selfølgelig gjørt innenfor <script></script>.

__Jeppe:__ Vi brukte HTML, Canvas og CSS. Det som skiller disse metodene er at HyperText Markup Language (HTML) er et markeringsspråk for formatering av nettsider hypertekst og mye annen informasjon som kan vises i en nettleser. Cascading Style Sheets(CSS) er derimot et språk som brukes til å definere utseende på filer som er skrevet i enten HTML eller XML. Canvas API er et program for å tegne grafikk via Javascript og HTML elementet.

__Martin:__ Noe som er positivt ved å bruke disse språkene er det at de er relativt enkle. Det er lærerike språk man kan trenge videre med koding. Hjelper videre med jobb hvis man trenger en nettside etc. En annen fordel er å bruke de forskjellige metodene sammen for å lage et bedre sluttprodukt.
Negative sider ved å bruke disse hver for seg er at sluttproduktet kan bli ganske simpelt. 

__Zaher:__ 'Style' kan brukes av et element ved å bruke style-attributten. HTML elementer gir en beskrivelse av det generelle innholdet. Og Style-attributten er et av de globale attributtene som brukes på ethvert CSS og HTML-dokument. Style elementet kan brukes som et tag i <head> eller <body>. Ved bruk av 'style' (som definerer CSS-stylinginformasjon) i <head> vil innholdet og styling-informasjonen holdes atskilt, og det kalles 'Embedded Style'. Ved bruk av '<canvas>' i HTML5 har man en enorm variasjon av grafikk. Det ville være enkelt å tegne et flagg ved å bruke elementet <canvas> ved hjelp av JavaScript. 

__Kilder:__

GeeksforGeeks. «Difference between an Id and Class in HTML?», 12. april 2019. https://www.geeksforgeeks.org/difference-between-an-id-and-class-in-html/.

GeeksforGeeks. «Create Indian Flag Using HTML and CSS», 12. mars 2021. https://www.geeksforgeeks.org/create-indian-flag-using-html-and-css/.

W3Schools. "HTML Canvas", Ukjent. https://www.w3schools.com/html/html5_canvas.asp.

Bidragsytere til Wikimedia-prosjektene. (2002, November 19). beskrivelsesspråk for web-dokumenter. Wikipedia.org; Wikimedia Foundation, Inc. https://no.wikipedia.org/wiki/HTML 

‌Bidragsytere til Wikimedia-prosjektene. (2004, May 30). programmeringsspråk brukt for å bestemme utseende til nettsider. Wikipedia.org; Wikimedia Foundation, Inc. https://no.wikipedia.org/wiki/Cascading_Style_Sheets

‌Canvas API - Web APIs | MDN. (2022, September 2). Mozilla.org. https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API

Janis sine timer.
