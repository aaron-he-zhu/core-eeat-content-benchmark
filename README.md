# CORE-EEAT Content Benchmark

> **8 dimensions × 10 items = 80 evaluation criteria** for optimizing content visibility across AI engines (GEO) and search engines (SEO).

**Version**: 1.0 | **Author**: Aaron | **Updated**: 2026-02-06

---

## How to Read This Document

This document uses **progressive disclosure** — read as deep as you need:

| Depth | Sections | You Will Learn |
|-------|----------|----------------|
| Skim | Parts 1–2 | What CORE-EEAT is + all 80 check items at a glance |
| Apply | Parts 3–5 | How to score content, adapt to content types, and run quality gates |
| Master | Parts 6–7 | Detailed Pass/Partial/Fail criteria for every item with examples |
| Optimize | Part 8 | AI engine preferences, implementation mapping, common errors |

---

# Part 1: Framework Overview

## What is CORE-EEAT?

CORE-EEAT is a content quality benchmark for the AI era. It evaluates content across two complementary systems:

| System | Optimization Target | Core Question | Items |
|--------|---------------------|---------------|-------|
| **CORE** | GEO (Generative Engine Optimization) | Can AI understand, extract, and cite this content? | 40 |
| **EEAT** | SEO (Search Engine Optimization) | Is the source behind this content trustworthy? | 40 |
| **Total** | GEO + SEO | — | **80** |

### MECE Boundary

The two systems are mutually exclusive and collectively exhaustive:

- **CORE** = the content body itself — *What does it say? How is it organized? Can AI cite it?*
- **EEAT** = everything outside the content body — *Who wrote it? Why should we trust them?*

**Quick rule**: If you can see it in the article/page → CORE. If you need to check the author/org/site → EEAT.

### 8 Dimensions

| System | Dim | Full Name | Core Question |
|--------|-----|-----------|---------------|
| CORE | **C** | Contextual Clarity | Does content match intent? Is the answer upfront? |
| CORE | **O** | Organization | Is structure clear? Can AI parse it efficiently? |
| CORE | **R** | Referenceability | Can data and evidence be verified and cited? |
| CORE | **E** | Exclusivity | What unique value does this add? Why cite you over others? |
| EEAT | **Exp** | Experience | Does the creator have first-hand experience? |
| EEAT | **Ept** | Expertise | Does the creator have professional competence? |
| EEAT | **A** | Authority | Do third parties recognize this source? |
| EEAT | **T** | Trust | Is the site technically, legally, and governance-wise trustworthy? |

### Priority Tags

Each check item carries a priority tag indicating its primary optimization target:

| Tag | Meaning | When to Prioritize |
|-----|---------|-------------------|
| GEO-First 🎯 | Critical for AI engine citation | Content targeting AI search visibility |
| SEO-First 🔍 | Critical for traditional search ranking | Content targeting Google/Bing organic traffic |
| Dual ⚡ | Important for both channels | All content should aim for these |

---

# Part 2: Complete 80-Item Checklist

> One-line standard for every check item. Use this as your evaluation reference.

### CORE — Content Body (40 Items)

| ID | Dim | Check Item | Priority | One-Line Standard |
|----|-----|-----------|----------|-------------------|
| C01 | C | Intent Alignment | Dual ⚡ | Title promise = content delivery |
| C02 | C | Direct Answer | GEO 🎯 | Core answer in first 150 words |
| C03 | C | Query Coverage | Dual ⚡ | Covers ≥3 query variants (synonyms, long-tail) |
| C04 | C | Definition First | GEO 🎯 | Key terms defined on first use |
| C05 | C | Topic Scope | GEO 🎯 | Explicitly states what is and isn't covered |
| C06 | C | Audience Targeting | Dual ⚡ | States "this article is for..." |
| C07 | C | Semantic Coherence | GEO 🎯 | Logical flow between paragraphs, no jumps |
| C08 | C | Use Case Mapping | GEO 🎯 | Decision framework: when to choose A vs B |
| C09 | C | FAQ Coverage | GEO 🎯 | Structured FAQ covering long-tail follow-ups |
| C10 | C | Semantic Closure | Dual ⚡ | Conclusion answers the opening question + next steps |
| O01 | O | Heading Hierarchy | Dual ⚡ | H1→H2→H3, no level skipping |
| O02 | O | Summary Box | GEO 🎯 | Has TL;DR or Key Takeaways section |
| O03 | O | Data Tables | GEO 🎯 | Comparisons and specs presented in tables |
| O04 | O | List Formatting | GEO 🎯 | Parallel items use bullet or numbered lists |
| O05 | O | Schema Markup | GEO 🎯 | Appropriate JSON-LD (Article/FAQ/HowTo/etc.) |
| O06 | O | Section Chunking | GEO 🎯 | Each section has single topic; paragraphs 3–5 sentences |
| O07 | O | Visual Hierarchy | SEO 🔍 | Key concepts bolded or highlighted |
| O08 | O | Anchor Navigation | Dual ⚡ | Table of contents with jump links |
| O09 | O | Information Density | GEO 🎯 | No filler; consistent terminology throughout |
| O10 | O | Multimedia Structure | Dual ⚡ | Images/videos have captions and carry information |
| R01 | R | Data Precision | GEO 🎯 | ≥5 precise numbers with units (%, $, ms) |
| R02 | R | Citation Density | GEO 🎯 | ≥1 external citation per 500 words |
| R03 | R | Source Hierarchy | GEO 🎯 | Primary sources first; ≥3 Tier 1–2 sources |
| R04 | R | Evidence-Claim Mapping | GEO 🎯 | Every claim backed by evidence immediately after |
| R05 | R | Methodology Transparency | GEO 🎯 | Sample size, steps, and criteria documented |
| R06 | R | Timestamp & Versioning | Dual ⚡ | Last updated <1 year; version changes noted |
| R07 | R | Entity Precision | GEO 🎯 | Full names for people/orgs/products; no "a company" |
| R08 | R | Internal Link Graph | SEO 🔍 | Descriptive anchor texts forming topic clusters |
| R09 | R | HTML Semantics | GEO 🎯 | Uses `<article>`, `<figure>`, `<time>`, `<cite>` |
| R10 | R | Content Consistency | Dual ⚡ | Data self-consistent; no broken links (404) |
| E01 | E | Original Data | GEO 🎯 | First-party surveys, experiments, or statistics |
| E02 | E | Novel Framework | GEO 🎯 | Named, citable original framework or model |
| E03 | E | Primary Research | GEO 🎯 | Original experiments/surveys with documented process |
| E04 | E | Contrarian View | GEO 🎯 | Challenges consensus with evidence |
| E05 | E | Proprietary Visuals | Dual ⚡ | ≥2 original infographics, charts, or diagrams |
| E06 | E | Gap Filling | GEO 🎯 | Covers questions competitors don't |
| E07 | E | Practical Tools | Dual ⚡ | Downloadable templates, checklists, or calculators |
| E08 | E | Depth Advantage | GEO 🎯 | Deeper than competing content on same topic |
| E09 | E | Synthesis Value | GEO 🎯 | Cross-domain knowledge combination (A+B=C) |
| E10 | E | Forward Insights | GEO 🎯 | Data-backed predictions and trend analysis |

