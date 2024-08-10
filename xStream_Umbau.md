

*Support Informationen anzeigen*
Nach Auswahl werden System Informationen angezeigt, welche für die Hilfe im Chat benötigt werden

*Resolver Einstellungen*
Hier werden Einstellungen zum Resolver vorgenommen

*Manuelle Aktualisierung starten* (Aktualisierung erzwingen)
Hiermit kann eine Update vom Resolver oder von xStream *erzwungen* werden
Informationsfenster führen durch den Update Prozess
Bitte aufmerksam lesen und die Anweisungen befolgen







Wenn Ihr Probleme mit s.to, kinox usw. habt, hilft es wenn Ihr Eure DNS Adresse (z.B. auf die von Google 8.8.8.8 und 8.8.4.4) ändert

Manche Seiten werden von den Internet Providern geblockt

Einge Seiten wie z.B. Flimmerstube, s.to usw. benötigen ein EIGENES Benutzerkonto auf der Seite, um diese Verwenden zu können

Ausserdem kann bei eingen Seiten (z.B.s.to) die Webseiten Domain in den xStream Einstellungen geändert werden, sollte es Probleme geben







### 2.4 Manuelle und automatische Hosterwahl

Die Hosterwahl als solches ist sehr schlicht und einfach gehalten

Es erinnert stark an die eigentlichen Benuteroberflächen der jeweiligen Streaming-Seiten

Wenn keine besonderen Wünsche bzw. keine entprechende Kenntisse im Bezug auf die Hosterauswahl vorhanden sind, kann die Automatische Hosterwahl verwendet werden

In dieser Einstellung werden darüber hinaus nicht funktionierende Hoster rausgefiltert





**Hosterauswahl**

*Dialogansicht (Standard)*
Bei Aktivierung wird die Hosterauswahl als Pop-Up Fenster dargestellt

*Listenansicht*
Bei Aktivierung wird die Hosterauswahl nicht mehr als Pop-Up-Fenster dargestellt, sondern als normale Verzeichnisliste

*Automatisch abspielen*
Automatische Hosterauswahl

