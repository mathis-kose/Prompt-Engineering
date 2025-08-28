# Prompt-Engineering
Meine Prompts, die ich für Coden etc. verwenden mag



1.  **Verwende Playgrounds statt der Consumer-Interfaces:** Nutze nicht die allgemeinen Chat-Oberflächen (wie `chat.openai.com` oder Claude). Verwende stattdessen die API-Playgrounds (z.B. `platform.openai.com`). Diese geben dir die volle Kontrolle über alle Parameter wie System-Prompt, Temperatur und Modellwahl und zeigen dir genau, wie das Modell arbeitet.

2.  **Kürze deine Prompts (Weniger ist mehr):** Die Leistung eines KI-Modells nimmt mit der Länge des Prompts ab. Lange, wortreiche Prompts führen zu ungenaueren Ergebnissen. Formuliere deine Anweisungen so kurz und informationsdicht wie möglich. Entferne alle Füllwörter und unnötigen Sätze.

3.  **Definiere das Ausgabeformat explizit:** Sage dem Modell genau, in welchem Format du die Ausgabe haben möchtest. Das ist entscheidend für die Automatisierung. Anstatt nur "gib mir eine Liste" zu sagen, fordere ein spezifisches Format an, wie z.B. **JSON**, **CSV** oder **Markdown**.

4.  **Sei unmissverständlich und spezifisch:** Vermeide vage Verben wie "produziere" oder "erstelle". Verwende stattdessen präzise Handlungsanweisungen wie "liste auf", "fasse zusammen", "übersetze", "schreibe neu". Je klarer deine Anweisung, desto geringer ist der Spielraum für Fehlinterpretationen durch die KI.

5.  **Gib Beispiele (One- oder Few-Shot-Prompting):** Die mit Abstand größte Leistungssteigerung erzielst du, indem du dem Modell Beispiele für die gewünschte Ausgabe gibst. Bereits ein einziges gutes Beispiel (**One-Shot**) ist effektiver als viele zusätzliche Anweisungen. Bei komplexen Aufgaben führen mehrere Beispiele (**Few-Shot**) zu noch besseren Ergebnissen.

6.  **Nutze die verschiedenen Rollen (System, User, Assistant):** Strukturiere deine Prompts in den Playgrounds klar:
    *   **System:** Definiert die übergeordnete Identität und die Grundregeln der KI (z.B. "Du bist ein hilfreicher Assistent").
    *   **User:** Enthält deine spezifischen Anweisungen und Aufgaben.
    *   **Assistant:** Hier kannst du Beispiele für ideale Antworten einfügen, um der KI zu zeigen, wie sie reagieren soll (für Few-Shot-Prompting).

7.  **Behandle LLMs als Konversations-Engines, nicht als Wissensdatenbanken:** Große Sprachmodelle sind hervorragend im Verstehen von Mustern, im logischen Schlussfolgern und im Führen von Gesprächen. Sie sind jedoch keine zuverlässigen Datenbanken für Fakten und können Fakten erfinden ("halluzinieren"). Verlasse dich nicht darauf, dass sie exakte, überprüfbare Informationen abrufen.

8.  **Iteriere und teste deine Prompts datengestützt:** Ein guter Prompt, der einmal funktioniert hat, kann beim nächsten Mal versagen. Anstatt dich auf dein Bauchgefühl zu verlassen, teste einen Prompt systematisch (z.B. 20 Mal mit verschiedenen Eingaben), verfolge die Erfolgsquote in einer Tabelle und vergleiche sie mit anderen Prompt-Varianten, um den zuverlässigsten zu finden.

9.  **Wähle das richtige Modell für die Aufgabe (Smart > Billig):** Beginne bei der Entwicklung eines Prompts immer mit dem intelligentesten und leistungsfähigsten verfügbaren Modell (z.B. GPT-4o statt GPT-4o mini). Die etwas höheren Kosten sind anfangs vernachlässigbar und sparen dir enorm viel Zeit, da das Modell deine Anweisungen besser versteht. Erst wenn der Prompt perfekt funktioniert, kannst du versuchen, für die Kostenoptimierung auf ein günstigeres Modell umzusteigen.

10. **Verwende das Wort "spartanisch" für einen prägnanten Ton:** Ein einfacher Trick für kurze, direkte und schnörkellose Antworten ist die Anweisung: "Verwende einen spartanischen Tonfall." Das Modell versteht diese Metapher sehr gut und reduziert die Ausgabe auf das Wesentliche.


---

***Anleitung-Generierung***

