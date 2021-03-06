# TODOS

* [ ] Put rest server in $mode=production
* [ ] Validate Upload Form in javascript before submitting file
* [ ] Upload size erhöhen wenn möglich 

## Fixes (22.6.15)

* [x] Upload: die neue Trennung der Keywords durch Komma ist im
Beschreibungstext noch nicht angepasst

* [x] Index: Bei Uploads mit mehreren Autoren werden die Autoren im Index
nicht separat dargestellt, sondern als eine Einheit. Bitte separieren
und alphabetisch ordnen. z.B:
    ```
    FIZEK, SONIA
    FUCHS, MATTHIAS
    RUFFINO, PAOLO
    SCHRAPE, NIKLAS

    anstatt:
    FUCHS, MATTHIAS; FIZEK, SONIA; RUFFINO, PAOLO; SCHRAPE, NIKLAS
    ```

## Fixes (20.6.15)

* [x] Landing Page: Der neueste Upload soll an erster Stelle angezeigt werden

* [ ] Seiten mit Items (nur in Chrome und Safari): Dreispaltige Anordnung der items funktioniert nicht immer. Bei 7 Einträgen wird nur die erste Reihe mit 3 Einträgen gefüllt, die anderen beiden haben jeweils nur 2. Bei 8 Einträgen ist dann wieder ok. Komisch. **Kann das Problem nicht reproduzieren**

* [x] Header-Wrapper: Content fließt sichtbar durch den Header durch. Bitte einen weißen Hintergrund für den Header-Wrapper.

* [x] Index Seite: Titles bitte farblich  codieren nach dazugehöriger collection

* [x] Upload: Required Fields sind nicht gekennzeichnet

* [x] Upload: Zusammengesetzte Keywords können nicht eingeben werden, da Special Character nicht unterstützt sind. Bitte Special Character zulassen und die Keywords mir Komma anstatt Leerzeichen separieren (auch im Beschreibungstext anpassen)

* [x] Upload: Der Range des Publishing Year Input Feldes, bzw. des dazugehörigen Buttons ist von 0 - 9999 und inkrementiert um 1. Das macht keinen Sinn. Kannst du den Button bitte entfernen?

* [x] Upload: neuer Disclaimer: "Respect copyright. Please be sure not to violate others' copyright or privacy rights. Only upload content that you made or that you're authorised to use."

* [?] Nach einem Upload wird eines neuen Eintrags wird auf der Home Seite das Item ohne Abstract und in falscher Größe dargestellt. Erst nach einem Refresh passt alles wieder. **habe die größe des items gefixt, kann aber das problem mit dem abstract weder in chrome, safari oder firefox reproduzieren**

### Admin Pages

* [x] In "Collections": Die Farbänderung braucht einen Hinweis, sonst checkt das keiner (habs testen lassen)

* [x] Reiter-Item "Docs" umbenennen in "Entries"

* [x] Reiter-Item "Page" umbenennen in "Settings"

* [x] Settings aka Page: Neue Anordnung und Gruppierung der Elemente in:

    ```
    HEADER:
    - Upload Logo (Button bitte Linksbündig)
    - Change Header Color (Farbänderung braucht einen Hinweis)
    ____________________________________
    FOOTER TEXT
    ____________________________________
    ABOUT PAGE
    Edit text
    ___________________________________
    ADMIN PASSWORD
    Type in your new password and click on SET
    ```

### Fixes (2.6.15)

* Document List
    * [x] truncate description
    * [x] make author more prominent
    * [x] keywords zufällig verschieben, evt in weiss darstellen
    * [x] Farben in topic drop down menu
    * [x] Kein Topic-Farbe auf primär farbe ändern
    * [x] Fix Column layout, no blank space
    * [x] Add Entry Type Property
* Upload
    * [x] Title Feld automatisch angewählt
    * [x] Autor und Keyword format erklären
    * [x] Autor format: Lastname, Firstname; Lastname2, Firstname2; ...
    * [x] Progressbar für file upload
    * [x] Disclaimer unter upload formular einfügen
* Index
    * [x] Kategorien einklappbar
    * [x] Color Coding für Topics und Title, evt durch farbige bullets
    * [x] Autor Index: nur erstautor anzeigen
* Admin    
    * [x] Topic Farbe aus 16 Grundfarben auswählbar
    * [x] Header Farbe und Logo auswählbar
    * [x] About, Footer Text auswählbar
* Header
    * [x] Topic schrift weiss 
    * [x] Search funktion implementieren
    * [x] Header Schriftzug neben Logo "Offline Library"

* Other
    * [x] "Topic" durch "collection" ersetzt werden 
    * [ ] Logout mechanismus
    * [x] Special Characters in upload file 
    * [x] Collection:name statt topic_id bei filter
    * [x] Fix Column Anordnung der Items in Firefox
    * [ ] Buggy Collection dropdown in safari
