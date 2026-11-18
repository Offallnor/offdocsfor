# NOU 2026: 14, del 4 av 20

- Hele dokumentet med innholdsfortegnelse: dokumenter/nou/2026/ac335adc-nou-2026-14.md
- Les hele dokumentet: https://www.regjeringen.no/no/dokumenter/nou-2026-14/id3191187/
- Original-PDF: https://www.regjeringen.no/contentassets/31691eb451e941e2b75fdc346978628f/no/pdfs/nou202620260014000dddpdfs.pdf
- Tekst: fra Word-fil lastet opp 2026-11-18, ikke fra PDF. Tabellene er med. Figurer er bare med som titler, så tall som bare finnes i en figur, må leses i originalen.

---

# Kunstig intelligente systemer

## Innledning

Dette kapittelet redegjør kort for kunstig intelligens (KI) som teknologi- og forskningsfelt. I kapittel 3.2 gis det et kort historisk riss, etterfulgt av definisjoner av KI i kapittel 3.3. I kapittel 3.4 presenteres ulike former for KI, fulgt av en nærmere redegjørelse for hvordan KI-systemer er bygget opp og en beskrivelse av ulike lag av teknologier som inngår i et kunstig intelligent system – teknologistabelen. Kapittelet avrundes med en omtale av trekk ved utviklingen av teknologi- og forskningsfeltet som utvalget mener er viktige for den videre diskusjonen i utredningen.

## Bakgrunn

KI tok for alvor plass i allmennhetens bevissthet i november 2022, med lanseringen av ChatGPT. Det ble da raskt klart at store språkmodeller kunne få betydelige konsekvenser for utdanning og arbeidsliv. For eksempel viser Studiebarometeret 2025 at andelen studenter som *ikke* bruker denne typen KI-systemer som en del av studiene er mindre enn 10 prosent.

Språkmodellene ble etter hvert utvidet til grunnmodeller (*foundation models*), som har de samme språklige kapabilitetene, men i stedet for å være begrenset til bare språk, fungerer på flere datatyper og -modaliteter. Selv om det er språk- og grunnmodeller som har fått størst plass i samfunnsdebatten i første halvdel av 2020-tallet, har kunstig intelligens en rik historie som fagfelt, og KI-teknologi er ikke begrenset til generativ eller språkbasert funksjonalitet.

Det som gjerne regnes som det tidligste arbeidet i fagfeltet er fra 1943, av McCulloch og Pitts (Russel & Norvig, 2022). Betegnelsen «kunstig intelligens» stammer fra et seminar ved Dartmouth College i 1956, hvor ti forskere var samlet i to måneder for å utforske utvikling av intelligente maskiner. Etter en periode med stor interesse for fagfeltet og betydelig finansiering, førte manglende resultater til at finansieringen tørket opp, og vi gikk inn i en «KI-vinter» på 1970-tallet. Kunstig intelligens fikk et oppsving igjen på 1980-tallet, denne gang med regelbaserte systemer (se kap. 3.4). Nok en gang overgikk forventningene hva feltet klarte å levere, og en ny KI-vinter satte inn på slutten av 1980-tallet og videre inn på 1990-tallet.

Grunnteknikken for å trene nevrale nettverk, tilbakepropagering, ble etablert på 1970- og 1980-tallet, men gjennom 1990- og 2000-tallet var nevrale nettverk fremdeles en marginal retning innenfor KI. Gjennombruddet kom tidlig på 2010-tallet, da metodeutvikling, kraftigere maskinvare, grafikkort og store datamengder samlet gjorde det mulig å trene dagens nevrale nettverk. I 2012 viste nevrale nettverk seg som klart overlegne tradisjonelle metoder for storskala bildeklassifisering (LeCun et al., 2015). Siden da har teknikken hatt fremgang på andre datatyper, som språk, og gitt fremgang innen flere anvendelsesområder, som medisinsk diagnose og værprognoser.

## Hva er et kunstig intelligent system?

En tilnærming til å definere kunstig intelligens er å beskrive *hva* KI-systemer kan gjøre. For eksempel beskriver UNESCO maskiner basert på KI som «potensielt i stand til å imitere, eller til og med overgå, menneskelige kognitive kapasiteter, inkludert sansing, språklig interaksjon, resonnering og analyse, problemløsing og endog kreativitet. Videre, slike ‘intelligente maskiner’ kan fremvise menneskelignende evne til å lære med mekanismer som selv-relasjon og selvkorreksjon, basert på algoritmer som utgjør ‘maskinlæring’ eller til og med ‘dyplæring’ som benytter ‘nevrale nettverk’ som etterligner virkemåten til den menneskelige hjernen» (COMEST, 2019).

En annen tilnærming til å definere kunstig intelligens er å vektlegge *hvordan* KI-systemer fungerer, som for eksempel i KI-forordningen (se Boks 3.1).