### EEAT — Source Credibility (40 Items)

| ID | Dim | Check Item | Priority | One-Line Standard |
|----|-----|-----------|----------|-------------------|
| Exp01 | Exp | First-Person Narrative | SEO 🔍 | Contains "I tested" or "We found" + action verbs |
| Exp02 | Exp | Sensory Details | SEO 🔍 | ≥10 sensory words (smooth, heavy, bright) |
| Exp03 | Exp | Process Documentation | Dual ⚡ | Step-by-step process with timeline |
| Exp04 | Exp | Tangible Proof | SEO 🔍 | ≥2 original photos/screenshots with timestamps |
| Exp05 | Exp | Usage Duration | SEO 🔍 | States "after X months of use..." |
| Exp06 | Exp | Problems Encountered | Dual ⚡ | Shares ≥2 real problems + solutions |
| Exp07 | Exp | Before/After Comparison | SEO 🔍 | Shows change, improvement, or difference |
| Exp08 | Exp | Quantified Metrics | Dual ⚡ | Measurable experience data (time, cost, success rate) |
| Exp09 | Exp | Repeated Testing | SEO 🔍 | Multiple tests or long-term tracking |
| Exp10 | Exp | Limitations Acknowledged | GEO 🎯 | States "we only tested X scenario" |
| Ept01 | Ept | Author Identity | SEO 🔍 | Byline + avatar + bio (>30 words) |
| Ept02 | Ept | Credentials Display | SEO 🔍 | Relevant degrees, certs, years of experience |
| Ept03 | Ept | Professional Vocabulary | Dual ⚡ | Accurate industry jargon, no misuse |
| Ept04 | Ept | Technical Depth | Dual ⚡ | Parameters, thresholds, examples are actionable |
| Ept05 | Ept | Methodology Rigor | GEO 🎯 | Analysis method is reproducible |
| Ept06 | Ept | Edge Case Awareness | Dual ⚡ | Discusses ≥2 exceptions or "when this doesn't apply" |
| Ept07 | Ept | Historical Context | SEO 🔍 | Shows knowledge of the field's evolution |
| Ept08 | Ept | Reasoning Transparency | GEO 🎯 | "We chose A over B because..." with tradeoffs |
| Ept09 | Ept | Cross-domain Integration | Dual ⚡ | Connects knowledge across fields |
| Ept10 | Ept | Editorial Process | SEO 🔍 | "Reviewed by" or "Fact-checked by" labels |
| A01 | A | Backlink Profile | SEO 🔍 | Cited by authoritative sites (.edu, .gov, leaders) |
| A02 | A | Media Mentions | SEO 🔍 | "Featured in" with media logos |
| A03 | A | Industry Awards | SEO 🔍 | Displays relevant industry awards or recognition |
| A04 | A | Publishing Record | SEO 🔍 | Conference talks, publications, patents |
| A05 | A | Brand Recognition | Dual ⚡ | Brand has search volume |
| A06 | A | Social Proof | SEO 🔍 | Authentic user testimonials with real details |
| A07 | A | Knowledge Graph Presence | Dual ⚡ | Has Wikipedia entry or Google Knowledge Panel |
| A08 | A | Entity Consistency | GEO 🎯 | Brand/author info consistent across the web |
| A09 | A | Partnership Signals | SEO 🔍 | Shows partnerships with authoritative organizations |
| A10 | A | Community Standing | SEO 🔍 | Active and influential in professional communities |
| T01 | T | Legal Compliance | SEO 🔍 | Privacy Policy + Terms of Service present |
| T02 | T | Contact Transparency | SEO 🔍 | Physical address or ≥2 contact methods |
| T03 | T | Security Standards | SEO 🔍 | Site-wide HTTPS, no security warnings |
| T04 | T | Disclosure Statements | Dual ⚡ | Affiliate links disclosed (**veto if missing**) |
| T05 | T | Editorial Policy | SEO 🔍 | Content standards and review process published |
| T06 | T | Correction & Update Policy | Dual ⚡ | Has corrections page or changelog |
| T07 | T | Ad Experience | SEO 🔍 | Ads <30% of page; no intrusive popups |
| T08 | T | Risk Disclaimers | Dual ⚡ | YMYL topics have necessary disclaimers |
| T09 | T | Review Authenticity | Dual ⚡ | Reviews show authenticity signals |
| T10 | T | Customer Support | SEO 🔍 | Clear return policy, complaint channels, response SLA |

---

# Part 3: Scoring System

## Per-Item Scoring

| Status | Score | Meaning |
|--------|-------|---------|
| **Pass** | 10 | Fully meets criteria |
| **Partial** | 5 | Partially meets criteria |
| **Fail** | 0 | Does not meet criteria |

## Dimension and Total Scores

Each dimension: sum of 10 items = 0–100 points.

```
GEO Score = (C + O + R + E) / 4
SEO Score = (Exp + Ept + A + T) / 4
Total Score = (GEO Score + SEO Score) / 2
```

## Weighted Scoring by Content Type

For specific content types, apply dimension weights instead of equal averaging:

```
Weighted Score = Σ (dimension_score × weight)
```