Erstelle mir eine sehr einfach zu folgende Schritt-für-Schritt-Anleitung. Sie soll selbst bei sehr schwacher Konzentration und völliger Übermüdung noch leicht verständlich sein. Es soll nur der nötigste Text mit den relevantesten Informationen enthalten sein.

Gehe nach der Erstellung die unten aufgeführte Checkliste durch und überprüfe jeden Punkt sorgfältig. Korrigiere mögliche Unstimmigkeiten.

**Thema der Anleitung:**




**Informationen zu Mir:**
Ich bin Elektrotechnik-Ingenieur mit einer kreativen Ader und arbeite gerne an persönlichen Technikprojekten. Ich möchte mich besser mit Informatik auskennen – insbesondere mit Themen wie GitHub, VS Code, Terminal-Nutzung, Linux und abstrakten Konzepten wie Softwarestrukturen.

Ich möchte dieses Wissen erwerben, damit es auf meinem Radar ist. In kreativen Phasen kann mein Gehirn dann neue Ideen entwickeln, weil es weiß, dass bestimmte Dinge mit diesen Technologien möglich sind – zumindest teilweise.


**Checkliste für die finale Überarbeitung:**

- Wurden die "Informationen zu Mir" in der Anleitung berücksichtigt?  
  → Falls nein, überarbeite die Informationsaufbereitung nochmal neu mit diesem Hintergrundwissen und unter diesem Aspekt.

- Sind die Übergänge zwischen den Anleitungsschritten nachvollziehbar?  
  → Falls nein, füge kleine Übergangskommentare oder Hinweise ein, z. B. *„Gehe zurück zum XY-Fenster“*.

- Wird zu viel Vorwissen vorausgesetzt?  
  → Besonders im Bereich Informatik: Ich code zwar gerne, komme aber aus der Elektrotechnik und habe weniger Erfahrung mit der fachgerechten Erstellung von Code.

- Ist der Text zu umfangreich, sodass ein ermüdetes Gehirn und überforderte Augen Schwierigkeiten haben könnten?  
  → Ziel ist es, dass alle Informationen schnell aufgenommen werden können, um zügig weiterzukommen.

- Wie kann das Lesen oder Verstehen der Anleitung so wenig Zeit wie möglich in Anspruch nehmen?

- Wurden alle Punkte der Checkliste berücksichtigt?

---












---
---
---
***Code-Überarbeitung***
***Code-Generierung & Optimierung***

**Ziel:** Erstellung von qualitativ hochwertigem, effizientem und sofort funktionsfähigem Code basierend auf einer spezifischen Problemanforderung. Die KI soll dabei maximalen Aufwand betreiben und eine strukturierte Herangehensweise nutzen.

**Dein spezifisches Coding-Problem:**

Code 1 Config Files, wenn dieser Punkt leer ist, dann einfach ignorieren :



Code 2 Der Hauptcode:


Mein Problem Thema:



**Informationen zu Deiner Umgebung und Präferenzen:**
Ich möchte unbedingt viel Redundante Sicherheit und User Experiance in allen meinen Codes haben.
Wenn eine doppelte Absicherung der Funktion möglich ist, dann möchte ich das immer im Notfall oder ungeplanten auftreten immer eine Fallbacklösung vorhanden ist.
Mir ist auch immer das Design sehr wichtig, da wie gesagt der Nutzer ein angenehmes Erlebnis haben soll, beim Stiel dann auch immer sích an Apples schlichem und guten Design orientieren.
Außerdem sollte alles was möglich ist mit Multithreading gelöst werden, und dabei auch immer streng auf eine saubere Mutex Infrastruktur geachtet werden,dass ist mir sehr wichtig.


**Anweisungen an die KI für die Bearbeitung:**

1.  **Verständnis & Planung:**
    *   Analysiere die Problembeschreibung und die Umgebungsinformationen sorgfältig. Stelle klärende Fragen, falls Aspekte unklar sind, *bevor* du mit der Implementierung beginnst.
    *   Erstelle einen detaillierten Plan, indem du das Problem und die Anforderungen in kleinere, logische Unteraufgaben zerlegst. Lege die Reihenfolge der Bearbeitung fest.

2.  **Iterative Implementierung & Überprüfung:**
    *   Arbeite die Unteraufgaben schrittweise ab.
    *   Nach jeder abgeschlossenen Unteraufgabe:
        *   **Überprüfe die Funktionalität:** Stelle sicher, dass der bisher erstellte Code korrekt funktioniert und die Teilaufgabe erfüllt.
        *   **Optimiere den Code:** Suche aktiv nach Verbesserungsmöglichkeiten hinsichtlich Lesbarkeit (z.B. klare Variablennamen, logische Struktur), Effizienz (Performance, Ressourcennutzung) und Einhaltung von Best Practices der jeweiligen Programmiersprache.
        *   **Teste den Code:** Implementiere (ggf. gedanklich oder durch kleine Testroutinen) Tests für die gerade entwickelte Funktionalität.

