# Data-Centric AI Intellectual Property Protection
This repository introduces research topics related to protecting the intellectual property (IP) of AI from a data-centric perspective. Such topics include data-centric model IP protection, data authorization protection, data copyright protection, and any other data-level technologies that protect the IP of AI. More content is coming, and in the end, we care about your uniqueness!!!

## Data-Centric Model Protection
Verify your ownership of a certain model via certain data and authorize the usage of your model to certain data.
### Image Data
- Non-Transferable Learning: A New Approach for Model Ownership Verification and Applicability Authorization
  - [[paper]](https://arxiv.org/abs/2106.06916) [[code]](https://github.com/conditionWang/NTL) 
  - ICLR 2022 Oral
- Model Barrier: A Compact Un-Transferable Isolation Domain for Model Intellectual Property Protection
  - [[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Model_Barrier_A_Compact_Un-Transferable_Isolation_Domain_for_Model_Intellectual_CVPR_2023_paper.pdf) [[code]](https://github.com/LyWang12/CUTI-Domain)
  - CVPR 2023
- Domain Specified Optimization for Deployment Authorization
  - [[paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Domain_Specified_Optimization_for_Deployment_Authorization_ICCV_2023_paper.html)
  - ICCV 2023
### Other Data
- Unsupervised Non-transferable Text Classification
  - [[paper]](https://arxiv.org/abs/2210.12651) [[code]](https://github.com/ChaosCodes/UNTL)
  - EMNLP 2022

## Data Authorization Protection (namely unlearnable data or examples)
Prevent unauthorized data usage of model training, usually achieved by decreasing the model performance via poisoning attacks.
### Image Data
- Unlearnable Examples: Making Personal Data Unexploitable
  - [[paper]](https://arxiv.org/abs/2101.04898) [[code]](https://github.com/HanxunH/Unlearnable-Examples)
  - ICLR 2021
- Going Grayscale: The Road to Understanding and Improving Unlearnable Examples
  - [[paper]](https://arxiv.org/pdf/2111.13244.pdf) [[code]](https://github.com/liuzrcc/ULE-Gray)
  - Arxiv 2021
- Robust Unlearnable Examples: Protecting Data Against Adversarial Learning
  - [[paper]](https://arxiv.org/abs/2203.14533) [[code]](https://github.com/fshp971/robust-unlearnable-examples)
  - ICLR 2022
- Self-Ensemble Protection: Training Checkpoints Are Good Data Protectors
  - [[paper]](https://arxiv.org/abs/2211.12005) [[code]](https://github.com/Sizhe-Chen/SEP)
  - ICLR 2023
- Transferable Unlearnable Examples
  - [[paper]](https://arxiv.org/abs/2210.10114) [[code]](https://github.com/renjie3/TUE)
  - ICLR 2023
- LAVA: Data Valuation without Pre-Specified Learning Algorithms
  - [[paper]](https://arxiv.org/abs/2305.00054) [[code]](https://github.com/ruoxi-jia-group/LAVA)
  - ICLR 2023 Spotlight
- Unlearnable Clusters: Towards Label-Agnostic Unlearnable Examples
  - [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zhang_Unlearnable_Clusters_Towards_Label-Agnostic_Unlearnable_Examples_CVPR_2023_paper.html) [[code]](https://github.com/jiamingzhang94/Unlearnable-Clusters)
  - CVPR 2023
- Universal Unlearnable Examples: Cluster-wise Perturbations without Label-consistency
  - [[paper]](https://openreview.net/forum?id=pHO19kq_yT)
  - ICLR 2023 submission
- Unlearnable Examples Give a False Sense of Security: Piercing through Unexploitable Data with Learnable Examples
  - [[paper]](https://arxiv.org/abs/2305.09241) 
  - Arxiv 2023
- Towards Generalizable Data Protection With Transferable Unlearnable Examples
  - [[paper]](https://arxiv.org/pdf/2305.11191.pdf)
  - Arxiv 2023
- CUDA: Convolution-Based Unlearnable Datasets
  - [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Sadasivan_CUDA_Convolution-Based_Unlearnable_Datasets_CVPR_2023_paper.html) [[code]](https://github.com/vinusankars/Convolution-based-Unlearnability)
  - CVPR 2023
- Raising the Cost of Malicious AI-Powered Image Editing
  - [[paper]](https://arxiv.org/pdf/2302.06588.pdf) [[code]](https://github.com/MadryLab/photoguard)
  - Arxiv 2023
- Learning the Unlearnable: Adversarial Augmentations Suppress Unlearnable Example Attacks
  - [[paper]](https://arxiv.org/abs/2303.15127) [[code]](https://github.com/lafeat/ueraser)
  - Arxiv 2023
- Towards Generalizable Data Protection With Transferable Unlearnable Examples
  - [[paper]](https://arxiv.org/abs/2305.11191)
  - Arxiv 2023
- The Devil's Advocate: Shattering the Illusion of Unexploitable Data using Diffusion Models
  - [[paper]](https://arxiv.org/pdf/2303.08500.pdf)
  - Arxiv 2023
- GLAZE: Protecting Artists from Style Mimicry by Text-to-Image Models
  - [[paper]](https://www.shawnshan.com/files/publication/glaze.pdf) [[App]](https://glaze.cs.uchicago.edu/download.html)
  - Usenix Security 2023
- Flew Over Learning Trap: Learn Unlearnable Samples by Progressive Staged Training
  - [[paper]](https://arxiv.org/pdf/2306.02064.pdf) [[code]](https://github.com/CherryBlueberry/ST)
  - Arxiv 2023
- Segue: Side-information Guided Generative Unlearnable Examples for Facial Privacy Protection in Real World
  - [[paper]](https://arxiv.org/pdf/2310.16061.pdf)
  - Arxiv 2023
- What Can We Learn from Unlearnable Datasets?
  - [[paper]](https://arxiv.org/pdf/2305.19254.pdf) [[code]](https://github.com/psandovalsegura/learn-from-unlearnable)
  - NeurIPS 2023

### Other Data
- Unlearnable Examples: Protecting Open-Source Software from Unauthorized Neural Code Learning
  - [[paper]](https://people.cs.pitt.edu/~chang/seke/seke22paper/paper066.pdf) [[code]](https://github.com/ZhenlanJi/Unlearnable_Code)
  - SEKE 2022
- WaveFuzz: A Clean-Label Poisoning Attack to Protect Your Voice
  - [[paper]](https://arxiv.org/abs/2203.13497)
  - Arxiv 2023
- Unlearnable Graph: Protecting Graphs from Unauthorized Exploitation
  - [[paper]](https://arxiv.org/abs/2303.02568) 
  - Poster at NDSS 2023
- Securing Biomedical Images from Unauthorized Training with Anti-Learning Perturbation
  - [[paper]](https://arxiv.org/abs/2303.02559)
  - Poster at NDSS 2023
- UPTON: Unattributable Authorship Text via Data Poisoning
  - [[paper]](https://arxiv.org/abs/2211.09717)
  - Arxiv 2023
- GraphCloak: Safeguarding Task-specific Knowledge within Graph-structured Data from Unauthorized Exploitation
  - [[paper]](https://arxiv.org/abs/2310.07100)
  - Arxiv 2023
- Make Text Unlearnable: Exploiting Effective Patterns to Protect Personal Data
  - [[paper]](https://arxiv.org/pdf/2307.00456.pdf)
  - Arxiv 2023


## Data Copyright Protection
Verify your ownership of certain data via black-box model access.
### Image Data
- Radioactive data: tracing through training
  - [[paper]](http://proceedings.mlr.press/v119/sablayrolles20a.html) [[code]](https://github.com/facebookresearch/radioactive_data)
  - ICML 2020
- Tracing Data through Learning with Watermarking
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3437880.3458442)
  - Proceedings of the 2021 ACM Workshop on Information Hiding and Multimedia Security
- On the Effectiveness of Dataset Watermarking
  - [[paper]](https://dl.acm.org/doi/abs/10.1145/3510548.3519376) 
  - Proceedings of the 2022 ACM on International Workshop on Security and Privacy Analytics
- Untargeted Backdoor Watermark: Towards Harmless and Stealthy Dataset Copyright Protection 
  - [[paper]](https://arxiv.org/pdf/2210.00875.pdf) [[code]](https://github.com/THUYimingLi/Untargeted_Backdoor_Watermark)
  - NeurIPS 2022 Oral
- Did You Train on My Dataset? Towards Public Dataset Protection with Clean-Label Backdoor Watermarking
  - [[paper]](https://arxiv.org/abs/2303.11470)
  - Arxiv 2023
- On the Effectiveness of Dataset Watermarking in Adversarial Settings
  - [[paper]](https://arxiv.org/pdf/2202.12506.pdf)
  - Proceedings of CODASPY-IWSPA 2022
- Anti-Neuron Watermarking: Protecting Personal Data Against Unauthorized Neural Networks
  - [[paper]](https://arxiv.org/pdf/2109.09023.pdf)
  - ECCV 2022
- Data Isotopes for Data Provenance in DNNs
  - [[paper]](https://arxiv.org/pdf/2208.13893.pdf) [[code]](https://anonymous.4open.science/r/data-isotopes-2E24/README.md)
  - Arxiv 2022
- Watermarking for Data Provenance in Object Detection
  - [[paper]](https://ieeexplore.ieee.org/abstract/document/10092239?casa_token=WRZjEznm7CIAAAAA:NCAQoiyihAJl9L2lDtaOLTPQLX8VImVrQZaz9lTtdDCMNtMhui_kI_iPsoxM4f2rih7tbvOKkZ0)
  -  2022 IEEE Applied Imagery Pattern Recognition Workshop (AIPR)
- Reclaiming the Digital Commons: A Public Data Trust for Training Data
  - [[paper]](https://arxiv.org/pdf/2303.09001.pdf)
  - AIES 2023
- MedLocker: A Transferable Adversarial Watermarking for Preventing Unauthorized Analysis of Medical Image Dataset
  - [[paper]](https://arxiv.org/abs/2303.09858)
  - Arxiv 2023
- How to Detect Unauthorized Data Usages in Text-to-image Diffusion Models
  - [[paper]](https://arxiv.org/pdf/2307.03108.pdf)
  - Arxiv 2023
- FT-Shield: A Watermark Against Unauthorized Fine-tuning in Text-to-Image Diffusion Models
  - [[paper]](https://arxiv.org/pdf/2310.02401.pdf)
  - Arxiv 2023
- Domain Watermark: Effective and Harmless Dataset Copyright Protection is Closed at Hand
  - [[paper]](https://arxiv.org/abs/2310.14942) [[code]](https://github.com/JunfengGo/Domain-Watermark)
  - NeurIPS 2023
- DiffusionShield: A Watermark for Copyright Protection against Generative Diffusion Models
  - [[paper]](https://arxiv.org/abs/2306.04642)
  - Arxiv 2023

### Other Data 
- CoProtector: Protect Open-Source Code against Unauthorized Training Usage with Data Poisoning
  - [[paper]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512225) [[code]](https://github.com/v587su/CoProtector)
  - WWW 2022
- CodeMark: Imperceptible Watermarking for Code Datasets against Neural Code Completion Models
  - [[paper]](https://arxiv.org/abs/2308.14401)
  - FSE 2023
- Watermarking Classification Dataset for Copyright Protection
  - [[paper]](https://arxiv.org/abs/2305.13257)
  - Arxiv 2023
