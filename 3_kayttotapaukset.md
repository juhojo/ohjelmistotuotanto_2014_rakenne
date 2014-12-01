## Käyttötapaukset

	Järjestelmän loppukäyttäjiä ovat opiskelijat, opettajat ja muut tuubi-tunnusten haltijat.

* Kaavio järjestelmän keskeisimmistä käyttötapauksista:
	<div style='float: center'>
		<img style='width: 600px' src="http://users.metropolia.fi/~jussisoi/Ohjelmistotuotanto/Drawing1.jpg"></img>
	</div>

	  Alkunäkymä on sisäänkirjautuminen, tästä siirrytään karttanäkymään josta näkee luokat
	  ja niissä olevat pelit. Sovellus tunnistaa hetken kuluttua luokkasi ja siirtyy ranking-näkymään,
	  jossa on listattu kyseisen pelin parhaat pelaajat.
	  Tämän jälkeen käyttäjä voi siirtyä peliin ja pelinäkymässä on kyseisen luokan peli.
	 * Normaalikulusta poikkeavia tapauksia ovat:
	  - Normaalikulku voi mennä pieleen, kun et ole luokassa vaan esimerkiksi käytävällä.
	  - Sovellus ei toimi ilman matkapuhelimen mobiiliverkkoa.
	  - Tuubi-verkkosivujen ollessa alhaalla sisäänkirjautuminen ei onnistu. Tällöin emme pääse karttanäkymään.
	  - Kirjautuminen ei toimi, jos kirjautujalla ei ole Tuubi-tunnuksia.