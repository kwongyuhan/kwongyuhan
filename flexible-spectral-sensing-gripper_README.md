# Flexible Spectral Sensing Gripper

A flexible gripper-integrated spectral sensing system for real-time food freshness assessment.

This project is based on our research work:

> Flexible Spectral Sensing Gripper for Real-Time Food Freshness Assessment  
> *Eng*, 2026  
> DOI: https://doi.org/10.3390/eng7050243

## Overview

This project develops a Flexible Spectral Sensing Gripper (FSSG) for real-time non-destructive food quality assessment. By embedding spectral sensing units into the grasping interface, the system can acquire multi-point spectral information while conforming to irregular food surfaces.

## My Contributions

- Participated in the system design of the flexible spectral sensing gripper.
- Integrated a low-cost 12-channel Vis/NIR spectral sensor array with electronic components and an ESP32-S microcontroller.
- Supported spectral data acquisition, preprocessing, model training, and performance evaluation.
- Contributed to manuscript writing as a co-first author.

## System Architecture

```text
Flexible Gripper Interface
        |
        v
12-Channel Vis/NIR Spectral Sensor Array
        |
        v
ESP32-S Microcontroller
        |
        v
Spectral Data Collection
        |
        v
Preprocessing + MLR / PLSR / SVM
        |
        v
Freshness and Quality Assessment
```

## Tech Stack

- ESP32-S
- Flexible printed circuit
- PDMS encapsulation
- Vis/NIR spectral sensing
- Spectral preprocessing
- MLR / PLSR / SVM
- Python

## Results

- Developed a gripper-integrated spectral sensing system for potato quality screening.
- Evaluated regression models for dry matter content and starch content prediction.
- Built an SVM-based classification pipeline for distinguishing healthy and deteriorated samples.
- Achieved 98.67% classification accuracy for healthy versus artificially induced deteriorated potato samples.

## Publication

**Yuhan Gong**, Ruihua Zhang, Chunling Liu, Wei Liu, Wenjing Zhao, Yingle Du, Tao Sun, Xinqing Xiao.  
Flexible Spectral Sensing Gripper for Real-Time Food Freshness Assessment.  
*Eng*, 2026.  
https://doi.org/10.3390/eng7050243

