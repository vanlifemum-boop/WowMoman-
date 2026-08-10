# Plan: Power-Mindset-Kurs — "Die Gewinnerin in dir"

## Kontext für den neuen Chat

Dies ist einer von zwei geplanten Kursen für die Marke **WowMoman**
(Coaching/Mindset/Business-Plattform für Frauen, Website live unter
`wowmoman.de`, Repo: `vanlifemum-boop/WowMoman-`). Der zweite Kurs
("KI-Business-Masterclass") wird in einem separaten Chat geplant.

## Zielgruppe

Frauen, die am eigenen Mindset arbeiten wollen — Selbstwert, Entscheidungs-
stärke, Resilienz, Abgrenzung. Passt zur WowMoman-Säule "Power-Mindset" und
ergänzt das bereits existierende Gratis-/Low-Ticket-Angebot im Shop.

## Vorhandenes Rohmaterial (im Repo, teils bereits verwendet)

- `Affirmationen.md` → bereits zu **"Die 30 Gesetze der Gewinnerin"**
  ausgebaut (Gratis-PDF `10-affirmationen-der-gewinnerin.pdf` +
  Bezahl-Workbook `30-gesetze-der-gewinnerin.pdf` in `downloads/`, verlinkt in
  `shop.html`). Kann als Modul 1 direkt übernommen werden.
- `Entscheidungen.md` — Bodo-Schäfer-inspirierte Entscheidungsmethoden
  (noch ungenutzt)
- `hormese.md` — Resilienz durch Hormesis/kontrollierten Stress
  (noch ungenutzt)
- `Die_Kunst_des_Selbstbetrugs_Whitepaper.pdf` — Whitepaper über
  Selbstbetrug-Mechanismen (noch ungenutzt)
- `blog-schopenhauer.html` — bereits veröffentlichter Artikel "Gegen Dummheit
  kämpfen selbst Götter vergebens" (Grenzen setzen, Energie schützen)

## Bereits vorhandener Website-Content, der als Basis dient

- `blog-kein-coaching.html` — "Du brauchst kein Coaching"
- `blog-5prozent.html` — "Nur 5% schaffen es"
- Das Anti-Coaching-Manifest und die "Keine Ausreden"-Sektion auf `index.html`
- Affirmationen-Rotator (`assets/app.js`) mit 15 Sätzen aus den 30 Gesetzen

## Vorgeschlagene Modul-Struktur (Diskussionsgrundlage für den neuen Chat)

1. **Modul 1 — Die 30 Gesetze der Gewinnerin:** bereits fertiges Workbook,
   wird als Kern-Fundament des Kurses eingebunden (ggf. um Reflexions-
   Übungen/Video-Begleitung erweitern).
2. **Modul 2 — Entscheidungen treffen wie eine Gewinnerin:** `Entscheidungen.md`
   zu einem praktischen Modul mit Übungen ausbauen (schnelle Entscheidungen,
   Entscheidungs-Frameworks).
3. **Modul 3 — Grenzen setzen & Energie schützen:** `blog-schopenhauer.html`
   als Grundlage, vertieft um konkrete Skripte/Sätze für schwierige
   Gespräche (Familie, Kritiker, toxische Kommentare).
4. **Modul 4 — Resilienz durch Wachstum:** `hormese.md` zu einem Modul über
   bewusstes Verlassen der Komfortzone ausbauen.
5. **Modul 5 — Selbstbetrug erkennen & auflösen:** Whitepaper als
   Grundlage für Selbstreflexions-Übungen (blinde Flecken, Ausreden
   entlarven — Brücke zum bestehenden "Keine Ausreden"-Manifest).
6. **Abschluss:** `blog-5prozent.html` + `blog-kein-coaching.html` als
   motivierender Abschluss ("Du bist bereit, jetzt machst du").

## Offene Fragen für den neuen Chat

- Format: reiner Text/PDF-Kurs (wie die 30-Gesetze-Workbook-Machart) oder
  mit Video/Audio-Begleitung?
- Preis-Tier: eigenständiges Produkt oder Bundle mit dem bereits bestehenden
  "30 Gesetze der Gewinnerin"-Workbook (12 €)?
- Soll der Kurs als eigene Verkaufsseite gebaut werden (analog zu
  `taler-buch.html`), mit Modul-Übersicht?

## Technischer Kontext (für den neuen Chat)

- Repo lokal klonen: `git clone --depth 1 https://github.com/vanlifemum-boop/WowMoman- /workspace/wowmoman-`
  (ggf. `add_repo` + `register_repo_root` Tools nutzen, falls verfügbar).
- Stil/Farben: `assets/styles.css` (Aubergine `#2a1030`/Magenta `#e0479a`
  Palette), bestehende Komponenten wiederverwenden (`.article`, `.product`,
  `.steps`, `.cards`).
- PDF-Erstellung: `reportlab` wird bereits genutzt, siehe Muster in
  `downloads/30-gesetze-der-gewinnerin.pdf` (Cover, Inhaltsverzeichnis,
  Kapitel-Layout mit Mantra-Box) als Vorlage für neue Workbooks.
- Wichtig: **kein Higgsfield oder anderes Bild-Tool ungefragt nutzen** — falls
  Bilder gebraucht werden, zuerst kie.ai-Zugang klären (Nutzerin hat einen
  eigenen API-Key, wurde in der Ursprungs-Unterhaltung aber noch nicht
  übermittelt).
