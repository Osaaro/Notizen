<h1> Notizen zur Website </h1>


1. Worum geht es auf meiner Website?                                              Star Wars
2. Welche Informationen zeige ich zu meinem Thema?                    Charakterbeschreibungen, Zusammenfassungen der Story, Planeten, verschiedene Schiffe
3. Wie soll meine Website aussehen?                                                  Dunkel, Simple, formale Schriftart, subtil



4. Website skizzieren *
5. Inhalte und aussehen bestimmen
6. Text schreiben
7. Hauptfarbe wählen
8. Bilder auswählen
  * Haben Sie ein Bild gefunden, das Sie nutzen möchten, machen Sie folgendes bei Google Images:
    * Klicken Sie auf das Bild.Wählen Sie "Bild ansehen“.
    * Klicken Sie mit der rechten Maustaste auf das Bild und wählen Sie "Grafik speichern unter…" oder kopieren Sie die Internetaddresse des Bildes und speichern diese ab.
9. Gehen Sie auf Google Fonts und scrollen Sie durch die Liste bis Sie eine Schriftart entdecken, welche Sie mögen. Sie können auch die Filter auf der rechten Seiten nutzen, um die Auswahl zu filtern.
  * Klicken Sie den "+" Button bei der gewünschten Schriftart.
  * Es erscheint eine Popup-Box. Klicken Sie auf den "* Family Selected" Button im unteren Bereich der Seite. ("*" abhängig davon wieviele Fonts man ausgewählt hat).
  * In der Popup-Box stehen jetzt zwei Codes. Diese können Sie kopieren und in einem beliebigen Texteditor für später speichern.


Einen Ordner für alle Webprojekte machen, im Webprojekte Ordner einen Ordner nur für diese Website erstellen, Index.html im VS Code erstellen, Bider Ordner, Styles Ordner (CSS-Dateien), Scripts Ordner  

Index.html

![Html-Dokument](/images/html-bildschirmfoto.png)

style.css

![css-Dokument](/images/css-Bildschirmfoto.png)

main.js

![Java-Script-Dokument](/images/javascript-bildschirmfoto.png)


Dann sieht die Website so aus:

![Website](/images/website-bildschirmfoto.png)

Am Anfang kann man seinen Namen in ein Pop-up Feld reinschreiben damit nachher der eigene Name im Titel steht.  Ausserdem kann man auf das w-vision Logo klicken damit es zu einem Star Wars Logo wird.




**Wie funktioniert der Weg vom Client bis zum Server?**


* Ihre Internetverbindung: Erlaubt Ihnen Daten über das Internet zu senden und zu empfangen. Dies ist wie die eigentliche Straße auf der Sie entlang gehen, um von Ihrem Haus zum Laden zu gelangen.
* TCP/IP: Transmission Control Protocol und  Internet Protocol  sind Kommunikationsprotokolle, welche bestimmen wie Daten über das Internet übertragen werden. Dies ist vergleichbar mit dem Transportvehikel, mit dem Sie zu dem Laden kommen, welches ein Auto oder ein Fahrrad oder ein anderes Fahrzeug sein könnte.
* DNS: Domain Name Servers sind wie ein Adressbuch für Internetseiten. Wenn Sie nach einer Internetadresse suchen, dann schaut der Browser auf dem DNS nach, um die wirkliche Adresse dieser Webseite zu finden. Der Browser muss herausfinden, auf welchem Server die Webseite liegt, damit er eine HTTP Anfrage an die richtige Stelle senden kann. Dies ist vergleichbar mit dem heraussuchen der Adresse des Geschäftes, in dem Sie einkaufen gehen wollen, damit Sie dieses auch finden.
* HTTP: Hypertext Transfer Protocol ist ein Applikations protocol welches eine Sprache definiert mit welcher Client und Server miteinander kommunizieren können. Dies ist wie die Sprache, mit der Sie im Laden Ihre Bestellung machen.
* Zusätzliche Dateien: Eine Webseite wir aus verschiedenen Dateien zusammengesetzt, ähnlich wie sie aus verschiedenen Teilen aus dem Laden etwas sinnvolles bauen können. Diese Dateien kommen in zwei Haupttypen vor:
* Code Dateien: Webseiten sind hauptsächlich aus HTML, CSS, und JavaScript, aber es gibt noch weitere Möglichkeiten.
* Inhalte: Dies ist alles andere, was auf einer Website zu finden ist, wie Bilder, Musik, Videos, Word-Dokumente oder PDFs.



**Was passiert jetzt also genau?**

Wenn Sie eine Internetadresse in Ihren Browser eintippen (wie wenn Sie zu dem Laden gehen):
1. Der Browser kontaktiert den DNS Server und findet die echte Adresse von dem Server auf dem die Webseite liegt (Sie finden die Adresse des Ladens).
2. Der Browser sendet eine HTTP-Anfrage an den Server und fragt nach einer Kopie der Webseite für den Client (Sie gehen zu dem Laden und bestellen Ihre Waren). Diese Nachricht und alle anderen Daten, welche zwischen Client und Server gesendet werden, nutzen Ihre Internetverbindung und nutzen TCP/IP für die Übertragung.
3. Wenn der Server die Anfrage entgegennimmt, sendet dieser an den Client eine "200 OK" Nachricht, welche soviel bedeutet wie "Natürlich können Sie sich die Webseite anschauen! Hier ist sie." Danach sendet der Server die Dateien der Webseite, in kleinen Datenpaketen, an den Browser.  (Im Laden bekommen Sie Ihre Waren und bringen diese nach Hause)
4. Im Browser werden die kleinen Datenpakete zusammengesetzt und zeigt Ihnen die komplette Webseite. (die Waren kommen bei Ihnen daheim an)
