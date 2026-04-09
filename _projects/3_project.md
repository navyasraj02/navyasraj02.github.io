---
layout: page
title: Pseudostem Weevil Detector (PSWD)
description: Acoustic pest detection in banana crops using CNNs.
importance: 3
category: Data Science
---

An innovative acoustic monitoring system designed to help farmers detect Pseudostem Weevil (PSW) infestations during the pupa stage. The system analyzes distinctive acoustic traits to provide early intervention insights.

### Technical Stack
* **Deep Learning:** Convolutional Neural Networks (CNN)
* **Audio Processing:** [Librosa](https://librosa.org/) for Mel spectrogram feature extraction
* **Backend:** Flask (Python) 
* **Frontend:** HTML5, CSS3, Bootstrap

### Core Features
* Acoustic Data Engineering: Curated a dataset of 6,000 field recordings, utilizing Mel spectrogram extraction to transform raw audio into 2D image representations for deep learning.

* Deep Learning Excellence: Trained a CNN classifier that achieved 99.75% accuracy in detecting early-stage infestations, significantly outperforming traditional manual inspection.

* Full-Stack Deployment: Engineered an end-to-end web portal on PythonAnywhere, enabling real-time audio uploads and instant inference for field use.

---
#### Team & Collaboration
*Collaborative project with Annie Treasa Sabu, Anuranjana Rajeev, and Nayana P.*

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/image_psw.png" title="PSW Pest Field Photos" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption text-center">
    Field photos of Pseudostem Weevil samples collected during data acquisition.
</div>
