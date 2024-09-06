# eduterm
# User Story:

## Title:
As an education committee member, I want to verify the usage of certain terms in educational documents by scanning PDFs, while an administrator manages the list of approved phrases, so that I can ensure compliance with standardized terminology across our materials.

---

## As an Administrator
I want to manage the list of phrases that are used to scan educational documents so that the committee members can ensure they are using the correct and up-to-date terms.

## As a Committee Member
I want to scan documents based on the approved phrase list managed by the administrator, so that I can ensure educational documents comply with standard terminology.

---

## Acceptance Criteria for Administrator Role:

1. **Phrases Management:**
   - I can add new phrases or terms to the list of approved phrases.
   - I can edit or remove existing phrases in the list.
   - I can categorize phrases into groups (e.g., subject-specific phrases, grade level phrases).
   - I can set phrases as "mandatory" or "optional" for each scan.

2. **Phrase Visibility:**
   - The education committee members can see the list of approved phrases when they upload a document.
   - Members cannot modify the list of approved phrases, but they can add temporary phrases for specific scans.

3. **Security and Permissions:**
   - Only administrators have the ability to add, edit, or delete phrases.
   - Committee members have read-only access to the phrase list for scanning purposes.

4. **Version Control:**
   - When changes are made to the list, the system keeps track of previous versions, so the administrator can revert to an earlier list if necessary.

5. **Notification System:**
   - When the administrator updates the list of approved phrases, an optional notification can be sent to committee members to inform them of the changes.

---

## Acceptance Criteria for Committee Member Role:

1. **Phrase Input:**
   - I can scan documents using the list of phrases provided by the administrator.
   - I can temporarily add additional phrases to the list for specific scans, but these are not saved for future scans.

2. **Phrase Visibility:**
   - I can see whether the phrases are categorized as "mandatory" or "optional."
   - I can view the results of the scan, including whether mandatory phrases are missing or found.

---

## Additional Administrator Features:

- **Phrases Export/Import:**
   - The administrator can export or import the list of approved phrases, enabling easier updates across multiple tools or locations.

- **Audit Logs:**
   - The system should maintain an audit log of changes to the phrase list, including who made the change and when.
