---
permalink: /
title: "Hello, I'm Michael. Welcome to my Portfolio!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a highly motivated Bioinformatics Ph.D. Candidate passionate about machine learning applications to biomedicine. My dissertation focuses on machine learning applications in multi-modal biological network modeling for drug target discovery. With over 5 years of bioinformatics research, I have developed a solid foundation in machine learning, statistics, genomics and molecular biology, multiomics integration, and software development. I have also worked with many bioinformatics databases and genomic repositories including NCBI, Encode, Ensembl, MsigDB, TCGA, GTEx, and Allen Brain Atlas. More recently, I have grown a deep interest in single cell foundation models to better understand cell identity and language.

# Research Experience

**Cell Attention is All You Need**: Currently I am exploring graph attention networks and single cell foundation models like Geneformer and CellPLM to learn cell communication from single cell and spatial omics data.

**Machine learning**: I developed a machine learning model for scRNAseq and spatial transcriptomics data that uses gradient boosting to infer gene regulation in cells. My method can model disease gene mechanisms and shows up to 0.5 AUROC improvement in predicting affected genes in gene knockout experiments. This method is published in *iScience* [[link](https://www.cell.com/iscience/fulltext/S2589-0042(23)01201-4?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2589004223012014%3Fshowall%3Dtrue)].

**Database Management**: I have also applied this method to over 1300 public scRNAseq datasets and created a the first database of cell type gene regulatory networks (GRNs) across human and mouse tissues. I built this using a LAMP stack and Neo4j graph database. Feel free to explore any gene regulatory network [here](https://mergeomics.research.idre.ucla.edu/scGRNdb/).

**Precision Medicine**: I have integrated gene regulatory network modeling with genetic data to genetic factors of traumatic brain injury recovery, allowing for tailored symptom prediction for brain injury patients. 

**Drug Target Discovery**: I have also applied network modeling to drug screen databases to identify drug-targettable genes for cancer immunotherapy resistance. I collaborated with cancer biologists to validate these findings in lung cancer cohorts. These findings are submitted to *Nature Communications* and currently in bioRxiv [[link](https://www.biorxiv.org/content/10.1101/2024.11.22.624939v1)].

**Representation Learning**  I applied nonnegative matrix factorization on 24 cancer types in The Cancer Genome Atlas (TCGA) to identify latent epigenetic factors that associate with patient survival. I also trained a neural network to stratify patients into high and low survival groups. These findings are published in *Communications Biology* [(link)](https://www.nature.com/articles/s42003-023-05459-w) and featured by the *National Cancer Institute* [[link](https://datascience.cancer.gov/news-events/news/epigenetics-and-machine-learning-help-make-cancer-predictions)].

## Personal AI Projects

I am creating a multi-agent RAG/GraphRAG system that incorporates biomedical fine-tuned LLMs with my gene regulatory network Neo4j knowledgebase to assist with gene function queries.
