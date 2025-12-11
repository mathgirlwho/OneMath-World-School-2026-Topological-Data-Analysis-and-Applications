# TDA OneMath World School 2026 — Introduction

**Topological Data Analysis and Applications**

The OneMath World School is a first-of-its-kind global program initiated by BIRS partner institutions. It is designed to connect young mathematical talent with leading experts in emerging fields. This initiative brings together advanced undergraduates, graduate students, and early-career researchers from around the world to collaborate with established leaders and explore cutting-edge topics at the intersection of theory and application. Visit the link for more details.

This School provides a practical introduction to topological data analysis (TDA) with emphasis on hands-on techniques and implementation. Participants will learn to apply TDA methods, particularly Persistent Homology and the Mapper algorithm, to extract meaningful features from complex datasets.

This repository serves as the course materials, notebooks, slides, datasets, and contribution guidelines for the TDA OneMath World School 2026 held at Chennai Mathematical Institute (FC Kohli Center).

**Dates:** February 20–28, 2026

**Official course page:** [https://www.cmi.ac.in/~pdeshpande/tda_omws_2026.html](https://www.cmi.ac.in/~pdeshpande/tda_omws_2026.html)

---


## Quick introduction

Topological Data Analysis (TDA) provides tools to capture shape- and connectivity-based features of data. This workshop focuses on practical TDA building blocks such as:

* Simplicial complexes and simplicial homology
* Persistent homology (barcodes & persistence diagrams)
* Vectorization methods: persistence landscapes, Betti curves, persistence images
* Mapper algorithm and Reeb graph intuition
* Software: `scikit-tda`, `ripser.py`, `giotto-tda`, `kepler-mapper`

The School balances theory (morning sessions) with hands-on tutorials (afternoon sessions) and group projects.

---

## Tutorials & Hands-On Notebooks

The **`tutorials/`** folder contains a curated set of Jupyter notebooks prepared by the Teaching Assistants.  
These notebooks provide a thorough, implementation-oriented introduction to core concepts in Topological Data Analysis (TDA).  
Each notebook blends intuition, theory, and practical examples using tools such as `ripser.py`, `giotto-tda`, `scikit-tda`, and KeplerMapper.

### **List of Tutorial Notebooks**

- **Ahana — Vectorization Methods in TDA**  
  Introduction to topological feature representations:  
  - persistence landscapes  
  - persistence images  
  - Betti curves  
  - persistence entropy  
  Includes demonstrations on synthetic and real datasets.

- **Aman — KeplerMapper & the Mapper Algorithm**  
  A hands-on introduction including:  
  - theory behind Mapper  
  - choices of filters, covers, lenses  
  - real-data visualizations and exploration workflows  

- **Aniket — Euler Characteristic Transform (ECT)**  
  Covers:  
  - theory behind the ECT and intuition for invertibility  
  - computing ECT on shapes and point clouds  
  - full pipeline for a classification problem using ECT features  

- **Ketaki — Classification with Classical ML Models**  
  A supervised learning pipeline using a 5-digit MNIST subset (1000 images per class).  
  Includes:  
  - SVM, Decision Trees, Random Forests  
  - Logistic Regression, Naive Bayes, k-NN  
  - intuitive algorithm explanations  
  - model comparison tables and feature-importance visualizations  

- **Sampriti — Basics of Persistent Homology**  
  Foundations of PH with step-by-step examples:  
  - Vietoris–Rips complexes  
  - barcodes & persistence diagrams  
  - bottleneck distance and stability  
  - toy datasets illustrating geometric intuition  

- **Shreya — Takens Embedding & Time-Series TDA**  
  Notebook covers:  
  - delay embeddings and Takens’ theorem (intuition + examples)  
  - basics of discrete dynamical systems  
  - PH-based classification of ECG / EEG signals  
---

## License

This repository is available under the MIT License. See `LICENSE`.

---

## Contact

Local organizers (from official page): Priyavrat Deshpande, Vijay Natarajan, Siddharth Pritam. For repo-specific queries, kindly please open an issue or tag the `maintainers` team on the organization GitHub.

---

*Prepared for the TDA OneMath World School 2026 — this README may be adapted and updated as the workshop progresses.*
