## Reading list to get you started


Various papers on sequencing technologies, analysis methods, cancer, genome
structure, transcription, splicing, and a bit of evolution, among other things.
This is in no way a comprehensive collection, just starting points for different
topics.

### Sequencing technologies

- [SequencENG](http://education.knoweng.org/sequenceng/index.html), a nice
  resource on NGS techniques, and the [preprint](https://doi.org/10.1101/319079)
  describing it.
- [Comparative Analysis of Single-Cell RNA Sequencing
  Methods](https://doi.org/10.1016/j.molcel.2017.01.023) discussing cost,
  accuracy, sensitivity, precision, etc of 6 different methods.
- Some of the cutting edge stuff: single-cell isoform RNA sequencing with
  [ScISOr-Seq](https://doi.org/10.1101/364950) and the
  [Mandalorion](https://doi.org/10.1038/ncomms16027) pipeline.
- [Single-Cell Multi-omics](https://doi.org/10.1016/j.tig.2018.06.001),
  complementing single-cell RNA-seq with other methods.

### Tools and methods for analysis

- [Aligning sequence reads, clone sequences and assembly contigs with
  BWA-MEM](https://arxiv.org/abs/1303.3997). A widely used tool for mapping
  sequence reads.
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
- A [very simple method](https://doi.org/10.2202/1544-6115.1071) to classify
  gene expression profiles, a cool application on [transcription factor pairs
  and cell types](https://doi.org/10.1038/nmeth.2445) and our implementation to
  [detect changes in the relative abundance of alternative transcripts and
  define cancer-specific splicing
  signatures](https://doi.org/10.1093/nar/gku1392).
- [Bioconductor: open software development for computational biology and
  bioinformatics](https://doi.org/10.1186/gb-2004-5-10-r80).
- [Mean-Variance QTL Mapping on a Background of Variance
  Heterogeneity](https://doi.org/10.1101/276980). Looking for genetic loci, that
  influence the variance of a phenotype.
- [Differential variability analysis for pathway level expression
  data](https://doi.org/10.4137/CIN.S14066). Looking for actual deregulation
  instead of changes in mean values.

### Cancer, transcription, splicing and chromatin structure

- [The Hallmarks of Cancer](https://doi.org/10.1016/S0092-8674%2800%2981683-9)
  and [Hallmarks of Cancer: The Next
  Generation](https://doi.org/10.1016/j.cell.2011.02.013). Seminal papers on the
  general principles underlying cancer.
- [TCGA Research Network
  publications](https://cancergenome.nih.gov/publications) on 31 different tumor
  types.
- [RNA splicing factor mutations in
  myelodysplasia](https://doi.org/10.1182/blood-2017-02-692715) with lots of
  open questions.
- [Building Robust Transcriptomes with Master Splicing
  Factors](https://doi.org/10.1016/j.cell.2014.09.054). Splicing regulatory
  networks in various biological processes.
- [Control of Stochasticity in Eukaryotic Gene
  Expression](https://doi.org/10.1126/science.1098641). Cis- and trans-acting
  mutations that alter the noise of gene expression.
- [Natural Variation in Gene Expression Modulates the Severity of Mutant
  Phenotypes](https://doi.org/10.1016/j.cell.2015.06.037). Natural variation in
  gene expression influences the manifestation of mutant phenotypes.
- [Domain organization of human chromosomes revealed by mapping of nuclear
  lamina interactions](https://doi.org/10.1038/nature06947). A comprehensive map
  of LADs and large-scale structure in the human genome.

### Complexity, evolution and other stuff

- [What is a complex system?](http://doi.org/10.1007/s13194-012-0056-8) And how
  to characterize it, not just in biology?
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
  Function](http://doi.org/10.1093/gbe/evv021). Functional DNA, junk DNA,
  garbage DNA, zombie DNA and all kinds of other DNA.
