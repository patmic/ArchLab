<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=MALTG%20v3&fontSize=80&fontColor=00e5ff&animation=fadeIn&fontAlignY=38&desc=LegalTech%20Governance%20Ontology&descAlignY=60&descSize=20&descColor=94a3b8" width="100%"/>

<br/>

<!-- STACK BADGES — shields.io simple-icons (100% GitHub-safe, no inline SVG) -->
<p>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 21"/>
  <img src="https://img.shields.io/badge/Python_3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/OWL_2-6B21A8?style=for-the-badge&logo=semanticweb&logoColor=white" alt="OWL 2"/>
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3dotjs&logoColor=white" alt="D3.js"/>
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js"/>
</p>

<br/>

<h2>MALTG: Structural Digital Twin-Driven Validation<br/>of a Multidimensional LegalTech Governance Ontology</h2>
<p><em>for Integrated Enterprise Standards</em></p>

<br/>

<!-- STATUS BADGES -->
<p>
  <a href="https://github.com"><img src="https://img.shields.io/badge/version-3.0.0--legaltech-00e5ff?style=for-the-badge&labelColor=050810" alt="version"/></a>
  <a href="data/MALTG_onto.owl"><img src="https://img.shields.io/badge/OWL_2_Classes-54-a855f7?style=for-the-badge&labelColor=050810" alt="OWL Classes"/></a>
  <a href="data/dt_arch.json"><img src="https://img.shields.io/badge/DT_Services-39-10e98c?style=for-the-badge&labelColor=050810" alt="DT Services"/></a>
</p>
<p>
  <a href="backend/main.py"><img src="https://img.shields.io/badge/Validation_Dims-9-ffc947?style=for-the-badge&labelColor=050810" alt="Dimensions"/></a>
  <a href="docker-compose.yml"><img src="https://img.shields.io/badge/Docker-ready-2496ed?style=for-the-badge&labelColor=050810&logo=docker&logoColor=2496ed" alt="Docker"/></a>
  <a href="https://www.sciencedirect.com/journal/knowledge-based-systems"><img src="https://img.shields.io/badge/Target-KBS_Q1_%C2%B7_IF_8.8-ff9a3c?style=for-the-badge&labelColor=050810" alt="Target"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-f472b6?style=for-the-badge&labelColor=050810" alt="License"/></a>
</p>

<br/>

> **MALTG** is a multi-layer governance ontology **(OWL 2)** and live-validation dashboard that measures conformance between a formal enterprise standard reference (`MALTG_onto.owl`) and a structural digital twin of an actual LegalTech implementation (`dt_arch.json`).
> Integrates **TOGAF 9.2 - COBIT 5 - NIST CSF 1.1 - GDPR - eIDAS - NIS2** in a single, formally defined, automatically scored architecture.

</div>

---

## Architecture Layers

<table>
<tr>
<td width="50%" valign="top">

### 🔵 LegalTech Domain Layer *(v3 — new)*

| Concept | Regulation |
|---------|-----------|
| `Contract_Lifecycle_Management` | eIDAS 910/2014 |
| `eDiscovery_Pipeline` | EDRM · ABA Rule 1.6 |
| `Legal_DLT_Notarization` | eIDAS Art. 41 |
| `GDPR_Compliance` | GDPR 2016/679 |
| `eIDAS_Compliance` | eIDAS 2.0 · 2024/1183 |
| `NIS2_Compliance` | NIS2 2022/2555 |
| `Smart_Legal_Contracts` | UNIDROIT · LegalDocML |
| `Attorney_Client_Confidentiality` | ABA Model Rule 1.6 |
| `Legal_Knowledge_Base` | ECLI · EuroVoc |
| `Court_System_Integration` | EU e-Justice Portal |

</td>
<td width="50%" valign="top">

### 🟣 Technology Integration Layer

| Layer | Components |
|-------|-----------|
| 🤖 **AI** | ML Models · NLP Pipeline · Computer Vision · Predictive Analytics |
| ⛓️ **Blockchain** | Smart Contracts · DLT Network · Consensus · Tokenization |
| 📡 **Open Data** | APIs · Data Lakes · Open Standards · Interoperability |
| 🛡️ **Security** | Zero Trust · Encryption · IAM · Compliance |

### 🔵 Foundation Layer