Definisjon av KI i KI-forordningen

«Et sentralt kjennetegn ved KI-systemer er deres evne til å trekke slutninger. Med denne evnen til å trekke slutninger menes prosessen med å generere utdata, for eksempel prediksjoner, innhold, anbefalinger eller beslutninger, som kan påvirke fysiske og virtuelle miljøer \[…\] Blant de teknikkene som muliggjør utledning under oppbyggingen av et KI-system, er maskinlæringstilnærminger som på grunnlag av data lærer hvordan bestemte mål best kan nås, og logikk- og kunnskapsbaserte tilnærminger som trekker slutninger på grunnlag av kodet kunnskap eller symbolsk representasjon av oppgaven som skal løses»

Kilde: KI-forordningen, avsnitt 12

\[Boks slutt\]

I den nasjonale strategien for KI fra 2020 er KI-systemer forstått som systemer som «utfører handlinger, fysisk eller digitalt, basert på tolkning og behandling av strukturerte eller ustrukturerte data, i den hensikt å oppnå et gitt mål. Enkelte KI-systemer kan også tilpasse seg gjennom å analysere og ta hensyn til hvordan tidligere handlinger har påvirket omgivelsene» (Kommunal- og moderniseringsdepartementet, 2020).

## Ulike former for kunstig intelligens

Det finnes mange ulike typer KI-systemer, og mange måter å dele dem inn på. Vi kan blant annet skille mellom regelstyrte og datadrevne KI-systemer, og mellom spesialisert og allmenn KI. Vi kan også skille mellom prediktive og generative KI-systemer, og mellom assisterende og agentiske systemer. Skillelinjene er ikke krystallklare, men ved å trekke dem kan vi få en bedre forståelse av hvilket mangfold av KI-systemer som finnes.

### Regelstyrt kontra datadrevet

Innenfor fagfeltet kunstig intelligens skilles det grovt mellom regelbaserte modeller og datadrevne modeller. Regelbaserte modeller benyttes eksempelvis i ekspertsystemer, hvor atferden til dataprogrammet bestemmes av forhåndsdefinerte regler. Ekspertsystemer brukes ofte på spesialiserte fagområder som er regelbundne og forutsigbare, som noen typer medisinsk diagnostikk eller oljeboring (Rossen et al., 2024), eller detaljerte, styrte juridiske områder (Ashley, 2017). KI-utviklingen har gradvis blitt dominert av datadrevne modeller, hvor reglene ikke er forhåndsdefinerte, men læres gjennom en databasert optimaliseringsprosess som identifiserer statistiske mønstre. Dette kalles maskinlæring. Eksempler på datadrevne modeller er store språkmodeller og ansiktsgjenkjenningsmodeller.

Regelstyrte og datadrevne modeller er ikke gjensidig utelukkende kategorier. Beslutningstrær har lenge vært i utstrakt bruk, og disse lager eksplisitte regler gjennom trening på data. Det utvikles også hybride modeller som kombinerer eksplisitte regler med databasert optimalisering (Garcez & Lamb, 2023). Nyere forskning innen kognitiv vitenskap og kunstig intelligens har vist at systemer som integrerer maskinlæring og automatisert resonnering har potensial innen flere områder, inkludert beregningsbiologi, feildiagnostikk, opplæring og vurdering i simulatorer, og programvareverifikasjon (Besold et al., 2017)**.**

Moderne nevrale nettverk er datastrukturer bestående av flere lag, også omtalt som *dype* nevrale nettverk. Treningen av dype nevrale nettverk omtales kollektivt som dyplæring, og deles inn i følgende tre regimer: Veiledet læring, hvor riktig svar er eksplisitt tilgjengelig i dataene, som ved diagnostikk. Uveiledet læring, hvor riktig svar ikke er angitt i dataene og hensikten er å finne mønstre og unntak, som i avviksdeteksjon. Forsterkende læring, hvor modellen selv innhenter treningsdata og dens atferd derfor avgjør hva den trenes på, som i sjakkmodeller. Dype nevrale nettverk trenger generelt store datamengder for å bli funksjonelle (Tidemann, 2023).

### Allmenn kontra spesialisert

En KI-modell til allmenne formål er ikke trent opp for å løse én type oppgave godt, men har mange ulike bruksområder. Store språkmodeller og grunnmodeller er eksempler på dette. Systemer som bygger på slike modeller, som samtaleroboter og agentiske systemer, har ikke klart forhåndsdefinerte bruksområder, og kan regnes som KI-systemer til allmenne formål (Bengio et al., 2026).

