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

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- Hi, I'm a final year undergraduate student from School of Mathematics, UESTC, and I am very fortunate to be advised by Prof. [Liangjian Deng](https://liangjiandeng.github.io/). I will begin my Ph.D. studies at the School of Computer Science, Peking University in 2025, under the supervision of Prof. [Ge Li](https://ligechina.github.io/).

My current research interests are mainly focused on AI for Software Engineering (AI4SE), encompassing software engineering and natural language processing (NLP) technologies. -->

Hi, I'm a first year Ph.D. student in the School of Computer Science, Peking University, fortunately supervised by Prof. [Ge Li](https://ligechina.github.io/). My current research interests are mainly focused on LLM Reasoning, Foundation Model Architecture and AI for Software Engineering (AI4SE). My CV can be found [here]({% link files/CV_YongdingTao.pdf %}).

<!-- # 🔥 News
- *2024.11*: &nbsp;🎉🎉 I have joined Ant Group to conduct research on AI for Software Engineering (AI4SE)! -->

<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->



# 📝 Publications {#publications}

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<ul class="pub-list" markdown="0">
<li>
<span class="pub-venue"><strong>[ICLR 2026]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/abs/2510.09259">Detecting Data Contamination from Reinforcement Learning Post-training for Large Language Models</a></span>
<span class="pub-authors"><strong><u>Yongding Tao</u></strong>, Tian Wang, Yihong Dong, Huanyu Liu, Kechi Zhang, Xiaolong Hu, Ge Li</span>
</li>
<li>
<span class="pub-venue"><strong>[ICASSP 2026]</strong></span>
<span class="pub-title"><a href="https://github.com/yongding-tao/yongding-tao.github.io/blob/main/papers/TimeDiff.pdf">TimeDiff: Leveraging Differential Domain Representations for Long Time Series Forecasting</a></span>
<span class="pub-authors"><strong><u>Yongding Tao</u></strong>, Xiaohang Zeng*, Qinxu Ding, Yihong Dong, Da Peng, Peng Di, Puzhuo Liu†, Wei Ke†</span>
</li>
<li>
<span class="pub-venue"><strong>[NeurIPS 2025]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/abs/2502.21309">FANformer: Improving Large Language Models Through Effective Periodicity Modeling</a></span>
<span class="pub-authors">Yihong Dong, Ge Li, Xue Jiang, <strong><u>Yongding Tao</u></strong>, Kechi Zhang, Hao Zhu, Huanyu Liu, Jiazheng Ding, Jia Li, Jinliang Deng, Hong Mei</span>
</li>
<li>
<span class="pub-venue"><strong>[NeurIPS 2025]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/pdf/2410.02675">FAN: Fourier Analysis Networks</a></span>
<span class="pub-authors">Yihong Dong, Ge Li, <strong><u>Yongding Tao</u></strong>, Xue Jiang, Kechi Zhang, Jia Li, Jing Su, Jun Zhang, Jingjing Xu</span>
</li>
<li>
<span class="pub-venue"><strong>[ICSE 2025]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/pdf/2411.07112">ROCODE: Integrating Backtracking Mechanism and Program Analysis in Large Language Models for Code Generation</a></span>
<span class="pub-authors">Xue Jiang, Yihong Dong, <strong><u>Yongding Tao</u></strong>, Huanyu Liu, Zhi Jin, Wenpin Jiao, Ge Li</span>
</li>
<li>
<span class="pub-venue"><strong>[Tiny Paper at ICLR 2024]</strong></span>
<span class="pub-title"><a href="https://openreview.net/pdf?id=ki4R0z0C4K">A Novel Window-Interaction Module Based on W-MSA</a></span>
<span class="pub-authors">Ruochen Cui, <strong><u>Yongding Tao</u></strong>, Mingjun Ni∗</span>
</li>
</ul>

# 📝 Preprints {#preprints}
<ul class="pub-list" markdown="0">
<li>
<span class="pub-venue"><strong>[arXiv:25.10]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/abs/2510.18471">CodeRL+: Improving Code Generation via Reinforcement with Execution Semantics Alignment</a></span>
<span class="pub-authors">Xue Jiang, Yihong Dong, Mengyang Liu, Hongyi Deng, Tian Wang, <strong><u>Yongding Tao</u></strong>, Rongyu Cao, Binhua Li, Zhi Jin, Wenpin Jiao, Fei Huang, Yongbin Li, Ge Li</span>
</li>
<li>
<span class="pub-venue"><strong>[arXiv:25.08]</strong></span>
<span class="pub-title"><a href="https://arxiv.org/abs/2508.00222">RL-PLUS: Countering Capability Boundary Collapse of LLMs in Reinforcement Learning with Hybrid-policy Optimization</a></span>
<span class="pub-authors">Yihong Dong, Xue Jiang, <strong><u>Yongding Tao</u></strong>, Huanyu Liu, Kechi Zhang, Lili Mou, Rongyu Cao, Yingwei Ma, Jue Chen, Binhua Li, Zhi Jin, Fei Huang, Yongbin Li, Ge Li</span>
</li>
</ul>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Education {#education}
<!-- - *2025.08 - *, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2025.09 - Present*, Peking University, School of Computer Science, Ph.D. Student
- *2021.09 - 2025.06*, University of Electronic Science and Technology of China, School of Mathematics, Bachelor’s Degree

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships {#internships}
- *2024.11 - 2025.05*, Research Intern, [Ant Group](https://www.antgroup.com/en), Shenzhen, China.