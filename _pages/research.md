---
title: "Research Projects"
permalink: /_pages/research/
layout: single
author_profile: true
classes: wide
---
My research connects optical measurement design, computational reconstruction, and machine learning to study brain physiology and tissue pathology. Building on my earlier work in optical cancer assessment, my current program focuses on two complementary directions.

<img src="/files/research_overview.png" width="1000" height="600" /> 

## <span style="color:black; font-family:Arial, sans-serif; font-size: 22px;">1. Physics-informed neurophotonic systems for measuring brain dynamics</span>

I develop optical imaging methods that combine physical models with machine learning to quantify brain dynamics. My work in laser speckle contrast imaging uses physics-informed neural networks to recover quantitative parameters without requiring ground-truth parameter labels. This approach enables rapid reconstruction while preserving consistency with the underlying optical model. [Published work](https://doi.org/10.1117/1.NPh.13.3.035012)

## <span style="color:black; font-family:Arial, sans-serif; font-size: 22px;">2. Interpretable and generalizable AI for brain injury and neurodegeneration</span>

I develop AI methods that identify meaningful tissue features from neuropathology and three-dimensional optical images. My age-informed, attention-based learning framework predicts tau burden from stained brain images and connects its predictions with cortical and cellular features. [Published work](https://doi.org/10.1186/s40708-025-00276-9)

<img src="/files/ABMIL_AT8.png" width="480" height="270" />

I also developed **NeuroPath**, a self-supervised foundation-model prototype for learning reusable representations of brain tissue.

<img src="/files/FM_figures.png" width="480" height="320" />

Together, these directions support a longer-term effort to connect optical measurements of brain dynamics with independently assessed tissue outcomes, testing which imaging features provide reliable information about vulnerability, injury, and recovery.

## <span style="color:teal; font-family:Arial, sans-serif; font-size: 16px;"> Self-supervised registration of Polarization-Sensitive Optical Coherence Tomography (PS-OCT) and quantitative Birefringence Microscopy (qBRM) images
I developed a self-supervised registration framework to align PS-OCT and qBRM images without requiring paired ground truth. This approach leverages intrinsic structural consistency across modalities to learn accurate spatial correspondence in a data-efficient manner. 

<img src="/files/OCT_qBRM_reg.png" width="480" height="320" /> 


# <span style="color:black; font-family:Arial, sans-serif; font-size: 22px;">Multimodal AI for Breast Cancer Diagnosis
I have developed data fusion approaches to combine ultrasound, Diffuse Optical Tomography (DOT), and radiologists' BIRADS assessments for breast cancer diagnosis. The proposed two-stage approach can potentially distinguish breast cancers from benign lesions in near real-time. [[Paper1: Two-stage]](https://onlinelibrary.wiley.com/doi/full/10.1002/jbio.202300483) [[code1]](https://github.com/OpticalUltrasoundImaging/DOT_two_stage) [[Paper2: DOT + BIRADS]](https://www.spiedigitallibrary.org/journals/journal-of-biomedical-optics/volume-28/issue-8/086002/Two-stage-classification-strategy-for-breast-cancer-diagnosis-using-ultrasound/10.1117/1.JBO.28.8.086002.full) [[code2]](https://github.com/OpticalUltrasoundImaging/DOT_histo_SVM) [[Paper3: DOT + ultrasound]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-14-4-1636&id=528551) [[code3]](https://github.com/OpticalUltrasoundImaging/Fusion_model)

<img src="/files/DOT_multimodal.png" width="350" height="200" /> <img src="/files/DOT_BIRADS_thumbnail.png" width="280" height="200" />  

# <span style="color:black; font-family:Arial, sans-serif; font-size: 22px;">AI for Colorectal Cancer Diagnosis
## <span style="color:teal; font-family:Arial, sans-serif; font-size: 16px;">Human coloreactal cancer classification using deep learning and Optical coherence tomography (OCT)
Optical coherence tomography (OCT) can differentiate normal colonic mucosa from neoplasia, potentially offering a new mechanism of endoscopic tissue assessment and biopsy targeting, with a high optical resolution and an imaging depth of ~1 mm. I designed a customized ResNet to classify OCT catheter colorectal images. An area under the receiver operating characteristic (ROC) curve (AUC) of 0.975 is achieved to distinguish between normal and cancerous colorectal tissue images.
[[Paper]](https://onlinelibrary.wiley.com/doi/10.1002/jbio.202100349) [[Code]](https://github.com/Shy-Li/OCT_CNN)

<img src="/files/OCT_colon.jpg" width="180" height="240" />  <img src="/files/OCT_colon2.jpg" width="300" height="240" />

## <span style="color:teal; font-family:Arial, sans-serif; font-size: 16px;">AdaBoost-based multiwavelength Spatial Frequency Domain Imaging (SFDI) for human colorectal tissue assessment
Multiwavelength spatial frequency domain imaging (SFDI) can provide tissue optical absorption and scattering signatures, and would be able to differentiate various colorectal neoplasia from normal tissue. In this ex vivo study of human colorectal tissues, we trained an abnormal vs. normal adaptive boosting (AdaBoost) classifier to dichotomize tissue based on SFDI imaging characteristics.
[[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/jbio.201960241)

<img src="/files/SFDI_colon.jpg" width="180" height="240" />  <img src="/files/SFDI_colon2.jpg" width="360" height="240" />


# <span style="color:black; font-family:Arial, sans-serif; font-size: 22px;">AI-Based Image Reconstruction and Quality Enhancement
Optical imaging like Diffuse Optical Tomography (DOT) offers label-free, radiation-free, and cost-effective solutions for biomedical applications, but its clinical translation has been slowed by long acquisition times, lengthy reconstruction, and inconsistent image quality. To address these limitations, I developed AI-based methods that enhance both image acquisition and reconstruction. I built deep learning models, including physics-informed neural networks (PINNs), that accelerate data acquisition, suppress image artifacts, and improve reconstruction speed and accuracy. Collectively, these advances make optical imaging more robust, efficient, and suitable for clinical use.

<img src="/files/coupling_error_thumbnail.jpg" width="240" height="240" />  <img src="/files/2021_edge_artifact_thumbnail.jpg" width="240" height="240" />

[[Paper1:Machine learning model with physical constraints for image reconstruction]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-9-5720&id=458081)

[[Paper2: Correction of optode coupling errors]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-8-5320&id=453847)  

[[Paper3: Ultrasound-guided edge artifact reduction]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-2-689&id=445667)

[[Paper4]](https://doi.org/10.1117/1.JBO.27.8.086003) [[Code]](https://github.com/Shy-Li/DOT_pert_generation)

[[Paper5]](https://doi.org/10.1117/1.JBO.26.10.106004)












