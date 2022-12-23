# 📌 M346 PA :: Bildverkleinerung

Willkommen zu der offiziellen Dokumentation über unsere Projektarbeit für das Modul 346, Bildverkleinerung.

## Team

| Name      | Vorname |
| --------- | ------- |
| Pavlov    | Dalibor |
| Sabic     | Din     |
| Ruckstuhl | Pascal  |

## **Vorwort**

In diesem Projekt erarbeiten wir ein Program, welches zwei Buckets auf Amazon S3 einrichtet. Sobald dann ein Bild in den ersten Bucket hochgeladen wird, soll automatisch eine Lambda-Funktion ausgeführt werden, die das Bild verkleinert und in das zweite Bucket hochlädt.

## **Inhalt**

[🔹 Vorwort](#vorwort)
<br>
[🔹 Installation](#to-do)
<br>
[🔹 Benutzung](#benutzung)
<br>
[🔹 Schlusswort](#schlusswort)

### To-Do

- [x] Setup Script
- [x] Cleanup Script
- [ ] Upload Setup
- [ ] Run Script

### Vorwort

### Installation

Bitte stellen Sie sicher, dass Sie die folgenden Packages installiert haben:

> [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

> [jq](https://stedolan.github.io/jq/download/)

> zip
>
> ```sh
>  sudo apt install zip
> ```
>
> <br>

### Benutzung

Wenn Sie den AWS CLI und jq heruntergeladen installiert haben, sollten Sie das Program starten können. Wenn keine Fehlermeldungen hervortreten wurde das Program erfolgreich gestartet. Danach wird ein Cleanup durchgeführt mit der \_cleanup.sh Datei, die alle Buckets und Funktionen löscht, damit es keien weitere Probleme mehr gibt. Dann wird die \_setup.sh Datei ausgeführt, welche einige Schritte zum Einrichten einer Lambda-Funktion und einer Benachrichtigung für einen S3-Bucket durchführt. Danach können Sie Ihre Bildatei hochladen und diese sollte dann verkleinert werden.

### Schlusswort

Zum Abschluss möchten wir erwähnen, dass das Projekt nicht gelungen ist. Problem war, dass die Aufgabe für uns zu schwer war. Wir mussten viel recherchieren und haben Tools wie ChatGPT benutzt. Dann haben wir versucht mit der Klasse den Code zu vervollständigen, was auch nicht wirklich geklappt hat.

Jedoch denken wir, dass wir als Team gut harmoniert und die Aufgaben fair verteilt haben.
