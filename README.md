# 💜 WowMoman — Ich gehe jetzt leben!

Die Website der Marke **WowMoman**: Mindset, Finanzen, KI-Business & Sales für Frauen, die neu anfangen.

## Seiten
- `index.html` — Startseite (mit interaktivem 3D-Kugel-Hero)
- `blog.html` — Blog „Zurück ins Leben" + Artikel (`blog-*.html`)
- `shop.html` — Shop mit 0-Euro-Versprechen, Produkten & Affiliate
- `nischen.html` — Nischen-Finder „Welches Business passt zu dir?"
- `wowmoms.html` — Schwester-Marke für Mütter
- `uploads/` — 📥 **Deine Upload-Box** (siehe `uploads/README.md`)

Alles ist reines HTML/CSS/JS — kein Baukasten nötig, läuft überall.

## 🌍 Website live schalten (kostenlos, GitHub Pages)
1. Oben im Repo auf **Settings → Pages**
2. Bei „Branch": **main** auswählen, Ordner **/(root)**, **Save**
3. Nach 1–2 Minuten ist die Seite online unter:
   `https://vanlifemum-boop.github.io/wowmoman-/`

## 🔗 Eigene Domain verbinden — `wowmoman.de` (Status: in Arbeit)

Die `CNAME`-Datei mit `wowmoman.de` liegt bereits im Repo. Diese zwei Schritte
kann nur die Kontoinhaberin selbst machen (GitHub gibt Repo-Settings nicht per
Bot frei):

1. **GitHub:** Settings → Pages → Custom domain → `wowmoman.de` eintragen → Save
   (GitHub prüft automatisch gegen die vorhandene `CNAME`-Datei).
2. **Beim Domain-Anbieter (checkdomain.de)** diese DNS-Einträge setzen:
   - Haupt-Domain (`@` / wowmoman.de) → **A-Records** auf alle vier IPs:
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `www` → **CNAME** → `vanlifemum-boop.github.io`
3. DNS-Propagation abwarten (meist Minuten, kann bis zu 24–48h dauern).
4. Sobald GitHub das Zertifikat ausgestellt hat: Häkchen bei **Enforce HTTPS**
   setzen — fertig! 🎉

Prüfen kannst du die Propagation z. B. mit `dig wowmoman.de +short` oder auf
dnschecker.org.

---
*Einfach machen und weitersehen!*
