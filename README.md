# ToothGenNet

A research series on deep generative modeling of tooth anatomy.

## Repositories

| Project | Repository | Reference |
|---|---|---|
| **Anterior tooth generative model** — unconditional VAE on central incisors with sample generation, latent interpolation, and damaged-tooth restoration. | [superbijk/toothgennet-anterior](https://github.com/superbijk/toothgennet-anterior) | Chanintonsongkhla et al., *A Latent Variable Deep Generative Model for 3D Anterior Tooth Shape.* J. Prosthodont., 2025. [DOI 10.1111/jopr.14092](https://doi.org/10.1111/jopr.14092) · PMID 40624318 |
| **Upper-arch latent translation** — PMA-based flow translator mapping a single anchor tooth latent to all U1–U7 classes on a frozen PointFlow backbone. | *To be released* | *Flow-based Latent Transformation Network for Identity-Aware Latent Translation.* CSAI 2025 (in press). |
| **Pose-aligned identity-grouped tooth dataset** — derived from 3DTeethSeg'22; pose-aligned, identity-grouped point clouds spanning U1–U7 for cross-tooth generative modeling. | *To be released* | Dataset descriptor (in preparation). |
| **Tooth point cloud canonicalization** — seven classical, neural, and hybrid methods for mapping arbitrary upper teeth into class-specific canonical poses. Best method reaches CD 0.62 × 10⁻³ and mean rotation error 3.3°. | [superbijk/toothgennet-alignment](https://github.com/superbijk/toothgennet-alignment) | *Neural Residual Correction for 3D Tooth Point Cloud Canonicalization* (under review). |

## Correspondence
**Chawalit Chanintonsongkhla** · <chawalit.ch@up.ac.th>