3.  **Maximale Anstrengung:**
    *   Nutze deine volle Verarbeitungskapazität, dein Wissen über Algorithmen, Datenstrukturen und Design Patterns, um den bestmöglichen Code zu generieren.
    *   Der Code soll nicht nur funktionieren, sondern auch robust, wartbar und gut dokumentiert sein.

4.  **Code-Lieferung:**
    *   Präsentiere den finalen Code klar strukturiert.
    *   Füge Kommentare im Code hinzu, die komplexe Abschnitte oder wichtige Entscheidungen erläutern.
    *   Gib ggf. eine kurze Anleitung zur Nutzung oder Integration des Codes.

**Checkliste für die KI vor der finalen Code-Auslieferung:**

- **Vollständigkeit:** Wurde das ursprüngliche Problem vollständig verstanden und alle expliziten sowie impliziten Anforderungen im Code adressiert?
- **Korrektheit:** Ist der Code logisch korrekt und frei von offensichtlichen Fehlern? Funktioniert er wie in der Problembeschreibung erwartet?
- **Robustheit:** Wurden mögliche Fehlerquellen und Grenzfälle bedacht und im Code behandelt (z.B. durch Fehlerbehandlung, Validierung von Eingaben)?
- **Effizienz:** Ist der Code unter Berücksichtigung der Problemstellung performant und ressourcenschonend? Gibt es unnötige Schleifen oder Berechnungen?
- **Lesbarkeit & Wartbarkeit:** Ist der Code klar strukturiert, gut formatiert und sind Variablennamen sowie Funktionsbezeichnungen aussagekräftig?
- **Planerfüllung:** Wurde der erstellte Plan (Unteraufgaben) vollständig abgearbeitet und jeder Schritt sorgfältig verifiziert und optimiert?
- **Dokumentation:** Sind ausreichende Kommentare im Code vorhanden? Ist eine externe Erklärung (falls nötig) klar und verständlich?
- **Kontextberücksichtigung:** Wurden die "Informationen zu Deiner Umgebung und Präferenzen" bei der Erstellung des Codes beachtet?
- **Selbstkritik:** Gibt es noch Aspekte des Codes, die verbessert werden könnten, auch wenn sie nicht explizit angefordert wurden? (Proaktive Optimierung)
- **Testabdeckung:** Wurden die Kernfunktionen gedanklich oder durch tatsächliche kleine Tests auf ihre Korrektheit geprüft?


---










---
---
---

# Lernen mit Google Gemini
 Einstellungen und Kontext

## 20 Wichtigste Aspekte für Gemini Prompt-Design

### 1. Klare und spezifische Anweisungen verwenden
Gemini funktioniert am besten mit präzisen, unzweideutigen Instruktionen. Vage Formulierungen führen zu unerwünschten Ergebnissen.

### 2. Input-Typen gezielt einsetzen
Unterscheiden zwischen: Fragen (Question Input), Aufgaben (Task Input), Entitäten (Entity Input) und partieller Vervollständigung (Completion Input).

### 3. Few-Shot Prompts bevorzugen
Zero-Shot Prompts (ohne Beispiele) sind weniger effektiv. Immer 2-3 konkrete Beispiele für gewünschte Ausgaben bereitstellen.

### 4. Constraints (Beschränkungen) definieren
Spezifizieren, was das Modell tun soll und was nicht. Länge, Format, Stil und inhaltliche Grenzen explizit festlegen.

### 5. Response-Format strukturiert vorgeben
Gewünschtes Ausgabeformat klar definieren: Tabelle, Liste, JSON, Absätze, etc. Format-Präfixe verwenden ("JSON:", "Tabelle:").

### 6. Completion-Strategie nutzen
Anstatt vollständige Anweisungen zu geben, den Anfang der gewünschten Antwort vorgeben und vom Modell vervollständigen lassen.

### 7. Optimale Anzahl von Beispielen wählen
2-5 Beispiele sind meist optimal. Zu wenige reduzieren Effektivität, zu viele führen zu Overfitting.

### 8. Positive Patterns statt Anti-Patterns
Zeigen, was getan werden soll, anstatt was vermieden werden sollte. Positive Beispiele sind effektiver.

