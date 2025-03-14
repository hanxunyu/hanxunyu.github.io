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

Hello! I am currently a student in <a href="https://www.zju.edu.cn/" target="_blank">Zhejiang University (浙江大学)</a>, majoring in Artifical Intelligence supervised by <a href="https://person.zju.edu.cn/jkzhu" target="_blank">Prof. Jianke Zhu</a>. I have obtained B.Eng (with Honors) from <a href="https://www.whu.edu.cn/" target="_blank">Wuhan University (武汉大学)</a> majoring in Computer Science and Technology supervised by <a href="https://wangzwhu.github.io/home/" target="_blank">Prof. Zheng Wang </a>. I used to be a summer research intern in-person at <a href="https://www.mcgill.ca/" target="_blank">McGill University</a> and <a href="https://mila.quebec/en/" target="_blank">Mila-Quebec AI Institute</a> in Montreal, Canada, under the supervision of <a href="https://www.cs.toronto.edu/~six/" target="_blank">Prof. Xujie Si</a>. Prior to that, I was a remote visit student at <a href="https://www.kaist.ac.kr/en/" target="_blank">KAIST</a> in Korea, supervised by <a href="https://sanctusfactory.com/family.php" target="_blank">Prof. Chang D. Yoo</a>.

My research interests include *2D/3D Multimodal LLMs*, *Visual/Scene Understanding* and *Embodied AI*, particularly in:

**_1.Enabling MLLMs with common visual tasks_**, including open-vocabulary visual grounding for image/video/3D scene.

**_2.Embodied scene understanding/reasoning_**, including 3D question answering, 3D dense captioning and embodied dialogue/planning.

**_3.Efficient and effective MLLMs_**, including visual token compression and lightweight MLLM.

I am currently seeking a long-term research internship opportunity. If you are interested in collaborating with me, please feel free to email at <a href="mailto:hanxun.yu@zju.edu.cn" target="_blank">hanxun.yu@zju.edu.cn</a>.

<!-- <a href="../assets/CV_CN_hanxun.pdf" target="_blank"><strong>Curriculum Vitae</strong></a> -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DruMxKYAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DruMxKYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 One paper is accepted by CVPR 2025. 
- *2024.07*: &nbsp;🎉🎉 One paper is accepted by IEEE TPAMI 2024. 
- *2023.07*: &nbsp;🎉🎉 One paper is accepted by ACM MM 2023. 
- *2023.06*: &nbsp;🎉🎉 I won the National Scholarship at Wuhan University (**Top 2%**). 
- *2022.06*: &nbsp;🎉🎉 Accepted to the Mitacs Globalink Research Internship 2022 program (in Canada). 
<!-- , &dagger;: corresponding authors -->