Spesialiserte KI-systemer er utviklet for bestemte formål eller bruksområder, og er trent på data og metoder direkte knyttet til enkeltdomener. Eksempler på spesialiserte KI-systemer er bildemodeller for klassifisering av røntgenbilder eller modeller for transkribering av tale til tekst. Spesialiserte KI-systemer fungerer bare innenfor sitt domene, mens allmenne KI-systemer kan utføre et bredt spekter av oppgaver. Forskjellen på KI-modeller til allmenne formål og spesialiserte KI-systemer, med de ulike formålene de kan tjene, er avgjørende for hvordan systemene er regulert i KI-forordningen, jf. kapittel 4.3.2.

### Prediktiv kontra generativ

Prediktiv KI benytter maskinlæring for å analysere mønstre i store datasett for å gi en forutsigelse av et eller annet slag, f.eks. om sannsynligheten for en fremtidig hendelse eller for at et gitt objekt tilhører en gitt kategori (Pratschke, 2024). Prediktive KI-systemer kan brukes til mange ulike formål, for eksempel til å lage værprognoser, til kredittvurdering innenfor finans, til klassifisering av bilder eller til å identifisere søppelpost. De benyttes i anbefalingssystemer på sosiale medier, og i utdanningssammenheng til tilpasning av læringsinnhold, hjelp til valg av fag, anbefaling av læringsressurser, gruppesammensetninger og andre typer persontilpassede digitale tjenester (NOU 2023: 19).

Generativ KI skaper nytt innhold, basert på data modellen er trent på og instruksjoner fra brukeren (Lorenz et al., 2023). Generative KI-systemer kan generere nye instanser fra en hvilken som helst datatype, inkludert tekst, tale, musikk, illustrasjoner, bilder, video og programkode. Et viktig særtrekk ved KI-generert innhold er at det kan være vanskelig, og i prinsippet umulig, å skille det fra innhold skapt av mennesker.

### Assisterende kontra agentisk

Assisterende KI-systemer, som de prediktive systemene omtalt ovenfor, gir resultater som direkte respons på instrukser, og handler ikke på eget initiativ. Det samme gjelder en samtalerobot isolert sett. Agentiske KI-systemer handler autonomt, og skiller seg fra andre KI-systemer ved at de kan operere uten oppsyn fra mennesker. KI-agenter er laget for å forfølge mål, ofte spesifisert av brukere i naturlig språk.

En agent er noen eller noe som handler, og en programvare-agent skal kunne handle autonomt, oppfatte omgivelsene sine, tilpasse seg endring, bestå over tid, og den må kunne skape og forfølge mål (Russel & Norvig, 2022). KI-agenter kan gis tilgang til internett, samt ressurser som databaser og intranett, og gis adgang til å håndtere filer og kjøre programkode på datamaskiner (Bengio et al., 2026). Et multiagentsystem består av flere agenter som samhandler for å nå egne eller felles mål (Wooldridge, 2009).

## Hvordan er et kunstig intelligent system bygget opp?

Et viktig element i utviklingen av KI-systemer er hvordan data blir representert på en måte som gjør at KI-modellen kan utføre beregninger på dem. Det er mange ulike typer representasjonsformer, men med gjennombruddet av dyplæring har vektor-representasjoner (*embeddings*) blitt sentrale (Mikolov et al., 2013)[^9].

Et nevralt nettverk kan forstås som et stort sett med beregningsenheter satt sammen på en bestemt måte. Måten nettverket er satt sammen på kaller man for nettverkets arkitektur, og angår hvilke beregninger som gjøres i hvilken rekkefølge. Et utvalg viktige nettverksarkitekturer er kort beskrevet i Boks 3.2.

Nettverksarkitekturer

Dagens store språkmodeller er laget med *transformer-arkitekturen* (Vaswani et al., 2017), som er spesielt egnet for bearbeiding av naturlig språk. GPT, som i ChatGPT, er en transformer-modell. En viktig egenskap ved denne arkitekturen er at den benytter oppmerksomhetsmekanismer for å modellere hvordan meningen i en tekst er fordelt over tekstens bestanddeler.

I 2012 kom en kraftig forbedring i utviklingen av maskinsyn, med *konvolusjonelle nevrale nettverk* (basert på LeCun et al., 1989; LeCun et al., 1998). Denne arkitekturen gjorde det mulig å redusere mengden treningsdata som skal til for at et program skal kunne klassifisere eller identifisere objekter i bilder, og benyttes for eksempel til ansiktsgjenkjenning eller i analyse av røntgenbilder.

*Autokodere* (Hinton & Salakhutdinov, 2006) er utformet for å lære seg å effektivt representere datasett, og er mye brukt for å finne underliggende mønstre eller uregelmessigheter i data – som for å avdekke økonomisk svindel, i datasikkerhet og i medisinsk diagnostikk.

