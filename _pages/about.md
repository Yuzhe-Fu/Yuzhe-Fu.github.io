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

I am currently a Master student in the School of Electronic and Computer Engineering of [Peking University](https://english.pku.edu.cn/), [VLSI Lab](http://www.pku-vlsi.com/) under the supervision of [Prof. Hailong Jiao](https://www.ece.pku.edu.cn/en/info/1095/1323.htm). I obtained my BEng degree in Microelectronic Science and Engineering from [Southern University of Science and Technology](https://www.sustech.edu.cn/en/) in 2021, advised by [Prof. Fengwei An](https://faculty.sustech.edu.cn/anfw/en/). My research realm focuses on **algorithm-hardware co-design, AI chip design, and neural network compression**. You can find more information through my [CV](../images/CV.pdf). I am currently applying for a PhD position, and if you are interested in me, please feel free to contact me at any time.  
E-mail: yuzhefu113@gmail.com \| WeChat: UcheFu6666

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
 -->
 
# 📖 Educations
- *2021.09 - Present*, Master in School of Electronic and Computer Engineering, Peking University. **GPA: 3.59/4.00**
- *2019.08 - 2019.12*, Global Access Program, University of California, Berkeley. **GPA: 3.94/4.00**
- *2017.08 - 2021.06*, BEng in Microelectronics Science and Engineering, School of Microelectronics, Southern University of Science and Technology. **GPA: 3.88/4.00, 1st in comprehensive ranking**

# 🎖 Honors and Awards
- *2021* Excellent Graduate Award, Southern University of Science and Technology
- *2021* Best Presentation Award in IEEE CASS Shanghai and Shenzhen Joint Workshop 
- *2020* **China National Scholarship**, Ministry of Education of the PRC (**Top 8** in SUSTech)
- *2020* Shenzhen Longsys Electronics Company Award (**Top 2%** in School of Microelectronics)
- *2019* The First Prize of Outstanding Students in SUSTech (**Top 5%** in SUSTech)
- *2018* The First Class Scholarship, Southern University of Science and Technology (**Top 5%** in SUSTech)
- *2017* The Third Class Freshman Scholarship, Southern University of Science and Technology

# 🔥 News
- *2023.08*: &nbsp;🎉🎉 Our paper "Sagitta: An Energy-Efficient Sparse 3D-CNN Accelerator for Real-Time 3D Understanding" has been accepted by IEEE IOTJ!
- *2023.07*: &nbsp;🎉🎉 Our paper "An Energy-Efficient 3D Point Cloud Neural Network Accelerator with Efficient Filter Pruning, MLP Fusion, and Dual-Stream Sampling" has been accepted by IEEE/ACM ICCAD 2023!

# 📝 Publications 
- Working on: SoftAct: A High-Precision Softmax Architecture for Transformers with Nonlinear Functions Support. **Yuzhe Fu**, Changchun Zhou, Tianling Huang, Yifan He, Hailong Jiao. **2023**, *IEEE Transactions on Circuits and Systems I: Regular Papers* (plan to submit in September)
- Working on: An Adjustable Multi-Stream Block-Wise Farthest Point Sampling Acceleration Framework. **Yuzhe Fu**#, Changchun Zhou#, Hailong Jiao. **2023**, *IEEE Transactions on Circuits and Systems II: Express Briefs* (plan to submit in September)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCAD</div><img src='images/ICCAD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

An Energy-Efficient 3D Point Cloud Neural Network Accelerator with Efficient Filter Pruning, MLP Fusion, and Dual-Stream Sampling

Changchun Zhou, **Yuzhe Fu**, Min Liu, Siyuan Qiu, Ge Li, Yifan He, Hailong Jiao.

**2023**, *IEEE/ACM International Conference On Computer Aided Design* (Accepted)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IOTJ</div><img src='images/IOTJ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sagitta: An Energy-Efficient Sparse 3D-CNN Accelerator for Real-Time 3D Understanding](https://ieeexplore.ieee.org/document/10224248)

Changchun Zhou, Min Liu, Siyuan Qiu, Xugang Cao, **Yuzhe Fu**, Yifan He, Hailong Jiao.

**2023**, *IEEE Internet of Things Journal*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-I</div><img src='images/tcas-i.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A 4.29 nJ/pixel stereo depth coprocessor with pixel level pipeline and region optimized semi-global matching for IoT application](https://ieeexplore.ieee.org/abstract/document/9505253)

Pingcheng Dong, Zhuoyu Chen, Zhuoao Li, **Yuzhe Fu**, Lei Chen, Fengwei An.  

**2021**, *IEEE Transactions on Circuits and Systems I: Regular Papers*

</div>
</div>

# 📃 Patent
- [Low-power-consumption stereo matching system and method for acquiring depth information](https://worldwide.espacenet.com/patent/search/family/073657313/publication/CN112070821A?q=CN112070821A), **2020**, *CN Patent, CN112070821A / WO2022021912A1*

# 🍀 Tape Out
- An energy-efficient pipelined and configurable 3D point cloud-based neural network accelerator is being designed in TSMC 28-nm HPC technology with an area of 2.0 mm×1.5 mm and is taped out in July 2023.
- A 4.5 TOPS/W sparse 3D-CNN accelerator for real-time 3D understanding was fabricated in UMC 55-nm low-power CMOS technology with an area of 4.2 mm×3.6 mm in August 2020.

# 🚀 Skills
- Proficient in digital integrated circuit (IC) front-end development, neural network model compression and FPGA development. 
- Familiar with Verilog HDL, PyTorch, Intel Distiller (Model Compression), Cadence (Genus and NCSim), Vivado.
- Knowledgeable in Python, JAVA, MATLAB, Shell, Makefile.

# ![0D4D876E](https://github.com/Yuzhe-Fu/Yuzhe-Fu.github.io/assets/54790390/34cd68b3-1087-400d-9c3a-1ea97768f74c) About Me: 
- I am a easy-going and spirited individual with a passion for life. My enthusiasm not only drives my own life but also positively influences those around me.
- Interests and Hobbies: fitness, jogging, swimming, photography, traveling. (Here is a short [📸 video](https://www.bilibili.com/video/BV19q4y1H716/?vd_source=5c9e9ee79e4910700f06815b0fd41bf3) about my graduation trip in 2021.)

<!-- 
# 🔥 News
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
