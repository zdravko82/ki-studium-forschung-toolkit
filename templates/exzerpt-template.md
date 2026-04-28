# Template: KI-gestütztes Exzerpt

Dieses Template erzeugt Exzerpte, die später in Literaturkapitel, Synthese-Tabellen oder Argumentationsstrukturen übernommen werden können.

## Prompt

```text
Ich gebe dir gleich Text aus einem Paper. Erstelle ein Exzerpt mit folgenden Feldern:

1. Vollständige Quelle: Autor, Jahr, Titel, Journal, DOI falls vorhanden. Falls unbekannt: „unbekannt“.
2. Forschungsfrage/Ziel: 1–2 Sätze.
3. Theorie/Begriffe: maximal 5 Stichpunkte.
4. Methode: Design, Daten, Stichprobe, Messung – 2–4 Stichpunkte.
5. Zentrale Ergebnisse: 3–6 Stichpunkte, keine Übertreibungen.
6. Limitationen: 2–4 Stichpunkte.
7. Relevanz für meine Forschungsfrage: [Forschungsfrage einfügen] – 1 Absatz.
8. Mögliche Zitat-Passage: Gib 2–3 kurze Sätze als sinngemäße Paraphrase und markiere deutlich „PARAPHRASE“. Keine wörtlichen Zitate erfinden.

Wenn Informationen im Text fehlen, schreibe „nicht im Auszug enthalten“.

Text:
[Text einfügen]
```

## Synthese-Tabelle als Folgeschritt

```text
Erstelle aus den folgenden Exzerpten eine Synthese-Tabelle:
Zeilen = Papers
Spalten = Theorieansatz | Methode | Hauptergebnis | Limitation | Beitrag zu meiner Frage | Widersprüche

Exzerpte:
[Exzerpte einfügen]
```
