3 Järjestelmäarkkitehtuuri
==========================

Selitykset:
-----------

* Käyttötietokanta sisältää tietoja kaupan nimi, aukioloajat, liikkeenkategoria, tarjoukset, 
kamppaniat, liikkeen koordinaatit, määritteitä/tageja yms. mitä sitten ikinä ohjelmiston toiminnallisuuteen vaaditaan. 

Nämä tiedot ovat tietoja joiden avulla käyttöjärjestelmä välittää
käyttäjälle tietoja kyseisestä kauppakeskuksesta. Esimerkkinä käyttäjä etsii liikkeen tietoja, nuo tiedot luetaan käyttötietokannasta
tai vaikkapa kun halutaan navigoida liikkeeseen liikkeen koordinaatit välittyy täältä tietokannasta.

* Käyttäjätietokanta: sisältää tiedot käyttäjän nimi, käyttäjätunnus, salasana, syntymäaika, 
osoite, tiedot, käyttäjän sijaintihistoria(koordinaatit), käyttölokin(mitä tehnyt, missä tehnyt, kuinka kauan jne).

Käyttäjätietokanta palvelee käyttäjää erityisesti tunnistautumisessa, sillä käyttäjätietokanta sisältää tiedot oikeista tunnuksista.
Käyttäjätietokantaan säilötään realiajassa tiedot käyttäjän sijainnista, sekä mahdollisista käyttötapauksista ja tottumuksista. 
Käyttötottumuksilla ja tapauksilla tarkoitan tietoja, joita on kerätty esimerkiksi silloin kun asiakas on käynyt liikkeestä
ja näyttänyt qr-koodia saadakseen alennuksen. Realiaikaista sijaintia verrataan käyttötietokannasta kaivettavien liikeiden
koordinaatteihin ja tällätavalla pystytään ehdottelemaan käyttäjälle realiajassa sijaintiin kytkettyjä tarjouksia.

* Tunnistautuminen: käyttäjätunnus, salasana.

Perustoiminta kulut:
--------------------

* Asiakaskäyttäjä tunnistautuu, jonka jälkeen käyttöjärjestelmään ladataan käyttäjätiedot 
käyttäjätietokannasta sekä käyttöjärjestelmää sisältö käyttötietokannasta.

* Asiakaskäyttäjän liikkuessa kauppakeskuksessa sijaintien koordinaatit kirjataan käyttäjätietokantaan.

* Kun sovellus esittää esimerkiksi tarjouksia käyttäjälle käyttäjän realiakaiseen sijaintiin perustuen, tuolloin sovellus
käyttää käyttäjäntietokantaa (asiakkaankoordinaatit) ja käyttötietokantaa (liikkeenkoordinaatit) kyseisten etäisyyksien tarkasteluun.

* Asiakaskäyttäjän käyttäessä jotain liikkeen kertakäyttöisiä tarjouksia tai tietylle käyttäjäryhmälle suunnattuja tarjouksia
asiakkaan käyttöjärjestelmä lataa tiedot kyseisista alennuksista. Käyttötietokantaan sisällönluoja on luonut tiedot että tietyn piirteen
täyttävä asiakas saa tämän edun. Kun etu käytetään tieto lähetetään käyttötietokantaan ja "leimataan" käytetyksi.

* Asiakaskäyttäjän liikkuessa kauppakeskuksessa liikkeet kirjataan käyttäjätietokantaan.

* Sisällönluoja (kauppa) tunnistautuu, jonka jälkee sisällönluojan käyttöjärjestelmä ladataan tunnistamisessa 
tulleiden käyttäjätietokanta tietojen perusteella oikeksi ja käyttöjärjestelmään tuodaan liikkeen 
tiedot käyttötietokannasta.

* Sisällönluoja (kauppias) voi sisällönluonnin jälkeen luoda sisältöä sovellukseen. Sisällönluoja luo sisällön käyttäen
käyttöjärjestelmää joka on mukautettu sisällönluontiin. Muutokset kirjataan käyttötietokantaan, josta sitten asiakaspuolen
sovellus käy tiedot hakemassa.

* Ylläpitäjä tunnistautuu ja pääsee käsiksi huoltojärjestelmään ja sen avulla kaikkii järjestelmän osiin.



![Järjestelmäarkkitehtuuri-kaavio](/arkkitehtuuri.png)