En annen arkitektur som også benyttes til blant annet bildegenerering, er *diffusjonsmodeller* (Ho et al., 2020; Sohl-Dickstein et al., 2015). Disse modellene er trent på store mengder bilder som gradvis er tilført mer og mer støy, til bildene er helt ødelagt. Den ferdig trente modellen jobber motsatt vei – den starter med ren støy som fjernes den gradvis i mange omganger frem til man står igjen med et ferdig bilde.

\[Boks slutt\]

Størrelsen eller kompleksiteten til et nevralt nettverk måles som regel i antall parametre. Parametre i maskinlæringsmodeller er numeriske verdier som optimaliseres for at modellen skal oppnå målet sitt, omtalt som «trening». Parametrene avgjør modellens tolkning av inndata og oppførsel. Jo flere parametre en modell har, jo mer treningsdata og regnekraft kreves generelt for å optimalisere parametrene. Empirisk klarer modeller med mange parametre (i kortform omtalt som «store modeller») å utføre flere oppgaver og å utføre de samme oppgavene med et bedre resultat enn modeller med få parametre (Maslej et al., 2025). For eksempel er kvaliteten på samtaleroboter som benytter GPT-4, med sine anslagsvis 1,8 billioner parametre, typisk bedre enn de som benytter GPT-3 med sine 175 milliarder parametere. Sammenhengen mellom antall parametre og ytelse er likevel ikke entydig. Mer effektive arkitekturer og treningsmetoder har gjort at modeller med få parametre i dag løser oppgaver som tidligere krevde svært mange parametre (f.eks. DeepSeek).

Det kreves betydelige ressurser for å utvikle store språk- og grunnmodeller, især regnekraft og datamengder. Det er derfor et begrenset antall aktører som har kapasitet til å lage de mest kapable modellene. I sin oversikt over det de kaller fremtredende (*notable*) KI-modeller, viser *The AI Index 2026 Annual Report* at det er en klar overvekt av modeller fra USA og Kina, og nær ingen konkurransedyktige fra Europa (Sajadieh et al., 2026). Det er dermed en betydelig konsentrasjon av teknologisk makt, både i form av at det er få selskaper som utvikler de mest kapable modellene, og i form av at det er få stater som har jurisdiksjon over modellutviklerne. Denne maktkonsentrasjonen er ytterligere forsterket av maktkonsentrasjon også i andre deler av teknologistabelen (jf. kap. 3.6). Sammen med at det er blitt økt geopolitisk spenning i verden, har dette bidratt til å aktualisere problemstillinger knyttet til digital suverenitet, jf. kap. 8.5.1.

De store språkmodellene er trent på store mengder tekstdata fra bl.a. internett, gjennom uveiledet læring. Etter en slik grunntrening kan modellen ettertrenes og finjusteres (oppdatering av modellens parametre), gjerne ved hjelp av tilbakemeldinger fra mennesker, ved trening på et mindre utvalg av spesialiserte tekster, eller ved sammenlikning med eksakte svar for oppgaver i for eksempel matematikk. Dette er illustrert i Figur 3.1 (Bengio et al., 2026):

- *Datainnsamling og -kuratering:* Før språkmodellen trenes, samles det inn store mengder rådata som renses, kurateres og standardiseres slik at de kan formateres til bruk i trening.

- *Grunntrening:* I dette første steget i treningen, hvor datasettet fra forrige steg benyttes, eksponeres modellene for millioner eller milliarder av eksempler av innhold som tekst eller bilder. Modellene lærer seg mønstre i datasettet, abstrakte egenskaper ved dataene og hvordan de henger sammen. Denne prosessen krever mye regnekraft, og tar uker eller måneder å gjennomføre. Grunntreningen kan også omtales som forhåndstrening.

- *Ettertrening og finjustering:* KI-modellen som er utviklet under grunntreningen, kan optimaliseres for spesifikke bruksområder gjennom finjustering, eller videreutvikles for lengre resonnementer eller multiagent-bruk gjennom forsterkende læring. Overvåket finjustering ved hjelp av mindre, annoterte datasett kan forbedre modellens ytelse innenfor bestemte områder, for eksempel norsk språk eller norske lovtekster. Ettertrening med forsterkende læring har blitt mer viktig og krever vel så mye regnekapasitet som grunntreningen og betydelig manuelt arbeid med dataklargjøring og merking.

- *Systemintegrasjon:* Utviklere setter sammen en eller flere KI-modeller med andre komponenter for å skape et anvendelig KI-system.

- *Idriftsetting:* KI-systemet gjøres tilgjengelig for bruk, for en virksomhets eller organisasjons interne brukere, for eksterne kunder, eller for allmennheten.

- *Overvåking og oppdatering:* Etter at KI-systemet er tatt i bruk, kan utviklere samle data fra bruk og tilbakemelding fra brukere, og benytte dette til å gjøre iterative forbedringer på systemet. Forbedringene gjøres ved å oppdatere systemintegrasjon, ofte gjennom kontinuerlig fintrening eller kontrollerte treningsforløp på oppdaterte treningsdata.

