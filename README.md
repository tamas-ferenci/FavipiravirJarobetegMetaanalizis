Járóbetegeknél alkalmazott favipiravir kezelés hatásosságára vonatkozó
meta-analízis
================
Ferenci Tamás

## Bevezető gondolatok, motiváció

A favipiravir hatásosságára vonatkozóan számtalan primer tanulmány, és –
ebből fakadóan – ma már jónéhány meta-analízis is elérhető. Ezek azonban
túlnyomórészt kórházban ápolt betegekre vonatkozó eredményeket
tartalmaznak. Jóval kevesebb eredmény van fennjáró betegek kezelésének
hatásosságáról, meta-analízis pedig – legjobb tudomásom szerint, nyilván
a primer eredmények kis száma miatt is – egyáltalán nem készült. Ez
azért is fontos téma, mert a mai magyar helyzetben a járóbetegek
kezelése az igazán releváns kérdés.

Jelen tanulmányban egy rendkívül gyorsan összerakott, nem komoly
tudományos igénnyel készült [irodalmi áttekintést és
meta-analízist](https://tamas-ferenci.github.io/FerenciTamas_AKlinikaiGyogyszervizsgalatokAlapjai/n%C3%A9h%C3%A1ny-tov%C3%A1bbi-t%C3%A9mak%C3%B6r-a-gy%C3%B3gyszervizsg%C3%A1latok-t%C3%A9m%C3%A1j%C3%A1b%C3%B3l.html#a-bizony%C3%ADt%C3%A9kok-%C3%B6sszess%C3%A9ge-szeml%C3%A9let)
adok erre a kérdésre.

## Tanulmányok rövid bemutatása, alkalmasság meta-analízisre

### Irodalmi áttekintés

Egy – nagyjából – szisztematikus reviewt végeztem: a
[PubMed](https://pubmed.ncbi.nlm.nih.gov/?term=favipiravir%20outpatient)-et
és a
[medRxiv](https://www.medrxiv.org/search/favipiravir%252Boutpatient)-ot
kerestem végig, mindkettőt a favipiravir + outpatient
keresőkifejezéssel, egyéb szűkítés nélkül. Előbbi 19 találatot adott,
közte 2 megfelelővel, utóbbi 48 találatot, közte 1 relevánssal.

A felkutatott tanulmányok:

-   Bosaeed 2022: Mohammad Bosaeed, Ahmad Alharbi, Ebrahim Mahmoud, et
    al. Efficacy of favipiravir in adults with mild COVID-19: a
    randomized, double-blind, multicentre, placebo-controlled clinical
    trial. Clin Microbiol Infect. 2022 Jan 11;S1198-743X(21)00734-5.
    doi: 10.1016/j.cmi.2021.12.026.
    [Link](https://www.clinicalmicrobiologyandinfection.com/article/S1198-743X(21)00734-5/fulltext).
-   Holubar 2021: Marisa Holubar, Aruna Subramanian, Natasha Purington.
    Favipiravir for treatment of outpatients with asymptomatic or
    uncomplicated COVID-19: a double-blind randomized,
    placebo-controlled, phase 2 trial. medRxiv. doi:
    10.1101/2021.11.22.21266690.
    [Link](https://www.medrxiv.org/content/10.1101/2021.11.22.21266690v1).
-   Ruzhentsova 2021: Tatiana A Ruzhentsova, Rodion A Oseshnyuk, Tatyana
    N Soluyanova, et al. Phase 3 trial of coronavir (favipiravir) in
    patients with mild to moderate COVID-19. Am J Transl Res. 2021 Nov
    15;13(11):12575-12587. eCollection 2021.
    [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8661194/).

Az utóbbi tanulmány egyszerre tartalmazott járó- és fekvőbetegeket, de
szerencsére a számunkra kritikus eredményeket külön-külön is közölte,
így felhasználható a mostani meta-analízisben.

### Végpontok összevethetősége

Az első kérdés, hogy a tanulmányok ugyanazt, vagy legalábbis kellően
hasonló végpontot néztek-e.

Ebben szerencsénk van: minden tanulmány pontosan ugyanazt a két
végpontot nézte: a vírusürítés megszűnéséig eltelő időt (“time to viral
clearence”) és a klinikai javulás bekövetkezéséig eltelő időt (“time to
clinical improvement”).

A konkrét definíciók is meglehetősen hasonlóak voltak. A vírusürítés
megszűnéséig eltelő idő:

| Tanulmány        | Definíció                                                                                                       |
|------------------|-----------------------------------------------------------------------------------------------------------------|
| Bosaeed 2022     | conversion of SARS-CoV-2 RT-PCR results from positive to negative within 15 days as described in procedures     |
| Holubar 2021     | first of two consecutive negative nasal RT-PCRs                                                                 |
| Ruzhentsova 2021 | the absence of SARS-CoV-2 virus according to PCR in two consecutive swabs with an interval of at least 24 hours |

A klinikai javulás bekövetkezéséig eltelő idő is nagyon hasonló, a
Ruzhentsova 2021 kivételével:

| Tanulmány        | Definíció                                                                                                                                      |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| Bosaeed 2022     | normalization of fever and respiratory symptoms and relief of cough (or other relevant symptoms at enrolment) maintained for at least 72 hours |
| Holubar 2021     | first of two consecutive days without symptoms                                                                                                 |
| Ruzhentsova 2021 | a reduction of patient clinical status on at least 1 score according to WHO 8-Category Ordinal Scale compared to screening                     |

Módszertani szempontból is szerencsénk van: minden tanulmány eltelt
időként kezelte mindkét végpontot, és mindegyik hazárdhányadossal (HR)
mérte le a kezelés hatását.

Ebből a szempontból tehát lehetséges meta-analízis készítése.

### Kutatások jellegének összevethetősége, a bevont betegcsoportok hasonlósága

Fontos kérdés az is, hogy a kutatások alapvető elrendezése, a
kutatásokban résztvevő betegek nagyjából hasonlóak legyenek. Ez fontos a
betegek jellemzőin túl az időpontra és a helyszínre nézve is (hiszen
eltérő lehet térben és időben a járványhelyzet, az éppen cirkuláló
variáns).

E szempontokról a következőek mondhatóak el:

|            | Bosaeed 2022                                                                                                                                                                                                                                                                                 | Holubar 2021                                                                                                                                 | Ruzhentsova 2021                                                                                                                                                                                                                                                                  |
|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Elrendezés | Randomizált, kettős vak                                                                                                                                                                                                                                                                      | Randomizált, kettős vak                                                                                                                      | Randomizált, open label                                                                                                                                                                                                                                                           |
| Dózis      | 1800 mg twice daily as a loading dose on day 1 followed by 800 mg twice daily as a maintenance dose for a total duration of 5 to 7 days of therapy                                                                                                                                           | 1800 mg BID on Day 1, then 800 mg BID on days 2-10                                                                                           | a loading dose of 1800 mg BID on Day 1, followed by 800 mg BID on Days 2-10                                                                                                                                                                                                       |
| Dátum      | Between July 23, 2020 and August 4, 2021                                                                                                                                                                                                                                                     | From July 8, 2020 through March 23, 2021                                                                                                     | Between May 23, 2020 and June 30, 2020                                                                                                                                                                                                                                            |
| Helyszín   | seven community medical<br>centres and ambulatory care centres in Saudi Arabia                                                                                                                                                                                                               | Stanford Healthcare, California                                                                                                              | Oroszország                                                                                                                                                                                                                                                                       |
| Betegek    | mild COVID-19 (confirmed by positive PCR test for SARS-CoV-2); they were enrolled within 5 days of disease onset. Mild COVID-19 was defined as mild illness (with or without respiratory symptoms) with oxygen saturation \>94% on room air and management at home with appropriate therapy. | asymptomatic or symptomatic adults without respiratory distress who had a positive SARS-CoV-2 RT-PCR collected within 72 hours of enrollment | had a diagnosis of mild to moderate COVID-19 without respiratory failure; with symptom manifestation no more than 6 days before the randomization; with SARS-CoV-2 confirmed by PCR of oro- or nasopharyngeal swabs, and had received no previous antiviral therapy for COVID-19. |

Látszik, hogy nagyjából jó a megfelelés; egy kivétellel, ami semmiképp
nem hanyagolható el: Ruzhentsova 2021 [aktív
kontrollt](https://tamas-ferenci.github.io/FerenciTamas_AKlinikaiGyogyszervizsgalatokAlapjai/a-kontroll%C3%A1l%C3%A1s-k%C3%A9rd%C3%A9sei.html#a-kontrollcsoport-megv%C3%A1laszt%C3%A1sa-akt%C3%ADv-kontroll)
(standard ellátás) használt, míg a másik két tanulmány
[placebo-kontrollos](https://tamas-ferenci.github.io/FerenciTamas_AKlinikaiGyogyszervizsgalatokAlapjai/a-kontroll%C3%A1l%C3%A1s-k%C3%A9rd%C3%A9sei.html#placeb%C3%B3hat%C3%A1s-kezeletlen-%C3%A9s-placebo-kontroll-a-kezel%C3%A9s-maszkol%C3%A1sa)
volt. Ez mindenképp szükségessé tesz egy alcsoport-analízist.

Nézzük az egyes betegcsoportok jellemzőit:

|                                              | Bosaeed 2022 | Bosaeed 2022 | Holubar 2021 | Holubar 2021 | Ruzhentsova 2021 | Ruzhentsova 2021 |
|----------------------------------------------|--------------|--------------|--------------|--------------|------------------|------------------|
|                                              | Favipiravir  | Placebo      | Favipiravir  | Placebo      | Favipiravir      | Standard of care |
| Nő                                           | 40 (35.7)    | 36 (30.2)    | 28 (47.5)    | 29 (50.9)    | 63 (56.2%)       | 26 (46.4%)       |
| Életkor                                      | 37 (31.5-45) | 36 (32-4)    | 42.9 (12.3)  | 43.4 (12.8)  | 41.7 (10.6)      | 41.7 (10.6)      |
| Time from symptoms onset to<br>randomization | 3 (2-4)      | 3 (2-4)      | 5 \[3-7\]    | 5 \[4-6\]    | 3.5 (1.4)        | 3.6 (1.4)        |
| Hypertonia                                   | 8 (5)        | 6 (7)        | 5 (8.5)      | 5 (8.8)      | ?                | ?                |
| Diabetes                                     | 15 (13.4)    | 10 (8.4)     | 7 (11.9)     | 3 (5.3)      | ?                | ?                |
| Chr. tüdő                                    | 1 (0.8)      | 1 (0.8)      | 2 (3.4)      | 3 (5.3)      | ?                | ?                |

Látszik, hogy nagyjából elfogadható a hasonlóság.

### Adatok extrakciója

A mostani elemzésben felhasznált konkrét számok, azok cikkbeli
forrásával együtt:

| Tanulmány        | Végpont                      | URL                                                                                                                                        | Forrás    | HR    | CI alsó széle | CI felső széle | nT  | nC  |
|------------------|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|-----------|-------|---------------|----------------|-----|-----|
| Bosaeed 2022     | Time to viral clearance      | <https://www.clinicalmicrobiologyandinfection.com/article/S1198-743X(21)00734-5/fulltext>                                                  | Figure 2  | 0,87  | 0,571         | 1,326          | 112 | 119 |
| Bosaeed 2022     | Time to clinical improvement | <https://www.clinicalmicrobiologyandinfection.com/cms/10.1016/j.cmi.2021.12.026/attachment/b21e8fdc-a521-4d8c-a134-80620a0af4ef/mmc2.docx> | Figure S1 | 0,894 | 0,639         | 1,25           | 112 | 119 |
| Holubar 2021     | Time to viral clearance      | <https://www.medrxiv.org/content/10.1101/2021.11.22.21266690v1.full.pdf>                                                                   | Table 2   | 0,76  | 0,48          | 1,2            | 59  | 57  |
| Holubar 2021     | Time to clinical improvement | <https://www.medrxiv.org/content/10.1101/2021.11.22.21266690v1.full.pdf>                                                                   | Table 2   | 0,84  | 0,54          | 1,29           | 65  | 70  |
| Ruzhentsova 2021 | Time to viral clearance      | <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8661194/pdf/ajtr0013-12575.pdf>                                                              | Table 2   | 1,11  | 0,76          | 1,61           | 83  | 44  |
| Ruzhentsova 2021 | Time to clinical improvement | <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8661194/pdf/ajtr0013-12575.pdf>                                                              | Table 2   | 1,65  | 1,08          | 2,52           | 83  | 44  |

## Módszertani és számítástechnikai részletek

Hazárdhányadosok analízise célszerűen log-skálán
[történhet](https://training.cochrane.org/handbook/current/chapter-06#section-6-1-2-1).
A pontbecslés egyszerűen logaritmálható, a standard hiba meghatározása
nem nehéz feladat, ha a konfidenciaintervallumot közölték a cikkek,
ahogy az jelen esetben történt ([Tierney et al,
2007](https://trialsjournal.biomedcentral.com/articles/10.1186/1745-6215-8-16)).
Megfelelő szoftvercsomaggal azonban erre sem lesz szükség.

Az analízist `R` statisztikai környezet alatt, a `meta` csomag
használatával végezzük. Töltsük be a szükséges csomagot és olvassuk be
az adatokat (a nyers adatokat külön is [elérhetővé
tettem](https://raw.githubusercontent.com/tamas-ferenci/FavipiravirJarobetegMetaanalizis/main/FavipiravirOutpatientMeta.csv)):

``` r
library(meta)

RawData <- read.csv2("FavipiravirOutpatientMeta.csv")
```

Ezt követően elvégezhetjük mindkét végpontra a meta-analízist:

``` r
mViral <- metagen(log(HR), lower = log(CIlwr), upper = log(CIupr), studlab = Study,
              n.e = nT, n.c = nC, data = RawData[RawData$Outcome=="Time to viral clearance",],
              subgroup = Subgroup, sm = "HR")
mClinical <- metagen(log(HR), lower = log(CIlwr), upper = log(CIupr), studlab = Study,
              n.e = nT, n.c = nC,
              data = RawData[RawData$Outcome=="Time to clinical improvement",],
              subgroup = Subgroup, sm = "HR")
```

Mint látható, a standard hibát nem számoltuk kézzel, egyszerűen átadtuk
a konfidenciaintervallumot (log-skálán), innen már mindent számolt a
`meta` csomag.

## Eredmények

A vírusürítés megszűnéséig eltelő időre vonatkozó meta-analízis
eredménye:

``` r
forest(mViral)
```

![](README_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

A klinikai javulás bekövetkezéséig eltelő időre vonatkozó meta-analízis
eredménye:

``` r
forest(mClinical)
```

![](README_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

## Diszkusszió

A vírusürítés megszűnéséig eltelő idő tekintetében nincs lényeges
heterogenitás, és a két alcsoport sem tér el egymástól szignifikánsan.
Az eredmény szerint a favipiravir ront a helyzeten (HR = 0.93), de nem
szignifikáns mértékben (95% CI: 0,73–1.18). A klinikai javulás
bekövetkezéséig eltelő idő esetében a két alcsoport már inkább eltér, de
az összesített eredmény szerint a favipiravir hat ugyan (HR = 1.07), ám
ez sem szignifikáns (95% CI: 0.71–1.61).

*A favipiravirnak egyetlen végpontra sem sikerült szignifikáns hatását
igazolni.*

Fontos: ne felejtsük el a ‘bizonyíték hiánya nem a hiány bizonyítéka’
[elvet](https://tamas-ferenci.github.io/FerenciTamas_AKlinikaiGyogyszervizsgalatokAlapjai/a-v%C3%A9letlen-ingadoz%C3%A1s-k%C3%A9rd%C3%A9sk%C3%B6re.html#a-kutat%C3%A1s-ereje-%C3%A9s-mintanagys%C3%A1ga)!
Különösen a klinikai javulás esetében elég széles a
konfidenciaintervallum, így még egy jelentékenyebb javítást (és persze
egy komolyabb rontást) sem tudunk kizárni.

## Továbbfejlesztési ötletek

-   Érdekes lehetne egy bayes-i reanalízis elvégzése (tekintettel az
    utolsóként említett kérdéskörre).
