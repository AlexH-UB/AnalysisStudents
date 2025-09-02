## JSB Lab Practical - Data evaluation - Experiment 4

[**Overview**](./README.md) - [**Experiment 1**](./exp1.md) - [**Experiment 2**](./exp2.md) - [**Experiment 3**](./exp3.md) - [**Experiment 4**](./exp4.md)

---


### In case of any question:

* If the installation is not working or you have any other problems or suggestions - please email us

    1. Dr. Thomas Ebert (te@uni-bonn.de)
    2. Alexander Hoch (te@uni-bonn.de)

##### **Experiment 4: Observing Tagged Proteins in Live Cells Using Spinning-Disc Laser Microscopy**
In this experiment, pre-made cell lines with tagged proteins are used for advanced live-cell imaging.  
The tags were introduced beforehand and selected with antibiotics so that most cells carry the same tagged locus.  
The goal is to visualize protein localization in real time during cell division using a *spinning-disc confocal microscope*.  
Temperature sensors and heating elements are used to keep the cells alive during imaging.  
Students should aim to identify dividing cells and observe how tagged proteins change their localization during mitosis.

---

1. Data organization
    * At the end of imaging, all recorded images will be available in one folder.  
    * The file sequence cycles through *conditions, channels, z-stacks, and time points*.  
    * Students need to carefully check the image order to understand how Fiji should import the dataset.

2. Open in Fiji
    * Launch Fiji (ImageJ) and open the image files.  
    * If Fiji does not automatically import them correctly, use *File → Import → Image Sequence*.  
    * Pay attention to the import dialog: specify the correct number of *channels, slices (z), and frames (t)*.  
    * This step ensures Fiji recognizes the data structure properly.

3. Convert to hyperstack
    * If the import results in a single long stack, convert it via *Image → Hyperstacks → Stack to Hyperstack*.  
    * Assign dimensions in the order:  
     * *Channels (C)*  
    * *Slices (Z)*  
    * *Frames (T)*  
    * This allows navigation through the dataset as a 4D hyperstack (x–y–z–t).

4. Channel assignment
    * Assign each channel a *meaningfully chosen pseudocolor* (e.g., GFP in green, DNA in blue, others as appropriate).  
    * Merge channels for visualization while keeping the option to view single channels.

5. Analysis workflow
    * Browse through *time frames* to identify dynamic processes.  
    * Navigate across *z-slices* to find the correct focal plane for dividing cells.  
    * Look for cells in different stages of mitosis and note how protein localization changes over time.

6. Figure preparation
* Select representative cells and prepare image panels or time series:  
    * Show consistent fields of view across time points.  
    * Use identical settings for brightness, contrast, and colors.  
    * Include a scale bar.
 
---