| Dim | Product Review | How-to Guide | Comparison | Landing Page | Blog Post | FAQ Page | Alternative | Best-of | Testimonial |
|-----|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **C** | 10% | 20% | 10% | 20% | 25% | 25% | 10% | 10% | 10% |
| **O** | 10% | 20% | 20% | 10% | 10% | 25% | 15% | 25% | 5% |
| **R** | 15% | 10% | 25% | 5% | 10% | 15% | 25% | 20% | 15% |
| **E** | 20% | 5% | 10% | 5% | 20% | 5% | 5% | 15% | 10% |
| **Exp** | 20% | 5% | 5% | 5% | 10% | 5% | 15% | 5% | 30% |
| **Ept** | 5% | 20% | 15% | 5% | 10% | 10% | 5% | 10% | 5% |
| **A** | 5% | 5% | 5% | 25% | 5% | 5% | 5% | 5% | 5% |
| **T** | 15% | 15% | 10% | 25% | 10% | 10% | 20% | 10% | 20% |

**Example** (Product Review):
```
Score = C×0.10 + O×0.10 + R×0.15 + E×0.20 + Exp×0.20 + Ept×0.05 + A×0.05 + T×0.15
```

## Rating Scale

| Score | Rating | Meaning |
|-------|--------|---------|
| 90–100 | Excellent | Industry benchmark quality |
| 75–89 | Good | Outperforms most competitors |
| 60–74 | Medium | Meets baseline with room to improve |
| 40–59 | Low | Needs focused optimization |
| 0–39 | Poor | Needs complete restructuring |

## Veto Items

These items trigger a risk alert regardless of total score:

| Item | Trigger | Impact |
|------|---------|--------|
| **T04** Disclosure Statements | Affiliate links present without disclosure | Trust dimension = Fail |
| **C01** Intent Alignment | Clickbait; content doesn't match title | Content credibility destroyed |
| **R10** Content Consistency | Core data contradicts itself | Citation reliability = zero |

---

# Part 4: Content Type Guide

## Decision Tree

```
What is the primary goal?
│
├── Teach users how to do something         → Blog (guides)
├── Your product vs one competitor           → Alternative
├── Objective comparison of 3+ products      → Best-of
├── Show product fits a persona              → Use-case
├── Show verified customer results           → Testimonial
├── Answer common questions                  → FAQ (or embed as faqs[] field)
├── Describe product features                → Landing
└── Share industry insights or trends        → Blog (insights)
```

## Boundary Disambiguation

| Confusion Pair | Type A | Type B | Deciding Factor |
|---------------|--------|--------|----------------|
| 1v1 vs multi-product | Alternative | Best-of | Alternative = persuade to switch; Best-of = help choose |
| User story vs customer proof | Use-case | Testimonial | Use-case = fictional persona; Testimonial = verified customer data |
| FAQ quantity | Embed as `faqs[]` | Dedicated FAQ page | <5 embed; 5–9 either; 10+ dedicated page |
| Product intro vs tutorial | Landing | Blog | Landing = short, feature-focused; Blog = long, educational |

## Citation Tier Requirements

Source tiers: **Tier 1** (.gov/.edu/official docs) | **Tier 2** (industry authorities: Moz, Ahrefs, Forbes) | **Tier 3** (community blogs)

| Content Type | Tier 1 | Tier 2 | Tier 3 | Notes |
|-------------|--------|--------|--------|-------|
| Blog (guides) | 1+ | 0–1 | 0 | Official tool documentation |
| Blog (tools) | 2+ | 1+ | 0–1 | Each tool's pricing page required |
| Blog (insights) | 2+ | 2+ | 0–1 | Research and data sources |
| Alternative | 1+ | 0–1 | 0 | Competitor's official pricing page |
| Best-of | 3+ | 1+ | 0–1 | All tools' pricing pages |
| Use-case | 0–1 | 1+ | 0 | Industry statistics |
| FAQ | 0 | 0 | 0 | User-generated content primarily |
| Testimonial | 0 | 0 | 0 | Verified customer data |
| Landing | 0–1 | 0 | 0 | Own product data |

## Review Frequency

| Content Type | First Review | Regular Review | Re-review Trigger |
|-------------|-------------|----------------|-------------------|
| Blog | Before publish | Quarterly | Ranking drops, info expires |
| Alternative | Before publish | Monthly | Competitor price/feature changes |
| Best-of | Before publish | Monthly | New tools launch, pricing changes |
| Use-case | Before publish | Quarterly | Industry data updates |
| Testimonial | Before publish | Annually | Customer info changes |
| FAQ | Before publish | Quarterly | New frequent questions appear |
| Landing | Before publish | As needed | Product feature updates |

---

# Part 5: Quality Workflow

## 4-Gate Quality Process

```
┌──────────────┬──────────────┬──────────────┬──────────────────────┐
│   Gate 1     │   Gate 2     │   Gate 3     │      Gate 4          │
│  Preparation │ CORE Review  │ EEAT Review  │   Score & Action     │
├──────────────┼──────────────┼──────────────┼──────────────────────┤
│ Set content  │ Review       │ Review       │ Calculate GEO/SEO/   │
│ type         │ C-O-R-E      │ Exp-Ept-A-T  │ Total scores         │
│ Select       │ (40 items)   │ (40 items)   │ Identify top 5       │
│ weights      │ Mark each    │ Mark each    │ improvements         │
│ Prepare      │ Pass/Partial │ Pass/Partial │ Check veto items     │
│ competitor   │ /Fail        │ /Fail        │ Generate action plan │
│ references   │              │              │                      │
├──────────────┼──────────────┼──────────────┼──────────────────────┤
│ Output:      │ Output:      │ Output:      │ Output:              │
│ Config sheet │ CORE card    │ EEAT card    │ Report + priorities  │
└──────────────┴──────────────┴──────────────┴──────────────────────┘
```

## Emergency Brake

These conditions require immediate action — do not wait for full evaluation:

| Trigger | Severity | Immediate Action |
|---------|----------|-----------------|
| T04 Fail: Affiliate links without disclosure | **Critical** | Add disclosure banner at page top |
| C01 Fail: Clickbait title | **Critical** | Rewrite title and first paragraph |
| R10 Fail: Core data contradicts itself | **High** | Verify all data before publishing |
| 3+ Fails in same dimension | **High** | Systematic restructure of that dimension |

## Content Lifecycle

```
Draft ──→ Review ──→ Live ──→ Monitor ──→ Update / Archive
  │         │         │         │              │
Write +   Gate 1-4   Publish   Track KPI    ┌──┴──┐
self-check quality            + rankings   Update  Archive
```

**Update vs Archive Decision**:

