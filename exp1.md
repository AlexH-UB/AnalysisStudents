## JSB Lab Practical - Data evaluation

[**Overview**](./README.md) - [**Experiment 1**](./exp1.md) - [**Experiment 2**](./exp2.md) - [**Experiment 3**](./exp3.md) - [**Experiment 4**](./exp4.md)

---


### In case of any question:

* If the installation is not working or you have any other problems or suggestions - please email us

    1. Dr. Thomas Ebert (Ebert87@uni-bonn.de)
    2. Alexander Hoch (Ebert87@uni-bonn.de)

#### **Experiment 1: Cloning and Sequencing of CRISPR Expression Plasmids**
In this initial experiment, we generated CRISPR constructs by cloning synthetic DNA oligonucleotides into a U6 expression vector using Golden Gate cloning. Using [Ape](https://jorgensen.biology.utah.edu/wayned/ape/), we will review plasmid sequences to confirm the correct integration of gRNA sequences into the vectors, which will ensure that the gRNAs are ready for downstream applications in gene editing. Tn5 sequencing files.

---

1. Make sure your sequencing files are unzipped ([*Mac*](https://support.apple.com/de-de/guide/mac-help/mchlp2528/mac) or [*Windows*](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-f6dde0a7-0fec-8294-e1d3-703ed85e7ebc)).
2. Reconstruct your plasmid from the Tn5 snippets with the [*Tn5 Plasmid Assembler*](http://www.outknocker.org/tn5.htm) website.
     * As a seed you can choose 20 bases of a [resistance](./comps.fa) you think should be on the plasmid.
     * Load your unzipped fastq files.
     * The tool will output a text file to your download folder.
3. Investigate the sequence in your file:
     * Is the sequence long enough to be your plasmid?
     * What could be potential problems with the assembly of the plasmid?
4. Copy and Paste the sequence into a new Ape file.
5. Explore the DNA sequence a bit.
    * What features or regions are on the plasmid? ([*Hint*](./comps.fa))
    * Annotate found sequences from the features tab.
7. Where can you find your gRNA target site?
8. Blast your target site against the human genome ([*human Blast*](https://genome.ucsc.edu/cgi-bin/hgBlat)).

---

#### Further questions for the presentation:
1. What function does the knocked out gene have?
2. What phenotype could the cells with a knock out have?

---
