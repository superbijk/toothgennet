# ToothGenNet

A research series on deep generative modeling of tooth anatomy.

## Repositories

| Project (Repo) | Overview | Publication |
|---|---|---|
| [**A Latent Variable Deep Generative Model for 3D Anterior Tooth Shape (toothgennet-anterior)**](https://github.com/superbijk/toothgennet-anterior) | Unconditional PointFlow variational autoencoder for 3D anterior tooth shape, supporting sample generation, latent interpolation, and damaged-tooth restoration through latent optimization. | Chanintonsongkhla et al., *J. Prosthodont.*, 2025. [DOI 10.1111/jopr.14092](https://doi.org/10.1111/jopr.14092) · PMID 40624318 |
| **Flow-Based Latent Transformation Network for Identity-Aware Latent Translation of Upper Arch Tooth Point Clouds** | Pooling-by-Multihead-Attention (PMA) latent translator mapping a single anchor tooth latent to all U1–U7 upper-arch classes on a frozen PointFlow backbone, enabling whole-arch completion from one observed tooth. | Chanintonsongkhla et al., *Proc. CSAI 2025*. [DOI 10.1145/3788149.3788240](https://doi.org/10.1145/3788149.3788240) |
| [**Neural Residual Correction for 3D Tooth Point Cloud Canonicalization (toothgennet-alignment)**](https://github.com/superbijk/toothgennet-alignment) | Seven classical, neural, and hybrid methods for mapping arbitrary upper teeth into class-specific canonical poses. The best method (gPCA-rPointNet) reaches a Chamfer Distance to per-sample ground truth of 0.62 × 10⁻³ and a mean geodesic rotation error of 3.3° on the 3DTeethSeg validation split. | *under review* |
| **Pose-aligned identity-grouped tooth dataset** | A 3DTeethSeg'22-derived resource: pose-aligned and normalized tooth point clouds spanning U1–U7, identity-grouped across classes to support cross-tooth relational and generative modeling. | *in preparation* |

## Correspondence
**Chawalit Chanintonsongkhla** · <chawalit.ch@up.ac.th>
