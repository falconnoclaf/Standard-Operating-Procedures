| ![Company Logo](https://stfnsrepo.blob.core.windows.net/pics/Vertical-Trans-150x150.png) | **Falcon Network Services**<br>691 N Squirrel Rd Ste 215<br>Auburn Hills, MI 48326<br>(248) 726-0577 \| FNS1.com |
|:---|---:|

---

# STANDARD OPERATING PROCEDURE

---

## Document Control

| **SOP Number:** | SOP-XXX-000 |
|---|---|
| **SOP Title:** | [Enter SOP Title] |
| **Version:** | 1.0 |
| **Effective Date:** | [MM/DD/YYYY] |
| **Last Reviewed:** | [MM/DD/YYYY] |
| **Next Review Date:** | [MM/DD/YYYY] |
| **Document Owner:** | [Name/Title] |
| **Approved By:** | [Name/Title] |

## Applicable Regulations/Frameworks

☐ GLBA  |  ☐ FFIEC  |  ☐ HIPAA  |  ☐ PCI DSS  
☐ CIS Controls  |  ☐ NIST CSF  |  ☐ Other: _______________

---

## 1. PURPOSE

[Describe the purpose and objective of this SOP. Explain what process or activity this document governs.]

## 2. SCOPE

**Applies To:**  
- [Department/Team/Role]
- [Systems/Applications]
- [Locations]

**Exclusions:**  
- [Any specific exclusions]

## 3. DEFINITIONS

| Term | Definition |
|---|---|
| [Term 1] | [Definition] |
| [Term 2] | [Definition] |

## 4. ROLES AND RESPONSIBILITIES

| Role | Responsibilities |
|---|---|
| [Role 1] | [List specific responsibilities] |
| [Role 2] | [List specific responsibilities] |
| [Role 3] | [List specific responsibilities] |

## 5. PREREQUISITES

- [Required access/permissions]
- [Required tools/systems]
- [Required training/certifications]
- [Required documentation]

## 6. PROCEDURE

### 6.1 Verify User Account Status

**Frequency:** On-demand  
**Estimated Time:** 5 minutes

1. Open PowerShell as Administrator on the domain controller
2. Run the following command to check the user account status:
   ```powershell
   Get-ADUser -Identity "username" -Properties LastLogonDate, PasswordLastSet, Enabled | Select Name, Enabled, LastLogonDate, PasswordLastSet
   ```
3. Review the output to confirm:
   - Account is enabled (Enabled = True)
   - Last logon date is within expected timeframe
   - Password was set according to policy requirements
4. Document findings in the ticket system

**Verification:** Account status displays correctly and matches expected security policy requirements

### 6.2 [Process Step Name]

**Frequency:** [On-demand/Daily/Weekly/Monthly/Quarterly/Annually]  
**Estimated Time:** [X minutes/hours]

1. [Detailed step-by-step instructions]
2. [Include decision points where applicable]
3. [Note any system commands, screenshots references, or specific actions]

**Verification:** [How to verify this step was completed correctly]

### 6.3 [Process Step Name]

[Continue as needed for all process steps]

## 7. DOCUMENTATION AND RECORD KEEPING

**Records to Maintain:**
- [Type of record]
- [Type of record]

**Retention Period:** [X years/As per retention policy]  
**Storage Location:** [System/Location where records are stored]

## 8. EXCEPTIONS AND ESCALATION

**Exception Process:**  
[Describe how to handle exceptions to this procedure]

**Escalation Path:**
1. [First Level] → [Name/Title]
2. [Second Level] → [Name/Title]
3. [Final Level] → [Name/Title]

## 9. RELATED DOCUMENTS

- [SOP-XXX-000: Related SOP Title]
- [POL-XXX-000: Related Policy Title]
- [Form/Template name]

## 10. COMPLIANCE CONTROLS ADDRESSED

[List specific control requirements this SOP satisfies, e.g.:]
- NIST CSF: [Function.Category.Subcategory]
- CIS Control: [Control Number and Description]
- HIPAA: [§164.xxx requirement]
- PCI DSS: [Requirement x.x.x]

## 11. REVISION HISTORY

| Version | Date | Author | Description of Changes |
|---|---|---|---|
| 1.0 | [MM/DD/YYYY] | [Name] | Initial document creation |
| | | | |

---

## Approval Signatures

| Role | Name | Signature | Date |
|---|---|---|---|
| Document Owner | | | |
| Compliance Officer | | | |
| Executive Approval | | | |

---

| SOP-XXX-000 v1.0 | © [Year] Falcon Network Services | Page [X] of [Y] |
|:---|:---:|---:|