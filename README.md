# Harjoitus 3

Tein harjoituksen omalla MacBook Pro kotikoneellani.
Käyttöjärjestelmänä on MacOs Catalina.
Aloitin harjoituksen 25.1.2023 klo 13.07 ja lopetin klo 16.20.
Prosessori koneessani on 2,6 GHz Dual-Core Intel Core i5.
Virtualboxin versio on 7.0.6.



Tiivistelmä


Vapaa ohjelmisto tarkoittaa, että käyttäjillä on oikeus käyttää, kopioida, jakaa, opiskella, muuttaa ja parantaa koodia. 
Vapaa ohjelmisto ei ole sama kuin ilmainen ohjelmisto.




Kolmen ohjelman lisenssit


Midnight commander

Käyttää lisenssiä GNU General Public License ja siten se luokitellaan vapaaksi ohjelmistoksi (free software). Tiedot löytyivät sivulta https://midnight-commander.org/ ja vapaa lisenssi on tarkistettu sivulta https://www.gnu.org/licenses/license-list.html. Lisenssi tarkoittaa sitä, että käyttäjillä on oikeus käyttää, kopioida, jakaa, opiskella, muuttaa ja parantaa ohjelmistoa.

Espeak 

Käyttää myös lisenssiä GNU General Public License ja se luokitellaan vapaaksi ohjelmistoksi eli käyttäjillä on oikeus käyttää, kopioida, jakaa, opiskella, muuttaa ja parantaa ohjelmistoa. Lisenssin tiedot on saatu nettisivuilta:  https://espeak.sourceforge.net/ ja vapaa lisenssi on tarkistettu sivulta https://www.gnu.org/licenses/license-list.html.

Wordgrinder

Ohjelman lisenssin tiedot löytyivät sivulta: http://cowlark.com/wordgrinder/index.html

Ohjelma käyttää lisenssiä MIT. Tämä lisenssi jäi hieman epäselväksi, että mitä se tarkoittaa. Ilmeisesti lisenssi ei ole copyleft lisenssi, jolloin koodia voidaan käyttää myös suljetun lähdekoodin ohjelmistoissa. Käyttäjillä on kuitenkin oikeus käyttää, muokata ja kopioida teosta. Lisenssi luokitellaan vapaaksi. Tiedot lisenssin vapaudesta on tarkistettu nettisivuilta: https://www.gnu.org/licenses/license-list.html.



Säännölliset lausekkeet

Grep komennon avulla voidaan etsiä tiedostoista säännöllisiä lausekkeita. Tein tätä tehtävää varten harjoitus.txt tiedoston, jossa on listattuna keksittyjä sanoja. Tästä tiedostosta etsin säännöllisiä lausekkeita. Aluksi etsin tiedostosta merkkijonoja, jotka alkoivat kirjaimella E ja päättyivät kirjaimeen ä. Näiden välillä oleva piste tarkoittaa, että merkkien E ja ä välillä etsitään yhtä merkkiä. Tämän jälkeen etsin merkkijonoja, jotka alkavat kirjaimella E ja loppuvat kirjaimeen ä ja joiden välillä on kaksi kirjainta. Alla kuvassa tarkemmin käyttämäni komennot ja saamani tulokset.


<img width="523" alt="Kuva1" src="https://user-images.githubusercontent.com/122889266/214775981-c6a94b95-a7d1-4c03-b1e8-08d73f58afd1.png">

Seuraavaksi kokeilin hakea tiedostosta merkkijonoja, jotka alkavat kirjaimella c ja päättyvät kirjaimeen t ja joiden välillä voi olla vokaaleja aeiou. Alla kuvassa käyttämäni komennot ja saamani tulokset. 


<img width="575" alt="Kuva2" src="https://user-images.githubusercontent.com/122889266/214776365-7a73cbcc-d581-4065-8658-cfcc8a74ef46.png">

Lisäksi kokeilin vielä hakea komennolla grep lukuja väliltä 0-9. Alla kuvassa saamani tulokset ja käyttämäni komennot.

<img width="612" alt="Screenshot 2023-01-26 at 9 15 59" src="https://user-images.githubusercontent.com/122889266/214778066-74c123f7-f852-4a5b-8790-c97f79839dd6.png">



Pipe

Pipe komennon avulla voidaan yhdistää kaksi tai useampia komentoja. Loin tähän tehtävään esimerkkitiedoston hedelmat.txt, jossa on listattuna eri hedelmiä. Aluksi selvitin tiedoston sisällön cat-komennolla, jolloin tiedoston sisältö tulostui ruudulle. 


<img width="556" alt="Screenshot 2023-01-26 at 9 25 44" src="https://user-images.githubusercontent.com/122889266/214779973-b1893a3c-1d00-4ba7-869b-3ab5eec04871.png">

Sen jälkeen yhdistin kaksi käskyä eli cat ja grep -komennot. Siten sain tulostettua tiedostosta tietyn sanan. Toisessa esimerkissä yhdistin käskyt cat ja sort pipen avulla. Sain siten järjestettyä tiedoston sanat aakkosjärjestykseen. 


<img width="697" alt="Screenshot 2023-01-26 at 9 27 41" src="https://user-images.githubusercontent.com/122889266/214780022-51776187-a77b-4510-a208-4bf915e83124.png">


Tehtävä tehty Linux-palvelimet kurssin ohjeiden mukaan:

h3 Vapaus! Karvinen, Tero. Linux palvelimet -kurssi 2023. Luettavissa: https://terokarvinen.com/2023/linux-palvelimet-2023-alkukevat/#h3-vapaus. Luettu 25.1.2023


















