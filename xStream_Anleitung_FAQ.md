# xStream für Kodi - Anleitung/ FAQ

![xStream logo](https://raw.githubusercontent.com/streamxstream/xStream-FAQ/master/Logo%20FAQ.png)


- [1. Allgemeines zum Addon](#1-allgemeines-zum-addon)
    - [1.1 Verfügbare Webseiten](#11-verfügbare-webseiten)
    - [1.2 Rechtliche Konsequenzen bei Nutzung](#12-rechtliche-konsequenzen-bei-nutzung)
   
   
- [2. Installation und Konfiguration](#2-installation-und-konfiguration)
    - [2.1 Bezugsquellen zur Installation](#21-bezugsquellen-zur-installation)
    - [2.2 Allgemeine Einstellungen](#22-allgemeine-einstellungen)
    - [2.3 Webseiten Aktivieren und Deaktivieren](#23-webseiten-aktivieren-und-deaktivieren)
    - [2.4 Manuelle und automatische Hosterwahl](#24-manuelle-und-automatische-hosterwahl)
 - [2.5 Metahandler benutzen](#25-metahandler-benutzen)
 - [2.6 Autoplay Funktion](#26-autoplay-funktion)
 - [2.7 Zentralisierte Einstellungen](#27-zentralisierte-einstellungen)
 - [2.8 Gemeinsamer gesehen Status in xStream und Lastship](#28-gemeinsamer-gesehen-status-in-xstream-und-lastship)
 
- [3. Bekannte Probleme](#3-bekannte-probleme)
    - [3.1 Fehler bei der Installation](#31-fehler-bei-der-installation)
    - [3.2 Fehler bei Verwendung der Globalen Suche](#32-fehler-bei-verwendung-der-globalen-suche)
    - [3.3 Fehler bei Verwendung einzelner Webseiten](#33-fehler-bei-verwendung-einzelner-webseiten)
    - [3.4 URL Resolver Fehler](#34-url-resolver-fehler)
   - [3.5 Fehlermeldungen im Betrieb](#35-fehlermeldungen-im-betrieb)
  
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


### 1.1 Verfügbare Webseiten

| Name           | Domain            | Hinzugefügt     |
|:-------------- |:----------------- |:--------- |
|Alleserien  	 |alleserien.com     |07.09.2018 |
|Animes-Stream24 |as.animes-stream24.tv |01.09.2017|
|Cinenator	 |cinenator.to	     |10.11.2018 |
|DirectDownLoad  |ddl.me             |09.04.2016 |
|Dokustream      |dokustream.org     |25.04.2017 |
|FilmPalast      |filmpalast.to      |09.04.2016 |
|Filmmerstube    |filmmerstube.com   |21.08.2016 |
|HD-Streams      |hdstreams.org      |30.12.2017 |
|HD-Streams      |hdstreams.to	     |08.09.2019 |
|HDfilme         |hdfilme.tv         |09.04.2016 |
|Kindertube  	 |kindertube.de      |13.03.2017 |
|Kino		 |kino.cx	     |26.08.2018 |
|Kinoger         |kinoger.com	     |21.02.2018 | 
|KinoX           |kinox.to           |09.04.2016 |
|KKiste  	 |kkiste.co  	     |04.10.2019 |
|Movie4k         |movie4k.to         |09.04.2016 |
|Moviedream      |moviedream.ws      |10.12.2018 |
|Moviestream	 |movie-stream.eu    |10.11.2018 |
|Movietown       |movietown.org	     |05.12.2019 |
|Netzkino	 |netzkino.de  	     |30.04.2017 |
|SerienStream 	 |serienstream.to    |26.10.2016 |
|StreamIt        |streamit.ws        |19.09.2016 |   
|Streamking	 |streamking.eu	     |13.01.2019 |
|Topstreamfilm	 |topstreamfilm.com  |03.05.2019 |

Empfehlungen und Vorschläge für neue Seiten können über das Forum eingereicht werden. Die Intergration der eingereichten Seiten ist nicht selbsverständlich und folgt daraufhin nicht automatisch. Sowohl das Potenzial der vorgeschlagenen Seite als auch der erforderliche Mehrwert wird geprüft und entscheidet über die Entwicklung eines neuen Site-Plugins.


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
**Das hinzufügen von xStream über "als Quelle hinzufügen" ist NICHT möglich!!!!**

Das Plugin kann direkt herunterladen werden (wobei die Update-Funktionalität nicht gegeben ist), oder über die xStream Repository installiert werden (empfohlen). 

Im xStream Repository ist auch der URLResolver enthalten

Wenn das installiert wird, aktualisiert sich auch der URL Resolver automatisch

Es wird übrigens der URL Resolver von Jsergio verwendet

***WICHTIG:*** 

Beim gesamten Daten Download von Github gilt es folgendes zu Beachten: 
Um eine Korrekte Installation zu Gewährleisten, ist es immer notwendig, den Anhang _Master, Beta, Nightly_ aus den  .zip Dateien und dem Unterordner zu entfernen

Geht wie folgt: 
	
- zum Beispiel, die Datei in "plugin.video.xstream.zip" umbenennen (quasi das "-master", -"beta" oder -"nightly" entfernen)

-  Datei öffnen (nicht entpacken) mit 7-Zip, WinRAR, WinZIP (oder einem anderen Packer)
	
- dort ist ein Ordner zu sehen der z.B. "plugin.video.xstream-master" heißt => auch hier das "-master" entfernen

Die Zip dann installieren.

xStream-Repository: 
(Bitte dieses nehmen)

- [xStream-Repo](https://github.com/streamxstream/xStreamRepo/blob/master/repository.xstream/repository.xstream-1.1.4.zip)

Das plugin alleine (wenn gewünscht), xStream Nightly, bekommt Ihr von Github:

- [xStream Nightly](https://github.com/streamxstream/plugin.video.xstream)


*Die Nightly Version gilt als Experimentell jedoch ist es viel aktueller*
*und neu Seiten sind hier zuerst enthalten.*

*Fehler können daher vorhanden sein.*

***WICHTIG / Achtung:*** 

An dieser Stelle wird klar darauf hingewiesen, dass bei alternativen Bezugsquelle nicht für den aktuellsten Stand und Funktion der Software garantiert werden kann!!!

 - Repo Installieren:

- öffne die Kategorie Addons
- aus zip installieren
- Download Ordner suchen und installieren

 - Nach dem das Repo Installiert wurde ist noch folgendes zu machen:

- öffnet die Kategorie Addons
- Aus Repository installieren
- xStream Repository
- *Video-Addons*
- xStream (installieren/aktivieren)
- *Addon Verzeichnis*
  hier Lastship Libraries Repository aktivieren
  (dann wird der URL-Resolver automatisch aktualisiert)

Im Anschluss kann dann das xStream "Autoupdate“ gemacht werden (muss aber nicht), wie unten Beschrieben

### 2.2 Allgemeine Einstellungen

Unter Bevorzugte Sprache, kann die gewünschte Sprache für die Seiten ausgewählt werden 

Dabei kann unter den Optionen Deutsch, Englisch und Alle gewählt werden, wobei Alle beide Sprachen einbezieht 

Zu berücksichtigen ist jedoch, dass die einzelnen Site-Plugins diese Option unterstützen müssen 

Wird also die ausgewählt Option nicht unterstützt werden auch Inhalte anderer Sprache nicht angezeigt

Sonst am besten alles so lassen wie es ist, die Views leer lassen, sowie auch die Downloads.

Wenn gesehene Filme auf einmal weg sind, liegt das an den Einstellungen im Seitenmenü

Hier die Markierung „gesehene Filme“ deaktivieren!

***Wenn Ihr  xStream Repo (v.1.0.5)  installiert habt, müsst Ihr in den xStream Einstellungen das Update auf nightly stellen um folgende Funktionen zu erhalten***

 **Auto-Update Funktion**
 
Diese installiert automatisch Änderungen *an Seiten* usw., welche auf der Entwicklerplattform (Github) durchgeführt werden

Das Updatet nimmt die aktuelle nighly Version

Dadurch werden Fehler/Bugs/Error, schnell & einfach behoben

Als Standard ist aktiviert eingestellt

Dieses Auto-Update wird nur ausgeführt mit dem Kodi Start und wird durch eine Meldung auch angezeigt

Diese xStream Auto-Update Funktion arbeitet Unabhängig von den KODI Einstellungen

Wenn in Kodi unter: 

Optionen-Einstellungen-Addons-Seitenmenü, Automatische Aktualisierung auf AUS gestellt ist, wird xStream trotzdem aktualisiert

Bei Problemen mit dem Update konnte man sich ja meist damit behelfen unter userdata die 'update_sha' zu löschen. Somit kam es dann zu einem erzwungenen, vollständigen Update

Die neue Option (rot) in den Einstellungen macht genau dieses Löschen. Nach dem Update wird diese Einstellung automatisch wieder auf "off" gesetzt!

**ACHTUNG! - Diese Funktion ist nur bei manuellem Update ( Nightly Update) aktiv!**

**URLResolver Nightly Update**

Für den URLResolver besteht auch die Möglichkeit schnell an die neusten Updates zu kommen um nicht auf ein Release warten zu müssen

Als Standard ist deaktiviert eingestellt

Im Menü Einstellungen- Allgemein kann es aktiviert werden

Beachtet an dieser Stelle, dass *Nighly's* auch Fehler enthalten können

### 2.3 Webseiten Aktivieren und Deaktivieren

*Standard:* Alle Site-Plugins aktiviert

In den Einstellungen, unter dem Menüpunkt *Site-Plugins*, besteht die Möglichkeit bestimmte Seiten an bzw. auszuschalten

Dies kann von Nutzen sein, wenn kein Interesse an bestimmten Medien besteht

Diese werden dann auch nicht in der globalen Suche angezeigt

Zusätzlich kann man auswählen, ob bzw. welche Seiten bei Durchführung der Globalen Suche, durchsucht werden sollen.

Hier **muß** mindesten eine Seite ausgewählt werden, sonst kann das Fenster nicht geschlossen werden!!

Nache einem xStream Update werden auch neu hinzugefügte Seiten automatisch angezeigt

*Anmerkung*

Wenn Ihr Probleme mit kinox, movie4k usw. habt, hilft es wenn Ihr Eure DNS (z.B. auf die von Google 8.8.8.8) Adresse ändert
Manche Seiten werden von den Internet Providern geblockt

### 2.4 Manuelle und automatische Hosterwahl

Die Hosterwahl als solches ist sehr schlicht und einfach gehalten. Es erinnert stark an die eigentlichen Benuteroberflächen der jeweiligen Streaming-Seiten

Wenn keine besonderen Wünsche bzw. keine entprechende Kenntisse im Bezug auf die Hosterauswahl vorhanden sind, kann die Automatische Hosterwahl verwendet werden. In dieser Einstellung werden darüber hinaus nicht funktionierende Hoster rausgefiltert. 

**Hosterauswahl**

*Dialog*

Bei Aktivierung wird die Hosterauswahl als Pop-Up Fenster dargestellt

*Hosterliste*

Bei Aktivierung wird die Hosterauswahl nicht mehr als Pop-Up-Fenster dargestellt, sondern als normale Verzeichnisliste.

*Auto*

Automatische Hosterauswahl

**Hosterliste prüfen und sortieren**

Bei Aktivierung werden aus der Hosterliste alle nicht unterstützten Hoster entfernt und nach ihrer Priorität (Resolver Settings) sortiert

Diese kann unter "Resolver Settings" angepasst werden. 

*Niedrige Werte werden vor hohen Werten gewählt*

*Da Lastship & xStream den gleichen URL Resolver verwenden, hat diese Einstellung auch Auswirkung auf beide Addons!!*

Die Deaktivierung diese Features kann auf leistungsschwachen System (z.B. RPi) einen spürbar schnelleren Ablauf bewirken.

Ich würde die Deaktivierung Empfehlen, da es nicht wirklich notwendig ist (und manchmal für Fehler verantwortlich ist)

***Anmerkung zu den Hostern Jetload TheVideo, Flashx usw.:***

Wenn Ihr einen dieser Hoster zum Streamen auswählt, erscheint ein Fenster, welches Euch auffordert Eure Gerät zu Pairen

Das könnt ihr mit ruhigen Gewissen machen

Ihr müsst im selben WLAN sein wie das zu Pairende Gerät (z.B. FireTV, Apple TV usw.)

Für Flashx müsst Ihr Euch auf Flashx.tv ein Benutzerkonto anlegen, dafür kann auch eine Wegwerf E-Mailadresse verwendet werden

Öffnet am Handy/Tablet/PC einen Browser mit der angezeigten Adresse von z.B. flashx (https://www.flashx.tv/pair)

Bei Jetload ist das folgende Pairing Seite: https://jlpair.net/

(Klickt in dem Kasten bei “Ich bin kein Roboter”)

Dann die Bilderaufgabe lösen

Dann ganz runter und klick auf “Pair”

Das wars

Dieser Vorgang muss immer wieder Wiederholt werden (nach 3-4 Stunden oder 5 Streams)

*Warum ist das "pairen" nötig?*

Auf der Homepage muss immer eine Werbung betrachet werden

Da wir ja die Homepage des Hostbetreibers nicht besuchen müssen, entgehen dem Betreiber Werbeeinnahmen. 

Damit dies nicht der Fall ist und die Hoster xStream so arbeiten lassen, wurde mit den Betreibern diese "pair" Funktion vereinbart

Durch den klick auf "pair" bekommen die Hoster Ihre Werbeeinnahme.

Für Euch entstehen dadurch KEINE Kosten!!

### 2.5 Metahandler benutzen

xStream und ander derartige Video Addons benutzen den gleichen Metahandler

Bei Aktivierung wird das externe Modul metahandler genutzt um ausführliche Informationen in Form von Metadaten, wie Fanarts, Covers oder Episodenbilder, zu den Streams bereitzustellen

Ermöglicht eine relativ konsistente Verwendung der "gesehen" Markierung

Bei erstmaliger Verwendung dauern die Ladevorgänge deutlich länger

Dies liegt daran, dass  zunächst alle neuen Informationen zusätzlich über das Internet abgerufen werden müssen

Für schwache Systeme nur bedingt zu empfehlen

Muss vom jeweiligen Site-Plugin unterstützt werden, sonst zeigt diese Option keine Funktion

- **Metahandler ersetzt Infos von Site**

	Bei Aktivierung werden Metainformationen vom  "Metahandler" bevorzugt, d.h. Metainformationen die von einem Site-Plugin geliefert wurden werden nicht nur ergänzt sondern auch ersetzt.

- ***ACHTUNG:*** 

	Da viele Seiten nicht sofort genug Informationen bereitstellen um jeden Film eindeutig zu identifizieren kann es vorkommen, dass alle angezeigten Informationen nicht zum tatsächlich verlinkten Film passen.

### 2.6 Autoplay Funktion

Ist diese Option aktiviert, wird keine Hosterliste angezeigt

xStream probiert automatisch alle verfügbaren Hoster aus, bis ein Stream abgespielt werden kann

Die Auswahlreihenfolge der Hoster richtet sich nach deren Priorität

Diese kann unter "Resolver Settings" angepasst werden

*Niedrige Werte werden vor hohen Werten gewählt*

Sind Eure Priorisierten (Lieblings) Hoster nicht dabei (weil sie nicht verfügbar sind), nimmt xStream den nächsten Hoster der funktioniert

*Bevorzugte Qualität bei Auto-Play: *

hier kann die Qualität der Streams eingestellt werden

Ist Best eingestellt,  wir immer der beste verfügbare Stream gewählt

### 2.7 Zentralisierte Einstellungen

Wenn AUS: werden im Hauptmenü 3 Ordner (Globale Suche, xStream Einstellungen, Resolver Einstellungen) angezeigt

Wenn EIN: wird nur Globale Suche & Einstellungen angezeigt

Einstellungen beinhaltet xStream Einstellungen & Resolver Einstellungen

### 2.8 Gemeinsamer gesehen Status in xStream und anderen derartigen Video Addons

Dies ist möglich über bzw. durch die Verwendung des Metahandlers

In xStream muss dieser aktiviert werden:

xStream-Einstellungen-KATEGORIE Allgemein- Metadaten-Metahandler verwenden aktivieren (nur diesen Eintrag)

Wenn Ihr das gemacht habt, müssen jedoch die Favoriten von xStream neu gesucht und gespeichert werden

Nachdem der Metahandler aktiviert wurde,erscheint in der xStream Oberfläche ein weiterer Menüpunkt (Metahandler-Einstellungen),diesen öffnen

*Kategorie:* Metahandler

Hier kann der Speicherort der Datenbank geändert werden (ist  aber eigentlich nicht notwendig diesen zu ändern)

*Kategorie:* TMDB

Language: Deutsch

Poster Size & Backdrop Size: original

*Kategorie TVDB:*

Language: Deutsch

OK. Das wars

*Der große Vorteil bei dieser Anwendung ist jener:*
 
Wenn Ihr jetzt in xStream einen Stream "gesehen" habt, ist dieser auch in andern Addons "gesehen", und auch umgekehrt
 
Dabei macht es keinen Unterschied mit welcher Seite in xStream (bs.to , serienstrem.to usw.) Ihr den Stream abspielt oder anschauen wollt

Der "gesehen Status" (watched state), kann auch exportiert und auf einem anderen System imortiert werden 

Dazu muss die *video_cache.db* Datei von folgendem Pfad auf das andere System (gleicher Pfad) übertragen werden:

 .....kodi/userdata/addon_data/skript.module.metahandler/meta_cache/video_cache.db


## 3. Bekannte Probleme

### 3.1 Fehler bei der Installation

Fehler können verschiedene Ursachen haben. Bei Hilfe bitte immer folgendes bekannt geben:

Log, Kodi Version, Betriebssystem, xStream Version, genaue Fehlerbeschreibung!

Bitte, schauen, ob der Fehler in einem früheren Post schon beantwortet wurde!

Es kann auch eine fehlerhafte Datei vorliegen, oder die .zip ist falsch aufbereitet

**xStream kann nicht aus der aktuellen Repo installiert werden**

Wenn Ihr Probleme habt, diese zu Installieren, kann es sehr oft hilfreich sein, die alte xStream Repository zu installieren und dann die NEUE Repo im Anschluss gleich drüber installieren.

Die alte Repo hat keine Funktion mehr, dient eben nur zur Behebung für das genannte Problem!!

Diese ist hier zum Downloaden [Link](https://github.com/streamxstream/xStreamRepo/blob/master/repository.xstream/repository.xstream-1.0.5.zip)

**xStream kann auf Kodi 17 nicht ausgeführt werden**

Das xStream Repo 1.1.3 und daraus xStream sind installiert, jedoch sind die Felder "Aktivieren" bzw. "Konfigurieren" ausgegraut.

Sollte das bei Euch der Fall sein, dann kann es helfen die alte Repo (1.0.5) aus dem Forum zu installieren und dann erst die neu Repo drüber installieren

Diese ist hier zum Downloaden [Link](https://github.com/streamxstream/xStreamRepo/blob/master/repository.xstream/repository.xstream-1.0.5.zip)

### 3.2 Fehler bei Verwendung der Globalen Suche

Falls bei der Globalen Suche eine Fehlermeldung bekommen, dass eine Seite nicht erreichbar war bzw. die Suche durch eine Meldung unterbrochen wurde, liegt dies meist an der Seite

Meistens sind die Seiten in diesem Moment nicht erreichbar, einfach abwarten

Es kann auch vorkommen, dass bei der Globalen Suche keine Treffer angezeigt werden, dann bitte in der gewünschten Seite die Suche nutzen (manchmal stören die Seiten, die Globale Suche)

Um schnelle Abhilfe zu leisten lohnt es sich in diesem Fall durchaus die Entwicklergemeinde darauf aufmerksam zu machen

### 3.3 Fehler bei Verwendung einzelner Webseiten

Das kann verschiedene Ursachen haben. Meistens liegt es jedoch an der eigentlichen Webseite

Denn wenn dort auch nur eine Kleinigkeit geändert wird, kann es schon sein, dass  das Site-Plugin nicht mehr geht

Die Entwickler wissen es meist und arbeiten an einer Lösung

Das Update wird dann, wenn es in xStream eingestellt wurde, automatisch installiert 

Die Seite im Browser aufrufen und auf Funktion überprüfen

Im Anschluss das Problem schildern

Bitte Sachlich bleiben und nicht jammern!

*Für die Streaming-Seiten kinox.to und movie4k.to können in den Einstellungen alternative Domäne bestimmt werden. Nutzen sie diese falls die Seiten nicht zu erreichen sind!*

### 3.4 URL Resolver Fehler

Sollte dies der Fall sein, bitte die aktuellste Version des "URLResolver" beziehen:

[Link](https://github.com/streamxstream/xStreamRepo/tree/master/script.module.urlresolver) 

Bitte den gewünschten Film auf der Homepage auf Funktion kontrollieren.

**Premium Anbieter funktionieren nicht, normale Streams laufen, bzw. Ladekreis kurz sichtbar aber kein Stream**

Es kommt oft vor, dass Streams von Premium Anbietern (z.B. Premiumize, RealDebrid, AllDebrid, MegaDebrid usw.) nicht laufen

oder der Ladekreis ist kurz sichtbar aber kein Stream wird abgespielt

Normale Streams laufen hingegen ohne Probleme

Eine mögliche Lösung (die schon Erfolge gezeigt hat)ist folgende:

Im URLReslover die Cache Funktion auf AUS schalten

Erreichbar direkt über xStream:

URLResolver Einstellungen

Eventuell noch Cache Funktion zurücksetzen klicken

**Ein Hoster (z.B. vidto) geht bei allen nur bei Euch nicht**

Das kann an einer falschen Installation des URL Resolver liegen 

(z.B. das "-master" wurde nicht entfernt bei Downloads von GitHub vor der Installation oder URLResolver ist 2 mal vorhanden usw.)

*Wenn dieser Fehler auftreten sollte, kann folgendes helfen:*

Alle Ordner, die zum URLResolver gehören, löschen. 

Und zwar einmal im

 ..kodi/addons-Ordner, script.module.urlresolver löschen 
 
 und zum anderen im
 
 ...kodi/userdata/addon_data-Ordner, script.module.urlresolver löschen

Dann installierst du den aktuellsten URL Resolver aus der [.zip von  Github](https://github.com/streamxstream/xStreamRepo/tree/master/script.module.urlresolver)

### 3.5 Fehlermeldungen im Betrieb

- **AlleSerien kein Menüeintrag (Serien z.B. Neustes Release ) vorhanden**

Und zwar gibt es ab und zu bei AlleSerien einen Fehler

Da steht dannn z.B. bei Serien / Neustes Release, *xStream Es wurde kein Eintrag gefunden*, nach ein paar Minuten funktionierts wieder

Über die Suche ist aber alles zu finden

Das liegt leider an der Seite. Wenn diese recht ausgelastet ist, dann kommt der Fehler

Ist auch bei den Hoster von der Seite so

Da kann man leider nichts machen als warten

- **ImportError:** Bad magic number in bs_finalizer.pyo

	- Status: Problem behoben (Master)

	- **TypeError:** string indices must be integers

	- Status: Problem behoben (Master)

- **AttributeError:** "...Resolver" object has no attribute "priority"

	- Status: Problem behoben (Master)

- **KeyError:**'TVShowTitle'

	- Status: Problem behoben (Master)

- **Movie4k funktioniert nicht**

	- Status: Problem behoben (Beta)

- **Metahandler funktioniert nicht**

	- Status: Problem bekannt, ist in Arbeit

Angaben in (...) = Aktueller "Ort"

- **Beim Starten von xStream kommt folgende Fehlermeldung**

	- "IOError: [Errno socket error] [SSL:CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:590)
	
	- Status: Problem behoben (Master)
	
	- *Anmerkung:* in den xStream-Settings die Suche nach Updates ausschalten, dann läuft es wieder
	
	Updates von Git muss man dann manuell einspielen oder auf Updates über das offizielle xStreamRepo warten
	
- **Beim Öffnen von Serien/Filmen in xStream kommt folgende Fehlermeldung**

	- AttributeError:´loadError´ object has no attribute ´encode´
	
	- Lösung: 
	
	Kodi (und daher auch xStream) mag keine Sonderzeichen im Benutzernamen
Sonderzeichen im Benutzernamen entfernen dann geht es

- **Fehler 1 beim Öffnen von BurningSeries (BS)**

	- [SSL:CERTIFICATE_VERIFY_FAILED] certificate failed (sl.c:590)

		und danach kommt eine Fehlermeldung:

		ValueError MO JSON object could be decoded File 
		"/Users/Shared/xbmc-depends/appletvos9.1_arm64-target/lib/line 366, in decode"

	- Status: Problem behoben 

- **Fehler 2 beim Öffnen von BurningSeries (BS):** 

	- ImportError: No Module named t0mm0. Common.net /script. Module. Urlresolver /lib/urlresolver /plugins /ecostrean. 
	
	Pline 19,in < module> 

	- Lösung: Es fehlt eine Abhängigkeit von xStream, welche eigentlich bei der Installation über das Repo mit installiert werden sollte.
	
Deinstalliert xStream nochmal und installier es über das xStream Repo neu oder von Git die [nightly](https://github.com/streamxstream/plugin.video.xstream/tree/nightly)

- **Fehlermeldung beim öffnen eines Site-Plugins**

	- Errno4 non-recoverable failure in the name Resolution.Fehler
	
	Weist auf ein Problem bei der Namesauflösung der Domains hin. 
		
	Könnte z.B. an der eingestellten DNS liegen (oder VPN) oder aber auch an den netzwerkbezogenen Einstellungen von Kodi

	- Lösung: Database im Profilordner von xStream löschen, wie folgt:
	
	Optionen-Dateimanager-Profil_Ordner-addon_data-plugin.Video.xstream-pluginDB wählen und löschen
		
- **Anzeige: Es ist mehr als ein URLResolver installiert. Bitte löschen**

	Das Problem entsteht durch komische Repos oder durch manuelle Installation (wenn man beim Installieren in der .zip nicht das "-master" entfernt)
	
	Dadurch wird dann ein zweiter URLResolver angelegt und das führt dann zum Problem.

	- Lösung:  geht im Kodi Ordner zu .../kodi/addons/
	
	Dort werdet ihr dann Ordner finden, die wie folgt heißen:

	- script.module.urlresolver
	- script.module.urlresolver-master


	Einfach den Ordner mit "-master" am Ende löschen und die Fehlermeldung ist weg. Und auch das AutoUpdate im xStream funktioniert wieder.
	
	
- **Errno 1 bzw. Errno 8 Fehlermeldung bei Seiten**

	Die Webseitenbetreiber & Hoster stellen Ihre  Verschlüsselung um

	Das Problem hat nichts mit xStream zu tun

	Es liegt an Kodi, bzw. der Pythonversion welche Kodi verwendet

	Ist diese veraltet (Kodi 16.1 abwärts) kommte es zur Fehlermeldung bei diversen Site-Plugins / Hoster
	
	- Lösung: Kodi 17 verwenden

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

	- Lösung: Die Seite 'Dokustreamer' deaktivieren (bis der Fehler behoben wird).Sie verursacht den Fehler.

- **Fehlermeldung für das Autoupdate xStream und URL Resolver**

	Es kommt am Apple TV immer wieder zu dieser Fehlermeldung, wenn das xStream AutoUpdate und das URL Resolver Autoupdate aktiviert sind

	Wenn beide Autoupdates deaktiviert werden gibt es auch keine Fehlermeldung. Updates müssen dann selber heruntergeladen & installiert werden

	Das ist jedoch KEIN xStream Fehler, sondern das liegt am Apple TV (bzw. das benutzte Python)

	Die kommt mit den HTTPS links vom Updater nicht klar

	Lösen kann das Problem nur Apple, oder ggf.Kodi

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

