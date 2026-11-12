# Gluten Free Storybook

An interactive, storybook sticker map of 10 top gluten-free friendly spots in and around San Jose. It's a sibling of [Hella Good Food](https://github.com/kamilkolacek/sanjose-food-map) and runs on the same engine: chunky 3D-style pins, vector roads, chiptune music and a visited quest log.

## GF levels (filter chips)

| Level | Meaning | Spots |
|---|---|---|
| 🟢 100% Gluten-Free | The whole kitchen is gluten-free | Oy Gluten Free Bakery, Asian Box |
| 🟡 Celiac-Friendly | Diners report careful GF handling | LUNA Mexican Kitchen, Moonbowls, Arepas Latin Cuisine, Starbird Chicken, The Counter |
| 🟠 Great GF Menu | Good GF options, but a shared kitchen | Pizza Antica, Veggie Grill, Crepevine |

Ratings come from gluten-free community sources (Find Me Gluten Free, Atly), researched in November 2026. Kitchens change, so always confirm with staff.

## Project layout

- `index.html`: the built, self-contained page (served by GitHub Pages)
- `src/template.html`: page source
- `src/data.js`: spots, roads, highway shields
- `src/build.py`: rebuilds `index.html` (`python3 src/build.py`)
- `data/geo.json`: spot coordinates, geocoded with the U.S. Census geocoder

Built with Claude Code.