```
Is the content still accurate?
├── YES → Update lastVerified date, continue monitoring
└── NO → Can it be updated?
    ├── YES (minor fix) → Update content, note revision
    ├── YES (major rewrite) → Full Gate 1-4 process
    └── NO (topic obsolete) → Archive:
        ① Add expiration notice at page top
        ② Set 301 redirect to replacement content
        ③ Remove from site navigation
```

## KPI Benchmarks

| Metric | Poor | Average | Good | Excellent |
|--------|------|---------|------|-----------|
| Bounce Rate | >70% | 50–70% | 30–50% | <30% |
| Time on Page | <1 min | 1–2 min | 2–4 min | >4 min |
| Scroll Depth | <25% | 25–50% | 50–75% | >75% |
| SERP CTR | <1% | 1–3% | 3–5% | >5% |
| AI Citation Rate | 0% | 5–15% | 15–30% | >30% |

---

# Part 6: CORE Dimensions — Detailed Criteria

> Detailed Pass/Partial/Fail criteria for all 40 CORE check items.
> Items marked with ❌/✅ include wrong/correct examples.

---

## C — Contextual Clarity (10 items)

> Does content clearly answer user intent? Can AI quickly grasp the core value and boundaries?

**C01: Intent Alignment** | Dual ⚡
- **Pass**: Title promise fully delivered in content; intent type (Informational/Transactional/Commercial) is clear
- **Partial**: Title and content mostly aligned with minor drift
- **Fail**: Clickbait; content doesn't match title promise
- ❌ Title "10 Best Free Tools" → content only covers 3 paid tools
- ✅ Title "How to Download YouTube Subtitles (3 Free Methods)" → covers exactly 3 free methods

**C02: Direct Answer** | GEO-First 🎯
- **Pass**: First 150 words contain a clear definition sentence or conclusion phrase (directly citable by AI)
- **Partial**: Answer within first 300 words but with lengthy preamble
- **Fail**: Answer buried in the middle or end; opening is all background
- ❌ "YouTube is the world's largest video platform... [answer in paragraph 4]"
- ✅ "The fastest way to download YouTube subtitles is using NoteLM — paste URL, select format, click download. Free, no account required."

**C03: Query Coverage** | Dual ⚡
- **Pass**: Covers ≥3 query variants (synonyms, long-tail terms, related questions); appropriate entity density
- **Partial**: Covers 1–2 variants
- **Fail**: Only targets a single exact query

**C04: Definition First** | GEO-First 🎯
- **Pass**: All key terms defined on first use ("X is Y..." pattern)
- **Partial**: Most terms defined
- **Fail**: Terms used without definition; readers or AI may misinterpret

**C05: Topic Scope** | GEO-First 🎯
- **Pass**: Explicitly states "This article covers X, not Y"; reaches AI's expected completeness threshold
- **Partial**: Implied boundaries, not explicitly stated
- **Fail**: Scope unclear; content sprawls

**C06: Audience Targeting** | Dual ⚡
- **Pass**: Explicitly states target reader (e.g., "for beginners"); language style matches audience
- **Partial**: Implied through content difficulty
- **Fail**: Audience unclear; inconsistent difficulty level

**C07: Semantic Coherence** | GEO-First 🎯
- **Pass**: Logical connectors between paragraphs (therefore, however, given that); no semantic jumps; follows NLP prediction logic
- **Partial**: Mostly coherent with occasional jumps
- **Fail**: Frequent logic breaks and topic jumps

**C08: Use Case Mapping** | GEO-First 🎯
- **Pass**: Clearly states applicable and inapplicable scenarios; provides decision framework (when to choose A vs B)
- **Partial**: Mentions some scenarios but incomplete
- **Fail**: No use case guidance

**C09: FAQ Coverage** | GEO-First 🎯
- **Pass**: Has structured FAQ (FAQPage Schema or explicit Q&A format) covering high-frequency long-tail follow-ups
- **Partial**: Has Q&A content but not structured
- **Fail**: No FAQ or Q&A content
- ❌ No FAQ section, or only 1–2 generic questions
- ✅ 8+ FAQs with FAQPage Schema, questions in natural language ("Can I download subtitles without an account?")

**C10: Semantic Closure** | Dual ⚡
- **Pass**: Conclusion explicitly answers the opening question and provides next steps or exploration direction
- **Partial**: Has conclusion but doesn't fully loop back to opening
- **Fail**: No conclusion, or conclusion unrelated to opening

---

## O — Organization (10 items)

> Is content structure clear? Does it reduce AI token processing burden and improve extraction efficiency?

**O01: Heading Hierarchy** | Dual ⚡
- **Pass**: Single H1; H2→H3 properly nested; no level skipping; logical progression
- **Partial**: Minor level skipping but overall clear
- **Fail**: Chaotic hierarchy, multiple H1s, or severe skipping

**O02: Summary Box** | GEO-First 🎯
- **Pass**: Has prominent TL;DR, key takeaways, or highlighted summary box
- **Partial**: Has summary but not prominent
- **Fail**: No summary of any kind
- ❌ Article starts with 500-word introduction, no summary anywhere
- ✅ "Key Takeaways: • NoteLM is fastest (2–5 sec) • Tool B best for batch • All support SRT format"

**O03: Data Tables** | GEO-First 🎯
- **Pass**: Uses HTML tables for comparisons, specs, and data with clear headers
- **Partial**: Has tables but unclear structure
- **Fail**: Uses prose where tables would be better
- ❌ "Tool A is cheaper than Tool B which is cheaper than Tool C" (prose comparison)
- ✅ Structured table: | Tool | Price | Speed | Accuracy | Winner |

**O04: List Formatting** | GEO-First 🎯
- **Pass**: Appropriate list usage (~1–2 lists per 500 words); parallel items listed
- **Partial**: Insufficient or slightly excessive list usage
- **Fail**: Lists overused or completely absent

**O05: Schema Markup** | GEO-First 🎯
- **Pass**: Correct JSON-LD (Article/FAQ/HowTo/Product/etc.) matching content type
- **Partial**: Has Schema but type doesn't match well
- **Fail**: No Schema markup
- ❌ FAQ content on page but no FAQPage JSON-LD markup
- ✅ FAQPage + Article + BreadcrumbList JSON-LD matching page content type

**O06: Section Chunking** | GEO-First 🎯
- **Pass**: Each H2/H3 section has a single clear topic; paragraphs 3–5 sentences; easy to scan
- **Partial**: Most sections clear; some paragraphs too long
- **Fail**: Mixed topics within sections; walls of text
- ❌ Single 500-word paragraph covering setup, features, and pricing
- ✅ Separate H2 sections for Setup (3 sentences), Features (4 sentences), Pricing (3 sentences)

