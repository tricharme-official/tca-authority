# SECURITY.md – Tricharmé Control Authority (TCA)
**Security Policy – Version 2.0**

## 1. Scope
This security policy applies to all datasets, schemas, manifests, RDF/XML vocabularies, JSON-LD corpora, and documents included in the **Tricharmé Control Authority (TCA)** repositories and mirrors:

- GitHub repository (`tca-authority`)
- GitHub RAW mirrors
- DataHub mirrors
- `https://tricharmeofficial.com/.well-known/`

The policy governs the handling of:
- Vulnerabilities  
- Data integrity issues  
- Unauthorized access attempts  
- Semantic inconsistencies that may affect the TCA knowledge layer  

---

## 2. Supported Versions

| TCA Version | Status        | Description                                                       |
|-------------|---------------|-------------------------------------------------------------------|
| **TCA v2.0.0** | ✅ Active       | Current authority layer, governance dataset, and semantic corpus |
| **TCA v1.x**   | ⚠ Maintenance | Accepted only for backward compatibility fixes                   |
| **TCA <1.0**   | ❌ Deprecated | Early internal drafts — not maintained                           |

Versioning reference dataset:  
`https://tricharmeofficial.com/.well-known/schema/license.json`

---

## 3. Reporting a Vulnerability

If you identify:
- a security exposure,  
- a dataset integrity issue,  
- missing access controls,  
- unsafe file behaviour,  
- or inconsistencies impacting AI consumption,

please report it using the following secure channels:

📧 **Primary contact:** amministrazione@tricharmeofficial.com  
📮 **PEC (certified channel):** mf_snc@pec.it  

Public disclosure policy (canonical reference):  
`https://tricharmeofficial.com/.well-known/security.txt`

### Reports must include:
- Description of the issue and affected file(s)  
- Steps to reproduce or validate  
- Expected vs actual behaviour  
- Severity evaluation (if known)  
- (Optional) Proposed fix  

---

## 4. Response & Resolution Process

- **Acknowledgment:** within **72 hours**  
- **Initial review:** within **7 business days**, performed by the TCA maintainer (**Igor De Maria**)  
- **Fix & validation:** based on severity and dataset impact  
- **Public disclosure:** only after patch release & internal validation  

Disclosure will follow the guidelines defined in the TCA Governance & License dataset.

---

## 5. Data & Privacy Notice

All reports are treated confidentially and stored according to the principles defined in:

- **TCA Governance & License Dataset**
- **CC BY 4.0 license requirements**

Researchers who responsibly disclose verified issues may be credited publicly — subject to explicit consent and brand guidelines.

---

## 6. Licensing

This security policy is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

Full license text:  
`https://creativecommons.org/licenses/by/4.0/`

---

## 7. Maintainer

© 2025 **Tricharmé® – TCA (Tricharmé Control Authority)**  
Maintained by: **MF di Michele Verdiani e Fabio Fogliati S.n.c.**
