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
├── UTP_Vocabularies/         # The OML Rosetta project root
│   └── src/
│       ├── oml/example.com/project/
│       │   ├── description/  # OML description files (e.g., Catapult instance data)
│       │   └── vocabulary/   # OML vocabulary files (the UTP Test ontologies)
│       └── sparql/           # Example SPARQL query files
└── README.md
```

---
## The Ontology Stack

These UTP ontologies are designed to be mapped to the foundation and core ontologies within the **University of Arizona Ontology Stack (UAOS)**. This layered approach ensures that the UTP models are interoperable with other domain ontologies built on the same stack, promoting consistency and cross-domain analysis.

---

## 🚀 Getting Started

### Requirements
- [OML Rosetta](https://github.com/opencaesar/oml-rosetta)  
- Java 11+  
- Git  

### Clone the repo
```bash
git clone https://github.com/panditpooja/UTP_Ontologies.git
cd UTP_Ontologies
```

### Running Ontology Checks
You can load the OML files in **OML Rosetta** to run consistency checks and explore the ontology.

### Running SPARQL Queries
Queries are provided under `/queries`.

---

## 📊 Catapult Example
The **catapult test dataset** illustrates how UTP ontologies can:  
- Detect semantic inconsistencies automatically  
- Extract insights (e.g., shared resource conflicts, verdict dashboards, faulty components)  
- Support traceability and interoperability in digital test workflows
  
---
<!--
## 📜 Citation
If you use the artifacts or concepts from this work in your research, please cite our paper.

> P. Pandit, J. Gregory, H. Fiore, and A. Salado,  
> *"An Ontological Representation of the UML Testing Profile for Digital Test and Evaluation,"* 2025.  

---
-->

## 🤝 Acknowledgements
This research has been supported by the **Systems Engineering Research Center (SERC)**, a University Affiliated Research Center (UARC) housed at Stevens Institute of Technology.

---

## ✍️ Authors
- **Pooja Pandit** – poojapandit@arizona.edu  
- **Dr. Joe Gregory** – joegregory@arizona.edu  
- **Hunter Fiore** – hunterfiore04@arizona.edu  
- **Dr. Alejandro Salado** – alejandrosalado@arizona.edu  