| Framework | Domains |
|-----------|---------|
| **TOGAF 9.2** | ADM Cycle · 6 architecture domains · Enterprise Continuum |
| **COBIT 5** | EDM · APO · BAI · DSS · MEA |
| **NIST CSF 1.1** | Identify · Protect · Detect · Respond · Recover |

</td>
</tr>
</table>

---

## 🔬 Formal Validation Methodology

The methodology is formalized as the **5-tuple `MALTG = (Omega, Delta, Gamma, Psi, delta)`**:

<br/>

<!-- VERTICAL TIMELINE — pure HTML table, GitHub-safe -->
<table>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/01-ONTOLOGY-00e5ff?style=for-the-badge&labelColor=050810" alt="Phase 1"/>
</td>
<td>

**Omega — Ontological Reference**
OWL 2 taxonomy `(C, P, I, subseteq, A)` — source: `MALTG_onto.owl`
54 classes · 15 properties · Full RDF/XML serialization

</td>
</tr>
<tr><td align="center"><sub>▼ parse</sub></td><td></td></tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/02-DIGITAL_TWIN-10e98c?style=for-the-badge&labelColor=050810" alt="Phase 2"/>
</td>
<td>

**Delta — Structural Digital Twin**
Service graph `G(V, E)` — source: `dt_arch.json`
39 services · 54 connections · 9 architectural layers

</td>
</tr>
<tr><td align="center"><sub>▼ align via maltg_ref</sub></td><td></td></tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/03-MAPPING-a855f7?style=for-the-badge&labelColor=050810" alt="Phase 3"/>
</td>
<td>

**Gamma — Conformance Mapping**
`Gamma: C -> 2^V` via `maltg_ref` annotations
Each OWL class mapped to the set of DT services that implement it

</td>
</tr>
<tr><td align="center"><sub>▼ score</sub></td><td></td></tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/04-COVERAGE-ffc947?style=for-the-badge&labelColor=050810" alt="Phase 4"/>
</td>
<td>

**Psi — Hierarchical Coverage**
`Psi(d) = 0.4 * I[root in R] + 0.6 * (|sub_d intersect R| / |sub_d|)`
Properties: Determinism · Monotonicity · Completeness · Boundedness in [0,1]

</td>
</tr>
<tr><td align="center"><sub>▼ gap</sub></td><td></td></tr>
<tr>
<td width="80" align="center">
<img src="https://img.shields.io/badge/05-GAP-ff4d6d?style=for-the-badge&labelColor=050810" alt="Phase 5"/>
</td>
<td>

**delta — Conformance Gap**
`delta(d) = score_Omega(d) * (1 - Psi(d))`
Quantifies unrealized governance potential per dimension

</td>
</tr>
</table>

<br/>

| Symbol | Name | Definition |
|:------:|------|------------|
| **Omega** | Ontological Reference | OWL 2 taxonomy — `MALTG_onto.owl` |
| **Delta** | Structural Digital Twin | Service graph `G(V,E)` — `dt_arch.json` |
| **Gamma** | Conformance Mapping | `Gamma: C -> 2^V` via `maltg_ref` annotations |
| **Psi** | Hierarchical Coverage | `0.4*root + 0.6*(sub_d intersect R / sub_d)` |
| **delta** | Conformance Gap | `score_Omega(d) * (1 - Psi(d))` |

---

## 📊 Validation Results — v3.0

<div align="center">

| Dimension | `score_Omega` | `Psi` | `dt_score` | `delta (gap)` | Status |
|-----------|:-------------:|:-----:|:----------:|:-------------:|:------:|
| Gobernanza TOGAF | 91.7 | 70.0% | 64.2 | 27.5 | ⚠️ |
| Control COBIT | 84.3 | 100% | 84.3 | **0.0** | ✅ |
| Resiliencia NIST | 77.5 | 100% | 77.5 | **0.0** | ✅ |
| Integracion IA | 87.2 | 85.0% | 74.1 | 13.1 | ⚠️ |
| Blockchain Adoption | 76.2 | 85.0% | 64.8 | 11.4 | ⚠️ |
| Open Data Comply | 83.4 | 100% | 83.4 | **0.0** | ✅ |
| Security Posture | 87.6 | 100% | 87.6 | **0.0** | ✅ |
| Interoperabilidad | 86.3 | 100% | 86.3 | **0.0** | ✅ |
| 🔵 **LegalTech Compliance** | **69.1** | **60.0%** | **41.5** | **27.6** | 🔵 |
| **OVERALL** | **82.6** | — | **73.7** | **8.9** | |

