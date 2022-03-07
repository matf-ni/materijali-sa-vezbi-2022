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
| 10 | Retke matrice - formati zapisa, bibliotečka podrška i primer primene u sistemima pretraživanja informacija |
| 11 | Dekompozicije matrica - LU, Čoleski i SVD dekompozicije, kompresija slika, sistemi preporuka i predikcija nedostajućih vrednosti |
| 12 | Optimizacija - bibliotečka podrška u problemima optimizacije sa i bez ograničenja; lokalna pretraga |
| 13 | Modelovanje optimizacionih problema korišćenjem Pyomo biblioteke |


Za pristup sveskama koje koristimo na času pogledajte `live` granu.

# Video lekcije
|Nedelja | Link |
|:--------|:------|
| 1 | [čas 01](https://matf.webex.com/matf/ldr.php?RCID=77b8de77f069847a8cc244a63b0a4161)
| 2 | [čas 02](https://matf.webex.com/matf/ldr.php?RCID=416cf5a4b54193ceb407d5340d7f0fe7)
| 3 | [čas 03](https://matf.webex.com/matf/ldr.php?RCID=e09595b957bad1d6e97e7101ad735e7c)

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
