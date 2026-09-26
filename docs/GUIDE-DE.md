# Pioneer Build Check

Finde fehlende Einstellungen und Anschlussprobleme direkt in deiner Fabrik. Mit der Build Check Gun prüfst du einzelne Gebäude oder einen selbst gewählten Bereich, lässt dir Warnungen an den Maschinen anzeigen und teilst Berichte mit anderen Spielern.

![Bereichsprüfung mit der Build Check Gun](images/area-scan.png)

## Funktionen

- Einzelprüfung und räumliche Bereichsauswahl mit einstellbarer Unterkante, Oberkante und Drehung.
- Prüfungen auf fehlende Rezepte, Stromverbindungen sowie auswertbare Förderband- und Rohranschlüsse.
- Abgleich beobachteter Materialien mit dem Rezept und Vergleich auswertbarer Bandkapazitäten mit dem konfigurierten Bedarf.
- Vergleich von Rezept, eingestelltem Takt und Sloop-Verstärkung mit einer Referenzmaschine desselben Typs.
- Hervorhebung von Warnungsgebäuden, mit ausführlichen Meldungen innerhalb von 25 Metern.
- Begrenzte Rückverfolgung von Zuführungen mit markierbaren Quellen und Abbruchpunkten.
- Filter, ignorierbare Treffer, gespeicherte Zonen und Berichte.
- Berichtfreigabe im Multiplayer mit sichtbarer Benachrichtigung und Ungelesen-Markierung.
- Deutsche und englische Oberfläche; Einzelspieler, selbst gehosteter Multiplayer und dedizierte Server.

## Erste Schritte

1. Installiere die Mod mit dem Satisfactory Mod Manager. Im Multiplayer benötigen Server und alle beteiligten Clients dieselbe Mod-Version.
2. Schalte den Meilenstein **Pioneer Build Check** in HUB-Stufe 1 frei.
3. Stelle die Build Check Gun in der Ausrüstungswerkstatt her und rüste sie aus.
4. Wähle ein Gebäude aus oder wechsle zur Bereichsauswahl.
5. Öffne das Menü und wähle **Prüfung starten**.

### Standardbedienung

| Taste | Funktion |
| --- | --- |
| Linke Maustaste | Gebäude auswählen oder eine Bereichsecke setzen |
| Rechte Maustaste | Build-Check-Menü öffnen/schließen |
| R | Zwischen Einzelgebäude und Bereich wechseln |
| Esc | Build-Check-Menü schließen |

Die eingeblendeten Hinweise und die Hilfe im Menü zeigen die Bedienung. Bei geänderten Tastenbelegungen gelten deine Einstellungen.

## Einen Bereich prüfen

Wechsle mit **R** in den Bereichsmodus und setze zwei Ecken mit der linken Maustaste. Über **Auswahl anpassen** kannst du Unterkante, Oberkante und Drehung einstellen. Die Höhen sind Weltkoordinaten in Metern. Schließe für den Bandbedarfsvergleich die Maschinen und ihre Zuleitungen ein und starte anschließend die Prüfung.

![Höhen und Drehung des Prüfbereichs](images/area-selection.png)

## Ergebnisse lesen

Klappe eine Gebäudekategorie und den gewünschten Treffer auf. **Details anzeigen** öffnet die vollständige Erklärung. Mit **Hervorheben** findest du das betroffene Gebäude; über die erneute Prüfung aktualisierst du den Befund nach einer Änderung.

Die Liste zeigt bis zu **48 Treffer pro Seite**. Die Seitennavigation bleibt unten sichtbar. Das ist keine Grenze von 48 gescannten Gebäuden. Automatische Warnungsmarkierungen berücksichtigen alle empfangenen, nicht ignorierten Warnungsgebäude; gefilterte Markierungen sind auf 48 begrenzt.

![Trefferliste mit Seitennavigation](images/check-list.png)

![Details zu einem fehlenden Eingang](images/finding-details.png)

| Ergebnis | Bedeutung |
| --- | --- |
| Warnung | Die Prüfung hat einen konkreten auffälligen Zustand erkannt. Prüfe die Erklärung und ob dieser Zustand beabsichtigt ist. |
| Nicht vollständig prüfbar | Die verfügbaren Daten reichen nicht für eine eindeutige Bewertung. Das ist kein bestätigter Baufehler. |
| Hinweis | Zusätzliche Informationen zur geprüften Konfiguration oder zum beobachteten Material. |
| Allgemeine Prüfgrenze | Eine Gebäudefunktion ist nur teilweise abgedeckt; diese Grenzen werden separat zusammengefasst. |

## Hinweise direkt an der Maschine

Aktiviere die automatische Markierung der Warnungsgebäude. In der Nähe erscheinen die ausführlichen Meldungen bis 25 Meter; weiter entfernt bleibt eine kompakte Beschriftung. Während geöffneter Menüs werden die Welttexte ausgeblendet.

![Warnungsdetails direkt an einer Maschine](images/machine-report.png)

## Quellen und Abbruchpunkte

Die Zuführungsdiagnose verfolgt unterstützte Verbindungen innerhalb fester Grenzen zurück. Mit **Quelle / Abbruchpunkt hervorheben** kannst du den erfassten Endpunkt finden; die Details zeigen dessen Anschlussdaten. Wenn die automatische Verfolgung dort endet, kannst du das markierte Gebäude oder den nächsten Bereich separat prüfen.

## Referenzvergleich und gespeicherte Zonen

Wähle zuerst eine einzelne Produktionsmaschine als Referenz. Wechsle dann zur Bereichsauswahl, schließe die Referenz ein und aktiviere den Gruppenvergleich. Maschinen desselben exakten Typs werden mit der Referenz verglichen. Die Zone lässt sich zusammen mit Gruppe und Referenz speichern. Nach Abriss oder Ersatz der Referenzmaschine musst du die Referenz neu setzen.

## Berichte teilen und empfangen

Öffne **Bericht teilen** und wähle den Empfänger. Ein empfangener Bericht ist eine schreibgeschützte Kopie. Neue Berichte werden im HUD, an der Gun und in der Berichtablage angezeigt.

![Sichtbare Benachrichtigung beim Berichtempfang](images/report-received.png)

![Hervorgehobene Berichtablage](images/report-notification.png)

Öffne die Berichtablage und anschließend den ungelesenen Bericht. Danach verschwindet seine Ungelesen-Markierung. Weitere ungelesene Berichte bleiben weiterhin markiert.

![Berichtablage mit ungelesenem Bericht](images/report-inbox.png)

![Geöffneter Bericht eines anderen Spielers](images/shared-report.png)

## Prüfgrenzen und Kompatibilität

Die Ergebnisse sind **Momentaufnahmen**, keine laufende Überwachung. Prüfe nach Umbauten oder geänderten Einstellungen erneut. Eine erkannte konfigurierte Quelle bestätigt keinen tatsächlichen Materialdurchsatz. Die Mod ist keine vollständige Stromnetz- oder Flüssigkeitssimulation.

Unbekannte Mod-Funktionen, mehrdeutige Materialzuordnungen und erreichte Prüfgrenzen können zu „Nicht vollständig prüfbar“ führen. Die Screenshots zeigen auch modifizierte Maschinen; daraus folgt keine vollständige Unterstützung aller Funktionen dieser Mods. Ein fehlender automatischer Ausgang kann bei bewusst manueller Abholung beabsichtigt sein.

Der Benachrichtigungston war im gemeldeten Multiplayer-Test nicht hörbar. Die sichtbaren Benachrichtigungen funktionieren unabhängig davon.