</div>

### Gap Visual Summary

```
Dimension    Score  ─────────────────────────────── Gap
────────────────────────────────────────────────────────
TOGAF        64.2 / 91.7  ████████████████████░░░░░░░  ⚠️  -27.5
COBIT        84.3 / 84.3  ████████████████████████████  ✅   0.0
NIST         77.5 / 77.5  ██████████████████████████░  ✅   0.0
AI           74.1 / 87.2  █████████████████████████░░  ⚠️  -13.1
BLOCKCHAIN   64.8 / 76.2  ████████████████████░░░░░░░  ⚠️  -11.4
OPEN DATA    83.4 / 83.4  ████████████████████████████  ✅   0.0
SECURITY     87.6 / 87.6  █████████████████████████████  ✅   0.0
INTEROP      86.3 / 86.3  █████████████████████████████  ✅   0.0
LEGALTECH    41.5 / 69.1  ██████████████░░░░░░░░░░░░░  🔵  -27.6
────────────────────────────────────────────────────────
OVERALL      73.7 / 82.6                          gap -8.9
```

> **Top gaps:** `LEGALTECH` (-27.6) · `TOGAF` (-27.5) · `AI` (-13.1) — See `GET /api/validation` for full remediation map.

---

## 🚀 Quick Start

```bash
# 1 · Clone repository
git clone https://github.com/your-org/maltg && cd maltg

# 2 · Launch  (requires Docker >= 20.10)
docker compose up -d --build

# 3 · Open the 5-tab dashboard
open http://localhost:8080

# 4 · Verify all endpoints
curl http://localhost:8080/api/health       # { status: ok, owl_exists: true }
curl http://localhost:8080/api/validation   # 9-dim scores (live)
curl http://localhost:8080/api/methodology  # formal model + 5-phase pipeline
open http://localhost:8080/docs             # Swagger UI
```

> 💡 **Live editing:** Modify `data/MALTG_onto.owl` or `data/dt_arch.json` then press **Recargar Datos** and scores update instantly, no rebuild required.

---

## 📂 Project Structure

<details>
<summary><strong>📁 Expand full file tree</strong></summary>

```
maltg/
├── 📄  README.md
├── 🐳  docker-compose.yml              ← single-command deploy, port 8080
│
├── 📁  data/                           ← Edit here to update dashboard live
│   ├── 🦉  MALTG_onto.owl              ← OWL 2 / RDF-XML  (54 classes, 15 props)
│   └── 🔷  dt_arch.json                ← Digital Twin (39 services, 54 connections)
│
├── 📁  backend/
│   ├── 🐍  main.py                     ← FastAPI · 5 endpoints · Psi scoring engine
│   ├── 📋  requirements.txt
│   └── 🐳  Dockerfile                  ← python:3.12-slim
│
├── 📁  frontend/
│   └── 🌐  index.html                  ← SPA · 5 tabs · D3.js + Chart.js
│
├── 📁  assets/
│   ├── 🖼️   banner.svg
│   ├── 🖼️   pipeline.svg
│   └── 🖼️   results.svg
│
└── 📁  evaluation/                     ← academic replication package
    ├── 📄  expert_survey.pdf
    ├── 📊  responses_anonymized.csv
    ├── 📓  analysis.ipynb              ← reproducible statistical analysis
    └── 🧪  test_scoring.py             ← pytest: verifies all published scores
```

</details>

---

## 📡 API Reference

| Method | Endpoint | Description | Key Response Fields |
|:------:|----------|-------------|---------------------|
| `GET` | `/api/health` | System status + file hashes | `owl_exists` · `owl_hash` · `dt_hash` |
| `GET` | `/api/ontology` | OWL parsed to D3 force graph | `nodes[]` · `links[]` · `node_count` |
| `GET` | `/api/dt-arch` | Digital Twin data | `services[]` · `connections[]` · `layers[]` |
| `GET` | **`/api/validation`** | **9-dim conformance scores** | `dimensions[]` · `overall_gap` · `top_gaps` |
| `GET` | `/api/methodology` | Formal model `(Omega, Delta, Gamma, Psi, delta)` | `formal_model` · `phases[]` |
| `GET` | `/docs` | Interactive Swagger UI | — |

