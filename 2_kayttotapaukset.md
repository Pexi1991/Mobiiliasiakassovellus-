Käyttötapaukset
==


Käyttäjäryhmät:
--

Uusi asiakas: henkilö joka on käynyt kauppakeskuksessa vasta muutaman kerran tai käy vasta ensimmäistä kertaa. Lataa sovelluksen ensimmäistä kertaa puhelimeensa.

(Kanta-)asiakas: henkilö joka on käyttänyt kauppakeskuksen palveluja jo jonkin aikaa. Lataa sovelluksen ensimmäistä kertaa tai on ladannut sen jo.

Kauppa: osapuoli, jonka liike toimii kysyisessä kauppakeskuksessa. Esittää sovelluksessa tarjouksia.

Kauppakeskus: osapuoli joka valvoo/tutkii kauppakeskuksen toimintaa, edistääkseen ja parantaakseen kauppakeskuksen tulosta.

Ylläpito: sovelluksen ylläpito, jolla on oikeus kaikkiin tietoihin, paitsi salasanoihin.Ylläåidon tehtävänä on ylläpitää sovelluksen toimintaa.


Käyttäjätarinat:
--

Uutena asiakkaana haluan löytää helposti millaisia kauppoja kauppakeskus sisältää ja opastuksen kuinka sen löytää.

Asiakkaana haluan tietää kaikki itseäni kiinnostavat tarjoukset.

Asiakkaana haluan rajata tarjousilmoitusten määrää.

Asiakkaana haluan tietää jos kauppakeskukseen on tullut uusi liike tai uusia muutoksia.

Asiakkaana haluan tietää mm. mitä ravintoloita kauppakeskuksessa on.

Kauppiaana haluan tarjoukseni tulevan huomatuksi, jotta liikeeni saisi enemmän asiakkaita.

Kauppiaana haluan rajata tarjouksen käytön vain yhteen käyttökertaan.

Kauppakeskuksena haluan kävijämäärien nousevan ja seurata missä asiakkaat kulkevat, jotta voin määritellä hyvät kauppapaikat.

Käyttäjäkaavio
--

![Käyttökaavio](/kayttajakaavio2.jpg)

Käyttäjäskenaariot
--
Skenaario 1

Kuvaus: asiakas haluaa selata kauppakeskuksen ravintoloita.

Lähtötilanne: asiakas on avannut sovelluken ja on Home-välilehdellä. Hänellä on edelleen kauppakeskuksen Wi-Fi yhteys.

Normaali eteneminen: 
	1. asiakas valitsee välilehden liikkeet
	2. asiakas painaa nappia joka kuvastaa ravintoloita
	3. kaikki kauppakeskuksen ravintolat listautuvat näytölle.

Vaihtoehtoinen eteneminen: 
1. asiakas valitsee v älilehden Haku.
2. Hän käyttää hakusanaa Ruoka, tai Ravintola
3. Näytölle ilmestyvät hakutulokset antavat kaikki liikkeet jotka ovat merkinneet tageihinsä haetun sanan.

Lopputilanne: asiakas on saanut  näyttölle näkyville kauppakeskuksen ravintoloiden nimet selattavaksi.

Mahdolliset vikatilanteet:
1. Vaihtoehtoisessa tilanteessa, hakutuloksiin ei välttämättä tule kaikki ravintolat, jos kaikki ravintolat eivät ole laittaneet kyseisiä tagejä liikkeensä tietoihin.
2. Vaihtoehtoisessa tilanteessa ei-ravintolat  ja ravintolat eivät erotu selkeästi hakutilanteessa


Skenaario 2

Kuvaus: asiakas haluaa löytää tiensä lähimpään kahvilaan.

Lähtötilanne:  asiakas on avannut sovelluken ja on Home-välilehdellä. Hänellä on edelleen kauppakeskuksen Wi-Fi yhteys.

Normaali eteneminen: 
1. Asiakas valitsee välilehden liikkeet
2. Asiakas painaa nappia joka kuvastaa kahviloita
3. Kaikki kauppakeskuksen kahvilat listautuvat näytölle.
4. Asiakas käy läpi kaikki kahviloiden navigoinnit.
5. Asiakas arvioi mikä kahvila on lähinnä.
6. Asiakas avaa valitsemansa kahvilan navigoinnin ja seuraa opastusta

Vaihtoehtoinen eteneminen: 
1. Asiakas valitsee välilehden Haku.
2. Hän käyttää hakusanaa Kahvi
3. Näytölle ilmestyvät hakutulokset antavat kaikki liikkeet jotka ovat merkinneet tageihinsä haetun sanan.
4. Asiakas käy läpi kaikki kahviloiden navigoinnit.
5. Asiakas arvioi mikä kahvila on lähinnä.
6. Asiakas avaa valitsemansa kahvilan navigoinnin ja seuraa opastusta.

Lopputilanne: Asiakas on löytänyt lähimmän kahvilan.

Mahdolliset vikatilanteet:
1. Vaihtoehtoisessa tilanteessa, hakutuloksiin ei välttämättä tule kaikki kahvilat, jos kaikki kahvilat eivät ole laittaneet ”Kahvi”-tagiä liikkeensä tietoihin.
2. Vaihtoehtoisessa tilanteessa ei-kahvilat ja kahvilat eivät erotu selkeästi hakutilanteessa
3. Asiakkalla luovuttaa kun sovellus ei ilmoita lähintä kahvilaa.
4. Asiakkaan alkusijainti on luettu väärin
5. Navingointiohje on väärä.


Käyttötapaus - etsi kahvila
--
![Käyttötapausvuokaavio](/kayttotapaus_etsi_kahvila.png)