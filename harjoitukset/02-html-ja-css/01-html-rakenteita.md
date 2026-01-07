# Harjoitukset: Html-rakenteita

Tee tehtäviä varten, oman github classroom-repositoriosi juureen, kansio `harjoitukset/02-html-ja-css`, jos sitä ei vielä ole olemassa.

Palauta yllä mainittuun kansioon kaikki tässä tiedostossa määritellyt tehtävät.

Näissä tehtävissä harjoitellaan vain html:n käyttöä.
Emme siis vielä käytä lainkaan css-tyylejä sivujen visuaalisen ilmeen muokkaamiseen.

## Ohjeita harjoitusten tekoon

### Tee tehtävät lokaalisti visual studio codessa

Tunnilla tästä repositoriosta tehtiin koneellesi paikallinen kopio.
Kaikki kurssin työt on tarkoitus tehdä tähän repositorioon.

Tee tehtävät omalla koneellasi käyttäen visual studio code -tekstieditoria (tai haluamaasi muuta tekstieditoria).
Tehtävät pitää tehdä lokaalisti, jotta voit testata tekemiäsi html-tiedostoja omassa selaimessasi.

Jos tekisit harjoitukset github.com-sivuston tekstieditorissa, et pystyisi testaamaan, miltä html-sivusi näyttävät selaimessa.

### Testaa tekemiäsi html-sivuja selaimessa

Voit kokeilla, että html-sivusi todella toimii, avaamalla html-tiedoston selaimessa.
Et tarvitse tähän palvelinta.
Selain osaa avata normaaleja html-sivuja suoraan windowsin tiedostojenhallinnan kautta, siis file explorer-työkalusta.

Tiedostoselaimessa klikkaa hiiren oikealla näppäimelllä html-tiedostoa, jonka haluat avata, 
ja valitse avautuvasta kontekstivalikosta "avaa sovelluksessa"-kohta. 
Valitse avaavaksi sovellukseksi haluamasi internet-selain, esimerkiksi Edge.
Sivun pitäisi näin avautua selaimeen.

### Muista commitoida muutokset github desktopilla

Kun olet tehnyt tehtävät, muista commitoida ne github desktopilla.

Ennen tehtävien tekemisen aloittamista on kuitenkin hyvä muistaa tehdä uusi haara (engl. branch) versionhallintaan github desktopissa.
Voit nimetä branchin `feature-`-etuliitteellä, ja tekemiäsi muutoksia kuvaavalla lyhyellä loppuosalla.

## Tehtävät

### Tehtävä 1 - html-sivu tekstillä

**palautettavan tiedoston nimi:** `teht1.html` (kansiossa: `harjoitukset/02-html-ja-css/teht1.html`)

Luo yksinkertainen html-dokumentti, joka:

* sisältää tekstin "Tervehdys, hyvä maailma!",
* ei sisällä yhtään html-elementtiä.

### Tehtävä 2 - html-sivu `html`-elementillä

**palautettavan tiedoston nimi:** `teht2.html` (kansiossa: `harjoitukset/02-html-ja-css/teht2.html`)

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää tekstin "Tervehdys, hyvä maailma!",
* sisältää seuraavat html-elementit: `html`, `head`, `body`

### Tehtävä 3

**palautettavan tiedoston nimi:** `teht3.html` (kansiossa: `harjoitukset/02-html-ja-css/teht3.html`)

#### Ohjeistus

Otsikkoja pystyy tekemään `h1`-elementin avulla

`h1`-elementin sisällön, eli lapsen, tulee olla tekstiä.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää `h1`-otsikkoelementin
 * otsikko pitää sisällään tekstin "Tervehdys, hyvä maailma!"
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

Otsikkoelementin kuuluu olla `body`-elementin sisällä.

### Tehtävä 3.1 - useita otsikoita

**palautettavan tiedoston nimi:** `teht3-1.html` (kansiossa: `harjoitukset/02-html-ja-css/teht3-1.html`)

#### Ohjeistus

Otsikkoja pystyy tekemään `h1`-elementin lisäksi myös seuraavilla elementeillä:

* `h2`
* `h3`
* `h4`
* `h5`
* `h6`

Myös näiden elementtien sisällön, eli lapsen, tulee olla tekstiä.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää 6 otsikkoa, jokainen toteutettu eri otsikkoelementin avulla (`h1`,`h2`,`h3`,`h4`,`h5`,`h6`):
 * jokainen otsikko sisältää tekstin "Tervehdys, hyvä maailma!"
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

