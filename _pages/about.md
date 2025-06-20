---
permalink: /
title: ""
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

**Hi!** I am currently a PhD student in the Department of Computer Science of [Duke University](https://duke.edu/), and a member of [Computational Evolutionary Intelligence (CEI) Lab](https://cei.pratt.duke.edu/) under the supervision of [Prof. Hai "Helen" Li](https://ece.duke.edu/people/hai-helen-li/) and [Prof. Yiran Chen](https://cei.pratt.duke.edu/people/yiran-chen). Before joining Duke University, I received my M.S. degree from [Peking University (北京大学)](https://english.pku.edu.cn/) in 2024, under the supervision of [Prof. Hailong Jiao](https://www.ece.pku.edu.cn/en/info/1095/1323.htm). I obtained my BEng degree from [Southern University of Science and Technology (南方科技大学)](https://www.sustech.edu.cn/en/) in 2021, advised by [Prof. Fengwei An](https://faculty.sustech.edu.cn/anfw/en/). For now, my research realm focuses on **algorithm-hardware co-design**. Please don't hesitate to reach out if you have any questions or interests🍀.

E-mail: yuzhe.fu@duke.edu

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->
 
# 📖 Educations
- *2024.08 - Present*, PhD student in the department of Computer Science, Duke University.
- *2021.09 - 2024.07*, Master of Science, Peking University.
- *2017.09 - 2021.06*, Bachelor of Engineering, Southern University of Science and Technology.
- *2019.08 - 2019.12*, Global Access Program, University of California, Berkeley. 

# 🔥 News
- *2025.06*: &nbsp;(PhD Journey) Finish my Reasearch Initial Project Defense ✅, which is the first milestone in my PhD journey!
- *2025.03*: &nbsp;(Paper)🎉🎉 "[SpeechPrune](https://speechprune.github.io/): Context-aware Token Pruning for Speech Information Retrieval" has been accepted by IEEE ICME! In this work, we proposed a new dataset for long speech information retrieval task in LLM, alone with an training-free pruning strategy for this task.
- *2025.02*: &nbsp;**(Best Paper Award)** 🎉🎉 "[GenAI at the Edge](https://arxiv.org/pdf/2502.15816): Comprehensive Survey on Empowering Edge Devices" has been accepted by AAAI SSS! In this work, I provide an overview of recent well-known architectures and chip works for LLMs and diffusion networks. I hope you find it insightful and helpful!
<!-- - *2024.10*: &nbsp;(Paper)🎉🎉 "[Nebula](https://ieeexplore.ieee.org/abstract/document/10904703?casa_token=z0z_h4_dJHgAAAAA:24_jLlNXCrjlmBK57nut2rHdoUI_62Zh22gIqqevu32hGtFOewRoV5aSN4LtVdAJD60rZu8stw): A 28-nm 109.8 TOPS/W 3D PNN Accelerator Featuring Adaptive Partition, Multi-Skipping, and Block-Wise Aggregation" has been accepted by IEEE ISSCC! -->
- *2024.08*: &nbsp;(PhD Journey) Starting my PhD journey — wish me luck🍀!
- *2024.04*: &nbsp;(Paper)🎉🎉 "[SoftAct](https://ieeexplore.ieee.org/document/10495359): A High-Precision Softmax Architecture for Transformers with Nonlinear Functions Support" has been accepted by IEEE TCSVT!
- *2024.02*: &nbsp;(Paper)🎉🎉 "[Adjustable Multi-Stream Block-Wise Farthest Point Sampling](https://ieeexplore.ieee.org/document/10430381) Acceleration in Point Cloud Analysis" has been accepted by IEEE TCAS-II!
- *2023.08*: &nbsp;(Paper)🎉🎉 "Sagitta: An Energy-Efficient Sparse 3D-CNN Accelerator for Real-Time 3D Understanding" has been accepted by IEEE IOTJ!
- *2023.07*: &nbsp;(Paper)🎉🎉 "An Energy-Efficient 3D Point Cloud Neural Network Accelerator with Efficient Filter Pruning, MLP Fusion, and Dual-Stream Sampling" has been accepted by IEEE/ACM ICCAD 2023!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME</div><img src='images/SpeechPrune.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SpeechPrune: Context-aware Token Pruning for Speech Information Retrieval](https://speechprune.github.io/)

Yueqian Lin#, **<u>Yuzhe Fu</u>**#, J. Zhang, Y. Liu, J. Zhang, J. Sun, Hai "Helen" Li, Yiran Chen.

**2025**, *IEEE International Conference on Multimedia & Expo* (# with equal contribution)

Oral, Top 15% in all submissions

[[pdf](../papers/SpeechPrune.pdf)]
<details>
<summary>Abstract</summary>
While current Speech Large Language Models (Speech LLMs) excel at short-form tasks, they struggle with the computational and representational demands of longer audio clips. 
To advance the model's capabilities with long-form speech, we introduce Speech Information Retrieval (SIR), a long-context task for Speech LLMs, and present SPIRAL, a 1,012-sample benchmark testing models’ ability to extract critical details from long spoken inputs. 
To overcome the challenges of processing long speech sequences, we propose SpeechPrune, a training-free token pruning strategy that uses speech-text similarity and approximated attention scores to efficiently discard irrelevant tokens. 
In SPIRAL, SpeechPrune achieves accuracy improvements of 29% and up to 47% over the original model and the random pruning model at a pruning rate of 20%, respectively. 
SpeechPrune can maintain network performance even at a pruning level of 80%. This highlights the potential of token-level pruning for efficient and scalable long-form speech understanding.
</details>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT</div><img src='images/SoftAct.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoftAct: A High-Precision Softmax Architecture for Transformers Supporting Nonlinear Functions](https://ieeexplore.ieee.org/document/10495359)

**<u>Yuzhe Fu</u>**, C. Zhou, T. Huang, E. Han, Y. He, Hailong Jiao.

**2024**, *IEEE Transactions on Circuits and Systems for Video Technology*

[[pdf](../papers/TCSVT.pdf)]
<details>
<summary>Abstract</summary>
  Transformer-based deep learning networks are revolutionizing our society. The convolution and attention co-designed (CAC) Transformers have demonstrated superior performance compared to the conventional Transformer-based networks. However, CAC Transformer networks contain various nonlinear functions, such as softmax and complex activation functions, which require high precision hardware design yet typically with significant cost in area and power consumption. To address these challenges, SoftAct, a compact and high-precision algorithm-hardware co-designed architecture, is proposed to implement both softmax and nonlinear activation functions in CAC Transformer accelerators. An improved softmax algorithm with penalties is proposed to maintain precision in hardware. A stage-wise full zero detection method is developed to skip redundant computation in softmax. A compact and reconfigurable architecture with a symmetrically designed linear fitting module is proposed to achieve nonlinear functions. The SoftAct architecture is designed in an industrial 28-nm CMOS technology with the MobileViT-xxs network as the benchmark. Compared with the state of the art, SoftAct improves up to 5.87% network accuracy, 153.2× area efficiency, and 1435× overall efficiency.
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-II</div><img src='images/TCASII.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adjustable Multi-Stream Block-Wise Farthest Point Sampling Acceleration in Point Cloud Analysis](https://ieeexplore.ieee.org/document/10430381)

Changchun Zhou#, **<u>Yuzhe Fu</u>**#, Y. Ma, E. Han, Y. He, Hailong Jiao.

**2024**, *IEEE Transactions on Circuits and Systems II: Express Briefs* (# with equal contribution)

[[pdf](../papers/TCAS-II.pdf)]
<details>
<summary>Abstract</summary>
  Point cloud is increasingly used in a variety of applications. Farthest Point Sampling (FPS) is typically employed for down-sampling to reduce the size of point cloud and enhance the representational capability by preserving contour points in point cloud analysis. However, due to low parallelism and high computational complexity, high energy consumption and long latency are caused, which becomes a bottleneck of hardware acceleration. In this brief, we propose an adjustable multi-stream block-wise FPS algorithm, adjusted by four configurable parameters, according to hardware and accuracy requirements. A unified hardware architecture with one parameter is designed to implement the adjustable multi-stream block-wise FPS algorithm. Furthermore, we present a rapid searching algorithm to select the optimal configuration of the five parameters. Designed in an industrial 28-nm CMOS technology, the proposed hardware architecture achieves a latency of 0.005 (1.401) ms and a frame energy consumption of 0.09 (27.265) µJ/frame for 1 k (24 k) input points at 200 MHz and 0.9 V supply voltage. Compared to the state of the art, the proposed hardware architecture reduces the latency by up to 99.9%, saves the energy consumption by up to 99.5%, and improves the network accuracy by up to 9.34%.
</details>
</div>
</div>


# 📝 Collaborative Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/AnglesDontLie.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Angles Don't Lie: Unlocking Training-Efficient RL Through the Model's Own Signals](https://arxiv.org/pdf/2506.02281)

Qinsi Wang, J. Ke, H. Ye, Y. Liu, **<u>Yuzhe Fu</u>**, J. Zhang, K. Keutzer, C. Xu, and Yiran Chen

**2025**, *ArXiv Preprint* [[codes](https://github.com/wangqinsi1/GAINRL/tree/main)]

<details>
<summary>Abstract</summary>
Current Reinforcement Fine-tuning (RFT) paradigms for Large Language Models (LLMs) suffer from sample inefficiency due to the redundant exposure of identical queries under uniform data sampling. While previous work has explored curriculum learning via heuristic difficulty metrics, these strategies exhibit limitations by neglecting the intrinsic learning signals generated by the model itself, thus leading to suboptimal training regimes. In this paper, we identify a model-inherent signal termed angle concentration that effectively reflects an LLM's capacity to learn from specific data. We theoretically and empirically demonstrate a correlation between the angular distribution of token hidden state vectors and the resulting gradient, revealing a learning preference for data exhibiting higher angle concentration. Inspired by this finding, we propose GAIN-RL, a Gradient-driven Angle-Informed Navigated RL framework. By leveraging the model's intrinsic angle concentration signal, GAIN-RL dynamically selects training data in each epoch, ensuring consistently impactful gradient updates and thus significantly enhancing overall training efficiency. Empirical evaluations show that GAIN-RL (GRPO) achieves over a 2.5× acceleration in training efficiency across diverse mathematical and coding tasks and varying model scales. Furthermore, GAIN-RL (GRPO)'s efficient sampling yields data-efficient training, achieving better performance with half the original data compared to vanilla GRPO with full training data. 
  
Code is realsed at https://github.com/wangqinsi1/GAINRL/tree/main.
</details>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/hipp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hippomm: Hippocampal-inspired multimodal memory for long audiovisual event understanding](https://arxiv.org/pdf/2504.10739)

Yueqian Lin, Q. Wang, H. Ye, **<u>Yuzhe Fu</u>**, Hai Li, and Yiran Chen

**2025**, *ArXiv Preprint* [[codes](https://github.com/linyueqian/HippoMM)]

<details>
<summary>Abstract</summary>
Comprehending extended audiovisual experiences remains a fundamental challenge for computational systems. Current approaches struggle with temporal integration and cross-modal associations that humans accomplish effortlessly through hippocampal-cortical networks. We introduce HippoMM, a biologically-inspired architecture that transforms hippocampal mechanisms into computational advantages for multimodal understanding. HippoMM implements three key innovations: (i) hippocampus-inspired pattern separation and completionspecifically designed for continuous audiovisual streams, (ii) short-to-long term memory consolidation that transforms perceptual details into semantic abstractions, and (iii) cross-modal associative retrieval pathways enabling modality-crossing queries. Unlike existing retrieval systems with static indexing schemes, HippoMM dynamically forms integrated episodic representations through adaptive temporal segmentation and dual-process memory encoding. Evaluations on our challenging HippoVlog benchmark demonstrate that HippoMM significantly outperforms state-of-the-art approaches (78.2% vs. 64.2% accuracy) while providing substantially faster response times (20.4s vs. 112.5s). Our results demonstrate that translating neuroscientific memory principles into computational architectures provides a promising foundation for next-generation multimodal understanding systems. 

The code and benchmark dataset are publicly available at https://github.com/linyueqian/HippoMM.
</details>
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/AAAI-SSS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[GenAI at the Edge: Comprehensive Survey on Empowering Edge Devices](https://arxiv.org/pdf/2502.15816)

M. Navardi, R. Aalishah, **<u>Yuzhe Fu</u>**, Y. Lin, Hai Li, Yiran Chen and Tinoosh Mohsenin

**Best Paper Award**🎉, **2025**, *AAAI Spring Symposium Series (AAAI SSS)*

<details>
<summary>Abstract</summary>
Generative Artificial Intelligence (GenAI) applies models and algorithms such as Large Language Model (LLM) and Foundation Model (FM) to generate new data. GenAI, as a promising approach, enables advanced capabilities in various applications, including text generation and image processing. In current practice, GenAI algorithms run mainly on the cloud server, leading to high latency and raising security concerns. Consequently, these challenges encourage the deployment of GenAI algorithms directly on edge devices. However, the large size of such models and their significant computational resource requirements pose obstacles when deploying them in resource-constrained systems. This survey provides a comprehensive overview of recent proposed techniques that optimize GenAI for efficient deployment on resource-constrained edge devices. For this aim, this work highlights three main categories for bringing GenAI to the edge: software optimization, hardware optimization, and frameworks. The main takeaways for readers of this survey will be a clear roadmap to design, implement, and refine GenAI systems for real-world implementation on edge devices.
</details>
</div>
</div>


<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISSCC</div><img src='images/ISSCC-chip.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Nebula: A 28-nm 109.8 TOPS/W 3D PNN Accelerator Featuring Adaptive Partition, Multi-Skipping, and Block-Wise Aggregation](https://ieeexplore.ieee.org/abstract/document/10904703?casa_token=z0z_h4_dJHgAAAAA:24_jLlNXCrjlmBK57nut2rHdoUI_62Zh22gIqqevu32hGtFOewRoV5aSN4LtVdAJD60rZu8stw)

Changchun Zhou, T. Huang, Y. Ma, **<u>Yuzhe Fu</u>**, S. Qiu, X. Song, J. Sun, M. Liu, Y. Yang, G. Li, Y. He, Hailong Jiao.

**2025**, *International Solid-State Circuits Conference (ISSCC)* 
<details>
<summary>Abstract</summary>
  Three-dimensional (3D) point clouds are increasingly deployed across various emerging fields, such as autonomous driving, robots, drones, and virtual reality (VR) [1]–[6]. Point-based point-cloud neural networks (PNNs) [3]–[6] have demonstrated superior performance in point-cloud analysis, compared to both sparse 3D convolution-based networks [7], [8] and graph-based convolutional neural networks [9], [10]. Due to the high computational complexity, low parallelism, and frequent irregular external memory accesses, deploying PNNs in hardware is a great challenge. PNN hardware accelerators have been developed [11]–[20]. However, three key challenges remain unsolved in these accelerators, as illustrated in Fig. 23.4.1. 1) The inherent farthest point sampling (FPS) features serial computation and suffers from quadratic growth in inference latency with rising point counts. The existing uniform block-wise FPS techniques [13], [21] fail to achieve a well-balanced block segmentation, due to a typically non-uniform point distribution. 2) A large amount of redundant operations exist for both discarded points (DPs) and retained points (RPs) in FPS. These operations exist in the sampling operations of RPs ① as well as grouping ② convolution ③, and aggregation ④ for DPs, introducing unnecessary energy and latency costs. 3) The irregular memory accesses in the aggregation operation cause significant latency penalties. Channel-wise aggregation in [11] relieves irregularity, yet is unsuitable for large-scale point clouds, as the external memory access of features and the neighbor index table (NIT) is quadratically increased due to the iterative loading of features or the NIT.
</details>
</div>
</div>
-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD</div><img src='images/ICCAD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Energy-Efficient 3D Point Cloud Neural Network Accelerator with Efficient Filter Pruning, MLP Fusion, and Dual-Stream Sampling](https://ieeexplore.ieee.org/document/10323704)

C. Zhou, **<u>Yuzhe Fu</u>**, M. Liu, S. Qiu, G. Li, Y, He, Hailong Jiao.

**2023**, *IEEE/ACM International Conference On Computer Aided Design*
[[pdf](../papers/ICCAD.pdf)][[YouTube](https://youtu.be/3Yw3-jFeRaE)]
<details>
<summary>Abstract</summary>
  Three-dimensional (3D) point cloud has been employed in a wide range of applications recently. As a powerful weapon for point cloud analysis, point-based point cloud neural networks (PNNs) have demonstrated superior performance with less computation complexity and parameters, compared to sparse 3D convolution-based networks and graph-based convolutional neural networks. However, point-based PNNs still suffer from high computational redundancy, large off-chip memory access, and low parallelism in hardware implementation, thereby hindering the applications on edge devices. In this paper, to address these challenges, an energy-efficient 3D point cloud neural network accelerator is proposed for on-chip edge computing. An efficient filter pruning scheme is used to skip the redundant convolution of pruned filters and zero-value feature channels. A block-wise multi-layer perceptron (MLP) fusion method is proposed to increase the on-chip reuse of features, thereby reducing off-chip memory access. A dual-stream blocking technique is proposed for higher parallelism while maintaining inference accuracy. Implemented in an industrial 28-nm CMOS technology, the proposed accelerator achieves an effective energy efficiency of 12.65 TOPS/W and 0.13 mJ/frame energy consumption for PointNeXt-S at 100 MHz, 0.9 V supply voltage, and 8-bit data width. Compared to the state-of-the-art point cloud neural network accelerators, the proposed accelerator enhances the energy efficiency by up to 66.6× and reduces the energy consumption per frame by up to 70.2×.
</details>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IOTJ</div><img src='images/IOTJ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sagitta: An Energy-Efficient Sparse 3D-CNN Accelerator for Real-Time 3D Understanding](https://ieeexplore.ieee.org/document/10224248)

C. Zhou, M. Liu, S. Qiu, X. Cao, **<u>Yuzhe Fu</u>**, Y. He, Hailong Jiao.

**2023**, *IEEE Internet of Things Journal*
[[pdf](../papers/Sagitta_An_Energy-Efficient_Sparse_3D-CNN_Accelerator_for_Real-Time_3-D_Understanding.pdf)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-I</div><img src='images/tcas-i.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A 4.29 nJ/pixel stereo depth coprocessor with pixel level pipeline and region optimized semi-global matching for IoT application](https://ieeexplore.ieee.org/abstract/document/9505253)

P. Dong, Z. Chen, Z. Li, **<u>Yuzhe Fu</u>**, L. Chen, Fengwei An.  

**2021**, *IEEE Transactions on Circuits and Systems I: Regular Papers*
[[pdf](../papers/A_4.29nJ_pixel_Stereo_Depth_Coprocessor_With_Pixel_Level_Pipeline_and_Region_Optimized_Semi-Global_Matching_for_IoT_Application.pdf)]

</div>
</div>

# 📃 Patent
- [A high-precision approximate calculation device for softmax function](https://patents.google.com/patent/CN118733946A/en), **2024**, *CN Patent*, CN118733946A.
- [Low-power-consumption stereo matching system and method for acquiring depth information](https://worldwide.espacenet.com/patent/search/family/073657313/publication/CN112070821A?q=CN112070821A), **2020**, *CN Patent*, CN112070821A / WO2022021912A1

# 💻 Reviewer
- TCSVT-IEEE Transactions on Circuits and Systems for Video Technology (2024)
- ELL-Electronics Letters (2022, 2025)
- AICAS-IEEE International Conference on Artificial Intelligence Circuits and Systems (2023, 2025)
- ICME-IEEE International Conference on Multimedia & Expo (2025)
- AVSS-IEEE International Conference on Advanced Visual and Signal-Based Systems (2025)

# 🍀 Tape Out
- An energy-efficient pipelined and configurable 3D point cloud-based neural network accelerator is being designed in TSMC 28-nm HPC technology with an area of 2.0 mm×1.5 mm and is taped out in July 2023.
- A 4.5 TOPS/W sparse 3D-CNN accelerator for real-time 3D understanding was fabricated in UMC 55-nm low-power CMOS technology with an area of 4.2 mm×3.6 mm in August 2020.

# 🎖 Honors and Awards
- *2025* Best Paper Award (2nd Place) in AAAI Spring Symposium Series.
- *2021* Excellent Graduate Award, Southern University of Science and Technology
- *2021* Best Presentation Award in IEEE CASS Shanghai and Shenzhen Joint Workshop 
- *2020* **National Scholarship**, Ministry of Education of the PRC (The highest scholarship for Chinese undergraduates)


# ![0D4D876E](https://github.com/Yuzhe-Fu/Yuzhe-Fu.github.io/assets/54790390/34cd68b3-1087-400d-9c3a-1ea97768f74c) About Me: 
- I am a easy-going and spirited individual with a passion for life. My enthusiasm not only drives my own life but also positively influences those around me.
- Interests and Hobbies: fitness, jogging, swimming, photography, traveling. (Here is a short [📸 video](https://www.bilibili.com/video/BV19q4y1H716/?vd_source=5c9e9ee79e4910700f06815b0fd41bf3) about my graduation trip in 2021.)


<!-- 

- *2018, 2019* The First Prize of Outstanding Students in SUSTech (**Top 5%** in SUSTech)

# 🚀 Skills
- Familiar with Verilog HDL, PyTorch, Intel Distiller (Model Compression), Cadence (Genus and NCSim), Vivado.
- Knowledgeable in Python, JAVA, MATLAB, Shell, Makefile.

# 🔥 News
- Proficient in digital integrated circuit (IC) front-end development, neural network model compression and FPGA development. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2020.07 - 2020.08*, algorithm-hardware development position, National Technology Company[nationstech](https://github.com/), China.
 -->