**O07: Visual Hierarchy** | SEO-First 🔍
- **Pass**: Important content emphasized through formatting (bold, boxes, color); key concepts and conclusions bolded
- **Partial**: Some visual emphasis
- **Fail**: No visual hierarchy throughout

**O08: Anchor Navigation** | Dual ⚡
- **Pass**: Has table of contents with anchor links; clear breadcrumb navigation
- **Partial**: Has TOC but no anchor links
- **Fail**: Long-form content without any navigation aids

**O09: Information Density** | GEO-First 🎯
- **Pass**: High information density; no filler content; same concept uses same term throughout (no synonym rotation)
- **Partial**: Minor repetition or filler
- **Fail**: Significant filler content

**O10: Multimedia Structure** | Dual ⚡
- **Pass**: Images/videos/code blocks have clear captions; positioned purposefully; convey step or structural information
- **Partial**: Has multimedia but lacks descriptions
- **Fail**: No multimedia, or decorative-only images

---

## R — Referenceability (10 items)

> Are data, evidence, and logic chains sufficient, precise, and verifiable by AI?

**R01: Data Precision** | GEO-First 🎯
- **Pass**: ≥5 precise data points with units (%, USD, kg, ms); directly extractable
- **Partial**: 2–4 precise data points
- **Fail**: No precise data; all vague descriptions ("many", "approximately", "a lot")
- ❌ "NoteLM is very fast and highly accurate with excellent support"
- ✅ "NoteLM processes videos in 2–5 seconds with 94% accuracy, supporting 100+ languages"

**R02: Citation Density** | GEO-First 🎯
- **Pass**: ≥1 external citation per 500 words; ≥3 source types (academic, media, official, industry)
- **Partial**: ≥1 citation per 1000 words; 2 source types
- **Fail**: Insufficient citations or single source type
- ❌ 2000-word article with zero external citations
- ✅ Every 500 words has ≥1 external source ("According to Wyzowl's 2026 Report...")

**R03: Source Hierarchy** | GEO-First 🎯
- **Tier 1**: .gov, .edu, .org, Wikipedia, PubMed, original papers and standards
- **Tier 2**: Industry authority sites (Moz, Ahrefs, Forbes, etc.)
- **Tier 3**: Notable industry blogs
- **Tier 4**: Short links, affiliate links (negative signal)
- **Pass**: Primary sources prioritized; ≥3 Tier 1–2 sources
- **Partial**: 1–2 Tier 1–2 sources
- **Fail**: No authoritative sources or multiple Tier 4 links

**R04: Evidence-Claim Mapping** | GEO-First 🎯
- **Pass**: Every core claim immediately followed by evidence, data, or citation
- **Partial**: Most claims backed by evidence
- **Fail**: Multiple claims without evidence ("empty assertions")

**R05: Methodology Transparency** | GEO-First 🎯
- **Pass**: Sample size, test steps, and statistical criteria documented; conclusions reproducible
- **Partial**: Partial methodology description
- **Fail**: Conclusions without methodological support

**R06: Timestamp & Versioning** | Dual ⚡
- **Pass**: Last updated <1 year; date visible; version change notes present
- **Partial**: Updated 1–3 years ago
- **Fail**: >3 years old or date not visible

**R07: Entity Precision** | GEO-First 🎯
- **Pass**: Full names for people, organizations, product models, locations, dates; no vague references ("a company", "a product")
- **Partial**: Most entities precise; occasional vagueness
- **Fail**: Frequent vague references

**R08: Internal Link Graph** | SEO-First 🔍
- **Pass**: Descriptive anchor texts building conceptual connections; forms topic clusters
- **Partial**: Has internal links but anchor texts are non-descriptive
- **Fail**: No internal links, or "click here" style anchors

**R09: HTML Semantics** | GEO-First 🎯
- **Pass**: Correct use of `<article>`, `<aside>`, `<figure>`, `<time>`, `<cite>` semantic tags
- **Partial**: Some semantic tags used
- **Fail**: Pure `<div>` markup; no semantic structure

**R10: Content Consistency** | Dual ⚡
- **Pass**: All data self-consistent; no broken links (404); no redirect chains; has corrections or revision log
- **Partial**: Mostly consistent with minor discrepancies
- **Fail**: Data contradicts itself or significant broken links

---

## E — Exclusivity (10 items)

> Does content provide information scarce in LLM training data? Why would AI cite you instead of others?

**E01: Original Data** | GEO-First 🎯
- **Pass**: Has first-party data (e.g., "We analyzed 10,000 samples"); dataset is citable
- **Partial**: Some original data
- **Fail**: All data cited from others
- ❌ Restating manufacturer specs from official docs
- ✅ "In our testing of 50 samples across 8 categories, NoteLM achieved 94% accuracy" (original test data)

**E02: Novel Framework** | GEO-First 🎯
- **Pass**: Proposes a named, citable original framework or model (e.g., "the CORE-EEAT Framework")
- **Partial**: Innovates on an existing framework
- **Fail**: No framework innovation

**E03: Primary Research** | GEO-First 🎯
- **Pass**: Has documented research process (experimental conditions, metrics, control groups)
- **Partial**: Some primary research
- **Fail**: No primary research

**E04: Contrarian View** | GEO-First 🎯
- **Pass**: Challenges mainstream consensus with data or logic backing
- **Partial**: Some differentiated views
- **Fail**: Entirely follows conventional wisdom

**E05: Proprietary Visuals** | Dual ⚡
- **Pass**: ≥2 original infographics, flowcharts, or data visualizations
- **Partial**: 1 original visualization
- **Fail**: No original visuals

**E06: Gap Filling** | GEO-First 🎯
- **Pass**: Covers niche questions or edge cases that competitors miss
- **Partial**: Partially fills content gaps
- **Fail**: Content highly similar to competitors

**E07: Practical Tools** | Dual ⚡
- **Pass**: ≥1 downloadable or copyable template, checklist, calculator, or interactive component
- **Partial**: Has examples but not actionable enough
- **Fail**: No practical tools

**E08: Depth Advantage** | GEO-First 🎯
- **Pass**: Depth clearly exceeds competing content on same topic
- **Partial**: Comparable depth to competitors
- **Fail**: Shallower than competitors

