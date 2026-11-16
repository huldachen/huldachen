# Hulda / Yuchun Chen

Computational biology/chemistry and machine learning. I work at the intersection of statistical modeling, molecular simulation, and comp-bio/chem  analysis.

Currently in 📍Bay Area, Solving Challenges in Chemistry & Biology

## Selected projects

- **[antibody-plm-benchmark](https://github.com/huldachen/antibody-plm-benchmark)** —
  No *zero-shot* PLM, inverse-folding model, or low-N regressor beats counting
  mutations at retrieving antibody affinity improvers — a result that only
  appears under distance-aware splits, budget-matched precision@K, and
  tier-separated positive sets. Supervision *does* fix the anti-prediction
  (cross-fitted near-improver AUROC 0.45 → 0.90), but the pretrained model
  contributes none of it: a LoRA-tuned ESM-2-650M is indistinguishable from a
  logistic regression on 260 one-hot features (paired DeLong, p = 0.995), and
  across three datasets never beats a cheap sequence encoding — losing outright
  to a 3-mer ridge on KyDab.

- **[immune-receptor-eval](https://github.com/huldachen/immune-receptor-eval)** —
  V-gene + CDR3β length alone reach 0.788 mean per-epitope AUROC on TCR–pMHC
  discrimination without seeing the peptide (28 epitopes, 95% CI 0.763–0.814;
  0.487 under label permutation) — the interaction-free baseline any TCR binding
  model must beat. Same diagnostic procedure as above, different receptor system.

- **[peak2gene-benchmark](https://github.com/huldachen/peak2gene-benchmark)** —
  Head-to-head benchmark of six peak–gene linkage methods on a colon single-cell
  atlas (Hickey 2023), ranked by IBD GWAS heritability enrichment via stratified
  LD-score regression. Paired multiome correlation concentrates heritability
  10–21× in <0.5% of SNPs; three methodological caveats not addressed in the
  original publications.

- **[amazon-multimethod-occupancy](https://github.com/huldachen/amazon-multimethod-occupancy)** —
  Hierarchical Bayesian occupancy modeling integrating camera traps, eDNA, line
  transects, and acoustic surveys across 12 transects in the Brazilian Amazon to
  assess how Brazil nut harvesting affects wildlife biodiversity.


## Publications

- Yang, J.G., Chen, H.Y.‡, Guardado, J.H.‡, Gardner, M., Foronda, M.S. "Two Stages of Substrate Discrimination Dictate Selectivity in the E. coli MetNI-Q ABC Transporter System." *J. Biol. Chem.*, 2025. [[paper]](https://doi.org/10.1016/j.jbc.2025.108672)
- Kamath, G., Illarionov, A., ..., Chen, Y., ..., Kornberg, R.D., Levitt, M., Fain, B. "Combining Force Fields and Neural Networks for an Accurate Representation of Bonded Interactions." *J. Phys. Chem. A*, 2024. [[paper]](https://doi.org/10.1021/acs.jpca.3c06781)
- Kurnikov, I.V., Pereyaslavets, L., ..., Chen, Y., ..., Kornberg, R.D., Levitt, M., Fain, B. "Neural Network Corrections to Intermolecular Interaction Terms of a Molecular Force Field Capture Nuclear Quantum Effects in Calculations of Liquid Thermodynamic Properties." *J. Chem. Theory Comput.*, 2024. [[paper]](https://doi.org/10.1021/acs.jctc.3c01339)
- Chen, Y.-C. et al. "Revisiting 3D Context Modeling with Supervised Pre-training for Universal Lesion Detection in CT Slices." *MICCAI*, 2020. [[paper]](https://arxiv.org/abs/2012.08770)

## Contact

📧 hulda.cyc@gmail.com

🧬 [LinkedIn](https://www.linkedin.com/in/yuchun-huldachen/)

🎓 [Google Scholar](https://scholar.google.com/citations?user=1P75Pk4AAAAJ&hl=en)

🌐 [huldacyc.com](https://huldacyc.com)
