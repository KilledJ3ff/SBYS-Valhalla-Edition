# SBYS Custom Scenery — Valhalla Edition

##### SBYS airport custom scenery for FlightGear — Valhalla Edition fork of mherweg/SBYS-fg-CustomScenery.

[![FlightGear](https://img.shields.io/badge/FlightGear-2020.3%2B-blue.svg)]()
[![License](https://img.shields.io/badge/License-GPL--3.0-red.svg)]()

> **Valhalla Edition** — fork maintained under **Projeto Valhalla** (ala NEXUS).
> Upstream: https://github.com/mherweg/SBYS-fg-CustomScenery

![SBYS — Campo Fontenelle (Pirassununga/SP) apron chart, landscape](SBYS_patio_horizontal.jpeg)

---

## The aerodrome — SBYS / Campo Fontenelle

**SBYS** is the military airfield of **Pirassununga, SP — Campo Fontenelle**, home of the **AFA (Academia da Força Aérea)** — the Brazilian Air Force Academy and one of the most important military aviation hubs in Brazil. It is where all FAB pilots receive their initial flight training:

- **1º EIA (1º Esquadrão de Instrução Aérea)** — advanced instruction
- **2º EIA (2º Esquadrão de Instrução Aérea)** — basic instruction
- **Esquadrilha da Fumaça (EDA)** — the FAB aerobatic demonstration squadron

Runways **02L/20R, 02C/20C, 02R/20L** (asphalt, ~2.1 km), elevation **1.976 ft**, ARP `S21 59 04 W047 20 39`.

---

## What is included

| Path | Content |
|------|---------|
| `Terrain/w050s30/w048s22/` | Custom terrain tiles (`.btg.gz` + `.stg`), incl. `SBYS.btg.gz` |
| `SBYS.dat` | Airport data (elevation, frequencies, runways, taxiways, parking) |
| `Airports/S/B/Y/SBYS.groundnet.xml` | Ground network (taxi routes, parking, rwy exits) — Valhalla addition |
| `Models/Airport/` | Airport buildings (hangar, office) — Valhalla addition |
| `Models/Sport/` | Football court, swimming pool, generic terrain objects — Valhalla addition |
| `Objects/` | Scenery objects — Valhalla addition |

## Installation

1. Clone into your FlightGear scenery directory (e.g. a custom scenery folder added in the launcher):
   ```bash
   git clone https://github.com/KilledJ3ff/SBYS-fg-CustomScenery-Valhalla-Edition.git SBYS
   ```
2. Add the parent folder as an additional scenery path in FlightGear (before TerraSync so it overrides).
3. Start at SBYS.

---

## Development

- **Roadmap:** [ROADMAP.md](ROADMAP.md)
- **Changelog:** [CHANGELOG.md](CHANGELOG.md)

## Credits

- **Valhalla Edition fork & airport objects/groundnet** — **Killed J3ff** (Projeto Valhalla — NEXUS)
- **Original SBYS terrain scenery** — mherweg

## License

GPL-3.0 — see [LICENSE](LICENSE).
