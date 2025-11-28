# Tooth Generative Networks: ToothGenNet
A unified research series on deep generative modeling of tooth anatomy.

---

- **Unconditional generative model (VAE-based) on Central Incisors**  
  Repository: https://github.com/superbijk/toothgennet-anterior  

  *A Latent Variable Deep Generative Model for 3D Anterior Tooth Shape* (Journal of Prosthodontics, 2025)  
  DOI: 10.1111/jopr.14092  
  PubMed: PMID 40624318  

  **Contexts**
  - Generate Samples – generate new tooth shapes  
  - Interpolate – W-space interpolation between two samples  
  - Restore Damaged Tooth – simulate damage and restore via latent optimization  
  - Operates on a pilot dataset available only in this repository  

---

- **Unconditional Model Extension (Upper-Arch Translation)**  
  Repository: <TO BE RELEASED>  

  *Flow-based Latent Transformation Network for Identity-Aware Latent Translation*  
  *CSAI 2025 — Proceedings (in press)*  

  **Contexts**
  - Pooling-by-Multihead-Attention based (PMA) latent translator for mapping a single anchor tooth latent code to target tooth classes  
  - Enables identity-aware prediction of missing teeth across U1–U7  
  - Builds on a frozen PointFlow-style VAE backbone  
  - Supports whole-arch completion from one observed tooth  

---

- **The Pose-Aligned Identity-Grouped Tooth Dataset**  
  Repository: <TO BE RELEASED>  

  *A Derived 3DTeethSeg’22 Resource for Generative Modeling*  

  **Contexts**
  - Pose-aligned and normalized tooth point clouds spanning multiple classes  
  - Identity-grouped samples enabling cross-tooth relational and predictive modeling  
  - Designed for generative, reconstructive, and hierarchical latent modeling  
  - Facilitates multi-tooth prediction and identity-consistent synthesis tasks  

---

- <MODEL: TBA>
- <APPLICATION: TBA>

---

## Correspondence
**Chawalit Chanintonsongkhla**  
School of Dentistry, University of Phayao  
Email: **chawalit.ch@up.ac.th**
