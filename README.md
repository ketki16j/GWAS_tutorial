# 🧬 GWAS & Post-GWAS Analysis Tutorial
 <img width="1536" height="1024" alt="ChatGPT Image Aug 24, 2025, 05_05_56 PM" src="https://github.com/user-attachments/assets/ac7d5689-eaa5-4c8e-9a7f-9a5c356c5d83" />


Welcome to a **hands-on tutorial** for Genome-Wide Association Studies (GWAS) and Post-GWAS analyses! This repository guides you from raw genotype data to advanced post-GWAS analyses using modern bioinformatics tools.  

---

## 📚 Table of Contents

1. [Pre-GWAS](#pre-gwas)  
    - [Data Formats](#data-formats)  
    - [Data Quality Control (QC)](#data-quality-control-qc)  
    - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)  
2. [GWAS](#gwas)  
    - [Association Tests](#association-tests)  
    - [Visualization](#visualization)  
3. [Post-GWAS](#post-gwas)  
    - [Variant Annotation](#variant-annotation)  
    - [Heritability Concepts](#heritability-concepts)  
    - [SNP-Heritability Estimation](#snp-heritability-estimation)  
    - [LD Score Regression](#ld-score-regression)  
    - [Gene / Gene-set Analysis](#gene--gene-set-analysis)  
    - [Fine-Mapping](#fine-mapping)  
    - [Polygenic Risk Scores (PRS)](#polygenic-risk-scores-prs)  
    - [Colocalization](#colocalization)  
    - [TWAS](#transcriptome-wide-association-studies-twas)  
4. [Topics & Concepts](#topics--concepts)  
5. [Tools & References](#tools--references)  
6. [License](#license)  

---

## 🔹 Pre-GWAS

### 🗂 Data Formats
Before analysis, understanding your data is essential. Learn standard formats for **sequence data, genotype data, and dosage data**.

### 🧹 Data Quality Control (QC)
Raw genotype data is often messy. Perform quality control with **PLINK**:
- Filter low-quality variants & individuals  
- Check missingness  
- Correct errors  

### 📊 Principal Component Analysis (PCA)
PCA helps identify population structure and stratification. Correcting for this ensures unbiased GWAS results.

---

## 🔹 GWAS

### ⚡ Association Tests
Run logistic regression for case-control traits using **PLINK** after QC.

### 🎨 Visualization
Visualize GWAS results using **gwaslab**:
- Manhattan plots 🏙  
- QQ plots 📈  
- Regional association plots 🗺  

---

## 🔹 Post-GWAS

### 📝 Variant Annotation
Use **ANNOVAR** or **VEP** to annotate variants and link them to genes and functional consequences.

### 🧠 Heritability Concepts
Understand **SNP-based heritability** and its role in complex traits.

### 📈 SNP-Heritability Estimation
Estimate variance explained by SNPs using **GCTA-GREML**.

### 🔗 LD Score Regression
Use **LDSC** for:
- Univariate heritability  
- Cross-trait genetic correlation  
- Partitioned heritability  

### 🧬 Gene / Gene-set Analysis
Run **MAGMA** for gene-level and pathway analyses.

### 🔎 Fine-Mapping
Identify causal variants using **SUSIE**.

### 🧩 Polygenic Risk Scores (PRS)
Compute PRS to estimate genetic predisposition.

### 🔄 Colocalization
Identify shared genetic signals between traits.

### 🧬 Transcriptome-Wide Association Studies (TWAS)
Link GWAS with gene expression to identify trait-associated genes.

---

## 💡 Topics & Concepts

- **Linkage Disequilibrium (LD)** – Variant correlations and implications  
- **Heritability** – Genetic contribution to traits  
- **Power Analysis** – Sample size & detection power  
- **Winner's Curse** – Effect size overestimation in GWAS  
- **Measures of Effect** – Odds ratios, beta coefficients, and interpretation  

---

## 🛠 Tools & References

| Tool | Purpose | Link |
|------|--------|------|
| PLINK | QC & association tests | [plink](https://www.cog-genomics.org/plink/) |
| GCTA | SNP-heritability | [gcta](https://cnsgenomics.com/software/gcta/) |
| LDSC | LD score regression | [ldsc](https://github.com/bulik/ldsc) |
| MAGMA | Gene / gene-set analysis | [magma](https://ctg.cncr.nl/software/magma) |
| ANNOVAR / VEP | Variant annotation | [annovar](https://annovar.openbioinformatics.org/) / [vep](https://www.ensembl.org/info/docs/tools/vep/index.html) |
| SUSIE | Fine-mapping | [susie](https://stephenslab.github.io/susie-paper/) |
| gwaslab | Visualization | [gwaslab](https://github.com/jialeong/gwaslab) |

---
