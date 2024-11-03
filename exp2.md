## JSB Lab Practical - Data evaluation - Experiment 2

[**Overview**](./README.md) - [**Experiment 1**](./exp1.md) - [**Experiment 2**](./exp2.md) - [**Experiment 3**](./exp3.md) - [**Experiment 4**](./exp4.md)

---


### In case of any question:

* If the installation is not working or you have any other problems or suggestions - please email us

    1. Dr. Thomas Ebert (te@uni-bonn.de)
    2. Alexander Hoch (te@uni-bonn.de)


##### **Experiment 2: Gene Knockout in Human Cells and Validation by Deep Sequencing**
In the second experiment, we targeted an unknown gene for knockout in HEK 293T cells, using a combination of Cas9 and gRNA plasmids. After lysing the cells and amplifying the target regions by PCR, we performed a Deep Sequencing run. Today we will quantify the editing efficiency using [*Outknocker*](http://www.outknocker.org/). For this experiment look up your dual indexing barcodes you noted in the script for this experiment and retrieve the corresponding sequencing files from the sciebo folder.

---

0. Perform data evaluation from Experiment 1.
1. Extract 200 bases upstream and downstream from the target site using the human blast interface.
2. Determine the PAM sequence in this context.
3. Open [*Outknocker*](http://www.outknocker.org/outknocker2.htm) and navigate to the "Analyze sequence data" tab.
4. Add your target site including the PAM.
5. Add your wildtype sequence.
6. Select your groups fastq files (unzipped).
7. Start the analysis.
9. Check your editing frequency and the must common mutations.
10. Repeat for the other target site.

---

#### Further questions for the presentation:
1. Is the editing frequency high enough for a follow up experiment?
2. What are the most common mutations?
3. Is the result realistic?

---
