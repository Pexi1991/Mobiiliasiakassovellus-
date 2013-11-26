Selitykset:
-----------

* Käyttötietokanta: sisältää tietoja kaupan nimi, aukioloajat, liikkeenkategoria, tarjoukset, 
kamppaniat, liikkeen koordinaatit, määritteitä/tageja.

* Käyttäjätietokanta: sisältää tiedot käyttäjän nimi, käyttäjätunnus, salasana, syntymäaika, 
osoite, tiedot, käyttäjän sijaintihistoria(koordinaatit), käyttölokin(mitä tehnyt, missä tehnyt, kuinka kauan jne).

* Tunnistautuminen: käyttäjätunnus, salasana.

Perustoiminta kulut:
--------------------

* Asiakaskäyttäjä: tunnistautuu, jonka jälkeen käyttöjärjestelmään ladataan käyttäjätiedot 
käyttäjätietokannasta sekä sen hetkinen sisältö käyttötietokannasta.

* Sisällönluoja: tunnistautuu, jonka jälkee sisällönluojan käyttöjärjestelmän ladataan tunnistamisessa 
tulleiden käyttäjätietokanta tietojen perusteella oikeksi ja käyttöjärjestelmään tuodaan liikkeen 
tiedot käyttötietokannasta.

* Ylläpitäjä: tunnistautuu ja pääsee käsiksi huoltojärjestelmään ja sen avulla kaikkii järjestelmän osiin.



![Järjestelmäarkkitehtuuri-kaavio](/arkkitehtuuri.png)