







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




