# Einführung und Ziele {#section-introduction-and-goals}

## Aufgabenstellung {#_aufgabenstellung}

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

### Zweck

- Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua.
- Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
- Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

## Stakeholder {#_stakeholder}

| Rolle                         | Kontakt             | Erwartungshaltung   |
|-------------------------------|---------------------|---------------------|
| **Geschäftsführung**           | *Max Mustermann*    | *\<Erwartung-1>*    |
| **Technical Consulting**       | *Anna Beispiel*     | *\<Erwartung-2>*    |
| **Fleet Operating Center**     | *John Doe*          | *\<Erwartung-2>*    |
| **X-Abteilung**                | *Lisa Musterfrau*   | *\<Erwartung-2>*    |
| **ZT-Abteilung**               | *Peter Beispielmann*| *\<Erwartung-2>*    |


# Qualitätsziele {#_qualit_tsziele}

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

# Randbedingungen {#section-architecture-constraints}

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

# Kontextabgrenzung {#section-system-scope-and-context}

## Fachlicher Kontext {#_fachlicher_kontext}

**\<Diagramm und/oder Tabelle>**

**\<optional: Erläuterung der externen fachlichen Schnittstellen>**

## Technischer Kontext {#_technischer_kontext}

**\<Diagramm oder Tabelle>**

**\<optional: Erläuterung der externen technischen Schnittstellen>**

**\<Mapping fachliche auf technische Schnittstellen>**

# Lösungsstrategie {#section-solution-strategy}

# Bausteinsicht {#section-building-block-view}

## Whitebox Gesamtsystem {#_whitebox_gesamtsystem}

***\<Übersichtsdiagramm>***

Begründung

:   *\<Erläuternder Text>*

Enthaltene Bausteine

:   *\<Beschreibung der enthaltenen Bausteine (Blackboxen)>*

Wichtige Schnittstellen

:   *\<Beschreibung wichtiger Schnittstellen>*

### \<Name Blackbox 1> {#__name_blackbox_1}

*\<Zweck/Verantwortung>*

*\<Schnittstelle(n)>*

*\<(Optional) Qualitäts-/Leistungsmerkmale>*

*\<(Optional) Ablageort/Datei(en)>*

*\<(Optional) Erfüllte Anforderungen>*

*\<(optional) Offene Punkte/Probleme/Risiken>*

### \<Name Blackbox 2> {#__name_blackbox_2}

*\<Blackbox-Template>*

### \<Name Blackbox n> {#__name_blackbox_n}

*\<Blackbox-Template>*

### \<Name Schnittstelle 1> {#__name_schnittstelle_1}

...

### \<Name Schnittstelle m> {#__name_schnittstelle_m}

## Ebene 2 {#_ebene_2}

### Whitebox *\<Baustein 1>* {#_whitebox_emphasis_baustein_1_emphasis}

*\<Whitebox-Template>*

### Whitebox *\<Baustein 2>* {#_whitebox_emphasis_baustein_2_emphasis}

*\<Whitebox-Template>*

...

### Whitebox *\<Baustein m>* {#_whitebox_emphasis_baustein_m_emphasis}

*\<Whitebox-Template>*

## Ebene 3 {#_ebene_3}

### Whitebox \<\_Baustein x.1\_\> {#_whitebox_baustein_x_1}

*\<Whitebox-Template>*

### Whitebox \<\_Baustein x.2\_\> {#_whitebox_baustein_x_2}

*\<Whitebox-Template>*

### Whitebox \<\_Baustein y.1\_\> {#_whitebox_baustein_y_1}

*\<Whitebox-Template>*

# Laufzeitsicht {#section-runtime-view}

## *\<Bezeichnung Laufzeitszenario 1>* {#__emphasis_bezeichnung_laufzeitszenario_1_emphasis}

-   \<hier Laufzeitdiagramm oder Ablaufbeschreibung einfügen>

-   \<hier Besonderheiten bei dem Zusammenspiel der Bausteine in diesem
    Szenario erläutern>

## *\<Bezeichnung Laufzeitszenario 2>* {#__emphasis_bezeichnung_laufzeitszenario_2_emphasis}

...

## *\<Bezeichnung Laufzeitszenario n>* {#__emphasis_bezeichnung_laufzeitszenario_n_emphasis}

...

# Verteilungssicht {#section-deployment-view}

## Infrastruktur Ebene 1 {#_infrastruktur_ebene_1}

***\<Übersichtsdiagramm>***

Begründung

:   *\<Erläuternder Text>*

Qualitäts- und/oder Leistungsmerkmale

:   *\<Erläuternder Text>*

Zuordnung von Bausteinen zu Infrastruktur

:   *\<Beschreibung der Zuordnung>*

## Infrastruktur Ebene 2 {#_infrastruktur_ebene_2}

### *\<Infrastrukturelement 1>* {#__emphasis_infrastrukturelement_1_emphasis}

*\<Diagramm + Erläuterungen>*

### *\<Infrastrukturelement 2>* {#__emphasis_infrastrukturelement_2_emphasis}

*\<Diagramm + Erläuterungen>*

...

### *\<Infrastrukturelement n>* {#__emphasis_infrastrukturelement_n_emphasis}

*\<Diagramm + Erläuterungen>*

# Querschnittliche Konzepte {#section-concepts}

## *\<Konzept 1>* {#__emphasis_konzept_1_emphasis}

*\<Erklärung>*

## *\<Konzept 2>* {#__emphasis_konzept_2_emphasis}

*\<Erklärung>*

...

## *\<Konzept n>* {#__emphasis_konzept_n_emphasis}

*\<Erklärung>*

# Architekturentscheidungen {#section-design-decisions}

# Modellierungsentscheidungen {#section-model-decisions}

- Warum haben wir uns für diese Modellansätze entschieden?
- Welche haben wir erwägt und aus welchen Gründen nicht verfolgt?
- Welche Daten haben wir einbezogen, welche nicht, und warum?

# Risiken und technische Schulden {#section-technical-risks}

# Glossar {#section-glossary}

| Begriff               | Definition                                    |
|-----------------------|-----------------------------------------------|
| *\<Begriff-1>*        | *\<Definition-1>*                             |
| *\<Begriff-2>*        | *\<Definition-2>*                             |

# Lizenz {#license}
Based on the arc42 template, by Dr. Peter Hruschka, Dr. Gernot Starke and contributiors. Siehe <https://arc42.org>