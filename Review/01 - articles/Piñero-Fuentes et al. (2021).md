---
type: article
title: A Deep-Learning Based Posture Detection System for Preventing Telework-Related Musculoskeletal Disorders
authors:
  - Piñero-Fuentes
  - Canas-Moreno
  - Rios-Navarro
  - Domínguez-Morales
  - Sevillano
  - Linares-Barranco
year: 2021
journal: Sensors
doi: 10.3390/s21155236
link: ""
language: en
study_country: Spain
temporal_context: pandemic
study_type: other
approach: quantitative
sample: 12 volunteers generating a dataset of 151 video sequences and 148 validated frames
population: Volunteers (males and females aged 20 to 50 with diverse hand dominances and biotypes) performing computer typing tasks
sector: education
company_size: not-reported
work_modality:
  - telework
  - remote
risk_categories:
  - "[[Ergonomic Risks]]"
  - "[[Organizational Risks]]"
specific_risks:
  - incorrect-posture
  - spinal-deformities
  - neck-pain
  - shoulder-pain
  - back-pain
  - arm-and-wrist-disorders
  - loss-of-ergonomic-oversight
management_practices:
  - automated-posture-detection
  - real-time-posture-feedback
  - edge-computing-monitoring
  - ergonomic-workstation-adjustment
  - active-rest-breaks
tools:
  - "[[ResNet18]]"
  - "[[Joint Angle Risk Classifier]]"
analyzes_gender: false
mentions_legislation: false
tags:
  - telework
  - deep-learning
  - posture-detection
  - musculoskeletal-disorders
  - computer-vision
---

### Piñero-Fuentes et al. (2021)

#### Reference (ABNT)
PIÑERO-FUENTES, Eva, et al. A deep-learning based posture detection system for preventing telework-related musculoskeletal disorders. **Sensors**, v. 21, n. 15, art. 5236, p. 1-20, 2021. DOI: 10.3390/s21155236.

#### Objective
To design, develop, and test an automated upper-body posture detection system using convolutional neural networks (CNN) and specialized embedded edge-computing hardware to monitor neck, shoulder, and arm alignment in real time and deliver corrective postural recommendations to teleworkers.

#### Research questions or hypotheses
How can occupational health services automatically detect and quantify the degree of postural deviation among home-based teleworkers without physical surveillance? Is it feasible to achieve high accuracy and real-time processing speeds with low power consumption on embedded edge devices using webcam video streams?

#### Method
*   **Type:** Experimental engineering and technical validation study
*   **Application:** Laboratory simulation of home office computer workstations at the Department of Computer Architecture and Technology, University of Seville (Spain), involving 12 diverse subjects performing continuous typing under natural and induced incorrect postures
*   **Type of work:** Telework and computer-based office work

#### Main findings
The proposed edge-computing posture detection system successfully executed real-time video processing (up to 25 frames per second) with low energy consumption (under 10 watts) on specialized embedded hardware. The system achieved an overall accuracy of 84.1% for multi-class classification across four risk ranges and exceeded 90% accuracy (mean of 92.4%, reaching 97.9% for shoulder alignment) when distinguishing between binary safe versus hazardous postures. The NVIDIA Jetson Xavier NX board demonstrated optimal operational efficiency, processing 7 frames per watt consumed in offline tests and 6 frames per watt during live 60 FPS video streams, confirming the technical feasibility of low-cost, non-invasive home ergonomic monitoring.

#### Identified risks
*   **Classification:** Ergonomic, Organizational
*   **Specific risk factors:** Sustained awkward postures, improper neck flexion, asymmetric shoulder tilting, excessive arm abduction, non-ergonomic home workstations, prolonged computer use, and loss of organizational ergonomic oversight by OSH services
*   **Impacts and consequences:** Work-related musculoskeletal disorders of the spine, neck, shoulders, arms, and wrists, progressive spinal deformities (hyperlordosis, hyperkyphosis, scoliosis), and cumulative biomechanical strain

#### Risk management strategies
Continuous, automated non-invasive posture monitoring via standard computer webcams without requiring body-attached wearable sensors. Deployment of real-time notification algorithms that provide immediate corrective feedback to workers when dangerous joint angles are detected. Transmission of objective, quantified postural metrics to occupational medical personnel to enable early diagnosis of poor ergonomic habits. Promotion of workstation micro-adjustments, active rest breaks, and targeted stretching exercises.

#### Tools and techniques
- [[ResNet18]]: A customized deep convolutional neural network model optimized with NVIDIA TensorRT and Torch2TRT, designed to extract 18 human skeletal keypoints in real time from video streams.
- [[Joint Angle Risk Classifier]]: A real-time geometric algorithm utilizing the arctangent trigonometric function (atan2) to calculate angular deviations across four biomechanical parameters (neck inclination, shoulder alignment, left and right arm abduction) and classify them into four ergonomic risk tiers (Range 0 to Range 3) based on Chaffin and Woodson ergonomic standards.

#### Relation to regulations
The authors observe that corporate occupational risk prevention services traditionally deliver in-person ergonomic training within company facilities. However, the mass migration to home telework eliminated employers' physical control over workstation environments and posture, necessitating autonomous technological countermeasures.

#### Gaps pointed out by the authors
The system was evaluated within a controlled laboratory setting on a relatively small cohort of 12 subjects. Future research should implement and validate real-time automated recommendation engines during live, extended work shifts in authentic home office environments. Further development is needed to enhance the neural network architecture to track additional complex anatomical parameters, such as multi-segment curvature of the vertebral column. Larger-scale empirical trials with expanded participant cohorts are recommended to validate industrial deployability.

#### Other relevant information
The authors provide benchmark comparisons across three embedded computing platforms (Raspberry Pi 4, Jetson Nano, and Jetson Xavier NX), identifying the Jetson Xavier NX as the most energy-efficient hardware solution.

#### Evidence quotes
- **Supports:** Main findings | "The system achieved a total accuracy of 84.1%... The results showed a posture detection accuracy higher than 80% for the original four-class problem and more than 90% for the two-class classification system." (p. 15)
- **Supports:** Main findings | "A viable recommendation for building a system like the one presented would be the Jetson Xavier NX, since its efficiency is the maximum achieved, with 7 frames processed per watt consumed..." (p. 16)
- **Supports:** Gaps pointed out by the authors | "Although this work has been implemented and tested in a laboratory environment with a not very extensive dataset, the results are very promising... A larger study with more people and/or parameters is also interesting..." (p. 18)

#### Reviewer notes
