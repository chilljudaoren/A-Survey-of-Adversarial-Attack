<h1 align="center">🤗🤗 Awesome VLMs Safety 🤗🤗</h1>

<p align="center">
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome Badge"></a>
    <img src="https://badges.toozhao.com/badges/01JM4JCV43N3ARA3BC25QSBH0S/blue.svg" alt="Custom Badge" />
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg" alt="License Badge"></a>
    <a href="https://github.com/XuankunRong/Awesome-LVLM-Safety"><img src="https://img.shields.io/github/stars/XuankunRong/Awesome-LVLM-Safety?style=social" alt="GitHub stars"></a>
</p>

⚠️ **This repository is currently under construction.**

![awesome](https://github.com/chilljudaoren/A-Survey-of-Adversarial-Attack/blob/main/images/overview.png)
This is the repository of <b><q>Adversarial Attacks on Vision-Language Multimodal Systems: A Survey</q></b>, a systematic survey of VLM adversarial attack studies in various adversarial attacks including Adversarial Jailbreak Attack, Adversarail Prompt Attack, Knowledge-based Adversarial Attack, etc. For details, please refer to:

<h2> 🙌 Abstract </h2>

With the boom of artificial intelligence, multimodal deep learning, especially vision-language multimodal systems (VLMS), has advanced remarkably and found wide applications. However, their adversarial security issues hamper further development. This paper comprehensively reviews adversarial attacks on VLMS. It first details multimodal deep-learning key technologies and the features of relevant models. Then, it deeply analyzes the adversarial vulnerabilities of VLMS. Next, it systematically reviews various adversarial attack methods in multimodal systems, covering task-specific attacks and attacks on different models, with a detailed analysis of their principles, implementations, and effects. Finally, it looks ahead to the future of multimodal adversarial attacks, suggesting research directions like improving attack universality and black-box attack capabilities. This review offers technical references, promotes research on multimodal adversarial attacks, and helps enhance VLMS security for reliable real-world applications.    

<h2> 📜 Table of Contents </h2>

- [News](#News)
- [Awesome Papers](#awesome-papers)
  - [Adversarial Attack on VLP models](#VLP)
  - [Adversarial Attack on MLLMs](#MLLM)

<h2 id="News"> 🔥 News </h2>

‼️ **We plan to update the arXiv version of our survey paper soon. If your paper is missing from this repository, feel free to contact us or open an issue!**

<h2 id="awesome-papers"> 👀 Awesome Papers </h2>

<h3 id="VLP"> 👑 Adversarial Attack on VLP models </h3>

#### Example-Specific Adversarial Attack on VLP Models
* [ACM MM 2022] Towards Adversarial Attack on Vision-Language Pre-training
 Models [[Paper](https://arxiv.org/pdf/2206.09391)][[Code](https://github.com/adversarial-for-goodness/Co-Attack)]
* [NeurIPS 2023] VLATTACK: Multimodal Adversarial Attacks on
 Vision-Language Tasks via Pre-trained Models [[Paper](https://arxiv.org/pdf/2310.04655)][[Code](https://github.com/ericyinyzy/VLAttack)]
* [ICCV 2023] Set-level Guidance Attack: Boosting Adversarial Transferability of
 Vision-Language Pre-training Models [[Paper](https://arxiv.org/pdf/2307.14061)][[Code](https://github.com/Zoky-2020/SGA)]
* [arXiv 2023] SA-Attack: Improving Adversarial Transferability of Vision-Language Pre-training Models via Self-Augmentation [[Paper](https://arxiv.org/pdf/2312.04913)][[Code](https://github.com/NY1024/Foundation-Model-Paper-Notes/blob/master/vlm-attack/sa-attack-improving-adversarial-transferability-of-vision-language-pretraining-models-via-self-au.md)]
* [arXiv 2023] OT-Attack: Enhancing Adversarial Transferability of Vision-Language Models via Optimal Transport Optimization [[Paper](https://arxiv.org/pdf/2312.04403)]
* [arXiv 2023] Exploring Transferability of Multimodal Adversarial Samples for Vision-Language Pre-training Models with Contrastive Learning [[Paper](https://arxiv.org/pdf/2308.12636)]
* [arXiv 2023] Improving Adversarial Transferability of Vision-Language Pre-training Models through Collaborative Multimodal Interaction [[Paper](https://arxiv.org/pdf/2403.10883)]
* [SP 2024] Transferable Multimodal Attack on Vision-Language Pre-training Models [[Paper](https://ieeexplore.ieee.org/abstract/document/10646738)][[Code](https://github.com/whdii/TMM)]
* [ECCV 2024] Boosting Transferability in Vision-Language Attacks via Diversification along the Intersection Region of Adversarial Trajectory [[Paper](https://arxiv.org/pdf/2403.12445)][[Code](https://github.com/SensenGao/VLPTransferAttack)]
* [arXiv 2024] Semantic-Aligned Adversarial Evolution Triangle for High-Transferability Vision-Language Attack [[Paper](https://arxiv.org/pdf/2411.02669)][[Code](https://github.com/jiaxiaojunQAQ/SA-AET)]
* [ICLR Workshop 2025] BOOSTING ADVERSARIAL ROBUSTNESS OF VISION LANGUAGE PRE-TRAINING MODELS AGAINST MULTI-MODAL ADVERSARIAL ATTACKS [[Paper](https://openreview.net/pdf?id=9obhyu9csa)]
* [arXiv 2025] Adversarial Attacks against Closed-Source MLLMs via Feature Optimal Alignment [[Paper](https://arxiv.org/pdf/2505.21494)][[Code](https://github.com/jiaxiaojunQAQ/FOA-Attack)]
* [arXiv 2025] A Frustratingly Simple Yet Highly Effective Attack Baseline: Over 90% Success Rate Against the Strong Black-box Models of GPT-4.5/4o/o1 [[Paper](https://arxiv.org/pdf/2503.10635?)][[Code](https://github.com/VILA-Lab/M-Attack)]

#### Example-Agnostic Adversarial Attack on VLP Models
* [ACM MM 2023] AdvCLIP: Downstream-agnostic Adversarial Examples in
 Multimodal Contrastive Learning [[Paper](https://arxiv.org/pdf/2308.07026)][[Code](https://github.com/CGCL-codes/AdvCLIP)]
* [ACM MM 2024] Sample-agnostic Adversarial Perturbation for Vision-Language Pre-training Models [[Paper](https://arxiv.org/pdf/2408.02980)][[Code](https://github.com/LibertazZ/MUAP)]
* [SIGIR 2024] Universal Adversarial Perturbations for Vision-Language Pre-trained Models [[Paper](https://arxiv.org/pdf/2405.05524)][[Code](https://github.com/sduzpf/UAP_VLP)]
* [arXiv 2024] One Perturbation is Enough: On Generating Universal Adversarial Perturbations against Vision-Language Pre-training Models [[Paper](https://arxiv.org/pdf/2406.05491)][[Code](https://github.com/ffhibnese/CPGC_VLP_Universal_Attacks)]
* [arXiv 2024] Efficient and Effective Universal Adversarial Attack against Vision-Language Pre-training Models [[Paper](https://arxiv.org/pdf/2410.11639)]
* [AAAI 2024] VQAttack: Transferable Adversarial Attacks on Visual Question Answering via Pre-trained Models [[Paper](https://arxiv.org/pdf/2402.11083)][[Code](https://github.com/ericyinyzy/VQAttack)]
* [ACM MM 2024] A Unified Understanding of Adversarial Vulnerability Regarding Unimodal Models and Vision-Language Pre-training Models [[Paper](https://arxiv.org/pdf/2407.17797)]
* [arXiv 2024] Doubly-Universal Adversarial Perturbations: Deceiving Vision-Language Models Across Both Images and Text with a Single Perturbation [[Paper](https://arxiv.org/pdf/2412.08108)]

<h3 id="MLLM"> 👑 Adversarial Attack on MLLMs </h3>

#### Traditional Adversarial Attack on MLLMs
* [ICCV 2023] On the adversarial robustness of multi-modal foundation models [[Paper](https://openaccess.thecvf.com/content/ICCV2023W/AROW/papers/Schlarmann_On_the_Adversarial_Robustness_of_Multi-Modal_Foundation_Models_ICCVW_2023_paper.pdf)]
* [arXiv 2023] InstructTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models [[Paper](https://arxiv.org/pdf/2312.01886)][[Code](https://github.com/xunguangwang/InstructTA)]
* [NeurIPS Workshop 2023] How Robust is Google’s Bard to Adversarial Image Attacks? [[Paper](https://arxiv.org/pdf/2309.11751)][[Code](https://github.com/thu-ml/Attack-Bard)]
* [EMNLP 2023] Sparse Black-Box Multimodal Attack for Vision-Language Adversary Generation [[Paper](https://aclanthology.org/2023.findings-emnlp.384.pdf)][[Code](https://github.com/JHL-HUST/SparseMA)]
* [NeurIPS 2023] OnEvaluating Adversarial Robustness of Large Vision-Language Models [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/a97b58c4f7551053b0512f92244b0810-Paper-Conference.pdf)][[Code](https://github.com/rain305f/AttackVLM_base)]
* [ICLR 2024] AN IMAGE IS WORTH 1000 LIES: ADVERSARIAL TRANSFERABILITY ACROSS PROMPTS ON VISION LANGUAGE MODELS [[Paper](https://arxiv.org/pdf/2403.09766)][[Code](https://github.com/Haochen-Luo/CroPA)]
* [ICLR Workshop 2024]  ADVERSARIAL ROBUSTNESS FOR VISUAL GROUNDING OF MULTIMODAL LARGE LANGUAGE MODELS [[Paper](https://arxiv.org/pdf/2405.09981)][[Code](https://github.com/KuofengGao/MLLM-Grounding-Robustness)]
* [CVPR 2024] Onthe Robustness of Large Multimodal Models Against Image Adversarial Attacks [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Cui_On_the_Robustness_of_Large_Multimodal_Models_Against_Image_Adversarial_CVPR_2024_paper.pdf)][[Code](https://github.com/NY1024/Foundation-Model-Paper-Notes/blob/master/vlm-attack/on-the-robustness-of-large-multimodal-models-against-image-adversarial-attacks.md)]
* [COLM 2024] Stop Reasoning! When Multimodal LLM with Chain-of-Thought Reasoning Meets Adversarial Image [[Paper](https://arxiv.org/pdf/2402.14899)][[Code](https://github.com/aiPenguin/StopReasoning)]
* [TIFS 2024]  Efficient Generation of Targeted and Transferable Adversarial Examples for Vision-Language Models Via Diffusion Models [[Paper](https://arxiv.org/pdf/2404.10335)][[Code](https://arxiv.org/pdf/2404.10335)]
* [CVPR 2025] AnyAttack: Towards Large-scale Self-supervised Adversarial Attacks on Vision-language Models [[Paper](https://arxiv.org/pdf/2410.05346)][[Code](https://github.com/jiamingzhang94/AnyAttack)]
* [arXiv 2025] Improving Adversarial Transferability in MLLMs via Dynamic Vision-Language Alignment Attack [[Paper](https://arxiv.org/pdf/2502.19672?)]

#### Adversarial Jailbreak Attack
* [NeurIPS 2023] Are aligned neural networks adversarially aligned? [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/c1f0b856a35986348ab3414177266f75-Paper-Conference.pdf)][[Code](https://paperswithcode.com/paper/are-aligned-neural-networks-adversarially)]
* [arXiv 2023] Query-Relevant Images Jailbreak Large Multi-Modal Models[Paper][[Code](https://export.arxiv.org/pdf/2311.17600v1)][(https://github.com/isXinLiu/MM-SafetyBench)]
* [ICML 2024] White-box Multimodal Jailbreaks Against Large Vision-Language Models [[Paper](https://arxiv.org/pdf/2405.17894)][[Code](https://github.com/roywang021/UMK)]
* [arXiv 2024] Jailbreak Vision Language Models via Bi-Modal Adversarial Prompt [[Paper](https://arxiv.org/pdf/2406.04031)][[Code](https://github.com/NY1024/BAP-Jailbreak-Vision-Language-Models-via-Bi-Modal-Adversarial-Prompt)]
* [AAAI 2024] Visual Adversarial Examples Jailbreak Aligned Large Language Models [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30150/32038)][[Code](https://github.com/unispac/visual-adversarial-examples-jailbreak-large-language-models)]
* [arXiv 2024] IDEATOR: Jailbreaking and Benchmarking Large Vision-Language Models Using Themselves [[Paper](https://arxiv.org/pdf/2411.00827)][[Code](https://github.com/roywang021/IDEATOR)]
* [ICLR 2024] JAILBREAK IN PIECES: COMPOSITIONAL ADVERSARIAL ATTACKS ON MULTI-MODAL LANGUAGE MODELS [[Paper](https://arxiv.org/pdf/2307.14539)][[Code](https://github.com/erfanshayegani/Jailbreak-In-Pieces)]
* [ACM MM 2024] White-box multimodal jailbreaks against large vision-language models [[Paper](https://arxiv.org/pdf/2405.17894)][[Code](https://github.com/roywang021/UMK.)]
* [ECCV 2024] Images are achilles' heel of alignment: Exploiting visual vulnerabilities for jailbreaking multimodal large language models [[Paper](https://arxiv.org/pdf/2403.09792)][[Code](https://github.com/RUCAIBox/HADES)]
* [ECCV Oral 2024]  Images are achilles’ heel of alignment: Exploiting visual vulnerabilities for jailbreaking multimodal large language models. [[Paper](https://arxiv.org/pdf/2403.09792)][[Code](https://github.com/RUCAIBox/HADES)]
* [ECCV 2024] MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models [[Paper](https://arxiv.org/pdf/2311.17600)][[Code](https://github.com/isXinLiu/MM-SafetyBench)]
* [arXiv 2025] Universal Adversarial Attack on Multimodal Aligned LLMs [[Paper](https://arxiv.org/pdf/2502.07987)]
* [TCSVT 2025] Align is not Enough: Multimodal Universal Jailbreak Attack against Multimodal Large Language Models [[Paper](https://arxiv.org/pdf/2506.01307?)]
* [AAAI 2025] FigStep: Jailbreaking Large Vision-Language Models via Typographic Visual Prompts [[Paper](https://www.overleaf.com/project/67e268fac5f1645b8a867f1c#cite.gong2023figstep)][[Code](https://github.com/thuccslab/figstep)]
* [arXiv 2025] Exploring Visual Vulnerabilities via Multi-Loss Adversarial Search for Jailbreaking Vision-Language Models [[Paper](https://arxiv.org/abs/2411.18000)]
* [CVPR 2025]  Distraction is All You Need for Multimodal Large Language Model Jailbreaking [[Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Yang_Distraction_is_All_You_Need_for_Multimodal_Large_Language_Model_CVPR_2025_paper.pdf)][[Code](https://github.com/TeamPigeonLab/CS-DJ)]

#### Adversarial Prompt Attack
* [arXiv 2023] Abusing Images and Sounds for Indirect Instruction Injection in Multi-Modal LLMs[[Paper](https://arxiv.org/pdf/2307.10490)][[Code](https://github.com/ebagdasa/multimodal_injection)]
* [arXiv 2023] Jailbreaking GPT-4V via Self-Adversarial Attacks with System Prompts [[Paper](https://arxiv.org/pdf/2311.09127)][[Code](https://github.com/NY1024/Foundation-Model-Paper-Notes/blob/master/vlm-attack/jailbreaking-gpt-4v-via-self-adversarial-attacks-with-system-prompts.md)]
* [arXiv 2024] Vision-LLMs Can Fool Themselves with Self-Generated Typographic Attacks [[Paper](https://arxiv.org/pdf/2402.00626)][[Code](https://github.com/mqraitem/Self-Gen-Typo-Attack)]

<h2 id="contact"> 🎉 Contact </h2>

This repository is currently maintained by [Zhihao Chen](https://github.com/chilljudaoren) 👨‍💻. If you have any questions, concerns, or suggestions regarding the contents of this repository or the resources shared here, feel free to reach out! I'm more than happy to assist you with any inquiries or help you navigate through the materials. Please don't hesitate to send an email to me at [daorenju9911@zust.edu.cn](daorenju9911@zust.edu.cn) 📧, and I will get back to you as soon as possible. Let's keep improving the **A-Survey-of-Adversarial-Attack** community together! 🏁

Looking forward to hearing from you! 😄


