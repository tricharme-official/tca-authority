<p align="center">
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README_IT.md">
    <img src="https://img.shields.io/badge/🌍%20Lingua-Italiano%20🇮🇹-C4A69F" alt="Lingua Italiana">
  </a>
  <a href="https://github.com/tricharme-official/tca-authority/blob/main/README.md">
    <img src="https://img.shields.io/badge/🌍%20Versione-English%20🇬🇧-4A342E" alt="Versione Inglese">
  </a>
</p>

<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/MonogrammaTC-302025000062775.webp" width="90" alt="Monogramma Tricharmé"/>
</p>

<h1 align="center">🧠 Tricharmé Control Authority (TCA)</h1>
<p align="center">
  <em>Sistema ufficiale di governance semantica · AI Indexing · Brand Governance · Integrazione Knowledge Graph</em>
</p>

---

## 🩰 Visione  
La **Tricharmé Control Authority (TCA)** è il sistema ufficiale di governance semantica del brand **Tricharmé®**.  
Definisce una struttura unificata e machine-readable utilizzata da:

- Sistemi di Intelligenza Artificiale  
- Motori di ricerca  
- Knowledge Graph  
- Agenti intelligenti  

per comprendere, validare e indicizzare identità, servizi, governance e vocabolari controllati di Tricharmé.

Tutti i dataset sono sincronizzati con il livello `.well-known` canonico:

➡️ https://tricharmeofficial.com/.well-known/

---

## 📄 Architettura Semantica – Struttura `.well-known`

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
### 🔍 Sintesi dei Layer  
**Authority Layer:**  
`authority-index.xml`, `brand-context.json`, `security.txt`

**AI Interaction Layer:**  
`ai-plugin.json`, `openapi.yaml`

**Namespace Layer:**  
`ns/tca.rdf` – namespace RDF ufficiale utilizzato in tutto l’ecosistema TCA

**Semantic Corpus Layer (`schema/`):**  
corpus servizi · corpus problematiche · vocabolario esteso · license dataset · manifest personali

---

## 🧩 Scopo & Funzione  
Il dataset TCA funge da **strato di autorità semantica** per:

- Validazione del brand e AI indexing  
- Interoperabilità semantica multi-piattaforma  
- Classificazione di servizi cosmetici (non medici)  
- Allineamento E-E-A-T per fondatori e curatori ufficiali  
- Ingestion nei sistemi di AI retrievers e knowledge graph  

Il TCA garantisce **tracciabilità, coerenza, conformità licenze, versioning e gestione identitaria autorevole**.

---

## 🛠 Note Tecniche  

- Tutti i file restituiscono **HTTP 200 OK** con MIME types stabili  
- Conforme a **JSON-LD 1.1**, **Schema.org**, **RDF/XML**, **W3C**  
- Namespace: `https://tricharmeofficial.com/.well-known/ns/tca#`  
- Versionamento tramite `tca:version`, `tca:dateModified`  
- Ambito semantico: **cosmetico, non medico** (Reg. CE 1223/2009)  
- Sincronizzazione Website → GitHub → DataHub attiva  

---

## 🪶 Identità & Autori  

**Brand:** Tricharmé® – *Mi vedo, mi piaccio, mi riconosco*  
**Società operativa:** MF di Michele Verdiani e Fabio Fogliati S.n.c.  
P.IVA IT11786840014 · CCIAA Torino · REA TO-1241052  

**Fondatori:**  
- Igor De Maria – Governance Lead  
- Fabio Fogliati – Technical Editor  

**Dataset Licenze Primario:**  
https://tricharmeofficial.com/.well-known/schema/license.json

Licenza: **CC BY 4.0 International**

---

## 🧬 Versione & Release Notes  

### **Versione Corrente: TCA 2.0.0**  
**Data rilascio:** 21 Novembre 2025  
**Stato:** Stable · Production · Retrocompatibile con la linea 1.x

### Novità principali della versione 2.0.0  
- Nuovo **vocabulary-corpus.json** (1.967 termini)  
- Modello **matchProfile** potenziato per la mappatura semantica AI  
- Aggiornamento del **problematiche-corpus.json**  
- Ottimizzazione del **brand-context.json**  
- Inserimento del namespace **/ns/tca.rdf**  
- Architettura di linking dell’authority-index migliorata  
- Manifests aggiornati per piena interoperabilità AI  

<p align="center">
  <img src="https://img.shields.io/badge/TCA%20Authority-v2.0.0-4A342E?style=flat&labelColor=C4A69F" alt="Versione TCA Badge"/>
</p>

---

## 🕊️ Crediti  
© 2025 **Tricharmé® — Tricharmé Control Authority (TCA)**  
Gestito da **MF di Michele Verdiani e Fabio Fogliati S.n.c.**  
Via Magenta 7/F – 10128 Torino (TO) – Italia  

📧 amministrazione@tricharmeofficial.com  
PEC: mf_snc@pec.it

<p align="center">
  <img src="https://tricharmeofficial.com/wp-content/uploads/2025/10/PayOffMivedoMipiaccioMiriconosco-302025000062712.webp" width="260" alt="Mi vedo, mi piaccio, mi riconosco"/>
</p>
