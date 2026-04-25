# WKU SRD Projects


This repository showcases Yixuan Mi's research projects presented at Student Research Day during his undergraduate studies at Wenzhou-Kean University. These projects represent various research directions and academic achievements explored throughout different semesters.

## Overview

This collection highlights projects presented at Student Research Day, each demonstrating exploration and innovation in specific research areas.

Project posters are available [here](./Posters).

### Current Projects

#### 1. ToM-Driver: Beyond Kinematic Models toward Social Intent Estimation with Theory-of-Mind in Autonomous Driving

![ToM-Driver](Posters/ToM-Driver.jpg)

- **Introduction**: This project explores how autonomous driving systems can better understand the social intentions of surrounding vehicles in complex traffic environments. Inspired by the human cognitive concept of Theory of Mind (ToM), ToM-Driver introduces a large language model-based reasoning framework that enables autonomous agents to infer other drivers’ intentions beyond traditional kinematic prediction.
- **Key Technologies**:
  - Theory of Mind (ToM) Reasoning
  - Autonomous Driving Decision-Making
  - Large Language Models (LLMs)
  - Social Intent Estimation
  - Multi-Agent Driving Scenario Analysis
  - nuScenes-Based Dataset Construction and Evaluation
- **Data Source**: nuScenes Autonomous Driving Dataset / nuScenes-ToM Dataset
- **Research Outcomes**:
  - Proposed ToM-Driver, a framework that integrates Theory-of-Mind reasoning into autonomous driving systems
  - Developed an LLM-amortized plausibility estimation workflow to reason about surrounding agents’ possible intentions
  - Compared ToM-Driver with traditional end-to-end planning and human-like planning methods
  - Evaluated the framework through open-loop and closed-loop driving experiments
  - Conducted ablation studies to analyze the contribution of key ToM reasoning components
  - Demonstrated improved decision-making and safety potential in multi-agent autonomous driving scenarios
  - Showed strong plausibility and stability on the nuScenes-ToM dataset

This project investigates the potential of cognitive reasoning and large language models for future autonomous driving systems by enabling agents to reason about other vehicles’ hidden intentions.


#### 2. FD-GAN: A Dual-Domain Approach with Fourier Domain Discriminators for Denoising Low-Dose CT Images (Poster Presentation Outstanding Award Winner at SRD 2025, Wenzhou-Kean University)

![FD-GAN](Posters/FD-GAN.jpg)

- **Introduction**: This project addresses the challenge of denoising low-dose CT (LDCT) images, aiming to minimize radiation exposure while preserving diagnostic accuracy. It proposes a novel dual-domain GAN model, FD-GAN, that leverages both spatial and Fourier domains to enhance detail recovery and training stability.
- **Key Technologies**:
  - Generative Adversarial Networks (GANs)
  - U-Net Discriminators in Image & Fourier Domains
  - Fourier Transform-Based Losses
  - PyTorch Deep Learning Framework
- **Data Source**: NIHAAPM-Mayo Clinic Low-Dose CT Dataset (2016 Low Dose CT Grand Challenge)
- **Research Outcomes**:
  - Developed a novel FD-GAN framework with dual-domain discriminators
  - Achieved superior denoising performance with improved PSNR and SSIM on both Chest-10% and Head-25% datasets
  - Outperformed state-of-the-art MSE-based (e.g., RED-CNN) and GAN-based (e.g., DU-GAN, WGAN-VGG) models in both visual and quantitative evaluations
  - Demonstrated effectiveness of dual-domain learning through comprehensive ablation studies

This paper has been accepted to the [International Joint Conference on Neural Networks (IJCNN) 2025](https://2025.ijcnn.org/).   
[Click here to see the paper](https://ieeexplore.ieee.org/document/11228631).


#### 3. Enhancing Portfolio Optimization with Data Fusion and Machine Learning in Quantitative Finance (Outstanding Research Award Winner at SRD 2024, Wenzhou-Kean University)


- **Introduction**: This project aims to revolutionize portfolio optimization in quantitative finance by integrating advanced machine learning techniques and data fusion methodologies.
- **Key Technologies**:
  - Machine Learning Models (LSTM, Random Forests, Gradient Boosting)
  - Qlib Library
  - Data Fusion Methods
- **Data Source**: CSMAR (China Stock Market & Accounting Research Database)
- **Research Outcomes**: 
  - Applied data fusion and deep learning to optimize financial portfolios
  - Reproduced and tested advanced models 50+ times with consistent performance
  - Planned sentiment analysis module for enhanced trading insight


#### *More projects will be added as research continues...*

## About the Author

Yixuan Mi
- Undergraduate CS Student at Wenzhou-Kean University
- Research Interests: Machine Learning, Computer Vision, NLP, Quantitative Finance
- Email: yixuanmi25@gmail.com


## Repository Updates

This repository will continuously update as new Student Research Day projects are completed. Each project will include detailed documentation and explanations to showcase the research process and outcomes.

---
*This repository is actively maintained and will be updated with new research projects and academic achievements. For any questions or suggestions, please feel free to reach out through the contact information provided above.*
