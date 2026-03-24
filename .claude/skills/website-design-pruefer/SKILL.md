---
name: website-design-prüfer
description: >
  Automatische Design- und SEO-Prüfung für Websites. Wird bei JEDER Website-Änderung aktiv – 
  ob der Nutzer JSX/HTML/CSS-Code zeigt, eine Seite beschreibt, ein Redesign anfordert oder 
  Feedback zu einem Website-Entwurf will. Triggert auch bei Begriffen wie "prüfe die Seite", 
  "was kann ich verbessern", "SEO-Check", "Design-Feedback", "ist das gut so", "stimmt das Layout", 
  "website review", "Verbesserungsvorschläge", oder wenn der Nutzer eine .jsx/.html/.css-Datei 
  hochlädt oder Code einfügt der eine Website darstellt. Der Skill prüft Design-Qualität 
  (Ästhetik, Tiefe, Proportionen, Farbharmonie, Typografie) und SEO (Keywords, Schema-Markup, 
  H-Tag-Struktur, lokale SEO-Signale, Core Web Vitals Risiken) und gibt priorisierte, 
  umsetzbare Verbesserungsvorschläge. Standardmäßig optimiert für Delluxe-Dellen GmbH 
  (PDR/Beulendoktor, Eichenau bei München), aber universell anpassbar für jede Website.
---

# Website Design & SEO Prüfer

## Wann dieser Skill aktiv wird

Führe diese Prüfung AUTOMATISCH durch, wenn:
- Der Nutzer Website-Code zeigt (JSX, HTML, CSS, React-Komponenten)
- Der Nutzer eine Änderung an einer Website vornimmt und das Ergebnis präsentiert
- Der Nutzer nach Feedback, Review oder Verbesserungen für eine Website fragt
- Der Nutzer Begriffe wie "prüfe", "check", "verbessern", "SEO", "Design-Feedback" nutzt
- Der Nutzer eine Website-Datei hochlädt oder einfügt

## Ablauf der Prüfung

Bei jeder Website-Änderung führst du folgende Prüfung durch und präsentierst die Ergebnisse strukturiert.

### Schritt 1: Kontext erkennen

Prüfe, ob Firmendaten bekannt sind. Falls nicht explizit anders angegeben, nutze den Delluxe-Dellen Standard:

**Delluxe-Dellen GmbH (Standard-Kontext):**
- Branche: PDR / Lackfreie Dellenreparatur / Beulendoktor
- Standort: Ringstraße 19, 82223 Eichenau bei München
- Markenfarbe Grün: #6ccc43
- Zielkeywords: "Dellenentfernung München", "Beulendoktor Eichenau", "Hagelschaden Reparatur München", "Smart Repair München", "Mobiler Beulendoktor München"
- USPs: Meisterbetrieb seit 2012, eigene PV-Anlage, 100% E-Autoflotte, digitale Abwicklung (PDR-Cloud), Google-Bewertung 5.0
- Telefon Festnetz: 08141 XXX XXX (Platzhalter bis echte Nummer bekannt)
- Zielgruppe: Privatkunden, Autohäuser, Flotten, Leasinggesellschaften, Versicherungen

Falls der Nutzer für eine ANDERE Website prüft, frage nach den relevanten Daten (Branche, Standort, Zielkeywords, Markenfarben) oder extrahiere sie aus dem gezeigten Code.

### Schritt 2: Design-Prüfung

Prüfe den Code oder die Beschreibung gegen diese Kriterien. Vergib für jeden Bereich eine Bewertung: ✅ Gut | ⚠️ Verbesserbar | ❌ Problem

**A. Visuelle Hierarchie & Typografie**
- Gibt es eine klare H1 → H2 → H3 Abstufung?
- Sind Schriftgrößen proportional und lesbar (min. 16px Fließtext)?
- Ist der Kontrast zwischen Headline und Hintergrund ausreichend?
- Werden maximal 2 Schriftfamilien verwendet?

