---
permalink: /
title: "Bingzhe Wang"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Bingzhe Wang. I received my Ph.D. degree in Artificial Intelligence from Gaoling School of Artificial Intelligence, Renmin University of China. My research focuses on game theory and mechanism design, machine learning, reinforcement learning, and large language models.

I hold both Bachelor’s and Master’s degrees in Mathematics from China University of Petroleum, Beijing. I have interned at Alibaba, Baidu and Huawei, and have published more than ten peer-reviewed papers in top conferences and journals.

My research interests include game theory, mechanism design, machine learning, reinforcement learning, and large language models.
I have published more than ten academic papers, with all citation data tracked via my Google Scholar page:
<a href='https://scholar.google.com/citations?user=lOuChXsAAAAJ'>google scholar homepage</a>
<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Completed my Ph.D. study at Renmin University of China.

# 📝 Publications 

## 2026
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JCSS 2026</div><img src='images/JCSS.png' alt="JCSS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Near-optimal algorithm for supporting small and medium-sized enterprises in ad systems](https://doi.org/10.1016/j.jcss.2026.103783)

Weian Li, Qi Qi, **Bingzhe Wang**, Tao Xiao, Changyuan Yu

*Journal of Computer and System Sciences, 159: 103783, 2026 (CCF B)*
<span class='show_paper_citations' data=''></span>
- Abstract: In this paper, we introduce an online decision model, effectively capturing the features of real-time support in online advertising. We target small and medium-sized enterprise (SME) advertisers, who lack opportunities for exposure, and consider how to provide additional support for them to acquire advertising slots. This paper investigates two settings, single slot and multiple slots. In both scenarios, our objective is to design online support algorithms that maximize the cumulative utility of SMEs across multiple rounds within the fixed support budget. Technically, we propose a dual-based online algorithm that contains deterministic rules for selecting support targets and allocating subsidies, achieving a competitive ratio of 1 − O(ε) for both settings within the random permutation model. Especially, in the single-slot setting, we propose tailored support policies for each advertiser.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCS 2026</div><img src='images/TCS.png' alt="TCS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Non-myopic Bidders in EIP-1559](https://doi.org/10.1016/j.tcs.2026.116175)

Yiming Ding, Qi Qi, **Bingzhe Wang**

*Theoretical Computer Science, 1084: 116175, 2026 (CCF B)*
<span class='show_paper_citations' data=''></span>
- Abstract: This paper presents a rigorous analytical framework for strategic transaction submission in Ethereum's EIP-1559 fee market, focusing on non-myopic users who optimize costs over finite planning horizons. Departing from the standard assumption of myopic bidding, we formalize the dynamic decision-making process where agents face hybrid uncertainties arising from stochastic block intervals and deterministic fee adjustments. We model the system evolution as a semi-Markov process (sMP) and formulate the optimal bidding strategy as a finite-horizon optimal stopping problem. By establishing a structural equivalence between this stopping problem and a semi-Markov Decision Process (sMDP), we prove the existence of deterministic stationary optimal policies and characterize the value function as the minimal solution to a recursive optimality equation. Furthermore, we construct a computationally efficient value iteration algorithm to compute ε-optimal stopping times.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/SACO.jpg' alt="SACO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SACO: Sequence-Aware Constrained Optimization Framework for Coupon Distribution in E-commerce](https://ojs.aaai.org/index.php/AAAI/article/view/38525)

Li Kong, **Bingzhe Wang**, Zhou Chen, Suhan Hu, Yuchao Ma, Qi Qi, Suoyuan Song, Bicheng Jin

