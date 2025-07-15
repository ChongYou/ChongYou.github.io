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

I am a Research Scientist at Google Research in NYC, where I work on sparsity, information retrieval, foundation models, and their intersections.

Before Google, I was a postdoc at UC Berkeley working with Prof. [Yi Ma](https://people.eecs.berkeley.edu/~yima/). I received my PhD in ECE at Johns Hopkins University in 2018, advised by Prof. [René Vidal](http://vision.jhu.edu/rvidal.html). Prior to Hopkins, I got my B.S. and M.S. degrees at Peking University. 

My research areas broadly include machine learning, computer vision, optimization and signal processing. I am interested in the development of mathematical principles and practical numerical algorithms for analyzing and interpreting modern data. 

My CV can be found [here](../assets/CV_chongyou.pdf).


# 🔥 News
- [2025.06] Paper Release: [Spark Transformer](https://arxiv.org/abs/2506.06644), which follows up on our earlier works — [Lazy Neuron, 2022](https://arxiv.org/abs/2210.06313) and [HiRE, 2024](https://arxiv.org/abs/2402.09360) — to introduce a strong activation sparsity (8% nonzeros in FFN and top-256 in Attention) to modern LLMs.
- [2025.03] Co-organized [Conference on Parsimony and Learning (CPAL)](https://cpal.cc/) at Stanford, CA

# 📝 Recent Publications 

- **Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, LongContext, and Next Generation Agentic Capabilities**<br/>
Gemini Team, Google<br/>
[\[Tech Report\]](https://storage.googleapis.com/deepmind-media/gemini/gemini_v2_5_report.pdf)

- **Spark Transformer: Reactivating Sparsity in FFN and Attention**<br/>
<ins>Chong You</ins>\*, Kan Wu\*, Zhipeng Jia\*, Lin Chen\*, Srinadh Bhojanapalli, Jiaxian Guo, Utku Evci, Jan Wassenberg, Praneeth Netrapalli, Jeremiah J. Willcock, Suvinay Subramanian, Felix Chern, Alek Andreev, Shreya Pathak, Felix Yu, Prateek Jain, David E. Culler, Henry M. Levy, Sanjiv Kumar<br/>
[\[Arxiv\]](https://arxiv.org/abs/2506.06644)

- **Efficient and Asymptotically Unbiased Constrained Decoding for Large Language Models**<br/>
Haotian Ye, Himanshu Jain,  <ins>Chong You</ins>, Ananda Theertha Suresh, Haowei Lin, James Zou, Felix Yu<br/>
*International Conference on Artificial Intelligence and Statistics **(AISTATS)***, 2025<br/>
[\[Arxiv\]](https://arxiv.org/abs/2504.09135)

- **Generalized Neural Collapse for a Large Number of Classes**<br/>
Jiachen Jiang\*, Jinxin Zhou\*, Peng Wang, Qing Qu, Dustin Mixon, <ins>Chong You</ins>, Zhihui Zhu<br/>
*International Conference on Machine Learning **(ICML)***, 2024<br/>
[\[Arxiv\]](https://arxiv.org/abs/2310.05351)

- **It's an Alignment, Not a Trade-off: Revisiting Bias and Variance in Deep Models**<br/>
Lin Chen, Michal Lukasik, Wittawat Jitkrittum, <ins>Chong You</ins>, Sanjiv Kumar<br/>
*International Conference on Learning Representations **(ICLR)***, 2024<br/>
[\[Arxiv\]](https://arxiv.org/abs/2310.09250)

- **Functional Interpolation for Relative Positions Improves Long Context Transformers**<br/>
Shanda Li, <ins>Chong You</ins>, Guru Guruganesh, Joshua Ainslie, Santiago Ontanon, Manzil Zaheer, Sumit Sanghai, Yiming Yang, Sanjiv Kumar, Srinadh Bhojanapalli<br/>
*International Conference on Learning Representations **(ICLR)***, 2024<br/>
[\[Arxiv\]](https://arxiv.org/abs/2310.04418)

- **Deep Self-expressive Learning**<br/>
Chen Zhao, Chun-Guang Li, Wei He, <ins>Chong You</ins><br/>
*Conference on Parsimony and Learning **(CPAL)***, 2024<br/>
[\[Arxiv\]](https://proceedings.mlr.press/v234/zhao24a.html)

- **HiRE: High Recall Approximate Top-$k$ Estimation for Efficient LLM Inference**<br/>
Yashas Samaga B L, Varun Yerram, <ins>Chong You</ins>, Srinadh Bhojanapalli, Sanjiv Kumar, Prateek Jain, Praneeth Netrapalli<br/>
[\[Arxiv\]](https://arxiv.org/abs/2402.09360)


<!---
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 💬 Invited Talks
- *2024.06*, **How Many FLOPS is a Token Worth?** Workshop on Mathematics of Deep Learning [\[video\]](https://www.birs.ca/events/2024/5-day-workshops/24w5297/videos/watch/202406131400-You.html) 
- *2022.09*, **Robust Learning by Double Over-Parameterization.** Seminar at University of Michigan [\[video\]](https://ece.engin.umich.edu/event/csp-seminar-by-chong-you)

