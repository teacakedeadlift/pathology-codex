# Pathology Codex

FRCPath Histopathology Part 2 examination aid.

Succinct information on exam entities with useful differential diagnoses, discriminatory IHC, and clinical pearls. Cytology entities supported alongside histology, with bidirectional linking between counterparts.

## Features

- **Histology and Cytology tabs** — separate entity sets with appropriate schemas for each
- **IHC Explorer** — search any marker to see which entities express it, which don't, and where it is discriminatory
- **Differential jump links** — navigate directly between related entities
- **Sidebar filters** — filter by subspecialty, behaviour, category, pattern, specimen type, and reporting system
- **RCPath reporting categories** — Thyroid (Thy1–5), Milan (salivary), Paris (urine), IAC Harrogate (effusion)

## Usage

Open `index.html` in any modern browser — no installation, no internet required after download.

**Adding entities:** use the **+ Add Entity** button. Data saves to browser localStorage immediately.

**Making changes permanent:** use **⬇ Save File** to download an updated `index.html` with all entities baked in. Replace the file in this repository to sync across devices.

**Import / Export:** use **↓ Export** to download all entities as JSON. Use **↑ Import** to load a JSON file — useful for bulk entry or sharing entities between users.

## Data persistence

Entities added via the UI are stored in browser localStorage and are device/browser specific. Use **⬇ Save File** and push the updated `index.html` to make entries permanent and portable.

## Current coverage

- GI mesenchymal tumours (GIST, Schwannoma, Leiomyoma, LMS, IFP, Desmoid, IMT, Glomus, Plexiform Fibromyxoma, Synovial Sarcoma)
- Appendiceal neoplasms (LAMN, HAMN, Goblet Cell Adenocarcinoma)
- GI neuroendocrine neoplasms (WD NET G1/G2, WD NET G3, NEC Small Cell, NEC Large Cell, MiNEN, Metastatic Mucinous/Signet Ring Adenocarcinoma)
