---
name: phtn-intelliops-theme
description: >
  PHTN.ai IntelliOps deck Theme DNA — complete slide template catalog extracted directly from the
  master IntelliOps proposal deck. Load this skill before creating or editing ANY PHTN.ai or
  IntelliOps deck. Contains exact OOXML for every distinct slide layout, embedded logo assets
  (zero file management), brand constants, and strict editing rules. When asked to use a named
  slide template (e.g. "use the section divider", "use the maturity model slide", "use the UC
  flow deep dive"), view the corresponding XML file in the slides/ folder, copy it exactly,
  and edit only text content — never recreate layout from scratch. Triggers: any PHTN.ai deck,
  IntelliOps proposal, Darden deck, Dutch Bros deck, Coty deck, Banfield deck, or any mention
  of "IntelliOps", "PHTN.ai", "AMS proposal", "IntelliOps slide", or any client deck for Photon.
---

# PHTN.ai IntelliOps — Theme DNA Skill

## ⚠️ PRIME DIRECTIVE — READ FIRST

**NEVER invent a slide layout. ALWAYS use the XML templates in `slides/`.**

Every time Claude creates a slide from scratch instead of copying XML, the output is wrong:
- Wrong logo (or no logo)
- Boxy generic layouts
- Wrong font hierarchy
- Wrong colour treatment on headings

**The correct workflow is always:**
1. `view` the relevant slide XML from `slides/`
2. Copy the entire XML
3. Edit ONLY the text nodes (`<a:t>` elements) and rId references
4. Never change positions, sizes, fonts, colours, or shapes

---

## Skill File Structure

```
phtn-intelliops-theme/
├── SKILL.md                          ← you are here (read this first, always)
├── USAGE_GUIDE.md                    ← plain-English guide for colleagues
├── slides/                           ← 39 XML templates — one per distinct layout
│   ├── 01_COVER.xml                  ← Cover / title slide
│   ├── 02_AGENDA.xml                 ← Agenda / table of contents
│   ├── 03_DARK_CONTENT.xml           ← Dark charcoal bg, left heading, right long-form text
│   ├── 04_WHY_AI_4BOX.xml            ← 4 numbered problem statements (01–04)
│   ├── 05_INTRODUCING.xml            ← 3-panel hero (WHY / WHY NOW / WHY PHOTON)
│   ├── 06_THREE_COL.xml              ← 3-column benefits (Team / Business / Partnership)
│   ├── 07_TIER_TABLE.xml             ← L1/L2/L3 before/after comparison table
│   ├── 08_MATURITY_4STAGE.xml        ← 4-stage horizontal maturity model
│   ├── 09_TEAMS_EVOLUTION.xml        ← Two-column org evolution (Traditional → IntelliOps)
│   ├── 10_SECTION_DIVIDER.xml        ← Section break (+ texture, charcoal bg, gold title)
│   ├── 11_ITSM_PILLAR.xml            ← ITSM pillar (traditional / new ways / outcomes)
│   ├── 14_SLA_TABLE.xml              ← Two-tier SLA table (AI-tier + Human-in-loop)
│   ├── 16_ARCH_OVERVIEW.xml          ← Architecture overview (4 capability cards)
│   ├── 17_TECHNICAL_ARCH.xml         ← Full technical architecture diagram (dense)
│   ├── 18_SCALE_3COL.xml             ← Scaling narrative (3 columns, large text blocks)
│   ├── 20_UC_LIBRARY_TABLE.xml       ← Full 16-UC library table (categorised rows)
│   ├── 21_UC_KEY_CASES.xml           ← Key use cases with sub-agent breakdown table
│   ├── 22_UC_FLOW_DEEPDIVE.xml       ← 10-step UC agent flow (DETECT/DIAGNOSE/RESPOND)
│   ├── 25_UC4_L1_AUTOMATION.xml      ← UC4 before/after step flow (Today vs With PHTN.ai)
│   ├── 26_SUBAGENT_MATRIX.xml        ← Sub-agent reuse matrix (UC × agent grid)
│   ├── 28_DEMO_VIDEO.xml             ← Demo video placeholder (ILLUSTRATIVE label)
│   ├── 30_ASSUMPTIONS_TEXT.xml       ← Assumptions & constraints (bulleted list)
│   ├── 32_ROADMAP_4PHASE.xml         ← 4-phase delivery roadmap
│   ├── 33_PHASE1_TIMELINE.xml        ← Phase 1 week-by-week timeline
│   ├── 35_ROI_FUNNEL.xml             ← ROI 4-box funnel + priority breakdown table
│   ├── 36_VALUE_PHASE_RAMP.xml       ← Value builds phase by phase (3 metrics, 4 phases)
│   ├── 38_STAFFING_PLAN.xml          ← Staffing org chart (onsite/offshore)
│   ├── 40_PRICING_OPTIONS.xml        ← Pricing 4 options (Marketplace/SaaS/OEM/License)
│   ├── 41_FINANCIAL_SUMMARY.xml      ← Phase financial table (agents, licensing, cost)
│   ├── 42_TOKEN_SIZING.xml           ← Token consumption sizing (Small/Mid/Enterprise)
│   ├── 45_STEADY_STATE_COST.xml      ← Steady-state cost model (4 cost buckets + ROI)
│   ├── 47_CASE_STUDY_COMPACT.xml     ← Case study compact format (Sony/Frontier style)
│   ├── 50_CASE_STUDY_DETAILED.xml    ← Case study detailed format (Coty/Banfield style)
│   ├── 53_LOGO_DIVIDER.xml           ← Logo-only appendix divider
│   ├── 55_RESOURCE_TRANSITION.xml    ← Resource transition table (role ramp-down/up by phase)
│   ├── 56_PLATFORM_AGNOSTIC.xml      ← Platform-agnostic IntelliOps intro (appendix)
│   ├── 57_ITSM_SUMMARY.xml           ← ITSM 3-pillar summary (Incident/Problem/Change)
│   ├── 58_ITSM_PILLARS_DETAILED.xml  ← 5 ITSM pillars numbered (detailed process)
│   ├── 59_SERVICE_ACCEPTANCE.xml     ← Service acceptance / peak event pillar
│   └── 61_TIME_ZONE_OVERLAP.xml      ← Work timings & time zone overlap diagram
└── assets/
    ├── logo_main.b64                 ← Primary logo EMF (90,988 bytes) — content slides
    ├── logo_section.b64              ← Section logo EMF (90,836 bytes) — section dividers
    └── bg_texture.b64                ← Background texture PNG (image12.png)
```

---

## Brand Constants

### Slide Canvas
- **Width:** 12,192,000 EMU = 13.333 inches
- **Height:** 6,858,000 EMU = 7.5 inches
- **Presentation XML declaration:** `<p:sldSz cx="12192000" cy="6858000"/>`

### Colours (never prefix with `#` — corrupts PPTX)
```
ECBB69   Gold         — first word of headings, hero text, accent fills, stat bars
5BA4AF   Teal         — AI/active accent, focus highlights
383838   Dark         — second word of headings, dark card fills
484848   Charcoal     — section divider backgrounds, dark panels
FFFFFF   White        — body text on dark bg, reversed text
000000   Black        — body text on white/light bg
B9B9B9   Gray         — subdued labels (OFFSHORE badge etc.)
999999   MidGray      — footer bar
```

### Fonts
```
GT Walsheim Black    — main headings (28–54pt), hero text, slide titles
GT Walsheim Bold     — financial values, emphasised labels (18–28pt)
GT Walsheim Medium   — subheadings, card labels, step tags (10–20pt)
GT Walsheim Light    — body copy, captions, footer (8–14pt)
GT Walsheim Thin     — decorative "+ + +" texture only (16pt)
```

### Heading Treatment — THE MOST IMPORTANT RULE
**Every slide title uses TWO text runs, never one:**
- Run 1: first word(s) → colour `ECBB69` (gold), GT Walsheim Black
- Run 2: remaining word(s) → colour `383838` (dark) OR `FFFFFF` (white on dark bg), GT Walsheim Black

```xml
<!-- CORRECT: two-run gold+dark heading -->
<a:r>
  <a:rPr sz="3600" b="1"><a:solidFill><a:srgbClr val="ECBB69"/></a:solidFill>
  <a:latin typeface="GT Walsheim Black" pitchFamily="2" charset="77"/></a:rPr>
  <a:t>introducing: </a:t>
</a:r>
<a:r>
  <a:rPr sz="3600" b="1"><a:solidFill><a:srgbClr val="383838"/></a:solidFill>
  <a:latin typeface="GT Walsheim Black" pitchFamily="2" charset="77"/></a:rPr>
  <a:t>PHTN.ai IntelliOps</a:t>
</a:r>

<!-- WRONG: single run, noFill, or wrong colour -->
<a:r><a:rPr><a:noFill/></a:rPr><a:t>Introducing PHTN.ai IntelliOps</a:t></a:r>
```

---

## Logo Embedding — Zero File Management

The logos are stored as base64 in `assets/`. To embed in a new PPTX:

### Step 1 — Read the b64 file
```python
with open('assets/logo_main.b64') as f:
    logo_b64 = f.read().strip()
```

### Step 2 — Inject into the PPTX media folder
When editing XML directly (python-pptx or zipfile approach):
```python
import base64, zipfile

logo_bytes = base64.b64decode(logo_b64)
# Write into the zip as ppt/media/image_LOGO.emf
with zipfile.ZipFile('output.pptx', 'a') as z:
    z.writestr('ppt/media/image_LOGO.emf', logo_bytes)
```

### Step 3 — Add the relationship in the slide rels file
```xml
<Relationship Id="rIdLOGO" 
  Type="http://schemas.openxmlformats.org/officeDocument/2006/relationships/image"
  Target="../media/image_LOGO.emf"/>
```

### Step 4 — Reference in the slide XML pic element
```xml
<p:pic>
  <p:nvPicPr>
    <p:cNvPr id="99" name="PHTN_logo"/>
    <p:cNvPicPr><a:picLocks noChangeAspect="1"/></p:cNvPicPr>
    <p:nvPr/>
  </p:nvPicPr>
  <p:blipFill>
    <a:blip r:embed="rIdLOGO"><a:lum/><a:alphaModFix/></a:blip>
    <a:srcRect l="-1" t="-1" r="32202" b="32202"/>
    <a:stretch><a:fillRect/></a:stretch>
  </p:blipFill>
  <p:spPr>
    <a:xfrm><a:off x="348616" y="307058"/><a:ext cx="596053" cy="596053"/></a:xfrm>
    <a:prstGeom prst="rect"><a:avLst/></a:prstGeom>
  </p:spPr>
</p:pic>
```

**Logo placement (standard content slides):**
- Position: x=348,616 EMU, y=307,058 EMU (top-left)
- Size: cx=596,053 EMU, cy=596,053 EMU (~0.65" × 0.65")
- Logo file: `logo_main.b64` (image3.emf) for content slides
- Logo file: `logo_section.b64` (image6.emf) for section dividers

### When cloning an existing template slide:
The logo is already in the XML with its rId. Simply preserve the rId and ensure the media file is copied to the new PPTX's media folder from assets/logo_main.b64. You do NOT need to create a new pic element — it's already in every template slide XML.

---

## Slide Catalog — When to Use Which Template

| Template Name | Slide File | Use When |
|---|---|---|
| COVER | 01_COVER.xml | First slide of any deck |
| AGENDA | 02_AGENDA.xml | Second slide — table of contents |
| DARK_CONTENT | 03_DARK_CONTENT.xml | Long narrative text on dark charcoal bg |
| WHY_AI_4BOX | 04_WHY_AI_4BOX.xml | 4 numbered problem statements (01–04) |
| INTRODUCING | 05_INTRODUCING.xml | 3-panel hero (Why / Why Now / Why [Partner]) |
| THREE_COL | 06_THREE_COL.xml | 3-column benefits (Team / Business / Partnership) |
| TIER_TABLE | 07_TIER_TABLE.xml | Before/after comparison table by tier (L1/L2/L3) |
| MATURITY_4STAGE | 08_MATURITY_4STAGE.xml | 4-stage maturity progression (horizontal) |
| TEAMS_EVOLUTION | 09_TEAMS_EVOLUTION.xml | Two-column role evolution |
| SECTION_DIVIDER | 10_SECTION_DIVIDER.xml | Section break between major topics |
| ITSM_PILLAR | 11_ITSM_PILLAR.xml | Any process pillar (Traditional / New Ways / Outcomes) |
| SLA_TABLE | 14_SLA_TABLE.xml | Two-tier SLA or commitment table |
| ARCH_OVERVIEW | 16_ARCH_OVERVIEW.xml | High-level architecture with 4 capability cards |
| TECHNICAL_ARCH | 17_TECHNICAL_ARCH.xml | Full dense technical architecture diagram |
| SCALE_3COL | 18_SCALE_3COL.xml | Scaling narrative with 3 large text columns |
| UC_LIBRARY_TABLE | 20_UC_LIBRARY_TABLE.xml | Full use case library categorised table |
| UC_KEY_CASES | 21_UC_KEY_CASES.xml | Key use cases with per-UC sub-agent breakdown |
| UC_FLOW_DEEPDIVE | 22_UC_FLOW_DEEPDIVE.xml | 10-step agent flow (DETECT / DIAGNOSE / RESPOND) |
| UC4_L1_AUTOMATION | 25_UC4_L1_AUTOMATION.xml | Before/after step-by-step flow (Today vs AI) |
| SUBAGENT_MATRIX | 26_SUBAGENT_MATRIX.xml | Sub-agent reuse matrix (UC × agent grid) |
| DEMO_VIDEO | 28_DEMO_VIDEO.xml | Demo video placeholder slide |
| ASSUMPTIONS_TEXT | 30_ASSUMPTIONS_TEXT.xml | Bulleted assumptions & constraints |
| ROADMAP_4PHASE | 32_ROADMAP_4PHASE.xml | 4-phase delivery roadmap |
| PHASE1_TIMELINE | 33_PHASE1_TIMELINE.xml | Week-by-week phase 1 timeline |
| ROI_FUNNEL | 35_ROI_FUNNEL.xml | 4-box revenue funnel + priority breakdown table |
| VALUE_PHASE_RAMP | 36_VALUE_PHASE_RAMP.xml | Phase-by-phase value ramp (3 metrics) |
| STAFFING_PLAN | 38_STAFFING_PLAN.xml | Staffing org chart (onsite/offshore) |
| PRICING_OPTIONS | 40_PRICING_OPTIONS.xml | 4 commercial options (Marketplace/SaaS/OEM/License) |
| FINANCIAL_SUMMARY | 41_FINANCIAL_SUMMARY.xml | Phase financial table (agents, discounts, total) |
| TOKEN_SIZING | 42_TOKEN_SIZING.xml | Token consumption sizing by tier |
| STEADY_STATE_COST | 45_STEADY_STATE_COST.xml | Year 2 steady-state cost model + 8× ROI |
| CASE_STUDY_COMPACT | 47_CASE_STUDY_COMPACT.xml | Compact case study (Sony/Frontier format) |
| CASE_STUDY_DETAILED | 50_CASE_STUDY_DETAILED.xml | Detailed case study (Coty/Banfield format) |
| LOGO_DIVIDER | 53_LOGO_DIVIDER.xml | Logo-only appendix divider |
| RESOURCE_TRANSITION | 55_RESOURCE_TRANSITION.xml | Role ramp-down/up transition table by phase |
| PLATFORM_AGNOSTIC | 56_PLATFORM_AGNOSTIC.xml | Platform-agnostic IntelliOps intro (appendix) |
| ITSM_SUMMARY | 57_ITSM_SUMMARY.xml | ITSM 3-pillar summary (Incident/Problem/Change) |
| ITSM_PILLARS_DETAILED | 58_ITSM_PILLARS_DETAILED.xml | 5 ITSM pillars with numbered process detail |
| SERVICE_ACCEPTANCE | 59_SERVICE_ACCEPTANCE.xml | Service acceptance or peak event pillar |
| TIME_ZONE_OVERLAP | 61_TIME_ZONE_OVERLAP.xml | Work timings & time zone overlap diagram |

---

## Workflow — How to Use This Skill

### Building a new deck for a new client

```
1. view SKILL.md (this file) — establish context
2. For each slide needed:
   a. view slides/NN_TEMPLATE_NAME.xml
   b. Identify all <a:t> text nodes that are Darden-specific (see variable list below)
   c. Replace with client-specific content
   d. Keep ALL positions, sizes, shapes, colours, fonts IDENTICAL
3. Handle logo: assets/logo_main.b64 is already referenced in each slide XML
   — ensure it is copied into the new PPTX media folder
4. Handle background texture: assets/bg_texture.b64 — same process
```

### Editing a single slide

```
1. view slides/NN_TEMPLATE_NAME.xml
2. Find the <a:t> node containing the text to change
3. Replace text content only — never touch surrounding XML attributes
4. Output the modified XML
```

### Using a template for a completely different slide topic

```
Example: "Use the 4-box problem statement layout for Dutch Bros challenges"
1. view slides/04_WHY_AI_4BOX.xml
2. Replace the 4 problem titles and body texts with Dutch Bros content
3. Keep layout, numbering style (01/02/03/04), colours, fonts exactly as-is
4. Only text nodes change
```

---

## Slide-by-Slide Variable Map — Darden-Specific Content

When adapting any slide for a non-Darden client, replace these tokens:

### Global replacements (every slide)
| Token | Replace with |
|---|---|
| `Darden` | Client name |
| `KROWD` | Client's loyalty/employee app name |
| `Olive Garden` | Client's primary brand/division |
| `11 brands` | Client's brand count |
| `2,100` / `2,100+` | Client's location count |
| `Azure` | Client's cloud platform |
| `Remedy` | Client's ITSM tool |
| `CommerceTools` | Client's commerce platform |
| `Contentstack` | Client's CMS |
| `Akamai` | Client's CDN |
| `xMatters` | Client's alerting tool |
| `$45 AOV` | Client's average order value |
| `80,000 orders/day` | Client's digital order volume |
| `Photon® Interactive UK Limited` | Keep (Photon is always the vendor) |

### Slide-specific Darden content
| Slide | Darden-Specific Content | Notes |
|---|---|---|
| 01 COVER | `JUNE 2026` | Update date |
| 03 DARK_CONTENT | All 3 paragraphs | Full rewrite for client |
| 05 INTRODUCING | "Three years inside your stack" block | Update tenure |
| 07 TIER_TABLE | Column headers L1/L2/L3 | Usually reusable |
| 11–13 ITSM | Business outcomes metrics | Targets are template-safe |
| 14 SLA_TABLE | All SLA numbers | Keep unless negotiated differently |
| 20 UC_LIBRARY | 16 UC names and Super Agent names | Usually reusable |
| 22 UC_FLOW | All step descriptions, tool names | Partial rewrite |
| 32 ROADMAP | Phase timing, UC phasing, brand names | Full client customisation |
| 35 ROI_FUNNEL | ALL numbers (4,282 / 1,538 / 473 / $3.90M) | Always client-specific — use ROI skill |
| 36 VALUE_RAMP | All % and $ values | Always client-specific — use ROI skill |
| 38 STAFFING | FTE counts, ONSITE/OFFSHORE split | Customise per deal |
| 41 FINANCIAL | All $ figures, phase durations | Always client-specific |
| 45+ CASE STUDIES | Sony, Frontier, Coty, Banfield, L'Oreal | Hide if presenting TO that client |

### Case study hide rule
If the new deck is FOR Coty → hide/remove the Coty case study slide (slide 49)
If the new deck is FOR Banfield → hide/remove the Banfield case study slide (slide 51)
If the new deck is FOR L'Oreal → hide/remove the L'Oreal case study slide (slide 52)
Darden, Sony, Frontier slides are safe to show to any client as external references.
Add a Darden case study slide (same format as Sony/Frontier) using slide 47 as the XML template.

---

## Editing Rules — Strict

### DO
- `view` the slide XML before any edit
- Copy the entire XML structure
- Edit only `<a:t>` text content nodes
- Keep all EMU coordinates (x, y, cx, cy) identical
- Keep all font attributes (`typeface`, `sz`, `b`, colour) identical
- Keep all rId references for images that stay the same
- When adding a new image, add a new rId in the rels file and a new `<p:pic>` element

### DO NOT
- Recreate any slide layout from scratch
- Use pptxgenjs to generate slides that have XML templates
- Change any coordinate values
- Remove the `+    +    +` texture text from section dividers
- Change the two-run gold+dark heading pattern to a single run
- Change `noFill` to a fill or vice versa on any shape
- Add borders/outlines that don't exist in the template
- Use `#ECBB69` — always `ECBB69` (no hash prefix)

---

## Common Patterns to Know

### Section divider text block (slides 10, 15, 19, 27, 29, 31, 34, 37, 39, 43, 44)
- Background: `484848` charcoal full-bleed
- Right side: `+    +    +` texture (GT Walsheim Thin, 16pt, white 50% alpha)
- Dark panel overlay: `484848` rect, right half of slide
- Title text: multi-line, centred, gold + white runs, GT Walsheim Black 40–44pt
- Slide number: bottom right, GT Walsheim Light 8pt, white 65%

### Content slide chrome (all non-cover, non-divider slides)
- Background: white or light (set in slide XML or slide master)
- Logo: top-left, x=348,616 y=307,058 cx=596,053 cy=596,053
- Footer: GT Walsheim Light 8pt, "Private And Confidential | Photon® Interactive UK Limited, Copyright ©2026"
- Slide number: bottom right auto-field

### Gold stat bar (ROI / financial slides)
- Position: y ≈ 6,200,000 EMU (near bottom)
- Fill: `ECBB69`
- Text: GT Walsheim Black, white, key stat or label

### Teal accent
Used for: AI-tier commitments, active agent steps, Phase 2+ highlights
Never used for: headings, general body text

---

## Portability — Setting Up on a New Account

This skill works on any Claude account (claude.ai Pro, Team, Max, or API) and in any Claude product (chat, Cowork, Projects, Claude Code).

### One-time setup
1. Upload the `phtn-intelliops-theme` folder to your Claude Project files
   OR place it at a path accessible to Claude Code / Cowork
2. No other setup needed — logos are embedded as base64 in `assets/`
3. GT Walsheim fonts must be installed on the machine where PowerPoint opens the file
   (not needed by Claude — only by the person opening the final .pptx)

### For colleagues
Share the entire `phtn-intelliops-theme/` folder. They place it in their skill path and Claude
finds it automatically. The folder is self-contained — no external dependencies.

### Moving from personal to corporate Photon account
Same folder, same path. No changes needed. The skill file is account-agnostic.

---

## Related Skills
- **phtn-intelliops-proposal** (Skill 1) — full 61-slide proposal template with Darden reference
- **phtn-intelliops-roi** (Skill 3) — ROI model: incident CSV → ROI slides (Slide 35/36)
