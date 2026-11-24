# BohemianSuite

**Deine Noten vom PC direkt auf deine Homepage.**

Du hast deine Kompositionen bereits als Einzelstimmen-PDFs auf deinem Computer? Dann hast du den wichtigsten Teil schon.

BohemianSuite übernimmt deine vorhandenen Noten, hilft dir beim Aufbau deiner Werke und bringt sie anschließend direkt auf deine WordPress-Homepage. Werkdaten ergänzen, synchronisieren, fertig. Hörproben, Deckblätter und Vorschauseiten kommen auf Wunsch dazu.

> Du kümmerst dich um deine Musik. BohemianSuite kümmert sich um den Weg von deinen Noten auf deine Homepage.

---

## Download – aktuelle Version

| | Datei | Download |
|---|---|---|
| **macOS** (Apple Silicon und Intel) | BohemianSuite-macOS.dmg | [Herunterladen](https://github.com/trompetist91/bohemiansuite-releases/releases/latest/download/BohemianSuite-macOS.dmg) |
| **Windows** (64-Bit) | BohemianSuite-Windows.msi | [Herunterladen](https://github.com/trompetist91/bohemiansuite-releases/releases/latest/download/BohemianSuite-Windows.msi) |
| **WordPress-Plugin** | bohemiansuite-directory.zip | [Herunterladen](https://github.com/trompetist91/bohemiansuite-releases/releases/latest/download/bohemiansuite-directory.zip) |

Diese Links zeigen immer auf die neueste Version.
Alle bisherigen Versionen und was sich jeweils geändert hat, findest du unter **[Releases](https://github.com/trompetist91/bohemiansuite-releases/releases)**. In der App siehst du den Änderungsverlauf außerdem auf der Seite **Info**.

---

## Was du brauchst

- deine Noten als Einzelstimmen-PDFs (optional eine Audiodatei als Hörprobe)
- eine eingerichtete **WordPress-Homepage** mit **SFTP-Zugang**
- einen Mac oder Windows-PC

---

## Installation

Eine Schritt-für-Schritt-Anleitung für die Einrichtung findest du im [Schnellstart](https://bohemiansuite.de/quickstart/).

### macOS

1. `BohemianSuite-macOS.dmg` herunterladen und öffnen.
2. **BohemianSuite** in den Ordner **Programme** ziehen.
3. Beim ersten Start kann macOS melden, dass die App nicht überprüft werden konnte.
   Öffne dann **Systemeinstellungen → Datenschutz & Sicherheit** und klicke bei BohemianSuite auf **Dennoch öffnen**.
   Alternativ: im Ordner Programme mit Rechtsklick auf BohemianSuite → **Öffnen**.
   Das ist nur beim ersten Start nötig.

### Windows

1. `BohemianSuite-Windows.msi` herunterladen und doppelklicken.
2. Erscheint der Hinweis „Der Computer wurde durch Windows geschützt“, auf **Weitere Informationen** und dann **Trotzdem ausführen** klicken.
3. Der Installation folgen.

### WordPress-Plugin

1. In WordPress **Plugins → Installieren → Plugin hochladen** öffnen.
2. `bohemiansuite-directory.zip` auswählen und **Jetzt installieren** klicken.
3. Das Plugin **aktivieren**.

---

## Update auf eine neue Version

- **macOS:** neue DMG herunterladen und BohemianSuite im Ordner Programme ersetzen.
- **Windows:** neue MSI herunterladen und ausführen – die vorhandene Installation wird aktualisiert.
- **WordPress-Plugin:** neue ZIP-Datei wie bei der Installation hochladen und das Ersetzen der vorhandenen Version bestätigen.

Deine Werke, Einstellungen und Daten bleiben bei einem Update erhalten. Vor größeren Updates empfehlen wir trotzdem eine **Sicherung** über **Einstellungen → Backup & Wiederherstellen**.

> Hinweis in den Release-Notizen beachten: Manche Versionen empfehlen nach dem Update einmal einen **Vollsync**, damit deine Homepage vollständig auf den neuesten Stand gebracht wird.

---

## Erste Schritte, Hilfe und Kontakt

- **Website:** [bohemiansuite.de](https://bohemiansuite.de/)
- **Schnellstart Desktop-App:** [bohemiansuite.de/quickstart](https://bohemiansuite.de/quickstart/)
- **Schnellstart WordPress-Plugin:** [bohemiansuite.de/quickstart-wp-plugin](https://bohemiansuite.de/quickstart-wp-plugin/)
- **Hilfe & FAQ:** [bohemiansuite.de/faq-hilfe](https://bohemiansuite.de/faq-hilfe/)
- **Kontakt:** [bohemiansuite.de/kontakt](https://bohemiansuite.de/kontakt/)

---

## Rechtliches

Die Desktop-App BohemianSuite ist proprietäre Software. © 2026 BohemianSuite – alle Rechte vorbehalten.
Das WordPress-Plugin „BohemianSuite Directory“ steht unter der [GPLv2 or later](https://www.gnu.org/licenses/gpl-2.0.html).
[Impressum](https://bohemiansuite.de/impressum/) · [Datenschutz](https://bohemiansuite.de/datenschutz/)
<!-- TODO: Nutzungsbedingungen/EULA verlinken, sobald vorhanden. -->

### Open-Source-Komponenten

BohemianSuite enthält Open-Source-Komponenten, unter anderem FFmpeg und LAME (LGPL) sowie PDFium.
Alle Lizenzhinweise findest du in **[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)** und in der App unter **Info → Open-Source-Lizenzen**.

Den Quellcode der mitgelieferten LGPL-Komponenten (FFmpeg, LAME) samt Build-Anleitung findest du unter
**[Quellcode der Drittkomponenten](https://github.com/trompetist91/bohemiansuite-releases/releases/tag/third-party-sources)**.
Fragen dazu: [bohemiansuite.de/kontakt](https://bohemiansuite.de/kontakt/)

Dieses Repository enthält ausschließlich die Installationsdateien, keinen Quellcode.
