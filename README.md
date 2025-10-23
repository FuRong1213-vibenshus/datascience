# data science

## Formål

- behandle og analysere datasæt ved hjælp af moderne Python-biblioteker.
- anvende NumPy til numeriske beregninger og array-manipulation.
- bruge pandas til håndtering og analyse af datasæt.
- visualisere resultater og sammenhænge med Matplotlib (og evt. SciPy til mere avancerede beregninger).
- arbejde projektorienteret med data og udvikle små, selvstændige analyser eller mini-apps.

Forløbet understøtter både programmeringsfagets formål og kompetencemål, og trækker på elevernes matematiske forståelse (funktioner, modeller, regression, eksponentiel vækst osv.).

## Indhold

I forløbet introduceres og anvendes følgende:

### Numpy og matplotlib
- Introduktion
    - `NumPy`: arrays, vektoriserede beregninger, statistiske funktioner.
    - `Matplotlib`: grafer, scatterplots, histogrammer, labels og figuropsætning.

- Øvelser
    - *computation_on_array_1.ipynb*
    - *computation_on_array_2.ipynb*

### Numpy, Scipy og Seaborn 

- `seaborn` 
- `SciPy`: (valgfrit/ekstra): fx regression, sandsynlighedsfordelinger.

### Databehandling med pandas
`pandas` er den bibliotek vi skal bruge gennem forløbet. `pandas` er et af de mest anvendte Python-biblioteker til databehandling og analyse. Vi kigger på:

- De to vigtigste datastrukturrer i `pandas`:
    - `Series`
    - `DataFrame`
- Indlæse og håndtere datasæt fra fx .csv, Excel, databaser eller API’er
- Filtrere, sortere og gruppere data efter betingelser
- Beregne statistiske mål, fx gennemsnit, median eller varians
- Visualisere resultater med fx Matplotlib eller Plotly
- Rense og transformere data, fx håndtere manglende værdier eller ændre datatyper
    - `re`(regular expression)


## Materialer

### NumPy
- [numpy_basic.ipynb](numpy_basic.ipynb)
- [computation_on_array_1.ipynb](computation_on_array_1.ipynb) 
- [computation_on_array_2.ipynb](computation_on_array_2.ipynb)
- (Supplerende læsestof) [Array programming with NumPy](https://www.nature.com/articles/s41586-020-2649-2)
### Matplotlib
- [Matplitlib tutorials](https://matplotlib.org/stable/users/explain/quick_start.html#quick-start)
- [pyplot](https://matplotlib.org/stable/tutorials/pyplot.html)
- [seaborn](https://seaborn.pydata.org/tutorial/introduction.html)
### Pandas
- [pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- data cleaning
    - [Pythonic data cleaning](https://realpython.com/python-data-cleaning-numpy-pandas/)
    - [Maternal mortality example](https://maternalmortalityexample.netlify.app/maternal_mortality.html)
### Data kilder
- [Our World in Data](https://ourworldindata.org/)
- [World Population Prospects 2024](https://population.un.org/wpp/downloads?folder=Standard%20Projections&group=Most%20used)

## Opgaver 

1. [Radioaktivt_henfald](https://classroom.github.com/a/fSm2uYTX)
2. [Moore's law](https://classroom.github.com/a/KVn_W6QB)
3. [Covid-19 data](https://classroom.github.com/a/v_typcv7)
4. [DMI data](https://classroom.github.com/a/O2WYWUSV)



## Krav til projekterne

- Alle matematiske operationer skal udføres med NumPy- eller pandas-funktioner – ikke med manuelle for/while-loops.
- Resultaterne skal visualiseres med Matplotlib.
- Til opgave 2 skal der afleveres en rapport og Projektrapporten/koden skal indeholde:
    - en kort problemformulering,
    - databehandling (import, oprensning, analyse),
    - præsentation af resultater (tabeller/grafer),
    - en kort konklusion.