Näheres dazu Kap.[2.6 Autoplay Funktion](#26-autoplay-funktion)

**Hosterliste prüfen und sortieren**

Bei Aktivierung werden aus der Hosterliste alle nicht unterstützten Hoster entfernt und nach ihrer Priorität (Resolver Settings) sortiert

Diese kann unter xStream - Einstellungen - Resolver Einstellungen - Universelle Resolver angepasst werden

*Niedrige Werte werden vor hohen Werten gewählt*

*Da xStream und andere Addons den gleichen Resolver verwenden, hat diese Einstellung auch Auswirkung auf diese Addons!!*





### 2.6 Autoplay Funktion

Einstellungen dazu sind in der Kategorie *ALLGEMEIN* zu finden

Hosterauswahl muss hierzu auf *Automatisch abspielen* stehen

Ist diese Option aktiviert, wird keine Hosterliste angezeigt

xStream probiert automatisch alle verfügbaren Hoster aus, bis ein Stream abgespielt werden kann

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität

Diese kann unter "Resolver Einstellungen" beim jeweiligen Hoster angepasst werden

*Niedrige Werte werden vor hohen Werten gewählt*

Sind Eure Priorisierten (Lieblings) Hoster nicht dabei (weil sie nicht verfügbar sind), nimmt xStream den nächsten Hoster der funktioniert




### 2.8 Downloads

xStream bietet die Möglichkeit, Filme/Serien von den Webseiten herunter zu laden

Dazu muss die *Hosterauswahl auf Listenansicht* gestellt sein, damit das entsprechende Menü angezeigt wird

In den xStream Einstellungen - Downloads, muss hier bei Download Verzeichnis, ein Speicherpfad festgelegt werden

Danach einfach die Episode oder Film starten, dann kommt die Hosterauswahl 
Hier das Kontextmenü aufrufen und Download wählen

**Download in Verbindung mit JDownloader2.**

Dabei macht Kodi/xStream nichts anderes als die URL an den JDownloader2 zuschicken

Dafür muss die IP des Gerätes konfiguriert sein auf dem JDownloader2 läuft

Desweiteren muss in den xStream-Einstellungen unter Allgemein/Hoster/Hosterauswahl auf Listenansicht eingestellt sein, da sonst das Kontextmenü nicht funktioniert

Danach einfach die Episode oder Film starten, dann kommt die Hosterauswahl und dann Kontextmenü aufrufen und dann "send to JDownloader2" drücken




### 3.0 TheMovieDB Helper

**Informationen**

TheMovieDB Helper bietet die Möglichkeit über verschiedene Player (z.B. xStream), lokale Videodateien und Streams abzuspielen

Das Addon TheMovieDB Helper ist ein eigenständiges Addon und dient als Erweiterung für xStream

Eine genau Beschreibung des Addons, Einstellungen und dessen Funktion ist hier zu finden: [TMDB Helper](https://www.kodinerds.net/index.php/Thread/76317-HowTo-TMDB-Helper/)

Informationen aus TMDb -, OMDb - und Trakt-APIs werden mit eigenen Benutzerdaten unterstützt

Die Player Datei muss für jede Seite separat erstellt werden, da die derzeitige Globale xStream Suche, diese Funktion nicht unterstützt

Die Downloads von verfügbaren Playerdateien sind auf der [Webseite]( https://streamxstream.github.io/xStreamRepoWeb/) zu finden

**Installation:**

*Das TheMovieDB Helper Addon befindet sich in der Kodi Repo und muss installiert werden, das geht wie folgt:*
  
Addons – Addons Browser (Schachtel) – Suchen – tmdb eintippen und OK

Das Addon **Medienquellen TheMovieDB Helper** installieren

Nach der Installation und dem Download der Player Datei, zu folgendem Pfad gehen und einen neuen Ordner *players* erstellen:

*userdata/addon_data/plugin.video.themoviedb.helper/players/*

Im Anschluss die Player Datei in diesen Ordner kopieren  
  
Nun kann diese Seite vom TMDb Helper Addon durchsucht und zum Abspielen xStream verwendet werden

**Einrichtung**

Nach der Installation die Einstellungen des Addons öffnen 

*Allgemein* 

Bei *Language and Country* auf German (Germany) stellen

*Accounts*

Unter Accounts kann [Trakt.tv](www.trakt.tv) konfiguriert werden

**Trakt Konto einrichten:**

Trakt.tv bietet viele Möglichkeiten, wie z.B. das Synchronisieren des Fortsetzungspunktes auf deren Server

Auf Trakt.tv ein Konto erstellen

In der Kategorie *Accounts* - *Trakt API* auf *Authenticate Trakt Account* klicken

*Es wird ein Infofenster angezeigt:*

Webseite besuchen: https://trakt.tv/activate

Dort werdet Ihr dann aufgefordert den Code (der in Kodi angezeigt wird)  einzugeben, Continue

Allow Trakt Helper to use Your Accout (Erlaube Trakt Helper die Verwendung Deines Kontos), YES

WooHoo! Your device is now connected and will automatically refresh in a few seconds (Dein Gerät ist jetzt verbunden und wird in wenigen Sekunden automatisch aktualisiert)

Zurück in plugin.video.themoviedb.helper wird nun zusätzlich die Kategorie Trakt angezeigt

Der Trakt Service kann ab jetzt genutzt weren

Nachdem nun im Addon eine Suche durchgeführt wurde und das Ergebnis angezeigt wird, kann das Kontextmenü geöffnet werden und hier *Trakt options*

Im folgendem Menü gibt es eine Anzahl an verschiedenen Trakt Möglichkeiten wie zum Beispiel "Add to Watchlist". Wird hier etwas gespeichert, ist das quasi die Trakt Merkliste, was man später mal anschauen möchte

Zu finden ist das Ganze dann im Menüpunkt Trakt z.B. unter Serien Watchlist

Startet man nun etwas aus der Watchlist, verschwindet es von dort und ist unter dem Eintrag *Your Recently Watched Serien/Filme* zu finden mit aktuellem gesehen Status

Dieser Menüpunkt kann dann für einen schnellen Zugriff als Kodi Favoriten gespeichert werden

*API Keys*

Bei API Keys können persönliche OMDB und Fanart.tv API Keys eingetragen werden

*Bibliothek*

Unter Bibliothek wird der Speicherpfad angelegt, wo Filme und Serien Verknüpfungen gespeichert werden und somit in die Kodi Bibliothek hinzugefügt werden können

*....userdata/addon_data/plugin.video.themoviedb.helper/movies*

*....userdata/addon_data/plugin.video.themoviedb.helper/tvshows*

Diese Ordner erscheinen erst, wenn ein Film bzw. eine Serie zur Bibliothek hinzugefügt wurde

Der Speicherpfad kann auch geändert werden bzw. manuell angelegt werden

Um etwas zur Kodi Bibliothek hinzuzufügen, wird nach Anzeige des Suchergebnis das Kontextmenü geöffnte und daraus der Eintrag *Zur Bibliothek hinzufügen* ausgewählt

Es werden nun lokale .strm Dateien in obigem Ordner abgelegt

Da das Addon sehr umfangreich ist, müssen weitere Funktionen durch Selbsttests herausgefunden werden

**TMDb Helper Addon verwenden**

Hier eine Beispiel für die Serien Suchen über Serienstream

Das Addon öffnen und Suchen klicken

Suchen Serie

Im Suchfeld z.B. Arrow eintippen und OK

Im Anschluss das gewünschte Suchergebnis, hier Arrow, auswählen

Staffel und Episode wählen

Im Anschluss erscheint nach kurzer Zeit ein Popup Fenster wo *Play with SerienStream* ausgewählt wird, dann die Serie (z.B. Arrow)

Nun kommt das gewohnte Fenster, *Hoster wählen*, welches schon bekannt ist

Ist der gewünschte Hoster nicht verfügbar, die obigen Schritte wiederholen

Was einmal gesucht wurde, ist im Reiter Suchen immer zu sehen und kann durch Clear Search Hirstory entfernt werden

*Eine TMDb Helper JSON Datei kann folgende Parameter enthalten:*

*name*: Name des Players

*plugin*: plugin ID des abzuspielenden Programms

*priority*: Priorität an welcher Stelle der Player in der Liste steht

*search_movie*: Plugin Eintrag für Suche Filme + erweiterte Parameter

*search_episode*: Plugin Eintrag für Suche Serie + erweiterte Parameter

*play_movie*: Plugin Eintrag für Filme + erweiterte Parameter

*play_episode*: Plugin Eintrag für Serien + erweiterte Parameter

*assert*: Erweiterte Einträge

*fallback*: Fallback Player wenn Datei nicht gefunden wird

Weitere Informationen zur Player Datei sind hier zu finden: [Link](https://github.com/jurialmunkey/plugin.video.themoviedb.helper/wiki/Player-Function)

## 3. Bekannte Probleme

### 3.1 Fehler bei der Installation

Fehler können verschiedene Ursachen haben

**Bei Hilfe bitte immer folgendes bekannt geben:**

**Kodi Version, Betriebssystem, xStream Version, Resolver Version, genaue Fehlerbeschreibung und eventuell Kodi Log, !**

OHNE diese Informationen gibt es KEINE Antwort/Hilfe vom Team!!

Diese Informationen können zum Teil direkt in xStream abgefragt werden:

*xStream starten - Einstellungen - Support Informationen anzeigen*



### 3.2 Fehler bei Verwendung der Globalen Suche

Falls bei der Globalen Suche eine Fehlermeldung bekommen, dass eine Seite nicht erreichbar war bzw. die Suche durch eine Meldung unterbrochen wurde, liegt dies meist an der Seite

Meistens ist eine Seite in diesem Moment nicht erreichbar, einfach abwarten und die betroffene Seite deaktivieren

Es kann auch vorkommen, dass bei der Globalen Suche keine Treffer angezeigt werden, dann bitte in der gewünschten Seite die Suche nutzen (manchmal stören die Seiten, die Globale Suche)

Um schnelle Abhilfe zu leisten lohnt es sich in diesem Fall durchaus die Entwicklergemeinde darauf aufmerksam zu machen






- **Bei direkter Suche in Serienstream kommt Meldung Error 500**

In den Einstellungen ist bei Serienstream, bei *Domain auswählen* auf Proxy gestellt

Als DNS Adresse wird auf dem betroffenem System, die DNS von Cloudflare (1.1.1.1) verwendet

Es ist offensichtlich so, dass es bei dieser Kombination zu Proxy Probleme mit der Cloudflare DNS kommt

Abhilfe schafft hier entweder eine andere DNS Adresse (z.B. Google 8.8.8.8 und 8.8.4.4.) zu verwenden oder von Proxy auf s.to umstellen

- **http Timeout Fehlermeldung bzw. the read operation timeout**

Kann an den Webseiten liegen wenn sie lange brauchen zum aufbauen oder sie ist Offline

Das Problem ist eher temporär, später nocheinmal probieren

Ebenso werden bei s.to Benutzer ausgesperrt, die einen VPN benützen bei der Verwendung mit Kodi



- **CLOUDFLARE-SCHUTZ AKTIV**

Das ist eine Fehlermeldung die kommt wenn eine Seite wie z. B. Filmpalast den Anti-BOT-Schutz von 

CLOUDFLARE aktiviert hat. Dann ist die Seite nicht mehr direkt zugänglich sondern es kommt entweder 

eine Art Warte-Seite wo der Bot prüft ob man ein Mensch ist oder man muss ein Capcha lösen, Haken klicken etc.

Kodi/xStream kann das nicht umgehen und hat bisher immer eine nichtssagende Fehlermeldung herausgegeben.

Das haben wir nun geändert.

Was könnt ihr gegen den Schutz machen? Rein gar nichts!! Einfach abwarten bis dieser nach ein paar Stunden bzw.

Tagen wieder verschwindet, und solange eine der anderen Seiten oder die VoD Dienste benutzen.

- **Beim Starten von xStream kommt folgende Fehlermeldung**

	- "IOError: [Errno socket error] [SSL:CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:590)
	
	- Status: Problem behoben
	
	- *Anmerkung:* in den xStream-Settings die Suche nach Updates ausschalten, dann läuft es wieder
	
	Updates von Git muss man dann manuell einspielen oder auf Updates über das offizielle xStreamRepo warten
	
- **Beim Öffnen von Serien/Filmen in xStream kommt folgende Fehlermeldung**

	- AttributeError:´loadError´ object has no attribute ´encode´
	
	- Lösung: 
	
	Kodi (und daher auch xStream) mag keine Sonderzeichen im Benutzernamen,
Sonderzeichen im Benutzernamen entfernen dann geht es


		

	
- **Errno 1 bzw. Errno 8 Fehlermeldung bei Seiten**

	Die Webseitenbetreiber & Hoster stellen Ihre  Verschlüsselung um

	Das Problem hat nichts mit xStream zu tun

	Es liegt an Kodi, bzw. der Pythonversion welche Kodi verwendet

	Ist diese veraltet kommte es zur Fehlermeldung bei diversen Site-Plugins / Hoster
	
	- Lösung: Kodi 19 bzw. Kodi 20 verwenden

- **"HTTPError HTTP Error 403**

	Weißt auf ein Problem mit dem VPN hin oder irgend etwas anders was mit Eurem Internet zutun hat.

	Deaktiviert mal den VPN und überprüft ob das Problem weg ist 

- **Site-Plugin Fehlermeldung: "kein Eintrag vorhanden"**

	zwei Probleme die das verursachen können:

	- VPN/Proxy
	- falsch gesetzte Zeit/Datums-Werte
	
- **Fehlermeldung bei Hosterauswahl: "no supported Hoster available"**

	Es kommt öfters vor das beim ersten Auswählen eines Elements die Meldung "no supported Hoster available" erscheint

	Klickt man erneut auf das selbe Element erscheint ganz normal die Hosterauswahl
	
	Helfen kann auch noch folgendes:
	
	xStream Einstellungen -> Hosterliste prüfen und sortieren, auszuschalten 

- **Errno 10061: Fehler Globale Suche**

	Bei der globalen Suche wird bei ca. 50% immer der Fehler *10061 Errno* angezeigt

	Man kann ihn weg klicken und gut ist es. Ergebnisse werden dann auch angezeigt 

	- Lösung: Das Problem wird von einer bestimmten Indexseite verursacht (beobachten bei welcher Seite der Fehler kommt), diese deaktivieren bis der Fehler behoben wird. Sie verursacht den Fehler

- **urlopen error [Errno 111] Connection refused:**

Connection refused (Verbindung abgelehnt) bedeutet, dass das Ziel (der Server der Webseite) die Verbindungsanfrage nicht akzeptiert, weil sich der Client (Kodi) nicht mit dem Port am Sever verbinden kann

- **Fehlermeldung für das Autoupdate xStream und Resolver**

	Es kommt am Apple TV immer wieder zu dieser Fehlermeldung, wenn das xStream AutoUpdate und das Resolver Autoupdate aktiviert sind

	Wenn beide Autoupdates deaktiviert werden gibt es auch keine Fehlermeldung. Updates müssen dann selber heruntergeladen & installiert werden

	Das ist jedoch KEIN xStream Fehler, sondern das liegt am Apple TV (bzw. das benutzte Python)

	Die kommt mit den HTTPS links vom Updater nicht klar

	Lösen kann das Problem nur Apple, oder ggf.Kodi



- **Ich bin neu und kenne mich mit Kodi gar nicht aus**

Sollte das der Fall sein, dann bitte erst einmal mit den nötigsten und wichtigsten Kodi Grundlagen befassen und erst dann dieses Addon nutzen. Fragen zu Kodi Grundlagen beantworten wir nicht
Dazu gibt es im Kodinerds Forum einen tolles Thema: Hilfe für Neulinge

- **Wo kann ich die Support Informationen in xStream finden/abfragen**

xStream öffnen - Einstellungen - Support Informationen anzeigen

- **Mein Internet Anbieter blockiert viele Seiten (DNS Sperre), was kann ich da machen**

Es kommt immer auf das Endgerät an welches Ihr zur Wiedergabe verwendet

Auf jedem Gerät (z.B. FireTV, PC, NvidaShield usw.) kann direkt am Gerät eine alternative DNS Adresse eingetragen werden, z.B. die von Google (8.8.8.8 & 8.8.4.4)

Damit wird dann die DNS Sperre von Eurem Internetanbieter umgangen und Ihr könnt die Seiten wieder nutzten

Noch besser wäre es, die DNS Adresse direkt auf Eurem Router/Modem zu ändern, weil dann alle Geräte im Heimnetzwerk vollen Zugriff  haben und die DNS Sperre umgehen

Einfach bei Google Suchen (z.B. DNS Adresse bei FireTV ändern/eintragen) und der Anleitung dort folgen

Wir können das hier leider nicht für jedes Gerät beschreiben wie das geht

- **Mein Lieblingshoster (z.B. voe) funktioniert schon wieder nicht**
- 
Das liegt daran, dass die die Hoster oft Ihre Domain ändern, damit Nutzer von Addons wie xStream es schwerer haben deren Server zu verwenden




- **s.to funktioniert nicht in xStream**

Sollte das der Fall sein ,dann bitte die Webseite von s.to öffnen und prüfen ob Ihr überhaupt Zugriff auf die Seite habt

Diese Seite wird von sehr vielen Internetanbietern blockiert

Lösen könnt nur Ihr selbst das Problem. Ihr müss auf Eurem Router, FireTV oder PC die DNS Adresse ändern, z.B. auf die von Google oder Quad9

Wie das geht bitte selbst suchen über Google, ist nicht schwer und hat nix mit xStream zu tun

- **s.to funktioniert nicht in xStream, auf der Webseite aber schon**

Solltet Ihr die Webseite öffnen können und in xStream zeigt s.to keine Treffer oder es kommt eine Fehlermeldung, so habt Ihr falsche Benutzerdaten eingetragen




