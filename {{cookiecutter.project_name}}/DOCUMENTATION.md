# Einführung und Ziele

## Aufgabenstellung

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

### Zweck

- Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
- Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Stakeholder

| Rolle                         | Kontakt             | Erwartungshaltung   |
|-------------------------------|---------------------|---------------------|
| **Geschäftsführung**           | *Max Mustermann*    | *\<Erwartung-1>*    |
| **Technical Consulting**       | *Anna Beispiel*     | *\<Erwartung-2>*    |
| **Fleet Operating Center**     | *John Doe*          | *\<Erwartung-2>*    |
| **X-Abteilung**                | *Lisa Musterfrau*   | *\<Erwartung-2>*    |
| **ZT-Abteilung**               | *Peter Beispielmann*| *\<Erwartung-2>*    |


# Qualitätsziele

## 1. Nicht-funktionale Anforderungen

### 1.1 Leistung

- Anforderungen:
- Metriken/Benchmarks:

### 1.2 Zuverlässigkeit

- Anforderungen:
- Metriken/Benchmarks:

### 1.3 Sicherheit

- Anforderungen:
- Compliance:

### 1.4 Benutzerfreundlichkeit

### 1.5 Wartbarkeit

- Anforderungen:

### 1.6 Portabilität

- Anforderungen:

## 2. Priorisierung der Qualitätsziele

In dieser frühen Prototypen-Phase liegt der Fokus auf dem Erreichen der funktionalen Anforderungen.
Nicht-funktionale Anforderungen werden erst in der nächste Phase relevant.

# Randbedingungen

## 3.1 Technologien

### Programmiersprachen

- **Python**

### Frontend-Technologien

- Technologie Beispiel A

### Backend-Technologien

- **Kedro**: Eingesetzt zur Datenverarbeitung und -modellierung, um einen strukturierten und wiederholbaren Workflow zu gewährleisten.

### Datenbanken

- Production DB: SQL
- Training: Data Export

### Hosting und Infrastruktur

- **AWS**: Genutzt für das Hosting.

### Versionierung

- **Trunk-basierte Entwicklung**

### CI/CD

- **Pre-Commit Hooks mit ruff**: Eingesetzt zur kontinuierlichen Integration und Deployment, um die Codequalität und Funktionalität vor jedem Commit zu überprüfen.

### Weitere Tools

- **Docker**: Genutzt zur Bereitstellung der Modellierung in AWS.

## 3.2 Bestehende Systeme

### System A

- Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.

### System B

- At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

# Kontextabgrenzung

## Fachlicher Kontext

**\<Diagramm und/oder Tabelle>**

**\<optional: Erläuterung der externen fachlichen Schnittstellen>**

## Technischer Kontext

**\<Diagramm oder Tabelle>**

**\<optional: Erläuterung der externen technischen Schnittstellen>**

**\<Mapping fachliche auf technische Schnittstellen>**

# Lösungsstrategie

# Bausteinsicht

## Whitebox Gesamtsystem

***\<Übersichtsdiagramm>***

Begründung

:   *\<Erläuternder Text>*

Enthaltene Bausteine

:   *\<Beschreibung der enthaltenen Bausteine (Blackboxen)>*

Wichtige Schnittstellen

:   *\<Beschreibung wichtiger Schnittstellen>*

### \<Name Blackbox 1>

*\<Zweck/Verantwortung>*

*\<Schnittstelle(n)>*

*\<(Optional) Qualitäts-/Leistungsmerkmale>*

*\<(Optional) Ablageort/Datei(en)>*

*\<(Optional) Erfüllte Anforderungen>*

*\<(optional) Offene Punkte/Probleme/Risiken>*

### \<Name Blackbox 2>

*\<Blackbox-Template>*

### \<Name Blackbox n>

*\<Blackbox-Template>*

### \<Name Schnittstelle 1>

...

### \<Name Schnittstelle m>

## Ebene 2

### Whitebox *\<Baustein 1>*

*\<Whitebox-Template>*

### Whitebox *\<Baustein 2>*

*\<Whitebox-Template>*

...

### Whitebox *\<Baustein m>*

*\<Whitebox-Template>*

## Ebene 3

### Whitebox \<\_Baustein x.1\_\>

*\<Whitebox-Template>*

### Whitebox \<\_Baustein x.2\_\>

*\<Whitebox-Template>*

### Whitebox \<\_Baustein y.1\_\>

*\<Whitebox-Template>*

# Laufzeitsicht

## *\<Bezeichnung Laufzeitszenario 1>*

-   \<hier Laufzeitdiagramm oder Ablaufbeschreibung einfügen>

-   \<hier Besonderheiten bei dem Zusammenspiel der Bausteine in diesem
    Szenario erläutern>

## *\<Bezeichnung Laufzeitszenario 2>*

...

## *\<Bezeichnung Laufzeitszenario n>*

...

# Verteilungssicht

## Infrastruktur Ebene 1

***\<Übersichtsdiagramm>***

Begründung

:   *\<Erläuternder Text>*

Qualitäts- und/oder Leistungsmerkmale

:   *\<Erläuternder Text>*

Zuordnung von Bausteinen zu Infrastruktur

:   *\<Beschreibung der Zuordnung>*

## Infrastruktur Ebene 2

### *\<Infrastrukturelement 1>*

*\<Diagramm + Erläuterungen>*

### *\<Infrastrukturelement 2>*

*\<Diagramm + Erläuterungen>*

...

### *\<Infrastrukturelement n>*

*\<Diagramm + Erläuterungen>*

# Querschnittliche Konzepte

## *\<Konzept 1>*

*\<Erklärung>*

## *\<Konzept 2>*

*\<Erklärung>*

...

## *\<Konzept n>*

*\<Erklärung>*

# Architekturentscheidungen

# Modellierungsentscheidungen

- Warum haben wir uns für diese Modellansätze entschieden?
- Welche haben wir erwägt und aus welchen Gründen nicht verfolgt?
- Welche Daten haben wir einbezogen, welche nicht, und warum?

# Risiken und technische Schulden

# Glossar

| Begriff               | Definition                                    |
|-----------------------|-----------------------------------------------|
| *\<Begriff-1>*        | *\<Definition-1>*                             |
| *\<Begriff-2>*        | *\<Definition-2>*                             |

# Lizenz
Based on the arc42 template, by Dr. Peter Hruschka, Dr. Gernot Starke and contributiors. Siehe <https://arc42.org>