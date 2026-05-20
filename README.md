# SciSurvey — Systematic Survey × Sciverse

> **SciSurvey** is a Claude Code skill that generates publication-quality academic literature surveys using the Sciverse academic database API.

[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blue)](https://claude.ai/code)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## What Makes SciSurvey Different

| Capability | SciSurvey | Typical Literature Review Skills |
|---|---|---|
| **Domain-adaptive keywords** | ✅ Auto-detects CS/Medical/Social Science and applies field-specific search terms (`survey` vs `systematic review` vs `meta-analysis`) | ❌ Generic keywords only |
| **Sciverse meta-search** | ✅ `filters_advanced` for citation_count, fwci, language, country, OA status | ❌ Keyword-only search |
| **Citation graph traversal** | ✅ Uses `references`/`related_works` fields to discover foundational papers | ❌ Not available |
| **Citation Evidence Mapping** | ✅ Every claim requires doc_id + verbatim text evidence before writing | ❌ No per-claim verification |
| **Blocking pre-output gate** | ✅ Fails hard if citation count mismatch, method misattribution, or unverified numbers | ❌ Self-assessment only |
| **Numerical 5-element rule** | ✅ Metric + Dataset + Baseline + Result + Ref required for every number | ❌ No constraint |
| **Survey vs Review modes** | ✅ `systematic-survey` (taxonomy + comparison tables) / `systematic-review` (PRISMA + critical analysis) / `scoping-review` | ❌ Single output structure |
| **Multi-format output** | ✅ Markdown / LaTeX / DOCX / PDF | ⚠️ Markdown only (most skills) |
| **6 citation styles** | ✅ APA / IEEE / Vancouver / Chicago / MLA / GB/T 7714 | ⚠️ 1-2 styles (most skills) |
| **Domestic/International split** | ✅ Explicit Chinese paper detection via `language` + `publication_published_country` | ❌ No concept |

---

## Quick Start

### Install

```bash
# Add to your Claude Code skills directory
git clone https://github.com/liweixiaogui10/Systematic_Survey_skills.git
cp -r Systematic_Survey_skills/skills/scisurvey ~/.claude/skills/
```

### Usage

```
大语言模型幻觉检测综述
```

```
systematic review of cognitive behavioral therapy for depression --type systematic-review --citation-style apa --format docx
```

```
机器人导航方法调研 --type systematic-survey --format latex --citation-style ieee
```

### Parameters

| Parameter | Options | Auto-inferred from domain |
|-----------|---------|--------------------------|
| `--type` | `systematic-survey` / `systematic-review` / `scoping-review` / `narrative-review` | CS/AI → survey; Medical/Psychology → review; New fields → scoping |
| `--format` | `markdown` / `latex` / `docx` / `pdf` | `markdown` |
| `--citation-style` | `gbt` / `apa` / `ieee` / `vancouver` / `chicago` / `mla` | CS → ieee; Medical → vancouver; Chinese → gbt |

---

## Survey vs Review — When to Use Each

```
Survey = Mapping a supermarket: cataloguing all products by category
         "There are 5 shampoo brands, prices range from $1 to $10"

Review = Product tester: deep-testing 3 products and giving a verdict
         "Brand A cleans well but damages hair; B is gentle but pricey; C is best overall"
```

| Type | Core Action | Best For | Typical Title |
|------|-------------|----------|---------------|
| **Systematic Survey** | Exhaustive classification + comparison | CS / AI / Engineering (many methods) | "A Survey of X" |
| **Systematic Review** | Critical evaluation + depth judgment | Medical / Psychology / Social Science | "A Systematic Review of X" |
| **Scoping Review** | Map field boundaries | Emerging / interdisciplinary fields | "A Scoping Review of X" |

---

## Architecture

```
SciSurvey Pipeline
│
├── Phase 0: meta-catalog field schema confirmation
├── Phase 1: Domain detection → Type inference → Adaptive keyword matrix
├── Phase 2: Parallel retrieval
│   ├── Semantic search (agentic-search, EN × 4 + ZH × 3)
│   ├── Structured meta-search (6 filter strategies)
│   └── Citation graph traversal (references + related_works)
├── Phase 3: Quality filtering (fwci + citation_count age-adjusted)
├── Phase 4: Deep metadata extraction + full-text reading (16384 bytes max)
├── Phase 4.5: Citation Evidence Mapping ⚠️ (MANDATORY, blocking)
├── Phase 5: Thematic clustering + domestic/international analysis
├── Phase 6: Writing (Survey/Review/Scoping structure per --type)
├── Phase 7: Citation Integrity Gate ⚠️ (blocking pre-output check)
└── Phase 8: Multi-format export (MD / LaTeX / DOCX / PDF)
```

---

## Requirements

- [Claude Code](https://claude.ai/code) with MCP support
- [Sciverse MCP server](https://sciverse.space) with API key configured in `.mcp.json`
- **Optional** (for format conversion): `pandoc`, `xelatex`/`pdflatex`

---

## Citation

If you use SciSurvey in your research workflow, please cite this repository.

---

## License

MIT License — see [LICENSE](LICENSE) for details.
