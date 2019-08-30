# Week2
 
## Tirsdag:

Jeg fik svaret på alle opgaverne, selvom jeg stadig ikke føler jeg er 100% inde i alle begreberne. Se dokumentet "Fundamental Network Topics".

Læringsmål:
 (Jeg vil forsøge at gøre min reflektion over læringsmålene kort, da det hovedsaglig er de samme ting spørgsmålene i opgaven handler om)
 
 1) Kunne forklare konceptuelt om begrebet TCP/IP
 
 TCP(Transmission Control Protocol)/IP(Internet Protocol) er overskriften på en række lag med forskellige protokoller, der beskriver
 hvordan data bevæger sig over internettet.
 
 2) Kunne forklare konceptuelt om IP-addresser, herunder forskellen på private og offentlige IP-addresser
 
 En IP-adresse er en unik beskrivelse af en enhed på et netværk. Alle netværk har udadtil til internettet en offentlig IP-adresse, som
 andre kan bruge hvis de skal sende ting til en. I et privat netværk har alle enheder der er koblet op til samme router udadtil den samme
 IP-adresse, men indadtil har de hver deres private IP-adresse, som fx bliver brugt til at finde ud af hvilken enhed på det private net
 der skal modtage noget data.
 
 3) Kunne finde sin nuværende private og offenlige IP-addresse
 
 Kan finde privat med "ipconfig" i terminal. Offentlig ved at google "my ip".
 
 4) Kunne forklare om porte og en række portnumre afsat til specifikke protokoller
 
 Porte bliver brugt når dataen har nået en bestemt enhed og den skal finde ud af hvilken application der skal bruge dataen.
 Se spørgsmål 5 i tirsdagsopgave "Fundamental Network Topics" for et par portnumre afsat til specifikke protokoller.
 
 5) Kunne forklare konceptuelt om DNS-systemet og funktionen af en DNS-server
 
 DNS (Domain Name System) servere står for at holde styr på hvilke domæne navne der passer til hvilke IP-adresser. De kan kommunikere
 med hinanden og cacher et domæne/ip-adresse par i et stykke tid, hvis en bruger har requested fra et, for DNS serveren, ukendt domæne.
 
 6) Kunne forklare konceptuelt om ideen med DHCP-protokollen og en DHCP-server
 
 DHCP (Dynamic Host Configuration Protocol) er ofte indkorporeret i ens router og står for at tildele lokale enheder en lokal IP-adresse
 når de kommer på nettet.
 
 7) Kunne forklare begrebet loopback addresse og forklare relevansen af denne for os som udviklere
 
 En loopback adresse sender udgående data tilbage til den samme computer. Loopback er en let måde at teste nye applicationer eller
 ændringer til gamle, fordi du kan gøre det på en maskine og dataen stadig kommer igennem de rigtige protokoller fx TCP/IP.
 
 8) Kunne finde addressen på sin (nærmeste) DNS-server, DHCP-server og default GateWay
 
 Se spørgsmål 9, 11 og 12 i tirsdagsopgave "Fundamental Network Topics".
 
 9) Kunne forklare vigtige begreber relateret til HTTP-protokollen som Headers, Caching, Sessions og Cookies.
 
 Headers bliver brugt til at holde al den information der er brug for når data skal sendes fra et sted til et andet. Fx hvor dataen
 kom fra, hvor den skal hen, hvordan den skal sammensættes igen osv.
 
 Caching er når noget data bliver (midlertidigt?) for ikke at skulle ud og finde den data man har brug for, hver gang den samme     
 situation opstår og man har brug for den samme data igen.
 
 Sessions er en (ofte kortere) tidsperiode hvor data kan blive gemt, fx gemmer man data i en session hvis en person er logged ind og 
 gerne skulle forblive logged ind når han bevæger sig mellem siderne på samme domæne. Session slutter så efter brugeren har lukket siden
 ned, eller man kan indstille en session til at lukke, fx efter et stykke tid uden input fra brugeren.
 
 Cookies bliver brugt til at opbevare data over længere tid, fx kan en side måske huske brugerens navn i en cookie, så han let kan
 logge ind igen, og dermed blive gemt som logged ind i sessionen. Eller de kan blive brugt til at huske forskellige valg man har taget på en side, som ikke skal nulstilles hver gang man besøger den.
 
 10) Kunne monitorere og forklare ideen bag de vigtigste Request og Response headers
 
 Jeg ved hvordan man ser headers (ctrl-shift-j i chrome). Jeg er stadig lidt usikker på hvad de vigtigste headers er. Jeg går ud fra det
 er hvor dataen kommer fra og hvor den skal hen, men kan være der er mange flere der kan siges at være vigtige.
 
 ## Onsdag:
 
 Jeg fik svaret på alle opgaverne. Se dokumentet "The HTTP Protocol". Projektet "HTTPProtocalTest" hører til exercise 1-6 og 
 "SessionAndCookies" hører til exercise 7-8. Spørgsmålene i opgaverne var generelt ret vage. Jeg har prøvet at svare efter bedste ævne,
 men det ville ikke undre mig hvis jeg har overset en masse.
 
 Læringsmål:
 
 1) Forklare begrebet HTTP Headers og demonstere udvalgte headers via en browsers NetVærksvindue
 
 Headers bliver brugt til at holde al den information der er brug for når data skal sendes fra et sted til et andet. Fx hvor dataen
 kom fra, hvor den skal hen, hvordan den skal sammensættes igen osv. Se exercise 7 og 8 for info om udvaglte headers. 
 
 2) Kunne læse og skrive henholdsvis Request og Response Headers på server
 
 Har lavet lidt med request headers i forhold til session og cookies i exercise 7 og 8, men syntes ikke jeg har lavet noget med response
 headers.
 
 3) Kunne forklare om HTTP statuskoder og de forskellige ranges 2xx, 3xx, 4xx og 5xx
 
 Se exercise 3, 4a, 4b og 4c.
 
 4) Kunne forklare ideen med og demonstrere hvordan HTTP tillader Sessions (state) oven på en stateles protokol
 
 Ideen med sessions er at den gemmer lidt data hos klienten som så bliver sendt med i nye requests, så HTTP, selvom den er stateless,
 kan den "huske" visse informationer. Se også exercise 7.
 
 5) Kunne forklare ideen med og demonstrere brug af HTTP-cookies
 
 Cookies bliver brugt til at opbevare data over længere tid, fx kan en side måske huske brugerens navn i en cookie, så han let kan
 logge ind igen, og dermed blive gemt som logged ind i sessionen. Eller de kan blive brugt til at huske forskellige valg man har taget  på en side, som ikke skal nulstilles hver gang man besøger den. Se exercise 8 for demonstration.
 
 ## Torsdag:
 Fik lavet opgaven. Mit domæne frederiket.dk fører en til tomcat siden. Er generelt set mange ting fra torsdags opgaven jeg er usikker på og jeg ville ikke kunne sætte et nyt domæne op uden at følge "opskriften" igen.
 
 Læringsmål:
 
 1) Kunne forklare begrebet Virtualization
 
 Virtualization betyder i forhold til vores øvelse at vi har brugt enginx til at simulere en virtuel reverse proxy server.
 Altså at hvis set-uppet var "rigtigt" ville det proxyen være en server for sig selv, men bruger vores droplet til at hoste en virtuel
 ekstra server.
 
 2) Kunne forklare om ofte benyttede server arkitekturer
 
 (svaret er baseret på hvordan jeg har forstået det, men jeg er ikke sikker på det er helt rigtigt)
 
 Proxy server:
 En proxy, som vi bruger via ngninx, er en server der sidder foran en eller flere andre servers og intercepter og regulerer
 requests sendt til serverne bag proxyen og måske også de responses de sender tilbage. Proxyer kan bruges til fordele arbejdet mellem forskellige servers, hvilket fx kan hjælpe hvis der er stor efterspørgsel på den application man har på serverne bag proxyen. Man kan også bruge proxyer til at cache information om det response der skal sendes, så fremtidige requests efter samme data hurtigere kan blive afsendt.
 
 Database:
 Man kan have sin database på en anden server end sin application. Det kan hjælpe med sikkerhed og fordele workload til to servers.
 
 3) Kunne forklare begrebet x-as-a-service og benytte/demonstrere en infra-structure-as-a-service platform
 
 Ved ærlig talt ikke rigtigt hvad det her er. Jeg kunne sikkert google det, men jeg syntes ikke det var noget der stod noget om i de forskellige ting vi skulle læse, og jeg syntes ikke Arne nævnte det.
 
 4) Kunne forklare konceptuelt, om assymetrisk kryptering, signatures og certifikater, relateret til TLS
 
 Assymetrisk kryptering er når man bruger to keys i kryptering/dekrypteringsprocessen. Den ene key er privat og den deler man ikke med nogen, den anden key er offentlig og den kan deles med alle. Nårmalt vil man kryptere med modtagerens public key, så de kan bruge deres private key til at dekryptere. Hvis man vil kryptere noget som en signatur, kan man kryptere med sin egen private key, og så kan modtageren se at det kommer fra en, hvis det er muligt for dem at dekryptere indholdet med afsenderens public key.
 
 Et digitalt certificat bruges til at vise at man er den rigtige ejer af en public key og handler om at man stoler på dem der har udstedt certificated.
 
 TLS (Transport Layer Security) er den protokol der står for at kryptere og dekryptere dataen 
 
 5) Kunne forstå og benytte begreber krævet for at opsætte en server med et Domænenavn, en Reverse Proxy og SSL
 
 Jeg ville godt kunne følge opskriften igen, men der er mange steps hvor jeg er usikker på præcist hvad det er jeg laver.
 
 6) Kunne opsætte en server i praksis med domænenavn, reverse proxy og https
 
 Jeg fik det i hvert fald til at fungere, men ville som sagt ikke kunne gøre det igen uden opskriften.
