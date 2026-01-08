# Molecular_Systems_Biology
## Introduction to Metabolomics
- What is metabolomics? What is its potential and what are the limitations?\
    The complete collection of small molecule metabolites in a cell, organ, tissue or organism at a given time.\
    It can answer the physiology and phenotype of a tissue or organism, and the pathway is well understood. But with a great difficulty of measurements, and easily be influenced by physiological or environmental factors, its more time sensitive.

- How do you acquire data about small molecule? What type of data for LC-MS workflow? How can we go from spectra to metabolite identification?\
    GC/MS, LC/MS, NMR\
    We can get feature(unique combination of m/z), retention time(RT), abundance information.\
    Matching with the database

- What can I use targeted metabolomics for? and untargeted metabolomics? What are limitations and advantages of each approach?\
    We can use targeted metabolomics to get the levels of specific metabolites in a sample.\
    We can use the untargeted metabolomics to know the global metabolic profile of a sample.\
![1](./1.PNG)

## RNA-Seq
- Describe the key steps in an RNA sequencing experiment\
    Extract RNA\
    Reverse transcribe RNA into a collection(library) of short complementary DNA(cDNA) fragments\
    Amplify cDNA fragments and add adaptors by PCR\
    Obtain sequences from each cDNA with sequencing by synthesis(Illumina)


- Evaluate factors that could affect the output of an RNA-seq experiment\
    RNA-Seq experiment design: library preparation & Sequencing protocol\
    Different RNA-Seq protocols produce different tyoes of information about the RNA population. Trade-off between sequencing length(bases per read) and sequencing depth(total bases sequences)

- Argue the need for normalization of RNA-Seq data\
    There're many factors affect a gene's read count, e.g.:total number of reads in the library(sequencing depth), gene/transcript length, GC content(affects amplification), and rRNA depletion, and **Biological factors**(what we care about!)

- Explain the features and the hypothesis behind normalization methods\
    - Total count normalization\
    Corrects only effects due to differences in library size. Divide by the total number of mapped reads in each sample.

    - FPKM,RPKM\
    Corrects against differencs in library size and transcript length. Reads per kilobase per million mapped reads, useful for qualitative comparisons between gens.

    - EdgeR/DESeq\
    Each assume that most genes are NOT differentially expressed and can corrrect for most effects.

- Explain the differences between short-read and long-read methods\
  
## GO Ontology Enrichemnt Analysis
- Explain Gene Ontology, its main characteristics and its sub-ontologies\
  Gene Ontology(GO) is a controlled vocabulary to annotate the functions of genes. Go-term are species-neutral, are applicable to prokaryotes and eukaryotes, single and multicellular organisms.\
  Go has three hierarchical structures, Biological Process(BP), Molecular Function(MF), Cellular Component(CC).

- Explain the hierarchical structure of the go\
  Go has three hierarchical structures, Biological Process(BP), Molecular Function(MF), Cellular Component(CC).

- Explain what enrichment analysis is\


- Identify which elements in an experiment are needed to compute the p-value in a hypergeometric test\
s

- Interpret the output of an enrichment analysis\












































