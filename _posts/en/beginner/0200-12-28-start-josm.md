---
layout: doc
title: Getting Started with JOSM
permalink: /en/beginner/start-josm/
lang: en
category: beginner
published: true
---

Bevezetés a JOSM használatába
=============================

Ebben a fejezetben a JOSM, a Java OpenStreetMap-szerkesztő telepítését nézzük meg 
lépésenként. Átállítunk néhány beállítást, hogy könnyebb legyen használni.
Ezután megnyitunk egy mintatérképet, és megtanuljuk az alap szerkesztési lehetőségeket.
Emlékszel, amikor a bevezetésben megkértünk, rajzold le a falud vagy városod térképét?
A fejezet végén őjra lerajzoljuk ezt a térképet, ezúttal digitálisan.
Miután végeztél, egy alapos áttekintéssel fogsz rendelkezni a
JOSM-es térképszerkesztésről.

JOSM letöltése
-------------

- Ha van egy példányod  a JOSM-ből CD-n vagy usb drive-on,
  akkor ugorj a JOSM telepítése részhez.
- Ha nincs még JOSM-ed, vagy a legfrissebbet szeretnéd beszerezni,
  nyisd meg a böngésződet.
- Írd be a következőt az ablak tetején lévő címsorba,
  majd nyomj Entert: [josm.openstreetmap.de](http://josm.openstreetmap.de)
- Úgy is megtalálhatod a JOSM oldalát, ha rákeresel arra, hogy "JOSM".
- A weboldal valahogy így fog kinézni:

  ![JOSM website][]

- Ha Windowsod van, kattints a Windows telepítő letöltésére.

  ![Windows installer][]

- Ha más operációs rendszered van, kattints az annak megfelelő linkre
  Hamarosan elindul a letöltésed. Ebben a fejezetben abból indulunk ki,
  hogy Windowst használsz, de a lépések hasonlóak a többi operációs
  rendszernél is.

JOSM telepítése
------------

>  Problémád lehet a JOSM telepítésével, ha még nincs Java a számítógépeden.
>  Ha problémába ütközöl, töltsd le és telepítsd a Javát innen:
>  [http://www.java.com/en/download/](http://www.java.com/en/download/)

- Keresd meg a JOSM-telepítőt a gépeden. Kattints rá  duplán.a telepítés elindításához.
- Kövesd a telepítő utasításait. Az installáció végén kattints a
  Befejezésre a JOSM elindításához.
  Később, ha el akarod indítani a JOSM-et, a Start Menüből meg tudod tenni.
- Az elején felugorhat egy ablak, amely felkínálja a szoftver frissítését.
  Erre nincs még szükség, hisz a legfrissebbet töltötted le.
  Kattintsd a Mégse-gombra. Ha többet nem akarod látni ezt az ablakot,
  pipáld ki az alján lévő dobozt, mielőtt a Mégsére kattintasz.
- Amikor elindul a JOSM, valahogy így fog kinézni:

  ![JOSM splash page][]

JOSM beállítások
--------------------

A JOSM-ben sok különböző beállítást lehet személyre szabni.
Az egyik, amit érdemes bállítani, az a nyelv. A JOSM-et
számos nyelvre fordították le, és lehet, hogy te nem az alapértelmezettet
szeretnéd használni.

- A Beállítások ablak eléréséhez kattints a Szerkesztés -\> Beállítások opcióra.

  ![Preferences window][]

- A bal oldalon kattints a festéket és ecsetet ábrázoló ikonra..
- Az ablak tetején kattints a "Look and Feel" nevű fülre.
- Válaszd ki a használni kívánt nyelvet a "Nyelv" melletti legördülő 
  menüből.
  
  ![Look and feel][]

- Kattints az  Okéra.
- Újra kell indítanod a JOSM-et a beállítások elmentéséhez. Kattints a Fájl menüre
  a bal felső sarokban, és választ ki az Újraindítást.

Rajzolási alapok JOSM-ben
-----------------------------

- Most nyissunk ki egy mint OSM-fájlt, amin megtanulhatunk rajzolni.
  Ne feledjük, hogy ez nem egy igazi térkép, nem is egy valós helyet
  ábrázol, úgyhogy nem mentjük el az OpenStreetMapbe.
- Innen tölthető le a fájl: [sample.osm](/files/sample.osm)
- Nyissuk meg a mintafájlt JOSM-ben. Kattintsunk a
  "Megnyitás" gombra a bal felső részen. 

  ![Open file][]

- Keressük meg a **sample.osm**nevű fájlt. Valószínáleg a Letöltések mappában van,
  kivéve, ha máshova mentetted. Kattints rá, majd menj a "Megnyitásra".
- Egy ilyen mintatérképet kellene látnod:

  ![Sample file][]

### Alapműveletek

- A jobbra-balra vagy fel-le mozgatáshoz, tartsuk lenyomva a jobb
  egérgombot, és mozgassuk az egeret.
- Több módon is tudunk nagyítani. Ha van egerünk, a görgővel tudunk
  ráközelíteni a térképre. Ha laptopot használunk, zoomolhatunk a 
  a képernyő bal felső részén található csúszkával is. A bal egérgombbal
  húzogathatjuk a csúszkát jobbra és balra.

  ![Scale bar][]

- Tekintsük át a mintatérképet. Több különböző dolog van feltűntetve.
  Látunk egy folyót, erdőt, néhány épületet, több utat, és néhány
  boltot. Egy objektum kiválasztásához, kattintsunk rá a bal
  egérgombbal.

### Pontok, vonalak, alakzatok

- Ha rákkatintasz a külöböző objektumokra, látszik, hogy három különböző
  típusból állnak. Vannak pontok, vonalak és alakzatok.
- Egy pont egy helyet jelöl, amit egy szimbólum is reprezentál. Ezen a térképen
  két pont található, egy cipőbolt és egy szupermarket. A cipőboltot egy
  cipő szimbólum jelképezi, a szupermarketet pedig egy bevásárlókocsi jelöli.
- Több vonal is látható a térképen, amik utakat jelképeznek.
  Ha megnézed közelebből, láthatod, hogy a vonalakon belül 
  pontok is vannak. Ezeken nincs szimbólum vagy egyb plusz információ,
  arra szolgálnak, hogy meghatározzák a vonal helyzetét.
- Végül különböző alakzazokat is találunk a mintatérképen, amelyek helyeket
  reprezenzálnak - erdőt, folyót, parkot, épületeket. Az alakzatok területeket jelölnek, 
  mint például egy mező vagy egy épület. Az alakzat gyakorlatilag egy vonal,
  azzal a különbséggel, hogy ugyanabban a pontban végződik, mint ahol kezdődik.

> Könnyű úgy felfogni a térképet, mint ami ezt a három alap objektumfajtát
> tartalmazza - pontokat, vonalakat és alakzatokat. Az OpenStreetMap egy külön
> terminológiát használ, amit idővel megszokik az ember. Az OSM-ben a pontokat
> **nodes**-oknak, a vonalakat **ways**-nek hívják. Az alakzatokat **closed way**-nek
> hívják, mert valójában egy vonal, amely abban a pontban végződik, ahonnan indul.

- Megfigyelhetted, hogy amikor kiválasztasz egy objektumot, egy lista
  jelenik meg a térképtől jobbra. A listéban lévő elemeket hívjuk címkéknek,
  vagy tageknek. A címkék a ponthoz, vonalhoz vagy alakhathoz tartozó, 
  azokat leíró információkat hordozzák. Egy későbbi fejezetben még lesz
  szó ezekről. Egyelőre annyit fontos megjegyezni, hogy ezek az információk
  írják le, hogy az adott objektum egy erdő, folyó, épület vagy valami más.  
- Képzeld el, hogy kézzel rajzolsz egy térképet pontokból, vonalakból,
  alakzatokból. Milyen helyeket ábrázolnál pontokkal? Milyeneket vonalakkal,
  alakzatokkal?

### Objektumok változtatása

- Válaszd ki a térlép bal oldalán az erdőt. Ügyelj rá, hogy az 
  erdő körvonalára kattints, és ne a vonalon lévő pontokra. 
  Tartsd nyomva a bal egérgombot, és mozgasd az egeret. Így át tudod 
  mozgatni az erdőt egy új helyre a térképen.
- Kattints az egyik pontra az erdő körvonalán. Tarts lenyomva a bal
  egérgombot, majd mozgasd az egeret. Így az adott pontot tudod mozgatni.
  Ezzel tudod változtni az adott objektum formáját vagy a pont helyét.

### Rajzolás

- A JOSM bal oldalán egy oszlopban gombok láthatók. Ezekből több új
  ablakot nyit meg a jobb oldalon, ami információkkal szolgál a 
  térképről. A legfontosabbak mégis az oszlop tetején lévők. Ezek
  határozzák meg, mit csinálsz az egérrel.
- Az oszlop felső gombjait fogod a leggyakrabban használni. Ezekkel
  vélaszthatjuk ki objektumokat, illetve rajzolhatsz újakat.
- Mostanáig a Kiválasztás-gombot használtad, ami így néz ki:

  ![Select tool][]

- Mielőtt rajzolnál, győződj meg róla, hogy semmi sincs kiválasztva.
  Kattints a térkép fekete részére, ami üres, így biztos nem
  lesz semmi kiválasztva
- Kattints a második gombra, a Rajzolás-eszközre.

  ![Draw tool][]

- Keress egy üres területet a térképen, és kattints ide duplán az egérrel.
  Ez egy önálló pontot fog rajzolni.
- Vonal rajzolásához kattints egyszer az egérrel. Mozgasd el az egeret, és
  kattints ismét, majd folytasd, amíg elégedett vagy a vonaladdal.
  A vonal lezárásához kattints duplán.
- Ugyanúgy tudsz alakzazokat rajzolni, mint  vonalat, befejezéskor
  pedig arra a pontra kell dupőlán kattintani, ahonnan indultál.

### Címkék hozzáadása

- Már tudjuk hogy kell pontokat, vonalakat és alakzatokat rajzolni,
  de nem tudjuk megadni, mit jelképeznek. Márpedig szükséges jelezni,
  hogy a pontjaink boltok, iskolák, stb., hogy az alakzatok mezők,
  épületek vagy bármi más.
- Kattints a Kiválasztás-gombra a baloldali oszlopban.
 
  ![Select tool][]

- Válaszd ki az egyik imént rajzolt objektumot. A felső menüből
  kattints a Címkékre. Válaszd ki az almenükből azt, amelyikkel szeretnéd
  leírni a helyet.
- Ha rákattintasz egy címkére, akkor egy űrlap fog felugrani, ahol
  még több információt tudsz megadni. Nem kötelező minden mezőt kitölteni,
  de a fontosabbakat érdemes, például az objektum nevét.
- Amikor végeztél az információ bevitelével, kattints a 
  Címke alkalmazása gombra. Ha minden jól ment, akkor a kiválasztott
  pont, vonal vagy alakzat színe megváltozik vagy egy szimbólum 
  jelenik meg rajta. Ez azért van, mert definiáltad, mi is az.

Rajzold meg a saját térképed
-----------------

- Most rajzoljunk egy térképet, hogy gyakorolhassuk az eddig tanultakat.
  Újrarazolhatod akár az előzőleg papírra rajzolt térképet is.
- Mozgasd el a látott területet a mintatérképtől. Tartsd nyomva a jobb
  egérgombot, és mozgasd az egered addig, amíg egy üres felület van
  előtted, amire rajzolhatsz. 
- Használd a Rajzolás-eszközd, hogy pontokat, vonalakat, alakzatokat
  hozz létre. Definiáld ezeket címkék hozáadásával.
- A végére lesz egy saját térképed, hasonló mint sample.osm mintatérképe.

Összegzés
-------

Kiváló! Ha minden jól ment, megtanultad, hogy kell telepíteni és beállítani a 
JOSM-et, és használni az alap rajzolási eszközöket. A következő fejezetben
közelebbről is megnézzük a JOSM-es térképszerkesztést.


[JOSM website]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image00_josm-website.png
[Windows installer]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image01_windows-installer.png
[JOSM splash page]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image02_josm-splash-page.png
[Preferences window]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image03_preferences-window.png
[Look and feel]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image04_look-and-feel.png
[Open file]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image05_open-file.png
[Sample file]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image06_sample-file.png
[Scale bar]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image07_scale-bar.png
[Select tool]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image08_select-tool.png
[Draw tool]: /images/en/beginner/03_start-josm/en_beg_03_start-josm_image09_draw-tool.png
