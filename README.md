# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   5/60 Punkten
#### Punktabzüge für:
- [x] (10) Elemente passen sich nicht an Fensterbreite an
```diff
- Das Formularfeld für Nachname springt bei vielen Fensterbreite nach rechts.
```
- [x] (10) Tags nicht geschlossen oder falsch verschachtelt
```diff
- row und col sind falsch verschachtelt. Inhalt darf nur in col stehen. col muss in row verschachtelt sein.
```
- [x] (5) Block-Tag in Inline-Tag
```diff
- aside in button (Zeile 110)
```
- [x] (5) Kinder-Tags im Code nicht eingerückt
```diff
- Ab Zeile 82 ist unklar, was Kinder und was Eltern sind
```
- [x] (10) Zweckfremde Tags verwendet
```diff
- aside für inline-Text verwendet
```
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [_] (5) Falsche Datei-Pfade
- [x] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- font-Styles im *-Selektor sollten nicht verwendet werden
```
- [x] (5) Fehlende essentielle Tag-Attribute
```diff
- In button kann im type-Attribut nicht der Wert "bottum" verwendet werden
```
