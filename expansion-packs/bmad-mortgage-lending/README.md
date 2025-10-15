# BMad Mortgage Lending Expansion Pack

Empower a solo mortgage broker with AI-driven loan origination, client service, and compliance workflows designed for end-to-end execution.

## 🏦 Overview

The Mortgage Lending Expansion Pack extends BMad Method with a focused toolkit for independent mortgage brokers who run their entire pipeline alone. It supplies specialized agents, checklists, templates, and LOS-ready workflows so you can qualify borrowers, structure loans, and coordinate closing tasks without needing a large back office. The pack emphasizes repeatable borrower communications, audit-ready documentation, and small-team automation that keeps a one-person shop competitive.

### Tailored Capabilities for Solo Brokers

- 🤝 **Borrower Relationship Ops** – nurture leads, gather documentation, and maintain consistent status updates
- 🧮 **Loan Structuring Support** – scenario modeling, rate comparisons, and eligibility guidance for common residential programs
- 📂 **Compliance & Audit Readiness** – QC checklists, disclosure reminders, and file organization standards
- 🔁 **Lightweight Automation** – ready-to-run tasks that eliminate manual re-entry between CRM, LOS, and settlement partners

## 🚀 Installation

### Via BMad Installer (after PR acceptance)

```bash
npx bmad-method install
# Select "Mortgage Lending Solo Broker" from the expansion packs list
```

### Manual Installation

1. Clone or download this expansion pack
2. Copy it into your BMad Method installation:
   ```bash
   cp -r bmad-mortgage-lending/* ~/bmad-method/expansion-packs/bmad-mortgage-lending/
   ```
3. Run the BMad installer to register the pack and refresh cached workflows

## 📊 LOS Workflows for One-Person Brokerages

Each workflow assumes you are the only loan officer, processor, and closer—prioritizing clarity, automation prompts, and borrower communication checkpoints.

1. **lead-intake-qualification** – capture lead data, run quick DTI/LTV checks, and produce a pre-qualification script
2. **document-collection-orchestration** – generate borrower task lists, send secure upload instructions, and track outstanding conditions
3. **loan-structuring-analysis** – evaluate conventional, FHA, VA, and non-QM options; create comparison summaries tailored to borrower goals
4. **underwriting-prep-and-submit** – compile AUS findings, verify compliance checklists, and format submission notes for investors/wholesalers
5. **closing-coordination-lite** – synchronize final disclosures, wire instructions, and post-closing follow-ups to protect relationships and referrals

---

**Version:** 1.0.0 (initial scaffold)
**Compatible with:** BMad Method v1.0+
**Maintainer:** Solo Broker Enablement Team
