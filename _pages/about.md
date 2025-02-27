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

Hello, I’m Kaike Zhang (张凯科), an phD student at the <a herf='http://www.ict.ac.cn'>Institute of Computing Technology, Chinese Academy of Sciences</a>.
My research interest includes trustworthy graph data mining and trustworthy recommender system.

# 🔥 News

- _2025.01_: &nbsp;🎉🎉 Our paper <a herf='#'>Personalized Denoising Implicit Feedback for Robust Recommender System</a> is accepted in TheWebConf (WWW) 2025.

- _2024.12_: &nbsp; I received the Huawei PhD Scholarship in 2024.

- _2024.09_: &nbsp;🎉🎉 Our paper <a herf='https://arxiv.org/pdf/2410.22844'>Understanding and Improving Adversarial Collaborative Filtering for Robust Recommendation</a> is accepted in NeurIPS 2024.

- _2024.08_: &nbsp;🎉🎉 Our paper <a herf='https://aclanthology.org/2024.findings-emnlp.335.pdf'>PKAD: Pretrained Knowledge is All You Need to Detect and Mitigate Textual Backdoor Attacks</a> is accepted in EMNLP 2024.

- _2024.07_: &nbsp;🎉🎉 Our paper <a herf='https://arxiv.org/pdf/2409.17476'>Improving the Shortest Plank: Vulnerability-Aware Adversarial Training for Robust Recommender System</a> is accepted in RecSys 2024.

- _2024.07_: &nbsp;🎉🎉 Our paper <a herf='https://arxiv.org/pdf/2408.10666'>Accelerating the Surrogate Retraining for Poisoning Attacks against Recommender Systems</a> is accepted in RecSys 2024.

- _2024.04_: &nbsp;🎉🎉 Our paper <a herf='https://arxiv.org/pdf/2401.17723.pdf'>LoRec: Combating Poisons with Large Language Model for Robust Sequential Recommendation</a> is accepted in SIGIR 2024.

- _2023.05_: &nbsp;🎉🎉 Our paper <a herf='https://arxiv.org/pdf/2210.10592.pdf'>DyTed: Disentangled Representation Learning for Discrete-time Dynamic Graph</a> is accepted in SIGKDD 2023.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TheWebConf 2025</div><img src='images/PLD2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Personalized Denoising Implicit Feedback for Robust Recommender System](#)
**Kaike Zhang**, Qi Cao, Yunfan Wu, Fei Sun, Huawei Shen, Xueqi Cheng

- We identify the limitations of existing loss-based denoising methods, highlighting the significant overlap between normal and noisy  interactions in the overall loss distribution.
- We find that, for a given user, there is a clear distinction between normal and noisy interactions in the user's personal loss distribution. Leveraging this insight, we propose a resampling strategy for denoising, PLD.
- We conduct an in-depth theoretical analysis, proving PLD's effectiveness and suggesting ways to further enhance its performance.

