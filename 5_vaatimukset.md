## Vaatimukset 

* Kuvaile tänne funktionaaliset ja ei-funktionaaliset vaatimukset
* Funktionaaliset vaatimukset
	  - Toimiva ranking ja tuubi-tunnukset
	  - Tietty vaihtelevuus peleissä
	  - Navigaatio, jolla selvitetään luokan peli
	  - User interface, jossa on listattu kaikki luokat ja niiden pelit
	  - Värien vaihtuminen johtavan ryhmän mukaan
	  - Pelin tulee tunnistaa kun parhaan pistemäärän omaava pelaaja kirjautuu peliin
  * Tarkentavat käyttötapauksia
	- Poistuttaessa luokasta käynnistyy pelin aikakatkaisu. Ajan loputtua sovellus sammuttaa pelin väkisin.
	    Pisteesi tallentuvat, mutta et voi jatkaa edellistä peliä.
	- Aikakatkaisua käytetään, jotta peliä ei voisi pelata muualla kuin sille määritetyssä luokassa.
	- Jos vastaanotat puhelun tai jos käytät toista sovellusta Metropolia Ranking Gamesin ollessa päällä, peli pysähtyy taukotilaan.
	- Taukotila aktivoituu vain edellämainituissa tapauksissa. Tällä pyritään pelaajasta riippumattomien haittojen minimoimiseen, mutta koska peliä ei voi manuaalisesti pysäyttää pakottaa se pelaajan intensiiviseen pelaamiseen.
	  
* Ei-funktionaaliset vaatimukset
	- Käytettävyys:
	  - Pelien tulee olla viihdyttäviä ja vaihtelevia
	  - Rankingin ja pelien sulavuus vaikuttaa järjestelmän viihtyvyyteen, ylläpitää listaa max. 5000 pelaajasta.
	- Tietoturva
	  - Käytetään Tuubin- ja Metropolian yleisiä tietoturvajärjestelmiä.
	- Tehokkuus:
	  - Pelien tulee pystyä latautumaan alle 2 sekunnissa
	  - Tulee toimia vanhemmilla puhelinmalleilla
	  - Sovelluksen siirtymien vaste-ajat ovat lyhyitä.
	- Skaalautuvuus:
	  - Voidaan skaalata kaikkiin Metropolian oppilaitoksiin
	- Hinta:
	  - Ilmainen
	Prosessimalli:
	  - Scrum

