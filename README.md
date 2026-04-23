# PT Maju Bersama Manufacturing Wiki

A fictional company knowledge base built using Karpathy's LLM Wiki pattern. This wiki serves as an illustration of a structured organizational memory system.

## Company Overview

**PT Maju Bersama Manufacturing** is a fictional Indonesian textile and garment manufacturer based in Bandung, West Java. Founded in 1998, the company employs ~1,200 people across two factories.

## Wiki Structure

- `entries/summaries/` — Company overview, case studies, annual reports
- `entries/entities/` — People, organizations, locations
- `entries/concepts/` — Manufacturing processes, products, business concepts
- `entries/analysis/` — Strategic analysis, financial performance, comparisons
- `SCHEMA.md` — Wiki conventions and workflows
- `index.md` — Content catalog with timeline
- `log.md` — Activity log

## Features

- ✅ 29 interconnected wiki pages
- ✅ Full wikilink support (`[[page-name]]`)
- ✅ Company timeline (1998-2024)
- ✅ Decision tracking with board meeting minutes
- ✅ Financial analysis with scored assessments
- ✅ Fake but realistic Indonesian business context

## Quick Links

- [Wiki Index](index.md) — Start here
- [Company Profile](entries/summaries/profil-perusahaan.md)
- [Key Decisions 2023](entries/summaries/keputusan-2023.md)
- [Surabaya Expansion Analysis](entries/analysis/analisis-strategi-ekspansi.md)

## Deployment

This wiki can be deployed using [Quartz](https://quartz.jzhao.cc/) as a static site.

```bash
npx quartz build
npx quartz build --serve  # preview locally
```

## License

This is fictional data for illustration purposes only.