---

## ✏️ Extending the Ontology

<details>
<summary><strong>🦉 Add a new LegalTech concept to <code>MALTG_onto.owl</code></strong></summary>

```xml
<!-- Add inside <rdf:RDF> ... </rdf:RDF> -->
<owl:Class rdf:about="http://maltg.arch/onto#AI_Legal_Reasoning">
  <rdfs:subClassOf rdf:resource="http://maltg.arch/onto#LegalTech_Domain"/>
  <rdfs:label>AI Legal Reasoning</rdfs:label>
  <maltg:layer>legaltech</maltg:layer>
  <maltg:radius>9</maltg:radius>
  <maltg:description>Automated legal reasoning via LLMs</maltg:description>
  <maltg:score>55</maltg:score>
  <maltg:regulation>EU AI Act 2024/1689 - High-Risk AI Systems</maltg:regulation>
</owl:Class>
```

</details>

<details>
<summary><strong>🔷 Add a microservice to <code>dt_arch.json</code></strong></summary>

```json
{
  "id": "lt_ai_legal",
  "label": "AI Legal Reasoning",
  "subtitle": "LLM - EU AI Act",
  "colorType": "legaltech",
  "x": 286, "y": 558, "width": 128, "height": 40,
  "status": "active",
  "maltg_ref": ["AI_Legal_Reasoning", "AI_Layer", "NLP_Pipeline"],
  "description": "LLM-based contract analysis with EU AI Act compliance controls"
}
```

</details>

<details>
<summary><strong>🎨 Available <code>maltg:layer</code> values and colors</strong></summary>

