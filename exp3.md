## JSB Lab Practical - Data evaluation - Experiment 3

[**Overview**](./README.md) - [**Experiment 1**](./exp1.md) - [**Experiment 2**](./exp2.md) - [**Experiment 3**](./exp3.md) - [**Experiment 4**](./exp4.md)

---


### In case of any question:

* If the installation is not working or you have any other problems or suggestions - please email us

    1. Dr. Thomas Ebert (te@uni-bonn.de)
    2. Alexander Hoch (te@uni-bonn.de)

##### **Experiment 3: Fluorescent Tagging of Endogenous Proteins and Verification by Microscopy**
In this experiment, CRISPaint and CRISPR/Cas9 are used to insert a *GFP tag* into the human genome.  
Instead of knocking out a gene, the goal is to label an endogenous protein with a fluorescent marker so that it becomes visible under the microscope in living cells.  
To prove specificity, six different conditions are tested. In five conditions, one essential component of the system is missing or varied, while the sixth contains all components in the correct ratio.  
Only the complete system should result in successful tagging, visible as a characteristic staining pattern.

---

1. Download the image data
    * Download the microscopy images from the given link.  
    * Save them in a clearly labeled folder.

2. Open in Fiji
    * Launch Fiji (ImageJ) and open the image files.  
    * Make sure all channels load correctly.

3. Assign colors to channels
    * Assign each channel a *meaningfully chosen pseudocolor* (e.g., GFP in green, DNA in blue, others as appropriate).  
    * Merge the channels to create composite images.

4. Figure preparation
    * Prepare a figure with six panels (A–F), each showing one condition.  
    * Use the same magnification, scaling, and contrast settings for all panels.  
    * Add a scale bar.  
    * Label panels consistently (Condition 1–6).

5. Conditions
    * pRZ-Cas9-mCherry  
    * Frame Selector +2  
    * Target Selector TUBB  
    * mNeonGreen-2A-PuroR  
    * mNeonGreen-2A-PuroR +pRZ-Cas9-mCherry +Frame Selector +2
    * mNeonGreen-2A-PuroR +pRZ-Cas9-mCherry +Frame Selector +2 +Target Selector TUBB

7. Interpretation and analysis
    * The figure should make clear that the system has *no background or unspecific integration* in the negative conditions (1–5). 
    * Only in the complete condition (Panel 6) should successful integration (tagging) be visible.  
    * Check if the observed staining pattern matches the *expected pattern* for the targeted protein.  
    * This comparison is key to confirming the specificity of the system.

---
