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

- As you click different objects on the sample map, notice that there
  are three different types of objects on the map. There are points,
  lines, and shapes.
- Points are a single location, represented by symbols. On this sample
  map, there are two points, a shoe shop and a supermarket. The
  shoe shop is represented by a shoe symbol, and the market is
  represented by a shopping cart.
- There are several lines on the map as well, which represent roads.
  If you look closely you will see that within the lines, there are
  points as well. These points don’t have any symbols or other
  information associated with them, but they help to define where the
  line is located.
- Lastly, there are numerous shapes on the sample map, representing
  different places - a forest, a river, a park, and buildings. A shape
  is used to represent an area, like a field or a building. A shape is
  exactly like a line - the only difference is that the line begins at
  the same point where it ends.

> It's easy to think of a map as containing these three basic types of objects - 
> points, lines, and shapes. In OpenStreetMap there is special terminology
> which you will come to learn as you progress. In OSM, points are actually called
> **nodes**, and lines are called **ways**. A shape is called a **closed way**
> because it is just a line that ends at the same point where it begins.

- You may notice that when you select an object, a list appears to the
  right of the map in a window called “Properties”. These are known as
  tags. Tags are information that is tied to a point, line or shape
  that describes what it is. We’ll learn more about tags in a later
  chapter. For now all you need to know is that this
  information helps describe whether our object is a forest, a river,
  a building, or something else.
- Think about drawing a map by hand, and how you are also drawing
  points, lines, and shapes. What other places are best represented by
  points? Lines? Shapes?

### Changing Objects

- Select the forest on the left side of the map. Be sure to click on
  the line around the forest, not one of the points on the line. Now
  hold your left mouse button down and drag your mouse. You should be
  able to move the forest to a new location on the map.
- Click on one of the points on the line around the forest. Hold your
  left mouse button down and drag your mouse. You should be able to
  move the point. This is how you can change the shape of an object,
  or move a point.

### Drawing

- On the left side of JOSM is a column of buttons. Many of these
  buttons open new windows on the right side that provide more
  information about the map. The most important buttons, however, are
  at the top of these column. These buttons change what you can do
  with your mouse.
- The top buttons in this column are the ones you will use the most.
  They are used for selecting objects and for drawing new ones.
- Until now, you have been using the Select tool, which looks like
  this:

  ![Select tool][]

- Before you draw, you need to make sure that nothing is selected.
  Click in the black space on the map, where it is empty, to make sure
  nothing is selected.
- Click on the second button, the Draw tool.

  ![Draw tool][]

- Find an empty area on the map, and double-click with your mouse.
  This will draw a single point.
- To draw a line, single-click with your mouse. Move your mouse and
  click again. Continue until you are happy with your line. To end the
  line, double-click your mouse.
- Draw a shape the same way that you draw a line, but finish the shape
  by double-clicking on the point where you started the line.

### Add Presets

- Now we know how to draw points, lines and shapes, but we still
  haven’t defined what they represent. We want to be able to say that
  our points are shops, schools, or something else, and whether our
  shapes are fields, buildings, or something else.
- Click on the Select tool, in the column of buttons on the left.

  ![Select tool][]

- Select one of the objects that you drew with the Draw tool. On the
  top menu, click “Presets”. Move your mouse through the sub-menu to
  the type of location you would like to define.
- When you click on a preset, a form will pop up asking you for more
  information. You do not have to fill in every field, but you may
  wish to add some of the important fields, such as the name of the
  object.
- When you are finished entering the information, click “Apply
  Preset”. If everything went well, your point, line, or shape should
  change colors or show a symbol. This is because you have defined
  what it is.

Draw Your Own Map
-----------------

- Now let’s draw a map in order to practice the techniques you have
  learned. You may wish to redraw the map that you drew on paper previously.
- Drag the map away from the sample map. Hold the right mouse button
  and drag your mouse, until you have a nice empty area to draw on.
- Use the Draw tool to create points, lines, and shapes. Describe what
  your objects are by selecting from the Presets menu.
- When you are finished, you should have your own map, similar to the
  sample map that we opened in sample.osm.

Summary
-------

Excellent! If all went well you have learned how to setup JOSM on your
computer, and the basic tools for drawing maps. In the next chapter we will
take a closer look at the process of editing the OSM map with JOSM.


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
