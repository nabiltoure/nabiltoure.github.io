# Personlig profilside

Enkel personlig presentasjonsside for Nabil. Én fil: `index.html` (HTML, CSS og JS i samme fil, ingen byggesteg).

## Formål og rammer
- Personlig profilside, ikke et konsulentselskap. Nabil er ansatt i Vivicta, så siden skal ikke tilby tjenester eller si "tilgjengelig for prosjekter".
- Skriv i jeg-form. Ingen kundenavn uten klarering. Ingen Vivicta-logo.
- Footer: bare "© år + fullt navn". Ingen "meninger er mine egne"-tekst.
- Hovedfokus: Data Engineering og Analytics. AI Governance, revisjonsbakgrunn og resten vises, men dempet.
- Portrett: `img/portrett.jpg` (400x400, beskåret fra originalbildet).
- Lenker kun til LinkedIn og GitHub.

## Design
- Minimalistisk stil inspirert av micio.no: varm hvit bakgrunn med prikkerutenett, Inter Tight.
- Bred layout (maks 1320px) i tre kolonner: person, tekst, globus. Globusen står helt til høyre. Fokus, Erfaring og Annet er rader under hverandre, etikett til venstre og innhold i tekstkolonnen.
- Globus (D3 + world-atlas fra jsDelivr) viser landene jeg har bodd i: Norge, England (UK-formen) og Togo. Under: språk, norsk, engelsk og fransk (ikke skriv morsmål/native). Feiler bibliotekene, skjules globusen.
- Norsk og engelsk via `data-lang` på body (klassene `.no` og `.en`).
- Lyst og mørkt tema: følger systemet, kan overstyres med knapp, valget lagres i localStorage. Knappen fylles og ikonet roterer ved hover; ved klikk fader gammelt tema ut og nytt inn (View Transitions, CSS-fallback, av ved redusert bevegelse).
- Ikke bruk tankestrek eller bindestrek som skilletegn i tekst; bruk komma, kolon eller egne setninger.

## Publisering
- GitHub Pages fra repoet nabiltoure/nabiltoure.github.io, branch main, rot.
- Eget domene: nabiltoure.no (filen `CNAME`). www.nabiltoure.no peker hit via CNAME i DNS.
- Push til main publiserer automatisk.
- Repoet er offentlig (krav for gratis Pages). `_config.yml` hindrer at CLAUDE.md og .claude publiseres på nettsiden, men de er synlige i repoet: ikke skriv noe her som ikke tåler å være offentlig.

## SEO
- Tittel, description, canonical (https://nabiltoure.no/), Open Graph og JSON-LD (ProfilePage + Person) i `<head>`. Hold dem i takt med teksten på siden.
- Delingsbilde: `img/deling.jpg` (1200x630). Favicon: `favicon.svg`, `img/apple-touch-icon.png`.
- `robots.txt` og `sitemap.xml` i roten. Oppdater `lastmod` i sitemap ved større endringer.
