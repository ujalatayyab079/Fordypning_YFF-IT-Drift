<img width="1500" height="500" alt="image" src="https://github.com/user-attachments/assets/4dc1af4f-2d3c-4196-a19f-f8646ec00bf3" />

# TryHackMe : Grunnleggende Cybersikkerhet _ Læring
Denne markdown-filen inneholder en oversikt over hva jeg har lært gjennom arbeidet med TryHackMe. Jeg har samlet de viktigste begrepene, temaene og ferdighetene jeg har jobbet med i løpet av perioden.

Målet med denne delen er å vise hva jeg har lært, hvordan jeg har utviklet forståelsen min innen cybersikkerhet, og hvor nyttig denne plattformen har vært for både teori og praktisk læring.

---

##  Hva er cybersikkerhet?
Cybersikkerhet er praksisen med å beskytte digitale systemer, nettverk, programmer og data mot digitale angrep, 
uautorisert tilgang eller skade. Målet er å sikre konfidensialitet, integritet og tilgjengelighet for informasjon 
ved hjelp av tekniske og organisatoriske tiltak, ofte som et forsvar mot trusler som hacking, datatyveri og sabotasje. 

#### _Her er nøkkelpunkter om cybersikkerhet:_
- **Hva besyttes?** Alt som er koblet til internett eller avhengig av IKT, inkludert personopplysninger, bedrfitshemmeligheter,
  datasystemer og kritiske infrastruktur.
- **Hvorfor er det viktig?** Cyberangrep kan føre til store økonomiske tap, driftshemmeligheter, datasystemer og kritisk infrastruktur.
- **Vanlige trusler:** Inkluderer skadevare (malware), phising, løsepengevirus (ransomware) og "denial of service"-angrep (DoS).
- **Sentralt prinsipp** _Zero Trust_ (null tillit) er en sentral moderne modell, som innebærer at ingen brukere
  eller enheter automatisk klareres, og alle må verifiseres.
- **Forskjell på cybersikkerhet og informasjonssikkerhet:** Cybersikkerhet fokuserer primært på digitale trusler, mens informasjonssikkerhet
  er et bedere begrep som også dekker fysisk sikring av informasjon
- #### _Eksempler på sikkerhetstiltak_
  er brannmurer, antivirusprogrammer, kryptering, tofaktorautentiering og opplæring av ansatte.

####  Tekniske tiltak
| Tiltak | Forklaring |
|--------|------------|
| Tofaktorautentisering (2FA) | Ekstra sikkerhetslag ved innlogging |
| Brannmur | Beskytter systemet mot uønsket trafikk |
| Kryptering | Gjør data uleselig for uvedkommende |
| Antivirus | Oppdager og fjerner skadelig programvare |
| VPN (sikkert nettverk) | Beskytter tilkoblingen på internett |

#### Bedrift og organisasjon
| Tiltak | Forklaring |
|--------|------------|
| Sikkerhetsopplæring | Lærer ansatte om sikker bruk av systemer |
| Begrenset tilgangsstyring | Kun nødvendige personer får tilgang |
| Beredskapsplaner | Plan for hva man gjør ved angrep |
| Programvareoppdatering | Lukker sikkerhetshull i systemer |
| Sikkerhetskopiering (backup) | Lager kopi av data for gjenoppretting |

####  Personlig sikkerhet
| Tiltak | Forklaring |
|--------|------------|
| Unike, sterke passord | Vanskeligere å hacke kontoer |
| Passordbehandler | Lagrer passord sikkert |
| Kildekritikk (phishing-sjekk) | Unngå falske lenker og svindel |
| Sikring av trådløst nett | Beskytte WiFi med passord |


---
## ⚔️ Offensiv sikkerhet (Red Team)

Offensiv sikkerhet er en proaktiv tilnærming der man tester egne systemer ved å angripe dem for å finne sårbarheter før ekte angripere gjør det. Målet er å identifisere svakheter og forbedre sikkerheten.

**Formål:**
- Identifisere sårbarheter og sikkerhetshull  

**Metoder:**
- Penetrasjonstesting (pentesting)  
- Sårbarhetsanalyser  
- Red Teaming  

**Tilnærming:**
Man tenker og handler som en angriper (hacker) for å simulere virkelige cyberangrep.

**Eksempel:**
En etisk hacker prøver å få tilgang til en bedrifts database for å vise hvor sikkerheten svikter.

---

## 🛡️ Defensiv sikkerhet (Blue Team)

Defensiv sikkerhet handler om å beskytte systemer, nettverk og data mot angrep og uautorisert tilgang. Fokus er på å oppdage, stoppe og håndtere trusler.

**Formål:**
- Beskytte IT-systemer og data  

**Metoder:**
- Brannmur (firewall)  
- Inntrengingsdeteksjonssystemer (IDS)  
- Overvåking og hendelseshåndtering  

**Tilnærming:**
Kontinuerlig overvåking av systemer for å oppdage og stoppe angrep i sanntid.

**Eksempel:**
IT-sikkerhetspersonell analyserer trafikk og stopper mistenkelig aktivitet.



##  Samspill mellom offensiv og defensiv sikkerhet