Det er viktig å påpeke at de siste tre elementene involverer testing, verifisering og validering. Før systemet tas i bruk, og fortløpende etterpå, undersøkes det om modellen og systemet fungerer slik de er spesifisert (verifisering), og om de er egnet for det bruksområdet de er tiltenkt (validering). Dette skjer blant annet gjennom standardiserte tester, systematisk leting etter svakheter og utprøving med brukere. Testresultater gir imidlertid ikke alltid et pålitelig bilde av hvordan systemet oppfører seg i praktisk bruk.

Trinn i utviklingen av en stor språkmodell

Utvalgets oversettelse og reproduksjon av figur fra Bengio m.fl.

Kilde: Bengio et al. (2026)

## Teknologistabel for generativ kunstig intelligens

En teknologistabel er et sett av maskin- og programvarer som samlet utgjør en plattform som et dataprogram trenger for å fungere. Komponentene i en teknologistabel vil typisk være utviklet av ulike leverandører, uavhengig av hverandre. Overordnet og forenklet fremstilt vil en teknologistabel for generativ KI inneholde tre lag, vist i Figur 3.2: infrastruktur, modell og applikasjon.

- *Infrastruktur*: Laget består av maskinvare for databehandling og -lagring, inkludert prosessorer, minnebrikker og datanettverk, som typisk blir gjort tilgjengelig på en sky-plattform som Microsoft Azure, Amazon Web Services eller Google Cloud.

- *Modell*: I dette laget finner vi grunnmodellene, de store nevrale nettverkene trent på store datamengder i den fasen som kalles forhåndstrening. Grunnmodellene er generelle modeller, som så forbedres eller spesialtilpasses gjennom ettertrening. Eksempler på grunnmodeller er store språkmodeller som GPT og Llama, eller modeller for bildegenerering som Stable Diffusion.

- *Applikasjon:* I dette øverste laget i teknologistabelen er de programmene og tjenestene som brukerne benytter seg av. Applikasjonslaget er det som forbinder brukerne med de store og komplekse KI-modellene. Eksempler på applikasjoner er velkjente samtaleroboter som ChatGPT eller Claude, agentiske systemer som OpenClaw, Claude Code og Codex, samtaleroboter for kundestøtte som IKEAs Billie, eller bedriftsinterne systemer til bruk i for eksempel kundeanalyser.

Forenklet teknologistabel for KI

Figuren viser en overordnet og forenklet teknologistabel. Det finnes mange ulike varianter, avhengig av hvilke typer KI-arbeid man gjør, ofte med flere lag enn de tre som er vist her. For eksempel kan man dele infrastrukturlaget i maskinvare for regnekraft og skyplattformer, eller modell-laget i grunnmodeller og finjusterte modeller, og man kan legge til et lag eller to for data og dataforvaltning.

## Utviklingstrekk

Hva kan et kunstig intelligent system gjøre? Den tekniske utviklingen går raskt, og det å identifisere rekkevidden av KI-kapabiliteter er et arbeid som krever kontinuerlig oppdatering. OECD har laget et utkast til et rammeverk for å måle hva kunstig intelligens og robotikk får til, og sammenligne disse med menneskelige ferdigheter (OECD, 2025c). Metodikken har blitt utviklet for å gi beslutningstakere et evidensbasert verktøy for å vurdere utviklingen innen KI på en måte som er lett å forstå for personer uten teknisk bakgrunn. Rammeverket vil oppdateres systematisk, slik at man kan følge med på utviklingen i KI-kapabiliteter.

Rammeverket består av ni indikatorer som dekker et spenn av menneskelige evner, hvor hver enkelt indikator beskriver utviklingen av KI-systemer mot full ekvivalens med menneskelige ferdigheter. Indikatorene er språk; sosial interaksjon; problemløsing; kreativitet; metakognisjon og kritisk tenkning; kunnskap, læring og hukommelse; synsevne; fysisk håndtering av gjenstander; og robotikk-intelligens. Indikatorene vurderes på en skala fra en til fem, hvor de evnene som er mest utfordrende for et KI-system har høyest verdi. I den foreløpige vurderingen kommer alle kategoriene med en verdi på to eller tre. For eksempel er indikatoren metakognisjon og kritisk tenkning vurdert til å være på nivå to: «KI-systemer overvåker sin egen forståelse og justerer sine tilnærminger tilsvarende. De arbeider med kjent informasjon som kan inneholde flertydighet, noe som krever avpasset sikkerhet og informerte gjetninger. De kan håndtere delvis ufullstendig informasjon ved å skille mellom hva de vet og hva de ikke vet» (OECD, 2025c, s. 13).

