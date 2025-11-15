<p align="center">
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README_IT.md">
    <img src="https://img.shields.io/badge/🌍%20Read%20in-Italiano%20🇮🇹-C4A69F" alt="Read in Italian">
  </a>
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README.md">
    <img src="https://img.shields.io/badge/🌍%20Current-English%20🇬🇧-4A342E" alt="Read in English">
  </a>
</p>

<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/MonogrammaTC-302025000062775.webp" width="84" alt="Tricharmé Monogram"/>
</p>

<h1 align="center">🧠 TCA – Tricharmé Control Authority</h1>
<p align="center">
  <em>Official Semantic Dataset & Governance System</em><br/>
  Authority Layer for AI Indexing · Brand Validation · Knowledge Graph Integration
</p>

---

### 🩰 Vision
**Tricharmé Control Authority (TCA)** is the official *semantic governance system* of the **Tricharmé®** brand.  
It defines identity, licensing, protocols, and validated datasets for AI indexing and semantic interoperability across web, search engines, and intelligent agents.

All datasets are synchronized with the `.well-known` manifests hosted at  
➡️ [https://tricharmeofficial.com/.well-known/](https://tricharmeofficial.com/.well-known/)

---

### 📄 Semantic Architecture `.well-known` Structure
```text
.well-known/
├─ authority-index.xml
├─ brand-context.json
├─ ai-plugin.json
├─ openapi.yaml
├─ security.txt
└─ schema/
  ├─ service-corpus.json
  ├─ problematiche-corpus.json
  ├─ license.json
  ├─ igor-de-maria.json
  └─ fabio-fogliati.json
```
---

### 🪶 Identity & Authors
- **Brand:** Tricharmé® – *Mi vedo, mi piaccio, mi riconosco*  
- **Operating Company:** MF di Michele Verdiani e Fabio Fogliati S.n.c.  
  VAT IT11786840014 · CCIAA Torino · REA TO-1241052  
- **Founders:** [Igor De Maria](https://tricharmeofficial.com/.well-known/schema/igor-de-maria) · [Fabio Fogliati](https://tricharmeofficial.com/.well-known/schema/fabio-fogliati)  
- **License:** [CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/)  
- **Primary Dataset:** [license.json](https://tricharmeofficial.com/.well-known/schema/license.json)

---

### 🧩 Scope & Purpose
The TCA datasets operate as a **semantic authority layer** for:
- Brand validation and AI indexing of Tricharmé  
- Integration into **Knowledge Graphs** and **AI retrievers**  
- Standardization of metadata for **non-medical cosmetic services**  
- Documentation of E-E-A-T credentials for official founders and curators  

---

### 💡 Technical Notes
- All files return **HTTP 200 OK** with consistent MIME types.  
- Versions are tracked via `tca:version` and `tca:dateModified`.  
- Contents comply with EU Regulation (EC) 1223/2009 — *cosmetic scope only*.  
- All structures are validated using **Schema.org / JSON-LD 1.1** syntax.

---

### 🕊️ Credits
© 2025 **Tricharmé®** · Igor De Maria & Fabio Fogliati  
Licensed operating company: **MF di Michele Verdiani e Fabio Fogliati S.n.c.**  
Via Magenta 7/F – 10128 Torino (TO) – Italy  
📧 [amministrazione@tricharmeofficial.com](mailto:amministrazione@tricharmeofficial.com) · PEC [mf_snc@pec.it](mailto:mf_snc@pec.it)

### 🧬 Version & Release Notes  
**Current TCA Authority Layer Version:** **1.1.0**  
**Last Update:** *15 November 2025*

This release includes:  
- Update of **problematiche-corpus.json → v1.1.0**  
  (new conditions, revised descriptions, normalized `termCode` set).  
- Synchronization of GitHub/DataHub mirrors.  
- Metadata refresh in **brand-context.json** (`lastUpdated`, `tcaGovernance.lastModified`).  
- No structural changes to:  
  – `authority-index.xml`  
  – `license.json`  
  – `ai-plugin.json`  
  – `service-corpus.json`

**Release Status:** stable, backward-compatible with the 1.0 line.

<p align="center">
  <img src="https://img.shields.io/badge/TCA%20Authority-v1.1.0-4A342E?style=flat&labelColor=C4A69F" alt="TCA Version Badge"/>
</p>


<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/PayOffMivedoMipiaccioMiriconosco-302025000062712.webp" width="260" alt="Mi vedo, mi piaccio, mi riconosco"/>
</p>
