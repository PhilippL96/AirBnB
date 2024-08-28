# Airbnb-Datenanalyse in Berlin - Tableau Dashboard

Dieses Projekt analysiert Buchungen und Bewertungen von Airbnbs in Berlin anhand von öffentlich verfügbaren Daten. Die Analyse wird durch verschiedene Dashboards in Tableau visualisiert, die verschiedene Aspekte der Airbnb-Daten darstellen.

## Projektstruktur

Der Projektordner enthält die folgenden Dateien:

- **Projekt_Airbnb.twbx**: Dies ist die Tableau-Projektdatei, die alle Dashboards und Visualisierungen enthält. Diese Datei kann direkt in Tableau geöffnet werden.

- **Zugehörige tbwr-Datei**: Diese Datei wird von Tableau automatisch generiert und speichert benutzerdefinierte Felder und Berechnungen. Sie wird im Hintergrund verwendet, wenn die Tableau-Projektdatei geöffnet wird.

## Dashboards

Die Tableau-Datei enthält folgende Dashboards:

1. **Geo-Dashboard**:
   - Visualisiert Airbnb-Daten nach Berliner Bezirken.
   - Eine Karte zeigt die Verteilung der Unterkünfte in Berlin.
   - Zusätzliche Visualisierungen zeigen (durchschnittliche) Preise, Verfügbarkeiten und weitere wichtige Kennzahlen nach Bezirken.

2. **Bewertungen**:
   - Analysiert die Anzahl der Bewertungen von Airbnbs anhand verschiedener Kriterien.
   - Kriterien sind u.a. Zimmertyp, Preis und weitere.

3. **Bewertungen über die Zeit**:
   - Ein großes Liniendiagramm zeigt die Entwicklung der Anzahl von Bewertungen im Laufe der Zeit.
   - Ermöglicht die Analyse von Trends und Veränderungen in der Anzahl der Bewertungen.

## Installation und Anwendung

Um das Dashboard auf Ihrem eigenen Rechner zu verwenden, folgen Sie diesen Schritten:

### Voraussetzungen

- **Tableau Desktop**: Um die Tableau-Projektdatei zu öffnen, benötigen Sie Tableau Desktop. Sie können eine kostenlose Testversion von der [offiziellen Tableau-Website](https://www.tableau.com/de-de) herunterladen.

### Datenbeschaffung

1. **Daten herunterladen**:
   - Besuchen Sie die Website [Inside Airbnb - Get the Data](http://insideairbnb.com/get-the-data/).
   - Scrollen Sie nach unten zur Tabelle mit den verfügbaren Daten.
   - Laden Sie die folgenden Datensätze für Berlin herunter:
     - **Listings**: Dies ist eine CSV-Datei (`listings.csv`), die detaillierte Informationen zu den Airbnb-Angeboten in Berlin enthält, einschließlich Angaben zu den Standorten, Preisen, Eigenschaften der Unterkünfte und vielem mehr.
     - **Reviews**: Dies ist eine CSV-Datei (`reviews.csv`), die Bewertungen von Gästen für die Airbnb-Angebote in Berlin enthält, einschließlich Informationen wie dem Bewertungsdatum, dem Text der Bewertung und den Bewertungskriterien.

2. **Dateien vorbereiten**:
   - Speichern Sie die heruntergeladenen Dateien `listings.csv` und `reviews.csv` im selben Verzeichnis wie die Tableau-Datei `Projekt_Airbnb.twbx`.

### Tableau-Projekt öffnen

1. **Tableau-Projekt öffnen**:
   - Doppelklicken Sie auf die Datei `Projekt_Airbnb.twbx`, um das Projekt in Tableau zu öffnen.
   - Tableau wird die zugehörigen Daten aus den CSV-Dateien automatisch laden.

2. **Dashboards anzeigen**:
   - Sobald das Projekt in Tableau geladen ist, können Sie durch die verschiedenen Dashboards navigieren und die Datenanalysen betrachten.
   - Verwenden Sie die Filter und interaktiven Elemente, um die Visualisierungen nach Ihren Wünschen anzupassen.

### Hinweise

- **Datenaktualisierung**: Wenn Sie die zugrunde liegenden CSV-Dateien aktualisieren (z.B. mit neueren Versionen von Inside Airbnb), können Sie das Tableau-Dashboard einfach aktualisieren, um die neuen Daten anzuzeigen.
- **Export**: Sie können die Dashboards als PDF oder Bild exportieren, indem Sie in Tableau auf `Datei > Exportieren` klicken.
