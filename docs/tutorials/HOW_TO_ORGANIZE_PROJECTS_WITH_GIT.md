# So organisiere ich Projekte mit Git

Dieses Tutorial ist fuer absolute Beginner im Team gedacht.
Es zeigt, wie wir mit `Git` und `GitHub` zusammenarbeiten, ohne dass alles im Chaos endet.

## Ziel

Nach diesem Tutorial sollst du:

- verstehen, warum wir `Git` benutzen
- wissen, wie du ein Repo klonst und aktuell haeltst
- kleine Aenderungen in einem eigenen Branch machen koennen
- Pull Requests und Issues sinnvoll nutzen
- verstehen, wie unser Team damit Projekte organisiert

## Kurz gesagt: Was ist Git?

`Git` speichert Aenderungen an Dateien.
Du kannst damit sehen:

- was sich geaendert hat
- wer etwas geaendert hat
- wann etwas geaendert wurde
- auf welchem Stand du gerade arbeitest

`GitHub` ist die Plattform drumherum:

- Repositories
- Issues
- Pull Requests
- Review
- Doku

## Unser einfaches Team-Modell

So halten wir es einfach:

1. Eine Idee oder Aufgabe wird als Issue notiert.
2. Du holst dir das Repo lokal.
3. Du arbeitest in einem eigenen Branch.
4. Du machst kleine Commits.
5. Du erstellst einen Pull Request.
6. Nach Review wird gemerged.

## Wichtige Begriffe

- `clone`: ein Repo auf deinen Rechner holen
- `branch`: ein eigener Arbeitszweig fuer deine Aenderung
- `commit`: ein gespeicherter Schritt deiner Arbeit
- `push`: deine Commits zu GitHub hochladen
- `pull request`: Vorschlag, deine Aenderung ins Haupt-Repo zu uebernehmen
- `main`: der Hauptzweig des Repos

Mehr dazu steht auch in [`docs/GLOSSARY.md`](/Users/weigend/Documents/GitHub/onboarding-borrowed-senses/docs/GLOSSARY.md).

## Ein typischer Ablauf

### 1. Repo klonen

```bash
git clone <repo-url>
cd onboarding-borrowed-senses
```

Damit hast du das Repo lokal auf deinem Rechner.

### 2. Aktuellen Stand holen

Bevor du loslegst:

```bash
git checkout main
git pull
```

So startest du auf dem neuesten Stand.

### 3. Eigenen Branch anlegen

Arbeite nicht direkt auf `main`.

```bash
git checkout -b docs/add-git-tutorial
```

Guter Stil fuer Branchnamen:

- `docs/...` fuer Doku
- `feat/...` fuer neue Inhalte oder Features
- `fix/...` fuer Korrekturen

## 4. Dateien aendern

Mach deine Aenderung in kleinen, sinnvollen Schritten.
Zum Beispiel:

- Glossar erweitern
- eine neue Frage dokumentieren
- eine Aufgabe klarer formulieren
- ein Tutorial verbessern

## 5. Status pruefen

```bash
git status
```

Damit siehst du:

- welche Dateien geaendert sind
- welche Dateien neu sind
- was noch nicht committet wurde

## 6. Dateien zum Commit vormerken

```bash
git add README.md docs/TODO.md
```

Wenn du alles vormerken willst:

```bash
git add .
```

`git add .` ist okay, aber nur wenn du wirklich weisst, was gerade mitgeht.

## 7. Commit machen

```bash
git commit -m "docs: add git workflow notes"
```

Gute Commit-Messages sind:

- kurz
- konkret
- auf den Punkt

Beispiele:

- `docs: add glossary entry for OpenRouter`
- `docs: add questions page for onboarding`
- `chore: update issue templates`

## 8. Branch hochladen

```bash
git push -u origin docs/add-git-tutorial
```

Danach taucht dein Branch auf GitHub auf.

## 9. Pull Request erstellen

Auf GitHub erstellst du dann einen Pull Request.

Wichtig dabei:

- kurz sagen, was du geaendert hast
- das passende Issue verlinken
- offene Fragen nennen

## 10. Review einarbeiten

Wenn jemand Feedback gibt:

- Aenderung lokal machen
- wieder `git add`
- wieder `git commit`
- nochmal `git push`

Der Pull Request aktualisiert sich dann automatisch.

## Unsere Teamregeln dazu

- Keine Arbeit direkt auf `main`
- Lieber kleine Pull Requests als riesige Monster-PRs
- Erst Issue oder Frage festhalten, dann losbauen
- Doku mitpflegen, wenn sich Arbeitsweise aendert
- Unklare Begriffe direkt ins Glossar packen

## Typische Mini-Workflows

### Eine Frage dokumentieren

1. `main` aktualisieren
2. neuen Branch anlegen
3. Eintrag in [`docs/QUESTIONS.md`](/Users/weigend/Documents/GitHub/onboarding-borrowed-senses/docs/QUESTIONS.md) machen
4. committen
5. Pull Request erstellen

### Eine Aufgabe anlegen

1. GitHub Issue mit Template erstellen
2. optional Eintrag in [`docs/TODO.md`](/Users/weigend/Documents/GitHub/onboarding-borrowed-senses/docs/TODO.md) ergaenzen
3. wenn noetig Doku im Repo anpassen

### Einen Begriff erklaeren

1. Begriff in [`docs/GLOSSARY.md`](/Users/weigend/Documents/GitHub/onboarding-borrowed-senses/docs/GLOSSARY.md) eintragen
2. kurz sagen, warum er im Projekt wichtig ist
3. Pull Request erstellen

## Was du am Anfang vermeiden solltest

- direkt auf `main` arbeiten
- zu viele verschiedene Themen in einen Commit packen
- Dateien aendern, ohne zu wissen warum
- Chatwissen nicht zu dokumentieren
- Pull Requests ohne Beschreibung anlegen

## Wenn du nicht weiterkommst

Dann bitte nicht raten.
Mach stattdessen eins von diesen Dingen:

- Frage in [`docs/QUESTIONS.md`](/Users/weigend/Documents/GitHub/onboarding-borrowed-senses/docs/QUESTIONS.md) eintragen
- im Team nachfragen
- ein kleines Draft-PR anlegen
- im Issue schreiben, wo du haengst

## Nacher

Wenn du dieses Tutorial einmal sauber durchgespielt hast, bist du bereit fuer:

- Issues sinnvoll anlegen
- kleine Doku-PRs machen
- im Team an einem Repo arbeiten
- spaeter auch am Produkt-Repo mitarbeiten