Et tydelig utviklingstrekk er at de generative KI-systemene blir i stand til å gjøre stadig mer, og med bedre kvalitet, i kraft av tekniske innovasjoner og større tilgang på data og regnekraft. Figur 3.3 viser hvordan de mest fremtredende grunnmodellene over tid har prestert bedre på en bred kapabilitetsindeks, *Epoch Capabilities Index*.

Indeksert kapabilitetsutvikling for fremtredende grunnmodeller, 2023–2026

Indeksen består av over 50 uavhengige målinger, blant annet innenfor matematikk, programmering, faktakunnskap, vitenskapelig kunnskap, spill, læringsevne og evne til å selvstendig utføre økonomisk verdifulle arbeidsoppgaver. Til forskjell fra OECDs rammeverk kombinerer denne indeksen de mange målingene i én «generell kapabilitet»-verdi. En høyere verdi betyr at modellen er mer kapabel.

Kilde: Tilpasset fra Epoch AI (2026c). Lisens: CC-BY.

Rapporten *The International AI Safety Report*, utarbeidet av ledende KI-forskere, slår fast at KI-systemer til allmenne formål kan utføre et stort utvalg av godt avgrensede oppgaver med høy grad av kyndighet (Bengio et al., 2026), jf. kap. 3.4.2. Dette inkluderer å kunne føre dialog på mange språk flytende, lage kode for å utføre avgrensede programmeringsoppgaver, lage realistiske bilder og korte videoer, og å kunne løse matematiske og vitenskapelige problemer på høyere grads nivå. Men de påpeker også at fronten av KI-utviklingen er ujevn; at det er mange oppgaver KI-systemer ikke løser på en god måte. Eksempler på dette er at de forsetter å dikte opp ting og saksforhold (hallusinering) eller at de fremdeles ikke er godt nok integrert med robotikk-komponenter til å utføre enkle husholdningsoppgaver.

Begrepet *the jagged frontier of AI ability* ble introdusert av Dell’Acqua og kollegaer i 2023 (Dell’Acqua et al., 2023) for å beskrive fenomenet at KI-systemer kan gjøre noe arbeid utrolig godt og annet utrolig dårlig, på måter som ikke passer godt inn i vår menneskelige intuisjon om hva som er enkelt og hva som er vanskelig. Figur 3.4 illustrerer denne ujevne utviklingsfronten, hvor utvikling over tid skisseres i tre stadier og de lyserøde områdene representerer KI-kapabilitet sammenlignet med menneskelig evne, vist i blått.

Den ujevne utviklingsfronten av KI-systemer

Utvalgets reproduksjon av Pueyo (2025)

Kilde: (Pueyo, 2025)

Toneangivende fagmiljøer i næringslivet, som Anthropic, OpenAI og Google DeepMind, signaliserer at de arbeider aktivt med systemer som kan forbedre seg selv. Ved lanseringen av en ny versjon av det agentiske KI-systemet Codex i februar 2026, uttalte OpenAI at dette bidro vesentlig til GPTs egen utvikling. KI-systemer som er gode på å programmere og på KI-relatert forskning, kan benyttes til å utvikle neste generasjons modeller. Dette kalles rekursiv selvforbedring, og kan føre til en markert økning i utviklingshastighet (Kwa et al., 2025). Det er likevel langt fra sikkert hvor stor betydning rekursiv selvforbedring vil ha. En mulighet er at man utvikler kunstig superintelligens (Bostrom, 2014), KI-systemer som i betydelig grad overgår menneskers kognitive prestasjoner på praktisk talt alle relevante områder (se f.eks. Morris et al., 2025). Men en slik utvikling kan begrenses av tilgang til data, regnekraft eller modellenes innovasjonsevne.

Globalt brukes det enorme summer på kunstig intelligens. Figur 3.5, hentet fra *The 2026 AI Index Report*, viser utviklingen i private investeringer i KI globalt for perioden 2013–25 (Sajadieh et al., 2026). Av totalen på 344,7 milliarder amerikanske dollar i 2025 utgjorde investeringer i selskaper som lager generativ KI 170,9 milliarder dollar, noe som er en økning på over 200 prosent fra 2024. Merk at oversikten ikke inneholder statlige investeringer. Som et eksempel estimerer man i rapporten at Kina investerte 184 milliarder amerikanske dollar i KI-selskaper i perioden mellom 2000 og 2023, gjennom statlige investeringsfond (Sajadieh et al., 2026, s. 184).

Private investeringer i KI globalt, 2013–25

Diagrammet viser beløp i milliarder amerikanske dollar.

Kilde: The 2026 AI Index Report (Sajadieh et al., 2026)

Det er en betydelig geografisk konsentrasjon av kapital, kompetanse og datasentre med de mest avanserte databrikkene, som er helt sentrale innsatsfaktorer i utvikling av de fremtredende grunnmodellene. Utfordringer knyttet til dette diskuteres i kapittel 8 om forvaltning av KI-systemer.

