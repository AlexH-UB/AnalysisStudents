## JSB Lab Practical - Data evaluation

[**Overview**](./README.md) - [**Experiment 1**](./exp1.md) - [**Experiment 2**](./exp2.md) - [**Experiment 3**](./exp3.md) - [**Experiment 4**](./exp4.md)

---


### In case of any question:

* If the installation is not working or you have any other problems or suggestions - please email us

    1. Dr. Thomas Ebert (te@uni-bonn.de)
    2. Alexander Hoch (te@uni-bonn.de)

---

# ----> [LINK FOR THE DATA](https://uni-bonn.sciebo.de/s/ekYE938YcRw6syK) <----


### Overview

On the final day of the schedule, the focus shifts to the analysis of data gathered from the week’s laboratory work. 

---

##### **Experiment 1: Cloning and Sequencing of CRISPR Expression Plasmids**
In this initial experiment, we generated CRISPR constructs by cloning synthetic DNA oligonucleotides into a U6 expression vector using Golden Gate cloning. With [Ape](https://jorgensen.biology.utah.edu/wayned/ape/), we will generate the plasmid sequences to confirm the correct integration of gRNA sequences into the vectors, which will ensure that the gRNAs are ready for downstream applications in gene editing. For this application, look up your Tn5 sequencing barcodes you noted in the script and retrieve the corresponding sequencing files from the sciebo folder.

---

##### **Experiment 2: Gene Knockout in Human Cells and Validation by Deep Sequencing**
In the second experiment, we targeted an unknown gene for knockout in HEK 293T cells, using a combination of Cas9 and gRNA plasmids. After lysing the cells and amplifying the target regions by PCR, we performed a Deep Sequencing run. Today we will quantify the editing efficiency using [*Outknocker*](http://www.outknocker.org/). For this experiment look up your dual indexing barcodes you noted in the script for this experiment and retrieve the corresponding sequencing files from the sciebo folder.


---

##### **Experiment 3: Fluorescent Tagging of Endogenous Proteins and Verification by Microscopy**
In the third experiment, we used [*CRISPaint*](https://www.nature.com/articles/ncomms12338) (CRISPR-assisted insertion tagging) to insert a green fluorescent protein (GFP) tag into the human genome, enabling visualization of endogenous proteins within live cells. CRISPaint combines CRISPR-Cas9 with a donor DNA template to introduce specific tags at precise genomic locations, allowing for functional tagging without disrupting natural protein expression. This method allowed us to integrate GFP into our target gene, so we could verify and observe protein localization and dynamics in real-time under a fluorescence microscope, providing insights into the tagged protein’s cellular role. Today we will validate if the technique worked correctly and will create iamge collages. Please download your groups imaging files for all conditions from the sciebo folder. 

---

##### **Experiment 4: Observing Tagged Proteins in Live Cells Using Spinning-Disc Laser Microscopy**
In the final experiment, we used pre-made tagged cell lines to observe protein dynamics in live cells. Our goal is to monitor protein localization over time, particularly during mitosis. Today, we will evaluate time-lapse microscopy images, focusing on the spatial distribution and movement of tagged proteins within the cells. Using [Fiji](https://fiji.sc/), we will analyze cell division stages and protein localization changes, providing insights into protein function and behavior during mitosis. For this experiment we took an imaging time course, including Z-axis images. Please download the corresponding time course images from your group from the sciebo folder. 

---

#### **Conclusion**
In the end you will collaborate to compile your experimental data into a cohesive final presentation. You will organize your individual results from each experiment, including sequencing data and microscopy images, and collaboratively summarize the findings. 

---

---

### Preparations:

1. Install the latest version of [Fiji](https://fiji.sc/) and [Ape](https://jorgensen.biology.utah.edu/wayned/ape/) on your machine.
  * *ApE* is a versatile plasmid editing program used widely in genetic engineering and molecular cloning. It allows us to view, annotate, and modify plasmid sequences, which is crucial for designing DNA constructs and verifying cloning results. Its user-friendly interface and detailed feature set make it ideal for managing DNA sequences and planning experimental workflows efficiently.

  * *Fiji*, on the other hand, is an image processing package based on ImageJ, tailored for scientific image analysis. It includes a range of plugins for processing biological images, from microscopy to histological sections, and offers tools for quantification, segmentation, and visualization. This enables us to analyze experimental images precisely, enhancing the reliability of our findings and data interpretation.
2. Check if the programs can start up.
3. Retrieve all gel pictures from the lab computer.
