# Assessing fMRI-Based Memory Detection: Can Personally Experienced Event Memories Be Differentiated from Second-Hand Event Knowledge?

**Poster Presentation** ([View Poster](./2016-chow-ins.png)) | International Neuroethics Society (INS) Annual Meeting | 2016 | San Diego, CA, USA

**Recognition:** Awarded **"Top Abstract"** and published in *The American Journal of Bioethics Neuroscience*

**Fellowship Award:** National Science Foundation Graduate Research Fellowship Program  

**Core Skills:** `MATLAB` `Machine Learning (MVPA)` `Predictive Modeling` `Regularized Logistic Regression (RLR)` `Cross-Validation` `Feature Engineering` `Time-Series Analysis` `Factorial Experimental Design` `Wearable Camera Technology` `fMRI`

---

## Executive Summary

* **Problem:** Investigated the granularity of functional magnetic resonance imaging (fMRI) machine learning models in classifying memory retrieval experiences, an essential distinction for potential legal and forensic memory detection. *Can machine learning models detect the neural signatures of memory characteristics, including differentiating personally experienced life events from second-hand familiarity?*
* **Approach:** Designed a 3-phase fMRI experimental paradigm utilizing naturalistic event sequences from participants' lives captured by wearable digital cameras over 3 weeks to simulate real-world event recall. Deployed multi-voxel pattern analysis (MVPA) using regularized logistic regression (RLR) classifiers and leave-one-run-out cross-validation across targeted brain networks to decode memory source, image familiarity, and temporal order base on neural activity.
* **Takeaway:** Demonstrated that machine learning models reliably decode real-world memory states above chance: the **Autobiographical Network** preferentially decoded memory source (Self vs. Other life events), whereas the **Retrieval Success Network** preferentially decoded prior image familiarity (Previewed vs. Non-Previewed events). While machine learning models successfully classified nuanced memories (e.g., personal experience vs. second-hand knowledge), sub-100% classification accuracy establishes critical empirical boundary conditions that caution against immediate deployment in legal and forensic settings.

---

## Technical Methodologies
*As the lead researcher and first author, I designed the end-to-end experimental and analytical workflow supported by an award from the National Science Foundation Graduate Research Fellowship Program:*
* **Experimental Design:** Designed a novel 3-phase functional magnetic resonance imaging (fMRI) experimental paradigm utilizing wearable digital cameras to capture unstructured, real-world event sequences, programming the fMRI tasks with customized stimulus delivery and scan-synchronized response collection in **MATLAB**, and collected neuroimaging and behavioral data.
* **Statistical & Predictive Modeling:** Designed and implemented a neuroimaging machine learning pipeline to clean and process the time-series, deploying multi-voxel pattern analysis (MVPA) and regularized logistic regression (RLR) classifier algorithms in **MATLAB** to decode memory states from brain activity, and evaluated machine learning performance along with additional behavioral analyses in **Microsoft Excel** and **SPSS**.
* **Data Visualization:** Developed data visualizations to translate complex machine learning and brain mapping findings into accessible formats and authored the final presentation materials.

---

![INS Poster](./2016-chow-ins.png)

---

## Funding Acknowledgment
This material is based upon work supported by the National Science Foundation Graduate Research Fellowship Program under Grant No. DGE-1144087 and DGE-1650604 awarded to Tiffany E. Chow, as well as a Hellman Fellows Fund award and UCLA COR Faculty Research Grant to Jesse Rissman.

Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
