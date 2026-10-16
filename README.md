# Nails by Blue – website

Statische website (HTML/CSS, geen build nodig) voor Nails by Blue, nagelstudio aan huis in Lewenborg, Groningen.

- `index.html` – home
- `prijslijst.html` – prijslijst
- `voorwaarden.html` – algemene voorwaarden
- `tips.html` – handige tips

Alle "Maak een afspraak"-knoppen linken naar de Salonized-boekingspagina.

## Nog in te vullen
- **Tips** zijn een concept: vergelijk ze met de Instagram-highlight en pas ze aan. (Voorwaarden zijn overgenomen van Instagram.)

De site draait via GitHub Pages (branch `Live_Website`) op https://www.nailsbybluegroningen.nl. Voeg je een pagina toe, zet die dan ook in `sitemap.xml` en geef hem een eigen `canonical`-link.

## Wijzigingen in CSS of JS
De stylesheet en het script worden geladen met een versienummer (`style.css?v=…`). Pas dat nummer in alle HTML-bestanden aan na een wijziging in `css/style.css` of `js/main.js`, zodat browsers niet een oude, opgeslagen versie blijven gebruiken.