([**Code**](https://github.com/Kaike-Zhang/PLD))
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/PamaCF2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Understanding and Improving Adversarial Collaborative Filtering for Robust Recommendation](https://arxiv.org/pdf/2410.22844)
**Kaike Zhang**, Qi Cao, Yunfan Wu, Fei Sun, Huawei Shen, Xueqi Cheng

- We provide theoretical evidence that ACF can achieve better performance and robustness compared to traditional CF in both clean and poisoned data contexts.
- We further identify upper and lower bounds of reduction in recommendation error for ACF during optimization and demonstrate that applying personalized perturbation magnitudes for each user can further improve ACF.
- Based on the above theoretical understandings, we propose Personalized Magnitude Adversarial Collaborative Filtering (PamaCF), with extensive experiments confirming that PamaCF further improves both performance and robustness compared to state-of-the-art defense methods.

([**Code**](https://github.com/Kaike-Zhang/PamaCF))
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/PKAD2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PKAD: Pretrained Knowledge is All You Need to Detect and Mitigate Textual Backdoor Attacks](https://aclanthology.org/2024.findings-emnlp.335.pdf)
Yu Chen, Qi Cao, **Kaike Zhang**, Xuchao Liu, Huawei Shen

- We delve into utilizing PLM insights to identify the mismatched relationship and shared characteristics of poisoned samples, forming a two-stage detection strategy.
- Through extensive experiments, we demonstrate our approach’s effectiveness across various datasets and attack strategies, achieving better performance more swiftly.

([**Code**](https://github.com/Ascian/PKAD))
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RecSys 2024</div><img src='images/VAT2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving the Shortest Plank: Vulnerability-Aware Adversarial Training for Robust Recommender System](https://arxiv.org/pdf/2409.17476)
**Kaike Zhang**, Qi Cao, Yunfan Wu, Fei Sun, Huawei Shen, Xueqi Cheng

- Through extensive empirical analysis, we interestingly find that “users with a higher degree of fit within the recommender system are at a higher risk of being affected by attacks”.
- Building on these insights, we introduce a novel vulnerability-aware adversarial training method, VAT, applying user-adaptive magnitudes of perturbations based on users’ vulnerabilities.
- Our comprehensive experiments confirm the effectiveness of VAT in resisting various attacks, maintaining recommendation quality, and demonstrating its adaptability across various recommendation models.

([**Code**](https://github.com/Kaike-Zhang/VAT))
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RecSys 2024</div><img src='images/GP2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerating the Surrogate Retraining for Poisoning Attacks against Recommender Systems](https://arxiv.org/pdf/2408.10666)
Yunfan Wu, Qi Cao, Shuchang Tao, **Kaike Zhang**, Fei Sun, Huawei Shen
- We introduce a novel method Gradient Passing (GP) based on
both intuitive and theoretical analyses, accelerating the retraining
process of surrogate recommenders.
- We present the use of GP to enhance data poisoning attacks. It can
be integrated into state-of-the-art attack methods and combined
with other techniques.
- Extensive experiments on three real-world datasets and six victim
recommenders validate the efficiency and effectiveness of GP.

([**Code**](https://github.com/WuYunfan/GradientPassingAttack))
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/LoRec2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LoRec: Combating Poisons with Large Language Model for Robust Sequential Recommendation](https://arxiv.org/pdf/2401.17723.pdf)
**Kaike Zhang**, Qi Cao, Yunfan Wu, Fei Sun, Huawei Sheng, Xueqi Cheng
- We pioneer the exploration of LLMs' knowledge of fraudsters within recommender systems, revealing how LLMs' knowledge can aid defense methods in generalizing across various attacks.
- We lead the initiative of incorporating LLMs into the robustness of sequential recommender systems, introducing LoRec as an innovative and general framework that employs LLM-enhanced Calibration for robust sequential recommendations.
- Our extensive experiments confirm the efficacy of the LoRec framework in withstanding diverse types of attacks and its adaptability across multiple backbone recommendation architectures.

([**Code**](https://github.com/Kaike-Zhang/LoRec))
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD 2023</div><img src='images/DyTed2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DyTed: Disentangled Representation Learning for Discrete-time Dynamic Graph](https://arxiv.org/pdf/2210.10592.pdf)
**Kaike Zhang**, Qi Cao, Gaolin Fang, Bingbing Xu, Hongjian Zou, Huawei Sheng, Xueqi Cheng
- To the best of our knowledge, we are the first to study and introduce the disentangled representation learning framework for discrete-time dynamic graphs.
- We propose two representation generators with carefully designed pretext tasks and a disentanglement-aware discriminator under an adversarial learning framework.
- We conduct extensive experiments on real dynamic graphs of daily capital transactions on Tencent, achieving state-of-the-art performance on various downstream tasks.

([**Code**](https://github.com/Kaike-Zhang/DyTed))
</div>
</div>

# 📖 Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/RobustRS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Recommender System: A Survey and Future Directions](https://arxiv.org/pdf/2309.02057.pdf)
**Kaike Zhang**, Qi Cao, Fei Sun, Yunfan Wu, Shuchang Tao, Huawei Sheng, Xueqi Cheng
- A comprehensive and systematic taxonomy for robustness-enhance methods in recommender systems.
- An all-encompassing overview of the representative methodologies, as well as evaluation approaches and datasets currently employed in the domain.
- Detailed discussions encompass various facets: the main consideration of recommender systems' robustness in diverse scenarios, its correlation with other trustworthy properties of recommender systems, as well as open issues coupled with recommender systems' robustness, and trends for future development.

</div>
</div>

# 🎖 Honors and Awards

- _2024_ Huawei PhD Scholarship.
- _2024_ NeurIPS Scholar Award.
- _2024_ Institute of Computing Technology 3A Student _Leader_.
- _2023_ Institute of Computing Technology 3A Student.
- _2022_ Institute of Computing Technology Director’s Named Scholarship.
- _2021_ Excellent Undergraduate Graduation Design of Chongqing University.
- _2021_ Outstanding Undergraduate Graduates.
- _2019_ Second Prize of the National College Student Mathematical Modeling Competition of China (Chongqing).
- _2018_ Second prize in the National College Student Mathematics Competition of China.

# 📖 Educations

- _2021.09 - Present_, **Institute of Computing Technology, Chinese Academy of Seiences**.
  - Consecutive MS and phD in Computer Application Technology and Cyberspace Security
  - Tutor: Professor Xueqi Cheng and Xinran Liu
- _2017.09 - 2021.06_, **Chongqing University**.
  - BS in Software Engineering
  - Tutor: Professor Haibo Hu

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships

- _2022.04 - 2023.03_, [Tencent](https://www.tencent.com/en-us/), China.
