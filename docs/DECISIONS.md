# Decisions

Dieses Dokument sammelt kurze, nachvollziehbare Projektentscheidungen.

## Vorlage

```text
## YYYY-MM-DD - Titel der Entscheidung

Status: Proposed | Accepted | Superseded

Kontext:
- Warum muessen wir das entscheiden?

Entscheidung:
- Was wurde festgelegt?

Folgen:
- Was wird dadurch einfacher, schwieriger oder ausgeschlossen?
```

## 2026-03-17 - GitHub als zentrale Planungsebene

Status: Accepted

Kontext:
- Das Projekt braucht eine schlanke, gemeinsame Organisationsbasis.
- Planung soll ohne zusaetzliche Tool-Landschaft funktionieren.

Entscheidung:
- Projektplanung, Aufgabenverfolgung und Aenderungsdokumentation laufen primaer ueber GitHub.
- Dieses Repo dient als organisatorische Schicht zum Template- und spaeteren Code-Repo von `Neural Flight`.

Folgen:
- Issues und Pull Requests werden zur verbindlichen Arbeitsgrundlage.
- Zusatztools sind optional, aber nicht die Quelle der Wahrheit.
- Planung kann vom Produktcode getrennt gepflegt werden, ohne Kontext zu verlieren.

## 2026-03-17 - Dieses Repo ist Orga- und Wissensbasis, kein Code-Repo

Status: Accepted

Kontext:
- Fuer `Neural Flight` existiert ein eigenes fachliches Template- bzw. Code-Repo.
- Das Team braucht einen klar getrennten Ort fuer Aufgaben, Begriffe, Links, Tutorials und Richtlinien.

Entscheidung:
- Dieses Repo dient ausschliesslich der Organisation des Projekts.
- Inhalte wie Backlog, offene Fragen, Glossar, Tutorial-Ideen, Link-Sammlung und Code-Richtlinien werden hier gepflegt.

Folgen:
- Produktcode und technische Implementierung bleiben in separaten Repositories.
- Dieses Repo kann als gemeinsames Nachschlagewerk und Onboarding-Basis verwendet werden.
