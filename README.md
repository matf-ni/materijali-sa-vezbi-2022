# Naučno izračunavanje

Ovaj repozitorijum sadrži materijale sa vežbi kursa `Naučno izračunavanje` u školskoj 2021/22. godini.

Asistent na kursu: Anđelka Zečević

Profesor: Mladen Nikolić

Zvanični sajt kursa: [http://ni.matf.bg.ac.rs/](http://ni.matf.bg.ac.rs/)

# Sadržaj časova po nedeljama

|Nedelja | Teme |
|:--------|:------|
| 1 | Uvod u programski jezik `Python` i pakete `numpy`, `pandas` i `matplotlib`|
| 2 | Rad sa vidžetima; `numpy` upravljanje memorijom |
| 3 | Srednjekvadratna aproksimacija |
| 4 | Regularizacija i odudarajući podaci |
| 5 | Furijeova transformacija - uvodni primeri za rad sa signalima, zvukom i slikama |
| 6 | Furijeova transformacija - primene u radu sa slikama |
| 7 | Furijeova transformacija - premene u radu sa signalima |
| 8 | Sopstvene vrednosti i sopstveni vektori - algoritmi izračunavanja, PCA i sopstvena lica |
| 9 | Pagerank algoritam - implementacija, podrška paketa `networkx` i primer sumarizacije dokumenata |
| 10 | Dekompozicije matrica - LU, Čoleski i SVD dekompozicije, kompresija slika, sistemi preporuka i predikcija nedostajućih vrednosti |
| 11 | Optimizacija - bibliotečka podrška u problemima optimizacije sa i bez ograničenja; lokalna pretraga |
| 12 | Modelovanje optimizacionih problema korišćenjem Pyomo biblioteke |


Za pristup sveskama koje koristimo na času pogledajte `live` granu.

# Video lekcije
|Nedelja | Link |
|:--------|:------|
| 1 | [čas 01](https://matf.webex.com/matf/ldr.php?RCID=77b8de77f069847a8cc244a63b0a4161)
| 2 | [čas 02](https://matf.webex.com/matf/ldr.php?RCID=416cf5a4b54193ceb407d5340d7f0fe7)
| 3 | [čas 03](https://matf.webex.com/matf/ldr.php?RCID=e09595b957bad1d6e97e7101ad735e7c)
| 4 | [čas 04](https://matf.webex.com/matf/ldr.php?RCID=7b6cebaf95c55aab8fb183a80fe6a904)
| 5 | [čas 05](https://matf.webex.com/matf/ldr.php?RCID=05d4e0f79cf5956f14aa4cee04798d4a)
| 6 | [čas 06](https://matf.webex.com/matf/ldr.php?RCID=39c4a805bd8ca031baf86ff9df6dcfaf)
| 8 | [čas 08](https://matf.webex.com/matf/ldr.php?RCID=83862e3f81f055307396cfd32e2135a3)
| 9 | [čas 09](https://matf.webex.com/matf/ldr.php?RCID=6af71b0779b45a2959ac9af81e377ced)
| 10 | [čas 10](https://matf.webex.com/matf/ldr.php?RCID=cc621b379876e77d5a56ef02c6869de9)
| 11| [čas 11](https://matf.webex.com/matf/ldr.php?RCID=0ce39c09ace94fbcb4d43aad5dab1220) - napomena: snimak je iz školske 2020/21. godine pa je za pristup u šifri potrebno zameniti godinu 22 sa godinom 21 
| 12| [čas 12](https://matf.webex.com/matf/ldr.php?RCID=fc3cc0a86a5de40ffcf456d6db106008)


# Tehnologije

Na kursu se koristi programski jezik `Python` i radno okruženje `Jupyter` koje omogućava kreiranje interaktivnih sveski. Osnovne funkcionalnosti jezika `Python` se upotpunjuju paketima poput `numpy` i `scipy`, ali i mnogim drugima poput `pandas`, `matplotlib` ili `PIL` koji omogućavaju lakšu manipulaciju podacima i propratne vizualizacije. Ukoliko se prvi put susrećete sa jezikom `Python`, sledeći linkovi mogu biti od pomoći:
- [zvanična stranica programskog jezika Python](https://www.python.org/)
- [stilske smernice programskog jezika Python](https://www.python.org/dev/peps/pep-0008/)
- [Real Python tutoriali](https://realpython.com/)

Za nesmetani rad je dovoljno instalirati platformu `Anaconda` koja dolazi sa velikim brojem već instaliranih paketa i `conda` sistemom za rukovanje paketima koji omogućava njihovu laku instalaciju i ažuriranje. Za preuzimanje instalacije platforme `Anaconda` možete posetiti [zvaničnu stranicu](https://www.anaconda.com/products/individual). 

Okruženje `Jupyter` dolazi kao sastavni deo platforme `Anaconda` i može se jednostavno pokrenuti navođenjem komande `jupyter notebook` u terminalu nakon pozicioniranja u željeni direktorijum za rad. Nakon ovoga će se otvoriti koreni direktorijum u veb pregledaču, najčešće na adresi koja je oblika `localhost:8888`.

Za više informacija o okruženju `Jupyter` možete pogledati [zvaničnu stranicu](https://jupyter.org/) projekta. Osnovne funkcionalnosti okruženja `Jupyter` se mogu proširiti instaliranjem odgovarajućih paketa. Predlažemo da istražite paket [jupyter_contrib_nbextensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/index.html) koji nudi neke zanimljive funkcionalnosti poput korišćenja grafičkih komponenti, formatera koda, provere pravopisa i drugih.

# Konferencije

Na godišenjm nivou zajednica koja se bavi naučnim izračunavanjem organizuje konferenciju [ScyPi conference](https://conference.scipy.org/) sa predavanjima i materijalima koji su javno dostupni. Predlažemo da istražite sajt konferencije i prateće `YouTube` kanale. Tutorijali i demo sesije su jako korisni i zanimljivi, neke primere smo pozajmili i za naš kurs. :)   

## Korsne informacije: 

U zajednici koja se bavi naučnim izračunavanjem, koriste se i alternativna radna okruženja:
- [Spyder](https://github.com/spyder-ide/spyder)
- [PyCharm](https://www.jetbrains.com/pycharm/) - može se koristiti besplatno uz Alas nalog

Python zajednica organizuje konferencije globalnog i regionalnog karaktera pod zajedničkim imenom [PyCon](https://pycon.org/). Većina materijala je javno dostupna i predstavlja sjajan resurs za učenje i usavršavanje.
