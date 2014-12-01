## Käyttötapaukset

* Määritä tänne järjestelmän loppukäyttäjät
	- Opiskelijat
	- Opettajat
	- muut Tuubi-tunnusten haltijat
* Käyttötapauskaavio, jossa järjestelmän keskeiset käyttötapaukset
	<div style='float: center'>
		<img style='width: 600px' src="http://users.metropolia.fi/~jussisoi/Ohjelmistotuotanto/Drawing1.jpg"></img>
	</div>
* Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen
  * mallipohja: määritä alkutila (initial state), normaali kulku (normal flow), lopputila (end state)
	  Alkunäkymä on sisäänkirjautuminen, tästä siirrytään karttanäkymään josta näkee luokat
	  ja niissä olevat pelit. Sovellus tunnistaa hetken kuluttua luokkasi ja siirtyy ranking-näkymään,
	  jossa on listattu kyseisen pelin parhaat pelaajat.
	  Tämän jälkeen käyttäjä voi siirtyä peliin ja pelinäkymässä on kyseisen luokan peli.
  * kerro myös kuinka normaali kulku voi mennä pieleen sekä
	  - Normaalikulku voi mennä pieleen, kun et ole luokassa vaan esimerkiksi käytävällä.
	  - Matkapuhelimen verkko ei toimi
	  - Tuubi-verkkosivu on alhaalla
	  - Tuubi-tunnukset eivät toimi
  * mahdolliset vaihtoehtoiset kulut (alternate flow)
	  - Sisäänkirjautumisen epäonnistuessa sovellus ei avaudu, etkä pääse pelaamaan.