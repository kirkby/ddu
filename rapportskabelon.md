# Rapportskabelon for DDU

**Indledning**. Ikke to projekter er ens. Forskellige produkter giver forskellige udviklingsforløb. Der er naturligvis forskel på at udarbejde en app (software), en arduino-baseret robot eller en fuldautomatisk pantautomat. Det vil sige at denne skabelon tjener som inspiration og et solidt udgangspunkt - men man slipper ikke for at bruge sin egen sunde fornuft og kritiske sans.

Som udgangspunkt indeholder en tekniksfagsrapport i DDU følgende kapitler:
- [Projektbeskrivelse](#kapitel-projektbeskrivelse)  med problemformulering
- [Problemanalyse](#kapitel-problemanalyse)
- [Konceptudvikling](#kapitel-konceptudvikling)
- [Forproduktion](#kapitel-forproduktion) (prototyping) 
- [Implementering](#kapitel-implementering) 
- [Test](#kapitel-test)
- [Præsentation](#kapitel-præsentation)
- [Konklusion og evaluering](#kapitel-konklusion-og-evaluering)
- [Bilag](#bilag)

Disse kapitler svarer nogenlunde til produktudviklingens faser i en simpel verden.  
Projektbeskrivelse &rarr; Konceptudvikling &rarr; Implementering &rarr; Test &rarr; Lancering   

Det er som sagt _udgangspunktet_. 
Afhængig af forløbets længde, projektets kompleksitet eller aftaler med læreren kan der afviges fra denne skabelon.

Nedenfor beskrives rapportens udstyr og kapitler i den _anbefalede_ rækkefølge.  
Husk at kapitler altid begynder på en ny side.

## Forsiden          
Rapporten skal have en forside med   
- Titel   
- Billede af produkt 
- Navne
- Fag, skolens navn og årstal
 
## Titelbladet 
Bagsiden af forsiden kan med fordel anvendes til et såkaldt _titelblad_. 
Her samles **al** praktisk information om rapporten og projektet.
- Rapportens titel
- Fag og vejleder
- Dato
- Evt. nøgleord 
- Evt. resume af opgaven (abstract)
- Fulde navne, hold og årgang
- Skolens navn og årstal

## Indholdsfortegnelsen
Dernæst følger en indholdsfortegnelse.   
Indholdsfortegnelsen skal indeholde sidenumre og være aktiv - henvisningerne skal være links. 
Forsøg at ramme en balanceret struktur og niveauinddeling med højest 2, måske 3 niveauer.

 Her følger et eksempel som inspiration - men det er ikke one-size-fits-all.

```
1. Projektbeskrivelse  
1.1 Indledning  
1.2 Problemformulering med tekniske spørgsmål  
1.3 Projektstyring
1.4 Afgrænsning

2. Problemanalyse  
2.1 Analyse af teknisk spørgsmål 1  
2.2 Analyse af teknisk spørgsmål 2  
2.3 Analyse af teknisk spørgsmål 3  
2.4 Opsamling på delkonklusioner  

3. Konceptualisering  
3.1 Regler
3.2 Design
3.3 Interaktion 

4. Forproduktion
4.1 Rutediagrammer
4.2 Tekniske tegninger
4.3 Prototyper

5. Implementering

6. Test
6.1 Testtype
6.2 Planlægning og udførsel
6.3 Resultater
6.3 Konklusioner og evaluering

7. Præsentation af produkt

8. Konklusion og evaluering  

Bilag A Kode
Bilag B Testresultater
```

## Kapitel: Projektbeskrivelse
Dette kapitel sætter scenen for det projekt som I skal i gang med. 

### Indledning
Det er en god ide at begynde med en _indledning_. Her introduceres den fysiske og teoretiske virkelighed som projektet befinder sig i - hvem, hvad, hvor - og alle de forudsætninger som læseren skal kende til for at forstå de følgende kapitler. 

Den centrale ide i projektet gennemgåes og bekrives kort og konkret med den viden man har på det tidspunkt.

Når læseren har læst dette afsnit, har hun en god ide om hvad hele handler om.

### Problemformulering
Herefter opstilles en problemformulering. Den indfanger kort og præcist hvilket problem som man forsøger at løse.  
Det er vigtigt at en problemformulering er _åben men afgrænsende_. Den afgrænser de ydre rammer, men stiller sig nysgerrig over for hvilke beslutninger der skal træffes undervejs.
En typisk problemformulering er på formen 

> "Hvordan kan vi **bygge-skabe-udvikle-implementere** en/et **produkt-spil-app** som kan **løse problem A-forbedre løsning B-underholde målgruppe C** ved hjælp af **teknologi X-metode-Y-princip-Z**"

Ovenstående eksempel tjener selvfølgelig kun som inspiration. Den skal ikke kopieres 1:1.

### Tekniske spørgsmål
Herefter opstiller man en række spørgsmål som skal besvares for at opgaven kan løses, de såkaldte tekniske underspørgsmål.

De tekniske spørgsmål skal identificere de tekniske udfordringer som skal løses hvis produktet skal komme i mål. 

De tager udgangspunkt i projektbeskrivelsen og problemformuleringen og _nedbryder_ disse i helt konkrete problemstillinger.  

Termen "teknisk" skal forstås bredt - det betyder i denne sammenhæng først og fremmest at der lægges vægt på en videnskabelig, faktabaseret analyse af disse spørgsmål. Så i den henseende kan et teknisk spørgsmål sagtens handle om målgrupper eller interaktiondesign.  

### Afgrænsning
I afgrænsningen kan man på forhånd afgrænse sit problemfelt. Det er nogle gange nødvendigt at forsimple den virkelighed som man forholder sig til. Dette afsnit tillader gruppen at definere visse aspekter af problemfeltet som man ikke vil arbejde med eller inddrage i sit projekt.  
Eksempel: Man vil lave et spil med en topscorerliste, men man har i første omgang ikke planer om at implementere multi-player mode. Så topscorerlisten viser altid den samme spiller.

## Kapitel: Problemanalyse
I problemanalysen analyseres de opstillede spørgsmål fra projektbeskrivelsen.
Det nemmeste er at behandle hvert spørgsmål i sit eget afsnit eller underkapitel.
Har man 5 spørgsmål, får man altså fem afsnit. 

I disse afsnit analyseres problemet med hjælp af de gængse videnskabelige metoder som man har lært. Videnskabelige artikler, feltstudier, online-research, sammenligning, test osv. 

Hvert afsnit rundes af med en _delkonklusion_ - en opsummering af resultaterne af analysen i dette afsnit.

Den _samlede_ problemanalyse rundes af med en sammenfatning af alle delkonklusionerne.

Denne sammenfatning beskriver overordnet _konsekvenserne_ af analyseresultaterne - hvilken betydning har de for teknologivalget/produktet/implementeringen osv. 

Altså - analysen viste det og det, og det betyder at vi har valgt den og den løsning.

## Kapitel: Konceptudvikling
I dette kapitel skal den beskrevne idé finpudses til et _koncept_. Det betyder groft sagt at man udarbejder og fastlægger på detajleniveau produktets endelig design, udformning og funktion. Hvis det er et brætspil eller et computerspil, fastlægges også hhv. reglerne og gameplayet.

## Kapitel: Forproduktion
Kaldes også Prototyper (prototyping).
Beskrivelse følger.

## Kapitel: Implementering
Beskrivelse følger.

## Kapitel: Præsentation 
Dette kapitel indeholder en visuel præsentation af det færdige produkt. Videoer kan inddrages (hvis de er klippede og redigerede!).

## Kapitel: Test
Beskrivelse følger.

## Kapitel: Konklusion og evaluering
I konklusionen skal man "vende tilbage". Man skal vende tilbage til forlægget (den stillede opgave), problemformuleringen og en evt. kravspecifikation og reflektere over "hvordan gik det så?".
Kort sagt: 
> reflekter over jeres resultater ved at forholde jer til udgangspunktet

Udgangspunktet er som sagt opgaven, problemformuleringen, analysen, kravspecificationen osv.
Her kommer testresultaterne i spil. For alt andet end meget trivielle systemer er det vanskeligt at skrive en troværdig konklusion hvis man ikke har nogle testresultater til at understøtte sine konklusioner med. Det er som regel ikke nok at skrive at "det virkede som forventet". Konklusioner skal som udgangspunkt baseres på en metodisk, systematisk afprøvning eller test.

## Bilag
De enkelte bilag er normalt "nummereret" med store bogstaver, A, B, C osv.
Ligesom kapitler begynder bilag øverst på en ny side.
Det er vigtigt at beskrive hvad de enkelte bilag indeholder.   

Eksempel:

> BILAG A. Testdata
> Her følger i fuld længde alle testresultater fra vores produkttest.  
> Testen blev udført den 10/10 af XX (observatør), YY (video) og ZZ (testleder) i lokale 73 på Slotshaven Gymnasium.
> Testpersoner var 10 tilfældigt udvalgte elever fra 2.g.

I bilagene anbringes dokumentation der er for omfattende til at indgå i selve rapporten.  
Eksempler kan være:   
- kvalitative interviews
- testresultater i fuldt omfang
- kildekode
- tekniske illustration og diagrammer i fuld størrelse

# Appendiks A. Gode råd om rapportskrivning
Her følger i stikordsform nogle formelle krav og venlige anbefalinger til hvordan man skriver en god rapport i DDU.

## Formidling og videnskabelighed
Brug: 
 - Korrekte og præcise fagtermer  
 - Sagligt, fagligt sprog
 - Konkrete eksempler 
 - Relevante citater 
 - Oplysende illustrationer med forklaringer

Alt dette for at underbygge din argumention og gøre den troværdig. 
 
Brug ikke:
 - værdiladede, personlige vurderinger eller synspunkter

Brug gerne:
 - korte introduktioner når du begynder nyt emne
 - korte afrundinger før du skifter emne

For at hjælpe læseren.

## Kilder
Husk: 
 - Referencer på alle teori, teser, påstande og argumenter 
 - Kildehenvisninger på alt eksternt materiale  

Det trækker ned _hver eneste gang_ man ikke gør det.

## Korrekturlæsning
God ide.

En tekst der er korrekturlæst, har højere troværdighed.

## Den iterative udvikling 
Hvor er den iterative udvikling henne i dette? Det er vanskeligt at udtrykke den iterative udviklingproces i en rapportstruktur. Det er derfor vigtigt at man fremhæver og beskriver denne proces i sin dokumentation af projektet i de enkelte kapitler. 

Det kan man fx gøre ved at dokumentere hvordan man undervejs har ændret sit design eller implementering efter et testfund har vist at den oprindelige løsning ikke virkede.  

# Appendiks B. Projektstyring og nedbrydning af opgaver
Her følger et par noter om hvordan man beskriver og nedbryder opgaver.
En opgave skal i det følgende forstås som det samme som et card i Trello.

## Nedbrydning af opgaver
Når man er færdig med sin projektbeskrivelse og problemformuleringen, har man i princippet den opgave der skal løses - nemlig "gør det som der står i beskrivelsen".

Hvis man fx skulle lave et unity-spil og en tilhørende rapport, kunne man begynde med at opstille disse opgaver: 

(1) Lav spil  
(2) Skriv rapport

Det er dog for bredt og løst og umuligt at arbejde med. Vi har brug for at at bryde den samlede opgave ned og identificere alle de delopgaver som "gemmer" sig i den samlede opgave.

Så det man har brug for, når man begynder på et nyt projekt og forsøger at danne sig et overblik, er _opgavenedbrydning_. 

Hvad vil det sige? Det vil sige at man forsøger at definere alle de _delopgaver_ som man kan identificere, man _nedbryder_ altså den store opgave i en række små opgaver. 
Ideen kendes fra princippet om hvordan man spiser en elefant - hvilket ikke er så svært: "En bid ad gangen".

Hvad er den rigtige størrelse på en opgave - hvordan nedbryder man? Her er et par forslag. 

**Varighed.** Først og fremmest skal en opgave have en overskuelig varighed. 
Den skal kunne løses indenfor et tidsrum hvis varighed kan estimeres nogenlunde.
Jeg foretrækker en varighed på ca. 1-2 timer.

**Kompleksitet.** 
Følger snart.

**Afgrænsning.** Opgaven skal optimalt set kunne løses uden at påvirke andre opgaver eller selv at være påvirket af andre opgaver - den skal være afgrænset. Har man fx at gøre med en to komponenter der kommunikerer, må opgaven kun påvirke den ene komponent. Består et system af flere subsystemer, må opgaven kun ligge i det ene subsystem. Subsystem er i øvrigt en oplagt kandidat for et label, fx "API", eller "Client".

**Ejerskab.** Optimalt set skal en opgave naturligt ligge hos en ejer og ikke kræve flere personers samarbejde. En opgave kan dog sagtens sendes videre til en anden ejer hvis situationen kræver det.

Der kan nævnes mange andre kriterier, men dette er en start.

## Beskrivelse af opgaver

Hvordan beskriver man en opgave? Her er nogle forslag.

**Beskrivelse.** 
Indhold. Hvad består opgaven i - hvad skal laves - giv kort præcis beskrivelse. 

Kriterier. Hvis man er rigtig flittig, beskriver man også _Acceptance Criteria_. 
Altså - hvornår kan opgaven siges at være færdig? 

Test. Og tilsidst - hvordan tester man det. Beskrivelse - trin for trin - af de skridt som man skal tage for at afgøre om opgaven er færdig.

**Kategori.** Oplagt kandidat til et label (#tag). Kategori kan være subsystem, komponent eller lignende.
Eksempler på kategorier: Database, Kode, Frontend, Interaktion, Rapport, Test osv. 

**Ejer.** Hvem skal løse opgaven?

**Estimat.** Hvor lang tid tager opgaven? 

**Vigtighed.** Need-to-have, Nice-to-have, MVP osv. Oplagt kandidat til et label.








