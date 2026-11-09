---
name: li-legal-mcp-skill
description: Official Liechtenstein (LI) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Liechtenstein Legal Research & Multi-Tier Case Law Skill (`li-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Liechtenstein (LI)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `LES 2024, 15 or LGBl. 2024 Nr. 10`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Fürstliches Landgericht (Princely Court of First Instance in Vaduz)
   - **Second Instance (Cantonal / Regional / Appellate):** Fürstliches Obergericht (Court of Appeal) & Beschwerdekommission für Verwaltungsangelegenheiten
   - **Supreme & Constitutional Instance:** Fürstlicher Oberster Gerichtshof (OGH), Staatsgerichtshof (StGH) & Verwaltungsgerichtshof (VGH)
   - **Primary Tiered Database:** Entscheidungen der liechtensteinischen Gerichte (gerichtsentscheide.li) (`https://www.gerichtsentscheide.li`)
