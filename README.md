### Yashraj Manan

Biotech student building toward a PhD in Computational Biology / Bioinformatics / AI in Biology.
I work across wet-lab-adjacent data (sequencing, phylogenetics, population genetics, protein structure) and
the computational methods used to analyze it — usually built twice, in two independent tools, to check the
result rather than trust one pipeline's output. ~50 repos below span sequencing pipelines, population-genetics
theory, systems biology, protein language models, network medicine, and applied ML tooling.

**MSc Dissertation — Computational and Experimental Approaches to Study HIV-1 Subtypes**
M.Sc. Biotechnology, South Asian University, New Delhi (CGPA 8.76/10), in Prof. Ritu Gaur's virology lab.

Three parts (all independent of each other): 

(1) HIV-1 subtype classification from the *pol* gene (https://github.com/YashrajManan/Machine_Learning_Models_for_HIV-1_Subtype_Classification_from_the_Pol_Gene) — alignment-free deep learning vs. classical ML comparison (Manuscript submitted)

(2) HivGagFormer, a compact temporal transformer [private Repo] (~0.24M params) combining frozen ESM-2 embeddings, rolling site-frequency priors, and continuous-time encoding to predict HIV-1 Gag mutations (Manuscript in preparation) 

(3) wet-lab validation of LDHA protein expression via western blotting, grounding the computational predictions in bench data.

**Start here — the most representative work:**
- [Phylodynamics & Pathogen Genomic Surveillance](https://github.com/YashrajManan/Phylodynamics-Pathogen_surveillance) — time-scaled SARS-CoV-2 phylogeny, molecular clock, skyline Ne(t)
- [Hospital Risk & Revenue Intelligence Platform](https://github.com/YashrajManan/hospital-risk-revenue-intelligence-platform) — two ML models deployed live via API; SQL analytics through drift-monitored MLOps, end to end
- [Single-Cell Multiomics (CITE-seq)](https://github.com/YashrajManan/Single_Cell_Multi_Omics) — joint RNA + surface protein modeling with totalVI
- [Epidemic Dynamics Simulation](https://github.com/YashrajManan/Epidemic_Dynamics_Simulation) — SEIR ODE fit cross-validated against an independent agent-based model on real COVID-19 case data
- [Molecular Docking & MD Simulations](https://github.com/YashrajManan/Molecular_Docking-and-MD_simulations) — structure-based virtual screening + GPU molecular dynamics across 4 real drug-discovery targets
- [Epitope Prediction/Design via AI-ML](https://github.com/YashrajManan/Immuno-Informatics-Epitope-Prediction-AI-ML) — fine-tuned ESM2 protein language model on real IEDB data

Every project README documents real data sources, the actual methods used, and any real bugs hit along the
way — I'd rather show the debugging than hide it.

**By subdomain:**

**By subdomain — all repos:**

*Genomics & sequencing* — [NGS Pipeline + Variant Calling](https://github.com/YashrajManan/NGS_PIPELINE_VARIANT_CALLING) · [ScRNA-Seq Pipeline (Snakemake + Nextflow)](https://github.com/YashrajManan/ScRNA-Seq-Pipeline-Workflow) · [Bulk RNA-seq Pipeline (Snakemake + Nextflow)](https://github.com/YashrajManan/Bulk_RNA_Seq_Pipeline_Workflow_Snakemake_Nextflow) · [Bulk RNA-seq Differential Expression](https://github.com/YashrajManan/Bulk_RNA_Seq_Analysis) · [16S Microbiome Diversity](https://github.com/YashrajManan/16S-Microbiome-Diversity-dada2-QIIME2) · [GWAS from Genotypes](https://github.com/YashrajManan/GWAS-from-Genotypes_HapMap_3_r3_1_dataset) · [Drug-Resistance Prediction from Genotype](https://github.com/YashrajManan/Drug-Resistance-Prediction-from-Genotype) · [Genomic Data Exploration](https://github.com/YashrajManan/genomic_eda) · [Pairwise Alignment from Scratch](https://github.com/YashrajManan/pairwise-alignment-from-scratch) · [Sequence Analysis Toolkit](https://github.com/YashrajManan/sequence-analysis-toolkit)

*Phylogenetics & molecular evolution* — [Phylodynamics & Pathogen Genomic Surveillance](https://github.com/YashrajManan/Phylodynamics-Pathogen_surveillance) · [Dengue Phylogenetics & Selection](https://github.com/YashrajManan/dengue-phylogenetics-selection)

*Population & mathematical biology* — [Red Queen Host-Parasite Coevolution](https://github.com/YashrajManan/red-queen-host-parasite-coevolution) · [Fisher's Fundamental Theorem](https://github.com/YashrajManan/Fishers-Fundamental-Theorem-Natural-Selection) · [Price Equation & Group Selection](https://github.com/YashrajManan/Price-Equation-Multilevel-Selection) · [Muller's Ratchet & Evolutionary Rescue](https://github.com/YashrajManan/Evolutionary-Rescue-by-Recombination-Mullers-Ratchet-Sex-Evolution) · [Neutral Theory Detectability](https://github.com/YashrajManan/neutral-theory-selection-detectability) · [Network-Topology Multistability](https://github.com/YashrajManan/Network-Topology-Multistability-GRN) · [Regulatory Hysteresis & Path Dependence](https://github.com/YashrajManan/Hysteresis-Path-Dependence-Regulatory-Switches) · [Darwinian Selection Foundations](https://github.com/YashrajManan/Darwinian-Selection-Foundations) · [Darwin in Real Data](https://github.com/YashrajManan/Darwin-theory-on-real-data-classical-studies) · [Epidemic Dynamics Simulation](https://github.com/YashrajManan/Epidemic_Dynamics_Simulation)

*Structural & protein ML* — [ESM-1v Variant-Effect Prediction](https://github.com/YashrajManan/ESM1v-Protein-Variant-Effect-Prediction) · [ESM-2 Protein Function Prediction](https://github.com/YashrajManan/ESM2-Protein-Function-Prediction-DeepLoc) · [Molecular Docking + MD Simulations](https://github.com/YashrajManan/Molecular_Docking-and-MD_simulations) · [QSAR Potency Prediction](https://github.com/YashrajManan/QSAR-Potency-Prediction) · [Epitope Prediction/Design via AI-ML](https://github.com/YashrajManan/Immuno-Informatics-Epitope-Prediction-AI-ML) · [SARS-CoV-2 Spike Epitope Prediction](https://github.com/YashrajManan/SARS-CoV-2-Spike-MHC-I-Epitope-Prediction)

*Systems biology* — [Genome-Scale Metabolic Modeling (FBA)](https://github.com/YashrajManan/Genome-Scale-Metabolic-Modeling-FBA) · [Mechanistic Identifiability in Gene Autoregulation](https://github.com/YashrajManan/Mechanistic-Identifiability-Gene-Autoregulation)

*Single-cell & spatial* — [Single-Cell Multiomics (CITE-seq)](https://github.com/YashrajManan/Single_Cell_Multi_Omics) · [Single-Cell Spatial Transcriptomics (Xenium)](https://github.com/YashrajManan/Single_Cell_Spatial_Transcriptomics_Xenium) · [Single-Cell RNA-seq Analysis](https://github.com/YashrajManan/Single_Cell_RNA_Seq_Analysis) · [Visium Spatial Transcriptomics](https://github.com/YashrajManan/Visium-Breast-Cancer-Spatial-Transcriptomics) · [Multi-Omics Integration, Classical](https://github.com/YashrajManan/Multiomics-Integration-Classical) · [Multi-Omics Integration, Deep Learning](https://github.com/YashrajManan/Multiomics-Integration-DeepLearning)

*Clinical/translational* — [TCGA-BRCA Histopathology Fairness Audit](https://github.com/YashrajManan/TCGA-BRCA-Histopathology-Performance-Disparity-Audit) · [Cancer Survival Prediction](https://github.com/YashrajManan/Cancer_Survival_Prediction) · [Multi-Cohort Survival, GBSG→METABRIC](https://github.com/YashrajManan/Breast-Cancer-Survival-GBSG-METABRIC-External-Validation) · [FDA Adverse Drug Event Analysis](https://github.com/YashrajManan/Adverse-Drug-Effect-Detection-) · [Biomedical NER (BC5CDR)](https://github.com/YashrajManan/BC5CDR-Biomedical-NER-PubMedBERT) · [Biomedical Data Warehouse (TCGA-BRCA)](https://github.com/YashrajManan/Biomedical-Data-Warehouse-TCGA-BRCA) · [HIV-1 Subtype Classification](https://github.com/YashrajManan/Machine_Learning_Models_for_HIV-1_Subtype_Classification_from_the_Pol_Gene) · [Hospital Risk & Revenue Intelligence Platform](https://github.com/YashrajManan/hospital-risk-revenue-intelligence-platform) · [PPI Network Drug Repurposing](https://github.com/YashrajManan/PPI-Network-Drug-Repurposing)

**Applied ML / tooling (separate from the comp-bio work above):** [compbio-rag-api](https://github.com/YashrajManan/compbio-rag-api) — PubMed RAG API · [Langchain-Live-Pubmed-QA](https://github.com/YashrajManan/Langchain-Live-Pubmed-QA) — live literature QA

**Practice / exercises:** [Rosalind Bioinformatics Stronghold](https://github.com/YashrajManan/Rosalind-Bioinformatics-Stronghold) · [Rosalind Bioinformatics Armory](https://github.com/YashrajManan/Rosalind-Bioinformatics-Armory)