### 9. Konsistente Formatierung in Beispielen
Alle Few-Shot Beispiele müssen identische Struktur, XML-Tags, Leerzeichen und Trennzeichen verwenden.

### 10. Kontextinformationen bereitstellen
Alle notwendigen Informationen in den Prompt einbetten, anstatt anzunehmen, dass Gemini alle Details kennt.

### 11. Präfixe strategisch einsetzen
Input-Präfixe ("Text:", "Frage:"), Output-Präfixe ("Antwort:", "JSON:") und Example-Präfixe für bessere Strukturierung.

### 12. Komplexe Prompts aufteilen
Bei komplexen Aufgaben: Instructions aufteilen, Prompt-Ketten erstellen oder parallele Verarbeitung mit Aggregation nutzen.

### 13. Temperature-Parameter anpassen
Niedrige Temperature (0-0.3) für deterministische Antworten, höhere (0.7-1.0) für kreative Ausgaben.

### 14. TopK und TopP Parameter optimieren
TopK begrenzt Wortauswahl, TopP kontrolliert kumulative Wahrscheinlichkeit. Standard TopP: 0.95.

### 15. Max Output Tokens definieren
Token-Limit basierend auf gewünschter Antwortlänge setzen (100 Tokens ≈ 60-80 Wörter).

### 16. Verschiedene Formulierungen testen
Identische Bedeutung, unterschiedliche Wortwahl kann verschiedene Ergebnisse liefern. Prompt-Variationen testen.

### 17. Analoge Aufgaben verwenden
Wenn direkte Instruktionen nicht funktionieren, ähnliche Aufgaben formulieren, die zum gleichen Ziel führen.

### 18. Content-Reihenfolge variieren
Reihenfolge von [Beispiele] [Kontext] [Input] kann Antwortqualität beeinflussen. Verschiedene Anordnungen testen.

### 19. Stop-Sequences definieren
Spezifische Zeichen oder Wörter festlegen, bei denen Gemini die Generierung stoppen soll.

### 20. Fallback-Strategien vorbereiten
Bei Safety-Filter-Auslösung Temperature erhöhen oder Prompt umformulieren. Faktische Genauigkeit nicht für komplexe Berechnungen erwarten.

## Einstellungen

## Optimale Gemini-Einstellungen für knappe Antworten:

**Parameter-Einstellungen:**
- **Temperature: 0-0.2** (deterministische, fokussierte Antworten)
- **Max Output Tokens: 50-150** (je nach gewünschter Länge)
- **TopP: 0.8** (statt Standard 0.95)
- **Stop Sequences:** "Zusammenfassend", "Darüber hinaus", "Außerdem"

**Prompt-Struktur:**
```
[KNAPP]: Antworte in maximal 2-3 Sätzen.
[AUFGABE]: [Deine konkrete Frage]
[FORMAT]: Nur die Kernaussage, keine Einleitung.

Beispiel:
Frage: Wie funktioniert Photosynthese?
Antwort: Pflanzen wandeln Licht + CO2 + Wasser in Glucose + Sauerstoff um.
```

**Effektive Prompt-Präfixe:**
- "Kurz:" / "Knapp:" / "Direkt:"
- "In einem Satz:"
- "Kernaussage:"
- "Nur das Wichtigste:"

## Persönlicher Kontext in Google AI Studio:

**System Instructions Bereich:** (meist oben in der Benutzeroberfläche)
```
Du bist mein Lern-Assistent. Antworte immer knapp und direkt.
Mein Hintergrund: [deine Expertise/Branche]
Meine Lernziele: [spezifische Themen]
Bevorzugter Stil: Bullet Points, kurze Sätze, keine Wiederholungen
```

**In den Model Parameters** kannst du diese Einstellungen als Standard speichern.

**Tipp:** Erstelle dir Prompt-Templates mit deinem Kontext, die du wiederverwenden kannst.












---
---
---
# Lern-Prompt für Schnittstellen lernen


## System Instructions (dauerhaft im AI Studio)
```
Du bist ein Lern-Assistent. Antworte immer in diesem Format:

KERNAUSSAGE: [1-2 prägnante Sätze mit der wichtigsten Information]
ERKLÄRUNG: [2-3 kurze Erklärungssätze]
SCHNITTSTELLEN: [Verwandte Themen als Titel-Liste]

*Erklärt Teil von:[für Benutzer leer lassen]*

Halte Antworten kurz und fokussiert. Keine Einleitungen oder Höflichkeitsfloskeln.

```

