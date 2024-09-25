---
title: "Research Projects"
permalink: /_pages/research/
layout: single
author_profile: true
classes: wide
---
# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;"> Deep Learning for Neuropathology </span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;"> Attention-based multiple instance learning for understanding Chronic Traumatic Encephalopathy (CTE)</span>

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">  A vision foundation model for neuropathology for advancing AI-driven neuropathological image analysis</span>
<img src="/files/FM_figures.png" width="360" height="360" />  

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;"> Deep Learning Analysis of Multi-modal Optical Imaging of Human Brain Tissue </span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;"> Deep learning registration of Polarization-Sensitive Optical Coherence Tomography (PS-OCT) and quantitative Birefringence Microscopy (qBRM) images</span>
<img src="/files/OCT_qBRM_reg.png" width="540" height="360" /> 

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Diffuse Optical Tomography (DOT)</span>

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Multimodal data fusion for breast lesion classification</span>
I have developed data fusion approaches to combine ultrasound, DOT, and radiologists' assessments for breast cancer diagnosis. The proposed two-stage approach can potentially distinguish breast cancers from benign lesions in near real-time.

<img src="/files/DOT_multimodal.png" width="540" height="360" />  <img src="/files/DOT_BIRADS_thumbnail.png" width="540" height="360" />  

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Tackling mismatch errors</span>
My thesis aims to solve practical problems in DOT breast imaging and to improve breast cancer diagnosis.
Our lab uses Ultrasound (US)-guided DOT to probe tissue optical properties i.e. optical absorption, oxygenated and deoxygenated hemoglobin concertation for breast cancer diagnosis and treatment monitoring. However, imaging artifacts can  appear due to mismatches between the two side breasts in tissue curvature, tissue heterogeneity, the depth and angle of the chest wall underneath the breast tissue, and source or detector (optode) coupling. During patient studies, these errors can all cause misinterpretation of lesion images. I proposed two algorithms to mitigate probe-tissue contact problems and reduce image artifacts. 

[[Paper1: Correction of optode coupling errors]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-8-5320&id=453847)  
[[Paper2: Ultrasound-guided edge artifact reduction]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-2-689&id=445667)

<img src="/files/coupling_error_thumbnail.jpg" width="360" height="360" />  <img src="/files/2021_edge_artifact_thumbnail.jpg" width="360" height="360" />


## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Difference imaging from single measurements</span>
“Difference imaging”, which reconstructs target optical properties using measurements with and without target information, is often used in DOT in vivo imaging. However, taking additional reference measurements is time-consuming, and mismatches between the target medium and the reference medium can cause inaccurate reconstruction. I designed a multi-layer perceptron (MLP) to output data for difference imaging from target measurements only. The model is trained and validated on simulation data and tested with simulations, phantom experiments, and clinical data from 56 patients with breast lesions. It can simplify the data acquisition procedure, mitigate mismatch problems, and improve reconstructed image quality in DOT difference imaging. 
[[Paper]](https://doi.org/10.1117/1.JBO.27.8.086003) [[Code]](https://github.com/Shy-Li/DOT_pert_generation)

<img src="/files/2022JBO.jpg"  width="480" height="480" />

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">CNN for accurately estimating breast tissue optical properties</span>

In general, image reconstruction methods used in diffuse optical tomography (DOT) are based on diffusion approximation, and they consider the breast tissue as a homogenous, semi-infinite medium. However, the semi-infinite medium assumption used in DOT reconstruction is not valid when the chest wall is underneath the breast tissue. We propose a deep learning-based neural network approach where a convolution neural network (CNN) is trained to simultaneously obtain accurate optical property values for both the breast tissue and the chest wall. The CNN model shows great promise in reducing errors in estimating the optical properties of the breast tissue in the presence of a shallow chest wall. 
[[Paper]](https://doi.org/10.1117/1.JBO.26.10.106004)

<img src="/files/JBO_26_10_106004_f002.png"  width="600" height="140" />
<img src="/files/JBO_26_10_106004_f009.png"  width="600" height="470" />

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Machine learning with physical constrains for DOT reconstruction</span>
We trained an Autoencoder-based machine learning model with physical constraints (ML-PC) to perform diffuse optical tomography (DOT) reconstruction. Our method has two key components: (i) a neural network based on an auto-encoder is adopted for DOT reconstruction, and (ii) physical constraints are implemented to achieve accurate reconstruction. Both qualitative and quantitative results demonstrate that the accuracy of the proposed method surpasses that of existing models.
[[Paper]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-9-5720&id=458081)

<img src="/files/ML_PC.jpg"  width="600" height="210" />

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Fusion network for breast lesion classification</span>
We propose a two-stage classification strategy with deep learning. In the first stage, US images and histograms created from DOT perturbation measurements are combined to predict benign lesions. Then the non-benign lesions are passed through the second stage, which combines US features and 3D DOT reconstructed images for final diagnosis.The first stage alone identified 72.6% of benign cases without image reconstruction. In distinguishing between benign and malignant breast lesions in patient data, the two-stage approach achieved an AUC of 0.960, outperforming diagnoses from the first stage alone (AUC = 0.889) and the second stage alone (AUC = 0.909). The proposed two-stage approach can potentially distinguish breast cancers from benign lesions in near real-time.

<img src="/files/DOT_individual_1.jpg" width="540" height="720" />  <img src="/files/DOT_combined_2.jpg" width="480" height="360" />

# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Optical Coherence Tomography (OCT)</span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Human coloreactal cancer classification using deep learning and OCT</span>
Optical coherence tomography (OCT) can differentiate normal colonic mucosa from neoplasia, potentially offering a new mechanism of endoscopic tissue assessment and biopsy targeting, with a high optical resolution and an imaging depth of ~1 mm. I designed customized ResNet is utilized to classify OCT catheter colorectal images. An area under the receiver operating characteristic (ROC) curve (AUC) of 0.975 is achieved to distinguish between normal and cancerous colorectal tissue images.
[[Paper]](https://onlinelibrary.wiley.com/doi/10.1002/jbio.202100349) [[Code]](https://github.com/Shy-Li/OCT_CNN)

<img src="/files/OCT_colon.jpg" width="270" height="360" />  <img src="/files/OCT_colon2.jpg" width="480" height="360" />


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Spatial Frequency Domain Imaging (SFDI)</span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">AdaBoost-based multiwavelength SFDI for human colorectal tissue assessment</span>

Multiwavelength spatial frequency domain imaging (SFDI) can provide tissue optical absorption and scattering signatures, and would be able to differentiate various colorectal neoplasia from normal tissue. In this ex vivo study of human colorectal tissues, we trained an abnormal vs. normal adaptive boosting (AdaBoost) classifier to dichotomize tissue based on SFDI imaging characteristics, and an area under the receiver operating characteristic (ROC) curve (AUC) of 0.95 is achieved. 
[[Paper]](https://onlinelibrary.wiley.com/doi/abs/10.1002/jbio.201960241)

<img src="/files/SFDI_colon.jpg" width="240" height="320" />  <img src="/files/SFDI_colon2.jpg" width="500" height="320" />


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Image-guided Photo-mediated Ultrasound Therapy</span>
Simultaneously applied laser and ultrasound treat neovascularization in rabbit eyes guided by OCT & photoacoustic microscopy (PAM).
Simulated bubble dynamics under simultaneous laser & ultrasound and validated the simulations with experiments on tubes filled with blood.
[[Paper]](https://iopscience.iop.org/article/10.1088/1361-6560/aac7bc/meta)







