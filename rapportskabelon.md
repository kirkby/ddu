# Rapportskabelon for DDU

**Indledning**. Ikke to projekter er ens. Forskellige produkter giver forskellige udviklingsforløb. Der er naturligvis forskel på at udarbejde en app (software), en arduino-baseret robot eller en fuldautomatisk pantautomat. Det vil sige at denne skabelon tjener som inspiration og et solidt udgangspunkt - men man slipper ikke for at bruge sin egen sunde fornuft og kritiske sans.

Som udgangspunkt indeholder en tekniksfagsrapport i DDU følgende kapitler:
- [Projektbeskrivelse](#kapitel-projektbeskrivelse)  med problemformulering
- [Problemanalyse](#problemanalyse)
- [Konceptudvikling](#kapitel-konceptudvikling)
- [Forproduktion](#kapitel-forproduktion) (prototyping) 
- [Implementering](#kapitel-implementering) 
- [Test](#kapitel-test)
- [Præsentation](#kapitel-præsentation)
- [Konklusion og evaluering](#kapitel-konklusion-og-evaluering)
- [Bilag](#kapitel-bilag)

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

## Kapitel: Implementering
Beskrivelse følger.

## Kapitel: Præsentation 
Dette kapitel indeholder en visuel præsentation af det færdige produkt. Videoer kan inddrages (kort og redigerede!).

## Kapitel: Test
Beskrivelse følger.

## Kapitel: Konklusion og evaluering
Beskrivelse følger.

## Bilag
Bilag er ikke kapitler og følger ikke den fortløbende nummerering.
Mere beskrivelse følger.
