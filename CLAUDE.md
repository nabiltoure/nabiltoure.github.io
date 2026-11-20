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
- Minimalistisk stil inspirert av micio.no: varm hvit bakgrunn med prikkerutenett, Inter Tight, smal kolonne.
- Norsk og engelsk via `data-lang` på body (klassene `.no` og `.en`).
- Lyst og mørkt tema: følger systemet, kan overstyres med knapp, valget lagres i localStorage. Knappen fylles og ikonet roterer ved hover; ved klikk sprer nytt tema seg som en sirkel fra knappen (View Transitions, av ved redusert bevegelse).
- Ikke bruk tankestrek eller bindestrek som skilletegn i tekst; bruk komma, kolon eller egne setninger.

## Gjenstår
- Publisering på GitHub Pages, eventuelt eget domene
