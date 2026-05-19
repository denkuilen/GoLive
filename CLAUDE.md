# GoLive — projectgeheugen

## Belangrijk: wijzigingen doorvoeren naar de live site

De website draait op **GitHub Pages** (`denkuilen.github.io`). De lokale git-omgeving pusht naar een lokale server, NIET naar GitHub.

Om wijzigingen zichtbaar te maken op de live site moet je altijd `mcp__github__push_files` gebruiken om bestanden direct naar de GitHub-repository te pushen:

- Owner: `denkuilen`
- Repo: `GoLive`
- Branch: `main`

Dus: na het bewerken van `index.html` altijd afsluiten met een `mcp__github__push_files` call naar `denkuilen/GoLive` op branch `main`.

## Projectstructuur

- `index.html` — volledige website (HTML + CSS + JS in één bestand)
- `fotos/` — vakantiefotos die automatisch worden ingeladen via de GitHub API

## Stijl & design

- Warme, aardse tinten: zand (`#f2ead8`), bruin (`#8b6f47`), accent oranje (`#c4783a`)
- Fonts: Playfair Display (serif, koppen) + Jost (sans-serif, tekst)
- Taal: Nederlands
