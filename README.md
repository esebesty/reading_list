## Reading list to get you started

Various papers on sequencing technologies, analysis methods, cancer, genome
structure, transcription, splicing, and a bit of evolution, among other things.
This is in no way a comprehensive collection, just starting points for different
topics.

### Sequencing technologies (mainly RNA)

- [Next-generation DNA sequencing](https://doi.org/10.1038/nbt1486), introducing
  the basic technology used in different protocols.
- [Coming of age: ten years of next-generation sequencing
  technologies](https://doi.org/10.1038/nrg.2016.49), review on various short
  and long-read sequencing technologies.
- [RNA-Seq: a revolutionary tool for
  transcriptomics](https://doi.org/10.1038/nrg2484), introducing RNA-seq.
- [RNA sequencing: the teenage
  years](https://doi.org/10.1038/s41576-019-0150-2), a very recent review of
  RNA-seq technology and the various improvements on the experimental protocols,
  analysis methods, besides describing novel sequencing technologies used beyond
  the analysis of gene expression.
- [Comparative Analysis of Single-Cell RNA Sequencing
  Methods](https://doi.org/10.1016/j.molcel.2017.01.023) discussing cost,
  accuracy, sensitivity, precision, etc of 6 different methods.
- [Translating RNA sequencing into clinical diagnostics: opportunities and
  challenges](https://doi.org/10.1038/nrg.2016.10): current and potential future
  applications of RNA-seq.
- [Diagnosis of fusion genes using targeted RNA
  sequencing](https://doi.org/10.1038/s41467-019-09374-9): panel RNA-seq for
  clinical diagnostics.
- [Highly parallel direct RNA sequencing on an array of
  nanopores](https://doi.org/10.1038/nmeth.4577): Oxford Nanopore for direct RNA
  sequencing.

### Tools and methods for analysis (again, mainly RNA-seq)

- [Aligning sequence reads, clone sequences and assembly contigs with
  BWA-MEM](https://arxiv.org/abs/1303.3997). A widely used tool for mapping
  sequence reads.
- [Short Read Mapping: An Algorithmic
  Tour](https://doi.org/10.1109/JPROC.2015.2455551): various methods for
  short-read mapping.
- [GATK for processing and analysing DNA sequencing
  data](https://doi.org/10.1101/gr.107524.110). Data preprocessing, SNP and
  INDEL discovery.
- [STAR: ultrafast universal RNA-seq
  aligner](https://doi.org/10.1093/bioinformatics/bts635). For mapping RNA-seq
  reads, considering the additional problem of non-contiguous reads spanning
  exon-exon borders.
- [Near-optimal probabilistic RNA-seq
  quantification](https://doi.org/10.1038/nbt.3519). A novel tool to estimate
  transcript level expression from RNA-seq, without the need to do mapping to a
  reference genome first.
- [voom: precision weights unlock linear model analysis tools for RNA-seq read
  counts](https://doi.org/10.1186/gb-2014-15-2-r29). limma-voom is a robust,
  widely used package for RNA-seq differential expression. The limma package
  also contains several methods for gene set enrichment analysis, differential
  exon usage, normalization and visualization of intermediate and final results.
- [Tackling the widespread and critical impact of batch effects in
  high-throughput data](https://doi.org/10.1038/nrg2825). What is the batch
  effect, and why does it matter?
- [A survey of best practices for RNA-seq data
  analysis](https://doi.org/10.1186/s13059-016-0881-8). An overview of analysis
  steps for RNA-seq data.
- [How many biological replicates are needed in an RNA-seq experiment and which
  differential expression tool should you
  use?](https://doi.org/10.1261/rna.053959.115) The more replicates, the
  better!
- [Bioconductor: open software development for computational biology and
  bioinformatics](https://doi.org/10.1186/gb-2004-5-10-r80).
- [RNA Sequencing Data: Hitchhiker’s Guide to Expression
  Analysis](https://doi.org/10.1146/annurev-biodatasci-072018-021255): one of
  the best current review on RNA-seq analysis.
- [Analytical Validation of Clinical Whole-Genome and Transcriptome Sequencing
  of Patient-Derived Tumors for Reporting Targetable Variants in
  Cancer](https://doi.org/10.1016/j.jmoldx.2018.06.007): Guideline on the analysis of
  WGS and transcriptome sequencing for clinical application, from sequencing to
  variant interpretation.
- [A beginners guide to SNP calling from high-throughput DNA-sequencing
  data](https://doi.org/0.1007/s00439-012-1213-z): as the title says.
- [A unified analytic framework to discover and genotype variation among
  multiple samples simultaneously](https://doi.org/10.1038/ng.806): BWA, MAQ,
  GATK and friends.

### Cancer genomes and transcriptomes

- [The Hallmarks of Cancer](https://doi.org/10.1016/S0092-8674%2800%2981683-9)
  and [Hallmarks of Cancer: The Next
  Generation](https://doi.org/10.1016/j.cell.2011.02.013). Seminal papers on the
  general principles underlying cancer.
- [RNA splicing factor mutations in
  myelodysplasia](https://doi.org/10.1182/blood-2017-02-692715) with lots of
  open questions.
- [RNA splicing factors as oncoproteins and tumor
  suppressors](https://doi.org/10.1038/nrc.2016.51): mutations in the splicing
  machinery and other RNA binding proteins.
- [The genetics of myelodysplastic syndrome: from clonal haematopoiesis to
  secondary leukaemia](https://doi.org/10.1038/nrc.2016.112): the varius driver
  mutations from CHIP to sAML, including splicng factors, chromatin modifiers
  and other genes.
- [RNA modifications regulating cell fate in
  cancer](https://doi.org/10.1038/s41556-019-0319-0): role of the more than 170
  RNA modifications in cancer.
- [High burden and pervasive positive selection of somatic mutations in normal
  human skin](https://doi.org/10.1126/science.aaa6806): widespread oncogenic
  mutations in normal human skin cells.
- [Hypermutation in human cancer genomes: footprints and
  mechanisms](https://doi.org/10.1038/nrc3816): mutator phenotype in cancer.

### Transcription, splicing and expression variance (in disease)

- [Building Robust Transcriptomes with Master Splicing
  Factors](https://doi.org/10.1016/j.cell.2014.09.054). Splicing regulatory
  networks in various biological processes.
- [Control of Stochasticity in Eukaryotic Gene
  Expression](https://doi.org/10.1126/science.1098641). Cis- and trans-acting
  mutations that alter the noise of gene expression.
- [Natural Variation in Gene Expression Modulates the Severity of Mutant
  Phenotypes](https://doi.org/10.1016/j.cell.2015.06.037). Natural variation in
  gene expression influences the manifestation of mutant phenotypes.
- [Interplay between gene expression noise and regulatory network
  architecture](https://doi.org/10.1016/j.tig.2012.01.006). Intro on how gene
  regulatory networks are influenced by expression variance, and why it might be
  interesting.
- [Splicing heterogeneity: separating signal from
  noise](https://doi.org/10.1186/s13059-018-1467-4): sources of splicing
  variance.
- [Challenges in measuring and understanding biological
  noise](https://doi.org/10.1038/s41576-019-0130-6): current state of research
  on the sources and effects of biological noise.
- [Higher gene expression variability in the more aggressive subtype of chronic
  lymphocytic leukemia](https://doi.org/10.1186/s13073-014-0125-z): correlation
  between gene expression variance and cancer progression.
- [Non-genetic heterogeneity — a mutation-independent driving force for the
  somatic evolution of tumours](https://doi.org/10.1038/nrg2556): how
  non-genetic expression variance might contribute to the development of cancer?
- [Predicting mutation outcome from early stochastic variation in genetic
  interaction partners](https://doi.org/:10.1038/nature10665).
- [Rare cell variability and drug-induced reprogramming as a mode of cancer drug
  resistance](https://doi.org/10.1038/nature22794): excellent example on how
  expression variability influences drug resistance in a cancer cell line.

### Complexity, evolution and other stuff

- [What is a complex system?](https://doi.org/10.1007/s13194-012-0056-8) And how
  to characterize it, not just in biology?
- [Is the cell really a machine?](https://doi.org/10.1016/j.jtbi.2019.06.002)
  Short answer: no (but read the paper anyway).
- [Sequences and consequences](https://doi.org/10.1098/rstb.2009.0221). Some
  justified criticism of the current 'low input, high throughput, no output'
  biology.
- [The future of data analysis](https://www.jstor.org/stable/2237638). Old, but
  still relevant.
- [Can a biologist fix a
  radio?](https://doi.org/10.1016/S1535-6108%2802%2900133-2) or [Could a
  Neuroscientist Understand a
  Microprocessor?](https://doi.org/10.1371/journal.pcbi.1005268)
- [An Evolutionary Classification of Genomic
  Function](https://doi.org/10.1093/gbe/evv021). Functional DNA, junk DNA,
  garbage DNA, zombie DNA and all kinds of other DNA.
- [An upper limit on the functional fraction of the human
  genome](https://doi.org/10.1093/gbe/evx121): can the whole human genome be
  functional?
- [Emerging and evolving concepts in gene
  essentiality](https://doi.org/10.1038/nrg.2017.74): essential genes or
  essential functions?