*AAAI 2026, pp.15027-15035 (CCF A)*
<span class='show_paper_citations' data=''></span>
- Abstract: Coupon distribution is a critical marketing strategy used by online platforms to boost revenue and enhance user engagement. Regrettably, existing coupon distribution strategies fall far short of effectively leveraging the complex sequential interactions between platforms and users. This critical oversight, despite the abundance of e-commerce log data, has precipitated a performance plateau. In this paper, we focus on the scene that the platforms make sequential coupon distribution decision multiple times for various users, with each user interacting with the platform repeatedly. Based on this marketing scenario, we propose a novel marketing framework, named Sequence-Aware Constrained Optimization (SACO) framework, to directly devise coupon distribution policy for long-term revenue boosting. SACO framework enables optimized online decision-making in a variety of real-world marketing scenarios. It achieves this by seamlessly integrating three key characteristics, general scenarios, sequential modeling with more comprehensive historical data, and efficient iterative updates within a unified framework. Furthermore, empirical results on real-world industrial dataset, alongside public and synthetic datasets demonstrate the superiority of our framework.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/BwEK.png' alt="BwEK" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Marketing Hosting: From Fixed to Endogenous Budgets](https://dl.acm.org/doi/epdf/10.1145/3774904.3792519)

**Bingzhe Wang**, Tianyu Wang, Qi Qi, Xiaoxuan Deng, Zhilin Zhang, Chuan Yu

*WWW 2026, pp.327-338 (CCF A)*
<span class='show_paper_citations' data=''></span>
- Abstract: The canonical model for multi-channel marketing, Bandits with Knapsacks (BwK), optimizes cumulative rewards subject to resource constraints but typically assumes a fixed, exogenous budget. This assumption is tenuous in real-world systems requiring performance-adaptive investment, where pre-committing to a budget is challenging and suboptimal. We introduce Marketing Hosting, a paradigm modeling the budget as an endogenous, performance-dependent variable. This yields a new problem class, Bandits with Endogenous Knapsacks (BwEK), characterized by a challenging feedback loop coupling rewards with constraints. We develop a specialized primal-dual algorithm to manage this coupling. For settings with hard, per-round constraints, we design a novel risk-aware algorithm that mitigates the path-dependent risk of ruin, providing the first high-probability safety guarantee for such problems. Finally, we solve the strategic bi-level problem of learning the optimal reinvestment rate. We validate our theoretical results through extensive simulations, real-world data experiments, and a live A/B test.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/GAM.png' alt="GAM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GAM: A Generative Auto-Marketing Framework in Online E-commerce Platforms](https://dl.acm.org/doi/epdf/10.1145/3774904.3792805)

Yuejia Dou, Shuai Dou, Yuchao Ma, **Bingzhe Wang**, Tianyu Wang, Zhilin Zhang, Chuan Yu, Jian Xu, Qi Qi

*WWW 2026, pp.7979-7988 (CCF A)*
<span class='show_paper_citations' data=''></span>
- Abstract: Auto-bidding plays an essential role in online advertising, allowing agents to automatically adjust bids for advertisers. Recently, the rise of Marketing Management service in e-commerce platforms has driven the evolution from auto-bidding to auto-marketing, enabling merchants to delegate their advertising bidding and product's coupon discounting decisions to agents. Auto-marketing requires agents to jointly decide on bidding and coupon discounting. Furthermore, compared to classic static constraints, auto-marketing agent faces a self-funding constraint (where the budget for both bidding and coupon discounting is entirely derived from the agent's commission revenue). Existing rule-based or RL-based methods often struggle with dynamic environments and complex sequential dependencies. To overcome these limitations, we propose a Generative Auto-Marketing framework (GAM), designed for performing joint sequential decisions on bidding and coupon discounting, and optimizing business objectives through post-training alignment. Furthermore, GAM employs a flexible, constraint-aware reward alignment module, and utilizes Group Relative Policy Optimization (GRPO) to align the pre-trained model, thus empirically balancing objective maximization and constraint satisfaction. We construct an offline simulation environment based on large-scale real-world dataset, and demonstrate the effectiveness of GAM through extensive experimental results.
</div>
</div>

## 2025
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/GenAuction.jpg' alt="GenAuction" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GenAuction: A Generative Auction for Online Advertising](https://ojs.aaai.org/index.php/AAAI/article/view/33348)

Yuchao Ma, Ruohan Qian, **Bingzhe Wang**, Qi Qi, Wenqiang Liu, Qian Tang, Zhao Shen, Wei Zhong, Bo Shen, Yixin Su, Bin Zou, Wen Yi, Zhi Guo, Shuanglong Li, Lin Liu