Otsikkoelementtien kuuluu taas olla `body`-elementin sisällä.

Huomaa, että otsikko elementit eivät saa olla toistensa lapsia, eli ne eivät saa olla toistensa sisällä. 
Niiden kuuluu kaikkien olla saman `body`-elementin lapsia, eli sisaruksia toisilleen.

Järjestä otsikot siten suurimmasta pienimpään.

### Tehtävä 4 - yksinkertainen järjestämätön lista

**palautettavan tiedoston nimi:** `teht4.html` (kansiossa: `harjoitukset/02-html-ja-css/teht4.html`)

#### Ohjeistus

Listoja pystyy tekemään [`ul`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)-elementin avulla.
Listaelementin lapsielementtien tulee olla [`li`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li)-elementtejä.

Vastaavasti `li`-elementillä voi olla lapsena tekstiä, tai mitä tahansa muita html-elementtejä.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää listan `<ul>`,
  * jossa on neljä listakohtaa (engl. list item) `<li>`
    * joissa lukee tekstinä yksi seuraavista: "ensimmäinen", "toinen", "kolmas", "neljäs"
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

### Tehtävä 5 - monitasoinen lista

**palautettavan tiedoston nimi:** `teht5.html` (kansiossa: `harjoitukset/02-html-ja-css/teht5.html`)

#### Ohjeistus

Teemme seuraavaksi monimutkaisemman listan, jossa listan elementeillä on omia alilistojaan.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka tekee seuraavan näköisen (monitasoisen) listan:

```
* ensimmäinen
  * toinen
    * kolmas
* neljäs
```

Alilistojen tekemiseen joudut käyttämään sisäkkäisiä listoja.

Jos tehtävä vaikuttaa liian vaikealta, voit sivuuttaa sen.

### Tehtävä 6 - kappale

**palautettavan tiedoston nimi:** `teht6.html` (kansiossa: `harjoitukset/02-html-ja-css/teht6.html`)

#### Ohjeistus

Otsikoiden lisäksi html-sivuilla on yleensä tekstiä.
Kun haluamme lisätä tekstiä, käytämme yleensä [`p`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)-elementtiä.
`p`-elementti saa nimensä englannin kielisestä sanasta "paragraph", joka tarkoittaa tekstin "kappaletta".

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää kaksi peräkkäistä kappaletta `<p>`,
  * ensimmäisen kappaleen sisältö: "Tämä on ensimmäinen kappale." 
  * jälkimmäisen kappaleen sisältö: "Tämä on seuraava kappale." 
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

### Tehtävä 7 - linkki

**palautettavan tiedoston nimi:** `teht7.html` (kansiossa: `harjoitukset/02-html-ja-css/teht7.html`)

#### Ohjeistus

