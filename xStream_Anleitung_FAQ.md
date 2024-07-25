# xStream für Kodi - Anleitung/ FAQ

![xStream logo](https://raw.githubusercontent.com/streamxstream/plugin.video.xstream/matrix/icon.png)


- [1. Allgemeines zum Addon](#1-allgemeines-zum-addon)
    - [1.1 Verfügbare Webseiten](#11-verfügbare-webseiten)
    - [1.2 Rechtliche Konsequenzen bei Nutzung](#12-rechtliche-konsequenzen-bei-nutzung)
   
    
- [2. Installation und Konfiguration](#2-installation-und-konfiguration)
    - [2.1 Bezugsquellen zur Installation](#21-bezugsquellen-zur-installation)
    - [2.2 Einstellungen Allgemein und Einstellungen xStream](#22-einstellungen-allgemein-und-einstellungen-xstream)
    - [2.3 Indexseiten Aktivieren und Deaktivieren](#23-indexseiten-aktivieren-und-deaktivieren)
    - [2.4 Manuelle und automatische Hosterwahl](#24-manuelle-und-automatische-hosterwahl)
    - [2.5 TMDB](#25-tmdb)
    - [2.6 Autoplay Funktion](#26-autoplay-funktion)
    - [2.7 Zentralisierte Einstellungen](#27-zentralisierte-einstellungen)
    - [2.8 Downloads](#28-downloads)
    - [2.9 Ansichten](#29-ansichten)
    - [3.0 TheMovieDB Helper](#30-themoviedb-helper)
 
- [3. Bekannte Probleme](#3-bekannte-probleme)
    - [3.1 Fehler bei der Installation](#31-fehler-bei-der-installation)
    - [3.2 Fehler bei Verwendung der Globalen Suche](#32-fehler-bei-verwendung-der-globalen-suche)
    - [3.3 Fehler bei Verwendung einzelner Webseiten](#33-fehler-bei-verwendung-einzelner-webseiten)
    - [3.4 Resolver Fehler](#34-resolver-fehler)
    - [3.5 Fehlermeldungen im Betrieb](#35-fehlermeldungen-im-betrieb)
    - [3.6 Wiederkehrende Fragen](#36-wiederkehrende-fragen)
  
- [4. Fehlerbericht über Log-Datei](#4-fehlerbericht-über-log-datei)
    - [4.1 Allgemeines zur Log-Datei](#41-allgemeines-zur-log-datei)
    - [4.2 Speicherort der Log Datei](#42-speicherort-der-log-datei)
    - [4.3 Erstellen und Hochladen der Log-Datei](#43-erstellen-und-hochladen-der-log-datei)

    
- [5. Phyton Dateien](#5-phyton-dateien)
    - [5.1 Allgemeines zur .py-Datei](#51-allgemeines-zur-py-datei)
    - [5.2 Bearbeiten einer .py-Datei](#52-bearbeiten-einer-py-datei)
    - [5.3 Speicherort der einzelnen Webseiten (.py Dateien)](#53-speicherort-der-einzelnen-webseiten-py-dateien)



## 1. Allgemeines zum Addon

xStream ist ein Video Addon für die Media-Center-Software Kodi. Mit xStream ist es möglich über eine simple Benutzeroberfläche mehrere Streaming-Seiten zu benutzen, mit denen man Filme und Serien anschauen kann.

**Bei Hilfe bitte immer folgendes bekannt geben:**

**Kodi Version, Betriebssystem, xStream Version, Resolver Version, genaue Fehlerbeschreibung und eventuell Kodi Log!**

OHNE diese Informationen gibt es KEINE Antwort/Hilfe vom Team!!

Fragen welche hier in dieser FAQ mit ein wenig Lesezeit beantwortet werden können, werden im Gitter Chat nicht mehr beantwortet!!

### 1.1 Verfügbare Webseiten

Hier ist eine Übersicht der derzeitigen Seiten in xStream.

|  Site Plugin                       | Enthalten | Funktioniert | Login | Fehler Beschreibung   |
|------------------------------------|:---------:|:------------:|:-----:|:---------------------:|
| Anicloud                     	     | [x]       | [x]          | [x]   |        		|
| Cinemathek                 	     | [x]       | [x]          |       |        	 	|
| Dokus4me                     	     | [x]       | [x]          |       |        	 	|
| Filmpalast                         | [x]       | [x]          |       |        		|
| Flimmerstube                       | [x]       | [x]          | [x]   |        		|
| HD Filme                           | [x]       | [x]          |       |               	|
| KinoGer                     	     | [x]       | [x]          |       |			|
| Kinokiste                          | [x]       | [x]          |       |			|
| Kinox                     	     | [x]       | [x]          |       |         		|
| KKiste                     	     | [x]       | [x]          |       |                       |
| MegaKino                           | [x]       | [x]          |       |        		|
| Moflix-Stream                      | [x]       | [x]          |       |         		|
| Movie2k                            | [x]       | [x]          |       |           	        |
| Movie4k                            | [x]       | [x]          |       |           	        |
| Netzkino                           | [x]       | [x]          |       |        		|
| Serienstream                       | [x]       | [x]          | [x]   |        		|
| Streamcloud                        | [x]       | [x]          |       |        		|
| XCine                     	     | [x]       | [x]          |       |                	|

Empfehlungen und Vorschläge für neue Seiten können in unserem Chatroom oder als PullRequest eingereicht werden

Die Intergration der eingereichten Seiten ist nicht selbsverständlich und erfolgt nicht automatisch

Der Mehrwert der Seite wird geprüft und dann eine Entscheidung getroffen

### 1.2 Rechtliche Konsequenzen bei Nutzung

Der Europäische Gerichtshof hat ein Urteil gefällt: 
 
 - Der Nutzer muss sich in Anbetracht des neuen EuGH-Urteils stets über das zur Nutzung vorgesehene Angebot (Portal, Webseite) informieren – der Nutzer muss prüfen, ob das Angebot rechtswidrig ist oder sein könnte. 

 - Streamingseiten, die etwa brandaktuelle Kinofilme kostenlos anbieten, die man nicht mal bei den Bezahlanbietern zu sehen bekommt – hier hat man es wahrscheinlich mit einer „offensichtlich rechtswidrigen Vorlage“ zu tun. 
Wer sich hier Streams anschaut, macht sich strafbar und kann sich nicht auf das Recht auf Privatkopie berufen.

 - Zukünftige Streaming-Abmahnungen sind also durchaus möglich,eine neue Abmahnwelle ist dennoch nicht zu befürchten
Nutzer können nur über ihre IP-Adressen zurückverfolgt werden Genau diese IP-Adresse ist jedoch nur dem illegalen Portal bekannt, welches meist anonym operiert und oft keine IP-Adressen speichert

Die meisten Streaming-Seiten speichern keine Zugriffsdaten
Solltet Ihr einen Premium Dienst auf diversen Seiten nutzen, könnt Ihr natürlich leicht(er) gefunden werden

Hier ist ein Video von Rechtsanwalt Christian Solmecke, der über das Thema rechtlich aufklärt: Stand 26.April 2017

[![EuGH: Streaming| Rechtsanwalt Christian Solmecke](https://i.ytimg.com/vi/uzOA09gomn0/hqdefault.jpg)](https://www.youtube.com/watch?v=uzOA09gomn0&feature=youtu.be)

[Link](https://www.youtube.com/watch?v=uzOA09gomn0&feature=youtu.be)
## 2. Installation und Konfiguration


### 2.1 Bezugsquellen zur Installation

**"als Quelle hinzufügen" kann ebenso gemacht werden!!!!**

Dazu in Kodi Einstellungen (Zahnrad)- Dateimanager - Quelle hinzufügen

Hier den Link eintragen: https://streamxstream.github.io/xStreamRepoWeb/

Einen Namen vergeben und speichern

Dann kann unter Addons- aus .zip Installieren eben diese Quelle ausgewählt werden und daraus die Repo installiert werden

Das Plugin kann direkt herunterladen werden (wobei die Update-Funktionalität nicht gegeben ist), oder über die xStream Repository installiert werden (empfohlen)

***Im xStream Repository ist auch das Repository ResolveURL enthalten, welche noch zusätzlich selbst installiert werden muss!!***

Wenn die ResolveURL Repository installiert wird, aktualisiert sich auch der Resolver automatisch

Es wird übrigens der ResolveURL von Gujal00 verwendet

Das offizielle Resolver Update wird übrigens 2 mal angeboten (ResolveURL Repo und xStream Repo) und das ist so beabsichtigt

Der Grund: Bei xStream Neuinstallation würde sonst KEIN Resolver installiert werden, wenn er nicht ebenso in unserer Repo enthalten ist

Nach der Installation xStream öffnen und am unteren Ende auf *Einstellungen - Resolver Einstellungen*
Hier dann *Cache Funktion benutzen* deaktivieren (um Fehler zu vermeiden)

***WICHTIG:*** 

Beim Daten Download direkt von Github gilt es folgendes zu Beachten: 

Um eine Korrekte Installation zu Gewährleisten, ist es immer notwendig, den Anhang _Master bzw. Nightly_ aus den  .zip Dateien und dem Unterordner zu entfernen

Geht wie folgt: 
	
- zum Beispiel, die Datei in "plugin.video.xstream.zip" umbenennen (quasi das "-master" oder -"nightly" entfernen)

-  Datei öffnen (nicht entpacken) mit 7-Zip, WinRAR, WinZIP (oder einem anderen Packer)
	
- dort ist ein Ordner zu sehen der z.B. "plugin.video.xstream-master" heißt => auch hier das "-master" entfernen

Die Zip dann installieren

**xStream-Repository:**
- [xStream-Repo](https://streamxstream.github.io/xStreamRepoWeb/)

Das plugin alleine (wenn gewünscht), xStream Nightly, bekommt Ihr direkt von Github:

- [xStream Nightly](https://github.com/streamxstream/plugin.video.xstream)


*Die Nightly Version gilt als Experimentell, jedoch ist sie viel aktueller und neue Seiten sind hier zuerst enthalten*

*Fehler können daher vorhanden sein*

***WICHTIG / Achtung:*** 

An dieser Stelle wird klar darauf hingewiesen, dass bei alternativen Bezugsquelle (das bedeutet wenn, es nicht unser Repository ist) nicht für den aktuellsten Stand und Funktion der Software garantiert werden kann!!!

 **Repo Installieren:**

- öffne die Kategorie Addons
- Addon Browser (Schachtel links oben)
- aus zip installieren
- Download Ordner suchen und installieren

*- Nachdem das xStream Repository Installiert wurde ist noch folgendes zu machen:*

- öffnet die Kategorie Addons
- Addon Browser (Schachtel links oben)
- Aus Repository installieren
- xStream Repository
- *Video-Addons*
- xStream (installieren/aktivieren)

Dann einen Schritt zurück zu:
- *Addon Repository*
- hier prüfen, dass xStream Repository aktiviert ist und 
- ResolveURL Repo anklicken und installieren (dann wird der Resolver automatisch aktualisiert)

  
### 2.2 Einstellungen Allgemein und Einstellungen xStream

Zu den xStream Einstellungen gelangt man am einfachsten, wenn man xStream startet und am unteren Ende Einstellungen wählt

**Hier befinden sich nun verschiedene Auswahlmöglichkeiten:**

*Support Informationen anzeigen*
Nach Auswahl werden System Informationen angezeigt, welche für die Hilfe im Chat benötigt werden

*Resolver Einstellungen*
Hier werden Einstellungen zum Resolver vorgenommen

*Manuelle Aktualisierung starten* (Aktualisierung erzwingen)
Hiermit kann eine Update vom Resolver oder von xStream *erzwungen* werden
Informationsfenster führen durch den Update Prozess
Bitte aufmerksam lesen und die Anweisungen befolgen

**xStream Einstellungen**

*ALLGEMEIN*

**Darstellung**

*Globale Suche an erster Position*

Wenn deaktiviert befindet sich die Globale Suche am unteren Ende der Seiten Anzeige
und nicht ganz oben

*Zentralisierte Einstellungen anzeigen*
Wenn deaktiviert, verschwindet der Menüpunkt *Einstellungen* und die darin enthaltenen Funktionen, werden am Ende der Seiten Anzeige aufgelistet

**Inhalt**

*Bevorzugte Sprache*

Hier kann unter den Optionen *Deutsch*, *Englisch*, *Japanisch* und *Alle* gewählt werden, wobei *Alle* jede Sprachen einbezieht 

Zu berücksichtigen ist jedoch, dass die einzelnen Site-Plugins diese Option unterstützen müssen 

*ACHTUNG:*

Wird die ausgewählt Option/Sprache nicht unterstützt, werden auch Inhalte anderer Sprachen nicht angezeigt!!

Alles andere am besten so lassen wie es eingestellt ist

Wenn gesehene Filme auf einmal weg sind, liegt das an den Einstellungen im Seitenmenü

Hier die Markierung *gesehene Filme* deaktivieren!

*AKTUALISIERUNGEN*

Update Funktion für xStream und Resolver
 
Diese Funktion installiert automatisch Änderungen an Seiten, am Resolver usw., welche auf der Entwicklerplattform (Github) durchgeführt werden

Das Updatet nimmt die ausgewählte Version (nightly oder release)

Dadurch werden Fehler/Bugs/Error, schnell & einfach behoben

Als Standard ist aktiviert eingestellt, es kann natürlich auch deaktiviert werden wenn nicht erwünscht

Dieses Auto-Update wird nur ausgeführt mit dem Kodi Start und wird auch durch eine Meldung angezeigt

Diese xStream Auto-Update Funktion arbeitet Unabhängig von den KODI Einstellungen

Wenn in Kodi unter: 

Optionen-Einstellungen-Addons-Seitenmenü, Automatische Aktualisierung auf AUS gestellt ist, wird xStream trotzdem aktualisiert

Für xStream besteht die Möglichkeit schnell an die neusten Updates zu kommen um nicht auf ein Release warten zu müssen

Release ist direkt vom xStream Github und Nightly mit Hotfixes vom xStream Team

Für den Resolver besteht auch die Möglichkeit schnell an die neusten Updates zu kommen um nicht auf ein Release warten zu müssen

Als Standard ist aktiviert eingestellt

Es stehen 2 Update Möglichkeiten zur Verfügung: Release und Nightly

Release ist direkt vom Gujal00 Github und Nightly mit Anpassungen vom Team
Das Gujal00 Release immer aktuell!

*Grundsätzlich sollte/soll jeder das Gujall00 Release einstellen* und nur bei Problemen z.b. mit voe, unsere Nightly ausführen

Im Resolver Nightly sind nur "Notfixes" enthalten, bis diese auch bei Gujall hinzugefügt werden 

Das Release im Resolver Nightly ist NICHT das Release im Repo sondern neuer,weil es direkt vom Github geladen wird sobald es dort etwas neues gibt

Es kann auch deaktiviert werden, wenn nicht erwünscht

Beachtet an dieser Stelle, dass *Nighly's* auch Fehler enthalten können

**Benachrichtigungen (ab xStream 4.0)**
*Vollständig*
Bei Vollständig ist der Text, beim xStream Start immer zu sehen und zeigt die Änderungen an

*Einfach*
Bei Einfach wird der Text nur dann angezeigt, wenn auch wirklich ein Update installiert wird und zeigt die neusten Änderungen an

Die Benachrichtigungs Funktion kann auch deaktiviert werden: Änderungsprotokoll nach Aktualisierung anzeigen

Unter Bevorzugte Sprache, kann die gewünschte Sprache für die Seiten ausgewählt werden 

### 2.3 Indexseite Aktivieren und Deaktivieren

*Standard:* Alle Site-Plugins aktiviert

In den Einstellungen, unter dem Menüpunkt *Index Seiten 1+2*, besteht die Möglichkeit bestimmte Seiten an bzw. auszuschalten

Dies kann von Nutzen sein, wenn kein Interesse an bestimmten Medien besteht

Diese werden dann auch nicht in der globalen Suche angezeigt

Zusätzlich kann man auswählen, ob bzw. welche Seiten bei Durchführung der Globalen Suche, durchsucht werden sollen.

Hier **muß** mindesten eine Seite ausgewählt werden, sonst kann das Fenster nicht geschlossen werden!!

Nache einem xStream Update werden auch neu hinzugefügte Seiten automatisch angezeigt

*Anmerkung*

Wenn Ihr Probleme mit s.to, kinox usw. habt, hilft es wenn Ihr Eure DNS Adresse (z.B. auf die von Google 8.8.8.8 und 8.8.4.4) ändert

Manche Seiten werden von den Internet Providern geblockt

Einge Seiten wie z.B. Flimmerstube, s.to usw. benötigen ein EIGENES Benutzerkonto auf der Seite, um diese Verwenden zu können

Ausserdem kann bei eingen Seiten (z.B.s.to) die Webseiten Domain in den xStream Einstellungen geändert werden, sollte es Probleme geben

Bei kinox.to erfolgt die Auswahl einer funktionsfähigen Webseite selbständig

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

Die Deaktivierung dieser Funktion kann auf leistungsschwachen System (z.B. RPi) einen spürbar schnelleren Ablauf bewirken

Es wird die Deaktivierung Empfohlen, da es nicht wirklich notwendig ist (und manchmal für Fehler verantwortlich ist)

***Anmerkung zu Hostern mit PAIRING (sollte es solche noch geben):***

Wenn Ihr einen dieser Hoster zum Streamen auswählt, erscheint ein Fenster, welches Euch auffordert Eure Gerät zu Pairen

Das könnt ihr mit ruhigen Gewissen machen

Ihr müsst im selben WLAN sein wie das zu Pairende Gerät (z.B. FireTV, Apple TV usw.)

Der Link zum Pairen ist fast immer die Webseite und hinten dran /pair

Eventuell muss man ein Benutzerkonto erstellen und einloggen, dann wenn nötig die Bilderaufgabe lösen und klick auf “Pair”

Das wars

Dieser Vorgang muss immer wieder Wiederholt werden (nach 3-4 Stunden oder 5 Streams)

*Warum ist das "pairen" nötig?*

Auf der Homepage muss immer eine Werbung betrachet werden

Da wir ja die Homepage des Hostbetreibers nicht besuchen müssen, entgehen dem Betreiber Werbeeinnahmen

Damit dies nicht der Fall ist und die Hoster xStream so arbeiten lassen, wurde mit den Betreibern diese "Pair" Funktion vereinbart

Durch den klick auf "Pair" bekommen die Hoster Ihre Werbeeinnahme

Für Euch entstehen dadurch KEINE Kosten!!

### 2.5 TMDB

Bei Aktivierung wird das externe Modul TMDB genutzt um ausführliche Informationen in Form von Metadaten, wie Fanarts, Covers oder Episodenbilder, zu den Streams bereitzustellen

**TMDB ersetzt Informationen der Webseiten**

Bei Aktivierung werden Metainformationen von  "TMDB" bevorzugt, d.h. Metainformationen die von einem Site-Plugin geliefert wurden, werden nicht nur ergänzt sondern auch ersetzt

### 2.6 Autoplay Funktion

Einstellungen dazu sind in der Kategorie *ALLGEMEIN* zu finden

Hosterauswahl muss hierzu auf *Automatisch abspielen* stehen

Ist diese Option aktiviert, wird keine Hosterliste angezeigt

xStream probiert automatisch alle verfügbaren Hoster aus, bis ein Stream abgespielt werden kann

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität

Diese kann unter "Resolver Einstellungen" beim jeweiligen Hoster angepasst werden

*Niedrige Werte werden vor hohen Werten gewählt*

Sind Eure Priorisierten (Lieblings) Hoster nicht dabei (weil sie nicht verfügbar sind), nimmt xStream den nächsten Hoster der funktioniert

*Bevorzugte Qualität bei Auto-Play: *

Hier kann die Qualität der Streams eingestellt werden, Standard: Beste Auflösung

Ist Beste Auflösung eingestellt, wir immer der beste verfügbare Stream gewählt

### 2.7 Zentralisierte Einstellungen

Zu finden in der Kategorie Allgemein

Wenn AUS: dann verschwindet der Menüpunkt _Einstellungen_ und die darin enthaltenen Funktionen, werden am Ende der Seiten Anzeige aufgelistet

Wenn EIN: wird nur Globale Suche & Einstellungen angezeigt

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

### 2.9 Ansichten

![Ansichten](https://raw.githubusercontent.com/streamxstream/xStream-FAQ/master/autoansichten.jpg)

Um die Ansichten in xStream fix/fest einzustellen, werden die View-Codes des jeweiligen Skins benötigt

Diese sind bei jedem Skin anders!!

**Hier die Liste für das Kodi Standard Skin Estuary:**

List 50

Poster 51

IconWall 52

Shift	53

InfoWall 54

WideList 55

Wall	500

Banner	501

FanArt	502

User mit etwas Kodi Erfahrung können die Liste selbst herausfinden, diese befinden sich im Kodi Pfad und dort im Skin Ordner:

Beispiel:

....kodi/addons/skin.estuary/xml/*MyVideoNav*

Diese Datei mit z.B. Note++ öffnen und schon sieht man die Listen Codes, zum Beispiel diesen vom Standard Skin: View_50_List, View_51_Poster, usw.

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

Fragen welche hier in dieser FAQ mit ein wenig Lesezeit beantwortet werden können, werden im xStream Chatroom nicht mehr beantwortet!!

Bitte, schauen, ob der Fehler in einem früheren Post schon beantwortet wurde!

Es kann auch eine fehlerhafte Datei vorliegen, oder die .zip ist falsch aufbereitet

Hilfe bei Probleme bekommt Ihr im Element Chatroom

### 3.2 Fehler bei Verwendung der Globalen Suche

Falls bei der Globalen Suche eine Fehlermeldung bekommen, dass eine Seite nicht erreichbar war bzw. die Suche durch eine Meldung unterbrochen wurde, liegt dies meist an der Seite

Meistens ist eine Seite in diesem Moment nicht erreichbar, einfach abwarten und die betroffene Seite deaktivieren

Es kann auch vorkommen, dass bei der Globalen Suche keine Treffer angezeigt werden, dann bitte in der gewünschten Seite die Suche nutzen (manchmal stören die Seiten, die Globale Suche)

Um schnelle Abhilfe zu leisten lohnt es sich in diesem Fall durchaus die Entwicklergemeinde darauf aufmerksam zu machen

### 3.3 Fehler bei Verwendung einzelner Webseiten

Das kann verschiedene Ursachen haben. Meistens liegt es jedoch an der eigentlichen Webseite

Denn wenn dort auch nur eine Kleinigkeit geändert wird, kann es schon sein, dass  das Site-Plugin nicht mehr geht

Die Entwickler wissen es meistens und sind um eine Lösung bemüht

Es kann aber NICHT immer *sofort* eine Seitenproblem behoben werden

Das Nightly Update wird, wenn die Funktion in xStream aktiviert wurde, automatisch installiert 

Die Seite im Browser aufrufen und auf Funktion überprüfen

Im Anschluss das Problem schildern

Bitte Sachlich bleiben und nicht jammern!

***Für die Streaming-Seite s.to können in den Einstellungen alternative Domains bestimmt werden. Nutzt diese, falls die Seite nicht erreichbar ist! Kinox sucht automatisch nach einer funktionsfähigen Webseite***

### 3.4 Resolver Fehler

**Fehlermeldung: Sie haben keinen funktionierenden Resolver installiert....**

Hierfür gibt es 2 Möglichkieten: 

Entweder Ihr habt *vergessen die ResolveURL Repo zu installieren* wie am Anfang der Anleitung beschrieben oder es gab ein *Problem beim Update*

*- Nachdem das xStream Repository Installiert wurde ist noch folgendes zu machen:*

- öffnet die Kategorie Addons
- Addon Browser (Schachtel links oben)
- Aus Repository installieren
- xStream Repository
- *Video-Addons*
- xStream (installieren/aktivieren)

Dann einen Schritt zurück zu:
- *Addon Repository*
- hier prüfen, dass xStream Repository aktiviert ist und 
- ResolveURL Repo anklicken und installieren (dann wird der Resolver automatisch aktualisiert)

*Update Fehler*

Das Problem lässt sich jedoch einfach lösen

In xStream Einstellungen - Manuelle Aktualisierung starten

Sollte das alleine nicht genügen, dann noch folgendes durchführen:

In Kodi: Einstellungen - Dateimanager - Profilverzeichnis - addon_data - script.module.resolveurl - update_sha 

Kontextmenü öffnen und Löschen, die Löschmeldung mit JA bestätigen

*Kodi Profis können die obige Datei auch im Explorer löschen:*

Kodi beenden, dann in einem Dateimanager zu folgendem Ordner navigieren (versteckte Ordner vorher sichtbar machen): *....\userdata\addon_data\script.module.resolveurl*

Hier die Datei *update_sha* löschen und Kodi neu starten

**Premium Anbieter funktionieren nicht, normale Streams laufen, bzw. Ladekreis kurz sichtbar aber kein Stream**

Es kommt oft vor, dass Streams von Premium Anbietern (z.B. Premiumize, RealDebrid, AllDebrid, MegaDebrid usw.) nicht laufen oder der Ladekreis ist kurz sichtbar aber kein Stream wird abgespielt

Normale Streams laufen hingegen ohne Probleme

Eine mögliche Lösung (die schon Erfolge gezeigt hat) ist folgende:

Im Reslover die *Cache Funktion benutzen* auf AUS schalten

Erreichbar direkt über xStream:

xStream öffnen - Einstellungen - Resolver Einstellungen

Eventuell noch *Cache Funktion zurücksetzen* klicken

**Ein Hoster (z.B. vivo.sx) geht bei allen nur bei Euch nicht**

Das kann an einer falschen Installation des Resolver liegen 

(z.B. das "-master" oder "-nightly" wurde nicht entfernt bei Downloads von GitHub vor der Installation oder Resolver ist 2 mal vorhanden usw.)

*Wenn dieser Fehler auftreten sollte, kann folgendes helfen:*

Alle Ordner, die zum Resolver gehören, löschen. 

Und zwar einmal im

 ..kodi/addons-Ordner, script.module.resolveurl löschen 
 
 und zum anderen im
 
 ...kodi/userdata/addon_data-Ordner, script.module.resolveurl löschen

Dann installierst du den aktuellsten Resolver aus der [.zip von  Github](https://github.com/streamxstream/xStreamRepo/tree/master/matrix/script.module.resolveurl) oder führst das Manuelle Update durch

### 3.5 Fehlermeldungen im Betrieb

- **ModuleNotFoundError: No Module named "serienstream_to"**

Wird diese oder ähnliche Meldungen angezeigt, so bedeutet dies, dass es Änderungen im jeweiligen Seiten Modul (z.B. Serienstream) gab. Diese Meldung erscheint eigentlich nur, wenn Favoriten/SuperFavoriten oder Widget angelegt wurden/verwendet werden

Um diese Meldung wieder los zu werden, müssen die Favoriten oder Widget neu angelegt werden

- **Bei direkter Suche in Serienstream kommt Meldung Error 500**

In den Einstellungen ist bei Serienstream, bei *Domain auswählen* auf Proxy gestellt

Als DNS Adresse wird auf dem betroffenem System, die DNS von Cloudflare (1.1.1.1) verwendet

Es ist offensichtlich so, dass es bei dieser Kombination zu Proxy Probleme mit der Cloudflare DNS kommt

Abhilfe schafft hier entweder eine andere DNS Adresse (z.B. Google 8.8.8.8 und 8.8.4.4.) zu verwenden oder von Proxy auf s.to umstellen

- **http Timeout Fehlermeldung bzw. the read operation timeout**

Kann an den Webseiten liegen wenn sie lange brauchen zum aufbauen oder sie ist Offline

Das Problem ist eher temporär, später nocheinmal probieren

Ebenso werden bei s.to Benutzer ausgesperrt, die einen VPN benützen bei der Verwendung mit Kodi

- **Bei Flimmerstube ist alles leer, es wird kein Inhalt angezeigt**

Es wird ein  Benutzerkonto benötigt, damit ihr die Seite nutzen könnt. Dazu müsst ihr euch auf der Seite http://flimmerstube.com registrieren 

Dafür reicht eine Fakeemail z.B. mail1a.de

Die Daten müssen dann in den xStream Einstellungen Eingetragen werden

Es ist auch dann alles leer, wenn die Registrierung auf der Website nicht korrekt abgeschlossen wurde!

Die Registrierung muss über einen Link endgültig bestätigt werden. Erst dann die Login-Daten in xStream eintragen

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

- **Fehlermeldung beim öffnen eines Site-Plugins**

	- Errno4 non-recoverable failure in the name Resolution.Fehler
	
	Weist auf ein Problem bei der Namesauflösung der Domains hin. 
		
	Könnte z.B. an der eingestellten DNS liegen (oder VPN) oder aber auch an den netzwerkbezogenen Einstellungen von Kodi

	- Lösung: Database im Profilordner von xStream löschen, wie folgt:
	
	Einstellungen-System-Dateimanager-Profilverzeichnis-addon_data-plugin.video.xstream-pluginDB wählen und löschen
		
- **Anzeige: Es ist mehr als ein Resolver installiert. Bitte löschen**

	Das Problem entsteht durch andere Repos oder durch manuelle Installation (wenn man beim Installieren in der .zip nicht das "-master" oder "-nightly" entfernt)
	
	Dadurch wird dann ein zweiter Resolver angelegt und das führt dann zum Problem.

	- Lösung:  geht im Kodi Ordner zu .../kodi/addons/
	
	Dort werdet ihr dann Ordner finden, die wie folgt heißen:

	- script.module.resolveurl
	- script.module.resolveurl-master

	Einfach den Ordner mit "-master" am Ende löschen und die Fehlermeldung ist weg. Und auch das AutoUpdate im xStream funktioniert wieder.
	
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

### 3.6 Wiederkehrende Fragen

- **Wie kann ich mich für den xStream Chatroom anmelden**

Zuerst muss auf Github.com ein Benutzer Konto erstellt werden

Passwörter und E-Mail Adresse sind dann immer auf Github.com zu ändern

Die Software *Element*, wird benötigt um einfachen Zugang zu erhalten, Download hier möglich: [Download](https://element.io/download)

Neue User wählen bei Heim-Server *matrix.org*

Jene User, die schon zuvor bei dem alten gitter.im Chatroom drinnen waren, können bei Heim-Server, *gitter.im* eintragen/verwenden oder *matrix.org*
Jedoch sollte man dann immer den gewählten Server auf ALLEN Geräten verwenden

Beim Anmelden im Browser, für den Chatroom, folgende Seite öffnen: [Chat Room](https://app.gitter.im/#/room/#streamxstream_community:gitter.im)

Den Heim-Server *matrix.org* wählen und dann auf den blauen *Continue* Knopf drücken

Bei der Einrichtung alle Schritte erledigen und den Sicherheitsschlüssel bzw. die Sicherheits Phrase unbedingt lokal irgendwo abspeichern

Diese werden bei einem erneuten Login abgefragt

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

Das Team xStream hat darauf keinen Einfluss

Jedoch sobald das Team davon weiß (weil es uns z.B. im Chat mitgeteilt wird), kommt ein Hotfix über das Resolver Nightly Update

- **Wo trage ich meine Benutzerdaten  in xStream ein (z.B. für s.to)**

Wie schon weiter oben beschrieben, muss dazu das Einstellungsmenü von xStream geöffnet werden, zum Menü Punkt Konten Scrollen und dort bei Serienstream die Zugangsdaten eintragen

**Ein Serienstream Zugang muss von jedem Benutzer, auf deren Webseite, selbst erstellt werden!!**

- **s.to funktioniert nicht in xStream**

Sollte das der Fall sein ,dann bitte die Webseite von s.to öffnen und prüfen ob Ihr überhaupt Zugriff auf die Seite habt

Diese Seite wird von sehr vielen Internetanbietern blockiert

Lösen könnt nur Ihr selbst das Problem. Ihr müss auf Eurem Router, FireTV oder PC die DNS Adresse ändern, z.B. auf die von Google oder Quad9

Wie das geht bitte selbst suchen über Google, ist nicht schwer und hat nix mit xStream zu tun

- **s.to funktioniert nicht in xStream, auf der Webseite aber schon**

Solltet Ihr die Webseite öffnen können und in xStream zeigt s.to keine Treffer oder es kommt eine Fehlermeldung, so habt Ihr falsche Benutzerdaten eingetragen

- **Wo sehe ich welche xStream Version installiert ist**

Zu finden unter: Addons - Video Addons, da steht dann rechts,  xStream-Team und die Versionsnummer

- **Wo sehe ich welche xStream Repository Version installiert ist**

Zu finden unter: Addons - Addon Browser (links oben die Schachtel) - aus Repo installieren, da steht dann rechts xStream-Team und die Versionsnummer

- **Wo sehe ich ob die Resolver Repository installiert ist**

Zu finden unter: Addons - Addon Browser (links oben die Schachtel) - aus Repo installieren, da steht dann rechts gujal und die Versionsnummer

 **Wo sehe ich die aktuelle Resolver Version**

Zu finden unter: Einstellungen (Zahnrad) - System - Addons - Abhängigkeiten verwalten - ResolveURL suchen und da steht dann gujal und die Versionsnummer

 **Warum habe ich eine Kodi Version 3.5.x und andere eine Kodi Version 4.0.x**

Das Team stellt derzeit für Kodi 19 und für Kodi 20 xStream Versionen bereit

BEIDE Versionen haben die gleichen Seiten, jedoch wird die Version 3.5.x (Kodi 19), nach dem Finalen Erscheinen von Kodi 20 nur noch Not-Updates bekommen

 **xStream wird als Virus angezeigt**

Wenn die xStream Repository von unserem Github herunter geladen wurde, so handelt es sich zu 100% NICHT um einen Virus

Alternativ, kann in Kodi auch unsere Webseite als direkt Download und zum Installieren von xStream verwendet werden

Virenscanner deaktivieren für den Zeitraum der xStream Installation

 **Ich nutz xStream nicht aus Eurer xStreamRepo bzw. von einer anderen Webseite usw.**

Sollte das so sein können wir nicht für den aktuellen Stand garantieren und bei Problemen helfen

Deinstalliere alles von xStream (Addon+Repo) und installiere unsere Version, so wie es oben beschrieben wird

## 4. Fehlerbericht über Log-Datei

### 4.1. Allgemeines zur Log-Datei

In dem log File werden alle Aktivitäten/Programmabläufe von Kodi protokolliert und gespeichert. Wenn man nun Probleme mit Kodi hat, ist es sehr hilfreich, dieses Log File im Forum zu Posten. Nur so kann eine schnelle und Zielgerichtete Lösung erfolgen.

### 4.2 Speicherort der Log Datei

Den Speicherpfad von Kodi anzeigen lassen – Scroll weiter runter zum Punk Debug_Loggin und folgen den Beschreibungen.

Das ist immer vom Betriebssystem abhängig

Im Folgenden werden bekannte Ordnerstrukturen der jeweiligen Betriebssysteme aufgelistet. Anstelle von "xbmc" kann in den Ordnern auch "kodi" stehen
(die Ordnerstruktur kann jedoch auch leicht von dieser Anleitung abweichen):

- Windows XP
    - `Documents and Settings\<your_user_name>\Application Data\Kodi`
    
- Vista/Windows 7
    - `C:\Users\<your_user_name>/%APPDATA%/Roaming/Kodi/Kodi.log`
    
- Mac OS X
    - `/Users/<username>/Library/Logs/ oder`
    - `/Users/<your_user_name>/Library/Application Support/Kodi/userdata`
    
- iOS
    - `/private/var/mobile/Library/Preferences`
    
- Linux, OpenElec, Raspberry Pi 1-3
    - `$HOME/.kodi/temp/`
    - `$HOME/.kodi/userdata/temp/xbmc.log`
    - `$HOME/.kodi/userdata`
    
- Android
    - `/android/data/org.xbmc.Kodi/files/.kodi/temp`
    - `data/data/org.xbmc.Kodi/cache/temp`

Die Ordner sind meist versteckt und müssen sichtbar gemacht werden, im Windows Explorer oder auf Android mit dem ESDateiexplorer.

Das Log File kann am besten mit Notepad++  unter Windows oder gedit unter Linux betrachtet werden

Auch der normale Texteditor unter Windows geht, Notepad ist aber übersichtlicher

Auf Android einen Texteditor verwenden zum Betrachten

Übrigens die Kodi „log.old“ ist die Logdatei vom letzten Neustart/Crash. Also wenn man keine mehr erstellen kann, dann diese nehmen.

### 4.3. Erstellen und Hochladen der Log-Datei

Kodi hat Standardmäßig die beiden wichtigen Log Addons integriert (eines zum Lesen der Log, das andere zum Hochladen). Damit ist das Erstellen der Log Datei und Posten im Forum sehr viel einfacher.

In Kodi gehe zu:

- Desktop-Optionen
- Einstellungen
- Addons
- Suche

In die Zeile "log" ein und Klicks auf Fertig.

Folgende Addons auswählen und installieren diese:

Log Viewer für Kodi (nur zum Lesen der Log-Datei)

Kodi Log Uploader (zum Auslesen & Uploaden der Log-Datei)

Mit dem LogViewer kann man die Log Datei ansehen, mit dem LogUploaded das Log-File auf die angezeigte Adresse hochladen.

Bei der Installation eine E-Mail Adresse angeben. An diese wird dir dann nach dem LogUpload ein Link zur Log Datei geschickt

Diesen Link im Forum Posten oder alles in einen Texteditor koperien, Die Datei speicherun und im Forum hochladen.

Debug-Logging (Kodi GUI):

Manchmal ist es gut das Debug Logging in Kodi zu aktivieren um noch mehr Informationen zu erhalten.

Folgendes Ausführen:

 Desktop-Optionen
 
- Einstellungen
- System
- Debugging
- "Debug-Logging aktivieren" anklicken

Fertig

Es wird nun am oberen Rand eine Statuszeile eingeblendet mit Infos; **Hier ist auch der Speicherort der Log-Datei zu sehen!**

Starte Kodi neu und öffne das Addon welches einen Fehler verursacht. Erstellen dann sofort eine Log-Datei (dann ist der Fehler leichter herauszulesen)

Das Debug-Logging kann im Anschluss wieder deaktiviert werden

Unter dem Punkt  Komponentenspezifische Protokollierung kann man bei der Kategorie "Konfiguration der Komponentenspezifischen Protokollierung" noch Einstellen was alles im Debug-Log Protokolliert werden soll

## 5. Phyton Dateien

### 5.1. Allgemeines zur .py-Datei

Eine .py Datei ist eigentlich eine Textdatei. Die Endung .py verweist auf die Programmiersprache Python, welche in Kodi zur Anwendung kommt.Diese .py Dateien werden in sämtlichen/den meisten Addons verwendet.
 
### 5.2 Bearbeiten einer .py-Datei

Manchmal werdet Ihr lesen z.B. Wechsel die .py Datei in dem Ordner „xyz“, oder ändere den Eintrag in Zeile 134.Öffnen könnt Ihr die Datei mit vielen Programmen z.B. Notepad++ (Freeware) oder Texteditor. In Notepad werden Euch die Zeilen-Nummern angezeigt und ist somit übersichtlicher, aber es geht auch mit dem EditorMit Notepad++ könnt Ihr die .py Datei sofort öffnen und wieder speichern.

Bei Verwendung des Text-Editors müsst Ihr die Endung vorher von .py auf .txt ändern. Dann könnt Ihr die Datei öffnen und Änderungen vornehmen. Im Anschluss bitte „Speichern unter“ wählen und bei „Dateityp“ alle wählen, und wieder als .py Datei speichern

### 5.3 Speicherort der einzelnen Webseiten (.py Dateien)

In den folgenden Ordnern findet Ihr alle Addons von Kodi. Das Addon xStream wird in aller Regel unter plugin.video.xstream istalliert.

- Android 
	- `/Android/data/org.xbmc.kodi/files/.kodi/addons/`
	- `/sdcard/Android/data/org.xbmc.kodi/files/.kodi/addons/`  (.kodi ist ein versteckter Ordner)
	
- iOS
	- `/private/var/mobile/Library/Preferences/Kodi/addons/`
	
- Linux 
	- `~/.kodi/addons/`
	
- Mac 
	- `/Users/<your_user_name>/Library/Application Support/Kodi/addons/`
	
- OpenELEC 
	- `/storage/.kodi/addons/`
	
- Windows
	- `C:\Users\BENUTZERNAME\AppData\Roaming\Kodi\addons`    (AppData ist ein versteckter Ordner)
	

Das Addon xStream wird in aller Regel unter plugin.video.xstream istalliert

Im Verzeichnis `sites/` sind die .py Daten und im Ordner `resources/art/sites/` die jeweiligen Artworks bzw. Site-Icons der einzelnen Webseiten abgelegt.

