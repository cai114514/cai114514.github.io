---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi there! I am Runxun Zhang (章润勋), a Master's student at the Institute of Automation, Chinese Academy of Sciences (CASIA), advised by [Prof. Jingwei Wei](https://weijingwei-ai-research.github.io/zh/). I received my B.Eng. in Microelectronics Science and Engineering from Sun Yat-sen University in 2026.

My research focuses on **LLM agents** and **agentic reinforcement learning**, with applications in medical AI. Before that, I worked on analog and RF integrated circuit design. Visit my [Google Scholar](https://scholar.google.com/citations?user=VK4upJIAAAAJ) profile for the full list of publications.

For collaborations or questions, feel free to reach me at zhangrunxun2026[at]ia.ac.cn.


# 🔥 News
- *2026.11*: &nbsp;🎤 Presented our competition results at the Champions Forum (群英会), Chinese Congress of Radiology 2026, Beijing.
- *2026.11*: &nbsp;📄 New work on evidence governance for tool-augmented medical agents is out on arXiv!
- *2026.11*: &nbsp;🏅 Received the First Prize at the award ceremony of the 2026 National Medical Insurance Imaging AI Competition.
- *2026.10*: &nbsp;🥇 First Prize (Final) in the 2026 National Medical Insurance Imaging AI Competition, Track 8 (chest X-ray, self-built model group); ranked 1st in the preliminary round.
- *2026.02*: &nbsp;🎉 MorphSeek was accepted by CVPR 2026 as a **Highlight**!
- *2025.11*: &nbsp;📄 MorphSeek is released on arXiv.
- *2025.10*: &nbsp;📄 One paper on CMOS power amplifiers was accepted by ICICM 2025.
- *2025.10*: &nbsp;🎓 Received the Sun Yat-sen University Outstanding Undergraduate Scholarship (Second Class).
- *2024.10*: &nbsp;🏆 Received the National Scholarship.
- *2024.10*: &nbsp;🎓 Received the Sun Yat-sen University Outstanding Undergraduate Scholarship (First Class) for the second time.
- *2023.10*: &nbsp;🎓 Received the Sun Yat-sen University Outstanding Undergraduate Scholarship (First Class).
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/fig_cieg.jpg' alt="CIEG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Not All Evidence Is Admissible: Evidence Governance for Tool-Augmented Medical Agents](https://arxiv.org/abs/2611.22169)

**Runxun Zhang**, Onofrio Antonio Catalano, Jinqiao Wang, Jingwei Wei

[**arXiv**](https://arxiv.org/abs/2611.22169)
- Identifies "evidence hijacking" in tool-augmented medical agents and proposes CIEG: an independent checker decides which tool outputs may enter as evidence. Training-free; best accuracy at comparable scale on MedQA, MedMCQA, NEJM, fundus glaucoma and chest X-ray pneumonia.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 Highlight</div><img src='images/fig_morphseek.jpg' alt="MorphSeek" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MorphSeek: Fine-grained Latent Representation-Level Policy Optimization for Deformable Image Registration](https://arxiv.org/abs/2511.17392)

**Runxun Zhang\***, Yizhou Liu, Dongrui Li, Bo Xu, Jingwei Wei\*

[**arXiv**](https://arxiv.org/abs/2511.17392) &nbsp; [**CVF Open Access**](https://openaccess.thecvf.com/CVPR2026?day=all) &nbsp; [**Code**](https://github.com/cai114514/MorphSeek)
- Reformulates deformable image registration as policy optimization in the latent feature space, trained with GRPO. Consistent Dice gains on OASIS, LiTS and Abdomen MR-CT with minimal parameter cost.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICICM 2025</div><img src='images/icicm_pa.jpg' alt="PA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A 2.4–2.6 GHz CMOS High Linearity Power Amplifier with MGTR and Harmonic Trap Techniques](https://ieeexplore.ieee.org/abstract/document/11316054)

**Runxun Zhang**, Gengzhen Qi

[**IEEE Xplore**](https://ieeexplore.ieee.org/abstract/document/11316054)

- Sole first-author work from my undergraduate research. A 65nm CMOS power amplifier that uses multi-gated transistors and a second-harmonic trap to improve linearity (post-layout: Psat 30.32 dBm, OP1dB 28.48 dBm, OIP3 38.58 dBm).
</div>
</div>

\* indicates equal contribution.

# 🛠 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Competition</div><img src='images/ccr2026_talk.jpg' alt="CCR 2026 talk" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-Detector Consensus for Chest X-ray Screening** (2026 National Medical Insurance Imaging AI Competition, Track 8)

Algorithm lead, Institute of Automation, CAS. Team X-Vision.

- Designed the full algorithm pipeline: anatomy-aware quality control and a "consult-style" detector ensemble in which heterogeneous detectors nominate findings and an independent model reviews them before a learned arbiter makes the final call.
- **1st place** in the preliminary round, **First Prize** in the final. Presented at the final defense, the award ceremony, the Champions Forum of the Chinese Congress of Radiology 2026, and the results-transfer meeting in Guangxi.
- In a 100k-case screening cohort, reviewing the top 20% by risk score covered 93.7%–98.2% of positives for the evaluated findings.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Internship</div><img src='images/intern_mri_clip.jpg' alt="Abdominal MRI foundation model" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-phase Abdominal MRI 3D-CLIP Foundation Model** (Research intern, Zidong Taichu Foundation Model Center, CASIA, 2025.03 - 2025.09)

- A multimodal foundation model for focal liver lesions on multi-phase abdominal MRI (3D image encoder + report text encoder), with downstream detection, classification and diagnosis tasks.
- Responsible for the data pipeline: integrating MRI sequences from multiple centers, completeness checking, de-duplication, segmentation and registration. The registration problems I met here led to MorphSeek.
</div>
</div>

# 🧪 Earlier Work

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tape-out</div><img src='images/sar_adc_layout.jpg' alt="SAR ADC layout" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**4-channel 8-bit 800 MSPS Time-Interleaved SAR ADC** (TSMC 65nm tape-out, 2024.11 - 2026.01)

Core member, Mixed-Signal Integrated Systems Lab, Sun Yat-sen University.

- Designed one 8-bit 200 MSPS asynchronous sub-SAR ADC: circuit, pre-layout simulation, layout drawing and post-layout simulation. The chip has been fabricated and tested.
</div>
</div>

- **RF power amplifiers** (2023.12 - 2025.12): core member of the team that won the Third Prize (South China Region) at the 8th IEEE Cup IC Innovation and Entrepreneurship Competition with a 2.4 GHz switched-capacitor PA, and of two university innovation projects on NB-IoT transmitters and linearized PAs.

# 🎖 Honors and Awards
- *2026.10* First Prize (Final) and 1st place (Preliminary), 2026 National Medical Insurance Imaging AI Competition, Track 8 (chest X-ray, self-built model group)
- *2025.10* Outstanding Undergraduate Scholarship (Second Class), Sun Yat-sen University
- *2024.10* National Scholarship (Undergraduate), Ministry of Education of China
- *2024.10* Outstanding Undergraduate Scholarship (First Class), Sun Yat-sen University
- *2023.10* Outstanding Undergraduate Scholarship (First Class), Sun Yat-sen University
- *2024.07* Third Prize (South China Region), 8th National College IC Innovation and Entrepreneurship Competition (IEEE Cup)
- *2024.02* Honorable Mention, MCM (Mathematical Contest in Modeling)
- *2023.12* Provincial Second Prize, 5th National College Mathematics Competition (Guangdong)

# 📖 Educations
- *2026.09 - now*, Master's student, Institute of Automation, Chinese Academy of Sciences, Beijing. Advisor: [Prof. Jingwei Wei](https://weijingwei-ai-research.github.io/zh/).
- *2022.09 - 2026.06*, B.Eng. in Microelectronics Science and Engineering, Sun Yat-sen University.