**E09: Synthesis Value** | GEO-First 🎯
- **Pass**: Combines cross-domain knowledge to produce new insights
- **Partial**: Some cross-domain content but combination isn't novel
- **Fail**: Knowledge siloed; no cross-domain integration

**E10: Forward Insights** | GEO-First 🎯
- **Pass**: Data-backed predictions or trend analysis with clear reasoning
- **Partial**: Some forward-looking content
- **Fail**: Only discusses past and present

---

# Part 7: EEAT Dimensions — Detailed Criteria

> Detailed Pass/Partial/Fail criteria for all 40 EEAT check items.
> Items marked with ❌/✅ include wrong/correct examples.

---

## Exp — Experience (10 items)

> Proves the creator "was there" with first-hand, real-world experience.

**Exp01: First-Person Narrative** | SEO-First 🔍
- **Pass**: First-person + action verb combinations ("I tested", "We analyzed")
- **Partial**: Has only first-person OR only action verbs
- **Fail**: Entirely third-person narration
- ❌ "This tool provides fast transcription with high accuracy"
- ✅ "I tested NoteLM on 50 YouTube videos over 2 weeks and found 94% accuracy in English content"

**Exp02: Sensory Details** | SEO-First 🔍
- **Pass**: ≥10 sensory words (smooth, heavy, bright, crisp, sluggish)
- **Partial**: 5–9 sensory words
- **Fail**: <5 sensory words

**Exp03: Process Documentation** | Dual ⚡
- **Pass**: Detailed operation or usage process with steps, timeline, and key decision points
- **Partial**: Partial process description
- **Fail**: No process documentation

**Exp04: Tangible Proof** | SEO-First 🔍
- **Pass**: ≥2 clearly original images (photos/screenshots/hand-drawn) with timestamps or environmental context
- **Partial**: 1 original image
- **Fail**: No original images
- ❌ Stock photo of a laptop with generic overlay text
- ✅ Original screenshot with timestamp showing actual transcription result + accuracy comparison photo

**Exp05: Usage Duration** | SEO-First 🔍
- **Pass**: Explicitly states testing or usage duration ("after 3 months of continuous use")
- **Partial**: Implied duration but not explicit
- **Fail**: No duration stated

**Exp06: Problems Encountered** | Dual ⚡
- **Pass**: Honestly shares ≥2 problems encountered, with solutions or workarounds
- **Partial**: Mentions 1 problem
- **Fail**: All positive descriptions; no problems mentioned
- ❌ "NoteLM is perfect — no issues at all, 10/10 recommended!"
- ✅ "Two issues: 1) Heavy accents dropped accuracy to ~80%, 2) Videos over 3 hours sometimes timeout"

**Exp07: Before/After Comparison** | SEO-First 🔍
- **Pass**: Clear before/after comparison or side-by-side comparison with alternatives
- **Partial**: Implied comparison
- **Fail**: No comparison

**Exp08: Quantified Metrics** | Dual ⚡
- **Pass**: Quantified experience data (time spent, cost, success rate, performance numbers)
- **Partial**: Some quantified data
- **Fail**: Purely subjective experience with no quantification

**Exp09: Repeated Testing** | SEO-First 🔍
- **Pass**: States that multiple tests or long-term tracking were conducted
- **Partial**: Implied repeat testing
- **Fail**: Single test only

**Exp10: Limitations Acknowledged** | GEO-First 🎯
- **Pass**: Explicitly states experience limitations ("We only tested X scenario", "Not tested on Y platform")
- **Partial**: Partially acknowledges limitations
- **Fail**: No limitations acknowledged
- ❌ "This is the best tool for everyone in every situation"
- ✅ "Limitation: We only tested English and Spanish. Results may differ for tonal languages like Mandarin"

---

## Ept — Expertise (10 items)

> Proves the creator has the knowledge and skills to get the subject right.

**Ept01: Author Identity** | SEO-First 🔍
- **Pass**: Byline + avatar + bio (>30 words) with clear role boundaries
- **Partial**: Has 1–2 of the above
- **Fail**: No author information
- ❌ "By Admin" with no photo or bio
- ✅ "By Sarah Chen, AI Product Researcher (5+ years). Previously at Google AI, published in ACM. [Photo + Social links]"

**Ept02: Credentials Display** | SEO-First 🔍
- **Pass**: Displays relevant professional qualifications (degrees, certificates, years of experience, project history)
- **Partial**: Has credentials but weak relevance
- **Fail**: No credentials displayed

**Ept03: Professional Vocabulary** | Dual ⚡
- **Pass**: Accurate use of industry jargon; average word length >5.5 characters; no terminology misuse
- **Partial**: Moderate professionalism
- **Fail**: Vocabulary too simple or terms misused

**Ept04: Technical Depth** | Dual ⚡
- **Pass**: Technical details accurate and deep; parameters, thresholds, and examples are actionable
- **Partial**: Has technical content but shallow
- **Fail**: Technical content superficial or contains obvious errors
- ❌ "The AI uses advanced technology to transcribe"
- ✅ "Uses Whisper large-v3 model (1550M params), WER of 5.2% on LibriSpeech, supports beam_size=5 for accuracy"

**Ept05: Methodology Rigor** | GEO-First 🎯
- **Pass**: Analysis methodology is clear, reproducible, and follows industry standards
- **Partial**: Has methodology but not rigorous enough
- **Fail**: No methodology or methodology has obvious flaws

**Ept06: Edge Case Awareness** | Dual ⚡
- **Pass**: Discusses ≥2 edge cases or exceptions, stating "when this doesn't apply"
- **Partial**: Mentions 1 edge case
- **Fail**: No edge cases considered

**Ept07: Historical Context** | SEO-First 🔍
- **Pass**: Demonstrates understanding of the field's development history; has timeline or evolution explanation
- **Partial**: Some historical background
- **Fail**: Lacks historical perspective

**Ept08: Reasoning Transparency** | GEO-First 🎯
- **Pass**: Explicitly states cause-effect relationships and tradeoffs ("We chose A over B because...")
- **Partial**: Some reasoning but incomplete
- **Fail**: Conclusions given without reasoning
- ❌ "NoteLM is the best choice" (no reasoning given)
- ✅ "We recommend NoteLM over Otter.ai because: free vs $16.99/mo, 94% vs 91% accuracy, no account needed"

