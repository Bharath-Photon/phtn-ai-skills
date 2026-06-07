# PHTN.ai IntelliOps Theme — Quick Start Guide for Colleagues

## What this is
A complete slide template library for PHTN.ai IntelliOps proposals. Every distinct slide layout
from the master IntelliOps deck is saved as an exact XML file. Claude uses these templates instead
of inventing layouts — so every deck produced looks identical to the master.

## Setup (one time, 2 minutes)

### If you use Claude.ai chat or Projects (Max, Pro, Team):
1. Create a Project in Claude.ai called "PHTN.ai Decks" (or add to existing)
2. Upload the entire unzipped `phtn-intelliops-theme` folder to the Project files
3. Done. Claude detects the skill automatically when you mention "IntelliOps deck"

### If you use Claude Code or Cowork:
1. Place the `phtn-intelliops-theme` folder at: `/mnt/skills/user/phtn-intelliops-theme/`
2. Claude auto-discovers it via the available_skills system

### Font requirement (on your machine only — not Claude's)
GT Walsheim fonts must be installed on any machine where you open the final .pptx file.
Claude does not need the fonts to build the file.

---

## How to ask Claude to build a deck

### New client deck
> "Build an IntelliOps proposal for Dutch Bros Coffee. They run AWS + Salesforce Commerce Cloud.
>  800+ locations across the US. Use the IntelliOps template."

### Use a specific slide template
> "Use the maturity model slide template to create a slide for Coty's IntelliOps journey"
> "Give me the UC flow deep dive slide for Dutch Bros UC1 synthetic monitoring"
> "Build a staffing plan slide for a 6-person team, 1 onsite 5 offshore"

### Add or replace a case study
> "Create a Darden case study slide in the same format as the Sony compact case study"
> "Hide the Coty case study — this deck is for Coty"

### Update numbers only
> "Update the ROI funnel slide with these numbers: 3,100 total incidents, 1,200 revenue category,
>  890 scope, 342 qualifying, $2.8M at risk"

---

## Complete slide template catalog (39 layouts)

| File | Slide Type | Use When |
|---|---|---|
| 01_COVER | Cover / title | First slide |
| 02_AGENDA | Table of contents | Second slide |
| 03_DARK_CONTENT | Dark bg, long narrative | Understanding the need, approach |
| 04_WHY_AI_4BOX | 4 numbered problem cards | Why traditional AMS fails |
| 05_INTRODUCING | 3-panel hero | Product introduction |
| 06_THREE_COL | 3-column benefits | What this means for [Client] |
| 07_TIER_TABLE | Before/after tier table | AI at every level |
| 08_MATURITY_4STAGE | 4-stage maturity model | IntelliOps maturity |
| 09_TEAMS_EVOLUTION | Two-column org evolution | Teams evolution |
| 10_SECTION_DIVIDER | Section break | Between major sections |
| 11_ITSM_PILLAR | Traditional vs AI pillar | Incident / Problem / Change management |
| 14_SLA_TABLE | Two-tier SLA | AI-tier + human-in-loop SLAs |
| 16_ARCH_OVERVIEW | 4 capability cards | How IntelliOps sits in the stack |
| 17_TECHNICAL_ARCH | Full technical diagram | Deep architecture detail |
| 18_SCALE_3COL | 3 large text columns | Scale / growth narrative |
| 20_UC_LIBRARY_TABLE | Full UC table | Use case library (all 16 UCs) |
| 21_UC_KEY_CASES | UC + sub-agent table | Key use cases deep |
| 22_UC_FLOW_DEEPDIVE | 10-step agent flow | UC1/UC2/UC3 deep dive |
| 25_UC4_L1_AUTOMATION | Before/after 4-step flow | UC4 L1 automation |
| 26_SUBAGENT_MATRIX | UC × agent grid | Sub-agent reuse |
| 28_DEMO_VIDEO | Demo placeholder | Demo section |
| 30_ASSUMPTIONS_TEXT | Bulleted list | Assumptions & constraints |
| 32_ROADMAP_4PHASE | 4-phase roadmap | Delivery phases |
| 33_PHASE1_TIMELINE | Week-by-week timeline | Phase 1 detail |
| 35_ROI_FUNNEL | 4-box revenue funnel | ROI methodology |
| 36_VALUE_PHASE_RAMP | 3-metric phase charts | Value build by phase |
| 38_STAFFING_PLAN | Org chart | Staffing plan |
| 40_PRICING_OPTIONS | 4 commercial options | Pricing models |
| 41_FINANCIAL_SUMMARY | Phase financial table | Cost summary |
| 42_TOKEN_SIZING | Token tier table | Token consumption estimate |
| 45_STEADY_STATE_COST | 4 cost buckets + ROI | Year 2 steady state |
| 47_CASE_STUDY_COMPACT | Compact case study | Sony / Frontier format |
| 50_CASE_STUDY_DETAILED | Detailed case study | Coty / Banfield format |
| 53_LOGO_DIVIDER | Logo-only divider | Appendix separator |
| 55_RESOURCE_TRANSITION | Role ramp table | Transition plan |
| 56_PLATFORM_AGNOSTIC | Platform-agnostic intro | Appendix / cross-sell |
| 57_ITSM_SUMMARY | 3-pillar ITSM summary | ITSM transformation |
| 58_ITSM_PILLARS_DETAILED | 5 ITSM pillars | Detailed ITSM process |
| 59_SERVICE_ACCEPTANCE | Service acceptance pillar | Onboarding / peak events |
| 61_TIME_ZONE_OVERLAP | Time zone diagram | Operational model |

---

## Important rules (Claude handles these automatically)
- Logo is always embedded from `assets/logo_main.b64` — no files to attach or manage
- Heading style is always: **gold first word + dark remaining words** (GT Walsheim Black)
- Section dividers always have the + + + texture pattern
- Darden-specific numbers are never carried over to other client decks
- If building a deck FOR Coty → Coty case study slide is hidden automatically
- If building a deck FOR Banfield → Banfield case study slide is hidden automatically
- ROI numbers (slides 35/36) always come from the client's own incident data via the ROI skill

---

## Troubleshooting
**"Claude isn't using the templates"** → Make sure the folder is uploaded to your Project files,
not just attached to a single chat. Project files persist across all chats in that project.

**"The deck won't open in PowerPoint"** → Check GT Walsheim fonts are installed on your machine.
The deck builds correctly without them but they're needed to display properly.

**"Wrong logo appeared"** → This shouldn't happen with this skill — logo is embedded as base64.
If it does, tell Claude: "Use logo_main.b64 from the assets folder" and it will correct it.
