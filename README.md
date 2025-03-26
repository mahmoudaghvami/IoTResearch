# IoT Privacy Reading List (IoT Privacy Research Papers)

This page includes a collection of papers focused on Internet of Things (IoT) privacy and security, which should be beneficial for those looking to study the privacy implications and security solutions in smart homes and other IoT environments.

---

## Privacy Preservation Techniques

### Activity Recognition Protection for IoT Trigger-Action Platforms (PTAP)
- **Link**: [PTAP on GitHub](https://github.com/mahmoudaghvami/ptap)
- **Link (EuroS&P 2024)**: [EuroS&P 2024 Paper](https://people.kth.se/~musard/research/pubs/EuroSP24.pdf)
- **Authors**: Mahmoud Aghvami, Morteza Amini, Musard Balliu, Cyrille Artho
- **Summary**: PTAP aims to preserve privacy while maintaining utility in smart home environments by using adversarial machine learning techniques to perturb smart home data, preventing sensitive inferences.

### Practical Data Access Minimization in Trigger-Action Platforms (minTAP)
- **Link**: [USENIX Security 2022](https://www.usenix.org/conference/usenixsecurity22/presentation/chen-yunang-practical)
- **Authors**: Yunang Chen, Andrei Sabelfeld, Rahul Chatterjee, et al.
- **Summary**: This paper focuses on minimizing data access in IoT platforms by implementing data access policies that limit the amount of user data shared with third-party applications.

### Data Privacy in Trigger-Action Systems (eTAP)
- **Link**: [arXiv 2020](https://arxiv.org/abs/2012.05749)
- **Authors**: Yunang Chen, Amrita Roy Chowdhury, et al.
- **Summary**: Trigger-action platforms (TAPs) allow users to connect independent web-based or IoT services to achieve useful automation. Unfortunately, TAPs introduce a large-scale security risk: if compromised, attackers could access sensitive data. eTAP addresses this by executing trigger-compute-action rules without accessing users' private data in plaintext or learning anything about the results. The paper uses garbled circuits as a primitive and has been implemented in platforms like IFTTT and Zapier.

### PFirewall: Semantics-Aware Customizable Data Flow Control for Smart Home Privacy Protection
- **Link**: [NDSS 2021](https://www.ndss-symposium.org/ndss-paper/pfirewall-semantics-aware-customizable-data-flow-control-for-smart-home-privacy-protection/)
- **Authors**: Haotian Chi, Qiang Zeng, Xiaojiang Du, et al.
- **Summary**: This paper introduces PFirewall, a customizable data-flow control system for enhancing IoT platform privacy. PFirewall generates data-minimization policies to disclose the minimum amount of data required for automation. It also allows homeowners to define user-specific privacy preferences.

---

## Malicious Platform & IoT Attacks

### Spying on the Smart Home: Privacy Attacks and Defenses on Encrypted IoT Traffic
- **Link**: [arXiv](https://arxiv.org/abs/1708.05044)
- **Authors**: Noah Apthorpe, Dillon Reisman, Nick Feamster, et al.
- **Summary**: This paper examines the privacy risks of encrypted IoT traffic and the potential for adversaries to spy on smart homes by exploiting traffic patterns.

### Mockdroid: Trading Privacy for Application Functionality on Smartphones
- **Link**: [ACM Digital Library](https://dl.acm.org/doi/10.1145/1929319.1929345)
- **Authors**: Alastair R. Beresford, Andrew Rice, Nick Skehin, Ripduman Sohan
- **Summary**: Focuses on privacy concerns when applications on smartphones trade sensitive user data for functionality, which also extends to IoT systems in the context of privacy loss for enhanced features.

### Sensitive Information Tracking in Commodity IoT
- **Link**: [USENIX Security 2018](https://www.usenix.org/conference/usenixsecurity18)
- **Authors**: Z Berkay Celik, Leonardo Babun, Amit Kumar Sikder, et al.
- **Summary**: This paper discusses the tracking of sensitive information across IoT devices and proposes mitigation strategies to prevent unauthorized leakage of private data.

---

## Human Activity Recognition (HAR) and Privacy

### A Survey of Human Activity Recognition in Smart Homes Based on IoT Sensors Algorithms: Taxonomies, Challenges, and Opportunities with Deep Learning
- **Link**: [Sensors 2021](https://www.mdpi.com/1424-8220/21/18/6037)
- **Authors**: Damien Bouchabou, Sao Mai Nguyen, Christophe Lohr, Benoit LeDuc, Ioannis Kanellos
- **Summary**: This paper reviews the state-of-the-art in human activity recognition within smart homes, focusing on IoT sensor-based algorithms, challenges, and privacy concerns in data processing.

### A Deep Learning-based Framework for Human Activity Recognition in Smart Homes
- **Link**: [Mobile Information Systems 2021](https://www.hindawi.com/journals/misy/2021/8849896/)
- **Authors**: Alaeddine Mihoub
- **Summary**: Discusses the use of deep learning for activity recognition and its implications on user privacy, with a focus on IoT-based smart home environments.

### Privacy Risks of Compromised Trigger-Action Platforms
- **Link**: [ESORICS 2020](https://link.springer.com/chapter/10.1007/978-3-030-58852-4_14)
- **Authors**: Yu-Hsi Chiang, Hsu-Chun Hsiao, Chia-Mu Yu, Tiffany Hyun-Jin Kim
- **Summary**: Explores the privacy risks associated with compromised trigger-action platforms used in smart homes, highlighting potential security vulnerabilities.

---

## Human Activity Recognition (HAR) Datasets

Welcome to the **Human Activity Recognition (HAR) Datasets Repository**! This section provides an overview of publicly available datasets used for **smart home automation, activity recognition, and machine learning**.

### 1. Multi-Modal Dataset of Human Activities of Daily Living
- **Link**: [Dataset Access](https://zenodo.org/records/7937591)
- **Summary**: Includes **25 activities**, **14 participants**, and **8615 instances**, captured with **audio, vibration, infrared, light**, and **environmental sensors**.

### 2. ContextAct@A4H Dataset
- **Link**: [Amiqual4Home Access](http://amiqual4home.inria.fr)
- **Summary**: A real-life smart home dataset over **four weeks** with **object interactions, environmental conditions**, and **self-reported activities**.

### 3. Orange4Home Dataset
- **Link**: [Dataset Link](#)
- **Summary**: Captures **multi-modal human activity** in a **smart home environment** including **occupancy tracking, temperature, motion**, and **appliance usage**.

---

## Use Cases

- **AI & ML-based Human Activity Recognition (HAR)**
- **Smart Home Automation & IoT**
- **Healthcare Monitoring (elderly care, assisted living)**

[GitHub Repository for HAR Datasets](https://github.com/mahmoudaghvami/human-activity-datasets)

---
|A|B|C|
|-|-|-|
|Learn more about IoT privacy concerns|Explore additional IoT datasets|Understand how HAR impacts privacy|