**Ept09: Cross-domain Integration** | Dual ⚡
- **Pass**: Effectively integrates cross-domain knowledge, generating new perspectives
- **Partial**: Some cross-domain content
- **Fail**: Knowledge siloed; single domain

**Ept10: Editorial Process** | SEO-First 🔍
- **Pass**: Has "Reviewed by" or "Fact-checked by" labels clearly visible
- **Partial**: Has editorial review but no visible labels
- **Fail**: No editorial process

---

## A — Authority (10 items)

> Proves that third parties — especially high-authority entities — recognize this source.

**A01: Backlink Profile** | SEO-First 🔍
- **Pass**: Naturally cited by authoritative sites (.edu, .gov, or industry leaders)
- **Partial**: Some backlinks
- **Fail**: No notable backlinks

**A02: Media Mentions** | SEO-First 🔍
- **Pass**: Has "Featured in" with media logos or mainstream news coverage
- **Partial**: Minor media mentions
- **Fail**: No media mentions

**A03: Industry Awards** | SEO-First 🔍
- **Pass**: Displays relevant industry awards or certification body recognition
- **Partial**: Has awards but weak relevance
- **Fail**: No awards

**A04: Publishing Record** | SEO-First 🔍
- **Pass**: Conference talks, professional publications, academic papers, or patents
- **Partial**: Some publishing record
- **Fail**: No publishing record

**A05: Brand Recognition** | Dual ⚡
- **Pass**: Brand has industry recognition; brand terms have search volume
- **Partial**: Some brand awareness
- **Fail**: Brand unknown

**A06: Social Proof** | SEO-First 🔍
- **Pass**: Authentic user reviews and recommendations (real photos, specific content, natural timing distribution)
- **Partial**: Reviews present but credibility uncertain
- **Fail**: No social proof

**A07: Knowledge Graph Presence** | Dual ⚡
- **Pass**: Has Wikipedia entry or Google Knowledge Panel
- **Partial**: Partially indexed in knowledge graphs
- **Fail**: Not in any knowledge graph

**A08: Entity Consistency** | GEO-First 🎯
- **Pass**: Brand and author name and description consistent across the entire web; facilitates AI attribution
- **Partial**: Mostly consistent
- **Fail**: Inconsistent information across web; contradictions exist

**A09: Partnership Signals** | SEO-First 🔍
- **Pass**: Displays partnerships with authoritative organizations or industry body endorsements
- **Partial**: Some partnership signals
- **Fail**: No partnership signals

**A10: Community Standing** | SEO-First 🔍
- **Pass**: Active and influential in professional communities; high-quality discussions and ratings traceable
- **Partial**: Some community participation
- **Fail**: No community presence

---

## T — Trust (10 items)

> Is the site technically, legally, and governance-wise trustworthy?

**T01: Legal Compliance** | SEO-First 🔍
- **Required**: Privacy Policy, Terms of Service
- **Bonus**: Cookie Policy, GDPR compliance, Affiliate Disclosure
- **Pass**: Required pages present plus bonus items
- **Partial**: Required pages present only
- **Fail**: Missing required pages
- ❌ No Privacy Policy or Terms page; footer only has copyright notice
- ✅ Footer links to Privacy Policy, Terms of Service, Cookie Policy, GDPR compliance page

**T02: Contact Transparency** | SEO-First 🔍
- **Pass**: Physical address or ≥2 contact methods; verifiable real entity behind the site
- **Partial**: Email only
- **Fail**: No contact information (anonymous site)

**T03: Security Standards** | SEO-First 🔍
- **Pass**: Site-wide HTTPS; no security warnings; extra security for payment and login pages
- **Partial**: Has HTTPS but some pages insecure
- **Fail**: Uses HTTP

**T04: Disclosure Statements** | Dual ⚡ — **VETO ITEM**
- **Pass**: Affiliate links present AND clearly disclosed (at page top or next to links)
- **Partial**: No affiliate links (not applicable)
- **Fail**: Affiliate links present WITHOUT disclosure — **automatic veto**
- ❌ Article contains affiliate links but no disclosure anywhere — **veto triggered**
- ✅ Page top: "Disclosure: Some links are affiliate. We earn commission at no extra cost. All opinions are our own."

**T05: Editorial Policy** | SEO-First 🔍
- **Pass**: Content standards, review process, and editorial team information published
- **Partial**: Some editorial guidelines
- **Fail**: No editorial policy

**T06: Correction & Update Policy** | Dual ⚡
- **Pass**: Has corrections page, update principles, and revision history
- **Partial**: Has update dates but no formal correction mechanism
- **Fail**: No correction or update mechanism
- ❌ Article published in 2024 with no update date or correction history
- ✅ "Last updated: 2026-02-01. Correction (2026-01-15): Updated Otter.ai pricing from $12.99 to $16.99/mo"

**T07: Ad Experience** | SEO-First 🔍
- **Pass**: Ads <30% of page area; no fullscreen popups; doesn't obstruct content
- **Partial**: Ads 30–50% of page area
- **Fail**: Ads >50% or has fullscreen/deceptive popups

**T08: Risk Disclaimers** | Dual ⚡
- **Pass**: YMYL topics (finance/health/legal) have necessary disclaimers and risk warnings
- **Partial**: Some disclaimer coverage
- **Fail**: YMYL content with no disclaimers

**T09: Review Authenticity** | Dual ⚡
- **Pass**: User reviews show authenticity signals (real photos, specific details, natural timing distribution)
- **Partial**: Reviews present but authenticity uncertain
- **Fail**: Reviews obviously fake or absent

**T10: Customer Support** | SEO-First 🔍
- **Pass**: Clear return/refund policy, complaint channels, and defined response SLA
- **Partial**: Policy exists but unclear
- **Fail**: No customer support or return policy

---

# Part 8: Advanced Reference

## AI Engine Citation Preferences

| Engine | Citation Style | Preferred Content | Priority Items |
|--------|---------------|-------------------|----------------|
| **Google AI Overview** | Snippet extraction from paragraphs, lists, tables, FAQs | Structured paragraphs, definition sentences, comparison tables, FAQ pairs | C02, O03, O05, C09 |
| **ChatGPT Browse** | Conversational answers with citation links | Complete information blocks, data statements with citations, standalone conclusions | C02, R01, R02, E01 |
| **Perplexity AI** | Multi-source synthesis + inline citations | Original research data, tiered sources, methodology-transparent conclusions | E01, R03, R05, Ept05 |
| **Claude** | Precision-first with nuanced arguments | Argument + evidence chains, balanced views, transparent reasoning | R04, Ept08, Exp10, R03 |

