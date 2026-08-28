# ASVA-CGR

*Algorithms for Structural Variation Analysis in Challenging Genomic Regions*

Funded under the "HORIZON.4.1 - Widening participation and spreading excellence" programme.

<ins>Grant agreement ID:</ins> 101180581

<ins>Funding scheme:</ins> HORIZON TMA MSCA Postdoctoral Fellowships - European Fellowships.

[https://doi.org/10.3030/101180581](https://doi.org/10.3030/101180581)

## Outcomes

The project aimed to design algorithms and develop software tools to facilitate and improve genomic analyses of structural variations from sequencing datasets. It focused on two main scientific themes: structural variations and pangenomics.

### Structural Variations
Accurate characterization of structural variations (genomic rearrangements affecting large DNA segments) plays a key role in unveiling their effects on human health, including their links with genetic diseases and tumors. Accordingly, our work pursued two complementary objectives: (i) an investigation of current best practices, along with their limitations, for benchmarking SV callers and (ii) the development of a new software tool for the discovery of somatic structural variations.

### Pangenomics
In parallel, we investigated how pangenomics can help us achieve our goal of characterizing structural variations. Since pangenomics is an emerging research field, we first established the algorithmic foundation and focused on designing data structures and algorithms that enable the practical use of pangenome graphs within existing genomic analysis pipelines. These developments will facilitate the analyses and interpretation of structural variations.

### Additional results

Over the course of the project, we also collaborated with other researchers on detecting differences between sequencing datasets, clustering third-generation transcriptomic datasets, and indexing massive bacterial databases.


## Publications

1. <i class="ai ai-open-access ai-2x"/>  D. Andrukhovskyi, M. Madzin, L. Denti, T. Vinař, B. Brejová\\
**Efficient Algorithms for Pangenome Personalization**\\
*WABI Proceedings (2026)* <a class="ai ai-doi ai-lg" href="https://doi.org/10.4230/LIPIcs.WABI.2026.8" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-open-access ai-2x"/> A. Petescia, L. Denti, A. Gafurov, V. Hodorova, J. Nosek, B. Brejova, T. Vinar\\
**Alignment-free Detection of Differences Between Sequencing Data Sets**\\
*iScience (2025)*  <a class="ai ai-doi ai-lg" href="https://doi.org/10.1016/j.isci.2025.113828" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-open-access ai-2x"/> D. Cozzi, B. Riccardi, L. Denti, S. Ciccolella, K. Sadakane, P. Bonizzoni\\
**Pangenome Graph Indexing via the Multidollar-BWT**\\
*SEA Proceedings (2025)* <a class="ai ai-doi ai-lg" href="https://doi.org/10.4230/LIPIcs.SEA.2025.13" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-open-access ai-2x"/> L. Denti, Y. Shibuya\\
**Weighted de novo clustering of third-generation transcriptomic datasets**\\
*ITAT Proceedings (2025)* <a class="ai ai-ceur ai-lg" href="https://ceur-ws.org/Vol-4092/paper24.pdf" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-biorxiv ai-2x"/> L. Denti, P. Bonizzoni, B. Brejova, R. Chikhi, T. Krannich, T. Vinar, F. Hormozdiari\\
**Pangenome graph augmentation from unassembled long reads**\\
*bioRxiv (2025)* <a class="ai ai-doi ai-lg" href="https://doi.org/10.1101/2025.02.07.637057" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-biorxiv ai-2x"/> L. Denti, T. Krannich, T. Vinar, R. Chikhi, P. Bonizzoni, B. Brejova, F. Hormozdiari\\
**Anyone can be the best: Impact of diverse methodologies on the evaluation of structural variant callers**\\
*bioRxiv (2025)* <a class="ai ai-doi ai-lg" href="https://doi.org/10.1101/2025.08.28.672546" style="text-decoration:none; color:inherit;"/>

1. <i class="ai ai-open-access ai-2x"/>  S. Ciccolella, D. Cozzi, G. Della Vedova, S. Kuria, P. Bonizzoni, L. Denti\\
**Differential quantification of alternative splicing events on spliced pangenome graphs**\\
*PLOS Computational Biology (2024)* <a class="ai ai-doi ai-lg" href="https://doi.org/10.1371/journal.pcbi.1012665" style="text-decoration:none; color:inherit;"/>

## Software

* [palss](https://github.com/ldenti/palss), a tool for augmenting pangenome graph from unassembled long reads (WIP)
* [svbench-fw](https://github.com/ldenti/svbench-fw), a modular and extensible framework to evaluate SV callers
* [pantas](https://github.com/AlgoLab/pantas), a tool for quantifying AS events from spliced pangenome graphs
* [kdiff](https://github.com/fmfi-compbio/kdiff), a tool for the alignment-free detection of differences between sequencing data sets
* [SolidClust](https://github.com/ldenti/solidclust), a method for the de novo clustering of third-generation transcriptomic datasets
* [GIndex](https://github.com/dlcgold/graph_index), a multidollar-BWT based graph index

## Slides and Posters

Invited talks:
* **Future impact of ALPACA / Open problems on pangenomes** <a class="fa fa-file-pdf-o" href="/pdfs/finalalpaca2024.pdf" style="text-decoration:none; color:inherit;"></a>\\
*Final workshop of the ALPACA ITN Project (St. Malo, France - December 9-11, 2024)*

* **Pangenome graph augmentation from unassembled long reads** <a class="fa fa-file-pdf-o" href="/pdfs/palss-biohack2025.pdf" style="text-decoration:none; color:inherit;"></a>\\
*Pangenome Bio Hacking 2025 Workshop (online - January 22-24, 2025)*

* **Foundations of Sequence Bioinformatics** <a class="fa fa-file-pdf-o" href="/pdfs/hpp2026.pdf" style="text-decoration:none; color:inherit;"></a>\\
*The Human Pangenome Project - For an inclusive genomics (Milano, Italy - July 9, 2026)*

Talks:

* **Pangenome graph augmentation from unassembled long reads**\\
*RECOMBSEQ2025. Seoul, South Korea* <a class="fa fa-file-pdf-o" href="/pdfs/RECOMBSEQ25.pdf" style="text-decoration:none; color:inherit;"></a>\\
*ITAT25. Telgart, Slovakia* <a class="fa fa-file-pdf-o" href="/pdfs/ITAT25.pdf" style="text-decoration:none; color:inherit;"></a>

Posters:
* **Challenges and Pitfalls in the Evaluation of Structural Variants Callers** <a class="fa fa-file-pdf-o" href="/pdfs/svbench_recomb2026.pdf" style="text-decoration:none; color:inherit;"></a> (lightning talk: <a class="fa fa-file-pdf-o" href="/pdfs/svbench_lt_recombseq2026.pdf" style="text-decoration:none; color:inherit;"></a>)\\
*RECOMBSEQ2026 and RECOMB2026*

* **Pangenome-based characterization of novel genetic variants** <a class="fa fa-file-pdf-o" href="/pdfs/matfyz2025.pdf" style="text-decoration:none; color:inherit;"></a>\\
*MatFyz Connections 2025*

* **Alignment-free de novo structural variations from pangenomes** <a class="fa fa-file-pdf-o" href="/pdfs/matfyz2024.pdf" style="text-decoration:none; color:inherit;"></a>\\
*MatFyz Connections 2024*