# 📝 Publications 
<div style="margin-bottom: -10px">* indicates equal contribution</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/CVPR25_pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inst3D-LMM: Instance-Aware 3D Scene Understanding with Multi-modal Instruction Tuning.](https://arxiv.org/pdf/2503.00513)

<span style="color:red; font-size: 1em;">Rating Score: 5/5/4</span>

**Hanxun Yu\***, Wentong Li\*, Song Wang, Junbo Chen, Jianke Zhu

<a href="https://arxiv.org/pdf/2503.00513" target="_blank">[**Paper**]</a> <a href="https://github.com/hanxunyu/Inst3D-LMM" target="_blank">[**Code**]</a>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- This paper proposes an effective instance-aware Large Multi-modal Model for 3D scene understanding. We develop a MCMF module for 2D/3D cross-modal feature fusion, which generates fine-grained instance-level tokens, and a 3D-ISR module to capture the complex spatial relationships among objects, producing informative scene-level tokens. Our Inst3D-LMM is designed to require fewer computational resources, while delivering faster training and inference speeds. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/MM23_pipeline.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Moiré Backdoor Attack (MBA): A Novel Trigger for Pedestrian Detectors in the Physical World](https://web.archive.org/web/20231028032552id_/https://dl.acm.org/doi/pdf/10.1145/3581783.3611910)

Hui Wei*, <strong>Hanxun Yu*</strong>, Kewei Zhang, Zhixiang Wang, Jianke Zhu, Zheng Wang

<a href="https://web.archive.org/web/20231028032552id_/https://dl.acm.org/doi/pdf/10.1145/3581783.3611910" target="_blank">[**Paper**]</a> <a href="https://github.com/weihui1308/Moire-Backdoor-Attack" target="_blank">[**Code**]</a>
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- This paper focuses on AI safety-critical tasks and introduces the Moiré Backdoor Attack (MBA), which firstly integrates Moiré-based triggers into pedestrian detection models. Our MBA approach enables individuals wearing clothes with Moiré patterns to evade detection in the real world scenarios, while maintaining considerable stealthiness.
</div>
</div>

<div style="margin-top: 17px">
<ul>
  <li>
  <div class="badge" style="display: inline-block; margin-right: 0px;">TPAMI 2024</div> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://ieeexplore.ieee.org/abstract/document/10602786" target="_blank">Physical Adversarial Attack meets Computer Vision: A Decade Survey, </a> &nbsp;Hui Wei, Hao Tang, Xuemei Jia, Zhixiang Wang, <strong>Hanxun Yu</strong>, Zhubo Li, Shin'ichi Satoh, Zheng Wang &nbsp;<a href="https://ieeexplore.ieee.org/abstract/document/10602786" target="_blank">[<strong>Paper</strong>]</a> <a href="https://github.com/weihui1308/PAA" target="_blank">[<strong>Code</strong>]</a>
  </li>
  <li>
  <div class="badge" style="display: inline-block; margin-right: 0px;">Preprint</div> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="../assets/IEEE_TMM.pdf" target="_blank">Aesthetic Yet Customizable Adversarial Patches Towards Physical Attacks, </a> &nbsp;Hui Wei*, <strong>Hanxun Yu*</strong>, Zhixiang Wang, Shin'ichi Satoh, Hao Tang, Zheng Wang &nbsp;<a href="../assets/IEEE_TMM.pdf" target="_blank">[<strong>Paper</strong>]</a>
  </li>
</ul>
</div>
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024* &nbsp;The Chiang Chen Scholarship, China. 
- *2024* &nbsp;The First Prize of Excellent Graduate Scholarship, Zhejiang University. 
- *2023* &nbsp;The National Scholarship, China. (**Top 2%**) 
- *2023* &nbsp;Outstanding Undergraduate Dissertation Award, Wuhan University. 
- *2023* &nbsp;Outstanding Graduate, Wuhan University. 
- *2022* &nbsp;Mitacs-CSC Globalink Research Internship Scholarship, China. (**200/year Nationwide**) 
- *2020,2021,2022* &nbsp;The First Prize of Excellent Undergraduate Scholarship, Wuhan University.

# 📖 Educations
- *2023.09 - now*, Zhejiang University. 
- *2019.09 - 2023.06*, Bachelor (with Honors), Wuhan University. 

# 💻 Internships
- *2022.06 - 2022.10*, [McGill University](https://www.mcgill.ca/) and [Mila-Quebec AI Institute](https://mila.quebec/en/), Montreal, Canada, advised by [Prof. Xujie Si](https://www.cs.toronto.edu/~six/). <a href="../assets/Certificate_Mitacs.pdf" target="_blank">[<strong>Certificate</strong>]</a>
- *2021.12 - 2022.02*, [KAIST](https://www.kaist.ac.kr/en/), Daejeon, Korea, advised by [Prof. Chang D. Yoo](https://sanctusfactory.com/family.php). <a href="../assets/Certificate_iURP.pdf" target="_blank">[<strong>Certificate</strong>]</a>

# 💬 Academic Services
- Conference Reviewer: ICML 2025, CVPR 2025, AAAI 2025, ACM MM 2023-2024
