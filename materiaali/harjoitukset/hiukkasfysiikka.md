## Hiukkasfysiikan työpaja lukiolaisille

Tältä sivulta löydät lukiotasoisen esimerkkityöpajan hiukkasfysiikasta, jonka suunniteltu kesto on kokonaisuudessaan noin 2,5 h. Aiempaa tietämystä hiukkasfysiikasta tai ohjelmoinnista ei tarvita. 

Ohjeellinen rakenne ja aikataulu:

| #  |       Aktiviteetti       | Aika-arvio |
|---:|--------------------------|--------|
| 1. | Aloitus                  | 40 min |
| 2. | Työkaluihin tutustuminen | 30 min |
| 3. | Tauko                    | 10 min |
| 4. | Hiukkasfysiikan harjoitteita | 30 min |
| 5. | Lisäharjoitteita         | 40 min |

### 1. Aloitus

Live-työpajassa työpaja aloitetaan presentaatiolla CERN:istä ja hiukkastutkimuksesta. 

Mikäli paikalla ei ole esittelijää, CERN:in sivuilta löytyy myös havainnollistavia videoita aiheista. Pohjatiedoksi voi katsoa esimerkiksi miten käsitellään CERN:n Large Hadron Collider -kiihdyttimellä saatavaa dataa.
- [Datan prosessointi](https://videos.cern.ch/record/1541893) Videon kesto noin 5 minuuttia.

Tai kolmiosaisen videosarjan, jossa selitetään kuinka fyysikot oikein löytävät uusia hiukkasia, miten se tapahtuu ja mitä sillä tarkoitetaan.
- [Higgs: osa 1/3](https://www.youtube.com/watch?v=so2nCu2Jkbc) Kuinka hiukkanen luodaan laboratioriossa? Videon kesto noin 7 minuuttia.
- [Higgs: osa 2/3](https://www.youtube.com/watch?v=pW4LTunlXS4) Miten havaitaan hiukkanen, jonka elinaika on erittäin lyhyt? Videon kesto noin 7 minuuttia.
- [Higgs: osa 3/3](https://www.youtube.com/watch?v=8-WFBGCvv-w) Millä tavalla Higgsin hiukkasen olemassaolo voidaan todistaa? Videon kesto noin 13 minuuttia.

---

### 2. Työkaluihin tutustuminen

Alla esittelemme muutamia harjoituksien kannalta olennaisia työkaluja. Aiempaa kokemusta ohjelmoinnista tai hiukkasfysiikasta et tarvitse, vaan pääset alkuun helposti seuraavien tehtävien avulla:

#### Python tutorial [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Opetusmateriaalit%2FAvoinDataHiukkasfysiikassa%2F3_Data-analyysi%2F00_Python-tutorial.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Opetusmateriaalit/AvoinDataHiukkasfysiikassa/3_Data-analyysi/00_Python-tutorial.ipynb)
Harjoituksissa tarvittavat perustiedot Python ohjelmointikielen käyttöön

#### Tervetuloa Jupyter-Notebookien pariin! [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=TyokalutTutuiksi%2FTervetuloa-Jupyter-Notebookien-pariin!.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/TyokalutTutuiksi/Tervetuloa-Jupyter-Notebookien-pariin!.ipynb)

Tässä tehtävässä pääset tutustumaan muutamiin Python-ohjelmoinnin peruskomentoihin Jupyter Notebook -ympäristössä.

#### Törmäykset CMS-kokeessa [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Opetusmateriaalit%2FAvoinDataHiukkasfysiikassa%2F2_CMS-simulaatio.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Opetusmateriaalit/AvoinDataHiukkasfysiikassa/2_CMS-simulaatio.ipynb)

Kiinnostaako, miltä hiukkausten törmäykset näyttävät? Törmäykset tapahtuvat todellisuudessa niin nopeasti ja pienessä mittakaavassa, että niitä ei ole mahdollista nähdä tai valokuvata, mutta niitä voidaan mallintaa ohjelmistoilla kokeissa tallennetun datan perusteella. Yllä olevasta linkistä pääset tutkimaan hiukkasten törmäyksiä CMS-ilmasimessa kerätyn aidon datan perusteella.

#### Histogrammien vertailu samassa kuvassa [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FHiukkasfysiikkaa%2FHistogrammien-vertailu-samassa-kuvassa.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Hiukkasfysiikkaa/Histogrammien-vertailu-samassa-kuvassa.ipynb)

Tehtyäsi edelliset tehtävät voit tutustua hiukkasdataan ohjelmoinnin kannalta tällä harjoituksella, jossa vertaillaan datan perusteella piirrettyjä histogrammeja

---

### 3. Tauko

---

### 4. Hiukkasfysiikan harjoitteita

Kun olet tutustunut edellisen osion materiaaleihin, voit kokeilla alta löytyviä tehtäviä haluamassasi järjestyksessä oman kiinnostuksesi mukaan. Tästä osiosta löydät hiukkasfysiikan harjoituksia CMS-ilmaisimesta kerättyyn dataan pohjautuen.

#### Higgs hakusessa [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FHiukkasfysiikkaa%2FHiggs-hakusessa-4-leptonia.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Hiukkasfysiikkaa/Higgs-hakusessa-4-leptonia.ipynb)
Löydä Higgsin hiukkanen ja voita oma Nobel-palkinto!

#### Histogrammi valitusta datamaarasta [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FHiukkasfysiikkaa%2FEsim2-histogrammi-valitusta-datamaarasta.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Hiukkasfysiikkaa/Esim2-histogrammi-valitusta-datamaarasta.ipynb)
Tässä harjoituksessa voit interaktiivisesti kokeilla, miten käytetty datamäärä vaikuttaa piirrettyihin kuvaajiin.

#### Sovite, poikittaisliikemäärä ja pseudorapiditeetti [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FHiukkasfysiikkaa%2FSovite%2C%20poikittaisliikem%C3%A4%C3%A4r%C3%A4%20ja%20pseudorapiditeetti.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Hiukkasfysiikkaa/Sovite%2C%20poikittaisliikem%C3%A4%C3%A4r%C3%A4%20ja%20pseudorapiditeetti.ipynb)
Tässä tehtävässä pääset sovittamaan normaalijakauman hiukkasdataan ja tutustumaan poikittaisliikemäärän ja pseudorapiditeetin käsitteisiin.

---

### 5. Lisäharjoitteita

Jos aikaa jäi, voit jatkaa harjoittelua vielä hiukkasfysiikan teemojen ulkopuoleltakin. Alla olevissa demoissa sovelletaan data-analytiikan ja ohjelmoinnin työkaluja muihin kuin hiukkasfysiikan aiheisiin.

#### 1854 koleraepidemia [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FMuut_aiheet%2F1854_koleraepidemia.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Muut_aiheet/1854_koleraepidemia.ipynb)
Data ja tilastot taistelussa kulkutauteja vastaan. Tiedät sittenkin, John Snow!

#### CERN:in henkilöstö [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FMuut_aiheet%2FCERN_henkilosto.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Muut_aiheet/CERN_henkilosto.ipynb)
Keitä CERN:ssä työskentelee? Tutkitaanpa vähän tilastoja!

#### Taivasta kartoittamassa [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FMuut_aiheet%2FTaivasta_kartoittamassa.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Muut_aiheet/Taivasta_kartoittamassa.ipynb)
Tutkitaan tähtiä!

#### Barometri Col de la Fausille [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FMuut_aiheet%2Fbarometri_col_de_la_fausille.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Muut_aiheet/barometri_col_de_la_fausille.ipynb)
Tutkitaan ilmanpaineen riippuvuutta korkeudesta puhelimella tehdyn mittauksen perusteella.

#### Ääntä datasta [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=Demot%2FMuut_aiheet%2Faanta-datasta.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Demot/Muut_aiheet/aanta-datasta.ipynb)
Miten datan voi muuttaa ääneksi? Tätä tehtävää varten kannattaa olla käytettävissä kuulokkeet tai muuten varmistua siitä, etteivät tehtävän äänet häiritse samassa tilassa työskenteleviä.

Jos innostuit oikein toden teolla, lisää materiaaleja löydät GitHubin [materiaalipankista](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish)!

```python

```
