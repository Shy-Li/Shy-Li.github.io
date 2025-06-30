---
title: "Research Projects"
permalink: /_pages/research/
layout: single
author_profile: true
classes: wide
---
As a researcher working at the intersection of artificial intelligence (AI) and biomedical imaging, I focus on both diagnostic applications and the investigation of disease mechanisms, particularly in cancer and neurodegenerative diseases (NDs). My work leverages trustworthy AI to enhance traditional and novel imaging modalities, uncover hidden pathological patterns, and integrate multimodal data. These efforts support drug discovery, improve diagnostic precision, and inform personalized treatment decisions.

<img src="/files/research_overview.png" width="900" height="540" /> 

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;"> AI for Neuropathology </span>
I develop data-efficient AI models that support large-scale, quantitative analysis of ND pathology and open new opportunities for identifying novel tissue-level markers of disease progression. 

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;"> Attention-based weakly-supervised AI for understanding Chronic Traumatic Encephalopathy (CTE)</span>
I developed data-efficient deep learning models trained with only slide-level supervision to extract biologically meaningful features from neuropathology images. The model generated attention maps that highlighted structural changes linked to tau aggregation, revealing subtle patterns often missed by manual review. These tools support large-scale, quantitative analysis of ND pathology and open new opportunities for identifying novel tissue-level markers of disease progression. 

<img src="/files/ABMIL_AT8.png" width="480" height="320" />  

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">  A vision foundation model for neuropathology for advancing AI-driven neuropathological image analysis</span>
I am developing the first neuropathology-specific foundation model leveraging the world’s largest digital neuropathology database, aiming to fully unlock the potential of AI-based analysis in advancing our understanding of NDs.  

<img src="/files/FM_figures.png" width="480" height="320" />  

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;"> AI Analysis of Multi-modal Optical Imaging of Human Brain Tissue </span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;"> Self-supervised registration of Polarization-Sensitive Optical Coherence Tomography (PS-OCT) and quantitative Birefringence Microscopy (qBRM) images</span>
I developed a self-supervised registration framework to align PS-OCT and qBRM images without requiring paired ground truth. This approach leverages intrinsic structural consistency across modalities to learn accurate spatial correspondence in a data-efficient manner. 

<img src="/files/OCT_qBRM_reg.png" width="480" height="320" /> 


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Multimodal AI for breast cancer diagnosis</span>

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Multimodal data fusion for breast lesion classification</span>
I have developed data fusion approaches to combine ultrasound, Diffuse Optical Tomography (DOT), and radiologists' BIRADS assessments for breast cancer diagnosis. The proposed two-stage approach can potentially distinguish breast cancers from benign lesions in near real-time. [[Paper1: Two-stage]](https://onlinelibrary.wiley.com/doi/full/10.1002/jbio.202300483) [[code1]](https://github.com/OpticalUltrasoundImaging/DOT_two_stage) [[Paper2: DOT + BIRADS]](https://www.spiedigitallibrary.org/journals/journal-of-biomedical-optics/volume-28/issue-8/086002/Two-stage-classification-strategy-for-breast-cancer-diagnosis-using-ultrasound/10.1117/1.JBO.28.8.086002.full) [[code2]](https://github.com/OpticalUltrasoundImaging/DOT_histo_SVM) [[Paper3: DOT + ultrasound]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-14-4-1636&id=528551) [[code3]](https://github.com/OpticalUltrasoundImaging/Fusion_model)

<img src="/files/DOT_multimodal.png" width="400" height="240" /> <img src="/files/DOT_BIRADS_thumbnail.png" width="320" height="240" />  


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">AI for Colorectal Cancer Diagnosis</span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Human coloreactal cancer classification using deep learning and Optical coherence tomography (OCT)</span>
Optical coherence tomography (OCT) can differentiate normal colonic mucosa from neoplasia, potentially offering a new mechanism of endoscopic tissue assessment and biopsy targeting, with a high optical resolution and an imaging depth of ~1 mm. I designed a customized ResNet to classify OCT catheter colorectal images. An area under the receiver operating characteristic (ROC) curve (AUC) of 0.975 is achieved to distinguish between normal and cancerous colorectal tissue images.
[[Paper]](https://onlinelibrary.wiley.com/doi/10.1002/jbio.202100349) [[Code]](https://github.com/Shy-Li/OCT_CNN)

<img src="/files/OCT_colon.jpg" width="180" height="240" />  <img src="/files/OCT_colon2.jpg" width="300" height="240" />

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">AdaBoost-based multiwavelength Spatial Frequency Domain Imaging (SFDI) for human colorectal tissue assessment</span>

Multiwavelength spatial frequency domain imaging (SFDI) can provide tissue optical absorption and scattering signatures, and would be able to differentiate various colorectal neoplasia from normal tissue. In this ex vivo study of human colorectal tissues, we trained an abnormal vs. normal adaptive boosting (AdaBoost) classifier to dichotomize tissue based on SFDI imaging characteristics.
[[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/jbio.201960241)

<img src="/files/SFDI_colon.jpg" width="180" height="240" />  <img src="/files/SFDI_colon2.jpg" width="360" height="240" />

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">AI-Based Image Reconstruction and Quality Enhancement</span>

Optical imaging like Diffuse Optical Tomography (DOT) offers label-free, radiation-free, and cost-effective solutions for biomedical applications, but its clinical translation has been slowed by long acquisition times, lengthy reconstruction, and inconsistent image quality. To address these limitations, I developed AI-based methods that enhance both image acquisition and reconstruction. I built deep learning models, including physics-informed neural networks (PINNs), that accelerate data acquisition, suppress image artifacts, and improve reconstruction speed and accuracy. Collectively, these advances make optical imaging more robust, efficient, and suitable for clinical use.

<img src="/files/coupling_error_thumbnail.jpg" width="240" height="240" />  <img src="/files/2021_edge_artifact_thumbnail.jpg" width="240" height="240" />

[[Paper1]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-9-5720&id=458081)

[[Paper2: Correction of optode coupling errors]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-8-5320&id=453847)  

[[Paper3: Ultrasound-guided edge artifact reduction]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-2-689&id=445667)

[[Paper4]](https://doi.org/10.1117/1.JBO.27.8.086003) [[Code]](https://github.com/Shy-Li/DOT_pert_generation)

[[Paper5]](https://doi.org/10.1117/1.JBO.26.10.106004)