**B. Farbharmonie & Branding**
- Wird die Markenfarbe konsistent eingesetzt?
- Stimmen die Grüntöne im Code mit dem Logo-Grün (#6ccc43 bei Delluxe) überein?
- Gibt es genug Kontrast zwischen Text und Hintergrund (WCAG AA: min. 4.5:1)?
- Werden Farben sparsam und gezielt als Akzente eingesetzt?

**C. Tiefe & Atmosphäre**
- Gibt es Layering (Overlays, Shadows, Glasmorphism)?
- Werden Licht-Effekte sinnvoll eingesetzt (Glows, Gradienten)?
- Hat das Layout genug "Luft" (Whitespace/Padding)?
- Wirkt die Seite dreidimensional oder flach?

**D. Layout & Responsiveness**
- Gibt es Media Queries für Mobile (< 820px)?
- Sind Touch-Targets groß genug (min. 44px)?
- Bricht das Grid sinnvoll auf mobile Spalten um?
- Sind Bilder responsiv (max-width: 100%, object-fit)?

**E. Bildsprache & Hero**
- Ist das Hero-Bild groß genug und hochwertig?
- Gibt es einen sauberen Übergang (Gradient-Fade) vom Bild zum Inhalt?
- Werden Stockfotos vermieden zugunsten echter Firmenfotografie?
- Haben Bilder ausreichend Kontrast zur darüber liegenden Schrift?

### Schritt 3: SEO-Prüfung

**A. H-Tag-Struktur**
- Gibt es genau EINEN H1-Tag pro Seite?
- Enthält der H1 das primäre Zielkeyword?
- Folgen H2/H3 einer logischen Hierarchie?
- Warnung: Dekorative Headlines sollten keine H-Tags sein

**B. Keyword-Integration**
- Ist das primäre Keyword im H1 enthalten?
- Erscheinen sekundäre Keywords in H2-Tags?
- Sind Keywords natürlich in den Fließtext integriert (nicht gestopft)?
- Enthält die Seite ortsbezogene Keywords (z.B. "München", "Eichenau")?

**C. Schema-Markup**
- Ist LocalBusiness / AutoBodyShop Schema vorhanden?
- Sind Öffnungszeiten, Adresse, Telefon im Schema?
- Gibt es FAQ-Schema auf FAQ-Seiten?
- Gibt es AggregateRating im Schema?

**D. Technische SEO-Signale**
- Haben alle Bilder beschreibende Alt-Texte mit Keywords?
- Gibt es aria-labels für Accessibility?
- Werden semantische HTML-Tags verwendet (section, article, nav, footer)?
- Ist die Seite für Core Web Vitals optimiert (keine Layout-Shifts, effiziente Bilder)?

**E. Lokale SEO**
- Erscheinen Stadtname und Region auf der Seite?
- Ist die vollständige NAP-Angabe (Name, Adresse, Phone) im Footer?
- Gibt es einen Link zum Google Business Profil?
- Sind die Einzugsgebiete erwähnt?

### Schritt 4: Ergebnis-Report

Präsentiere die Ergebnisse in diesem Format:

```
══════════════════════════════════════
  WEBSITE DESIGN & SEO PRÜFBERICHT
══════════════════════════════════════

📐 DESIGN-SCORE: X/10
🔍 SEO-SCORE: X/10

── DESIGN ──────────────────────────

✅ [Bereich]: [Was gut ist]
⚠️ [Bereich]: [Was verbessert werden sollte]
❌ [Bereich]: [Was dringend gefixt werden muss]

── SEO ─────────────────────────────

✅ [Bereich]: [Was gut ist]
⚠️ [Bereich]: [Was verbessert werden sollte]
❌ [Bereich]: [Was dringend gefixt werden muss]

── TOP 3 PRIORITÄTEN ───────────────

1. [Wichtigste Änderung mit konkreter Anweisung]
2. [Zweitwichtigste Änderung]
3. [Drittwichtigste Änderung]

══════════════════════════════════════
```

### Schritt 5: Konkrete Fixes vorschlagen

Nach dem Report: Biete an, die Top-Prioritäten direkt umzusetzen. Zeige konkreten Code für jeden Fix. Frage den Nutzer, welche Änderung er zuerst umgesetzt haben möchte.

## Wichtige Regeln

1. **Immer beides prüfen** – Design UND SEO, auch wenn der Nutzer nur nach einem fragt
2. **Konkret sein** – Keine vagen Tipps wie "verbessere die Farben". Stattdessen: "Ändere den Grünton von #4ade80 auf #6ccc43 um dem Logo-Grün zu entsprechen"
3. **Priorisieren** – Die 3 wichtigsten Änderungen klar hervorheben
4. **Positives zuerst** – Immer zuerst sagen, was gut gelungen ist, bevor Kritik kommt
5. **Für Platz 1 optimieren** – Jede SEO-Empfehlung zielt darauf ab, bei lokalen Suchanfragen (z.B. "Beulendoktor München") auf Platz 1 zu kommen
6. **Code-ready** – Verbesserungsvorschläge wenn möglich mit konkretem CSS/JSX-Code untermauern
7. **Kontext-sensibel** – Bei Delluxe-Dellen immer gegen die bekannten Firmendaten und Markenrichtlinien prüfen
8. **Nicht überladen** – Der Report soll knapp und scanbar sein, nicht ein Roman
