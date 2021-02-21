# RalSWiek Preview Repository
> Release repo for the RalSWiek project

> Aktuelle Version pre 0.1.4
> Current version: pre 0.1.4
---

Das RalSWiek-Projekt ist ein Rollenspiel, das auf dem XNA-Framework basiert.
Der Benutzer übernimmt die Kontrolle über einen kleinen Mann, der sich über einige Inseln bewegen muss.
Auf diesen Inseln leben einige seltsame Menschen. Es gibt einen immer betrunkenen Zauberer und einen manchmal kämpfenden Lehrer. Der Zauberer hält eine Aufgabe bereit.
Du musst seine Suche beginnen, sonst kann man die erste Insel nicht verlassen.
Die zweite Insel hat ein automatisches Ende. Dabei müssen beide Teleporter genutzt werden, um zur ganz rechten Insel zu gelangen. Dort ist das Ende rechts neben dem Teleporter.

The RalSWiek project is a roleplay game based on the XNA framework. 
The user takes control over a little man who has to pass his way over some islands.
On this islands there are some strange people living. There is an always drunk wizard and a sometimes struggeling teacher. The wizard holds a quest for you.
You have to start his quest. Otherwise you can't leave the first island.
The second island has a automatic end. You have to reach the third small island on the left and have to walk to the right upper side. 

---

#### Sound bug

Um Sounddateien abspielen zu können, muss der OpenAL-Treiber installiert werden. Anderenfalls läuft das Spiel ohne Ton.

To prevent the sound bug please run the OpenAL_Driver_Installer.exe. This will install the OpenAL driver which is needed for the XNA framework to load and play sound files.
The game will run without sounds otherwise.

---

#### 4K Support

Wird auf einem 4K-Display gespielt, muss eine Datei "4k.txt" im Verzeichnis der Spieldatei erstellt werden.

If you use a 4K display create a textfile "4K.txt" in the directory of the game exe. Otherwise the dialogues and inventory overlays will be displayed wrong.

---

#### Imüplementierte Funktionen / Implemented Functions
- Inventarsystem / Inventory overlay with movable item frame
- Lebens- und Manapunkte-System / Health and Mana system
- Nutzbare Tränke / Usable poisons
- Interaktionen mit NPCS / Dialogues with NPCs
- Questsystem / Quests
- Unterschiedliche Level / Different levels
- Teleporter
- Umherlaufende NPCs / Moving NPCs
- Sammelbare Items / Collectable items
- Interaction mit Objekten in der Welt / Interaction with objects in the world
---

#### Tastenbelegung / Controls

- W A S D bewegt die Spielfigur. / W A S D moves the character.
- E ist die Aktionstaste / E to talk to NPCs and to use teleporter
- PFEIL HOCH und RUNTER wählt Dialogoptionen / ARROW UP and DOWN to switch dialogue options
- I öffnet und schließt den Inventar / I to open/close the inventory
- PFEILTASTEN bewegen die Inventarauswahl / ARROW Keys to select an item in the inventory
- ENTER wählt eine Dialogoption aus / ENTER to select a dialogue option
- LEERTASTE wechselt bei Erfolg in den nächsten Level / SPACE after the "Finished" sound to leave the level
- F3 Debug
- MAUSRAD HOCH und RUNTER zoomt die Kamera / MOUSE WHEEL UP and DOWN for camera zoom
---
#### Bekannte Fehler / Known bugs

- Der Lehrer läuft wild umher / The teacher struggles sometimes.
- Falsche Dialogtexte / Some wrong dialogue texts

#### Copyright

- Sound from Zapsplat.com