Html-sivulta on mahdollista linkata toisille html-sivuille.
Tätä varten voidaan käyttää [`<a>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)-elementtiä.

Voit katsoa `a`-elementin syntaksin yllä olevasta mdn-sivun `a`-elementtiä käsittelevästä ohjeistuksesta.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää kappaleen `p`,
  * kappaleen sisältö: "Tässä kappaleessa on linkki, joka osoittaa github:in etusivulle."
  * tee kappaleen "linkki"-sanasta linkki `a`-elementin avulla, ja laita se osoittamaan github.com:in etusivulle: `https://github.com`.
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

### Tehtävä 8 - koodielementti

**palautettavan tiedoston nimi:** `teht8.html` (kansiossa: `harjoitukset/02-html-ja-css/teht8.html`)

#### Ohjeistus

Jos halutaan merkitä html-sivulla esimerkkikoodia tekstin seassa,
kuten tällä sivulla on tehty erilaisten tiedoston- ja html-elementtien nimien osalta,
voidaan se tehdä [`code`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code)-elementin avulla.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää kappaleen `p`-elementtiä käyttäen
  * kappaleen tekstinä on: "Tässä kappaleessa käytetty p-elementti on tehty käyttäen code-elementtiä."
  * tee tämän kappaleen `p`- ja `code`-sanoista koodielementin avulla koodielementin näköiset.
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`

### Tehtävä 8.1 - korostuksia

**palautettavan tiedoston nimi:** `teht8-1.html` (kansiossa: `harjoitukset/02-html-ja-css/teht8-1.html`)

#### Ohjeistus

Välillä tekstin sekaan halutaan lisätä korostuksia.

Tällaisia korostuksia löytyy useampia, sen mukaan minkälaista korostusta halutaan ilmaista:

* [`em`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/em) - stress emphasis -korostus - näytetään yleensä kursivoidulla tekstillä,
* [`i`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/i) - idiomaattinen teksti - näytetään yleensä kursivoidulla tekstillä,
* [`b`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/b) - bring to attention -korostus - näytetään yleensä lihavoidulla tekstillä,
* [`strong`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/strong) - suuren merkityksen teksti - näytetään yleensä lihavoidulla tekstillä,

Html:n spesifikaatio määrittää näille kaikille verrattain tarkat käyttötapaukset. Voi olla mielenkiintoista tutustua näihin käyttötarkoituksiin oheisten linkkien kautta.

Huomaa, että vaikka elementeille näille on osalle erilaiset visuaaliset muodot, niitä pitäisi käyttää ensisijaisesti kuvaamaan niiden semanttisiä käyttötapauksia - siis niille määriteltyjä merkityksiä. 
Näitä elementtejä ei siis pitäisi käyttää niiden oletustyylien mukaisesti, koska tyylejä voidaan aina muuttaa halutunlaisiksi css:n avulla.

Html:n korostukset ovat ehkä hieman epäselviä, mutta toisaalta, jos niitä pitää myöhemmin jossain työtehtävässä käyttää, on hyvä tietää, että [developer.mozilla.org](https://developer.mozilla.org) yleensä osaa antaa vähintään auttavan lisätiedon elementin käyttötarkoituksesta.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* sisältää kappaleen `p`-elementtiä käyttäen,
  * kappaleen tekstinä on: "Html:ssä korostuksia on paljon."
  * "html"-termi on korostettu käyttäen `i`-korostusta,
  * "korostuksia"-termi on korostettu käyttäen `strong`-korostusta,
  * "on"-termi on korostettu käyttäen `em`-korostusta,
  * "paljon"-termi on korostettu käyttäen `b`-korostusta,
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`.

Huomattakoon, että tämä tehtävä ei nyt ihan täytä w3c:n (The World Wide Web Consortium, html-standardin kehittämisestä vastaava organisaatio) määrittelyitä. 

Jos tehtävän didaktinen harjoite on oppia, että html-elementtien joukosta löytyy useampi erilainen korostukseen käytetty elementti,
niin moraalinen oppi voisi olla vaikka se, että html:n ollessa varsin monimutkainen standardi, sen semanttisia elementtejä käytettäessä tulee aina välillä tehtyä virheitä, mutta elämä jatkuu tästä huolimatta.

### Tehtävä 9 - päivän lopputehtävä

**palautettavan tiedoston nimi:** `teht9.html` (kansiossa: `harjoitukset/02-html-ja-css/teht9.html`)

Tässä tehtävässä tarkoituksena on käyttää kaikkea tällä sivulla opittua.

Tehtävänäsi on tehdä tämän auki olevan `01-html-rakenteita.md`-sivun sisällöstä html-versio. 
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

Sivulta tulee löytyä kaikki sama teksti mitä tältä sivulta löytyy tällä hetkellä. Voit kopioida tekstin suoraan tältä sivuta, jos et sitä jaksa itse käsin uudelleen kirjoitella.
Jos tätä tehtäväsivua päivitetään myöhemmin, muutoksia ei tarvitse lisätä tekemällesi sivulle.

Sinun ei tarvitse kirjoittaa tämän tiedoston tekstiä, vaan voit kopioida sen tältä sivulta. Tarkoitus on lisätä sivulle oikeisiin kohtiin tarvittavat html-elementit, 
jotta saat sivun näyttämään suurinpiirtein samalta.

Huomaa myös, että koska emme käytä css-tyylejä, sivusi tulee poikkeamaan tästä sivusta. Tällä sivulla on käytössä github:in tyylit, joiden takia, 
esimerkiksi koodiosiot näkyvät harmaalla taustalla. 
Omassa versiossa todennäköisesti koodiosio poikkeaa muusta tekstistä vain siinä, että se käyttää niin sanottua monospace-kirjasinta, joka poikkeaa muun tekstin käyttämästä kirjasimesta.

#### Tehtävänanto

Luo yksinkertainen, oikeaoppinen html-dokumentti, joka:

* näyttää tämän tiedoston html-versiolta
* sisältää lisäksi seuraavat html-elementit: `html`, `head`, `body`
