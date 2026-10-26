### Yashraj Manan

Biotech student building toward a PhD in computational biology / bioinformatics / mathematical biology.
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
- [NGS Pipeline + Variant Calling](https://github.com/YashrajManan/NGS_PIPELINE_VARIANT_CALLING) — raw reads → variants on real NA12878 data, validated against the GIAB truth set
- [GWAS from Genotypes](https://github.com/YashrajManan/GWAS-from-Genotypes_HapMap_3_r3_1_dataset) — full GWAS pipeline + from-scratch reimplementation
- [Epitope Prediction/Design via AI-ML](https://github.com/YashrajManan/Immuno-Informatics-Epitope-Prediction-AI-ML) — fine-tuned ESM2 protein language model on real IEDB data
- [Red Queen Host-Parasite Coevolution](https://github.com/YashrajManan/red-queen-host-parasite-coevolution) — when coevolution does and doesn't oscillate
- [Multi-Omics Integration (classical + deep learning)](https://github.com/YashrajManan/Multiomics-Integration-Classical) — same real iHMP cohort, two integration strategies compared

Every project README documents real data sources, the actual methods used, and any real bugs hit along the
way — I'd rather show the debugging than hide it.

**By subdomain:**
- *Genomics & sequencing:* NGS variant calling, bulk/single-cell RNA-seq (Snakemake + Nextflow), 16S microbiome, GWAS, AMR genotype→phenotype prediction
- *Population & mathematical biology:* Red Queen coevolution, Fisher's Fundamental Theorem, Price equation & group selection, Muller's ratchet, neutral theory detectability, network-topology multistability, regulatory hysteresis
- *Structural & protein ML:* ESM1v/ESM2 protein language models, molecular docking + MD simulation, QSAR potency prediction
- *Systems biology:* genome-scale metabolic modeling (FBA), mechanistic identifiability
- *Single-cell & spatial:* CITE-seq multiomics, Xenium and Visium spatial transcriptomics
- *Clinical/translational:* TCGA-BRCA survival + histopathology fairness audit, GBSG→METABRIC external validation, FDA FAERS pharmacovigilance, biomedical NER

**Applied ML / tooling (separate from the comp-bio work above):**
[compbio-rag-api](https://github.com/YashrajManan/compbio-rag-api) — PubMed RAG API · [Langchain-Live-Pubmed-QA](https://github.com/YashrajManan/Langchain-Live-Pubmed-QA) — live literature QA

**Practice / exercises:** [Rosalind Bioinformatics Stronghold](https://github.com/YashrajManan/Rosalind-Bioinformatics-Stronghold) and [Armory](https://github.com/YashrajManan/Rosalind-Bioinformatics-Armory)
