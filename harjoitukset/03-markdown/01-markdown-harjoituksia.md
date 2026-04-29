# Harjoitukset: Markdown-rakenteita

Tee tehtäviä varten, oman github classroom-repositoriosi juureen, kansio `harjoitukset/03-markdown`, jos sitä ei vielä ole olemassa.

Palauta yllä mainittuun kansioon kaikki tässä tiedostossa määritellyt tehtävät.

Näissä tehtävissä harjoitellaan vain markdown:in käyttöä.

## Ohjeita harjoitusten tekoon

### Tee tehtävät lokaalisti visual studio codessa tai github.com:in tekstieditorilla github classroom:iin

Kaikki kurssin html- ja markdown-harjoitukset on tarkoitus tehdä moodlessa määritettyyn github classroom -repositorioon.

Voit kuitenkin valita teetkö tehtävät:

* lokaalisti vscode:ssa, kuten html-tehtävät tehtiin, vai
* github.com:in tekstieditoria käyttäen.

Ohjeet näiden kahden tekstieditorien käyttöön:

* [markdown-editorit](./00-2-teoria-2-markdown-editorit.md)

### Muista commitoida muutokset github desktopilla

Kun olet tehnyt tehtävät, muista commitoida ne github desktopilla, ja siirrä ne github.com:in palvelimelle (engl. push).

### Ohjeet markdown-syntaksille

Ohjeet markdown-syntaksille löytyvät github:in dokumentaatiosta:

