---
title: "Research Projects"
permalink: /_pages/research/
layout: single
author_profile: true
classes: wide
---


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Diffuse Optical Tomography (DOT)</span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Tackling mismatch errors</span>
My thesis aims to solve practical problems in DOT breast imaging and to improve breast cancer diagnosis.
Our lab uses Ultrasound (US)-guided DOT to probe tissue optical properties i.e. optical absorption, oxygenated and deoxygenated hemoglobin concertation for breast cancer diagnosis and treatment monitoring. However, imaging artifacts can  appear due to mismatches between the two side breasts in tissue curvature, tissue heterogeneity, the depth and angle of the chest wall underneath the breast tissue, and source or detector (optode) coupling. During patient studies, these errors can all cause misinterpretation of lesion images. I proposed algorithms to mitigate probe-tissue contact problems and image artifacts, which can easily happen during clinical studies due to breast curvature and patient movement. 

[[Paper1: Correction of optode coupling errors]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-8-5320&id=453847)  
[[Paper2: Ultrasound-guided edge artifact removal]](https://opg.optica.org/boe/fulltext.cfm?uri=boe-12-2-689&id=445667)


## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Difference imaging from single measurements</span>
“Difference imaging”, which reconstructs target optical properties using measurements with and without target information, is often used in DOT in vivo imaging. However, taking additional reference measurements is time-consuming, and mismatches between the target medium and the reference medium can cause inaccurate reconstruction. I designed a multi-layer perceptron (MLP) to output data for difference imaging from target measurements only. The model is trained and validated on simulation data and tested with simulations, phantom experiments, and clinical data from 56 patients with breast lesions. It can simplify the data acquisition procedure, mitigate mismatch problems, and improve reconstructed image quality in DOT difference imaging. 
[[Paper]](https://doi.org/10.1117/1.JBO.27.8.086003) [[Code]](https://github.com/Shy-Li/DOT_pert_generation)

<img src="/files/2022JBO.jpg"  width="450" height="450" />

## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Fusion network for breast lesion classification</span>
Trained a fusion network to combine DOT and co-registered ultrasound for real-time classification of breast lesions that can assist in clinical decisions. 


# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Optical Coherence Tomography (OCT)</span>
## <span style="color:teal; font-family:Comic Sans MS;font-size: 20px;">Human coloreactal cancer classification using deep learning and OCT</span>
Optical coherence tomography (OCT) can differentiate normal colonic mucosa from neoplasia, potentially offering a new mechanism of endoscopic tissue assessment and biopsy targeting, with a high optical resolution and an imaging depth of ~1 mm. I designed customized ResNet is utilized to classify OCT catheter colorectal images. An area under the receiver operating characteristic (ROC) curve (AUC) of 0.975 is achieved to distinguish between normal and cancerous colorectal tissue images.

[[Paper]](https://onlinelibrary.wiley.com/doi/10.1002/jbio.202100349) [[Code]](https://github.com/Shy-Li/OCT_CNN)

<img src="/files/OCT_colon.jpg" width="270" height="360" /><img src="/files/OCT_colon2.jpg" width="480" height="360" />



# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Spatial Frequency Domain Imaging (SFDI)</span>
Trained an AdaBoost classifier using optical absorption and scattering features calculated from SFDI colorectal images.

<img src="/files/SFDI_colon.jpg" width="270" height="360" />



# <span style="color:black; font-family:Comic Sans MS;font-size: 25px;">Image-guided Photo-mediated Ultrasound Therapy</span>
Simultaneously applied laser and ultrasound treat neovascularization in rabbit eyes guided by OCT & photoacoustic microscopy (PAM).
Simulated bubble dynamics under simultaneous laser & ultrasound and validated the simulations with experiments on tubes filled with blood.
