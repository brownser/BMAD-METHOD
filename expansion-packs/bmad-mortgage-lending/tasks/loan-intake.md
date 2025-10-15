<!-- Powered by BMAD™ Core -->

# Loan Intake Task

## Purpose

Conduct a comprehensive application intake, collect required documentation, and populate the loan origination system with compliant data for disclosures and underwriting preparation.

## Inputs

- Completed borrower intake questionnaire (`../templates/borrower-intake-questionnaire.md`)
- Borrower-provided documentation (IDs, income, assets)
- Loan origination system (LOS) access
- `../templates/document-request-letter.md`
- `../checklists/hmda-data-capture-checklist.md`
- `../checklists/trid-timing-checklist.md`

## Key Activities & Instructions

### 1. Verify Borrower Identity & Application Completeness

1. Authenticate borrower identity using two-factor or knowledge-based verification.
2. Confirm receipt of six key application items (ALIENS) to start TRID timing clock.
3. Update LOS with borrower contact preferences and disclosure delivery method.
4. Reference TRID checklist to document application completion date.

### 2. Capture Detailed Application Data

1. Walk through URLA sections to gather employment, income, assets, liabilities, and declarations.
2. Record HMDA demographic information per checklist guidance and note if borrower declines.
3. Validate property details, estimated value, and occupancy intentions.
4. Document co-borrower information and relationship.

### 3. Collect and Organize Documentation

1. Review submitted documents for completeness, legibility, and date ranges.
2. Issue document request letter template for outstanding items with clear due dates.
3. Tag received documents in LOS (naming convention, expiration tracking).
4. Flag any red flags (large deposits, inconsistent income) for LO awareness.

### 4. Disclosures & Compliance Preparation

1. Prepare preliminary fee worksheet and loan estimate data for compliance review.
2. Confirm state-specific disclosure requirements using the state checklist.
3. Schedule disclosure issuance within TRID timing requirements.
4. Document borrower consent and preferred signature method.

### 5. Data Quality & Handoff

1. Run LOS validation to ensure required fields completed for AUS submission.
2. Cross-check HMDA data entry using checklist as quality control.
3. Summarize key borrower metrics (DTI estimate, LTV, credit score) for loan officer.
4. Upload organized intake package to team workspace for pre-approval analysis.

## Outputs

1. Fully populated loan application file ready for AUS and disclosures.
2. Updated TRID log with application completion and planned disclosure dates.
3. Outstanding document tracker sent to borrower via request letter template.
4. Intake summary report delivered to loan officer or processing team.

## Linked Checklists & Assets

- `../checklists/hmda-data-capture-checklist.md` for demographic and loan data entry accuracy.
- `../checklists/trid-timing-checklist.md` to manage disclosure timing and logs.
- `../checklists/state-specific-disclosures-checklist.md` for state-driven requirements.
- `../templates/document-request-letter.md` to communicate outstanding documentation needs.

## Elicitation Prompts

- "Have there been any employment changes in the last two years that we should document?"
- "Can you confirm the source of funds for your down payment and whether gifts are involved?"
- "Would you prefer to review disclosures electronically or schedule an in-person review?"
