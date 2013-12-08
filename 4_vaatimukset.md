

Funktionaaliset vaatimukset
==


Asiakkaan puhelinsovelluksen funktionaaliset vaatimukset
--


+ Rekisteröityminen: tämä tulee vain kuin sovellus avataan enimmäistä kertaa. Käyttäjän tulee syöttää sukupuolensa, ikänsä, sähköpostinsa ja salasanansa
+ Reksiteröinti → Sähköposti jo käytössä: samalla sähköpostilla ei voi olla toista tunnusta, eikä sitä myöten toista salasanaakaan. Näyttöön tulee ilmoitus, että sähköposti on jo käytössä.  Annetaan mahdollisuus kirjautua sisään sillä sähköpostiosoitteella.
+ Tunnistautuminen: rekisteröinnin yhteydessä käyttäjä saa automaattisen ID numeron, joka on riippuvainen annetusta sähköpostista. Näin esimerkiksi kahta puhelinta käyttävä voi käyttää sovellusta yhtenä henkilönä, eikä tilastot vääristy.
+ Kirjautuminen: kun sovellus käynnistetään kirjautuminen tapahtuu automaattisesti. Mikäli näin ei tapahdu avautuu rekisteröinti mahdollisuus tai manuaalinen kirjautuminen. Manuaaliseen kirjautumiseen tarvitaan sähköposti ja salasana.
+ Salasanan unohtaminen: manuaalisen kirjautumisen yhteydessä on mahdollisuus valita toiminto jossa asiakkaalle lähetetään annetamaansa sähköpostiin linkki salasanan uusimiseen.
+ Sähköpostin unohtaminen: käyttäjän täytyy rekisteröityä uudelleen.
+ Tunnuksen poisto: tunnuksen voi poistaa käytöstä puhelimen lisävalikkonapin takaa, kohdasta asetukset. 
+ Sähköpostin aktivointi: rekisteröinnin jälkeen pyydetään aktivoimaan sähköposti. Ennen kuin sähköposti on aktivointi tarjouksia ei voi nähdä. Aktivointilinkki tulee sähköpostiin ja linkki johtaa sovelluksen nettisivuille, jossa suoritetaan aktivointi.
+ Perustietojen muokkaus: puhelimen lisävalikkonapin takaa kohdasta perustiedot, voi muokata mitä tarjouksia haluaa. Ikää ja sukupuolta ei voi vaihtaa enää jälkikäteen.
+ Navigointi: aina kun painetaan navigoi-nappia niin annetaan reittiohjeet haluttuun paikkaan kun lähtöpaikka on Wi-Fin kautta laskettu paikka. Reittiohje on sekä kartalla, että kirjallisesti.
+ Mainosilmoitus: kun käyttäjä kulkee riittävän lähellä kauppaa hän saa puhelimeensa ilmoituksen tarjouksesta, mikäli heillä sellainen on. Sama tarjousilmoitus tulee vain kerran.
+ Tarjouksen käyttö: Tarjousta näytetään puhelimesta myyjälle oston yhteydessä. Tarjous ei ole tällöin kertakäyttöinen. Jos tehdää kertakäyttöinen tarjous, käytetään QR-koodia, joka luetaan kassalla.
+ Haku: hakutulokset perustuvat liikeiden nimiin ja niiden tageihin.




Ei-funktionaaliset vaatimukset
==


Käytettävyys
--

Palvelulla on oma nettisivustonsa, minkä kautta ylläpitäjät,  kaikki kauppakeskukset ja kaupat päivittävät tietojaan. Samalle sivustolle ohjataan uusimaan salasana, sekä sähköpostin aktivointi sähköpostiin lähetetyn linkin avulla. Tässä vaatimusmäärittelyssä keskitytään puhelinsovellukseen.

Sovelluksen voi ladata vain älypuhelimeen tai tablettiin. Laitteen tulee pystyä suorittamaan kaikki mitä sovellus vaatii, kuten ottamaan Wi-Fi yhteyden.




Yksityisyys
--

Tietoja pääsee tarkkailemaan hyvin rajoitetusti. Vain ylläpitäjä pääsee käsiksi koko käyttäjädataan (salasanaa lukuunottamatta). Kauppakeskukselle ja kaupoille näkyy vain sovelluksen antama ID-numero, ikä ja sukupuoli. Kauppakeskuksella on mahdollisuus tarkkailla yksittäisen kävijän reittiä, sekä toimintaa sovelluksessa. Kauppa näkee vain kaupassa QR-koodin kanssa asioineiden ja kaupan sisällä todennäköisesti käyneiden käyttäjien tiedot ja kaupassa vietetyn ajan.

Muut vaatimukset
--

Jotta sovellus toimisi sujuvasti täytyy kauppakeskuksen itse tarjota riittävä Wi-Fi. On kauppakeskuksen oma valinta onko Wi-Fi suojattu vai avoin. Suojattuna, Wi-Fin kirjautumisena käy käyttäjän sähköposti ja salasana sovellukseen, eikä manuaalista kirjautumista tarvitse tehdä kuin kerran laitetta kohti.

Sijaintimäärittely ei ole koskaan täysin luotettava, enemmän kyseessä on suuntaa antava, mutta tavoitteena on mahdollisimman tarkka sijaintilaskelma. Minimi vaatimuksena on ettei sijainti saisi heittä kerroksella. Paikannustarkkuutta parannetaan oikeisiin paikkoihin sijoitetuilla tukiasemilla.

Sovelluksen sisällön päivitys tapahtuu vain silloin kuin ollaan yhteydessä kauppakeskuksen tarjoamasssa Wi-Fissä. Sovellus automaattisesti ottaa käyttöön kyseisen Wi-Fin  kysymättä käyttäjältä lupaa joka kerta erikseen. Lupa on kysytty etukäteen sovelluksen asennuksen yhteydessä esitettyt vaatimukset hyväksymällä.

Mikäli todetaan että puhelimen lisävalikkonappi aiheuttaa hankaluuksia eri puhelinmallien takia, voidaan se korvata tekemällä Asetukset-välilehti alimmaiseksi välilehdeksi.

