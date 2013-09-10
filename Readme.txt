
Dette filsettet inneholder

proglangs.html - hovedside for webapplikasjonen, med punktene i listeformat
dropdown.html - hovedside for webapplikasjonen, med drop-down meny
proglangs.css - stiler for webapplikasjonen
proglangs.js - javascriptbibliotek 

---------------

Kontrollspørsmål: 

0. JavaScript er et programmeringsspråk som kan brukes til å implementere ulike funksjoner, eller dynamiske elementer, inn i en html-side. 
Dette gjør at man feks kan legge inn egen tekst, eller gjøre andre endringer, noe som ikke vil være mulig hvis man kun bruker html. 

1. Forskjellen på CSS id og class elementer er at id er en knagg som er unik for hvert enkelt element, mens class kan brukes for en gruppe elementer. 
Det betyr at dersom det er flere elementer som skal behandles på samme måte er det en fordel å bruke class, siden en id kun kan brukes en gang per side. 

2. Ved presentasjon av en liste med mange elementer kan det ofte være hensiktsmessig å å bruke en dropdown funksjon, 
særlig hvis listen er en del av en annen side. Dette gjør det ofte mer brukervennlig og oversiktlig, 
da en liste tar opp mye plass og det kan være vanskeig å scrolle seg nedover for å finne riktig element dersom listen er for lang. 
På en side der selve listen er hovedelementet kan man like gjerne bruke en komplett liste uten dropdown, 
da gjerne sortert alfabetisk eller på andre måter gjort mer lesbar og oversiktlig. 

3. Wikipedia løser problemstillingen med en lang liste av programmeringsspråk med å bruke class-elementer, 
og de ulike programmeringsspråkene er delt opp i bolker etter alfabetet, der man kan velge fra en meny øverst for  komme til rett bokstav 
og deretter velge fra de ulike listene. Det ulike språkene er presentert i lister, og altså ikke ved bruk av dropdown meny. 
Dette fungerer bra på denne siden, da det er selve listen som er hovedfokuset. 
 
4. Hovedforskjellen mellom <div> og <span> er hvordan de vises. 
Div er et blokk-element som isolerer en seksjon av dokumentet på siden, og lager således en logiske divisjoner, mens span er et 
inline element og gjør at man kan gjøre lokaliserte formateringer innad i dokumentet. 

5. Med den siste versjonen av implementeringen i deloppgave to kan det oppstå noen brukbarhetsproblemer, blant annet kan det skje at 
teksten i noen av boksene (output) kan være for lang slik at man ikke får lest hele teksten. Det er heller ikke mulig å søke på kun starten 
av et navn, feks første bokstaven eller de første bokstavene. 