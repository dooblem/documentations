# Übersicht Haus-Automatisierung
**Analyse → Zusammenfassung der Hausautomation**

Auf dieser Seite können Sie die verschiedenen Elemente, die in Ihrem Jeedom konfiguriert sind, auf einer einzigen Seite zusammenfassen. Es bietet auch Zugriff auf Funktionen zum Organisieren von Geräten und Steuerungen, auf deren erweiterte Konfiguration und zum Anzeigen von Konfigurationsmöglichkeiten..

## Informations

Oben auf der Seite finden wir :
- **Anzahl der Objekte** : Gesamtzahl der in unserem Jeedom konfigurierten Objekte, einschließlich inaktiver Elemente.
- **Anzahl der Ausrüstungen** : Gleiches gilt für die Ausrüstung.
- **Anzahl der Bestellungen** : Gleiches gilt für Bestellungen.
- **Inactif** : Aktivieren Sie dieses Kontrollkästchen, wenn inaktive Elemente auf dieser Seite angezeigt werden sollen.
- **Rechercher** : Suchen Sie nach einem bestimmten Artikel. Dies kann der Name eines Geräts, eine Bestellung oder der Name des Plugins sein, mit dem das Gerät erstellt wurde.
- **CSV-Export** : Ermöglicht das Exportieren aller Objekte, Geräte und ihrer BefehDie in eine CSV-Datei.

Sie haben auch eine Registerkarte **Historique**, Anzeigen des Verlaufs von Aufträgen, Geräten, Objekten, Ansichten, Design, 3D-Design, Szenarien und gelöschten Benutzern.

## Objektrahmen

Darunter befindet sich ein Frame pro Objekt. In jedem Frame finden wir die Liste der Geräte, die dieses Objekt als übergeordnetes Objekt haben.
Der erste Frame **Aucun** repräsentiert Geräte, denen kein übergeordnetes Element zugewiesen ist.

Für jedes Objekt stehen neben seiner Beschriftung zwei Schaltflächen zur Verfügung.
- Die erste wird verwendet, um die Objektkonfigurationsseite in einer neuen Registerkarte zu öffnen.
- Die zweite enthält einige Informationen zum Objekt,

> **Tip**
>
> Die Hintergrundfarbe der Objektrahmen hängt von der Farbe ab, die in der Konfiguration des Objekts ausgewählt wurde.

> **Tip**
>
> Mit einem Klick auf die Objekte oder Geräte können Sie deren Reihenfolge ändern oder sie sogar einem anderen Objekt zuweisen. Aus der auf dieser Seite festgelegten Reihenfolge wird die Anzeige des Dashboards berechnet.

## Die Ausrüstungen

Auf jeder Ausrüstung finden wir :

- Ein **Kontrollkästchen** um die Ausrüstung auszuwählen (Sie können mehrere auswählen). Wenn mindestens ein Gerät ausgewählt ist, haben Sie Aktionsschaltflächen, die oben links zu angezeigt werden **supprimer**, make **visible**/.**invisible**,  **actif**/.**inactif** ausgewählte Ausrüstung.
- L'**id** Ausrüstung.
- Die **type** Ausrüstung : Kennung des Plugins, zu dem es gehört.
- Die **nom** Ausrüstung.
- **Inactif** (kleines Kreuz) : Bedeutet, dass das Gerät inaktiv ist (wenn es nicht vorhanden ist, ist das Gerät aktiv).
- **Invisible** (durchgestrichenes Auge) : Bedeutet, dass das Gerät unsichtbar ist (wenn es nicht vorhanden ist, ist das Gerät sichtbar).

Wenn das Geräte-Plugin deaktiviert ist, werden die beiden SymboDie rechts nicht angezeigt:
- **Externer Link** (Quadrat mit Pfeil) : Ermöglicht das Öffnen der Gerätekonfigurationsseite in einer neuen Registerkarte.
- **Erweiterte Konfiguration** (Zahnrad) : öffnet das Fenster zur erweiterten Gerätekonfiguration.

> Durch Klicken auf die ZeiDie mit dem Namen des Geräts werden alDie BefehDie für dieses Gerät angezeigt. Durch Klicken auf eine Bestellung gelangen Sie zum Bestellkonfigurationsfenster.

