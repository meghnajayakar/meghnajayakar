# Hi, I'm Meghna 👋

**MSc Applied Bioinformatics (King's College London, Distinction)** · B.Tech Data Science (NMIMS MPSTME, 3rd Rank Merit Holder)

I work on human genomics and computational biology: variant calling and prioritisation, RNA-seq, reproducible workflows on HPC, and deep learning for biological and clinical data.

📫 [LinkedIn](https://linkedin.com/in/meghna-jayakar)

> 🔎 Open to bioinformatics and computational biology roles in India.

---

## 🔬 What I work on

- **Human genomics:** WGS variant calling, filtering and annotation (GATK, bcftools, Ensembl VEP, gnomAD, ENCODE cCRE)
- **Transcriptomics:** bulk RNA-seq differential expression (DESeq2), pathway enrichment, spatial transcriptomics (10x Visium)
- **Regulatory variant interpretation:** motif disruption analysis (MotifDiff, FIMO), AlphaMissense, AlphaGenome
- **Workflows and HPC:** Nextflow (DSL2), SLURM, Docker, Singularity, Conda
- **Deep learning for biology:** sequence models for TFBS prediction, biomedical NLP, computational pathology

---

## ⭐ Featured projects

### [HIV-1 iPSC Project](https://github.com/meghnajayakar/HIV-1_iPSC_Project) (MSc research project)
Used iPSC genetic variation to define HIV-1 regulatory networks. Starting from ~20 million variants in whole-genome sequencing data from two independent cohorts, I built an HPC pipeline and a multi-layer annotation framework that narrowed them to **15 coding and 53 regulatory candidates**, then integrated RNA-seq differential expression, motif analysis and orthogonal AlphaMissense/AlphaGenome validation.
`GATK` `bcftools` `VEP` `DESeq2` `MotifDiff` `FIMO` `SLURM` `R` `Python`

### [Nextflow Variant Calling and Annotation Pipeline](https://github.com/meghnajayakar/nextflow_sars-cov2-variant-pipeline)
Modular Nextflow (DSL2) pipeline for germline variant calling and annotation (GATK HaplotypeCaller, joint genotyping, hard filtering, Ensembl VEP). Containerised with Docker, with configurable profiles and resumable execution; validated end to end on simulated SARS-CoV-2 reads.
`Nextflow` `Docker` `GATK` `VEP`

### [Spatial Transcriptomics of Human Lymph Node](https://github.com/meghnajayakar/visium-human-lymph-node)
QC, clustering and marker-based annotation of a 10x Visium lymph node section. Used preranked GSEA and gene-set scoring to characterise a proliferative germinal-centre cluster and an interferon-response cluster, with documented limitations.
`Scanpy` `GSEApy` `Python`

### [Transcription Factor Binding Site Prediction](https://github.com/meghnajayakar/Transcription-Factor-Binding-Site-Prediction-in-DNA-Sequences-using-CNNs-and-BiLSTMs)
Extended a DanQ-style CNN + BiLSTM across 690 sparse ChIP-seq targets. Cut parameters from ~218.8M to ~2.6M with global max pooling, added reverse-complement augmentation and evaluated with ROC-AUC and PR-AUC rather than accuracy.
`TensorFlow` `Deep learning` `Genomics`

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| **Genomics** | GATK, bcftools, Ensembl VEP, gnomAD, ENCODE cCRE, AlphaMissense, AlphaGenome, MotifDiff, FIMO, IGV |
| **Transcriptomics** | DESeq2, Scanpy, GSEApy, Enrichr, KEGG, Reactome |
| **Languages** | Python, R, SQL, Bash |
| **ML / DL** | PyTorch, TensorFlow, Keras, scikit-learn, BioPython, SciSpaCy |
| **Infrastructure** | Linux, SLURM, Nextflow, Docker, Singularity, Conda, Git |
| **Computational pathology** | QuPath, OpenSlide, TiffSlide |

---

## 📄 Publications

- Jayakar, M.B., & Subhash, S. (2026). *Graph Theoretical Insights into the Genomic Integrity of Saccharomyces cerevisiae.* Research Journal of Pharmacy and Technology, 19(6). [doi:10.52711/0974-360X.2026.00398](https://doi.org/10.52711/0974-360X.2026.00398) 🏆 Best Paper Award, IMRCSIES-2025
- Jayakar, M.B., et al. (2025). *Diagnosing Alzheimer's Disease Through Hippocampal MRI Analysis Using Artificial Intelligence.* CRC Press/Taylor & Francis. [doi:10.1201/9781003716648-5](https://doi.org/10.1201/9781003716648-5)
- Jayakar, M.B., & Subhash, S. (2025). *Graph-Based Approaches in Bioinformatics.* Ecology, Environment and Conservation, 31(Suppl.). [doi:10.53550/EEC.2025.v31i03s.057](https://doi.org/10.53550/EEC.2025.v31i03s.057)

---

## 🧪 Previous experience

**Data Science Research Intern, Tata Memorial Centre-ACTREC (2025):** benchmarked histopathology foundation models (UNI, UNI-2, CONCH, Virchow) against retrained CNNs for whole-slide image analysis on head and neck cancer tissue, working with histopathologists and clinicians.

---

*Always happy to chat about genomics, workflows or computational pathology. Feel free to reach out!*
