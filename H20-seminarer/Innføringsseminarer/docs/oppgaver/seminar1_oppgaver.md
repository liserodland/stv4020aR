Oppgaver seminar 1
================

### Oppgaver fra dagens tema:

Bruk datasettet vi lastet ned i slutten av av forrige seminar.
Datasettet inneholder informasjon om passasjerer på Titanic.

1.  Hvilke variabler finnes i datasettet?
2.  Hvilken klasse er variablene?
3.  Hvor mange observasjoner er det i datasettet?
4.  Var det flest menn eller kvinner på Titanic?
5.  Hva er gjenomsnittsalderen for menn som var på Titanic? (Tips:
    kombiner mean() med det vi har lært om indeksering)
6.  Lag en logisk test for om den eldeste mannen på Titanic var yngre
    enn den eldste kvinnen.
7.  Hent ut passasjerene som er eldre enn 70 år. Lagre observasjonene
    som et objekt. Hvor mange var det?
8.  Hva forteller funksjonen is.na() oss?
9.  Hvor mange missing er det på aldersvariabelen? (Tips: kombiner
    table() med is.na())
10. Lag et datasett som bare inneholder observasjoner av de som gikk om
    bord i Queenstown (de som har verdien Q på variabelen Embarked).
    (Tips: kombiner \<- med det vi har lært om indeksering)

### Oppgaver om morgendagens tema:

11. Lag en ny variabel som har verdien 1 dersom passasjeren er eldre enn
    gjennomsnittet og 0 ellers. Lagre den i Titanic datasettet.
12. Lag en ny variabel som er Age opphøyd i annen.
13. Kjør en OLS-regresjon med Survived som avhengig variabel og Pclass,
    Sex og Age som uavhengige variabler.