I flere tiår har man forsket på KI både i akademia og i næringslivet. Men etter at dyplæring har blitt den ledende teknologien, har næringslivet i økende grad dominert forskningsfeltet. Dette er illustrert i Figur 3.6, som viser hvilken sektor forskningsgrupper som utvikler fremtredende KI-systemer tilhører.

Sektortilknytning for forskningsgrupper som utvikler fremtredende KI-systemer, etter publiseringsår

Utvalgets oversetting og tilrettelegging av data fra Epoch AI.

Kilde: (Epoch AI, 2026b)

Miserocchi et al. (2026) har studert konkurransen om KI-forskere i arbeidsmarkedet mellom næringsliv og akademia, og dokumenterer en stor reallokering av KI-forskere mot de fremste teknologiselskapene mellom 2005 og 2020. Ahmed et al. (2023) har undersøkt forfatternes sektor-tilknytning på artikler til ledende KI-konferanser, og finner at andelen artikler med minst én forfatter fra næringslivet viser en skarp økning fra 2016, fra ca. 20 prosent til ca. 40 prosent. Dermed har næringslivet i økende grad kommet til å dominere alle de tre nøkkelingrediensene i moderne KI-forskning og KI-utvikling: regnekraft, store datasett og høyt kvalifiserte forskere. Dette gir utslag i forskningsresultater: Næringslivet har større innflytelse på akademiske publikasjoner, de ledende modellene og på referansepunkt for ytelse (Ahmed et al., 2023). Utviklingen har fortsatt etter 2020. I 2025 sto næringslivet for over 90 prosent av de mest betydningsfulle KI-modellene, og de mest kapable modellene er også de minst åpne når det gjelder treningsdata, kode og størrelse (Sajadieh et al., 2026). Et flertall av nye KI-doktorer går fortsatt til næringslivet, men andelen i USA og Canada som velger akademia, har økt noe siden 2022 (Sajadieh et al., 2026, kap. 7).

Tall fra Statistisk sentralbyrås undersøkelse om den samlede ressursbruken til forskning og utviklingsarbeid (FoU) i Norge gir indikasjoner på forholdene nasjonalt (Statistisk sentralbyrå, 2025a). Innenfor kategorien «Kunstig intelligens, maskinlæring og maskinresonnering» ble det i 2023 brukt totalt 4 515 millioner kroner på FoU-utgifter, FoU-personale og FoU-årsverk. 73 prosent av dette beløpet ble brukt i næringslivet, 19 prosent i universitets- og høyskolesektoren og 8 prosent i instituttsektoren.

Resonnerende modeller (Wei et al., 2022) har stått for flere av de seneste gjennombruddene i hva KI-systemer kan gjøre. For eksempel har de gjort det mulig å produsere avanserte matematiske og logiske bevis, jf. kap. 5.6.2. Resonnerende modeller er i stand til å bryte opp komplekse oppgaver i mindre steg, som så løses sekvensielt, og kan deretter sammenholde ulike løsninger før de gir endelige svar. Denne typen modeller krever mer beregningsressurser enn tidligere KI-modeller både når de kjøres og når de trenes.

Et annet utviklingstrekk er at KI-agenter (jf. kap. 3.4.4) i økende grad er i stand til å gjøre nyttig arbeid. For eksempel har KI-agenter vist evne til å fullføre en rekke oppgaver innenfor programvareutvikling under begrenset tilsyn av mennesker. 2025 ble av mange utpekt som «agentenes år», og selv om de høyeste forventningene ikke ble oppfylt, slår 2025-utgaven av den velrennomerte *AI Index Report* fra Stanford University fast at KI-agenter viser lovende ytelse (Maslej et al., 2025).

OECD har skissert fire hovedscenarioer for KI-utviklingen frem mot 2030 (Hobbs et al., 2026), basert på vurderinger av kapabilitetsindikatorene nevnt i starten av dette delkapittelet. De fire scenarioene spenner fra at utviklingen stanser opp og kapabilitetene blir værende på dagens nivå fremover, til at utviklingen akselerer og fremskrittene kommer enda raskere enn de har gjort de siste fem årene. Dette siste scenarioet rommer også muligheten for såkalt kunstig generell intelligens, der kapabilitetene er på nivå med menneskelige evner på de fleste arbeidsområder, eller superintelligens, der kapabilitetene langt overgår det som er mulig for mennesker. Mellom disse ytterpunktene er det i OECD sin analyse to nivåer, der utviklingen går videre, men saktere eller i samme tempo som nå. Innenfor hvert av de fire scenarioene kan det være variasjoner i utviklingstakten mellom ulike kapabiliteter, som språk, syn og fysisk interaksjon. For eksempel kan utviklingen tenkes å gå raskere innen maskinsyn (systemenes evne til å tolke visuell informasjon i bilder og video) enn når det gjelder evnen til å håndtere fysiske objekter.

