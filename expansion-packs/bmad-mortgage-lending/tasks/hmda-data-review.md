<!-- Powered by BMAD™ Core -->

# HMDA Data Review Workflow

## Mission

Validate HMDA reportable data for accuracy and completeness before submission or audit.

## Prerequisites

- Access to LOS HMDA export and source documents
- HMDA field mapping reference
- Exception reporting template

## Execution Steps

1. **Extract Data**
   - Pull HMDA dataset for target loans and note extraction timestamp.
   - Ensure filters include relevant actions and dates.
2. **Cross-Check Fields**
   - Compare borrower demographics, loan amount, action taken, and property data with source documents.
   - Validate geocoding and census tract accuracy.
3. **Identify Exceptions**
   - Flag missing values, invalid codes, or inconsistencies.
   - Categorize issues (data entry, documentation, policy).
4. **Investigate Root Cause**
   - Review LOS notes, underwriting decisions, and compliance logs.
   - Determine whether corrections require re-disclosure or re-underwriting.
5. **Document Findings**
   - Populate HMDA exception report with issue, severity, owner, and remediation deadline.
   - Update defect tracking log for systemic issues.
6. **Confirm Corrections**
   - Verify LOS updates and re-export dataset to confirm resolution.
   - Retain evidence of changes for audit trail.

## Completion Criteria

- HMDA exception report updated with current status.
- Corrected data reflected in LOS export.
- Compliance notified of any outstanding or systemic issues.

## Compliance Notes

- Follow official HMDA filing instructions for coding standards.
- Retain corrected datasets and communications for five-year audit window.
