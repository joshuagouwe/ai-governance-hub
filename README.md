# AI Governance Hub

This repository is a consolidated GitHub workspace for AI governance and ISO 42001 resources, brought together for use in Copilot-enabled workflows and Claude/AI-assisted governance work.

It combines the most relevant public repositories in a single place so teams can browse policy, risk, and compliance guidance without jumping between repos.

## Included source repositories

- Verifywise AI Governance Skills
  - Source: https://github.com/verifywise-ai/ai-governance-skills
  - Local path: `sources/verifywise/`
  - Use: Claude skill bundles, multi-regulation governance prompts and compliance workflows

- Ankit Uniyal ISO 42001 AI Governance Toolkit
  - Source: https://github.com/Ankit-Uniyal/iso-42001-ai-governance-toolkit
  - Local path: `sources/ankit-iso42001/`
  - Use: full implementation toolkit, templates, gap assessment, SoA, and crosswalks

- pifpof ISO 42001 Readiness Plugin
  - Source: https://github.com/pifpof/iso42001
  - Local path: `sources/pifpof-iso42001/`
  - Use: Claude Code skills, vault structure, readiness flows and onboarding guidance

- icdfa ISO 42001 Lead Implementer Toolkit
  - Source: https://github.com/icdfa/iso-42001-lead-implementer-toolkit
  - Local path: `sources/icdfa-iso42001/`
  - Use: implemented guidance, case studies, audit prep, and practical templates

- AndyZet ISO 42001 Exam Simulator
  - Source: https://github.com/AndyZet/iso42001-exam-simulator
  - Local path: `sources/andy-iso42001-exam/`
  - Use: exam prep, audit training, learning exercises

## Recommended usage

- For interactive compliance assistance: use the `verifywise` content and Claude skill bundles.
- For evidence and implementation artifacts: use the `ankit` and `icdfa` toolkits.
- For a lightweight readiness workflow in Claude Code: use the `pifpof` content.
- For learning and exam prep: use the `andy` exam simulator.

## Repository structure

```text
.
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── MAINTAINERS.md
├── docs/
│   └── README.md
├── sources/
│   ├── verifywise/
│   │   ├── README.md
│   │   └── ORIGIN.md
│   ├── ankit-iso42001/
│   │   ├── README.md
│   │   └── ORIGIN.md
│   ├── pifpof-iso42001/
│   │   ├── README.md
│   │   └── ORIGIN.md
│   ├── icdfa-iso42001/
│   │   ├── README.md
│   │   └── ORIGIN.md
│   └── andy-iso42001-exam/
│       ├── README.md
│       └── ORIGIN.md
└──
```

## Governance and maintenance

This repo is intentionally a curated aggregate. The canonical upstream repos remain the source of truth for content changes. Local content can be refreshed or extended from upstream as needed.

## License

This monorepo is licensed under the MIT License. Individual upstream repositories also use MIT where applicable; check the source repo for specifics.
