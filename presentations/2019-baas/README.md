# Apolipoprotein ɛ4 Relates to Cognitive Empathy and Frontoparietal Gray Matter Volume in Healthy Older Adults

**Poster Presentation** ([View Poster](./2019-chow-baas.png)) | Bay Area Affective Science (BAAS) | 2019 | San Francisco, CA, USA

**Tools:** `R` `nlme` `MATLAB` `Statistical Parametric Mapping Toolbox (SPM12)` `Computational Anatomy Toolbox (CAT12)`

**Core Skills:** `Structural Neuroimaging (MRI)` `Voxel-Based Morphometry (VBM)` `Linear Mixed-Effects Models` `Multivariate Linear Regression` `Cohort Stratification` `Multimodal Data Integration`

---

## Executive Summary

* **Problem:** Alzheimer's disease (AD) is characterized by progressive cognitive decline alongside socioemotional alterations, including deficits in empathy. The Apolipoprotein ɛ4 (APOE\*E4) allele is one of the greatest genetic risk factors for sporadic AD. Whether APOE\*E4 relates to individual differences in cognitive empathy in healthy older adults, and how this genetic vulnerability is reflected in structural neuroanatomy, remains poorly understood.
* **Approach:** Evaluated a large, longitudinal cohort of cognitively healthy older adults (*n* = 359; follow-up range up to 12.4 years) with informant ratings of cognitive empathy, a subset of which also had magnetic resonance imaging (MRI) scans (*n* = 216). Built multivariate mixed-effects linear regression models in **R** (`nlme`) to assess baseline cognitive empathy differences and conducted whole-brain voxel-based morphometry in **MATLAB** (`SPM12` and `CAT12`) to evaluate the interaction between APOE\*E4 carrier status and cognitive empathy on gray matter volume.
* **Takeaway:** Identified behavioral and structural neuroanatomical signatures of genetic AD risk in asymptomatic adults. **APOE\*E4 carriers** exhibited significantly lower baseline cognitive empathy relative to **non-carriers**. Furthermore, lower cognitive empathy in carriers was specifically associated with greater gray matter volume across **frontoparietal regions** that support emotional regulation and executive functions, suggesting a structural compensatory mechanism for emerging socioemotional deficits prior to cognitive decline.

---

## Technical Methodologies
*As the lead researcher and first author, I designed and conducted the end-to-end neuroimaging, statistical, and visualization workflow:*
* **Structural Neuroimaging and Statistical Modeling:** Built a voxel-based morphometry pipeline in **MATLAB** (`SPM12` and `CAT12`) to test whole-brain APOE\*E4 and empathy interactions on gray matter volume. Developed multivariate linear regressions and linear mixed-effects models in **R** (`nlme`) to evaluate group differences in baseline cognitive empathy between carriers and non-carriers.
* **Data Wrangling and Multimodal Integration:** Investigated the core research question and operationalized the analytical design. Curated and harmonized genetic testing (APOE*E4 allelic profiling), informant-based empathy evaluations, neuropsychological batteries, and structural neuroimaging across 359 older adults.
* **Data Visualization:** Authored all presentation materials, developing statistical interaction plots in **R** and anatomical maps to translate behavioral and morphometric findings into accessible visual formats detailing preclinical structural-behavioral associations in asymptomatic individuals.

---

![BAAS Poster](./2019-chow-baas.png)

---

## Funding Acknowledgment

This study was supported by the Larry L. Hillblom Foundation, the John Douglas French Alzheimer’s Foundation, and grants from the National Institute on Aging (P30 AG062422, K23AG040127, K99AG065501, R01AG057204, and R01AG073244).