Offensiv og defensiv sikkerhet jobber sammen for å styrke den totale sikkerheten. Offensiv sikkerhet brukes til å teste systemer, mens defensiv sikkerhet beskytter og overvåker dem.

Begge tilnærmingene er viktige for å bygge et sikkert system, og brukes ofte sammen i moderne cybersikkerhet.

<p align="right" style="font-size:5px;">
(LinkedIn Norge) - (Forsvaret) - (Regjeringen.no)
</p>

---


##  Hva er pentesting?


Pentesting (penetrasjonstesting) er en metode der man tester sikkerheten i et datasystem, nettverk eller en nettside ved å simulere ekte cyberangrep. Dette gjøres for å finne svakheter før ekte hackere kan utnytte dem (Fence; Sicra AS).



#### Formålet med pentesting

- **Finne sårbarheter:** Oppdage svakheter i systemer, apper og nettverk  
- **Simulere angrep:** Teste hvordan systemet reagerer på ulike typer hacking  
- **Forbedre sikkerhet:** Gi forslag til hvordan man kan tette sikkerhetshull  
- **Etisk hacking:** Bruke hacker-metoder på en lovlig og kontrollert måte (Fence)



####  Hvordan brukes pentesting?

Pentesting brukes ofte ved å:

- Bestemme hvilke systemer som skal testes (f.eks. nettside eller nettverk)  
- Velge testmetode (åpent eller skjult system)  
- La sikkerhetseksperter prøve å hacke systemet  
- Lage en rapport med funn og anbefalinger (Sicra AS)



####  Kort oppsummert

Pentesting handler om å “hacke sitt eget system” for å finne feil, slik at man kan gjøre det tryggere før ekte angripere finner dem.

---
##  Hvordan beskytte seg på nettet

<img src="https://github.com/user-attachments/assets/a41cc5ff-7dbd-4fff-a11c-9eb6df12af42" width="1100">

For å beskytte seg på nettet i 2026 er det viktig å kombinere tekniske sikkerhetstiltak med god digital dømmekraft. Dette handler både om å bruke riktige verktøy og å være kritisk til det man møter på internett (Telenor).


### ⚠️ Slik beskytter du deg på nettet

- **Bruk tofaktorautentisering (2FA):** Gir ekstra sikkerhet ved innlogging, spesielt for e-post, sosiale medier og banktjenester.  
- **Bruk passordbehandler og sterke passord:** Lag unike passord for hver tjeneste for å unngå at flere kontoer blir kompromittert samtidig. 
- **Oppdater programvare jevnlig:** Operativsystemer og apper må oppdateres for å tette sikkerhetshull.
- **Bruk sikre nettverk:** Unngå åpne Wi-Fi-nettverk ved sensitive handlinger, og bruk gjerne VPN for kryptering av trafikk. 
- **Sjekk nettsider (HTTPS):** Se etter “https://” og hengelås-ikon for å sikre trygg kommunikasjon.
- **Ta backup:** Regelmessig sikkerhetskopiering beskytter viktige filer ved angrep eller feil.

<p align="right">
(Telenor)
</p>

### ⚠️ Hva du bør være forsiktig med

- **Phishing (falske e-poster/SMS):** Meldinger som prøver å lure deg til å gi fra deg passord eller BankID (Politiet).  
- **Ukjente lenker:** Ikke klikk på lenker i mistenkelige meldinger – gå heller direkte til nettsiden selv (Politiet).  
- **Deling av sensitiv informasjon:** Aldri del passord, BankID eller kortinformasjon (Politiet).  
- **Mistenkelige vedlegg:** Kan inneholde virus eller skadelig programvare (Politiet).  
- **Falske tilbud og nettsider:** Hvis noe virker for godt til å være sant, er det ofte svindel (KLP).  
- **Overdeling på sosiale medier:** Kan gi angripere informasjon de kan bruke (Politiet).

<p align="right">
(Politiet) - (KLP)
</p>

#### Ekstra råd for netthandel

- Bruk kredittkort for bedre beskyttelse ved svindel (DNB).  
- Sjekk omtaler og vurderinger av nettbutikker før kjøp (KLP).  

#### Hva gjør du hvis du blir utsatt for svindel?

- Kontakt banken umiddelbart for å sperre konto eller kort (DNB).  
- Endre passord på berørte kontoer og andre tjenester med samme passord (DNB).  
- Anmeld hendelsen til politiet (DNB).  

#### Kort oppsummert

God nettsikkerhet handler om å kombinere tekniske tiltak som 2FA, oppdateringer og kryptering med kritisk tenkning og forsiktighet i hverdagen på nettet. 

---

## Begrepsliste: Alle begreper jeg lærte (TryHackMe - Cybersikkerhet)

<img src="https://github.com/user-attachments/assets/ca685a97-0e3d-48bf-9f34-a040024b4a4d" width="1100">

#### Generelle begreper
- **Simulering:** Teste noe som om det var ekte  
- **Angrep:** Forsøk på å skade eller få tilgang til et system  
- **Detect (oppdage):** Finne tegn på angrep  
- **Mistenkelig aktivitet:** Unormal oppførsel i systemet  
- **Containment:** Stoppe eller begrense et angrep  

