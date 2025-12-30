# CLAUDE.md - Hive Marketing Repository

## Project Overview

This is the **master repository for Hive blockchain marketing, promotion, and outreach materials**. Hive is a decentralized blockchain built on Delegated Proof of Stake (DPoS), and this repo serves as the centralized content library for marketing initiatives across the Hive ecosystem.

**Core Purpose:**
- Develop and maintain comprehensive marketing strategy for Hive blockchain
- Host marketing materials, promotional content, and outreach components
- Manage campaign documentation, graphics, logos, and brand assets
- Provide approved messaging statements and brand guidelines
- Track marketing initiatives, events, and strategic partnerships

## Tech Stack

**Primary Format:** Markdown documentation
**Media Assets:** PDF files (campaigns, presentations), Adobe Illustrator files (.ai - logos)
**Version Control:** Git (hosted on GitLab)
**Collaboration Tools:** Google Drive/Sheets for cost tracking, Google Slides for presentations

**Licensing:**
- Documentation: GNU LGPL v3
- Logos: Creative Commons Attribution Non-Commercial (CC-BY-NC)

## Directory Structure

```
marketing/
├── README.md                    # Main repository overview
├── LICENSE                      # LGPL v3 license
│
├── strategy/                    # Core marketing strategy documents
│   ├── general/                 # Primary strategy components
│   │   ├── 1-Introduction.md    # Purpose statement & goals
│   │   ├── 2-Story.md           # Brand story and approved statements
│   │   ├── 3-Analysis.md        # Best practices, SWOT analysis
│   │   ├── 4-Outreach.md        # Outreach methods & collaborations
│   │   ├── 5-Contributions.md   # Contribution guidelines
│   │   └── 6-HiveRepresentation.md  # Brand guidelines, naming conventions
│   ├── boilerplate/             # Template content (EN/ES)
│   └── Value Plan/              # Value Plan initiative documentation
│       ├── projectgoals.md      # 2024-2025 project goals
│       └── strategy feedback/   # Mission, vision, values, SWOT docs
│
├── campaigns/                   # Campaign materials & assets
│   ├── CBW2022/                 # Crypto Blockchain Week 2022
│   ├── Engifest 2022/           # Engifest event materials
│   └── rallycar/                # Rally car sponsorship project
│
├── logos/                       # Brand assets & logos
│   └── Logos [1-3].ai           # Adobe Illustrator logo files
│
└── planning/                    # Event planning guides & resources
    └── ReadMe.md                # Comprehensive event planning framework
```

## Development Commands

**This is a documentation/content repository with no build system.**

Common git operations:
```bash
# Clone the repository
git clone git@gitlab.syncad.com:hive/marketing.git

# Create a new branch for changes (master is protected)
git checkout -b feature/your-feature-name

# Push changes and create MR
git push -u origin feature/your-feature-name
```

## Key Files

| File | Purpose |
|------|---------|
| `strategy/general/2-Story.md` | Seven pre-approved brand story statements |
| `strategy/general/6-HiveRepresentation.md` | Brand guidelines, naming conventions, prohibited terminology |
| `strategy/boilerplate/ReadMe.md` | Short approved "About Hive" statements (EN/ES) |
| `planning/ReadMe.md` | Event planning framework, budgeting, vendor approval |
| `strategy/Value Plan/projectgoals.md` | Active project categories and 2024-2025 goals |

## Coding Conventions

### Markdown Standards
- Numbered strategy files (1-Introduction through 6-HiveRepresentation) for logical flow
- Consistent H1/H2/H3 hierarchy for sections
- Bullet points and numbered lists for clarity
- Quote blocks for approved messaging statements

### Brand Guidelines

**Approved terminology:**
- "Hive", "Hive ecosystem", "Hive platform"
- Taglines: "Fast. Scalable. Powerful." and "The Blockchain for Web3"
- Descriptors: Innovative, decentralized, Web3, grass-roots, global, open-source, fee-less

**Prohibited terminology:**
- Never call it "easy money"
- Never use "HIVE Blockchain" (redundant)
- Never link to political movements

**Target audiences:** Content creators, investors, developers, startups, youth

### Project Management Standards
- All costs tracked via Google Sheets
- Photo documentation of all expenditures
- Vendor approval criteria: legitimate business, local priority, invoicing capability
- Per diems: 30 HBD/day for full-day volunteer work
- All surplus funds returned to DHF or Value Plan

## CI/CD Notes

**No CI/CD pipeline exists** - this is a content/documentation repository.

**Branch protection:**
- `master` branch is protected
- All changes require merge requests
- No direct commits to master

**Repository access:**
- Hosted on gitlab.syncad.com
- Restricted to registered GitLab users
- Contribution via Issues and Merge Requests

## Related Resources

- **Hive Whitepaper:** https://gitlab.syncad.com/hive/hive-whitepaper
- **Brand assets:** https://hive.io/brand
- **Font Awesome Hive icon:** fontawesome.com
