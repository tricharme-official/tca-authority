<p align="center">
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README_IT.md">
    <img src="https://img.shields.io/badge/🌍%20Read%20in-Italiano%20🇮🇹-C4A69F" alt="Read in Italian">
  </a>
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README.md">
    <img src="https://img.shields.io/badge/🌍%20Current-English%20🇬🇧-4A342E" alt="Read in English">
  </a>
</p>

<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/MonogrammaTC-302025000062775.webp" width="90" alt="Tricharmé Monogram"/>
</p>

<h1 align="center">🧠 Tricharmé Control Authority (TCA)</h1>
<p align="center">
  <em>Official Semantic Authority Layer · AI Indexing · Brand Governance · Knowledge Graph Integration</em>
</p>

---

## 🩰 Vision  
The **Tricharmé Control Authority (TCA)** is the official semantic governance system of the **Tricharmé®** brand.  
It provides a unified, machine-readable framework used by:

- AI systems  
- Search engines  
- Knowledge graphs  
- Intelligent agents  

to understand, validate and index Tricharmé’s identity, services, governance metadata, and controlled vocabularies.

All datasets are synchronized with the canonical `.well-known` authority layer:

➡️ https://tricharmeofficial.com/.well-known/

---

## 📄 Semantic Architecture – `.well-known` Structure

```text
.well-known/
├─ authority-index.xml
├─ brand-context.json
├─ ai-plugin.json
├─ openapi.yaml
├─ security.txt
├─ ns/
│   └─ tca.rdf
└─ schema/
    ├─ service-corpus.json
    ├─ problematiche-corpus.json
    ├─ vocabulary-corpus.json
    ├─ license.json
    ├─ igor-de-maria.json
    └─ fabio-fogliati.json
```
---
### 🔍 Layer Summary  
**Authority Layer:**  
`authority-index.xml`, `brand-context.json`, `security.txt`

**AI Interaction Layer:**  
`ai-plugin.json`, `openapi.yaml`

**Namespace Layer:**  
`ns/tca.rdf` – official RDF namespace used across all TCA datasets

**Semantic Corpus Layer (`schema/`):**  
service corpus · problematiche corpus · vocabulary corpus · license dataset · persona manifests

---

## 🧩 Purpose & Scope  
The TCA dataset serves as a **semantic authority layer** for:

- Brand validation and AI indexing  
- Cross-platform semantic interoperability  
- Non-medical cosmetic service classification  
- E-E-A-T alignment for official founders and curators  
- AI retrievers and knowledge graph ingestion pipelines  

TCA ensures **data traceability, consistency, licensing compliance, version control, and authoritative identity management**.

---

## 🛠 Technical Notes  

- All files return **HTTP 200 OK** with stable MIME types  
- Fully compliant with **JSON-LD 1.1**, **Schema.org**, **RDF/XML**, and **W3C** standards  
- Namespace: `https://tricharmeofficial.com/.well-known/ns/tca#`  
- Versioning tracked via `tca:version`, `tca:dateModified`  
- Semantic scope: **cosmetic, non-medical** (EC 1223/2009 compliant)  
- GitHub → Website → DataHub synchronization enabled  

---

## 🪶 Identity & Authors  

**Brand:** Tricharmé® – *Mi vedo, mi piaccio, mi riconosco*  
**Operating Company:** MF di Michele Verdiani e Fabio Fogliati S.n.c.  
VAT IT11786840014 · CCIAA Torino · REA TO-1241052  

**Founders:**  
- Igor De Maria – Governance Lead  
- Fabio Fogliati – Technical Editor  

**Primary License Dataset:**  
https://tricharmeofficial.com/.well-known/schema/license.json

License: **CC BY 4.0 International**

---

## 🧬 Version & Release Notes  

### **Current Version: TCA 2.0.0**  
**Release Date:** 21 November 2025  
**Status:** Stable · Production · Backward-compatible with 1.x

### Highlights of TCA 2.0.0  
- New **vocabulary-corpus.json** (1,967 terms)  
- Reinforced **matchProfile** model for AI semantic mapping  
- Updated **problematiche-corpus.json**  
- Cleaned & optimized **brand-context.json**  
- Added **/ns/tca.rdf** ontology namespace  
- Improved authority-index linking architecture  
- Updated manifests for AI interoperability  

<p align="center">
  <img src="https://img.shields.io/badge/TCA%20Authority-v2.0.0-4A342E?style=flat&labelColor=C4A69F" alt="TCA Version Badge"/>
</p>

---

## 🕊️ Credits  
© 2025 **Tricharmé® — Tricharmé Control Authority (TCA)**  
Managed by **MF di Michele Verdiani e Fabio Fogliati S.n.c.**  
Via Magenta 7/F – 10128 Torino (TO) – Italy  

📧 amministrazione@tricharmeofficial.com  
PEC: mf_snc@pec.it

<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/PayOffMivedoMipiaccioMiriconosco-302025000062712.webp" width="260" alt="Mi vedo, mi piaccio, mi riconosco"/>
</p>
