---
layout: page
title: BioVault - Biometric Authentication
description: A decentralized biometric system using template fragmentation and encrypted distribution.
importance: 1
category: Software
---

A secure biometric authentication framework designed to prevent centralized data breaches by distributing encrypted biometric templates across multiple server nodes.

### Technical Stack
* **Backend:** Flask (Python), REST APIs
* **Database:** MongoDB
* **Image Processing:** [OpenCV](https://opencv.org/), NumPy
* **Security:** AES Encryption, Template Fragmentation

### Core Capabilities
* Decentralized Security: Engineered a distribution protocol that fragments encrypted biometric templates across multiple servers, ensuring data cannot be reconstructed from a single compromised node.
* Feature Extraction: Developed image processing pipelines using **OpenCV** to perform fingerprint enhancement, thinning, and minutiae extraction for high-precision matching.
* Scalable Infrastructure: Designed and implemented **RESTful APIs** in Flask to manage asynchronous biometric data processing and retrieval from a **MongoDB** cluster.
