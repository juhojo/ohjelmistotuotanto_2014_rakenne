## Käyttöliittymä

1. Miten käyttötapaukset ja käyttöliittymät voisi yhdistää toisiinsa vaatimusmäärittelydokumentaatiossa? Perustele
vastauksesi.
Käyttötapauksen jälkeen voisi olla esitettynä kuva miltä kyseinen tapaus näyttää sovelluksessa, ja miten se olisi toteutettu. Kyseinen esitystapa olisi konkreettinen tapa esittää haluttu toiminto.
2. Listaa järjestelmän käyttöliittymän olennaisimmat näkymät
Kirjautumisnäkymä, huonenäkymä, ranking-näkymä ja pelinäkymä.
3. Kuvaile näkymät *sanallisesti*: mitä näkymällä tehdään ja mitä siinä näkyy. Pyri määrittelemään tässä näkymät
*toiminnallisesta näkökulmasta*, älä niinkään ajattele miltä ne näyttävät.
<div style='float: center'>
  <img style='width: 600px' src="http://users.metropolia.fi/~jussisoi/Ohjelmistotuotanto/Drawing1.jpg"></img>
</div>

Alkunäkymä on sisäänkirjautuminen, tästä siirrytään karttanäkymään josta näkee luokat ja niissä olevat pelit. Sovellus tunnistaa hetken kuluttua luokkasi ja siirtyy ranking-näkymään, jossa on listattu kyseisen pelin parhaat pelaajat. Tämän jälkeen käyttäjä voi siirtyä peliin ja pelinäkymässä on kyseisen luokan peli.
4. Määritä näkymien väliset siirtymät korkealla tasolla, mistä näkymästä pääsee minnekin? Millä tavoin visualisoisit tilasiirtymät?
Sisäänkirjautumisnäkymästä karttanäkymään siirtyminen tapahtuu nopean fade-to-black efektin avulla. Karttanäkymästä ranking-näkymään tapahtuu zoom-in-zoom-out siirtymällä. Siirtymä ranking-näkymästä pelinäkymään tapahtuu nopealla fade-to-black efektillä.
5. Listaa jokaista näkymää kohti tieto siitä, millaista tietosisältöä tai data käyttöliittymässä näytetään.
  - Kirjautumisessa: Pelin nimi ja Käyttätunnus / Salasana
  - Kartta: Metropolian kartta ja luokkien numerot, sekä niissä olevat pelit
  - Ranking: Luokan numero, peli ja ranking-lista
  - Pelinäkymä: Pelin nimi ja peli

#### 3. Visualisoi listaamasi näkymät ja niihin liittyvät siirtymät

<div style='float: center'>
  <img style='width: 600px' src="http://users.metropolia.fi/~juhojo/ohjelmistotuotanto/Lab%206.jpg"></img>
</div>

- vähintään 3 näkymää
- Voit käyttää Painttia, Visiota tai esimerkiksi [Moqupsia](https://moqups.com/). 
