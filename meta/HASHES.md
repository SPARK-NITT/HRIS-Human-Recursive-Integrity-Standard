# HRIS — Integrity Hashes (SHA-256)

**Purpose:** This file records SHA-256 hashes for canonical HRIS documents.  
**Rule:** Append-only. Do not delete prior entries. If a canonical document changes, create a new versioned filename and add a new hash entry.

**Important:** README.md is intentionally NOT hashed here so the repo’s landing page can be refined without invalidating canonical document hashes.

---

## Hash Batch: v1.0 (2025-12-13)

_Date recorded:_ 2025-12-13  
_Tooling:_ Windows PowerShell `Get-FileHash -Algorithm SHA256`

- `docs/HRIS_Governance_Charter_v1.1.md`  
  SHA-256: `60E75EBBC33AA4D0CC1BDC36142A99FD45A5B1666FA47F1171A11A2E2BB5156C`

- `docs/HRIS_Operational_Enforcement_v1.0.md`  
  SHA-256: `56A207115ADF01672BDFCC80BDC6BA696CAE6FCBBF89FF0A4B325FC003267A64`

- `docs/HRIS_3.2.4(b)_CCR_v1.0.md`  
  SHA-256: `137E9C36CB6F482737E7D32C611E85EDE34EB6622E9C4C6725FD99EA1F770E95`