* github:in ohje: [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## Tehtävät

### Tehtävä 1 - markdown-tiedosto tekstillä

**palautettavan tiedoston nimi:** `teht1.md` (kansiossa: `harjoitukset/03-markdown/teht1.md`)

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää tekstin "Tervehdys, hyvä maailma!",
* ei sisällä lainkaan markdown-syntaksia.

### Tehtävä 2 - otsikolla

**palautettavan tiedoston nimi:** `teht2.md` (kansiossa: `harjoitukset/02-markdown/teht2.md`)

#### Ohjeistus

Otsikkoja pystyy tekemään rivin alkuun lisättävän `#`-merkin avulla. Tällöin `#`-merkin ja otsikon väliin lisätään lisäksi välilyönti.

Markdown:issa `#`-merkintä vastaa html:n `h1`-elementtiä.

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää `#`-otsikon
 * otsikko pitää sisällään tekstin "Tervehdys, hyvä maailma!"

### Tehtävä 3 - useita otsikoita

**palautettavan tiedoston nimi:** `teht3.md` (kansiossa: `harjoitukset/03-markdown/teht3.md`)

#### Ohjeistus

Otsikkoja pystyy tekemään `#`-elementin lisäksi myös seuraavilla elementeillä:

* `##`     - vastaa html:n `h2`-elementtiä
* `###`    - vastaa html:n `h3`-elementtiä
* `####`   - vastaa html:n `h4`-elementtiä
* `#####`  - vastaa html:n `h5`-elementtiä
* `######` - vastaa html:n `h6`-elementtiä

Myös näiden elementtien sisällön, eli lapsen, tulee olla tekstiä.

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää 6 otsikkoa, jokainen toteutettu eri otsikkoelementin avulla (`#`,`##`,`###`,`####`,`#####`,`######`):
 * jokainen otsikko sisältää tekstin "Tervehdys, hyvä maailma!"

Järjestä otsikot suurimmasta pienimpään.

### Tehtävä 4 - yksinkertainen järjestämätön lista

**palautettavan tiedoston nimi:** `teht4.md` (kansiossa: `harjoitukset/03-markdown/teht4.md`)

#### Ohjeistus

Lue github:in dokumentaatiosta miten listoja tehdään. (linkki yllä.)

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää listan,
  * jossa on neljä listakohtaa (engl. list item)
    * joissa lukee tekstinä yksi seuraavista: "ensimmäinen", "toinen", "kolmas", "neljäs"

### Tehtävä 5 - monitasoinen lista

**palautettavan tiedoston nimi:** `teht5.md` (kansiossa: `harjoitukset/03-markdown/teht5.md`)

#### Ohjeistus

Teemme seuraavaksi monimutkaisemman listan, jossa listan elementeillä on omia alilistojaan.

Tähänkin ohjeet löytyvät samasta github:in markdown-dokumentaatiosta.

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka tekee seuraavan näköisen (monitasoisen) listan:

```
* ensimmäinen
  * toinen
    * kolmas
* neljäs
```

Tämä tehtävä on markdown:illa paljon helpompi, kuin sitä vastaava html-tehtävä.

### Tehtävä 6 - kappale

**palautettavan tiedoston nimi:** `teht6.md` (kansiossa: `harjoitukset/03-markdown/teht6.md`)

#### Ohjeistus

Otsikoiden ja listojen lisäksi markdown-tiedostoissa on yleensä myös ihan vain normaalia tekstiä kappaleiden muodossa.

Kun haluamme markdown-tiedostossa erottaa kaksi peräkkäistä riviä omiksi erillisiksi kappaleikseen,
laitamme näiden rivien väliin yhden tyhjän rivin:

```markdown
eka kappale

toka kappale
```

Jos lisäämme rivien väliin vain rivinvaihdon, ne näkyvät esikatselussa (ja renderöitynä) samana kappaleena:

```markdown
nämä rivit ovat osa samaa kappaletta,
vaikka ovatkin eri riveillä.
```

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää kaksi peräkkäistä, mutta toisistaan erillään olevaa kappaletta,
  * ensimmäisen kappaleen sisältö: "Tämä on ensimmäinen kappale." 
  * jälkimmäisen kappaleen sisältö: "Tämä on seuraava kappale." 
* sisältää kolmannen erillisen kappaleen, joka on toteutettu markdown-tiedostossa, seuraavina erillisinä riveinä:
  * ensimmäinen rivi: "Tämä on"
  * toinen rivi: "kolmas kappale."
 
Lopputuloksen pitäisi näyttää seuraavalta:

```
Tämä on ensimmäinen kappale.

Tämä on seuraava kappale.

Tämä on kolmas kappale.
```

### Tehtävä 7 - linkki

**palautettavan tiedoston nimi:** `teht7.md` (kansiossa: `harjoitukset/03-markdown/teht7.md`)

#### Ohjeistus

markdown-tiedostolta on mahdollista linkata:

* toisiin markdown-tiedostoihin saman repositorion sisällä, mutta myös
* url:ihin, niinkuin html:ssäkin.

Molemmat tapahtuvat saman syntaksin avulla:

```markdown
[googlen etusivu](https://google.com)
[toinen markdown-dokumentti](./muu-markdown-dokumentti.md)
```

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää kappaleen,
  * kappaleen sisältö: "Tässä kappaleessa on linkki, joka osoittaa github:in etusivulle."
  * tee kappaleen "linkki"-sanasta linkki markdown-syntaksin avulla, ja laita se osoittamaan github.com:in etusivulle: `https://github.com`.

### Tehtävä 8 - koodielementti

**palautettavan tiedoston nimi:** `teht8.md` (kansiossa: `harjoitukset/03-markdown/teht8.md`)

#### Ohjeistus

Jos halutaan merkitä markdown-tiedostoon esimerkkikoodia tekstin sekaan,
kuten tällä sivulla on tehty erilaisten tiedoston- ja html-elementtien nimien osalta,
voidaan se tehdä ~``~-syntaksin avulla.

```markdown
Tässä lauseessa mainitaan `a`-elementti, joka on merkitty koodiksi, koska se on html-elementti.
```

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää kappaleen
  * kappaleen tekstinä on: "Tässä kappaleessa mainittu p-elementti on merkitty markdown-syntaksilla koodiksi."
  * tee tämän kappaleen `p`-sanasta koodisyntaksin avulla muusta tekstistä erottuva.

### Tehtävä 8.1 - korostuksia

**palautettavan tiedoston nimi:** `teht8-1.md` (kansiossa: `harjoitukset/03-markdown/teht8-1.md`)

#### Ohjeistus

Välillä tekstin sekaan halutaan lisätä korostuksia.

Markdown tuntee mm. seuraavat korostukset:

* _kursivointi_ - merkitään `_kursivointi_` tai `*kursivointi*`,
* **lihavointi** - merkitään `**lihavointi**` tai `__lihavointi__`,
* ~~yliviivaus~~ - merkitään `~~yliviivaus~~`.

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää kappaleen,
  * kappaleen tekstinä on: "Markdown:issa korostuksia on paljon."
  * "Markdown"-termi on korostettu käyttäen kursivointia,
  * "korostuksia"-termi on korostettu käyttäen lihavointia,
  * "paljon"-termi on korostettu käyttäen yliviivausta.

### Tehtävä 9 - päivän lopputehtävä

**palautettavan tiedoston nimi:** `teht9.md` (kansiossa: `harjoitukset/03-markdown/teht9.md`)

Tässä tehtävässä tarkoituksena on käyttää kaikkea tällä sivulla opittua.

Tehtävänäsi on tehdä tämän selaimessa auki olevan `01-markdown-harjoituksia.md`-sivun sisällöstä markdown-versio.
Voit tehdä koko sivun, mutta riittää, että toisinnat tehtävänannot tehtävän 4 loppuun asti.

Tarvitset siis: 

* otsikoita,
* kappaleita,
* listoja,
* sisäkkäisiä listoja,
* korostuksia,
* linkkejä ja
* koodiesimerkkejä.

Sinun ei siis tarvitse toteuttaa github-sivun yleisiä piirteitä, värejä tai fontteja.
Esimerkiksi `code`-elementtien taustan ei tarvitse olla harmaa, kuten github:ssa on tätä kirjoittaessa - riittää että elementin sisällä oleva teksti näyttää normaalista tekstistä poikkeavalta.
Et myös muutenkaan tarvitse css-tyylejä, tai `style`-attribuutteja tähän tehtävään.
Tehtävänäsi on vain toteuttaa tämän tehtävänantosivun sisältö html-syntaksia käyttäen, tehden siitä semanttisesti riittävän samanlaista aiemmin oppimiesi html-elementtien avulla.

Sivulta tulee löytyä kaikki sama teksti mitä tältä sivulta löytyy tällä hetkellä. Voit kopioida tekstin suoraan tältä sivulta selaimessa, jos et sitä jaksa itse käsin uudelleen kirjoitella.
Jos tätä tehtäväsivua päivitetään myöhemmin, muutoksia ei tarvitse lisätä tekemällesi sivulle.

Sinun ei tarvitse kirjoittaa tämän tiedoston tekstiä, vaan voit kopioida sen tältä sivulta selaimessa. Tarkoitus on lisätä sivulle oikeisiin kohtiin tarvittavat markdown-syntaksit, 
jotta saat sivun näyttämään suurinpiirtein samalta.

#### Tehtävänanto

Luo yksinkertainen markdown-tiedosto, joka:

* sisältää tämän sivun tekstin,
* näyttää esikatselussa samalta kuin tämä sivu näyttää selaimessa.

Riittää, että teet kopiosi tehtävänannon 4 tekstin loppuun asti. Ei siis tarvitse tehdä sivua aivan kokonaan uudestaan.
