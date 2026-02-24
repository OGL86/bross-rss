# 🔴 BRÅSS! Studio Radar

**Live nyhetsdashbord for Nintendo & videospill** — bygget for podcast-produksjon.

Aggregerer 33 RSS-kilder i sanntid og presenterer dem i et ryddig, filtrerbart dashbord. Laget som arbeidsverktøy for [BRÅSS! Nintendo & Videospill Podcast](https://www.youtube.com/@brassNintendo).

## Funksjoner

- **33 RSS-kilder** — internasjonale, norske og nisje-kilder (inkl. Reddit)
- **Automatisk hype-score** — artikler scores basert på nøkkelord (Switch 2, Zelda, leaks, osv.)
- **Manuell hype-justering** — klikk +/− for å overstyre scoren
- **Duplikatfjerning** — Jaccard-likhet fjerner overlappende saker på tvers av kilder
- **Kategorifilter** — Nyheter, Rykter, Anmeldelser, Utgivelser, Hardware, Bransje, Salg
- **Kildefilter** — Internasjonale / Norske / Nisje
- **Søk** — fritekst-søk med highlighting
- **Manus-funksjon** — bokmerke saker med ⭐, kopier alle til utklippstavlen
- **Lokal cache** — nyheter lagres i localStorage, overlever refresh
- **Auto-refresh** — oppdaterer hvert 10. minutt
- **Mørk/lys modus** — bytt med kontrastknappen
- **Arkivkolonne** — vis saker opptil 30 dager tilbake

## Kom i gang

Ingen bygging eller avhengigheter — bare én `index.html`-fil.

1. Åpne `index.html` i en nettleser
2. Eller deploy til GitHub Pages / Netlify / hva som helst

RSS-feeds hentes via [rss2json.com](https://rss2json.com/) API.

## Teknologi

- Vanilla JavaScript (ingen rammeverk)
- Vanilla CSS (ingen biblioteker)
- Én enkelt HTML-fil
- localStorage for cache og brukerpreferanser

## Skjermbilde

> *Mørkt tema med to-kolonners layout: Dagens nyheter til venstre, ukens til høyre.*

## Lisens

Fritt tilgjengelig for personlig bruk.
