# An Ontological Representation of the UML Testing Profile(UTP) for Digital Test and Evaluation

This repository contains the ontological representation of the **UML Testing Profile (UTP) v2.1** using the **Ontological Modeling Language (OML)**.  
It accompanies the research paper *"An Ontological Representation of the UML Testing Profile for Digital Test and Evaluation"*.

---

## 📖 Overview
The UML Testing Profile (UTP) is widely used for specifying test architectures, procedures, and verdicts in model-based testing.  
However, its semi-formal semantics limit tool interoperability and automated reasoning in **Digital Engineering (DE)** workflows.  

This project:
- Formalizes UTP constructs (TestCases, TestProcedures, Configurations, Data) in OML.
- Provides a principled ontology stack aligned with the **University of Arizona Ontology Stack (UAOS)**.
- Demonstrates reasoning and querying via **SPARQL** using a notional **catapult test case study**.
- Enables **semantic consistency checks**, **tool-agnostic integration**, and **query-driven insights**.

---

## 📂 Repository Structure
```
📁 UTP_Ontologies
 ├── processes/         # Ontology for processes (TestCase, TestAction, VerdictCalculation)
 ├── procedures/        # Ontology for procedures (TestProcedure, ExecutionSchedule)
 ├── configurations/    # Ontology for test configurations
 ├── data/              # Ontology for test data and datasets
 ├── examples/          # Catapult test case study with OML instances
 └── queries/           # SPARQL queries (Shared Component Check, Verdict Check, Quality Check)
```

---

## 🚀 Getting Started

### Requirements
- [OML Rosetta](https://github.com/opencaesar/oml-rosetta)  
- Java 11+  
- Git  

### Clone the repo
```bash
git clone https://github.com/YourUsername/UTP_Ontologies.git
cd UTP_Ontologies
```

### Running Ontology Checks
You can load the OML files in **OML Rosetta** to run consistency checks and explore the ontology.

### Running SPARQL Queries
Queries are provided under `/queries`. They can be executed with any standard SPARQL processor against the exported dataset.

---

## 📊 Catapult Example
The **catapult test dataset** illustrates how UTP ontologies can:  
- Detect semantic inconsistencies automatically  
- Extract insights (e.g., shared resource conflicts, verdict dashboards, faulty components)  
- Support traceability and interoperability in digital test workflows
  
---
<!--
## 📜 Citation
If you use this work in your research, please cite:

> P. Pandit, J. Gregory, H. Fiore, and A. Salado,  
> *"An Ontological Representation of the UML Testing Profile for Digital Test and Evaluation,"* 2025.  

---
-->

## 🤝 Acknowledgements
This work was supported by the **Systems Engineering Research Center (SERC)**, a UARC at Stevens Institute of Technology.

---

## ✍️ Authors
- **Pooja Pandit** – poojapandit@arizona.edu  
- **Dr. Joe Gregory** – joegregory@arizona.edu  
- **Hunter Fiore** – hunterfiore04@arizona.edu  
- **Dr. Alejandro Salado** – alejandrosalado@arizona.edu  
