# Neural Flight Organization

Das ist unser Orga-Repo fuer `Neural Flight`.

`Neural Flight` ist ein Studi-Projekt.
Das eigentliche Produkt und der Anwendungscode liegen in anderen Repos.

Hier sammeln wir vor allem:

- Aufgaben und Backlog
- offene Fragen
- Glossar fuer Begriffe und Tools
- Ideen fuer Tutorials und Lehrmaterial
- Links und Referenzen
- Code-Richtlinien und Arbeitsregeln

## Overview

Die fachliche Vorlage liegt im Template-Repo:

- [`dweigend/neural-flight-template`](https://github.com/dweigend/neural-flight-template)

Dieses Repo hier begleitet das nur organisatorisch.

## Purpose

Dieses Repo ist bewusst nur fuer Organisation da.
Es ist unser gemeinsamer Ort fuer Planung, Orientierung, Wissenssammlung und Standards.

Was hier rein gehoert:

- Aufgaben, To-dos und GitHub-Issues
- offene Fragen und Klaerungsbedarf
- Begriffsdefinitionen und Tool-Erklaerungen
- Tutorial-Ideen und Onboarding-Material
- wichtige Projektlinks
- Repo-, Git- und Team-Richtlinien

Was hier nicht rein gehoert:

- eigentliche Produktimplementierung
- Experimente im Anwendungscode
- Feature-Planung im Detail, wenn sie nur das Produkt betrifft
- technische Code-Aenderungen

## Repository Guide

Die wichtigsten Einstiegsdokumente:

- [`AGENTS.md`](AGENTS.md) fuer die wichtigsten Spielregeln
- [`docs/TODO.md`](docs/TODO.md) fuer Aufgaben und Backlog
- [`docs/QUESTIONS.md`](docs/QUESTIONS.md) fuer offene Fragen
- [`docs/GLOSSARY.md`](docs/GLOSSARY.md) fuer Begriffe wie `OpenRouter`, `Git`, `OpenCode` und `Zed`
- [`docs/TUTORIAL_IDEAS.md`](docs/TUTORIAL_IDEAS.md) fuer Lehr- und Tutorial-Ideen
- [`docs/tutorials/HOW_TO_ORGANIZE_PROJECTS_WITH_GIT.md`](docs/tutorials/HOW_TO_ORGANIZE_PROJECTS_WITH_GIT.md) fuer den Git-Workflow im Team
- [`docs/LINKS.md`](docs/LINKS.md) fuer wichtige Projektlinks
- [`docs/CODE_GUIDELINES.md`](docs/CODE_GUIDELINES.md) fuer Repo-, Git- und Review-Regeln
- [`docs/DECISIONS.md`](docs/DECISIONS.md) fuer Entscheidungen
- [`docs/templates/`](docs/templates/TASK_TEMPLATE.md) fuer lokale Vorlagen im geklonten Repo

## Workflow

Die Grundregel: Alles, was Orga-Arbeit erzeugt, bekommt ein GitHub-Issue.

- Groessere Orga-Vorhaben werden als `Feature` oder `Epic` angelegt.
- Konkrete Orga-Arbeitspakete laufen als `Task`.
- Fehler oder Blocker in Prozessen, Doku oder Setup laufen als `Bug`.
- Aenderungen an Orga-Dokumenten laufen ueber Pull Requests und referenzieren die passenden Issues.
- Wichtige Architektur- oder Prozessentscheidungen landen zusaetzlich im Decision Log.
- Offene Fragen werden in [`docs/QUESTIONS.md`](docs/QUESTIONS.md) gesammelt.

## Working Style

1. Idee oder Bedarf identifizieren.
2. Passendes Issue mit Template anlegen.
3. Prioritaet und naechsten Schritt festhalten.
4. Umsetzung in kleinem, nachvollziehbarem Pull Request.
5. Entscheidung oder Erkenntnis bei Bedarf in [`docs/DECISIONS.md`](docs/DECISIONS.md) dokumentieren.

## Issue Labels

Fuer GitHub Issues reicht zum Start dieses Set:

- `type:task`
- `type:feature`
- `type:bug`
- `priority:high`
- `priority:medium`
- `priority:low`
- `area:teaching`
- `area:experience`
- `area:infrastructure`
- `area:tooling`
- `blocked`

## Backlog

Der echte Arbeitsstand liegt in GitHub Issues.
Als schnelle Uebersicht nutzen wir zusaetzlich [`docs/TODO.md`](docs/TODO.md).

Empfohlene Statuslogik:

- `Inbox`: Idee ist notiert, aber noch nicht geschnitten
- `Ready`: ausreichend klar, kann umgesetzt werden
- `In Progress`: aktiv in Arbeit
- `Blocked`: haengt von externer Entscheidung oder Abhaengigkeit ab
- `Done`: erledigt und dokumentiert

## Contents

Dieses Repo deckt vor allem diese Dinge ab:

- Aufgabenmanagement
- Fragensammlung und Klaerungsbedarf
- Wissenssammlung und Glossar
- Onboarding und Tutorial-Planung
- Link-Sammlung
- Team-, Repo- und Git-Konventionen

## Included

Schon drin:

- `AGENTS.md` als gemeinsame Regelbasis
- `README` als Einstiegspunkt
- Issue-Templates fuer Tasks, Features und Bugs
- lokale Markdown-Templates fuer Aufgaben, Fragen, Glossar, Tutorials und Links
- Pull-Request-Template
- einfache To-do-Uebersicht
- Fragensammlung
- Decision Log fuer wichtige Projektentscheidungen

## Tutorials

Im Produkt-Repo liegen bereits Beginner-Tutorials fuer Setup und Einstieg.
Dieses Orga-Repo ergaenzt sie nur um Organisations-, Team- und Git-Workflows.

- Template-Tutorials: https://github.com/dweigend/neural-flight-template/tree/main/tutorials
- Git-Teamtutorial: [`docs/tutorials/HOW_TO_ORGANIZE_PROJECTS_WITH_GIT.md`](docs/tutorials/HOW_TO_ORGANIZE_PROJECTS_WITH_GIT.md)

## Next Steps

- Glossar gemeinsam vervollstaendigen
- offene Fragen zentral sammeln
- Tutorial-Liste mit Prioritaeten versehen
- Link-Sammlung mit den wichtigsten Tools und Repos fuellen
- Code-Richtlinien auf den Stack im Template-Repo zuschneiden
- erste 5 bis 10 Organisations-Issues aus [`docs/TODO.md`](docs/TODO.md) erstellen

## Repository-Struktur

```text
.
├── AGENTS.md
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/
│   ├── CODE_GUIDELINES.md
│   ├── DECISIONS.md
│   ├── GLOSSARY.md
│   ├── LINKS.md
│   ├── QUESTIONS.md
│   ├── TUTORIAL_IDEAS.md
│   ├── TODO.md
│   ├── templates/
│   └── tutorials/
└── README.md
```