*AAAI 2025, pp.12372-12380 (CCF A)*
<span class='show_paper_citations' data=''></span>
- Abstract: Previous ad auctions predominantly relied on rule-based mechanisms, which selected winning advertisements (ads) at the ad-level and subsequently combined them into page views (PVs), leading to suboptimal allocations in multi-round auctions. This limitation stems from the significant computational burden required to design ranking score rules and select winning ad sets, as well as the inability to fully capture contextual information within PVs during ad-level selection. In this paper, we propose a key-performance-indicator (KPI) based auction mechanism that selects winning PVs at the PV-level, modeling the ad allocation as a constrained optimization problem. This approach enables us to address both short-term and long-term KPIs while leveraging the comprehensive contextual information available within PVs. Based on this framework, we design GenAuction, a generative auction mechanism utilizing a Generator-Evaluator architecture powered by Transformer algorithms. The Generator swiftly generates multiple candidate PVs, while the Evaluator selects the optimal PVs based on contextual information, adhering to the objectives and KPIs of multi-round auctions. We conduct extensive experiments using real-world data and online A/B tests to validate that GenAuction efficiently handles multi-objective allocation tasks, demonstrating its efficacy and potential for real-world application.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TAMC 2025</div><img src='images/TAMC.png' alt="TAMC" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Strategies for Non-myopic Users in EIP-1559](https://link.springer.com/chapter/10.1007/978-981-95-4839-2_5)

Yiming Ding, Qi Qi, **Bingzhe Wang**

*TAMC 2025, pp.51-62*
<span class='show_paper_citations' data=''></span>
- Abstract: This paper analyzes strategic transaction submission behavior in Ethereum's EIP-1559, focusing on non-myopic users who optimize costs over finite horizons. While prior work assumes myopic users who schedule their transactions in the immediate block, we formalize the dynamic decision-making of non-myopic bidders facing stochastic base fee adjustments, variable block capacities, and transaction deferral risks. We model the evolving base fee and user interactions as a semi-Markov process (sMP) and frame the optimal bidding strategy as a finite-horizon optimal stopping problem. By establishing equivalence to a semi-Markov decision process (sMDP), we prove the existence of deterministic stationary optimal policies and characterize the value function as the minimal solution to a recursive optimality equation. A value iteration algorithm is proposed to compute ε-optimal stopping policies, with explicit convergence bounds dependent on the semi-Markov kernel's properties.
</div>
</div>

- [ADT4Coupons: An Innovative Framework for Sequential Coupon Distribution in E-commerce](https://arxiv.org/abs/2508.09198), Li Kong, Bingzhe Wang, Zhou Chen, Suhan Hu, Yuchao Ma, Qi Qi, Suoyuan Song, Bicheng Jin, arXiv preprint abs/2508.09198, 2025

## 2024
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COCOON 2024</div><img src='images/COCOON.png' alt="COCOON" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Near-Optimal Algorithm for Supporting Small and Medium-Sized Enterprises in Ad Systems](https://link.springer.com/chapter/10.1007/978-981-96-1090-7_21)

Weian Li, Qi Qi, **Bingzhe Wang**, Tao Xiao, Changyuan Yu

*COCOON 2024, pp.252-263 (CCF B)*
<span class='show_paper_citations' data=''></span>
- Abstract: In this paper, we introduce an online decision model, effectively capturing the features of real-time support in online advertising. We target small and medium-sized enterprise (SME) advertisers, who lack opportunities for exposure, and consider how to provide additional support for them to acquire advertising slots. This paper investigates two settings, single slot and multiple slots. In both scenarios, our objective is to design online support algorithms that maximize the cumulative utility of SMEs across multiple rounds within the fixed support budget. Technically, we propose a dual-based online algorithm that contains deterministic rules for selecting targets and allocating subsidies, achieving a competitive ratio of 1 − O(√(log n / n)) for both settings. Especially, in the single-slot setting, we propose tailored support policies for each advertiser.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2024</div><img src='images/JRegNet.png' alt="JRegNet" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Joint Auction in the Online Advertising Market](https://dl.acm.org/doi/epdf/10.1145/3637528.3671746)

Zhen Zhang, Weian Li, Yahui Lei, **Bingzhe Wang**, Zhicheng Zhang, Qi Qi, Qiang Liu, Xingxing Wang

*KDD 2024, pp.4362-4373 (CCF A)*
<span class='show_paper_citations' data='lOuChXsAAAAJ:u5HHmVD_uO8C'></span>
- Abstract: Online advertising is a primary source of income for e-commerce platforms. In the current advertising pattern, the oriented targets are the online store owners who are willing to pay extra fees to enhance the position of their stores. On the other hand, brand suppliers are also desirable to advertise their products in stores to boost brand sales. However, the currently used advertising mode cannot satisfy the demand of both stores and brand suppliers simultaneously. To address this, we innovatively propose a joint advertising model termed "Joint Auction", allowing brand suppliers and stores to collaboratively bid for advertising slots, catering to both their needs. However, conventional advertising auction mechanisms are not suitable for this novel scenario. In this paper, we propose JRegNet, a neural network architecture for the optimal joint auction design, to generate mechanisms that can achieve the optimal revenue and guarantee (near-)dominant strategy incentive compatibility and individual rationality. Finally, multiple experiments are conducted on synthetic and real data to demonstrate that our proposed joint auction significantly improves platform's revenue compared to the known baselines.
</div>
</div>

- [Joint Auction in the Online Advertising Market](https://arxiv.org/abs/2408.09885), Zhen Zhang, Weian Li, Yahui Lei, Bingzhe Wang, Zhicheng Zhang, Qi Qi, Qiang Liu, Xingxing Wang, arXiv preprint abs/2408.09885, 2024
- [IC Mechanisms for Risk-Averse Advertisers in the Online Advertising System](https://arxiv.org/abs/2411.13162), Bingzhe Wang, Ruohan Qian, Yuejia Dou, Qi Qi, Bo Shen, Changyuan Li, Yixuan Zhang, Yixin Su, Xin Yuan, Wenqiang Liu, Bin Zou, Wen Yi, Zhi Guo, Shuanglong Li, Liu Lin, arXiv preprint abs/2411.13162, 2024

## 2021
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AMC 2021</div><img src='images/QFOGDM.png' alt="QFOGDM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A quasi fractional order gradient descent method with adaptive stepsize and its application in system identification](https://doi.org/10.1016/j.amc.2020.125797)

Jianjun Liu, Rui Zhai, Yuhan Liu, Wenliang Li, **Bingzhe Wang**, Liyuan Huang

*Applied Mathematics and Computation, 393: 125797, 2021*
<span class='show_paper_citations' data=''></span>
- Abstract: In this paper, the fractional order gradient method (FOGM) is extended to the solution of high-dimensional function optimization problems. A quasi fractional order gradient descent method (QFOGDM) is proposed and then introduce an adaptive stepsize into QFOGDM. The theoretic analysis for convergence of QFOGDM is be done by three theorems. The numerical experiments for solving 15 unconstrained optimization benchmarks are compared to show its' better performance. Meanwhile, the proposed algorithm is utilized to identify the parameters in the linear discrete deterministic systems and achieves a better convergence rate and accuracy.
</div>
</div>

# 🎖 Honors and Awards


# 📖 Educations
- *2022.09 - 2026.06*, Ph.D. in Artificial Intelligence, Gaoling School of Artificial Intelligence, Renmin University of China
- *2019.09 - 2022.06*, M.S. in Mathematics, College of Science, China University of Petroleum, Beijing
- *2015.09 - 2019.06*, B.S. in Mathematics and Applied Mathematics, College of Science, China University of Petroleum, Beijing

# 💬 Invited Talks
- *2024*, Presentation of paper *Near-optimal algorithm for supporting small and medium-sized enterprises in ad systems*, COCOON 2024
- *2025*, Presentation of paper *Strategies for Non-myopic Users in EIP-1559*, TAMC 2025
- *2026*, Presentation of paper "Autobidding Auctions with LLM-Powered Creatives" at ICML 2026  \| [\[slides recording\]](https://icml.cc/virtual/2026/poster/65017)
- *2026*, Presentation of paper *EPMD: A Framework for LLM-Enhanced Ad Auctions*, KDD 2026
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- Alibaba, Research Intern
- Baidu, Research Intern
- Huawei, Research Intern
