# Mimic
This repository will be used for exploring the MIMIC-III and MIMIC-IV datasets with a goal of developing various AI applications on top of them. Project website for mimic can be found at [https://mimic.mit.edu](https://mimic.mit.edu) 

# Datasets
|Dataset|Description|Date|Comments|
|---|---|---|---|
|MIMIC-III|Critical care data for patients admitted to ICUs at the BIDMC|2001 - 2012|Haven't started exploring in this repo|
|MIMIC-IV|Hospital and critical care data for patients admitted to the ED or ICU|2008 - 2019|Currently exploring|
|MIMIC-IV-ED|Emergency department data for individuals attending the ED|2011 - 2019|Haven't started exploring in this repo|
|MIMIC-IV Waveforms (TBD)|This dataset has yet to be published.|?|Haven't started exploring in this repo|
|MIMIC-CXR|Chest x-ray imaging and deidentified free-text radiology reports for patients admitted to the ED|2012 - 2016|Haven't started exploring in this repo|

# Chest X-Ray Data
One of the major changes from MIMIC-III to MIMIC-IV is the availability of Chest x-ray data. As noted from the ['What's new?'](https://mimic.mit.edu/docs/iv/about/whatsnew/) section of MIMIC, it is a new addition to MIMIC and the database is publicly available in the [MIMIC-CXR Database](https://physionet.org/content/mimic-cxr/2.0.0/). The *subject_id* identifer used in MIMIC-IV is the same *subject_id* used in the MIMIC-CXR database. Thus, all chest x-rays in MIMIC-CXR are linkable to patient stays in MIMIC-IV.

# References
- [MIMIC Code Repository](https://github.com/MIT-LCP/mimic-code/tree/main)
- Johnson, A., Bulgarelli, L., Pollard, T., Horng, S., Celi, L. A., & Mark, R. (2023). MIMIC-IV (version 2.2). PhysioNet. https://doi.org/10.13026/6mm1-ek67.
- Johnson, A.E.W., Bulgarelli, L., Shen, L. et al. MIMIC-IV, a freely accessible electronic health record dataset. Sci Data 10, 1 (2023). https://doi.org/10.1038/s41597-022-01899-x
- Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.
- Çallı E, Sogancioglu E, van Ginneken B, van Leeuwen KG, Murphy K. Deep learning for chest X-ray analysis: A survey. Med Image Anal. 2021;72:102125. doi:10.1016/j.media.2021.102125 [link](https://pubmed.ncbi.nlm.nih.gov/34171622/)
