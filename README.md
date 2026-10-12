# Code Cracker 🔒

Een party-/eventspel: teams kraken een 6-cijferig slot, snelste tijd wint.

## Spel
1. Vul een **teamnaam** in, kies een **locatie** (Vuurtoren, Balans of Kompas) en een **emoji**.
2. Druk op **START** — de timer begint.
3. Stel met de ▲ / ▼ knoppen de 6 cijfers in en druk op **CHECK CODE**.
4. Fout geraden? Dan **20 seconden geblokkeerd** (de timer loopt door).
5. Goed geraden? Je tijd wordt opgeslagen in het **scorebord**, te filteren per locatie.

## Organisator
Klik op het tandwiel ⚙️ rechtsboven om de geheime 6-cijferige code te bekijken of in te stellen.
Alle teams op hetzelfde apparaat spelen dezelfde code. Laat het veld leeg en sla op voor een
nieuwe willekeurige code.

## Techniek
- Eén bestand: `index.html` (geen build, geen dependencies).
- Scores en de geheime code worden opgeslagen in `localStorage` van de browser.
- Werkt op desktop, tablet en telefoon.

## Lokaal draaien
Open `index.html` in een browser, of host via GitHub Pages.