## Erweiterte Gerätekonfiguration

> **Tip**
>
> Sie können (sofern das Plugin dies unterstützt) direkt von der Gerätekonfigurationsseite auf dieses Fenster zugreifen, indem Sie auf die Schaltfläche Erweiterte Konfiguration klicken

Das Fenster von **Erweiterte Gerätekonfiguration** erlaubt es zu ändern. Zunächst sind oben rechts einige Schaltflächen verfügbar :

- **Informations** : Zeigt die Roheigenschaften des Geräts an.
- **Liens** : Ermöglicht die Anzeige der Verknüpfungen des Geräts mit den Objekten, Befehlen, Szenarien, Variablen, Interaktionen usw. in grafischer Form (in diesem Fall führt ein Doppelklick auf ein Element zu seiner Konfiguration)..
- **Log** : Zeigt die Ereignisse des betreffenden Geräts an.
- **Sauvegarder** : Speichern Sie die am Gerät vorgenommenen Änderungen.
- **Supprimer** : Ausrüstung entfernen.

### Registerkarte Informationen

Die Registerkarte **Informations** enthält allgemeine Informationen über das Gerät und seine Bedienelemente :

- **ID** : Eindeutige Kennung in der Jeedom-Datenbank.
- **Nom** : Name der Ausrüstung.
- **Logische ID** : Kennung der logischen Ausrüstung (kann leer sein).
- **Objekt-ID** : Eindeutige Kennung des übergeordneten Objekts (kann leer sein).
- **Erstellungsdatum** : Erstellungsdatum der Ausrüstung.
- **Activer** : Aktivieren Sie das Kontrollkästchen, um das Gerät zu aktivieren (vergessen Sie nicht, es zu speichern)..
- **Visible** : Aktivieren Sie das Kontrollkästchen, um das Gerät sichtbar zu machen (vergessen Sie nicht, es zu speichern)..
- **Type** : Kennung des Plugins, mit dem es erstellt wurde.
- **Versuch fehlgeschlagen** : Anzahl fehlgeschlagener aufeinanderfolgender Kommunikationsversuche mit dem Gerät.
- **Datum der letzten Mitteilung** : Datum der letzten Mitteilung des Geräts.
- **Letztes Update** : Datum der letzten Kommunikation mit dem Gerät.
- **Tags** : Geräteetiketten, die durch zu trennen sind ','. Im Dashboard können benutzerdefinierte Filter erstellt werden

Unten finden Sie eine TabelDie mit der Liste der GerätebefehDie mit jeweils einem Link zu deren Konfiguration.

### Registerkarte &quot;Ansicht&quot;

In der Registerkarte **Affichage**, Sie können bestimmte Verhaltensweisen bei der Anzeige von Kacheln im Dashboard oder auf Mobilgeräten konfigurieren.

#### Widget

-  **Visible** : Aktivieren Sie das Kontrollkästchen, um das Gerät sichtbar zu machen.
- **Name anzeigen** : Aktivieren Sie das Kontrollkästchen, um den Namen des Geräts auf der Kachel anzuzeigen.
- **Objektnamen anzeigen** : Aktivieren Sie das Kontrollkästchen, um den Namen des übergeordneten Objekts des Geräts neben der Kachel anzuzeigen.

### OptionaDie Parameter auf der Kachel

Unten finden Sie optionaDie Anzeigeparameter, die auf das Gerät angewendet werden können. Diese Parameter bestehen aus einem Namen und einem Wert. Klicken Sie einfach auf **Ajouter** einen anwenden
wieder. Für Geräte nur den Wert **style** Wird derzeit verwendet, kann CSS-Code in das betreffende Gerät eingefügt werden.

> **Tip**
>
> Vergessen Sie nicht, nach jeder Änderung zu speichern.

### Registerkarte Layout

In diesem Teil können Sie zwischen dem Standardlayout der BefehDie (nebeneinander im Widget) oder im Tabellenmodus wählen. Im Standardmodus ist nichts einzustellen. Hier sind die im Modus verfügbaren Optionen
**Tableau** :
- **Anzahl der Zeilen**
- **Anzahl der Spalten**
- **In Kisten zentrieren** : Aktivieren Sie das Kontrollkästchen, um die Bestellungen in den Kontrollkästchen zu zentrieren.
- **Allgemeiner Boxstil (CSS)** : Ermöglicht das Definieren des allgemeinen Stils im CSS-Code.
- **Tabellenstil (CSS)** : Hier können Sie nur den Stil der TabelDie definieren.

