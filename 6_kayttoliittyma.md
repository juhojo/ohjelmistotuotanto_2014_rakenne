## Käyttöliittymä

Käyttötapauksen jälkeen on esitetty kuva miltä kyseinen tapaus näyttää sovelluksessa. Kyseinen esitystapa olisi konkreettinen tapa esittää haluttu toiminto.

Järjestelmän olennaisimmat näkymät ovat kirjautumisnäkymä, huonenäkymä, ranking-näkymä ja pelinäkymä.

<div style='float: center'>
  <img style='width: 600px' src="http://users.metropolia.fi/~jussisoi/Ohjelmistotuotanto/Drawing1.jpg"></img>
</div>

Alkunäkymä on sisäänkirjautuminen, tästä siirrytään karttanäkymään josta näkee luokat ja niissä olevat pelit. Sovellus tunnistaa hetken kuluttua luokkasi ja siirtyy ranking-näkymään, jossa on listattu kyseisen pelin parhaat pelaajat. Tämän jälkeen käyttäjä voi siirtyä peliin ja pelinäkymässä on kyseisen luokan peli.

Sisäänkirjautumisnäkymästä karttanäkymään siirtyminen tapahtuu nopean fade-to-black efektin avulla. Karttanäkymästä ranking-näkymään tapahtuu zoom-in-zoom-out siirtymällä. Siirtymä ranking-näkymästä pelinäkymään tapahtuu nopealla fade-to-black efektillä.
Kättöliittymässä näytettävät tietosisällöt:
  - Kirjautumisessa: Pelin nimi ja Käyttätunnus / Salasana
  - Kartta: Metropolian kartta ja luokkien numerot, sekä niissä olevat pelit
  - Ranking: Luokan numero, peli ja ranking-lista
  - Pelinäkymä: Pelin nimi ja peli

#### 3. Visualisoi listaamasi näkymät ja niihin liittyvät siirtymät

<div style='float: center'>
  <img style='width: 600px' src="http://users.metropolia.fi/~juhojo/ohjelmistotuotanto/Lab%206.jpg"></img>
</div>