Overordnet peker OECD på flere usikkerhetsmomenter knyttet til utviklingen videre. Tilgang på data, beregningskapasitet, samt energi og vann til drift av datasentre er kritiske faktorer. Fortsatt skalering av KI-modellene vil kreve store investeringer, mens det er usikkert om en slik skalering vil gi tilstrekkelig økonomisk avkastning til at investeringene opprettholdes. Forbedringer av algoritmene kan øke ytelsen betydelig, men forutsetningene for dette er usikre. Bruk av KI i programmering kan akselerere utviklingen av KI-systemer, men akkurat hvor sterk effekten av dette vil være, er usikkert.

*The Government Office for Science* i Storbritannia legger i sine scenarier for KI i 2030 (2026) til grunn at KI-kapabiliteter vil fortsette å øke. De mener at KI-systemer trolig vil operere langt mer selvstendig og kunne utføre et bredere spekter av kognitive og faglige oppgaver innen 2030.

I tillegg til den teknologiske utviklingen kan en rekke andre kulturelle, sosiale, økonomiske og institusjonelle faktorer virke inn på hvilken retning og hastighet utviklingen tar. Det kan handle om politiske beslutninger, regulering, eierskap og styringsstrukturer, utbredelse av KI-systemer i befolkningen og endringer i opinionen. Men det kan også handle om faktorer vi per nå ikke kjenner eller forstår.

Vi kan derfor ikke legge til grunn én bestemt beskrivelse av teknologiutviklingen, men må ta høyde for en stor grad av usikkerhet. Samtidig kan vi fastslå at kapabilitetene som allerede er oppnådd, er tilstrekkelige til å medføre betydelige endringer på flere områder, og at disse endringene uansett vil få større betydning i tiden som kommer.

# Grunnleggende problemstillinger og juridiske rammer for utvikling og bruk av kunstig intelligens

## Innledning

Fremskrittene innenfor kunstig intelligens (KI) og den raske utbredelsen av teknologien har åpnet store muligheter på en rekke samfunnsområder. Bedrifter, organisasjoner, offentlige myndigheter og enkeltpersoner finner stadig nye bruksområder der KI-systemer kan automatisere arbeidsoppgaver, gi bedre tilgang til informasjon, utvikle nye løsninger eller gi forbedringer i kvalitet og effektivitet.

KI-støttet forskning kan bidra til nye vitenskapelige gjennombrudd, økt innovasjon og verdiskapning, og løsninger på globale samfunnsutfordringer som klimaendringer og smittsomme sykdommer (OECD, 2023a). KI-systemer kan også spille en viktig rolle i krisehåndtering og humanitær hjelp (FN, u.å.).

Utvikling og bruk av KI-systemer reiser på den annen side mange problemstillinger. Problemstillingene oppstår delvis på grunn av hvordan kunstig intelligente systemer blir utviklet, med store datasett som kan inneholde åndsverk, personopplysninger og historiske skjevheter. Det har også å gjøre med hvor komplekse og ressurskrevende beregninger systemene utfører, der vi ikke enkelt kan forstå hvordan de kommer frem til resultatene de gjør, eller hva et system identifiserer som effektive metoder for å oppnå de målene det er trent for. Som maktmiddel reiser KI-teknologien også strategiske problemstillinger, blant annet om hva slags løsninger vi kan gjøre oss avhengige av og hva slags løsninger vi skal ha kontroll over, samt hvordan den påvirker vår kognisjon og adferd. I tillegg til slike etiske og strategiske vurderinger må utvikling og bruk av KI-systemer forholde seg til både nye og etablerte lover og regler.

Flere av de etiske problemstillingene og juridiske rammene som beskrives her, vil også bli løftet frem i andre kapitler. Utvalget ser dem likevel som såpass viktige for en kritisk og reflektert tilnærming til KI at vi har valgt å synliggjøre dem i et eget kapittel. Kunnskap om denne typen problemstillinger vil være viktig både for ansatte i universitets- og høyskolesektoren og for studentene som skal forberedes på et arbeidsliv og et samfunnsliv som er mer preget av KI.

Kapittel 4.2 beskriver en del av de grunnleggende problemstillingene som reiser seg ved utvikling og bruk av KI-systemer. Kapittel 4.3 beskriver noen av de viktigste juridiske rammene for utvikling, kjøp, salg og bruk av KI-systemer i Norge og Europa. De beskrevne problemstillingene og juridiske rammene er ikke særegne for høyere utdanning som brukskontekst, men eksempler med særlig relevans for høyere utdanning trekkes frem i beskrivelsene. Hvordan universitets- og høyskolesektoren kan forholde seg til og håndtere denne typen problemstillinger, tas opp i andre kapitler.
