# Geo Entity Explorer

An interactive graph visualization tool for exploring entity relationships in the [Geo knowledge graph](https://geo.xyz) platform.

> ⚠️ This is a **demo / proof of concept** using static sample data. Live Geo API integration is planned.

## Live Demo

👉 **[Open Demo](https://YOUR_USERNAME.github.io/geo-entity-explorer/)**

---

## What it does

Pick any entity and instantly see all its connections as a navigable graph — brands, companies, clinical trials, conditions, molecules, and more.

![screenshot](screenshot.png)

### Features

- **Interactive graph** — click any node to inspect its details and highlight all relations
- **Filter by entity type** — Ingredient, Drug, Company, Clinical Trial, Molecule, Condition
- **Drag nodes** — rearrange the layout freely
- **Pan & zoom** — scroll to zoom, drag canvas to pan
- **Relation labels** — animated edges show relationship type on selection
- **Info panel** — full entity description + all connections listed in sidebar

---

## Spaces

This tool is designed to work across all Geo spaces:

| Space | Status |
|-------|--------|
| Health Datasets | ✅ Demo data included |
| Health | 🔜 Planned |
| AI | 🔜 Planned |
| Crypto | 🔜 Planned |
| Software | 🔜 Planned |
| Technology | 🔜 Planned |
| Industries | 🔜 Planned |
| World Affairs | 🔜 Planned |
| AI Datasets | 🔜 Planned |

---

## How to run

### Option 1: Just open the file
```bash
open index.html
```
No build step, no dependencies. Pure HTML/CSS/JS.

### Option 2: Local server
```bash
npx serve .
# or
python3 -m http.server 8080
```

---

## Roadmap

- [ ] Connect to live Geo data via [Geo SDK](https://github.com/graphprotocol/graph-node)
- [ ] Search entities by name
- [ ] Multi-hop traversal (expand neighbors on click)
- [ ] Export subgraph as JSON
- [ ] Support all Geo spaces
- [ ] Embed widget mode for external sites

---

## Tech stack

- Vanilla HTML / CSS / JavaScript
- Canvas 2D API for graph rendering
- Zero dependencies — runs in any browser

---

## About Geo

[Geo](https://geo.xyz) is a decentralized knowledge graph platform. This tool is an independent community project exploring ways to visualize and navigate the Geo entity graph.

---

## Author

Built by a Geo curator & editor (Health Datasets space).  
Feedback welcome — open an issue or reach out on Discord.