## Prompt-Template für Fragen
```
Frage: [Deine spezifische Frage]
Format: Kernaussage + Erklärung + Schnittstellen
```

## Beispiel-Anwendung
**Input:**
```
Frage: Wie funktioniert ein PID-Regler?
Format: Kernaussage + Erklärung + Schnittstellen
```

**Erwartete Ausgabe:**
```
KERNAUSSAGE: Ein PID-Regler kombiniert drei Regelanteile (P, I, D) zur optimalen Regelung.

ERKLÄRUNG: P-Anteil reagiert proportional auf Regelabweichung, I-Anteil eliminiert bleibende Abweichungen, D-Anteil dämpft Schwingungen durch Ableitung.

SCHNITTSTELLEN:
• Regelkreis-Grundlagen
• Übertragungsfunktionen  
• Einschwingverhalten
• Regler-Parametrierung
• Zeitkonstanten
• Störgrößenaufschaltung
```

## Einstellungen für AI Studio
- **Temperature:** 0.2 (fokussiert)
- **Max Output Tokens:** 2000
- **TopP:** 0.85
- **Stop Sequence:** "WEITERES:" (verhindert Abschweifen)

## Erweiterte Varianten

### Für Vertiefung:
```
Vertiefe: [Schnittstellen-Thema aus vorheriger Antwort]
Format: Kernaussage + Erklärung + Schnittstellen
```

### Für Zusammenhänge:
```
Verbindung: Wie hängen [Thema A] und [Thema B] zusammen?
Format: Kernaussage + Erklärung + Schnittstellen
```

### Für Anwendung:
```
Praxis: Wann/Wo wird [Thema] angewendet?
Format: Kernaussage + Anwendungsfälle + Schnittstellen
```

---

# Key-Takeaways Promp
```
EXTREME KEY TAKEAWAYS - NUR DAS ABSOLUTE MINIMUM

Analysiere den folgenden Text und extrahiere die 3-5 wichtigsten Kernaussagen. Jeder Punkt sollte:
- Maximal 1 Satz
- Nur das absolut Wesentliche
- Keine Füllwörter
- Keine Wiederholungen
- Fokus auf handlungsrelevante oder entscheidende Informationen

Format: Kurze, prägnante Bulletpoints

```

# Einleitung in technische Themen auch für Leihen
```
Write a business English introduction for [TECHNICAL TOPIC]. The target audience includes both technical professionals and non-technical stakeholders who need to understand the business relevance.

Requirements:
- Length: 150-250 words
- Start with a clear, jargon-free definition
- Explain the business value/impact in 2-3 sentences
- Include one concrete, relatable analogy or example
- End with a transition sentence that leads into the main article
- Use professional but accessible language (avoid heavy technical jargon)
- Structure: Definition → Business relevance → Practical example → Transition

Topic: [INSERT YOUR SPECIFIC TOPIC HERE]
Context: [Brief note about your industry/company if relevant]

```

# Umfangreiche technische Recherche

```

Stellen Sie eine umfassende technische Analyse von [THEMA EINFÜGEN] mit fundierten technischen Kenntnissen bereit. Strukturieren Sie die Antwort als dichten, informationsreichen, zusammenhängenden Text, der für die weitere KI-Verarbeitung geeignet ist.

Anforderungen:
1. **Technische Tiefe**: Erläutern Sie sowohl die allgemeinen Funktionsprinzipien als auch die zugrunde liegenden technischen Mechanismen auf Komponenten-/Physikebene.
2. **Struktur**: Folgen Sie einer logischen Abfolge – Grundprinzipien → Detaillierte Funktion → Implementierungsschritte  
3. **Mathematische Grundlagen**: Fügen Sie relevante Formeln mit klaren Erklärungen und ausgearbeiteten Beispielen hinzu.
4. **Priorität der Quellen**: Verwenden Sie IEEE-Publikationen, technische Dokumentationen und von Fachkollegen begutachtete technische Quellen.
5. **Qualität des Inhalts**: Vermeiden Sie Füllsätze – jeder Satz muss einen technischen Einblick oder ein technisches Verständnis vermitteln.
6. **Praktischer Kontext**: Fügen Sie Details zur Umsetzung in der Praxis und Überlegungen zum Design hinzu.

Konzentrieren Sie sich darauf, WARUM und WIE die Technologie auf grundlegender Ebene funktioniert. Erläutern Sie die physikalischen, elektrischen und technischen Prinzipien, die ihre Funktionsweise ermöglichen.

Thema: [IHR SPEZIFISCHES ELEKTROTECHNISCHES THEMA HIER EINFÜGEN]

```
