## HTML - GRUNDSTRUKTUR
* doctype - jede HTML Version hat seinen spezifischen doctype
* html - umschließt die gesamte Web-Seite und beinhaltet Sprachparameter
* head - beinhaltet hauptsächlich technische und dokumentarische Informationen
* body - umschließt den Inhalt der Seite, die im Browser dargestellt wird

* script - bindet JavaScript-Code in die Seite ein
* noscript - wird ausgeführt, wenn kein JavaScript zur Verfügung steht
* style - enthält Stilinformationen, hauptsächlich CSS-Deklarationen



### HTML - HEAD
* title - bezeichnet den Titel der Seite, der von den meisten Browsern in der Titelleiste angezeigt wird
* meta - kann vielfältige Metadaten enthalten, z.B. Darstellungsoptionen, SEO-Daten
* base - gibt entweder eine Basis-URI oder einen Basisframe an
* link - dient zur Angabe von logischen Beziehungen zu anderen Ressourcen, z.B. CSS


### HTML - UNSEMANTISCHE, SEGMENTIERENDE ELEMENTE
* div - generischer Container für unspezifische Inhalte, volle Breite
* p - definiert einen unspezifischen Textblock, Abschnitt
* span - generischer Container für unspezifische Inhalte, exakte Breite

### HTML - SEMANTISCHE, SEGMENTIERENDE ELEMENTE
* main - beinhaltet den Hauptinhaltsbereich der Seite
* article - beinhaltet einen Artikel, in sich abgeschlossenen Inhalt
* section - beinhaltet einen unspezifischen, in sich abgeschlossenen Inhalt
* nav - beinhaltet die Navigation der Seite,
* aside - beinhaltet Nebeninformationen zum Artikel oder zur Seite
* details - beinhaltet zusätzliche, optionale Informationen
* summary - beinhaltet eine Zusammenfassung
* header - beinhaltet den Kopfbereich der Seite
* footer - beinhaltet den Fußbereich der Seite
* address - beinhaltet die Kontaktinformationen zum Artikel oder zur Seite

### HTML - TEXT ELEMENTS
* h1 - h6 - verschiedene Formate an Überschriften
* strong - definiert einen wichtigen Text
* em - definiert einen bedeutungsvollen Text
* mark - definiert einen markierten Text
* small - definiert einen kleinen Text
* del - definiert einen gelöschten Text
* ins - definiert einen hinzugefügten Text
* sub - definiert einen tiefgestellten Text
* sup - definiert einen hochgestellten Text
* abbr - definiert eine Abkürzung
* code - definiert einen Code-Abschnitt
* b - definiert einen Text in fetter Schrift, veraltet
* i - definiert einen Text in kursiv Schrift, veraltet
* s - definiert einen durchgestrichenen Text, veraltet
* u - definiert einen unterstrichenen Text, veraltet

### HTML - KOMPLEXE ELEMENTE
* canvas - erzeugt eine Zeichenfläche / Leinwand
* iframe - Fenster in ein anderes Dokument
* figure - Container für Grafiken und Abbildungen
* img - definiert ein Bild
* picture - Container für mehere Bildquellen für ein Bild
* audio - bettet Audio in eine Webseite ein
* video - bettet Video in eine Webseite ein
* form - definiert ein Formular
* dl - definiert eine "description" Liste
* ol - definiert eine sortierte Liste
* ul - definiert eine unsortierte Liste
* table - definiert eine Tabelle
* template - dynamisch generierter, gerenderter Inhalt
* blockquote - definiert ein
Zitat

### HTML - TABELLEN
* table - Tabelle
* caption - Kurzbeschreibung einer Tabelle
* tbody - Körper einer Tabelle
* thead - Tabellenkopf
* tfoot - Tabellenfuß
* th - Kopfzelle einer Tabelle
* tr - Tabellenreihe
* col - Tabellenspalte
* colgroup - Tabellenspaltengruppe
* td - Tabellenzelle


### HTML - FORMULALRE
* form - Behälter für ein Formular
* fieldset - Behälter für Formularinhalte
* label - Beschriftung eines Formularelements
* legend - Beschriftung eines Formularbereichs
* input - Eingabefeld - hidden, text, number, range, password, search, checkbox, radio, date, color, email, file, image, button, submit, reset
* datalist - Eingabefeld
* button - Schaltfläche
* select - Behälter für eine Auswahlliste
* option - Option einer Auswahlliste
* optgroup - Optionsgruppe in einer Auswahlliste
* textarea - Eingabefeld für lange Texte
* output - Ausgabe einer Berechnung, die durch ein Script erzeugt wurde
* progress - Fortschrittsbalken
* meter - Wert innerhalb eines bestimmten Bereichs
* keygen - Erzeugt ein Paar aus öffentlichem und privaten Schlüssel   

HTML - FORMULARE - TYPE INPUT
types
* number
* email
* text
* url
* password
* tel
* checkbox
* radio
* hidden
* range
* color
* file
* image
* url
* button
* reset
* submit
* date
* datetime
* datetime-local
* month
* time
* week
* attributes

type, id, name, value, disabled, min, max, autocomplete, placeholder

### HTML - LISTEN
Geordnete und ungeordnete Listen sind sehr beliebt.

Listen können in beliebiger Tiefe verschachtelt werden.

* ol - beinhaltet eine geordnete Liste
* ul - beinhaltet eine ungeordnete Liste
* li - beinhaltet ein Listenelement
* dl - beinhaltet eine "description" Liste
* dt - beinhaltet den Titel des Eintrags
* dd - beinhaltet den Inhalt des Eintrags