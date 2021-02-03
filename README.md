# Styleguide

Was IT von Styleguide braucht / Was bei Syleguide zu beachten ist:

Allgemeines:

Stell dir Alles als einzelne Elemente vor (z.B. einen Button oder eine Überschrift), die mit anderen Elementen ein weiteres Element bilden (Text + Button oder Überschrift und Untertitel). 
Diese Elemente erweitert man (bzw. gruppiert sie mit weiteren Elementen), sodass daraus am Ende eine Seite wird.

Diese Elemente sollten immer gleich bleiben. Natürlich sieht ein Fließtext anders aus, als ein Text unter einer Überschrift. Aber alle Texte unter einem bestimmten Typ von Überschrift sehen gleich aus.

&rarr; Alles besteht aus einzelnen kleinen Elementen, die sich immer wiederholen. Diese müssen bestimmt werden und auch, wie sie zusammen mit anderen Elementen aussehen.  
&rarr; Sodass am Ende ein “Baukasten” entsteht, mit dem man aus den Elementen eine Seite baut.

Für jedes Element ist wichtig:
- wie soll es mobil aussehen, und wie bei größeren Bildschirmen (Desktop). Es muss dabei aber weiterhin so aussehen, als wäre es immer noch eine Seite. Natürlich können Elemente auch mobil und auf Desktop gleich aussehen.
- Wenn man verschiedene Hintergrundfarben hat (z.B. einen Hellen Hintergrund und einen dunklen), wie soll das Element auf diesem hellem und wie auf diesem dunklen Hintergrund aussehen.

Bitte beachten:

Es gibt Menschen, die nicht so gut sehen oder schlechte Geräte haben (schlechte Farbdarstellung oder schlechte Auflösung). Auch diese Menschen sollen die Website/App besuchen können.
Es gibt Menschen, die Farbenblind sind (rot-grün Schwäche oder nur Grautöne).  Auch diese Menschen sollen die Website/App besuchen können.

Dafür ist wichtig:
- guter Kontrast zwischen Text und Hintergrund (Überprüfung z.B. mit https://webaim.org/resources/contrastchecker/)
- Infos (z.B. Fehler), sollen auch durch Icons erkannt werden. z.B. einen Haken für “Erfolg/Alles gut” oder ein “!” für “Achtung / Fehler”

Allgemeine Regeln:
- Achtet auf die Hierarchy. Eine h1-Überschrift soll mehr beachtet werden, als ein h2-Überschrift
- nicht mehr als 2 Fontfamilies (z.B. Robot, Raileway) pro Seite.
- Bitte Google Fonts benutzen, sind besser einzubinden
- Achtet auf Konsistent, auch wenn Unterseiten etwas anders aussehen. User wollen Elemente wiedererkennen und wissen, dass sie noch auf der gleichen Seite sind.
- Best Practice sind nicht zu viele Farben (1 bis 3 Farben + Abstufungen davon) + Text + Hintergrund + UI Farben (Rot für Fehler/Warnung, Grün für Erfolg, Gelb oder Blau für Info)
- Farben bitte in HEX-Code oder bei Transparenz RGBA angeben
- Best-Practice: Abstände zwischen Elemente sind mobil meist kleiner als auf Desktop. Da Schriften auch meist kleiner sind.
- Website mobil sieht anders aus als eine App, selbst wenn es zusammen gehört.

Speziell:

Für Text-Elemente:
- Fontfamily (z.B. Roboto)
- Textgröße (fontsize): Best-Practice sind mindestens 16px; bitte in px angeben
- Textdicke (fontweight): ist der Text dick/dünn/normal? Bitte in 300, 400, 500, etc angeben
- Zeilenhöhe (lineheight) des Textes;
- Farbe (color) des Textes; bei mehreren Hintergründen (zB hellem und dunklen), Farbe je Hintergrund

Für interaktive Elemente (alles was man anklicken kann):
- Aussehen, wenn noch nicht geklickt
- Aussehen, wenn man mit Maus darüber fährt (hover)
- Aussehen, wenn geklickt (active)
- evtl Aussehen, wenn man Element nicht anklicken kann

Sonstiges:
- Wenn Elemente Hintergrundfarbe oder einen Rahmen haben: Wie viel Abstand von Rahmen/Ende des Hintergrundes zu dem Element
- Sollen die Ecken abgerundet sein?
- Sollen die Elemente einen Schatten haben?
- Wenn es eine Linie oder einen Rahmen gibt: Wie dick ist dieser?
- Wie viel Abstand haben die Elemente zueinander?

Welche Elemente gibt es / werden vorkommen:
- Textelemente:
- Fließtext
- Text unter Überschrift
- Überschriften (benutzt werden meist h1 - h4). Pro Seite gibt es eine h1, die die Hauptüberschrift ist. Die anderen sind für Titel, die unter diesem Titel stehen.)
- Links
- Listen
- Buttons: Meist benutzt man einen Primary Button (wichtiger) und einen Secondary (weniger wichtig)
- Form Elemente:
- Textinputs (Felder, in die man einen Text eingibt)
- Selects (Felder, bei denen man nur eine Option sieht und beim Daraufklicken mehr angezeigt werden)
- Radio Buttons (Dabei musst du eine von mehreren auswählen; diese sind rund)
- Checkbox (Du kannst das Feld  oder mehrere auswählen (zB AGB akzeptieren); diese sind eckig)
- Textarea (Textfelder, die größer sind, für mehr Text)

Anforderungen an hochzuladende Bilder:
- wenn für Wordpress:
  - Bild: .jpeg
  - Icon: .png
- sonst: .svg, bei Bildern .png
- in der Größe, die auch gebraucht wird (ohne größer/kleiner ziehen) - evtl automatisieren wir dies

Ressourcen:
- Best Practice für Formen (engl): https://gerireid.com/forms.html
