PUBLIC DEPLOYMENT PACKAGE

This folder intentionally excludes internal editorial controls, claims matrices, audit reports,
working notes, and evidence-room control documents.

Before live deployment:
1. Review every file under evidence/Sources for privacy/redaction.
2. Confirm OX treatment immediately before launch.
3. Perform browser visual QA in the actual hosting environment.
4. Confirm that no server directory listing exposes files outside this package.

Current status: prelaunch candidate; OX remains open.

PRIVACY HARDENING PASS
- Removed unnecessary broker account numbers from public HTML.
- Withheld 7 native/raw source files from the deployable package because they have not been individually privacy-cleared.
- Public source folders retain only redacted/public derivatives, reader guides/status notes, and the controlled AFT presentation PDF.
- This is intentionally more conservative than the internal evidence archive.

FILE-BY-FILE REDACTION REVIEW — PASS 1
- Scanned remaining deployable evidence for email addresses, phone numbers, SSNs, known broker account identifiers, customer name, and street-address patterns.
- Removed known broker account identifiers found in OX, GNT and Monaxa public evidence/support files.
- Renamed the Monaxa public-derivative filename so its broker account number is not exposed.
- Cleared common DOCX author/last-modified metadata.
- The redacted orphan-trade spreadsheet remains the public spreadsheet source.

CONFIDENTIALITY REVIEW — PASS 2
- Removed public-facing references to confidential non-public proceedings or submissions.
- Removed the retired OX dollar figure that remained inside Exhibit G and replaced it with non-numeric historical wording.
- Cleaned redaction placeholders in the Monaxa reader/source guides for readability.
- Corrected the OX open-question transfer entry from +$200 to +$200,000.