### Top 6 GEO-First Priority Items

These items have the highest impact on AI engine visibility across all engines:

| Rank | Item | Why It Matters |
|------|------|---------------|
| 1 | **C02** Direct Answer | All engines extract from the first paragraph; first 150 words determine citation |
| 2 | **C09** FAQ Coverage | FAQ structure directly matches user follow-ups; heavily extracted by Google AI Overview and Perplexity |
| 3 | **O03** Data Tables | Comparison data is the most extractable structured format; significantly higher citation rate than prose |
| 4 | **O05** Schema Markup | JSON-LD helps AI understand content type and structure; increases correct parsing probability |
| 5 | **E01** Original Data | AI prefers citing exclusive, verifiable data sources over second-hand summaries |
| 6 | **O02** Summary Box | Key Takeaways are often the first choice for AI summary citations |

## Implementation Mapping

> Maps check items to UI components, Schema types, and data fields.

| Check Item | Component | Schema | Data Field |
|-----------|-----------|--------|-----------|
| C02 Direct Answer | DirectAnswerBox | — | excerpt, directAnswer |
| C09 FAQ Coverage | FAQAccordion (includeSchema) | FAQPage | faqs[] |
| O02 Summary Box | SummaryBox (7 variants) | — | keyTakeaways[] |
| O03 Data Tables | DataTable (5 variants) | — | comparisons, tools |
| O05 Schema Markup | JSON-LD generator | Per content type | Auto-generated |
| O08 Anchor Nav | TableOfContents | — | Auto-extract H2/H3 |
| R02 Citations | CitationsList | — | eeat.externalCitations[] |
| R03 Source Tiers | CitationsList (showTierBadge) | — | eeat.externalCitations[].tier |
| R05 Methodology | MethodologySection | — | methodology |
| R06 Timestamp | VerificationBadge | — | lastVerified, updateDate |
| R08 Internal Links | RelatedResourcesSection | BreadcrumbList | relatedPosts[], relatedTools[] |
| Exp06 Problems | ProConsList | — | cons[] |
| Exp07 Before/After | DataTable (before-after) | — | beforeAfter |
| Ept01 Author | AuthorCard | Person | eeat.authorInfo |
| A06 Social Proof | TestimonialCard | Review | testimonials[] |
| T04 Disclosure | Disclosure banner | — | eeat.dataDisclaimer |

### Schema by Content Type

| Content Type | Required Schema | Conditional Schema |
|-------------|----------------|--------------------|
| Blog (guides) | Article, Breadcrumb | FAQ, HowTo |
| Blog (tools) | Article, Breadcrumb | FAQ, Review |
| Blog (insights) | Article, Breadcrumb | FAQ |
| Alternative | Comparison*, Breadcrumb, FAQ | AggregateRating |
| Best-of | ItemList, Breadcrumb, FAQ | AggregateRating per tool |
| Use-case | WebPage, Breadcrumb, FAQ | — |
| FAQ | FAQPage, Breadcrumb | — |
| Landing | SoftwareApplication, Breadcrumb, FAQ | WebPage |
| Testimonial | Review, Breadcrumb | FAQ, Person |

*Comparison = custom implementation extending Product Schema.

## Common Errors

| # | Error | Item | Wrong | Right |
|---|-------|------|-------|-------|
| 1 | Answer buried | C02 | 500-word preamble before answer | Core answer in first 150 words |
| 2 | Clickbait title | C01 | "Shocking! This method is insane" | Title accurately describes content |
| 3 | Heading skip | O01 | H1 jumps to H3, no H2 | H1→H2→H3 sequential nesting |
| 4 | Wall of text | O06 | Single 300-word paragraph | 3–5 sentences per paragraph, by topic |
| 5 | No summary | O02 | No TL;DR or key takeaways | Key Takeaways box at article top |
| 6 | Vague numbers | R01 | "very fast", "very cheap" | "120ms response", "$29/mo" |
| 7 | Unsourced stats | R02 | "Studies show 90% of users..." | Include source link and year |
| 8 | Stale pricing | R06 | 2023 prices shown, no date | "Pricing as of 2026-02" |
| 9 | Broken links | R10 | External links to 404 pages | Regular link audits; fix or remove |
| 10 | No unique value | E01 | Restates official docs verbatim | Add original test data or comparisons |
| 11 | No first person | Exp01 | Entirely third-person tone | Add "I tested" or "We found" |
| 12 | Only positives | Exp06 | Zero negatives; reads like an ad | Honestly share ≥2 downsides |
| 13 | No author info | Ept01 | No byline, avatar, or bio | Name + photo + 30-word bio |
| 14 | Undisclosed affiliate | T04 | Affiliate links without disclosure | Disclosure banner at page top |
| 15 | Missing FAQ Schema | O05 | Q&A content without JSON-LD | Add FAQPage Schema markup |

## MECE Disambiguation Rules

When unsure which dimension a check item belongs to:

| Rule | Assign To |
|------|-----------|
| Visible in the article or page | CORE |
| Requires checking author, org, or site | EEAT |
| "Can this sentence be verified?" | CORE-R |
| "Is this entity worth trusting?" | EEAT-T |
| "Does this content add unique value?" | CORE-E |
| "Does the value come from personal experience?" | EEAT-Exp |

### Commonly Confused Pairs

| Pair | Disambiguation |
|------|---------------|
| **R (Citation Density)** vs **A (Backlinks)** | R = sources YOU cite (outbound); A = others citing YOU (inbound) |
| **CORE-E (Exclusivity)** vs **Exp (Experience)** | E = is the content unique (information gain); Exp = did the creator personally experience it |
| **R (Timestamp)** vs **T (Correction Policy)** | R = is info current (freshness); T = is there a maintenance mechanism (governance) |
| **O (Schema)** vs **R (HTML Semantics)** | O = page-level JSON-LD; R = semantic tags in content (`<article>`, `<time>`) |
| **R (Method Transparency)** vs **Ept (Method Rigor)** | R = was the method documented (transparency); Ept = is the method sound (quality) |
| **Ept (Reasoning)** vs **R (Evidence Mapping)** | Ept = is reasoning explainable; R = does each claim have an evidence chain |

---

## Changelog

- **v1.0** (2026-02-06): Initial release — clean English benchmark with progressive disclosure architecture
