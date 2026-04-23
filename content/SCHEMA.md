# PT Maju Bersama Manufacturing — Wiki Schema

## Philosophy

This wiki is the long-term organizational memory for PT Maju Bersama Manufacturing. Following Karpathy's LLM Wiki pattern:
- **Obsidian is the IDE**
- **The LLM is the programmer**
- **The wiki is the codebase**

Every decision, process, and lesson learned should be captured here. Answers to operational questions should be filed back as wiki pages.

## Source Provenance

Every page must cite its source:
- Internal documents: `Source: Internal memo, YYYY-MM-DD`
- Meeting notes: `Source: Board Meeting Minutes, YYYY-MM-DD`
- External: `Source: [URL or publication], accessed YYYY-MM-DD`

## File Naming Conventions

- **kebab-case.md** for all filenames
- Indonesian language names where appropriate, transliterated to kebab-case
- Examples: `budiarjo-widodo.md`, `mesin-tenun-otomatis.md`, `keputusan-2023.md`

## Page Structure Requirements

Every page must include:
1. **Wikilinks** (`[Page Name](page-name.md)`) for all mentioned entities/concepts that have pages
2. **Connected Pages** section listing all outbound wikilinks
3. **Sources** section listing original references

## Content Types

### Summary Pages (`entries/summaries/`)
- Front matter: Source, Date, Type, Ingested
- Overview, Key Findings, Critical Quotes, Timeline (if applicable)
- Entities Mentioned, Concepts, Sources

### Entity Pages (`entries/entities/`)
- People: executives, managers, key employees
- Organizations: departments, partners, suppliers, customers
- Locations: factories, offices, warehouses

### Concept Pages (`entries/concepts/`)
- Manufacturing processes
- Product lines
- Business frameworks
- Technical standards

### Analysis Pages (`entries/analysis/`)
- Strategic decisions with pros/cons
- Comparative analysis
- Root cause analysis
- Financial performance analysis

## Workflows

### Ingest Workflow
1. Classify source type
2. Extract key information
3. Write summary page
4. Create/update entity pages
5. Create/update concept pages
6. Cross-reference all links
7. Update index.md
8. Log in log.md

### Query Workflow
1. Search wiki first (index.md, then relevant sections)
2. Answer from wiki content
3. If new info discovered, update relevant pages
4. Log query in log.md

### Lint Schedule
- Monthly: check for contradictory claims
- Quarterly: find orphan pages (no inbound links)
- Annually: flag stale claims, identify data gaps

## Token Budgets

- **L0 (overview)**: ~200 tokens — index entries, entity one-liners
- **L1 (summary)**: ~1-2k tokens — standard summary pages
- **L2 (detailed)**: ~2-5k tokens — analysis pages, deep dives
- **L3 (full)**: ~5k+ tokens — comprehensive reports, full documentation

## Company Context

**PT Maju Bersama Manufacturing** is a fictional Indonesian textile and garment manufacturer based in Bandung, West Java. Founded in 1998, the company employs ~1,200 people across two factories and serves both domestic and export markets (primarily Japan, US, and EU).

**Product Lines:**
- Traditional batik textiles
- Ready-to-wear garments
- Technical textiles for automotive industry
- Custom printing services

**Key Facts:**
- Founded: 1998 (post-Asian financial crisis)
- HQ: Bandung, West Java, Indonesia
- Employees: ~1,200
- Revenue (2023): IDR 340 billion (~USD 23M)
- 2 production facilities, 1 headquarters office
