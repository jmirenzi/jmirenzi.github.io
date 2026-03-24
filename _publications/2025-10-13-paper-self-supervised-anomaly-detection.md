---
title: "Self-Supervised Time-Series Anomaly Detection with Temporal Logic Explanations"
collection: publications
category: conferences
permalink: /publication/2025-10-13-paper-self-supervised-anomaly-detection
excerpt: 'Self-Supervised Anomaly Detector'
date: 2025-10-13
venue: 'Conference on Game Theory and AI for Security'
paperurl: 'https://doi.org/10.1007/978-3-032-08067-7_15'
bibtexurl: 'http://jmirenzi.github.io/files/bibtex/10.1007_978-3-032-08067-7_15-citation.bib'
citation: 'Noorani, M., Puranic, A.G., Mirenzi, J., Baras, J.S. (2026). Self-supervised Time-Series Anomaly Detection with Temporal Logic Explanations. In: Baras, J.S., Papavassiliou S., Tsiropoulou, E.E., Sayin, M.O. (eds) Game Theory and AI for Security. GameSec 2025. Lecture Notes in Computer Science, vol 16224. Springer, Cham. https://doi.org/10.1007/978-3-032-08067-7_15'
---
### Abstract
The growing complexity of Cyber-Physical Systems (CPS) has heightened the need for robust, real-time anomaly detection to ensure safety and reliability in time-critical applications such as autonomous vehicles, industrial automation, etc. While deep learning methods have demonstrated exceptional performance in detecting anomalies within multivariate time-series data, their inherent lack of interpretability limits their adoption in such critical environments. This paper presents a novel framework for deep learning-based anomaly detection in CPS, specifically designed to operate on unlabeled multivariate time-series data. The framework utilizes autoencoders to generate latent data representations, whose reconstruction error is used in a threshold-augmented discriminator network model to detect anomalies. Our approach then integrates Signal Temporal Logic (STL) inference to provide meaningful, human-understandable explanations for the decisions made by the deep learning models. This interpretability is crucial for diagnosing anomalies and implementing corrective actions in real time. We validate our method on real-world data collected from a Clearpath Husky mobile robot, to demonstrate its ability to detect anomalies with high accuracy while offering actionable insights into the decision-making process. We deploy the detector on the robot to show the real-time detection capabilities, as shown in the supplemental video.

