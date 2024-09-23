![logo_tutorial](https://raw.githubusercontent.com/secure-robust-recsys/secure-robust-recsys.github.io/main/logo2_tutorial.png)
![uq_logo](https://raw.githubusercontent.com/secure-robust-recsys/secure-robust-recsys.github.io/main/uq_logo2.jpg)

<br>
Welcome! This is the page of our tutorial "<b>Towards Secure and Robust Recommender Systems: Recent Advances and Future Prospectives</b>" at The Web Conference (WWW) 2024.

(Last update: 23/09/2024)

### Time
CET 14:00 - 15:30, 26/04/2024
<hr>

### Description

Recommender systems (RS) have proven to be vulnerable to malicious activities, where harmful data is injected into training datasets or model gradients are manipulated. These attacks compromise system functionality and distort RS objectives, allowing exploitation for malicious purposes. While significant research has been dedicated to understanding attack methods and their weaknesses, defensive strategies to protect RS from these vulnerabilities remain underexplored. This tutorial addresses secure and robust recommendations by exploring three critical research questions: (1) From the secure recommender system perspective, understanding the factors involved in executing successful attacks and exploring techniques to enhance system security; (2) From the robust recommender system perspective, addressing the challenges posed by maliciously injected and noisy data, and examining methods such as data denoising and model enhancement to improve system resilience; (3) Identifying research limitations and future opportunities, particularly the role of large language models in creating new vulnerabilities for attackers and offering novel defensive strategies for defenders. Additionally, the tutorial will culminate in the release of a toolkit designed to support empirical analysis and foster future research innovations in secure and robust recommendations. 
<hr>

### Presenters

<b>Hongzhi Yin</b> is an ARC Future Fellow, Full Professor, and the Director of the Responsible Big Data Intelligence Lab at The University of Queensland. He has published 300+ papers with an H-index of 77, making notable contributions to recommender systems, graph learning, decentralized learning, and edge intelligence. He has rich lecture experience and taught five relevant courses, such as information retrieval and web search, social media analytics, and responsible data science. Additionally, he has delivered 20+ keynotes and tutorials at the top-tier conferences like WWW’17,22,24, DASFAA’23, and KDD’17. 

<b>Zongwei Wang</b>  is currently pursuing his Ph.D. at Chongqing University and is a visiting student at The University of Queensland. His research work has been published on top data mining conferences such as KDD, TIST, PAKDD, WSDM, etc. He has ample experience tutoring relevant courses and has presented his work at multiple top-tier conferences, such as KDD and PAKDD. 

<b>Junliang Yu</b> is an ARC DECRA Fellow at the University of Queensland. His research interests include recommender systems, data-centric AI, and graph learning. With over 30 publications in premier venues, he is a recognized contributor in his field. He has delivered multiple lectures at summer schools and taught courses on recommender systems and social media analytics. He organized two well-received tutorials on self-supervised recommender systems at WWW’22 and DASFAA’23 and presented his work at multiple top-tier conferences.

<b>Tong Chen</b> is a Senior Lecturer and ARC DECRA Fellow at The University of Queensland. His research on lightweight, on-device, and trustworthy recommender systems has been published in top-tier international venues such as KDD, SIGIR, WWW, TKDE, WSDM, TNNLS, TOIS, and CIKM. He has ample track records in lecturing, evidenced by his course design and delivery experience in business analytics, teaching experience in data science, and invited tutorials on cutting-edge recommender systems at the WWW’22, 24, and DASFAA’23.

<b>Shazia Sadiq</b> is a Full Professor at The University of Queensland. Her research focuses on responsible data management and aims to reduce the socio-technical barriers to data-driven transformation. She is a Fellow of the Australian Academy of Technological Sciences and Engineering. Throughout her 25-year career, she has received numerous invitations to speak at prestigious conferences, academic institutions, and industry forums, delivering over 20 tutorials, talks, panels, and keynotes. One notable example is the Keynote talk at SIGMOD’23.

<b>Min Gao</b> works as a Full Professor at Chongqing University, China. She has published 100+ papers, making notable contributions to recommender systems and data mining. She has been SPC or PC for many top conferences, such as WWW, IJCAI, AAAI, KDD, WSDM, and CIKM. Prof. Min Gao has rich lecture experience and has taught three relevant courses, such as advanced machine learning, computer networks, and advanced database, and has presented her work at multiple top-tier conferences.

<hr>

### Outline

The tutorial is delivered as a lecture-style tutorial (3 hours in duration) that includes:
- <b>Introduction</b>  (20 mins)
  - Overview of Recommendation (5 mins)
  - Overview of Secure and Robust Recommendation (15 mins)   
- <b>Secure Recommendation</b>  (50 mins)
  - Poisoning Attacks against Recommendation (40 mins)
  - Defense Against Poisoning Attacks in Recommendation (30 mins)
- <b>Robust Recommendation</b>  (50 mins)
   - Robustness Problem in Recommendation (10 mins)
   - Robust Methods Against Noisy Data (40 mins)
- <b> Limitations and Future Research Trends</b>  (30 mins)
   - Extension of Existing Research Questions (15 mins)
   - Large Language Models in Secure and Robust Recommendation (15 mins)
- <b>Open-source Toolkit for Robust and Safe Recommendation</b> (10 mins)
<hr>

### Targeted Audience

  This tutorial is designed for a broad audience, including academic and industrial researchers, graduate students, and practitioners from the recommendation field and related areas. By the end of the tutorial, participants will have a solid understanding of basic poisoning attacks and defensive strategies to enhance the robustness and security of recommendation systems. Additionally, they will gain hands-on experience using an open-source toolkit. While prior knowledge of recommendation systems is preferred, the tutorial will also cover foundational concepts to ensure better engagement and accessibility for all attendees.

<hr>

### Our papers on secure and robust recommendation


+ [Stealthy attack on graph recommendation system](https://doi.org/10.1016/j.eswa.2024.124476). <i><b>Expert Systems with Applications (2024)</b><i> <br>
+ [Gray-Box Shilling Attack: An Adversarial Learning Approach](https://doi.org/10.1145/3512352). <i><b>ACM TIST (2022)</b><i> <br>
+ [Unveiling Vulnerabilities of Contrastive Recommender Systems to Poisoning Attacks](https://doi.org/10.1145/3637528.3671795). <i><b> KDD (2024)</b><i> <br>
  
+ [Are Graph Augmentations Necessary? Simple Graph Contrastive Learning for Recommendation](https://arxiv.org/abs/2112.08679).  <i><b>SIGIR'22</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SimGCL.py) <br>
Junliang Yu, Hongzhi Yin, Xin Xia, Tong Chen, Lizhen Cui, Quoc Viet Hung Nguyen
+ [	On-Device Next-Item Recommendation with Self-Supervised Knowledge Distillation](https://arxiv.org/abs/2204.11091).  <i><b>SIGIR'22</b></i> [[code]]() <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Guandong Xu, Quoc Viet Hung Nguyen
+ [Self-Supervised Graph Co-Training for Session-based Recommendation](https://dl.acm.org/doi/abs/10.1145/3459637.3482388).  <i><b>CIKM'21</b></i> [[code]](https://github.com/xiaxin1998/COTREC) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Yingxia Shao, Lizhen Cui
+ [Double-Scale Self-Supervised Hypergraph Learning for Group Recommendation](https://dl.acm.org/doi/10.1145/3459637.3482426).  <i><b>CIKM'21</b></i> [[code]](https://github.com/0411tony/HHGR) <br>
Junwei Zhang, Min Gao, Junliang Yu, Lei Guo, Jundong Li, Hongzhi Yin
+ [Socially-Aware Self-Supervised Tri-Training for Recommendation](https://dl.acm.org/doi/10.1145/3447548.3467340).  <i><b>KDD'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/SEPT.py) <br>
Junliang Yu, Hongzhi Yin, Min Gao, Xin Xia, Xiangliang Zhang, Nguyen Quoc Viet Hung
+ [Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation](https://dl.acm.org/doi/abs/10.1145/3442381.3449844).  <i><b>WWW'21</b></i> [[code]](https://github.com/Coder-Yu/QRec/blob/master/model/ranking/MHCN.py) <br>
Junliang Yu, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, Xiangliang Zhang
+ [Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/16578).  <i><b>AAAI'21</b></i> [[code]](https://github.com/xiaxin1998/DHCN) <br>
Xin Xia, Hongzhi Yin, Junliang Yu, Qinyong Wang, Lizhen Cui, Xiangliang Zhang