Unten für jede Box die **detaillierte Konfiguration** erlaubt dir
diese :
- **Boxtext** : Fügen Sie zusätzlich zum Befehl Text hinzu (oder allein, wenn das Feld keinen Befehl enthält)..
- **Box-Stil (CSS)** : Ändern Sie den spezifischen CSS-Stil der Box (beachten Sie, dass das allgemeine CSS der Boxen überschrieben und ersetzt wird)..

> **Tip**
>
> Wenn Sie in einem Feld in der TabelDie zwei BefehDie untereinander setzen möchten, vergessen Sie nicht, nach dem ersten in der TabelDie einen Zeilenumbruch hinzuzufügen **Erweiterte Konfiguration** davon.

### Registerkarte &quot;Warnungen&quot;

Auf dieser Registerkarte können Sie Informationen zur Batterie des Geräts abrufen und entsprechende Warnungen definieren. Hier sind die Arten von Informationen, die gefunden werden können :

- **Batterietyp**,
- **Neuestes Feedback**,
- **Verbleibendes Niveau**, (wenn Ihre Ausrüstung natürlich mit Batterie betrieben wird).

Im Folgenden können Sie auch die spezifischen Batteriewarnschwellen für dieses Gerät definieren. Wenn Sie die Felder leer lassen, werden diese Standardschwellenwerte angewendet.

Sie können das Zeitlimit der Ausrüstung auch in Minuten verwalten. Zum Beispiel sagt 30 jeedom, dass wenn das Gerät 30 Minuten lang nicht kommuniziert hat, es in Alarmbereitschaft versetzt werden muss.

> **Tip**
>
> Die globalen Parameter sind in **→ Einstellungen → Systemkonfiguration : Logs** oder **Equipements**

### Registerkarte &quot;Kommentar&quot;

Ermöglicht das Schreiben eines Kommentars zur Ausrüstung.

## Erweiterte Konfiguration einer Bestellung

Zunächst sind oben rechts einige Schaltflächen verfügbar :

- **Tester** : Wird zum Testen des Befehls verwendet.
- **Liens** : Ermöglicht die Anzeige der Verknüpfungen des Geräts mit Objekten, Befehlen, Szenarien, Variablen, Interaktionen…. in grafischer Form.
- **Log** : Zeigt die Ereignisse des betreffenden Geräts an.
- **Informations** : Zeigt die Roheigenschaften des Geräts an.
-  **Übernehmen** : Ermöglicht die Anwendung derselben Konfiguration auf mehrere Befehle.
- **Sauvegarder** : Speichern Sie die am Gerät vorgenommenen Änderungen.

> **Tip**
>
> In einer Grafik bringt Sie ein Doppelklick auf ein Element zu seiner Konfiguration.

> **Note**
>
> Abhängig von der Art der Bestellung können sich die angezeigten Informationen /. Aktionen ändern.

### Registerkarte Informationen

Die Registerkarte **Informations** enthält allgemeine Informationen zur Bestellung :

- **ID** : Eindeutiger Bezeichner in der Datenbank.
- **Logische ID** : Logische Kennung der Bestellung (kann leer sein).
- **Nom** : Name der Bestellung.
- **Type** : Art der Bestellung (Aktion oder Info).
- **Sous-type** : Befehlssubtyp (binär, digital usw.).
- **Direkte URL** : Gibt die URDie für den Zugriff auf dieses Gerät an. (Rechtsklick, kopieren Sie die Linkadresse) Die URDie startet den Befehl für a **action** und geben Sie die Informationen für a zurück **info**.
- **Unité** : Steuereinheit.
- **Befehl, der ein Update auslöst** : Gibt die Kennung eines anderen Befehls an, der bei Änderung dieses anderen Befehls die Aktualisierung des angezeigten Befehls erzwingt.
- **Visible** : Aktivieren Sie dieses Kontrollkästchen, um den Befehl sichtbar zu machen.
- **Folgen Sie der Zeitleiste** : Aktivieren Sie dieses Kontrollkästchen, um diesen Befehl bei Verwendung in der Zeitleiste sichtbar zu machen. Sie können eine bestimmte Zeitleiste in dem Feld angeben, das angezeigt wird, wenn die Option aktiviert ist.
- **In automatischen Interaktionen verbieten** : verbietet automatische Interaktionen mit diesem Befehl
- **Symbol** : Ermöglicht das Ändern des Befehlssymbols.