| Value | Swatch | Layer |
|-------|:------:|-------|
| `core` | ![core](https://img.shields.io/badge/%20%20%20%20-00e5ff?style=flat-square) | MALTG root nodes |
| `togaf` | ![togaf](https://img.shields.io/badge/%20%20%20%20-00e5ff?style=flat-square) | Foundation — TOGAF 9.2 |
| `cobit` | ![cobit](https://img.shields.io/badge/%20%20%20%20-ffc947?style=flat-square) | Foundation — COBIT 5 |
| `nist` | ![nist](https://img.shields.io/badge/%20%20%20%20-ff4d6d?style=flat-square) | Foundation — NIST CSF |
| `ai` | ![ai](https://img.shields.io/badge/%20%20%20%20-a855f7?style=flat-square) | Tech Integration — AI/ML |
| `blockchain` | ![bc](https://img.shields.io/badge/%20%20%20%20-10e98c?style=flat-square) | Tech Integration — Blockchain/DLT |
| `opendata` | ![od](https://img.shields.io/badge/%20%20%20%20-ff9a3c?style=flat-square) | Tech Integration — Open Data |
| `security` | ![sec](https://img.shields.io/badge/%20%20%20%20-f472b6?style=flat-square) | Tech Integration — Security |
| `legaltech` | ![lt](https://img.shields.io/badge/%20%20%20%20-60a5fa?style=flat-square) | LegalTech Domain *(v3)* |

</details>

---

## 🎓 Academic Contribution

<div align="center">

| Attribute | Value |
|-----------|-------|
| **Full title** | *MALTG: A Multi-Layer LegalTech Governance Ontology with Structural Digital Twin-Based Conformance Validation for Integrated Enterprise Standards* |
| **Target journal** | Knowledge-Based Systems — Elsevier · **Q1 · IF 8.8** |
| **Methodology** | OWL 2 ontology engineering + Structural Digital Twin + multi-case study (N>=2 LegalTech orgs) |
| **Frameworks integrated** | TOGAF 9.2 · COBIT 5 · NIST CSF 1.1 · GDPR · eIDAS · NIS2 |
| **Scientific gap** | First formal multi-framework validator with domain-specific LegalTech ontology layer and automated DT-based conformance scoring |

</div>

<details>
<summary><strong>🔬 Research Questions</strong></summary>

| # | Question | Validation Method |
|:---:|----------|-----------------|
| **RQ1** | How can OWL 2 formalize the semantic intersection of TOGAF/COBIT/NIST in LegalTech? | Expert survey — Lawshe IVC >= 0.78 · Cronbach alpha >= 0.70 |
| **RQ2** | Can a Structural Digital Twin automatically quantify governance conformance gaps? | Psi engine vs manual audit — Pearson r >= 0.70 |
| **RQ3** | Which dimensions show the largest gaps in LegalTech SMEs? | Multi-case study + statistical analysis |
| **RQ4** | How does MALTG compare to ArchiMate+TOGAF and SABSA? | 10-attribute Framework Comparison Matrix |

</details>

<details>
<summary><strong>📖 BibTeX Citation</strong></summary>

```bibtex
@article{maltg_legaltech_2025,
  title   = {{MALTG}: A Multi-Layer {LegalTech} Governance Ontology
             with Structural Digital Twin--Based Conformance Validation
             for Integrated Enterprise Standards},
  journal = {Knowledge-Based Systems},
  year    = {2025},
  note    = {Under review},
  doi     = {10.5281/zenodo.XXXXX},
  url     = {https://github.com/your-org/maltg}
}
```

</details>

---

## 🔬 Experimental Reproducibility

<div align="center">

| Level | ACM Standard | MALTG Guarantee |
|:-----:|:------------:|-----------------|
| **L1** Repeatability | Artifact Available | `docker compose up` — identical scores on any machine with Docker >= 20.10 |
| **L2** Replicability | Artifact Evaluated | Zenodo DOI · OWL in Turtle + RDF/XML · `pytest evaluation/test_scoring.py` |
| **L3** Reproducibility | Results Reproduced | Expert survey public · anonymized data open · Jupyter analysis executable |

</div>

```bash
# Independently verify all published validation scores
pip install requests pytest
pytest evaluation/test_scoring.py -v

# Expected:
# TOGAF     onto=91.7  dt=64.2  gap=27.5  PASS  ✅
# COBIT     onto=84.3  dt=84.3  gap=0.0   PASS  ✅
# NIST      onto=77.5  dt=77.5  gap=0.0   PASS  ✅
# AI        onto=87.2  dt=74.1  gap=13.1  PASS  ✅
# BC        onto=76.2  dt=64.8  gap=11.4  PASS  ✅
# OD        onto=83.4  dt=83.4  gap=0.0   PASS  ✅
# SEC       onto=87.6  dt=87.6  gap=0.0   PASS  ✅
# INTEROP   onto=86.3  dt=86.3  gap=0.0   PASS  ✅
# LEGALTECH onto=69.1  dt=41.5  gap=27.6  PASS  ✅
# OVERALL   onto=82.6  dt=73.7  gap=8.9   PASS  ✅
```

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

<div align="center">

<p>
  <a href="https://www.opengroup.org/togaf"><img src="https://img.shields.io/badge/TOGAF-9.2-00e5ff?style=for-the-badge&labelColor=050810" alt="TOGAF"/></a>
  <a href="https://www.isaca.org/resources/cobit"><img src="https://img.shields.io/badge/COBIT-5-ffc947?style=for-the-badge&labelColor=050810" alt="COBIT"/></a>
  <a href="https://www.nist.gov/cyberframework"><img src="https://img.shields.io/badge/NIST_CSF-1.1-ff4d6d?style=for-the-badge&labelColor=050810" alt="NIST CSF"/></a>
  <a href="https://gdpr.eu"><img src="https://img.shields.io/badge/GDPR-2016%2F679-60a5fa?style=for-the-badge&labelColor=050810" alt="GDPR"/></a>
  <a href="https://digital-strategy.ec.europa.eu"><img src="https://img.shields.io/badge/eIDAS-2.0-60a5fa?style=for-the-badge&labelColor=050810" alt="eIDAS"/></a>
  <a href="https://www.enisa.europa.eu"><img src="https://img.shields.io/badge/NIS2-2022%2F2555-60a5fa?style=for-the-badge&labelColor=050810" alt="NIS2"/></a>
</p>

<sub><b>MALTG Architecture Validator</b> · FastAPI · D3.js v7 · Chart.js v4 · OWL 2 · Docker Compose</sub><br/>
<sub>TOGAF® — The Open Group · COBIT® — ISACA · NIST CSF — NIST (public domain) · GDPR — EUR-Lex · eIDAS — EU Commission · NIS2 — ENISA</sub>

</div>
