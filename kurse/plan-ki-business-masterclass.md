# Plan: KI-Business-Masterclass — "Content, Sichtbarkeit & Verkauf mit KI"

## Kontext für den neuen Chat

Dies ist einer von zwei geplanten Kursen für die Marke **WowMoman**
(Coaching/Mindset/Business-Plattform für Frauen, Website live unter
`wowmoman.de`, Repo: `vanlifemum-boop/WowMoman-`). Der zweite Kurs
("Power-Mindset: Die Gewinnerin in dir") wird in einem separaten Chat geplant.

Dieser Kurs ist im Shop (`shop.html`) bereits als Produkt angeteasert:
*"KI-Business-Masterclass — Schritt für Schritt zum ersten selbstverdienten
Geld mit KI — Content, digitale Produkte, Verkauf. Preis: bald."*

## Zielgruppe

Frauen, die mit KI-Unterstützung ein eigenes digitales Business (Content,
Coaching, digitale Produkte) aufbauen wollen — auch ohne Vorkenntnisse.
Passt zur WowMoman-Säule "KI-Business".

## Vorhandenes Rohmaterial (im Repo, bisher ungenutzt)

- `Leitfaden-fuer-Instagram-Post-Beitraege.pdf` — Instagram-Content-Leitfaden
- `hooks.pdf` — Hooks für Videos/Posts
- `insta Strategie.docx` — Instagram-Strategie
- `geo-seo-prompt-template-coaching.md` — SEO-Prompt-Vorlage für die
  Coaching-Nische (wiederverwendbar für KI-gestützte Blogartikel)
- `plattformen_vergleich- Bezahlsystem .pdf` — Vergleich von Bezahlsystemen
  für den Verkauf digitaler Produkte

## Bereits vorhandener Website-Content, der als Basis dient

- `nischen.html` — Nischen-Finder (10 Business-Nischen-Ideen mit Tags)
- `blog-0euro.html` — "Broke, aber bereit": Start ohne Budget
- `blog-freiberuflerin.html` — Freiberuflich anmelden (ELSTER, Finanzamt)
- `blog-5prozent.html` — "Nur 5% schaffen es": Durchhalte-Motivation

## Vorgeschlagene Modul-Struktur (Diskussionsgrundlage für den neuen Chat)

1. **Modul 1 — Deine Nische finden:** aufbauend auf `nischen.html`, vertieft
   um eine konkrete Auswahl-Methodik (Stärken × Nachfrage × Marge).
2. **Modul 2 — Content mit KI erstellen:** Hooks (`hooks.pdf`), SEO-Prompt-
   Vorlage (`geo-seo-prompt-template-coaching.md`) zu einem wiederholbaren
   KI-Workflow ausbauen (Prompt-Bibliothek für Posts, Blogartikel, Skripte).
3. **Modul 3 — Sichtbar werden:** Instagram-Leitfaden + -Strategie zu einem
   Posting-Fahrplan verdichten (Frequenz, Formate, Content-Pillars).
4. **Modul 4 — Verkaufen & Bezahlsystem einrichten:** Plattformen-Vergleich
   auswerten, konkrete Empfehlung + Schritt-für-Schritt-Setup.
5. **Modul 5 — Rechtlich startklar:** `blog-freiberuflerin.html` als Basis,
   zum vollständigen Anmelde-Fahrplan ausbauen.
6. **Bonus:** `blog-0euro.html` als Einstieg für Teilnehmerinnen ohne Budget.

## Offene Fragen für den neuen Chat

- Format: reiner Text/PDF-Kurs (wie die bisherigen Workbooks) oder mit Video/
  Audio? (Falls Video/Audio: Higgsfield ist verbunden, kie.ai wurde erwähnt
  aber noch nicht mit einem API-Key hinterlegt — das müsste dort geklärt
  werden.)
- Preis-Tier (Shop zeigt aktuell "bald", andere Low-Ticket-Produkte liegen bei
  12–19 €, das Premium-Mentoring ist "auf Anfrage").
- Soll der Kurs als eigene Verkaufsseite (wie `taler-buch.html`) gebaut werden,
  mit Modul-Übersicht und Checkout-Platzhaltern?

## Technischer Kontext (für den neuen Chat)

- Repo lokal klonen: `git clone --depth 1 https://github.com/vanlifemum-boop/WowMoman- /workspace/wowmoman-`
  (ggf. `add_repo` + `register_repo_root` Tools nutzen, falls verfügbar).
- Stil/Farben: `assets/styles.css` (Aubergine `#2a1030`/Magenta `#e0479a`
  Palette), bestehende Komponenten wiederverwenden (`.article`, `.product`,
  `.steps`, `.cards`).
- Wichtig: **kein Higgsfield oder anderes Bild-Tool ungefragt nutzen** — falls
  Bilder gebraucht werden, zuerst kie.ai-Zugang klären (Nutzerin hat einen
  eigenen API-Key, wurde in der Ursprungs-Unterhaltung aber noch nicht
  übermittelt).
