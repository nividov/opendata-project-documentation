# Inhalt
- [Einleitung](#einleitung)
  * [Projektumfeld](#projektumfeld)
  * [Projektbegründung](#projektbegründung)
  * [Projektschnittstellen](#projektschnittstellen)
  * [Projektziel](#projektziel)


# Einleitung
## Projektumfeld
Das Modellunternehmen Future Technology Consulting GmbH ist im Security Bereich tätig und berät Unternehmen sowie Selbstständige bezüglich Ihrer Sicherheit sowohl im digitalen, als auch im analogen Bereich. Zu den Hauptaufgaben des Modellunternehmens Future Technology Consulting GmbH ist das entwickeln von verschiedenen Softwarelösungen mittels Opendata und visualisiert diese nach Kundenwunsch.

## Projektbegründung
Das Modellunternehmen Future Technology Consulting GmbH hat sich entschieden eine Software für Berliner Unternehmen zu entwickeln, die eine grafische Übersicht der verschiedenen Kriminalitätsfälle aller Berliner Bezirken darstellt.

## Projektschnittstellen
Für die Darstellungen von Berlin inklusive der einteilung in Bezirken wird D3.js verwendet. Diese liest die .geojson aus um die Bezirke in ihrer Form zu zeichnen.

Die daten werden aus einer .csv ausgelesen und mittels D3.js gefiltert und dargestellt.

Das Projekt wurde von dem Leiter der IT Abteilung und dem Chef genehmigt.

## Projektziel
Unser Kunde, ENTO Security KG, vertreibt verschiedenste Sicherheitstechnik für Mensch und Gebäude in und um Berlin. Das Unternehmen möchte eine Übersicht der Kriminalität in den berliner Bezirken um regionale Angebote anzupassen.

Das Ziel des Projekts ist es daher zusätzlich zu den bisherigen Kriminalitätsdaten eine übersichtliche Anwendung darzustellen. Dabei sollen die Daten durch verschiedene Kriterien gefiltert werden. Man soll die Möglichkeit haben sich nur bestimmte Kriterien anzeigen zu lassen, um das Ergebnis individueller filtern zu können. 

Die Anwendung soll jährliche Statistiken anzeigen lassen und somit einen Verlauf veranschaulichen. Die Darstellung erfolgt als interaktive Karte von Berlin und den einzelnen Bezirken innerhalb Berlins.  

## Ausgangslage
Die ENTO Security KG hat bisher immer auf sehr aufwändige Art und Weise die Kriminalitätsraten aus bestehenden Daten selbst für Berlin berechnet. Diese konnten weder gut gefiltert werden noch auf die einzelnen Bezirke eingegrenzt werden. Auf Grund der bisherigen Datenbeschaffung war es auch mühselig Vergleiche zum Vorjahr zu ziehen und einen Verlauf in den Kriminalitätsraten zu sehen. 

Daher suchte die ENTO Security KG nach einer übersichtlichen Anwendung um die bisherigen Daten darzustellen und zu filtern. Geünscht ist es auch sich die letzten Jahre anschauen zu können um diese besser miteinander vergleichen zu können. 