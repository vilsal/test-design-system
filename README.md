
# Beta Design System <!-- omit in toc -->

## Sisällysluettelo <!-- omit in toc -->
- [Typografia](#typografia)
  - [Typografian saavutettavuus](#typografian-saavutettavuus)
- [Kuvat](#kuvat)
  - [Hero-kuva](#hero-kuva)
  - [Julkaisu-elementtien kuvat](#julkaisu-elementtien-kuvat)
    - [Valokuvat](#valokuvat)
    - [Place holder -kuvat](#place-holder--kuvat)
    - [Julkaisu-elementtien kuvien koko](#julkaisu-elementtien-kuvien-koko)
    - [Julkaisu-elementtien kuvien saavutettavuus](#julkaisu-elementtien-kuvien-saavutettavuus)
- [Ikonit](#ikonit)
- [Värit](#värit)
- [Sivupohja](#sivupohja)
  - [Navigaatiopalkki](#navigaatiopalkki)
    - [Navigaatiopalkki pienellä näytöllä](#navigaatiopalkki-pienellä-näytöllä)
    - [Navigaatiopalkki isolla näytöllä](#navigaatiopalkki-isolla-näytöllä)
    - [Mobiilimenu](#mobiilimenu)
  - [Sisältöalue](#sisältöalue)
  - [Sivuston tausta](#sivuston-tausta)
  - [Tekstipalsta](#tekstipalsta)
  - [Blokit](#blokit)
  - [Alatunniste](#alatunniste)
  - [Yläpalkki](#yläpalkki)
    - [Kielivalinnat](#kielivalinnat)
- [Komponentit](#komponentit)
  - [Avainluvut](#avainluvut)
    - [Avainlukujen tyylit](#avainlukujen-tyylit)
  - [Bannerit](#bannerit)
    - [Yleistä bannereista](#yleistä-bannereista)
    - [Bannerien koko](#bannerien-koko)
    - [Neutraali banneri](#neutraali-banneri)
    - [Huomio-banneri](#huomio-banneri)
    - [Varoitus-banneri](#varoitus-banneri)
    - [Bannerien saavutettavuus](#bannerien-saavutettavuus)
  - [Elementtien menut](#elementtien-menut)
  - [Info-laatikko](#info-laatikko)
    - [Info-laatikon tyylit](#info-laatikon-tyylit)
  - [Laajennuspaneeli](#laajennuspaneeli)
    - [Yksittäinen laajennuspaneeli](#yksittäinen-laajennuspaneeli)
    - [Laajennuspaneeliryhmä](#laajennuspaneeliryhmä)
    - [Hierarkinen laajennuspaneelit](#hierarkinen-laajennuspaneelit)
    - [Laajennuspaneeleiden koko](#laajennuspaneeleiden-koko)
    - [Laajennuspaneelin tyylit](#laajennuspaneelin-tyylit)
    - [Laajennuspaneelin saavutettavuus](#laajennuspaneelin-saavutettavuus)
  - [Linkki](#linkki)
    - [Linkkien saavutettavuus](#linkkien-saavutettavuus)
    - [Sisäinen linkki](#sisäinen-linkki)
      - [Tavallinen linkki](#tavallinen-linkki)
      - [Negatiivi-linkki](#negatiivi-linkki)
      - [Linkki tekstin seassa](#linkki-tekstin-seassa)
      - [Linkki ikonilla](#linkki-ikonilla)
    - [Ulkoinen linkki](#ulkoinen-linkki)
  - [Lyhenteiden selitykset -laatikko](#lyhenteiden-selitykset--laatikko)
  - [Murupolku](#murupolku)
    - [Murupolku pienillä näytöillä](#murupolku-pienillä-näytöillä)
    - [Murupolku isoilla näytöillä](#murupolku-isoilla-näytöillä)
  - [Painikkeet](#painikkeet)
    - [Yleistä painikkeiden saavutettavuudesta](#yleistä-painikkeiden-saavutettavuudesta)
    - [Painikkeiden yhteiset ominaisuudet](#painikkeiden-yhteiset-ominaisuudet)
    - [Painikkeiden koko](#painikkeiden-koko)
    - [Ensisijainen painike](#ensisijainen-painike)
    - [Toisijainen painike](#toisijainen-painike)
    - [Kolmassijainen painike](#kolmassijainen-painike)
    - [Negatiivi-painike](#negatiivi-painike)
  - [Pilleri-painikkeet](#pilleri-painikkeet)
    - [Pilleri-painikkeet pienillä näytöillä](#pilleri-painikkeet-pienillä-näytöillä)
    - [Pilleri-painikkeiden tyylit](#pilleri-painikkeiden-tyylit)
    - [Pilleri-painikkeiden saavutettavuus](#pilleri-painikkeiden-saavutettavuus)
  - [Pudotusvalikko](#pudotusvalikko)
    - [Yleistä pudotusvalikoista](#yleistä-pudotusvalikoista)
      - [Pudotusvalikkojen yhteiset tyylit](#pudotusvalikkojen-yhteiset-tyylit)
    - [Tavallinen pudotusvalikko desktop-käyttöliittymissä](#tavallinen-pudotusvalikko-desktop-käyttöliittymissä)
      - [Tavallisen pudotusvalikon tyylit](#tavallisen-pudotusvalikon-tyylit)
    - [Multi select (monen valinnan) pudotusvalikko desktop-käyttöliittymissä](#multi-select-monen-valinnan-pudotusvalikko-desktop-käyttöliittymissä)
      - [Multi select -pudotusvalikon tyylit](#multi-select--pudotusvalikon-tyylit)
    - [Pudotusvalikoiden saavutettavuus](#pudotusvalikoiden-saavutettavuus)
  - [Pääkohdat](#pääkohdat)
  - [Tagit](#tagit)
    - [Aihe-tagit](#aihe-tagit)
    - [Muut tagit](#muut-tagit)
  - [Tilastokuviot](#tilastokuviot)
    - [Kuviot pienillä näytöillä](#kuviot-pienillä-näytöillä)
    - [Kuviot isoilla näytöillä](#kuviot-isoilla-näytöillä)
    - [Kuvion tooltip](#kuvion-tooltip)
    - [Kuvioiden lähdemerkintä](#kuvioiden-lähdemerkintä)
    - [Kuvioiden saavutettavuus](#kuvioiden-saavutettavuus)
    - [Kuvioiden tyylit](#kuvioiden-tyylit)
      - [Kuvioiden fontit](#kuvioiden-fontit)
      - [Kuvioiden hilaviivat](#kuvioiden-hilaviivat)
      - [Kuvioiden akselit](#kuvioiden-akselit)
    - [Kuviotyypit](#kuviotyypit)
      - [Viivakuvio](#viivakuvio)
      - [Piirakkakuvio](#piirakkakuvio)
      - [Pylväskuvio](#pylväskuvio)
  - [Tilastotaulukot](#tilastotaulukot)
    - [Taulukot pienillä näytöillä](#taulukot-pienillä-näytöillä)
    - [Taulukot isoilla näytöillä](#taulukot-isoilla-näytöillä)
      - [Taulukot tekstipalstan sisällä](#taulukot-tekstipalstan-sisällä)
      - [Taulukot muualla kuin tekstipalstan sisällä](#taulukot-muualla-kuin-tekstipalstan-sisällä)
    - [Taulukoiden alaviite](#taulukoiden-alaviite)
    - [Taulukoiden lähdemerkintä](#taulukoiden-lähdemerkintä)
    - [Taulukoiden saavutettavuus](#taulukoiden-saavutettavuus)
    - [Taulukoiden tyylit](#taulukoiden-tyylit)
      - [Taulukkopohjan tyylit](#taulukkopohjan-tyylit)
      - [Taulukon fontit](#taulukon-fontit)
  - [Tooltip](#tooltip)
    - [Tooltipin saavutettavuus](#tooltipin-saavutettavuus)
  - [Video](#video)
    - [Videoelementin koko](#videoelementin-koko)
    - [Videoiden saavutettavuus](#videoiden-saavutettavuus)
  - [Video-blokki](#video-blokki)
    - [Video-blokin tyylit](#video-blokin-tyylit)
  - [Vierityspalkki](#vierityspalkki)
    - [Pystysuuntainen vierityspalkki](#pystysuuntainen-vierityspalkki)
    - [Vaakasuuntainen vierityspalkki](#vaakasuuntainen-vierityspalkki)
  - [Viiva](#viiva)

## Typografia
Fontteina käytetään Googlen ilmaisia fontteja. Vaikka osa fonttien ko'oista on tässä ilmoitettu pikseleinä, ne tulee toteuttaa suhteellisina arvoina (em tai rem). 

| Taso                                                    | Font                            | Font-size                         | Font-family                                                          | Color   | Text-align                      | Vertical-align |
| ------------------------------------------------------- | ------------------------------- | --------------------------------- | -------------------------------------------------------------------- | ------- | ------------------------------- | -------------- |
| **Leipäteksti**                                         | Source Sans Pro, regular        | 16px/1rem                         | Source Sans Pro, Arial, Verdana, Lucida, Helvetica, Sans-serif       | #000000 |                                 |                |
| **H1**                                                  | Barlow, regular                 | 34px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **H2**                                                  | Barlow, regular                 | 28px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **H3**                                                  | Barlow, regular                 | 22px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **H4**                                                  | Barlow, medium                  | 16px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **H5**                                                  | Barlow, medium                  | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **Introteksti** (aiheessa/tarkan aiheessa)              | Barlow, medium                  | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **Tagit**                                               | Barlow, semibold                | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #333333 |                                 |                |
| **Aihe-tagit**                                          | Source Sans Pro, regular        | 14px                              | Source Sans Pro, Arial, Verdana, Lucida, Helvetica, Sans-serif       | #ffffff |                                 |                |
| **Päiväys ja kirjoittaja** (blokkien nostoelementeissä) | Barlow, regular                 | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **Ingressi**                                            | Barlow, regular                 | 17px/1.255rem                     | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |
| **Iso leipäteksti (esim. asiantuntijan nimi)**          | Source Sans Pro, regular        | 18px                              | Source Sans Pro, Arial, Verdana, Lucida, Helvetica, Sans-serif       | #000000 |                                 |                |
| **Label**                                               | Source Sans Pro, semibold       | 17px                              | Source Sans Pro, Arial, Verdana, Lucida, Helvetica, Sans-serif       | #000000 |                                 |                |
| **Murupolku, linkki**                                   | Barlow, medium                  | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #006ca5 |                                 |                |
| **Murupolku, ei linkki**                                | Barlow, medium                  | 14px                              | Barlow, Arial, Verdana, Lucida, Helvetica, Sans-serif                | #000000 |                                 |                |
| **Taulukon otsikko**                                    | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 |                                 |                |
| **Taulukon sarake- ja riviotsikot**                     | Barlow Semi Condensed, semibold | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 | ks. taulukon solujen text-align | bottom         |
| **Taulukon solut: numero tai numeron korvaava teksti**  | Barlow Semi Condensed, regular  | 0.9rem (15px) tai 0.875rem (14px) | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 | right                           | bottom         |
| **Taulukon solut: teksti**                              | Barlow Semi Condensed, regular  | 0.9rem (15px) tai 0.875rem (14px) | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 | left                            | bottom         |
| **Taulukon alaviite**                                   | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 |                                 |                |
| **Taulukon ja kuvion lähdemerkintä**                    | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 |                                 |                |
| **Tilastokuvion otsikko**                               | Barlow Semi Condensed, medium   | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 | center                          |                |
| **Tilastokuvion alaotsikko**                            | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 | center                          |                |
| **Tilastokuvion muut tekstit**                          | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 |                                 |                |
| **Tilastokuvion tooltip**                               | Barlow Semi Condensed, regular  | 1rem (16px)                       | Barlow Semi Condenced, Arial, Verdana, Lucida, Helvetica, Sans-serif | #000000 |                                 |                |

### Typografian saavutettavuus
* Fonttien koot tulee toteuttaa suhteellisina arvoina (em tai rem), jolloin käyttäjät pystyvät suurentamaan niitä halutessaan. 
* Fontteja ei saa muotoilla itse vaan on käytettävä yllä esitettyjä fonttitasoja. Näin ruudunlukijaa käyttävät saavat sivujen rakenteesta oikean käsityksen ja myös fonttityylien yhtenäisyys säilyy. 


## Kuvat
### Hero-kuva

Hero-kuvia käytetään aihe- ja tarkka aihe -sivujen yläosassa. Jokaisella aiheella ja tarkalla aiheella on oma kuvansa. Hero-kuviksi valitaan sellaisia, jotka toimivat monessa koossa. 

![Hero-kuva aihe-sivun mobiili-version yläosassa.](images/herokuva_mobiili.png)

Mobiilissa hero-kuva ulottuu näytön laidasta laitaan. Mobiilinäytöllä näkyy täysikokoisesta kuvasta rajattu tietty kohta. (Kohta määritellään myöhemmin tarkemmin.) Mobiilissa sivun otsikko ja sen sininen tausta tulevat hero-kuvan alle. 

![Hero-kuva aihe-sivun desktop-version yläosassa.](images/herokuva.png)

Desktopissa hero-kuva ulottuu näytön laidasta laitaan kunnes kuvan koko tulee vastaan. Sen jälkeen kuvan vasemmalle ja oikealle puolelle tulee marginaalit. Kuva-alueen korkeus pysyy samana koko ajan ja kuva rajautuu korkeudesta näytön koon kasvaessa. Desktopissa sivun otsikko ja otsikon alla oleva sininen palkki tulee kuvan päälle. 

### Julkaisu-elementtien kuvat

Julkaisu-elementeissä kuvina käytetään joko graafikoiden tekemiä ja valitsemia valokuvia tai place holder -kuvia. Place holder -kuvia käytetään siinä tapauksessa, että julkaisusta ei ole saatavissa valokuvaa.  

![Artikkelien, blogien, videoiden ja muiden julkaisuiden julkaisu-elementeissä käytetään kuvina valokuvia.](images/julkaisu_blogi.png)

Eri sisältötyyppien julkaisu-elementeissä käytetyt kuvat: 

| Julkaisutyyppi      | Ensisijainen kuva                     | Toissijainen kuva                      |
| ------------------- | ------------------------------------- | -------------------------------------- |
| Aikakausjulkaisu    | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Artikkeli           | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Blogi               | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Katsaus             | Perusjulkaisemisen place holder -kuva | -                                      |
| Kokoomajulkaisu     | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Käsikirjat          | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Tiedote             | Perusjulkaisemisen place holder -kuva | -                                      |
| Tietokantajulkistus | Perusjulkaisemisen place holder -kuva | -                                      |
| Tutkimus            | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Video               | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Working paper       | Valokuva                              | Muiden julkaisuiden place holder -kuva |
| Muut julkaisut      | Valokuva                              | Muiden julkaisuiden place holder -kuva |


#### Valokuvat

Osio päivittyy kun valokuvien linjaukset saadaan sovittua. 

Valokuvia käytetään artikkelien, blogien, videoiden, kokoomajulkaisujen, käsikirjojen, aikakausjulkaisujen, tutkimuksien ja working papers -julkaisujen julkaisu-elementeissä. Ts. valokuvia käytetään kun kyseessä on muu kuin perusjulkaisemisen (tiedotteet, tietokantajulkistukset ja katsaukset) sisältötyyppi. Valokuvat ovat graafikoiden tekemiä ja valitsemia. Jos valokuvia ei ole saatavissa, käytetään näille sisältötyypeille tehtyjä omia place holder -kuviaan. Ks. Place holder -kuvat. 

Verkkouudistuksen jälkeen ilmestyvien kansikuvallisten julkaisujen kansikuvana käytetystä kuvasta tai valokuvasta graafikot muotoilevat verkkoon sopivankokoisen kuvan. Vanhoista ennen verkkouudistusta julkaistuista julkaisuista ei tuoda kansikuvia julkaisu-elementteihin, vaan näiden kohdalla käytetään julkaisuille muotoiltua omaa place holder -kuvaa. 

#### Place holder -kuvat

Place holder -kuva on graafinen kuvituskuva, jota käytetään julkaisu-elementeissä kun valokuvaa ei ole saatavilla. 

Osio päivittyy kun place holder -kuvien linjaukset saadaan sovittua. 

#### Julkaisu-elementtien kuvien koko
Julkaisut-elementeissä olevat kuvat käyttävät samaa kuvasuhdetta kuin video-elementti: **16:9**, esim. **resoluutio 1920x1080**. 

Tieto&trendit-sivustolta tuotavat valokuvat rajataan kuvasuhteeseen 16:9. Valokuvia rajataan alareunasta. Tieto&trendit-sivuston place holder -kuvaa rajataan sekä ylä -että alareunasta. 

**Huom!** Julkaisuissa tekstin seassa olevat kuvat ja tilastokuviot eivät välttämättä noudata samaa kuvasuhdetta kuin julkaisu-elementtien kuvat. Etenkin tilastokuvioiden kokoon vaikuttaa niissä oleva data eikä niitä kaikkia voida rajata kooltaan saman kokoisiksi etenkään pituudesta. 

#### Julkaisu-elementtien kuvien saavutettavuus
Julkaisuelementtien kuvat ovat kuvituskuvia eli niillä ei ole mitään informatiivista sisältöä. Ne toimivat linkkeinä julkaisuihin näkeville käyttäjille, mutta ruudunlukijalta ne piilotetaan. Ruudunlukijaa käyttävät pääsevät julkaisuun kuvan alla olevasta julkaisun otsikosta, joka on linkki julkaisun sivulle. 

## Ikonit

Ikoneina käytetään (jo aiemmin käytössä olleita) Font Awesomen ja IcoMoonin ilmaisia perus ikonikirjastoja. Linkki ikonikirjastoihin lisätään myöhemmin. 

## Värit
Väreinä käytetään Tilastokeskuksen väripalettia. Värit täydennetään tänne tai linkki niihin lisätään myöhemmin. 

## Sivupohja

### Navigaatiopalkki

#### Navigaatiopalkki pienellä näytöllä

![Navigaatiopalkki pienellä näytöllä.](images/navipalkki_mobiili.png)

Pienillä näytöillä navigaatiopalkki sisältää oikealta vasemmalle Tilastokeskuksen logon negatiivina, haku-linkin ja menu-painikkeen. Hae-linkin ja menu-painikkeen ikoni ja teksti ovat allekkain, ikoni yllä, teksti alla. 

Pienillä näytöillä navigaatiopalkki ulottuu näytön laidasta laitaan. Tilastokeskuksen logo on tasattu vasempaan laitaan, haku-linkki ja menu-painike oikeaan laitaan. 

Navigaatiopalkki ei ole sticky eli se ei liimaudu näytön ylälaitaan kun sivuja selataan alaspäin. Se on näkyvissä vain sivun yläosassa. 

Navigaatiopalkin tyylit pienillä näytöillä:

| Background-color | Font            | Font-size | Color   | Height | Ikonien color |
| ---------------- | --------------- | --------- | ------- | ------ | ------------- |
| #0073b0          | Barlow, regular | 17px      | #ffffff | 60px   | #ffffff       |

	
#### Navigaatiopalkki isolla näytöllä

![Navigaatiopalkki, Tilastotieto-osio korostettuna.](images/navipalkki.png)

Navigaatiopalkin osiot ovat linkkejä laskeutumissivuille. Linkit erotetaan toisistaan pystyviivalla. 

Se sivuston osio, jossa kulloinkin ollaan, näkyy navigaatiopalkissa korostettuna. Korostuksena käytetään paksua alleviivausta linkin kohdalla. Alleviivaus ulottuu pystyviivasta toiseen pystyviivaan navigaatiopalkin alareunassa. Alleviivaus ei ole ihan kiinni navipalkin alareunassa. Navipalkin alareunasta jää näkyviin 1px-korkuinen sininen osa. Näin valkoinen alleviivaus ei sulaudu sisältöalueen valkoiseen taustaan. 

Samaa alleviivausta käytetään navigaatiopalkin linkeissä hover-tilassa. Jos kaksi vierekkäistä linkkiä ovat alleviivatussa tilassa, niiden väliin jää näkyviin linkkien välissä oleva pystyviiva: 

![Navigaatiopalkki, Tilastotieto- ja Tiedonkeruut-osiot korostettuna.](images/navipalkki_hover.png)

Navipalkin sisältöalue on leveydeltään 1200px eli sama kuin muukin sisältöalue. Navipalkin sisältö pysyy sisältöalueen sisällä, se ei leviä taustan mukana näytön koon kasvaessa. Navipalkin sisältö on samassa linjassa sivun muun sisällön kanssa eli alkaa vasemmassa laidassa samasta kohdasta kuin sivuston muukin sisältö. Navipalkin sisältö haku-linkkiä lukuunottamatta on tasattu vasempaan laitaan eikä siis levity tasaisesti koko navipalkin alueelle. Haku-linkki on erotettu muusta sisällöstä ja tasattu navipalkin oikeaan laitaan. 

![Navigaatiopalkki sisältöaluetta leveämmällä näytöllä.](images/navipalkki_levea.png)

Navigaatio-palkin tausta ulottuu näytön/selainikkunan laidasta laitaan 2500px asti. Siitä isompikokoisilla näytöillä navipalkin oikealle ja vasemmalle puolelle tulee marginaalit. 
*Poikkeus:* 
Jos ollaan sivulla, jossa on bannerikuva (eli aiheen ja tarkennetun aiheen sivuilla), navipalkin tausta loppuu siinä missä bannerikuvakin. 

Navigaatiopalkki ei ole sticky eli se ei liimaudu näytön ylälaitaan kun sivuja selataan alaspäin. Se on näkyvissä vain sivun yläosassa. 

Navigaatiopalkin tyylit isoilla näytöillä:

| Max-width | Background-color | Sisältöalueen leveys | Sisällön tasaus                       |
| --------- | ---------------- | -------------------- | ------------------------------------- |
| 2500px    | #0073b0          | 1200px               | haku-linkki: right, muut linkit: left |

Navigaatiopalkin linkkien tyylit isoilla näytöillä:

| Background-color | Border left/right | Font           | Font-size | Font color | Padding       | Font variant | Text-decoration |
| ---------------- | ----------------- | -------------- | --------- | ---------- | ------------- | ------------ | --------------- |
| #0073b0          | 1px, #338FC0      | Barlow, medium | 1.1rem    | #ffffff    | 1.2rem 1.5rem | normal       | none            |

Alleviivauksen tyylit (sijainti ja navipalkin linkin hover-tila) isoilla näytöillä: 

| Height | Color   |
| ------ | ------- |
| 8px    | #ffffff |

**Huom!** Alleviivaus ei tule ihan kiinni navipalkin alareunaan. Navipalkkia näkyvissä valkoisen alleviivauksen alla 1px. 

#### Mobiilimenu

![Mobiilimenu avattuna.](images/mobiilimenu.png)

Mobiilimenu aukeaa pienen näytön navigaatiopalkin menu-painikkeesta. Mobiilimenu aukeaa navigaatiopalkin alle. Menu sisältää kaikki samat sivuston pääosioiden linkit kuin navigaatiopalkki isoilla näytöillä. 

Se osio, jossa käyttäjä on, korostetaan paksulla sinisellä pystyviivalla linkin vasemmalla puolella. Linkit erotetaan navipalkista ja toisistaan viivalla. 

Kun mobiilimenu avataan menu-painikkeesta, menu-painike muuttuu sulje-painikkeeksi. Menun ikoni muuttuu ruksiksi ja menu-teksti sulje-tekstiksi. Menun saa suljettua sulje-painikkeesta. 

Sivuston pääosioiden linkkien alla on kielivalinnat ja Kirjaudu-painike. Kirjaudu-painikkeen kuvaus ja kuva päivitetään myöhemmin sen designin valmistuttua. 

Mobiilimenun tekstien tyylit:
|        | font            | font-size | color   |
| ------ | --------------- | --------- | ------- |
| linkki | Barlow, regular | 22px      | #0073b0 |

Mobiilimenun muut tyylit:
|                     | color   | height | width |
| ------------------- | ------- | ------ | ----- |
| viiva               | d7d7d7  | 1px    | 100%  |
| korostus-pystyviiva | #0073b0 | 55px   | 10px  |


### Sisältöalue

|             | Leveys | Palstoja max |
| ----------- | ------ | ------------ |
| **Desktop** | 1200px | 3            |
| **Mobiili** |        | 1            |

Sisältöalueen maksimileveys desktopissa on 1200px. Sisältöalue on jaettu desktopissa maksimissaan kolmeen palstaan ja mobiilissa yhteen palstaan. Desktopin kolme palstaa asettuvat responsiivisesti allekkain näytön/selainikkunan pienentyessä. 

### Sivuston tausta

Saavutettavuuden parantamiseksi sivuston tausta ei ole puhtaan valkoinen vaan 2% musta. 

| Background          |
| ------------------- |
| valkoinen, 2% musta |

	
### Tekstipalsta

|             | Width | Text-align |
| ----------- | ----- | ---------- |
| **Desktop** | 555px | left       |
| **Mobiili** |       | left       |

### Blokit

|             | Background-color    | Margin        | Padding                                                                                                  |
| ----------- | ------------------- | ------------- | -------------------------------------------------------------------------------------------------------- |
| **Desktop** | valkoinen, 2% musta | 2.5rem (40px) | 2.5rem (40px)                                                                                            |
| **Mobiili** | valkoinen, 2% musta | 2.5rem (40px) | **Padding-top/bottom**: puolet desktopin paddingista. **Padding-left/right**: 1/4 desktopin paddingista. |

### Alatunniste

Alatunniste koostuu kahdesta osasta. Osat eroavat toisistaan asettelultaan ja ne erotetaan toisistaan viivalla. 

Alatunnisteen tausta ulottuu näytön laidasta laitaan pienillä näytöillä. Isoilla näytöillä alatunnisteen tausta on 2500px leveyteen asti koko näytön levyinen, sen jälkeen vasemmalla ja oikealla puolella alkavat marginaalit. 

Alatunnisteen sisältöalue on leveydeltään 1200px eli sama kuin muukin sisältöalue. Alatunnisteen sisältö pysyy sisältöalueen sisällä, se ei leviä taustan mukana näytön koon kasvaessa. Alatunnisteen ylemmän osan sisältö on samassa linjassa sivun muun sisällön kanssa eli alkaa vasemmassa laidassa samasta kohdasta kuin sivuston muukin sisältö. Alemman osan sisältö on keskitetty. 

Alatunnisteen ylemmässä ja isommassa osassa on neljä palstaa. Ensimmäisen palstan alussa on Tilastokeskuksen logo. Palstat käyttäytyvät responsiivisesti eli näytön pienentyessä palstat menevät allekkain ensin kaksi palstaa per rivi ja pienimmillä näytöillä kaikki palstat ovat allekkain yksi palsta per rivi. 

Alatunnisteen alemmassa osassa on linkkejä, jotka sijoittuvat rinnakkain isoilla näytöillä ja pienillä allekkain. 

Alatunnisten pienillä näytöillä:

![Alatunniste pienillä näytöillä.](images/footer_mobiili.png)

Alatunniste isoilla näytöillä: 

![Alatunniste isoilla näytöillä.](images/footer_desktop.png)

Alatunnisteen tyylit: 
|        | Max-width | Sisältöalueen leveys | Background-color | Palstoja max | Palstan tekstit    | Fontit                                 | Fontin color | Ikonien color |
| ------ | --------- | -------------------- | ---------------- | ------------ | ------------------ | -------------------------------------- | ------------ | ------------- |
| Yläosa | 2500px    | 1200px               | #0073b0          | 4            | Tasattu vasemmalle | Otsikot: H3, Linkit: negatiivilinkkejä | #ffffff      | #ffffff       |
| Alaosa | 2500px    | 1200px               | #0073b0          | 1            | Tasattu keskelle   | Linkit: negatiivilinkkejä              | #ffffff      | #ffffff       |

|       | Max-width | Height | Color   |
| ----- | --------- | ------ | ------- |
| Viiva | 1200px    | 1px    | #ffffff |

### Yläpalkki

![Yläpalkki isolla näytöllä.](images/ylapalkki_desktop.png)

Yläpalkki sijaitsee sivustolla kaikkein ylinpänä. Navigaatiopalkki sijaitsee yläpalkin alapuolella. 

Yläpalkin vasemmassa laidassa on Tilastokeskuksen logo. Oikeassa laidassa on vasemmalta oikealle Kirjaudu-painike ja kielivalinnat, ks. Kielivalinnat. Yläpalkin sisältö noudattaa sivuston sisältöalueen leveyttä eli on 1200px leveä. 

#### Kielivalinnat

Mobiilimenussa kielivalinnat sijaitsevat alareunassa sivuston pääosioiden linkkien jälkeen. Isoilla näytöillä ne sijaitsevat yläpalkin oikeassa reunassa navigaatiopalkin yläpuolella. Kielivalinnat noudattavat pilleri-painikkeiden tyylejä ja toiminnallisuutta. Ks. Pilleri-painikkeet. 

Kielivalinnat pienillä näytöillä: 

![Kielivalinnat mobiilimenussa.](images/kielivalinnat_mobiili.png)

Kielivalinnat isoilla näytöillä: 

![Kielivalinnat yläpalkissa.](images/kielivalinnat_desktop.png)

Käyttäjä pystyy vaihtamaan koko sivuston kielen valitsemalla kielivalinnoista haluamansa kielen. Käyttäjä voi vaihtaa sivuston kielen millä sivulla tahansa. Käyttäjä pidetään samalla sivulla kielen vaihdoksen jälkeen. Kielivalinta-painikeryhmästä se kieli, joka sivustolla on käytössä/aktiivisena, näkyy korostettuna, ks. Pilleri-painikkeiden tyylit. 

Aivan koko sivustoa ei ole saatavissa kaikilla kolmella kielellä. Joillakin kielillä on tarjolla vain osa sivuista tai sivujen sisällöstä. Jos sivusta ei ole saatavissa haluttua kieliversiota, käyttäjän klikattua kielivalinta-painiketta sen alapuolelle ponnahtaa näkyviin tooltip-laatikko, joka kertoo kyseisellä kielellä, ettei sivua ole tällä kielellä saatavissa. Tooltip-laatikossa on linkki etusivulle. Tooltipin saa kiinni valitsemalla kyseisen kielivalinta-painikkeen uudestaan tai tooltipin oikeassa ylänurkassa olevasta ruksista. 

![Mobiilimenun kielivalinnan alle avautunut tooltip, joka kertoo ettei sivua ole saatavissa englanniksi.](images/kielta_ei_saatavilla_mobiili.png)

## Komponentit

### Avainluvut

![Avainluku.](images/avainluku_lyhyt.png)

Avainluvussa kerrotaan yksi tilastoluku, mitä ajankohtaa se koskee sekä tarjotaan reitti eteenpäin tietokantaan ja sivulle, josta löytyy lisätietoa aiheesta. Avainluvun tarkoituksena on kiinnittää käyttäjien huomio ja houkutella heidät tutkimaan lukuun liittyvää tietoa enemmän. Avainluvun voi jakaa myös sosiaalisessa mediassa. 

Avainluvut sisältävät seuraavat elementit:
* otsikko, 
* menu. Menun sisällöstä kerrotaan kohdassa Elementtien menut. 
* avainluku, 
* avainluvun yksikkö, 
* viiteajankohta, 
* muu tarkentava teksti, optionaalinen, 
* linkki avainluvun ensisijaikseksi merkitylle sivulle, ns. "kotisivulle".

![Avainluku kaikkine elementteineen.](images/avainluku_pitka.png)

Avainlukuja on tarkan aiheen, tilaston, tiedotteen ja katsauksen sivuilla. Sama avainluku voi esiintyä useilla eri sivuilla. Avainluku merkitään kuitenkin aina kuuluvaksi ensisijaisesti johonkin tilastoon, tiedotteeseen, katsaukseen tai tarkkaan aiheeseen. Avainluvussa oleva linkki vie tälle avainluvun ensisijaiseksi merkitylle sivulle, ns. avainluvun "kotisivulle". Avainluvussa ei ole linkkiä silloin kun se esiintyy ensisijaikseksi merkityllä sivullaan. 

Avainluvut asettuvat omassa Avainluvut-blokissaan responsiivisesti rinnakkain tai allekkain näytön koosta riippuen. Pienillä näytöillä avainluvut asettuvat allekkain. Isoilla näytöillä avainlukuja on Avainluvut-blokissaan enintään kolme rinnakkain: 

![Avainluku-blokki tilaston sivulla.](images/avainluvut_tilasto_desktop.png)

Avainluku-elementit venyvät tarvittaessa pituutta. Kaikki samalla rivillä olevat avainluvut ovat kuitenkin saman pituisia eli vähemmän sisältöä sisältävät avainluvut venyvät pituutta pisimmän avainluvun mukaan. 

Tiedotteessa avainluvut sijaitsevat ingressin alla ja ennen Pääkohdat-elementtiä kun sivua katsotaan pieneltä näytöltä. Isoilla näytöillä avainluku tai avainluvut asettuvat ingressin oikealle puolelle omaan palstaansa allekkain. **Huom!** Isoilla näytöllä on sama selaus-/lukujärjestys näppäimistökäytössä kuin pienillä näytöillä eli avainlukujen jälkeen siirrytään Pääkohdat-elementtiin. 

![Tiedotteen sivulla olevat avainluvut. Avainluvuissa ei ole linkkiä, koska tiedote on niiden ensisijainen sivu. Ison näytön näkymässä avainluvut asettuvat ingressin oikealle puolelle allekkain.](images/avainluku_tiedote.png)

Avainluvut voivat sijaita katsauksessa tekstin seassa, jolloin ne ottavat tekstipalstan leveyden. 

#### Avainlukujen tyylit
|                                           | Font                        | Font-size | Color   | Background-color |
| ----------------------------------------- | --------------------------- | --------- | ------- | ---------------- |
| Avainluvun laatikko                       |                             |           |         | #f2f2f2          |
| Avainluvun otsikko                        | Barlow, medium              | 14px      | #000000 |                  |
| Avainluku                                 | Barlow Semi Condenced, bold | 65px      | #0073b0 |                  |
| Avainluvun lyhyt yksikkö (max. 2 merkkiä) | Barlow Semi Condenced, bold | 65px      | #0073b0 |                  |
| Avainluvun pitkä yksikkö                  | Barlow Semi Condenced, bold | 35px      | #0073b0 |                  |
| Avainluvun viiteajankohta                 | leipäteksti                 |           |         |                  |
| Avainluvun muu teksti                     | leipäteksti                 |           |         |                  |
| Avainluvun linkki                         | tavallinen linkki nuolella  |           |         |                  |

### Bannerit

#### Yleistä bannereista
Bannerit ovat huomiota herättäviä väliaikaisia elementtejä, joilla viestitään sivustoon ja sen sisältöön liittyvistä muutoksista ja poikkeustilanteista. Bannereiden tarkoitus on vetää käyttäjien huomio puoleensa erottumalla sivuston muusta sisällöstä. Bannereita on eri tyylisiä. Riippuu banneriin tulevasta sisällöstä minkä tyylinen banneri valitaan. 

Banneri ei ole sivuston kiinteä elementti vaan niille määritellään tietty aika, jonka ajan ne ovat verkkosivuilla näkyvissä. Lähtökohtaisesti verkkosivuston loppukäyttäjät eivät saa itse poistettua bannereita näkyvistä, mutta muutamia poikkeuksia voi olla, kuten sivustouudistuksesta kertova banneri. Bannereita tulee käyttää harkitusti ja niillä viestitään vain poikkeuksellisista muutoksista ja tilanteista. 

Bannerit sisältävät aina tekstiä ja sen lisäksi niissä voi olla linkki ja ikoni. Tekstin tulee kertoa ilmoitusasia lyhyesti ja ytimekkäästi. On suositeltavaa tarjota myös linkki sivulle, jossa asiasta kerrotaan lisää. Banneritekstin otsikkona käytetään ns. isoa leipätekstiä ja muun tekstin fonttina tavallista leipätekstiä. Bannereihin ei ole pakollista laittaa otsikkoa. 

#### Bannerien koko
Pienillä näytöillä bannerit ulottuvat näytön laidasta laitaan. Isoilla näytöillä yksittäistä sivua tai sen osaa koskevat bannerit ovat yhtä leveitä kuin se elementti, jonka sisällä ne ovat tai johon ne liittyvät. 

Koko sivustoa koskevat bannerit näkyvät navigaatiopalkin alla ja ovat isoilla näytöillä yhtä leveitä kuin navigaatiopalkki. Esimerkiksi sivustouudistuksesta kertova banneri:
![Neutraali banneri tilaston sivulla, desktop-versio.](images/banneri_sivustouudistus_desktop.png)


#### Neutraali banneri
Neutraalia banneria käytetään ilmoittamaan asiasta, joka käyttäjän on hyvä, mutta ei kriittistä huomata. Neutraali banneri erottuu sivuston muusta sisällöstä hienovaraisesti. 

Neutraali banneri, mobiili-versio:

![Neutraali banneri, mobiili-versio.](images/neutraali_banneri_mobiili.png)

Neutraali banneri, desktop-versio:

![Neutraali banneri, desktop-versio.](images/neutraali_banneri_desktop.png)

Neutraalia banneria voidaan käyttää ilmoittamaan esimerkiksi tilastossa tapahtuneista muutoksista: 

![Neutraali banneri tilaston sivulla, desktop-versio.](images/neutraali_banneri_tilaston_sivulla.png)

Neutraalin bannerin tyylit:
|                               | Font                     | Font-size      | Color   | Text-decoration | Background-color | Border  | Padding                          |
| ----------------------------- | ------------------------ | -------------- | ------- | --------------- | ---------------- | ------- | -------------------------------- |
| **Banneri-laatikko**          |                          |                |         |                 | #ffffff          | #a40084 | top/bottom: 2rem left/righ: 1rem |
| **Otsikko = iso leipäteksti** | Source Sans Pro, regular | 18px           | #000000 |                 |                  |
| **Teksti = leipäteksti**      | Source Sans Pro, regular | 1rem (n. 16px) | #000000 |                 |                  |         |                                  |
| **Linkki**                    | Source Sans Pro, regular | 1rem (n. 16px) | #006ca5 | underline       |                  |         |                                  |


#### Huomio-banneri

Huomio-banneria käytetään ilmoittamaan asiasta, joka käyttäjän on tärkeää huomata. Se erottuu selkeästi sivuston muusta sisällöstä. Huomio-bannerissa on huomiota herättävä taustaväri sekä vasemmassa laidassa iso huutomerkki-ikoni vetämässä käyttäjien huomiota puoleensa ja korostamassa ilmoituksen tärkeyttä.

Huomio-banneri, mobiili-versio:

![Huomio-banneri, mobiili-versio.](images/huomio_banneri_mobiili.png)

Huomio-banneri, desktop-versio:

![Huomio-banneri, desktop-versio.](images/huomio_banneri_desktop.png)

 Huomio-banneria voidaan käyttää esimerkiksi ilmoittamaan tieto, että käyttäjä ei ole uusimman tiedotteen sivulla vaan vanhalla:

![Huomio-banneri vanhan tiedotteen sivulla.](images/huomio_banneri_tiedote_desktop.png)


Huomio-bannerin tyylit:
|                               | Font                     | Font-size      | Color   | Text-decoration | Background-color | Border | Padding                          |
| ----------------------------- | ------------------------ | -------------- | ------- | --------------- | ---------------- | ------ | -------------------------------- |
| **Banneri-laatikko**          |                          |                |         |                 | feead2           |        | top/bottom: 2rem left/righ: 1rem |
| **Otsikko = iso leipäteksti** | Source Sans Pro, regular | 18px           | #000000 |                 |                  |        |                                  |
| **Teksti = leipäteksti**      | Source Sans Pro, regular | 1rem (n. 16px) | #000000 |                 |                  |
| **Linkki**                    | Source Sans Pro, regular | 1rem (n. 16px) | #006ca5 | underline       |                  |        |                                  |
| **Ikoni**                     |                          |                | #000000 |                 |                  |        |                                  |


#### Varoitus-banneri

Varoitus-banneria käytetään kriittisten ilmoitusten ja ongelmia yhteydessä, kuten silloin kun verkkopalvelussa on sen toimintaa haittaava tai estävä häiriö. Varoitus-bannerissa on voimakas taustaväri sekä vasemmassa laidassa iso huutomerkki-ikoni vetämässä käyttäjien huomiota puoleensa ja korostamassa ilmoituksen tärkeyttä.

Varoitus-banneri, mobiili-versio:

![Varoitus-banneri, mobiiliversio.](images/varoitus_banneri_mobiili.png)

Varoitus-banneri, desktop-versio:

![Varoitus-banneri, desktopversio.](images/varoitus_banneri_desktop_paikka.png)

Varoitus-bannerin tyylit
|                               | Font                     | Font-size      | Color   | Text-decoration | Background-color | Border | Padding                          |
| ----------------------------- | ------------------------ | -------------- | ------- | --------------- | ---------------- | ------ | -------------------------------- |
| **Banneri-laatikko**          |                          |                |         |                 | #c30045          |        | top/bottom: 2rem left/righ: 1rem |
| **Otsikko = iso leipäteksti** | Source Sans Pro, regular | 18px           | #ffffff |                 |                  |        |                                  |
| **Teksti = leipäteksti**      | Source Sans Pro, regular | 1rem (n. 16px) | #ffffff |                 |                  |
| **Linkki**                    | Source Sans Pro, regular | 1rem (n. 16px) | #ffffff | underline       |                  |        |
| **Ikoni**                     |                          |                | #ffffff |                 |                  |        |                                  |


#### Bannerien saavutettavuus
* Huomio- ja varoitus-bannerien huutomerkki-ikoni piilotetaan ruudunlukijalta. 
* Jos banneri sisältää linkin, vain tämä linkki on linkki. Koko banneri ei siis toimi linkkinä eikä semanttisesti ole linkki. 

### Elementtien menut

![Avainluvun avattu menu.](images/avainluku_menu.png)

Avainlukujen, tilastotaulukoiden ja tilastokuvioiden oikeasta yläkulmasta löytyy menu-ikoni. Menu sisältää linkin tietokantaan siihen tietokantataulukkoon, josta elementin data on peräisin, datan lataamisen eri formaateissa, linkin elementin jakamiseen sosiaalisessa mediassa sekä suosikkeihin lisäämisen toiminnon (tulossa verkkosivustolle myöhemmin). 

Kun menun avaa, menu-ikoni muuttuu ruksiksi. Ruksista menun saa kiinni. Menun sulkeuduttua ikoni palaa jälleen menu-ikoniksi. Näppäimistökäytössä menun avaaminen, sulkeminen, selaaminen ja valintojen tekeminen toimii samalla tavalla kuin tavalliset pudotusvalikot, ks. kohta Pudotusvalikoiden saavutettavuus. Menu aukeaa menu-ikonin alle elementtinsä päälle sekä pienillä että isoilla näytöillä. 

Menussa ensimmäisenä oleva Taulukko tietokannassa -linkki vie tietokantaan siihen tietokantataulukkoon, josta elementin data on peräisin. Koska tietokantataulukko sijaitsee eri verkkopalvelussa, linkki on ulkoinen linkki, ks. kohta Ulkoinen linkki. 

Dataan pohjautuvien elementtien menuissa on tarjolla ainakin datan lataaminen taulukkomuodossa: mm. xlsx- ja csv-formaateissa. Jos elementti on tilastokuvio, tarjolla on myös datan lataaminen kuvamuodossa: mm. svg- ja png-formaateissa. Formaatti ilmoitetaan suluissa Lataa taulukko - tai Lataa kuvio -tekstien perässä. 

![Tilastokuvion menu sisältää datan lataamisen taulukkomuodon lisäksi kuvamuodossa.](images/menu_kuvio.png)

|                                             | Font            | Color   | Background-color | Border  | Height                       | Width                        |
| ------------------------------------------- | --------------- | ------- | ---------------- | ------- | ---------------------------- | ---------------------------- |
| Menu-ikoni                                  |                 | #000000 |                  |         | (riippuu valitusta ikonista) | (riippuu valitusta ikonista) |
| Ruksi-ikoni                                 |                 | #000000 |                  |         | (riippuu valitusta ikonista) | (riippuu valitusta ikonista) |
| Menun laatikko                              |                 |         | #ffffff          | #c9c9c9 |                              |                              |
| Menun horisontaalinen divider               |                 |         |                  | #c9c9c9 |                              |                              |
| Linkki tietokantataulukkoon                 | Ulkoinen linkki |         |                  |         |                              |                              |
| Muiden toimintojen teksti                   | Leipäteksti     |         |                  |         |                              |                              |
| Menun listan kohdan hover                   |                 |         | #f2f2f2          |         |                              |                              |
| Menun listan kohta selected/pressed-tilassa |                 |         | #f2f2f2          |         |                              |                              |


### Info-laatikko

Info-laatikko on väritaustainen muusta sisällöstä erottuva elementti. Sen sisältö liittyy sivun muuhun sisältöön, mutta sen halutaan erottautuvan muusta sisällöstä.  

![Info-laatikko](images/infobox.png)

![Info-laatikko](images/infobox_levea.png)

Mobiilissa Info-laatikko on aina täysilevyinen. Desktop-koossa info-laatikko voi olla tavallisen blokin sisältöalueen levyinen tai puolet siitä. Info-laatikkoa voidaan käyttää myös oikeassa palstassa. 

![Info-laatikko](images/infobox_valkoinen.png)

Taustaväriltään info-laatikko on joko vaaleansininen tai valkoinen. Tarkemmat tyylit löytyvät kohdasta Info-laatikon tyylit. 

#### Info-laatikon tyylit

|            | Color   | Background-color    | Width                                |
| ---------- | ------- | ------------------- | ------------------------------------ |
| Tausta     |         | #f2f8fb tai #ffffff | mobiili: 100%, desktop: 100% tai 50% |
| Reunaviiva | #0073b0 |                     | 3px                                  |


### Laajennuspaneeli 
(Eng. expansion panel)

Laajennuspaneeli on elementti, jonka otsikon alle on piilotettu sisältöä. Laajennuspaneelia klikkaamalla sisällön saa esiin ja taas piiloon. Laajennuspaneelilla on aina jokin nimi tai otsikko, joka näkyy paneelin sinisellä taustalla. Laajennuspaneeleilla voidaan lyhentää sivun pituutta. Kun niitä käytetään ryhmänä, ne auttavat hahmottamaan laajoja kokonaisuuksia.

#### Yksittäinen laajennuspaneeli

![Kiinni oleva laajennuspaneeli.](images/laajennuspaneeli_kiinni.png)

Laajennuspaneelit ovat oletusarvoisesti suljettuja. Laajennuspaneelia klikkaamalla sisällön saa esiin ja taas piiloon. Suljetun laajennuspaneelin oikean laidan nuoli osoittaa alas.

![Avattu laajennuspaneeli.](images/laajennuspaneeli_auki.png)

Avatun laajennuspaneelin oikean laidan nuoli kääntyy osoittamaan ylös. Ruudunlukijakäyttäjälle tulee kertoa onko laajennuspaneeli auki vai kiinni. 

#### Laajennuspaneeliryhmä

![Laajennuspaneeleita ryhmässä.](images/laajennuspaneeli_ryhmä.png)

Laajennuspaneeleita voidaan käyttää yksittäin tai ryhmässä. Ryhmässä olevien laajennuspaneeleiden sisältöjen tulee muodostaa yhtenäinen kokonaisuus. Useita laajennuspaneeliryhmän osia voi olla avattuna auki samaan aikaan.

Samaan ryhmään kuuluvat laajennuspaneelit asettuvat yleensä allekkain. Ne voivat asettua isoilla näytöillä myös vierekkäin, jos ne eivät tarvitse koko sisältöalueen leveyttä eikä niillä ei ole tarkkaa keskenäistä järjestystä tai hierarkiaa. Tällainen tapaus on esim. Usein kysytyt kysymykset -blokin laajennuspaneelit:  

![Vierekkäin asettuvat kapeat laajennuspaneelit Usein kysytyt kysymykset -blokissa.](images/laajennuspaneeli_vierekkain.png)

#### Hierarkinen laajennuspaneelit

![Sisäkkäin asettuvat hierarkiset laajennuspaneelit.](images/laajennuspaneeli_hierarkinen.png)

Laajennuspaneelit voivat olla hierarkisia. Hierarkia on enintään kaksi tasoa syvä. Sisempi taso on sisennetty ensimmäisen tason alle. Tällä sisennyksellä viestitään visuaalisesti laajennuspaneelien hierarkista rakennetta. Ruudunlukijakäyttäjille on myös välitettävä tieto hierarkiasta. 

#### Laajennuspaneeleiden koko

Laajennuspaneeleiden korkeus on vähintään 60px, mutta ne venyvät tarvittaessa korkeammaksi otsikoidensa tekstien mukaan. Leveydeltään laajennuspaneelit voivat olla blokkinsa koko sisältöalueen levyisiä tai vain puolet siitä. 

#### Laajennuspaneelin tyylit

|                  | Font                                   | Font-size | Color   | Background-color | Min-height |
| ---------------- | -------------------------------------- | --------- | ------- | ---------------- | ---------- |
| Paneeli          | (leipäteksti) Source Sans Pro, regular | 16px/1rem | #000000 | #F2F8FB          | 60px       |
| Nuoli            |                                        |           | #0073B0 |                  |            |
| Paneelin sisältö | (leipäteksti) Source Sans Pro, regular | 16px/1rem | #000000 | #ffffff          |            |

#### Laajennuspaneelin saavutettavuus
* Kaikki käyttäjät eivät välttämättä huomaa laajennuspaneeli-elementtiä tai ymmärrä miten se toimii. Siksi laajennuspaneeliin ei pidä laittaa sellaista sisältöä, joka on käyttäjälle tärkeää huomata tai löytää. 
* Laajennuspaneeliryhmän sisällön tulee muodostaa yhtenäinen kokonaisuus. 
* Ruudunlukijalle tulee kertoa onko laajennuspaneeli auki vai kiinni. 
	
### Linkki

Linkkejä käytetään navigaatiossa sivuston sisällä sekä navigoinnissa ulkoisiin sivustoihin ja palveluihin. 

#### Linkkien saavutettavuus
* Yleisiä Katso lisää -tyylisiä linkkejä on hyvä välttää. Linkin tekstin tulee olla mahdollisimman tarkoitustaan tai kohdesivuaan kuvaava. 
* Linkkien tekstien tulee olla mahdollisimman paljon kohdesivun otsikkoa vastaavia. 
* Jos linkissä on ikoni, ikoni piilotetaan ruudunlukijalta ja sille ei tehdä alt-tekstiä. Poikkeuksena ulkoiselle sivustolle vievien linkkien ikoni. 
* Jos linkki vie ulkoiselle sivustolle, on tämä käytävä linkistä ilmi sekä ruudunlukijaa käyttäville että näkeville käyttäjille. Jo linkin tekstissä olisi hyvä ilmaista, että linkki vie toiseen palveluun. Näkeviä käyttäjiä varten linkin yhteyteen lisätään myös ulkoisen linkin ikoni. Ruudunlukijaa varten ikoniin lisätään alt-teksti, joka kertoo, että linkki vie ulkoiselle sivustolle. 
* Jos linkki avaa tiedoston, on tämä käytävä ilmi sekä näkeville että ruudunlukijaa käyttäville käyttäjille. Linkin loppuun laitetaan esimerkiksi sulkuihin tiedoston muoto: (pdf).
* Linkkien tyylit on pidettävä yhtenäisinä. Navigaatiolinkit ovat poikkeus tästä, niillä on omat tyylinsä. 
* Kaikki linkit toimivat näppäimistökäytössä vain enterillä. 

#### Sisäinen linkki

##### Tavallinen linkki

 Tavallisissa tekstistä erillään olevissa linkeissä on alleviivaus vain hover- ja focus-tilassa. 

| Tila           | Font        | Text-decoration | Color   | Muuta                                 |
| -------------- | ----------- | --------------- | ------- | ------------------------------------- |
| **Tavallinen** | Leipäteksti | none            | #006ca5 |                                       |
| **Hover**      | Leipäteksti | underline       | #0039a6 | Kursori muuttuu kädeksi linkin päällä |
| **Focus**      | Leipäteksti | underline       | #0039a6 | Reunus: 2px, #0073b0                  |
| **Vierailtu**  | Leipäteksti | none            | #551a8b |                                       |

Tavallinen-tila:
![Tavallinen linkki.](images/link.png)

Hover-tila:
![Linkki hover-tilassa.](images/hover_link.png)

Focus-tila:
![Kohdistettuna oleva linkki.](images/focus_link.png)

Vierailtu-tila:
![Vierailtu linkki.](images/visited_link.png)

##### Negatiivi-linkki

Negatiivi-linkki on linkki tummalla taustalla. Tumman taustan vuoksi sen tyylit eri tiloissa hieman eroavat tavallisesta linkistä. 

| Tila           | Font        | Text-decoration | Color   | Muuta                                 |
| -------------- | ----------- | --------------- | ------- | ------------------------------------- |
| **Tavallinen** | Leipäteksti | none            | #ffffff |                                       |
| **Hover**      | Leipäteksti | underline       | #ffffff | Kursori muuttuu kädeksi linkin päällä |
| **Focus**      | Leipäteksti | underline       | #ffffff | Reunus: 2px, #ffffff                  |
| **Vierailtu**  | Leipäteksti | none            | #ffffff |                                       |

Tavallinen-tila:
![Tavallinen negatiivinen linkki.](images/negative_link.png)

Hover-tila:
![Negatiivinen linkki hover-tilassa.](images/negative_hover_link.png)

Focus-tila:
![Negatiivinen linkki kohdistettuna.](images/focus_negative_link.png)

Vierailtu-tila:
![Vierailtu negatiivinen linkki.](images/negative_link.png)

##### Linkki tekstin seassa

Tekstin seassa, eli p-elementin sisällä, olevat linkit alleviivataan aina. Muissa linkeissä on alleviivaus vain hover- ja focus-tilassa. 

![Tekstin seassa olevat linkit alleviivataan.](images/linkkip.png)

| Tila           | Font        | Text-decoration | Color   | Muuta                                 |
| -------------- | ----------- | --------------- | ------- | ------------------------------------- |
| **Tavallinen** | Leipäteksti | underline       | #006ca5 |                                       |
| **Hover**      | Leipäteksti | underline       | #0039a6 | Kursori muuttuu kädeksi linkin päällä |
| **Focus**      | Leipäteksti | underline       | #0039a6 | Reunus: 2px, #0073b0                  |
| **Vierailtu**  | Leipäteksti | underline       | #551a8b |                                       |


##### Linkki ikonilla

Ikoneja voidaan käyttää linkkien osana helpottamaan linkin tunnistamista tai huomaamista. 

![Linkkejä ikonien kanssa.](images/icons_link.png)

Ikoni tulee linkin eteen (poikkeuksena ulkoinen linkki, jossa ikoni tulee tekstin jälkeen) ja on samanvärinen kuin linkin teksti. Ikoni on osa linkkiä. 

![Nuoli linkin perässä korostaa sitä, että linkistä tapahtuu jotain.](images/linkki_nuoli.png)

![Nuoli linkin perässä, negatiivinen linkki.](images/negative_link_icon.png)

Yksittäisessä erillään olevassa linkissä linkin perässä oleva nuoli korostaa, että linkistä tapahtuu jotain. Nuoli on aina linkin perässä. Nuoli-ikoni ei ole osa linkkiä, siitä klikkaamalla ei tapahdu mitään. 

![Linkillä voi olla kaksi ikonia.](images/link_kaksi_ikonia.png)

Linkeillä voi olla myös kaksi ikonia. Ikonit asettuvat silloin linkkitekstin molemmille puolille. 

Linkkien ikonien tyylit:

| Ikoni                         | Color   |
| ----------------------------- | ------- |
| **Nuoli**                     | #000000 |
| **StatFin/database**          | #f59a23 |
| **Muut ikonit**               | #0073b0 |
| **Negatiivi-linkkien ikonit** | #ffffff |

#### Ulkoinen linkki

![Ulkoiseen palveluun vievä linkki.](images/ulkoinen_link.png)

Ulkoisen linkin tekstissä pyritään kertomaan, että linkki vie toiseen sivustoon tai palveluun. Linkkitekstin perässä on ulkoisen linkin ikoni, joka on osa linkkiä. Ruudunlukijaa varten ikoniin lisätään alt-teksti, joka kertoo, että linkki vie ulkoiselle sivustolle. Ikonin alt-tekstissä lukee: Siirryt toiseen verkkopalveluun. 

### Lyhenteiden selitykset -laatikko

Lyhenteiden selitykset -laatikko sisältää lyhenteiden ja merkkien selityksiä siellä missä niitä on tarpeen selittää käytäjille. Laatikko esiintyy esimerkiksi tietokantataulukoiden yhteydessä, jolloin se sisältää selitykset siitä mitä tietokantataulukoiden viiteajankohdissa olevat lyhenteet tarkoittavat. Laatikko sijaitsee sivulla tai blokissa ennen niitä elementtejä, joiden sisältöön se liittyy. 

Mobiilissa ja pienillä näytöillä laatikon sisältö menee allekkain:

![Mobiilissa laatikon sisältö on järjestäytynyt allekkain.](images/lyhenteidenselitykset_laatikko_mobiili.png)

Isoilla näytöillä laatikko ja laatikon sisältö sisältö levittäytyy sivusuunnassa. Tietokantataulukoiden yhteydessä se on yhtä leveä kuin tietokantataulukoiden väliset dividerit eli se asettuu niiden kanssa samaan linjaan:

![Isolla näytöllä laatikko ja sen sisältö on levittäytynyt sivusuunnassa.](images/lyhenteidenselitykset_laatikko_desktop.png)

|              | Font                          | Font-size   | Border       | Width                                                                 | Padding                           |
| ------------ | ----------------------------- | ----------- | ------------ | --------------------------------------------------------------------- | --------------------------------- |
| **Label**    | Pudotusvalikon label:n fontti |             |              |                                                                       |                                   |
| **Lyhenne**  | Source Sans Pro semibold      | 1rem (16px) |              |                                                                       |                                   |
| **Teksti**   | Leipätekstin fontti           |             |              |                                                                       |                                   |
| **Laatikko** |                               |             | #aaaaaa, 1px | Desktopissa: saman levyinen kuin tietokantataulukko-elementin divider | top/bottom: 2rem left/right: 1rem |


### Murupolku

Murupolku on navigaatioelementti, josta pääsee siirtymään sivuhierarkiassa ylöspäin. Murupolku tulee merkitä semanttisesti navigaatioelementiksi.

Murupolun fonttina on H5-otsikkotason fontti. Murupolkun linkkiosat käyttäytyvät kuten tavalliset linkit kaikkine eri tiloineen.

Murupolku käyttäytyy pienillä ja isoilla näytöillä hieman eri tavoin. 


#### Murupolku pienillä näytöillä

Pienillä näytöillä, jos murupolku koostuu vain kahdesta osasta (linkkiosa ja kyseinen sivu), näytetään koko murupolku. Jos murupolku on siis lyhyt ja mahtuu todennäköisesti yhdelle tai kahdelle riville pienellä näytöllä, näytetään koko murupolku. Murupolun osat erotetaan toisistaan /-merkillä. **Murupolun viimeinen kohta ei ole linkki.** 

Esim. murupolku tilaston sivulla pienellä näytöllä: 

![Pienillä näytöillä näytettävä kahden kohdan murupolku, joka mahtuu yhdelle riville.](images/murupolku_mobiili1.png)

Jos murupolussa on enemmän kohtia kuin kaksi, murupolun sijaan on vain yksi linkki ylemmälle hierarkian tasolle. Näin estetään murupolun rivittyminen usealle riville ja liika tilan vieminen pienillä näytöillä. 

Esim. pienellä näytöllä tiedotteen sivulla murupolkuna näkyy linkki tilaston sivulle:

![Pienellä näytöllä pitkä murupolku lyhenee vain yhdeksi linkiksi ylemmälle hierarkian tasolle.](images/murupolku_mobiili2.png)

|                                             | Murupolun muoto                       |
| ------------------------------------------- | ------------------------------------- |
| **Desktop**                                 | Linkki ylemmälle tasolle / Sivun nimi |
| **Mobiili (max. kaksi kohtaa murupolussa)** | Linkki ylemmälle tasolle / Sivun nimi |
| **Mobiili (yli kaksi kohtaa murupolussa)**  | < Linkki ylemmälle tasolle            |


#### Murupolku isoilla näytöillä

Isoilla näytöillä näytetään murupolku kokonaan. **Huom!** Murupolun viimeinen kohta ei ole linkki. Murupolun osat erotetaan toisistaan /-merkillä. Esim. murupolku tiedotteen sivulla: 

![Isolla näytöllä murupolusta näytetään kaikki tasot.](images/murupolku.png)


| Murupolun osa | Font           | Font-size | Color   | Muuta                                  |
| ------------- | -------------- | --------- | ------- | -------------------------------------- |
| **Linkki**    | Barlow, medium | 14px      | #006ca5 | samat tilat kuin tavallisella linkillä |
| **Viimeinen** | Barlow, medium | 14px      | #000000 | ei linkki                              |


### Painikkeet

Painike käynnistää toiminnon. Painikkeita on neljää eri tyyliä ja niiden koko vaihtelee laitteen tai selainikkunan koosta riippuen. 

#### Yleistä painikkeiden saavutettavuudesta

* Painike käynnistää jonkin toiminnon. 
* Painikkeen tekstissä kerrotaan lyhyesti ja ytimekkäästi minkä toiminnon painike käynnistää. 
* Painikkeet, etenkin ensisijaiset painikkeet erottuvat muusta käyttöliittymästä helposti, joten on suositeltavaa käyttää niitä vain rajattu määrä.
* Painiketyylejä ei käytetä linkeissä linkkityylien asemasta.

#### Painikkeiden yhteiset ominaisuudet

Nämä ominaisuudet pätevät kaikille painikkeille painikkeen tyypistä tai laitteen/selainikkunan koosta riippumatta. 

| Font                     | Font-size | Border-radius | Min-width | Min-height | Focus-kehys |
| ------------------------ | --------- | ------------- | --------- | ---------- | ----------- |
| Source Sans Pro, regular | 16px/1rem | 5px           | 80px      | 40px       | 2px         |

#### Painikkeiden koko

**Painikkeiden koko mobiilissa**

![Painikkeet ovat mobiilissa täysleveitä.](images/buttons_mobile.png)

Mobiilissa tai pienessä selainikkunassa painikkeet ovat täysleveitä lukuunottamatta niiden oikealle ja vasemmalle puolelle jääviä marginaaleja. 

**Painikkeiden koko desktopissa**

![Painikkeiden koko ja eri tilat desktopissa.](images/buttons.png)

Isoilla näytöillä eli desktopissa painikkeiden leveys skaalautuu painikkeen tekstin mukaan. Minimi-leveys painikkeille on kuitenkin 80px. 

#### Ensisijainen painike

![Ensisijaisen painikkeen eri tilat.](images/primary_buttons.png)

| Tila                 | Color   | Background-color | Border | Box-shadow                              | Focus-kehys color |
| -------------------- | ------- | ---------------- | ------ | --------------------------------------- | ----------------- |
| **Tavallinen**       | #ffffff | #0073b0          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)   |                   |
| **Selected/pressed** | #ffffff | #0073b0          | -      | 2px, 2px, 5px, rgba(5,3,112,0.35) inset |                   |
| **Disabled**         | #666666 | #f2f2f2          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)   |                   |
| **Hover**            | #ffffff | #338fc0          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)   |                   |
| **Focus**            | #ffffff | #338fc0          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)   | #0073b0           |


#### Toisijainen painike

![Toissijaisen painikkeen eri tilat.](images/secondary_buttons.png)

| Tila                 | Color   | Background-color | Border  | Box-shadow                                  | Focus-kehys color |
| -------------------- | ------- | ---------------- | ------- | ------------------------------------------- | ----------------- |
| **Tavallinen**       | #0073b0 | #ffffff          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Selected/pressed** | #0073b0 | #ffffff          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35) inset |                   |
| **Disabled**         | #7f7f7f | #ffffff          | #aaaaaa | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Hover**            | #0073b0 | #f2f2f2          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Focus**            | #0073b0 | #f2f2f2          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35)       | #0073b0           |

#### Kolmassijainen painike

![Kolmassijaisen painikkeen eri tilat.](images/tertiary_buttons.png)

| Tila                 | Color   | Background-color | Border | Box-shadow                                  | Focus-kehys color |
| -------------------- | ------- | ---------------- | ------ | ------------------------------------------- | ----------------- |
| **Tavallinen**       | #0073b0 | #f2f8fb          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Selected/pressed** | #0073b0 | #f2f8fb          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35) inset |                   |
| **Disabled**         | #666666 | #f2f2f2          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Hover**            | #000000 | #f2f8fb          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)       |                   |
| **Focus**            | #000000 | #f2f8fb          | -      | 2px, 2px, 5px, rgba(102,102,102,0.35)       | #0073b0           |

#### Negatiivi-painike

Negatiivi-painike on painike tummalla taustalla. Negatiivi-painikkeen tyylit ovat pitkälti samanlaiset kuin toissijaisen painikkeen tyylit, varjostuksia ja focus-kehyksen väriä lukuunottamatta. Negatiivi-painikkeen ulkoinen varjostus on hieman isompi ja tummempi kuin toissijaisen painikkeen. Tämä johtuu siitä, että negatiivi-painiketta käytetään tumman taustan päällä. Isompi ja tummempi varjostus erottuu tummasta taustasta paremmin. Negatiivi-painikkeen focus-kehyksen väri on valkoinen. 

![Negatiivi-painikkeen eri tilat.](images/negative_buttons.png)

| Tila                 | Color   | Background-color | Border  | Box-shadow                                  | Focus-kehys color |
| -------------------- | ------- | ---------------- | ------- | ------------------------------------------- | ----------------- |
| **Tavallinen**       | #0073b0 | #ffffff          | #0073b0 | 4px, 4px, 5px, rgba(85,85,85,0.35)          |                   |
| **Selected/pressed** | #0073b0 | #ffffff          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35) inset |                   |
| **Disabled**         | #7f7f7f | #ffffff          | #aaaaaa | 4px, 4px, 5px, rgba(85,85,85,0.35)          |                   |
| **Hover**            | #0073b0 | #f2f2f2          | #0073b0 | 4px, 4px, 5px, rgba(85,85,85,0.35)          |                   |
| **Focus**            | #0073b0 | #f2f2f2          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35)       | #ffffff           |

### Pilleri-painikkeet

Pilleri-painikkeet on painikkeita, joilla on aktiivinen ja epäaktiivinen tila. Painikkeet vaikuttavat sivuston käyttöliittymään tai osaan siitä. Sivuston käyttöliittymä muuttuu sen mukaan mikä painikkeista on aktiivisena. 

![Sivuston kielen valinnassa käytetään pilleri-painikkeita. Vain yksi kieli voi kerrallaan olla valittuna.](images/kielivalinta.png)

Pilleri-painikkeet esiintyvät vähintään kahden painikkeen ryhmissä. Ryhmän painikkeista vain yksi voi olla kerrallaan aktiivinen. Kun toinen painike aktivoidaan, aikaisemmin aktiivisena ollut painike menee epäaktiiviseen tilaan. Toiminnaltaan pilleri-painikkeet muistuttavat siis radio buttoneita ja välilehtiä. 

Pilleri-painikkeet eroavat visuaalisesti muista painikkeista pyöreämmällä ulkomuodollaan. Pilleri-painikkeissa voi olla ikoni mukana havainnollistamassa painikkeet toimintoa. Esim. Julkaisut-listaussivulla pilleri-painikkeilla voi muuttaa listan kuvien kanssa näytettäväksi tai pelkäksi tekstiksi. Pilleri-painikkeissa on mukana näitä toimintoja kuvaavat ikonit: 

![Julkaisut-listaussivulla ikoneilla havainnollistetaan pilleri-painikkeiden toimintoja.](images/listanakyma_painikkeet.png) 

#### Pilleri-painikkeet pienillä näytöillä

Pienillä näytöillä pilleri-painikkeiden fontti on isompi ja ei-aktiivisissa pilleri-painikkeissa on reunus. Esim. mobiilimenun kielivalinnat: 

![Kielivalinnat mobiilimenussa.](images/kielivalinnat_mobiili.png)

#### Pilleri-painikkeiden tyylit

| Tila                      | Font                    | Font-size   | Padding | Color   | Background-color | Border       | Border-radius | Ikonin color |
| ------------------------- | ----------------------- | ----------- | ------- | ------- | ---------------- | ------------ | ------------- | ------------ |
| **Mobiili aktiivinen**    | Source Sans Pro regular | 18px        | 2px     | #ffffff | #0073b0          | -            | 32px          | #ffffff      |
| **Mobiili epäaktiivinen** | Source Sans Pro regular | 18px        | 2px     | #0073b0 | #ffffff          | 1px, #0073b0 | 32px          | #0073b0      |
| **Desktop aktiivinen**    | Source Sans Pro regular | 1rem (16px) | 2px     | #ffffff | #0073b0          | -            | 32px          | #ffffff      |
| **Desktop epäaktiivinen** | Source Sans Pro regular | 1rem (16px) | 2px     | #0073b0 | #ffffff          | -            | 32px          | #0073b0      |


#### Pilleri-painikkeiden saavutettavuus
* Käyttäjille kerrotaan kunkin pilleri-painikkeen kohdalla kumpi painikkeen tiloista on päällä. Painikkeen visuaalinen ilme vaihtuu selkeästi painikkeen tilan mukaan. Aktiivisen painikkeen alt-tekstissä kerrotaan "Valittu" ja epäaktiivisen kohdalla "Ei valittu", jotta ruudunlukijaa käyttävät saavat myös tiedon painikkeen tilasta. 
* Pilleri-painikkeet voi rinnastaa toiminnaltaan ja teknisesti radio buttoneihin tai välilehtiin. Radio buttonien ja välilehtien tapaan niiden tulee kuulua html:ssä samaan ryhmään. 

### Pudotusvalikko
(Eng. dropdown)

Pudotusvalikko on elementti, jonka tarjoamista vaihtoehdoista valitaan yksi tai useampi. Pudotusvalikoita on kahdenlaisia:
1.  tavallinen pudotusvalikko: pudotusvalikon vaihtoehdoista valitaan yksi. 
2.  multi select: pudotusvalikon vaihtoehdoista voidaan valita useita. 

#### Yleistä pudotusvalikoista

* Jokaisella pudotusvalikolla on valikon nimike eli label, joka kertoo lyhyesti mitä pudotusvalikko sisältää. Label on yleensä pudotusvalikon yllä (esim. filttereissä), mutta se voi olla myös pudotusvalikon vieressä (Näytä tuloksia sivulla -pudotusvalikko). Label noudattaa label-tekstin tyylejä, ks. Typografia. 
* Valittu vaihtoehto tai vaihtoehdot tulevat näkyviin pudotusvalikon kenttään. 
* Pudotusvalikot venyvät leveyttä sisältönsä mukaan, kaikki eivät siis välttämättä ole samanlevyisiä. 

Kapea pudotusvalikko, jonka label on valikon vieressä:

![Kapean sisällön vuoksi kapea pudotusvaliko.](images/dropdown_pieni.png)

Leveä pudotusvalikko, jonka label on valikon yläpuolella:

![Leveämmän sisällön vuoksi leveä pudotusvalikko.](images/pudotusvalikko_iso.png)

* Pudotusvalikoissa käytetään selainten ja mobiilikäyttöjärjestelmien valmiita elementtejä ja niiden toiminnallisuutta niin pitkälle kuin mahdollista. Esim. pudotusvalikon avautumisen tyylinä pidetään selaimen pudotusvalikossa käytössä oleva avautumistyyli. Elementtien visuaalinen ilme muotoillaan Tilastokeskuksen ilmeeseen sopiviksi. 


##### Pudotusvalikkojen yhteiset tyylit

Nämä tyylit ovat kaikille pudotusvalikoille yhteisiä.

|                            | Font                     | Font-size | Color   | Background-color | Border  |
| -------------------------- | ------------------------ | --------- | ------- | ---------------- | ------- |
| **Pudotusvalikon label**   | Source Sans Pro Semibold | 17px      | #000000 |                  |         |
| **Pudotusvalikko**         |                          |           | #ffffff |                  | #c9c9c9 |
| **Kentän nuoli**           |                          |           | #0073b0 |                  |         |
| **Pudotusvalikon tekstit** | Source Sans Pro regular  | 16px/1rem | #000000 |                  |         |

#### Tavallinen pudotusvalikko desktop-käyttöliittymissä

![Kiinni oleva pudotusvalikko.](images/pudotusvalikko.png)

Tavallisesta pudotusvalikosta voi valita vain yhden listan vaihtoehdoista. Kentässä näkyy mikä valikon vaihtoehdoista on valittuna. Valikon kenttää klikkaamalla valikko avautuu ja vaihtoehdot tulevat näkyviin. Kun valikko on kiinni, kentän nuoli osoittaa alaspäin. Avatun valikon nuoli osoittaa ylöspäin: 

![Avattu pudotusvalikko.](images/pudotusvalikko_auki.png)

Valittu vaihtoehto näkyy pudotusvalikon kentässä sekä valikon listassa korostettuna. Valintatoiminto sulkee valikon. Komponentin ruudunlukija- ja näppäimistökäyttö on kuvattu kohdassa Pudotusvalikoiden saavutettavuus. 

![Pudotusvalikkoon, jossa on paljon sisältöä tulee hakukenttä ja vieritysominaisuus.](images/pudotusvalikko_iso.png)

Jos pudotusvalikossa vaihtoehtoja on yli 14, valikko ei veny pituutta vaan siitä tulee pystysuunnassa vieritettävä. Valikon oikeaan laitaan tulee näkyviin vierityspalkki. Vierityspalkin tyyli löytyvät alempaa kohdasta Vierityspalkki. 

Jos pudotusvalikko sisältää yli 20 vaihtoehtoa, valikon sisään on hyvä lisätä hakutoiminnallisuus ja hakukenttä, ks. kuva yllä. Näin käyttäjät voivat hakea pitkästäkin listasta haluamaansa vaihtoehtoa nopeasti. Hakukentän paikka avatussa valikossa on heti ylhäällä ennen listaa. 

##### Tavallisen pudotusvalikon tyylit

Tässä on kerrottu vain tavallisia pudotusvalikkoja koskevat tyylit. Osa tyyleistä on määritetty kohdassa Pudotusvalikkojen yhteiset tyylit. 

|                               | Font                    | Font-size | Color   | Background-color | Border  |
| ----------------------------- | ----------------------- | --------- | ------- | ---------------- | ------- |
| **Valikon vaihtoehdon hover** | Source Sans Pro regular | 16px/1rem | #000000 | #f2f2f2          | #c9c9c9 |
| **Valittu vaihtoehto**        | Source Sans Pro regular | 16px/1rem | #000000 | #f2f2f2          | #c9c9c9 |

#### Multi select (monen valinnan) pudotusvalikko desktop-käyttöliittymissä

Multi select -pudotusvalikosta voi valita useamman vaihtoehdon.

Avatussa multi select -pudotusvalikossa jokaisen vaihtoehdon vasemmalla puolella on checkbox-valintaruutu. Vaihtoehdon valinta tehdään klikkaamalla joko valintaruutua tai tekstiä, samoin valinnan poisto. Valitun vaihtoehton valintaruudussa on täppä.

Multi select -pudotusvalikossa on oletuksena valittuna Kaikki xxx -vaihtoehto (kohdan "xxx" teksti riippuu pudotusvalikon sisällöstä ja labelista). Kaikki xxx -vaihtoehto on avatussa valikossa listan ensimmäisenä. Kun Kaikki xxx -vaihtoehto on valittuna, myös kaikissa muissa listan vaihtoehdoissa on täppä ilmaisemassa, että ne kaikki on todella valittu:  

![Multi select -pudotusvalikosta voidaan valita useita vaihtoehtoja. Oletuksena kaikki valikon vaihtoehdot on valittu. ](images/multi_dropdown_desktop_auki.png)

Jos valinta eli täppä otetaan pois yhdestä listan vaihtoehdoista, poistuu myös kohdan Kaikki xxx täppä, koska kaikki vaihtoehdot eivät silloin enää ole valittuna:

![Multi select -pudotusvalikko kun valinta on poistettu yhdestä listan vaihtoehdosta.](images/multi_dropdown_desktop_auki_4.png)

Jos täppä poistetaan kaikista listan vaihtoehdoista, täppä palaa kohtaan Kaikki xxx. Eli jos mitään ei ole valittuna, kaikki on valittuna, koska ei voi olla tilannetta, jossa multi select -pudotusvalikon listasta ei olisi mitään valittuna:   

![Multi select -pudotusvalikko kun kaikki listan vaihtoehtojen täpät on poistettu.](images/multi_dropdown_desktop_auki_3.png)

Jos kaikista listan kohdista poistetaan valinta kuten yllä kuvattiin ja valikko sitten suljetaan ja avataan taas uudestaan, täpät ovat jälleen palanneet kaikkiin listan kohtiin: 

![Multi select -pudotusvalikko sulkemisen ja uudelleen avaamisen jälkeen kun valinnat oli ennen sulkemista poistettu kaikista listan kohdista.](images/multi_dropdown_desktop_auki.png)

Kun vain yksi vaihtoehto on valittuna, pudotusvalikon kentässä näkyy kyseinen valinnan teksti. Kun on valittu useampia vaihtoehtoja, kentässä näkyy valintojen lukumäärä, esim. 5 valittu. Jos kaikki vaihtoehdot ovat valittuna (Kaikki xxx), kentässä lukee Kaikki xxx. 

![Multi select -pudotusvalikon kentässä lukee "5 valittu" kun pudotusvalikon listasta on valittu 5 vaihtoehtoa.](images/multi_dropdown_desktop_auki_2.png)

Multi select -pudotusvalikoiden valinnat otetaan käyttöön kun valikko suljetaan. Multi select -pudotusvalikon voi sulkea klikkaamalla valikon kenttää tai valikon ulkopuolelle. Multi select -pudotusvalikko ei siis toimi kuten tavallinen pudotusvalikko, joka sulkeutuu aina kun valintatoiminto tehdään. Komponentin ruudunlukija- ja näppäimistökäyttö on kuvattu kohdassa Pudotusvalikoiden saavutettavuus. 

Jos pudotusvalikossa vaihtoehtoja on yli 14, valikko ei veny pituutta vaan siitä tulee pystysuunnassa vieritettävä. Valikon oikeaan laitaan tulee näkyviin vierityspalkki. Vierityspalkin tyyli löytyvät alempaa kohdasta Vierityspalkki. 

##### Multi select -pudotusvalikon tyylit

Tässä on kerrottu vain Multi select -pudotusvalikkoja koskevat tyylit. Osa tyyleistä on määritetty kohdassa Pudotusvalikkojen yhteiset tyylit.  

|                                    | Color   | Background-color | Border | Height             | Width              |
| ---------------------------------- | ------- | ---------------- | ------ | ------------------ | ------------------ |
| **Checkbox-valintaruutu**          | #ffffff | #c9c9c9          | 23px   | 23px               |
| **Valitun checkboxin check-ikoni** | #0073b0 |                  |        | (riippuu ikonista) | (riippuu ikonista) |

#### Pudotusvalikoiden saavutettavuus

* Pudotusvalikolla on nimike eli label. Label kertoo lyhyesti mitä pudotusvalikko sisältää. 
* Ruudunlukijaa käyttäville kerrotaan pudotusvalikon status eli onko valikko kiinni vai auki.
* Ruudunlukijaa käyttäville kerrotaan mikä tai mitkä valikon vaihtoehdoista ovat valittuna.
* Näppäimistökäytössä noudatetaan html-pudotusvalikoiden oletustoiminnallisuutta: 
  * Pudotusvalikot avataan enterillä tai välilyönnillä (space). 
  * Pudotusvalikon suljetaan tabulaattorilla tai enterillä. 
  * Pudotusvalikoiden sisältöä selataan ylös ja alas nuolinäppäimillä. Kun lista loppuu, focus ei palaa automaattisesti listan alkuun tai siirry eteenpäin seuraavaan pudotusvalikkoon. Ylös on palattava jälleen ylös-nuolinäppäimellä. 
  * Tavallisessa pudotusvalikossa valinta tehdään joko enterillä tai tabulaattorilla. Kummatkin tavat suorittavat samalla sekä vaihtoehdon valinnan että sulkevat pudotusvalikon. 
  * Multi select -pudotusvalikossa vaihtoehtojen valinta tapahtuu pitämällä ctrl-näppäintä pohjassa koko ajan listassa liikuttaessa ja tekemällä valinnat välilyönti-painikkeella. 
  * Tabulaattorilla liikutaan pudotusvalikoiden välillä. Huom! Tabulaattori ei avaa pudotusvalikoita! Yksi tabulaattorin painallus sulkee avatun pudotusvalikon ja toinen painallus siirtää käyttäjän toisen pudotusvalikon kohdalle. 
 

### Pääkohdat

Pääkohdat-elementissä kerrotaan tiiviisti tilastojulkistuksen tärkeimmät asiat. Elementissä voi olla 2-5 kohtaa, jokainen kerrottuna yhdellä lauseella. Kohdat esitetään listana ja erotetaan toisistaan pienillä pallo-listamerkeillä.  Pääkohdat-elementti sijaitsee tilastojulkistuksessa ingressin alla. 

![Pääkohdat kertovat tiiviisti tilastojulkistuksen tärkeimmät asiat.](images/paakohdat.png)

|                                        | Font            | Font-size | Color   |
| -------------------------------------- | --------------- | --------- | ------- |
| **Pääkohdat-otsikko (H2-fontti)**      | Barlow, regular | 28px      | #000000 |
| **Pääkohtien lista (Ingressi-fontti)** | Barlow, regular | 17px      | #000000 |

Tekstissä on riippuva sisennys eli kaikki tekstirivit ovat samassa linjassa pallo-listamerkkien oikealla puolella. Tekstit eivät siis mene pallo-listamerkkien alle ts. pääkohdat-listassa käytetään css-listan normaalia toiminnallisuutta. (Yllä oleva kuva ei vastaa tältä osin visuaalisesti haluttua toteutusta.)

Desktop-koossa elementin vasemmalla puolella on ohut elementin kanssa samankorkuinen pystyviiva korostamassa elementtiä muusta sivun sisällöstä. Mobiili-koossa tätä pystyviivaa ei ole. 

|                      | Color   | Height           | Width     | Muuta             |
| -------------------- | ------- | ---------------- | --------- | ----------------- |
| **Pallot**           | #000000 | (default)        | (default) |                   |
| **Vasen pystyviiva** | #000000 | elementin pituus | 1px       | ei ole mobiilissa |

### Tagit

#### Aihe-tagit

Aihe-tagit ovat linkkejä niiden aiheiden- ja tarkkojen aiheiden -sivuille, joihin sivu kuuluu. Niitä on tarkkojen aiheiden, tilastojen, tiedotteiden, katsausten ja Muutoksia tilastossa -tiedotteiden sivuilla. Niitä voi olla yhdellä sivulla useita, sillä sivu voi kuulua useaan eri aiheeseen ja tarkkaan aiheeseen. 

![Aihe-tageja voi olla yhdellä sivulla monta.](images/aihe_tagit.png)

Aihe-tagit sijaitsevat murupolun ja sivun otsikon välissä. Aihe-tagit ovat navigaatio-elementtejä. Ne eivät kuitenkaan lukkiudu sivun yläosaan kuten murupolku kun sivua skrollataan alaspäin. 

Isoilla näytöillä aihe-tagit asettuvat rinnakkain sivun otsikon yläpuolelle: 

![Aihe-tagit asettuvat isoilla näytöillä rinnakkain.](images/aihe_tagit_desktop.png)

Pienillä näytöillä aihe-tagit menevät tarvittaessa allekkain, mutta pysyvät silti sivun otsikon yläpuolella: 

![Aihe-tagit asettuvat mobiilinäytöillä allekkain.](images/aihe_tagit_mobiili.png)

**Aihe-tagien tyylit**

Aihe-tagien eri tilat: 

| Tila           | Font                    | Font-size | Text-decoration | Color   | Background-color | Padding      | Muuta                                                               |
| -------------- | ----------------------- | --------- | --------------- | ------- | ---------------- | ------------ | ------------------------------------------------------------------- |
| **Tavallinen** | Source Sans Pro regular | 14px      | none            | #ffffff | #0073b0          | 0.2em, 0.6em |                                                                     |
| **Hover**      | Source Sans Pro regular | 14px      | underline       | #ffffff | #0073b0          | 0.2em, 0.6em | Kursori muuttuu kädeksi linkin päällä                               |
| **Focus**      | Source Sans Pro regular | 14px      | underline       | #ffffff | #0073b0          | 0.2em, 0.6em | Reunus: 2px, #0073b0 (sama focus-tyyli kuin muissakin elementeissä) |
| **Vierailtu**  | Source Sans Pro regular | 14px      | none            | #ffffff | #0073b0          | 0.2em, 0.6em | Vierailtu-tila ei eroa tavallinen-tilasta                           |

Tavallinen-tila:
![Normaalitilassa oleva aihe-tagi.](images/aihe_tagi.png)

Hover-tila:
![Aihe-tagi hover-tilassa.](images/aihe_tagi_hover.png)

Focus-tila:
![Aihe-tagi focus-tilassa.](images/aihe_tagi_focus.png)

Vierailtu-tila, ei eroa tavallinen-tilasta:
![Vierailtu-tilassa oleva aihe-tagi.](images/aihe_tagi.png)

#### Muut tagit

![Tagien paikka on otsikon yläpuolella. ](images/tagin_paikka.png)

Tageja käytetään antamaan julkaisuista lisää tietoa. Ne sijaitsevat otsikon yläpuolella tilastojen ja julkaisujen sivuilla sekä julkaisujen nostoelementeissä. 

Tagit antavat lisätietoa julkaisun ja sivun: 
* sisältötyypistä: tilasto, tiedote, taulukko, kuvio, indikaattori, artikkeli, blogi, video, katsaus, muutoksia tässä tilastossa, jne.   
* mihin tilastoon julkaisu kuuluu,
* mitä viiteajankohtaa tiedote käsittelee, 
* mikä on tiedotteen status: ennakko, pikaennakko, lopullinen jne. 
* mihin domainiin/palveluun julkaisu kuuluu, jos se kuuluu muuhun kuin stat.fi-domainiin: Findikaattori, Tieto&trendit. 
 
Huom! Tageilla ei merkitä julkaisupäivämäärää, sitä varten on oma elementtinsä. 

![Julkaisujen nostoelementeissä tageja on useita. ](images/tagi_tilasto.png)

Tageja voi olla julkaisujen nostoelementeissä useampi peräkkäin. Esimerkiksi tiedotteen nostoelementissä on julkaisun tyyppi, tilasto, viiteajankohta ja julkaisun status. Julkaisun sisältötyyppi erotetaan muista tageista |-merkillä. 

![Sisältötyyppi-tagi tiedotteen sivulla. Tagin paikka on otsikon yläpuolella.](images/tagi_tiedote.png)

Julkaisujen sivuilla on vain sivun sisältötyyppi-tagi, esimerkiksi tiedotteen sivulla Tiedote. Muille tageille ei ole julkaisujen sivuilla tarvetta, sillä niiden tiedot esitetään sivulla muissa kohdissa. 

**Tagien tyyli** 

|                        | Font             | Font-size | Color   |
| ---------------------- | ---------------- | --------- | ------- |
| Tagit                  | Barlow, semibold | 14px      | #333333 |
| Ulkoinen linkki -ikoni |                  |           | #333333 |

### Tilastokuviot

#### Kuviot pienillä näytöillä

Mobiilinäytöillä kuva mahdutetaan näytölle eli se **näytetään kokonaan**. Kuvioita ei suurenneta valmiiksi ja päästetä osaksi näytön ulkopuolelle. Kuvioissa ei ole vieritysominaisuutta. Käyttäjä voi itse tarvittaessa suurentaa kuviota. 

#### Kuviot isoilla näytöillä

Desktop-näytöillä kuvioita on kahta kokoa: palstan levyinen ja täysileveä. 

![Kuvio desktop-koossa palstan sisällä noudattaa palstan leveyttä.](images/kuvio_palstan_sisalla.png)

 Tekstipalstan sisällä olevat kuviot noudattavat tekstipalstan leveyttä. Näin ne asettuvat kauniimmin samaan linjaan muun palstan sisällön kanssa. 

![Muualla kuin palstan sisällä oleva sisältöalueen levyinen kuvio.](images/kuvio_levea.png)

Muualle kuin tekstipalstan sisälle tulevat kuviot (esim. Kuviot-blokin kuviot) ottavat tavallisen blokin sisältöalueen leveyden. Kuviot asettuvat sivustolla kauniimmin kun ne ovat samanlevyisiä keskenään ja linjassa muun sisällön kanssa. 

#### Kuvion tooltip

![Viivakuvion tooltip.](images/viivakuvio_tooltip.png)

Kuvion tooltip on pieni laatikko, joka tulee näkyviin kuvion päälle ja kertoo tietyn datapisteen arvon. Tooltip ilmestyy näkyviin hover-toiminnolla eli kursorin osuessa kuvion kohtaan, josta datapisteen arvo on saatavissa. Tooltip kertoo muuttujan nimen, arvon labelin ja lopullisen datapisteen arvon. 

| Font                          | Font-size   | Background-color | Border  | Box-shadow                            |
| ----------------------------- | ----------- | ---------------- | ------- | ------------------------------------- |
| Barlow Semi Condensed regular | 1rem (16px) | #f2f8fb          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35) |

#### Kuvioiden lähdemerkintä

Tilastokuvioihin liitetään lähdemerkintä, josta käy ilmi kuvion tunniste, tilasto, johon kuvio liittyy sekä kuvion tuottaja. Lähdemerkintä tulee kuvion alle oikeaan alareunaan. Esimerkkilähdemerkintä: 

Lähde: Kuvio 32425, Rakennus- ja asuntotuotanto, Tilastokeskus. 

Kuvioiden lähdemerkinnässä käytetään samaa tyyliä kuin taulukoiden lähdemerkinnöissä, katso kohta Taulukoiden lähdemerkintä. 

#### Kuvioiden saavutettavuus

* Suositus on, että kuvioon ei laiteta liikaa sisältöä. Tällöin kuvio pysyy helpommin ymmärrettävänä ja värisävyjen kontrastit riittävät harmaan sävyisinäkin (täyden värisokeuden tapaus). Jos sisältöä on paljon, on parempi jakaa sisältö useaan eri kuvioon. 

* Tilastokuviot piilotetaan ruudunlukijalta. Tällöin ruudunlukija ei lue kuvioiden otsikoitakaan. Näin toimitaan, koska kuvioita on niin paljon, että tekstivastineita (alt-tekstiä) ei ole mahdollista tehdä niille kaikille. Kuvioiden sisältö tulee kuitenkin tarjota sivulla tekstimuodossa, jotta myös ruudunlukijaa käyttävät saavat kuvioiden sisältämän informaation. 

* Tilastokuvioissa viivat, pylväät ja piirakan siivut erotetaan toisistaan väreillä. Tämä saavutettavuusrajoite tulee mainita saavutettavuusselosteessa. Tilastokuvioissa ei siis käytetä reunaviivoja, paksuuseroja, eri muotoja tai pintakuviointeja osioiden erottamiseksi toisistaan. 

#### Kuvioiden tyylit

##### Kuvioiden fontit

|                         | Font                          | Font-size   | Text-align |
| ----------------------- | ----------------------------- | ----------- | ---------- |
| **Kuvion otsikko**      | Barlow Semi Condensed medium  | 1rem (16px) | center     |
| **Kuvion alaotsikko**   | Barlow Semi Condensed regular | 1rem (16px) | center     |
| **Kuvion muut tekstit** | Barlow Semi Condensed regular | 1rem (16px) |            |

##### Kuvioiden hilaviivat

| Color   | Width  |
| ------- | ------ |
| #666666 | 0.25px |

##### Kuvioiden akselit

|              | Color   | Width | Akselin otsikon sijainti                   |
| ------------ | ------- | ----- | ------------------------------------------ |
| **y-akseli** | #666666 | 0.5px | Akseliviivan keskellä, eli nykyinen paikka |
| **x-akseli** | #666666 | 0.5px | Akseliviivan keskellä, eli nykyinen paikka |

#### Kuviotyypit

##### Viivakuvio

![Viivakuvio.](images/viivakuvio.png)

Viivojen selitteet sijaitsevat kuvion alla. Näin saadaan niille enemmän tilaa, sillä selitetekstit voivat olla pitkiä. 

|            | Width |
| ---------- | ----- |
| **Viivat** | 3px   |

##### Piirakkakuvio

(Tähän kuva piirakkakuviosta.)

Piirakkakuvioissa lukuarvot sijaitsevat piirakan ulkopuolella ja on luku yhdistetty viivalla piirakan viipaleeseen (tämä on jo ennestään käytössä oleva malli). 

Piirakoissa selitetekstien järjestys on laskeva suuruusjärjestys. 

##### Pylväskuvio

(Tähän kuva pylväskuviosta.)

Pylväskuvioissa selitetekstit ovat järjestyksessä palkkien mukaan eli alhaalta ylös. 

### Tilastotaulukot

#### Taulukot pienillä näytöillä

![Taulukko mobiilissa, riviotsikot jäädytetty paikoilleen.](images/taulukko_mobile_tyylit.png)

Joskus taulukosta tulee niin leveä tai pitkä, että se ei mahdu etenkään pienille näytöille kokonaan. Tällöin taulukon rivi- tai sarakeotsikot voidaan lukita paikoilleen. 

Jos taulukko on näyttöä leveämpi, taulukon riviotsikot lukitaan paikalleen ja muu taulukko on liikuteltavissa oikealle ja vasemmalle. Riviotsikot vievät korkeintaan n. 30% näytön leveydestä. Vierityspalkit taulukon liikutettavan osan yllä ja alla vihjaavat taulukon liikuteltavuudesta. Vierityspalkin tyylit löytyvät alempaa kohdasta Vierityspalkki. Taulukkoa voi mobiililaitteissa liikutella vierityspalkkien lisäksi myös itse taulukon liikuteltavaan osaan (muu kuin rivi- tai sarakeotsikot-sarake) koskemalla. 
 
Jos taulukko on näyttöä pidempi, taulukon sarakeotsikot voidaan lukita paikoilleen. Kun sivua vieritetään taulukon kohdalta alaspäin, taulukon sarakeotsikot jäävät näkyviin näytön yläreunaan ja muuta taulukkoa voidaan liikuttaa pystysuunnassa. Kun on päästy taulukon loppuun ja jatketaan sivun vieritystä edelleen alaspäin, sarakeotsikot katoavat näytön yläreunasta näkyvistä muun taulukon mukana. 

Sekä rivi- että sarakeotsikot eivät voi olla samaan aikaan lukitut. Riippuu taulukosta, kummat otsikot kannattaa lukita mobiililaitteissa ja pienissä näytöissä. 

Kun taulukkoa aletaan vierittää sivu- tai pystysuunnassa, tulee lukitun otsikon reunaan taulukon sisältösolujen puolelle pieni varjostus. Sivusuunnassa taulukkoa vieritettäessä varjostus tulee siis lukittujen riviotsikoiden oikealle puolelle:

![Taulukon riviotsikoiden otsikoiden oikealla puolella oleva varjo kun taulukkoa vieritetään vaakasuunnassa.](images/taulukko_shadow_pysty.png)

Pystysuunnassa vieritettäessä varjo tulee lukittujen sarakeotsikoiden alle: 

![Taulukon sarakeotsikoiden otsikoiden alapuolella oleva varjo kun taulukkoa vieritetään pystysuunnassa.](images/taulukko_shadow_vaaka.png)

Varjostus auttaa käyttäjää hahmottamaan, että osa taulukosta on piilossa rivi- tai sarakeotsikkojen alla. Varjostuksen tyylimääritykset löytyvät kohdasta Taulukkopohjan tyylit. 

#### Taulukot isoilla näytöillä

##### Taulukot tekstipalstan sisällä

Desktop-näytöillä taulukoita on kahta kokoa: palstan levyinen ja täysileveä.

![Desktop-koossa palstan sisällä taulukko noudattaa palstan leveyttä.](images/taulukko_lahde.jpg)

Tekstipalstan sisällä olevat taulukot noudattavat tekstipalstan leveyttä. Näin ne asettuvat samaan linjaan muun palstan sisällön kanssa. Jos taulukon sisältö ei mahdu palstan leveydessä kokonaan näkyville, siitä tulee sivusuunnassa vieritettävä. Tällöin taulukon sarakeotsikot jäädytetään paikalleen ja ne vievät korkeintaan n. 30% palstan leveydestä. Taulukon ylä- ja alapuolelle tulee vierityspalkit vihjaamaan vieritysominaisuudesta kuten taulukoissa pienillä näytöillä. Taulukkoa pääsee vierittämään sivusuunnassa vierityspalkeista. Vierityspalkin tyylit löytyvät alempaa kohdasta Vierityspalkki.

##### Taulukot muualla kuin tekstipalstan sisällä

![Blokin sisältöalueeseen mahdutettu taulukko.](images/taulukko_desktop_levea.png)

Muualle kuin tekstipalstan sisälle tulevat taulukot (esim. Taulukot-blokin taulukot ja taulukot omilla sivuillaan) ottavat tavallisen blokin sisältöalueen leveyden. Taulukot sisältöineen tulee mahduttaa tähän kokoon. Sisältöaluetta kapeammat taulukot venytetään blokin sisältöalueen levyisiksi. Tällöin taulukon soluihin jää enemmän tyhjää tilaa, mutta kun kaikki taulukon ovat samanlevyisiä keskenään ja linjassa muun sisällön kanssa, ne asettuvat sivustolla kauniimmin. 

![Blokin sisältöalueen ylimenevään taulukkoon tulee vierityspalkit.](images/taulukko_desktop_ylilevea.png)

Vain hyvin poikkeuksellisissa tilanteissa, joissa taulukon mahduttaminen blokin sisältöalueeseen ei onnistu eikä taulukkoa saada muokattua blokin sisältöalueeseen mahtuvaksi, taulukkoon tulee vieritysominaisuus kuten mobiilissa ja palstan sisällä olevissa taulukoissa. Taulukon rivi- tai sarakeotsikot lukitaan ja taulukon muuta osaa pystyy liikuttamaan vaakasuunnassa vierityspalkkeja liikuttamalla tai sivua alaspäin skrollaamalla. Vierityspalkit tulevat taulukon liikutettavan osan ylä- ja alapuolelle. Vierityspalkin tyylit löytyvät alempaa kohdasta Vierityspalkki. Taulukkoa vieritettäessä riviotsikoiden oikealle puolelle tai sarakeotsikoiden alapuolelle tulee näkyviin myös varjostus, jonka tyylit löytyvät kohdasta Taulukkopohjan tyylit. 

Taulukoiden sisällön, rivien ja sarakkeiden määrän pitäminen maltillisena auttaa taulukoita myös pysymään blokkien sisältöalueen sisällä desktop-koossa. Tällöin ne eivät tarvitse desktop-laitteilla lukittuja riviotsikoita ja vaaka- tai pystysuuntaista vieritysominaisuutta. 

#### Taulukoiden alaviite

Taulukon alaviitteet sijaitsevat taulukon ulkopuolella heti taulukon alla:

![Tilastotaulukon lähdemerkintä taulukon alla taulukon lisätietojen jälkeen.](images/taulukko_alaviite.jpg)

Taulukon alaviitteen tyylit löytyvät kohdasta Taulukon fontit. 

#### Taulukoiden lähdemerkintä

Taulukoihin liitetään lähdemerkintä, josta käy ilmi taulukon tunniste, tilasto, johon taulukko liittyy sekä taulukon tuottaja. Esimerkkilähdemerkintä: 

Lähde: Taulukko 32425, Rakennus- ja asuntotuotanto, Tilastokeskus. 

Lähdemerkintä tulee taulukon ulkopuolelle taulukon alle. Jos taulukon alla esitetään myös taulukkoon liittyviä lisätietoja ts. taulukossa on alaviitteitä, lähdemerkintä sijaitsee niiden jälkeen:

![Taulukon lähdemerkintä tulee alaviitteen jälkeen.](images/taulukko_lahde.jpg)

Jos taulukon lähdemerkintä tai osa siitä on linkki, linkki alleviivataan. 

Taulukon lähdemerkinnän tyylit löytyvät kohdasta Taulukon fontit. 

#### Taulukoiden saavutettavuus
* Taulukkoon ei tule laittaa liikaa sisältöä. Näin taulukot pysyvät helpommin ymmärrettävinä ja vertailtavina. Jos sisältöä on paljon, on parempi jakaa sisältö useaan eri taulukkoon. 
* Taulukoissa ei tulisi olla todella paljon sarakkeita ja/tai rivejä. Tämä helpottaa taulukoiden käyttöä ja ymmärrettävyyttä, erityisesti mobiililaitteilla. 
* Sarake- ja riviotsikkojen tulee olla mahdollisimman lyhyitä ja ytimekkäitä. Liian pitkiä sarake- ja riviotsikoita tulee välttää. Tämä auttaa taulukoita asettumaan paremmin mobiililaitteissa. 
* Jos on tarpeen tehdä hierarkisia taulukoita, on suositeltavaa käyttää korkeintaan kahta hierarkian tasoa. Myös tämä auttaa taulukon ymmärrettävyyttä. 
* Se taulukon rivi, jonka päälle kursori osuu, korostetaan erottuvalla värillä (tyyli löytyy kohdasta Taulukon tyylit). Kosketuskäyttöliittymissä sama taulukon rivin hover-efekti toimii kun käyttäjä klikkaa taulukon riviä. Rivin korostaminen  helpottaa käyttäjiä taulukon lukemisessa. 

#### Taulukoiden tyylit

##### Taulukkopohjan tyylit

|                              | Background-color | Border  | Border-width                         | Padding                                |
| ---------------------------- | ---------------- | ------- | ------------------------------------ | -------------------------------------- |
| **Taulukko**                 |                  | #0073b0 | top/bottom: 0,5px left/right: 0,25px | top/bottom: 8px left/right: 10px       |
| **Rivi- ja sarakeotsikot**   | #f2f8fb          | #0073b0 | 0,5px                                | top/bottom: 8px left/right: 10px       |
| **Koko rivin sarakeotsikot** | #f2f8fb          | #0073b0 | 0,5px                                | top: 16px bottom: 8px left/right: 10px |
| **Solu**                     | #ffffff          | #0073b0 | 0,25px                               | top/bottom: 8px left/right: 10px       |
| **Rivin hover**              | #cce3fe          |         |                                      |                                        |

Taulukon rivi- ja sarakeotsikoiden varjostuksen tyylit (2px varjo lukitun otsikon sille puolelle minne skrollataan):
|                                   | Size    | rgba                    |
| --------------------------------- | ------- | ----------------------- |
| **Riviotsikoiden Outer shadow**   | 2px 0px | rgba (102,102,102,0.35) |
| **Sarakeotsikoiden Outer shadow** | 0px 2px | rgba (102,102,102,0.35) |

##### Taulukon fontit
|                                                                                                          | Font                           | Font-size                         | Text-align                      | Vertical-align |
| -------------------------------------------------------------------------------------------------------- | ------------------------------ | --------------------------------- | ------------------------------- | -------------- |
| **Taulukon otsikko**                                                                                     | Barlow Semi Condensed regular  | 1rem (16px)                       |                                 |                |
| **Taulukon sarake- ja riviotsikot**                                                                      | Barlow Semi Condensed SemiBold | 1rem (16px)                       | ks. taulukon solujen text-align | bottom         |
| **Taulukon solut: numeroksi merkitty sisältö ja numeron korvikkeena oleva teksti (esim. Puuttuva arvo)** | Barlow Semi Condensed regular  | 0.9rem (15px) tai 0.875rem (14px) | right                           | bottom         |
| **Taulukon solut: tekstiksi merkitty sisältö**                                                           | Barlow Semi Condensed regular  | 0.9rem (15px) tai 0.875rem (14px) | left                            | bottom         |
| **Taulukon alaviite**                                                                                    | Barlow Semi Condensed regular  | 1rem (16px)                       |                                 |                |
| **Taulukon lähdemerkintä**                                                                               | Barlow Semi Condensed regular  | 1rem (16px)                       |                                 |                |

### Tooltip

Tooltip on pieni laatikko, joka tulee näkyviin käyttäjän toiminnon käynnistämänä. Tooltip kertoo lisätietoa elementistä tai kontekstista, johon se liittyy. (Miten tooltip tulee näkyviin: klikkauksella vai hover-toiminnolla kuten kuvioiden tooltipit? Miten tooltip sulkeutuu?)

![Viivakuvion tooltip.](images/viivakuvio_tooltip.png)

| Font                          | Font-size   | Background-color | Border  | Box-shadow                            |
| ----------------------------- | ----------- | ---------------- | ------- | ------------------------------------- |
| Barlow Semi Condensed regular | 1rem (16px) | #f2f8fb          | #0073b0 | 2px, 2px, 5px, rgba(102,102,102,0.35) |

#### Tooltipin saavutettavuus

* Tooltipiin ei tule laittaa sellaista sisältöä, joka käyttäjän on tärkeää löytää tai nähdä. Kaikki käyttäjät eivät välttämättä huomaa elementtiä, josta tooltip on saatavissa tai ymmärrä miten tooltipin saa näkyviin. 

### Video
#### Videoelementin koko
Videon kuvasuhde on **16:9**, esim. **resoluutio 1920x1080**. 

#### Videoiden saavutettavuus

* Videoissa, joissa on puhetta tulee olla tekstitys. 
* (Kuvailutulkkaus ja sen tekstitys?) 
* Videon yhteydessä on tarjottava linkki Youtube-palveluun, jossa videon voi myös katsoa. 
* Videon käsikirjoitus tulee olla saatavissa. Sille on paikka videon alla Videon käsikirjoitus-laajennuspaneelissa. 

### Video-blokki

Tiedotteisiin voidaan liittää video-blokki. Video-blokki sijaitsee tiedotteissa tekstiosuuden jälkeen. 

![Video-blokki desktop-koossa. Käsikirjoitus-laajennuspaneeli on avattu. ](images/video_desktop_avattu.png)

Video-blokki koostuu useasta pienemmästä elementistä. Blokin sisältämät elementit järjestyksessä ylhäältä alas ovat: sisältötyyppi-, tilaston nimi- ja viiteajankohta -tagit, videon otsikko, videon julkaisupäivämäärä, linkki Youtube-palveluun, itse videoelementti ja laajennuspaneeli, joka sisältää videon käsikirjoituksen. 

Video-blokin osat asettuvat samoin sekä mobiili- että desktop-näytöillä. Blokki mobiili-näytöllä: 

![Video-blokki mobiili-koossa. ](images/video_mobiili.png)

#### Video-blokin tyylit

| Background-color |
| ---------------- |
| #ffffff          |

| Video-blokin osa   | Noudattaa tyyliä        |
| ------------------ | ----------------------- |
| Tagit              | tagin tyyli             |
| Otsikko            | H3                      |
| Julkaisupäivämäärä | päiväyksen tyyli        |
| Youtube-linkki     | linkin tyyli            |
| Käsikirjoitus      | laajennuspaneelin tyyli |

### Vierityspalkki

Vierityspalkki vihjaa elementissä olevasta vieritys-ominaisuudesta silloin kun elementin koko sisältö ei mahdu sivulle tai elementin sisään kokonaan näkyviin. Vierityspalkki voi olla vaaka- tai pystysuuntainen. 

![Vaakasuuntainen vierityspalkki.](images/vierityspalkki.png)

#### Pystysuuntainen vierityspalkki

|                         | Color   | Border-radius | Height                     | Width |
| ----------------------- | ------- | ------------- | -------------------------- | ----- |
| **Vieritettävä palkki** | #0073b0 | 10px          | määräytyy elementin mukaan | 10px  |
| **Tausta**              | #e6e6e6 |               | määräytyy elementin mukaan | 10px  |

#### Vaakasuuntainen vierityspalkki

|                         | Color   | Border-radius | Height | Width                      |
| ----------------------- | ------- | ------------- | ------ | -------------------------- |
| **Vieritettävä palkki** | #0073b0 | 10px          | 10px   | määräytyy elementin mukaan |
| **Tausta**              | #e6e6e6 |               | 10px   | määräytyy elementin mukaan |

### Viiva

Viiva on kapea harmaa vaakaviiva, joka erottaa sisältöjä toisistaan. Viivoja voidaan käyttää myös asioiden ryhmittelyyn asettamalla niitä eri ryhmien väliin, esim. menuissa. 

![Viiva](images/divider.png)

| Height | Color   |
| ------ | ------- |
| 1px    | #d7d7d7 |

Ensisijaisesti eri osioiden erottamiseen toisistaan tulee käyttää tyhjää tilaa. Niissä tilasteissa, joissa tyhjää tilaa ei voida käyttää tai se ei ole riittävä tapa, käytetään viivoja.  

![Viiva erottamassa toisiinsa julkaisu-elementtejä.](images/divider_example1.png)

Viivoilla voidaan myös erottaa saman kokonaisuuden tai toisiinsa liittyviä elementtejä toisistaan. 

	

