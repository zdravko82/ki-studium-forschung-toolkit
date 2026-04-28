# Prompt-Debugging

Wenn eine KI-Antwort nicht passt, liegt es häufig an fehlendem Kontext, unklarer Aufgabe, falschem Format, Faktenunsicherheit oder unpassendem Stil.

## Zu wenig Kontext

```text
Antworte nur bezogen auf meinen Kontext: [Kontext]. Wenn wichtige Informationen fehlen, sage „Kontext fehlt“ und nenne die drei wichtigsten Infos, die du brauchst.
```

## Aufgabe zerlegen

```text
Zerlege die Aufgabe in fünf Schritte. Stelle pro Schritt eine Rückfrage und warte auf meine Antwort, bevor du fortfährst.
```

## Format erzwingen

```text
Gib die Antwort als Tabelle mit den Spalten: Begriff | Definition | Quelle-Platzhalter | Beispiel. Keine Fließtextantwort.
```

## Faktenunsicherheit markieren

```text
Markiere jede Aussage als Belegt, Plausibel oder Spekulation und nenne, was zur Verifikation nötig wäre.
```

## Stil korrigieren

```text
Schreibe im Stil wissenschaftlicher Prosa: präzise, neutral, keine Floskeln. Verwende kurze Sätze, Fachbegriffe sparsam und keine Metaphern.
```

## Selbstprüfung erzwingen

```text
Bewerte deine Antwort nach den Kriterien Richtigkeit, Vollständigkeit, Nachvollziehbarkeit, Quellenlage und Risiko von Überbehauptungen. Verbessere sie anschließend.
```