Sie haben auch drei andere orangefarbene Knöpfe darunter :

- **Dieser Befehl ersetzt die ID** : Ermöglicht das Ersetzen einer Bestellnummer durch die betreffende Bestellung. Nützlich, wenn Sie ein Gerät in Jeedom gelöscht haben und Szenarien haben, in denen BefehDie verwendet werden.
- **Dieser Befehl ersetzt den Befehl** : Befehl durch aktuellen Befehl ersetzen.
- **Ersetzen Sie diesen Befehl durch den Befehl** : Ersetzen Sie umgekehrt den Befehl durch einen anderen Befehl.

> **Note**
>
> Diese Art von Aktion ersetzt die BefehDie überall in Jeedom (Szenario, Interaktion, Befehl, Ausrüstung…)..

Unten finden Sie eine Liste der verschiedenen Geräte, Befehle, Szenarien oder Interaktionen, die diesen Befehl verwenden. Klicken Sie darauf, um direkt zur jeweiligen Konfiguration zu gelangen.

### Registerkarte Konfiguration

#### Für eine Info-Bestellung :

- **Berechnung und Rundung**
    - **Berechnungsformel (\#Wert \# für den Wert)** : Ermöglicht es Ihnen, den Wert der Bestellung vor der Verarbeitung durch Jeedom zu bearbeiten : `# value # - 0.2` um 0 zu subtrahieren.2 (Versatz an einem Temperatursensor).
    - **Abgerundet (Zahl nach Dezimalpunkt)** : Wird verwendet, um den Wert des Befehls zu runden (Beispiel : Setze 2, um 16 zu transformieren.643 345 in 16,64).
- **Generischer Typ** : Ermöglicht das Konfigurieren des generischen Befehlstyps (Jeedom versucht, ihn im automatischen Modus selbst zu finden).. Diese Informationen werden von der mobilen Anwendung verwendet.
- **Aktion auf Wert, wenn** : Machen wir eine Art Miniszenario. Sie können beispielsweise sagen, dass Sie eine solche Aktion ausführen müssen, wenn der Wert 3 Minuten lang mehr als 50 wert ist. So kann beispielsweise ein Licht X Minuten nach dem Einschalten ausgeschaltet werden.

- **Historique**
    - **Historiser** : Aktivieren Sie das Kontrollkästchen, damit die Werte dieses Befehls protokolliert werden. (Siehe **Analyse → Geschichte**)
    - **Glättungsmodus** : Modus von **lissage** oder d'**archivage** Hier können Sie auswählen, wie die Daten archiviert werden sollen. Standardmäßig ist dies ein **moyenne**. Es ist auch möglich, die zu wählen **maximum**, Die **minimum**, oder **aucun**. **aucun** Lassen Sie uns Jeedom mitteilen, dass für diesen Befehl keine Archivierung durchgeführt werden soll (sowohl während der ersten 5 Minuten als auch mit der Archivierungsaufgabe).. Diese Option ist gefährlich, weil Jeedom alles behält : Es werden also viel mehr Daten gespeichert.
    - **Verlauf löschen, wenn älter als** : Sagen wir Jeedom, dass alDie Daten gelöscht werden sollen, die älter als ein bestimmter Zeitraum sind. Es kann praktisch sein, keine Daten zu speichern, wenn dies nicht erforderlich ist, und daher die Menge der von Jeedom aufgezeichneten Informationen zu begrenzen.

- **Werteverwaltung**
    - **Verbotener Wert** : Wenn der Befehl einen dieser Werte annimmt, ignoriert Jeedom ihn, bevor er angewendet wird.
    - **Statusrückgabewert** : Setzt den Befehl nach einer bestimmten Zeit auf diesen Wert zurück.
    - **Dauer vor Statusrückgabe (min)** : Zeit vor der Rückkehr zum obigen Wert.

- **Autres**
    - **Management der Wiederholung von Werten** : Wenn der Befehl automatisch um den doppelten Wert in Folge erhöht wird, berücksichtigt Jeedom den zweiten Aufstieg nicht (vermeidet das mehrfache Auslösen eines Szenarios, es sei denn, der Befehl ist vom binären Typ).. Sie können die Wiederholung des Wertes erzwingen oder ihn vollständig verbieten.
    - **URDie drücken** : Ermöglicht das Hinzufügen einer URL, die im FalDie einer Aktualisierung der Bestellung aufgerufen werden soll. Sie können die folgenden Stichworte verwenden : `# value #` für den Wert der Bestellung, `# cmd_name #` für den Namen der Bestellung, `# cmd_Identifikation #` für die eindeutige Kennung der Bestellung, `# humanname #` für den vollständigen Namen der Bestellung (z : `# [Badezimmer] [Hydrometrie] [Dieuftfeuchtigkeit] #`), `# eq_name #` für den Namen des Geräts.

#### Für einen Aktionsbefehl :

-  **Generischer Typ** : Ermöglicht das Konfigurieren des generischen Befehlstyps (Jeedom versucht, ihn im automatischen Modus selbst zu finden).. Diese Informationen werden von der mobilen Anwendung verwendet.
- **Aktion bestätigen** : Aktivieren Sie dieses Kontrollkästchen, um eine Bestätigung der Jeedom-Anforderung zu erhalten, wenn die Aktion über die SchnittstelDie dieses Befehls gestartet wird.
- **Zugangscode** : Ermöglicht das Definieren eines Codes, den Jeedom beim Starten der Aktion über die SchnittstelDie dieses Befehls abfragt.
- **Aktion vor Ausführung des Befehls** : BefehDie hinzufügen **avant** jede Ausführung des Auftrags.
- **Aktion nach Ausführung des Auftrags** : BefehDie hinzufügen **nach** jede Ausführung des Auftrags.

### Registerkarte &quot;Warnungen&quot;

Ermöglicht das Definieren einer Alarmstufe (**warning** oder **danger**) abhängig von bestimmten Bedingungen. Wenn beispielsweise 30 Minuten lang &quot;Wert&gt; 8&quot; angezeigt wird, kann das Gerät in Alarmbereitschaft versetzt werden **warning**.

> **Note**
>
> Auf der Seite **→ Einstellungen → Systemkonfiguration : Logs**, Sie können einen Nachrichtentypbefehl konfigurieren, mit dem Jeedom Sie benachrichtigen kann, wenn der Warn- oder Gefahrenschwellenwert erreicht ist.

### Registerkarte &quot;Ansicht&quot;

In diesem Teil können Sie bestimmte Widget-Anzeigeverhalten im Dashboard, in Ansichten, im Design und auf Mobilgeräten konfigurieren..

- **Widget** : Ermöglicht die Auswahl des Widgets auf dem Desktop oder auf dem Handy (beachten Sie, dass Sie das Widget-Plugin benötigen und dies auch von dort aus tun können)..
- **Visible** : Überprüfen Sie, ob der Befehl sichtbar ist.
- **Name anzeigen** : Aktivieren Sie diese Option, um den Namen des Befehls je nach Kontext sichtbar zu machen.
- **Anzeigename und Symbol** : Aktivieren Sie das Kontrollkästchen, um das Symbol zusätzlich zum Befehlsnamen sichtbar zu machen.
- **Umbrochene ZeiDie vor dem Widget** : Wählen **vor dem Widget** oder **nach dem Widget** Hinzufügen eines Zeilenumbruchs vor oder nach dem Widget (um beispielsweise eine Anzeige in der Spalte der verschiedenen BefehDie des Geräts anstelDie von Zeilen standardmäßig zu erzwingen)

Unten finden Sie optionaDie Anzeigeparameter, die an das Widget übergeben werden können. Diese Parameter hängen vom jeweiligen Widget ab. Sie müssen sich daher die Datei auf dem Markt ansehen, um sie zu kennen.

> **Tip**
>
> Vergessen Sie nicht, nach jeder Änderung zu speichern.
