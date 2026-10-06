# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G105 – G105-strand |
| **Product brief** | Ingen product brief funnet på main per 2026-10-06 (siste commit `3b99ba4`, «Initialiser gruppeprosjekt for IBE160») |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Det finnes ingen product brief å vurdere ennå. Lag den før dere går videre til PRD og arkitektur.

Vi fant ingen product brief, proposal eller annen prosjektbeskrivelse på main-grenen i repoet per 2026-10-06. Repoet inneholder bare README og .gitignore fra opprettelsen, og README sier ikke noe om hvilken app dere planlegger. Det er derfor ikke mulig å gi en foreløpig vurdering av vanskelighetsgrad eller gjennomførbarhet. Har dere en brief liggende lokalt eller på en annen gren, bør den committes og pushes til main så snart som mulig.

## Hvorfor product brief er viktig for mappen

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen (applikasjon og prosess, 70 %) vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app. Prosess og KI-styring er det kriteriet som teller mest (30 %), og der ser sensor etter planleggingsdokumenter som faktisk er brukt og oppdatert, og en historikk som viser jevn utvikling over tid. Del 1 vurderes også på om appen gjør det dere har beskrevet, om den er testet mot tydelige kriterier, og om den kan kjøres etter README. Uten en brief mangler alt dette et felles utgangspunkt, og det blir vanskeligere å vise en sporbar prosess. Det er mye enklere å starte riktig nå enn sent i semesteret.

## Hva briefen bør inneholde

Følg BMAD-flyten (product brief → PRD → arkitektur → epics og stories), og bruk gjerne BMAD sin product brief-arbeidsflyt i Claude Code. Faglærers eksempelprosjekt viser hvordan en brief og den videre flyten kan se ut: https://github.com/IBE160-2026/beergame. Briefen bør dekke disse delene:

| Del av brief | Hva den bør svare på |
|---|---|
| Executive Summary | Hva er appen, hvem er den for, og hvilket problem løser den – på noen få setninger. |
| The Problem | Et konkret problem med reelle situasjoner og brukere, gjerne med et eksempel. |
| The Solution | Hva brukeren gjør og opplever i appen, steg for steg – ikke bare hvilken teknologi dere skal bruke. |
| What Makes This Different | En ærlig vurdering av hva som finnes fra før, og hva som skiller deres løsning ut. |
| Who This Serves | Én tydelig primærbruker og hva den trenger. «Alle» er ingen målgruppe. |
| Success Criteria | Kriterier som kan sjekkes eller testes, for eksempel «en bruker kan registrere X og se det i oversikten». |
| Scope | Hva som er med i første versjon («In for v1»), og hva som bevisst er utelatt («Explicitly out»). |
| Vision | Hvor appen kan gå videre, uten at det blåser opp omfanget for v1. |

I tillegg bør briefen eller et vedlegg inneholde en begrunnet vurdering av **vanskelighetsgrad og gjennomførbarhet**:

- **Vanskelighetsgrad:** Sammenlign idéen med forslagslista «Prosjektforslag for IBE160 Programmering med KI». Enkel er for eksempel 1) AI Study Buddy, 6) To-do-liste med smarte etiketter og 8) Foredragsnotater – sammendrag og quizgenerator. Middels er for eksempel 2) AI CV- og søknadsassistent og 7) Kurs-FAQ-chatbot. Vanskelig er for eksempel 3) KI-styrt simulering av prosjektledelse, 4) KI-støttet MRP II og 5) KI-styrt sensurering. Et enkelt prosjekt gir stor sjanse for å bli ferdig, men krever mer i gjennomføringen for å nå helt opp. Et vanskelig prosjekt gir større mulighet, men også større risiko.
- **Gjennomførbarhet:** Kan første versjon bli ferdig og testet i løpet av semesteret, med tid til hele BMAD-flyten? Kan dere selv kontrollere at koden Claude Code lager, gir riktige svar? Kan sensor kjøre appen lokalt etter README uten deres nøkler eller betalte kontoer – for eksempel med testmodus hvis appen bruker en språkmodell?

Siden gruppen består av én person, bør dere velge et omfang som realistisk kan bli ferdig og stabilt av én person, med én tydelig kjerneflyt som kan beskrives i 3–5 steg.

## Neste steg for gruppen

1. Velg prosjektidé, gjerne fra forslagslista eller en egen idé med tilsvarende omfang, og skriv en product brief med delene over. Legg den i repoet (for eksempel under `_bmad-output/planning-artifacts/briefs/`) og push til main.
2. Ta med en kort, begrunnet vurdering av vanskelighetsgrad og gjennomførbarhet, med et sammenlignbart forslag fra lista og en plan for hvordan sensor kan kjøre appen.
3. Gå videre til PRD og arkitektur med BMAD når briefen er på plass, og commit underveis slik at historikken viser hvordan planen utvikler seg.

Oppdater product brief i repoet når dere har gjort endringene, slik at historikken viser hvordan planen utviklet seg. Det er en del av prosessen sensor ser etter.