####  Sikkerhet og systemer
- **SOC (Security Operations Center):** Team som overvåker og beskytter systemer  
- **DevSecOps:** Kombinerer utvikling, drift og sikkerhet  
- **Kryptografi:** Beskytte data ved å gjøre det om til kode  

#### Web og teknologi
- **Apache:** Webserver som viser nettsider på internett  
- **Lighttpd:** Lett og rask webserver  
- **Forespørsel (request):** Når en nettleser ber om en nettside  


####  Verktøy
- **dirb:** Verktøy for å finne skjulte mapper på nettsider  
- **VirusTotal:** Sjekker filer og lenker for virus  
- **Have I Been Pwned:** Sjekker om data er lekket  


####  Søkeferdigheter
- **Source:** Hvor informasjon kommer fra  
- **Evidence and reasoning:** Bevis og forklaringer  
- **Objectivity og bias:** Om informasjon er nøytral eller påvirket  
- **Corroboration:** Flere kilder bekrefter samme info  


####  Søkeoperatorer
- `"tekst"` = nøyaktig søk  
- `site:` = søk på en bestemt nettside  
- `-ord` = fjern ord fra søk  
- `filetype:` = finn spesifikke filer  

####  Spesialiserte søkemotorer
- **Shodan:** Søker etter enheter på internett (kameraer, servere, IoT)  
- **Censys:** Søker etter internett-systemer og sikkerhetsdata  


####  Sårbarheter og angrep
- **Sårbarhet (vulnerability):** En svakhet i et system  
- **Exploit:** En metode for å utnytte en sårbarhet  
- **CVE:** ID-system for kjente sikkerhetsfeil  
- **Exploit Database:** Samling av kjente exploits  


## Begrepstabell (Cybersikkerhet)

| Begrep | Forklaring |
|--------|------------|
| Cybersikkerhet | Beskyttelse av systemer, nettverk og data mot angrep |
| Offensiv sikkerhet | Teste systemer ved å simulere angrep for å finne svakheter |
| Defensiv sikkerhet | Beskytte systemer mot angrep og uønsket tilgang |
| Pentesting | Etisk hacking for å finne sikkerhetshull i systemer |
| Simulering | Å teste noe som om det var ekte, uten faktisk skade |
| Malware | Skadelig programvare som kan skade eller stjele data |
| Phishing | Forsøk på å lure brukere til å gi fra seg informasjon |
| Firewall (brannmur) | System som blokkerer uønsket nettverkstrafikk |
| Kryptering | Gjør data uleselig for uvedkommende |
| VPN | Krypterer internettforbindelse for tryggere nettbruk |
| SOC | Team som overvåker og beskytter IT-systemer |
| 2FA | To-faktor autentisering for ekstra sikkerhet ved innlogging |
| Backup | Sikkerhetskopi av data som kan gjenopprettes |
| Vulnerability | Sårbarhet eller svakhet i et system |
| Exploit | Metode for å utnytte en sårbarhet |
| CVE | ID-system for kjente sikkerhetshull |
| DDoS | Angrep som overbelaster en nettside med trafikk |
| HTTPS | Sikker og kryptert forbindelse mellom bruker og nettside |
| SSL/TLS | Teknologi som krypterer data på internett |
| SOC | Security Operations Center – overvåker sikkerhet |
| API | System som lar programmer kommunisere med hverandre |
| IoT | Enheter koblet til internett (smart devices) |
| Shodan | Søkemotor for internett-tilkoblede enheter |
| Censys | Søkemotor for internett-systemer og sikkerhetsdata |
| VirusTotal | Verktøy som sjekker filer og lenker for virus |
| Have I Been Pwned | Sjekker om e-post/passord er lekket |
| Apache | Webserver som viser nettsider |
| Lighttpd | Lett og rask webserver |
| dirb | Verktøy som finner skjulte mapper på nettsider |
| DevSecOps | Integrering av sikkerhet i utvikling og drift |

---

##  Refleksjon

Gjennom arbeidet med TryHackMe har jeg lært mye nytt om cybersikkerhet og hvordan ulike systemer og angrep faktisk fungerer i praksis. Jeg har fått en bedre forståelse av hva cybersikkerhet er, og forskjellen mellom offensiv og defensiv sikkerhet.

Offensiv sikkerhet handler om å teste systemer ved å prøve å finne svakheter, mens defensiv sikkerhet handler om å beskytte systemer mot angrep. Dette har gjort at jeg forstår hvordan både angripere og forsvar jobber i cybersikkerhet.

Jeg har også fått prøve ulike oppgaver i praksis, som har hjulpet meg å forstå teorien bedre. Det å jobbe praktisk gjorde læringen mer interessant og lettere å huske.

I tillegg har jeg lært mange nye begreper og verktøy som brukes innen cybersikkerhet, og jeg ser nå bedre hvordan dette brukes i ekte IT-systemer.

Videre ønsker jeg å fortsette med TryHackMe på fritiden for å utvikle kunnskapen min enda mer, spesielt innen sikkerhet og praktisk hacking/penetrasjonstesting.
