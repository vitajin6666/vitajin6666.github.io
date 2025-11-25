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
**I am a former mid-senior Product Manager (P8) at Tencent preparing to pursue a PhD in Information Systems, with a research focus on human-centered generative AI and user behavior on digital platforms.**

At Tencent, I led the digital goods marketplace in the Appstore ecosystem, serving 700,000+ paying users and generating ¥60 million in monthly GMV. I executed hundreds of large-scale A/B tests and built RFM/CLV segmentation, churn prediction, and pricing models, consistently lifting ARPPU by over 30% and repurchase rates by 20%. These experiences revealed the behavioral limitations of metric-driven product iteration and shaped my commitment to theory-grounded, human-centered AI research.

After leaving Tencent, I have been preparing full-time for doctoral study while leading an independent research project, which uses appraisal theory and multi-study experiments to show how luck-based explanation framing enhances user acceptance of generative AI recommendations.

Previously, I earned my bachelor’s degree from the [School of Tourism Management](https://stm.sysu.edu.cn/about) at Sun Yat-sen University (中山大学旅游学院), [ranked #1 in Mainland China and #3 globally](https://www.shanghairanking.com/rankings/gras/2024/RS0513). I also interned at Baidu (百度), Trip.com (携程), China Mobile (中国移动), and the United Nations World Tourism Organization (联合国世界旅游组织), and was admitted to Tencent’s flagship Product Manager Program (≈0.4% acceptance rate)[(腾讯产品经理培训生)](https://mp.weixin.qq.com/s/Xg1GtNG6ej3SUq9j6DGoLA).

I am actively seeking research collaborations and PhD opportunities in Information Systems.
[vitajin101@gmail.com](mailto:vitajin101@gmail.com) | Full [CV](CV/Wanyuan Jin_CV.pdf)

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 📖 Education
- *2016.09 - 2020.06*, B.M. in Exhibition Economy and Management, Sun Yat-sen University (GPA: 3.9/4.0)

# 🕵️ Current Research
**The Serendipity Switch: A Novel Luck-based Explanation Framing for Enhancing User Acceptance of Generative AI**
Recommendations
- Research Gap: Modern recommender systems deliver highly personalized and often serendipitous content, yet
their explanation mechanisms remain generic, factual, and non-personalized. This mismatch limits users’
perceived serendipity and acceptance of generative AI recommendations.
- Research Design: This project introduces luck-based explanation framing by embedding cues of serendipity and
fortunate coincidence into recommendation explanations. Drawing on Appraisal Theory and a sequential
mixed-methods design (five experiments plus a qualitative study), it investigates how such framing enhances
user acceptance through opportunity appraisal and perceived diagnosticity, and examines moderators including
AI role-playing, product orientation, product involvement, and AI literacy.

# 💻 Work Experience
## Professional Summary
Product Manager at Tencent with three years of experience in platform strategy. Selected into Tencent’s highly competitive Product Management Trainee Program (0.4% acceptance) through campus recruitment and promoted to P8 (mid-to-senior level). Led cross-functional teams and mentored junior members while driving data-informed initiatives. Skilled in data-driven analysis and experimental frameworks to optimize platform performance and user engagement.
## 🎮 *2021.08 - 2023.03*, Tencent Appstore (应用宝) – Product Planning Manager
Led the full lifecycle development of a digital goods marketplace supporting 730+ games, 700K+ paying users,
and ¥60M+ monthly GMV, focusing on platform strategy, monetization, and user lifecycle management.
- Platform Design: Designed modular, scalable marketplace platform with end-to-end system architecture.
- CRM & User Analytics: Built precision CRM system with RFM/CLV models; applied behavior-based
segmentation and churn-risk prediction to boost ARPPU to ¥600+ and increase repurchase rates by 20%.
- Pricing & Promotion: Designed data-driven pricing and bundling strategies, achieving 3.5x ROI.
- Product Experimentation & Analytics: Conducted A/B tests, funnel analysis, and behavioral analytics to improve user conversion (+17%) and retention (+9%).

## 📱 *2020.07 - 2021.07*, Tencent Live – Product Operations Manager 
Drove user acquisition and content creator engagement on Tencent’s livestreaming platform using data-informed
community strategies.
- UGC Activation & Growth: Applied the AARRR framework to convert viewers to content creators, activating
1,000+ new streamers and generating 8,000+ high-engagement live sessions.
- User Research & Feedback Integration: Conducted 50+ qualitative interviews to identify product pain points.
Collaborated with engineering to reduce CPU load by 50%, improving system stability.


<!-- 加以下这行，是因为导航栏点击Research Interests无法成功跳转，加上具体id名就可以成功了-->
<span class='anchor' id='research-interests'></span>

# ♥️ Research Interests
- Research Areas: Human Computer/AI Interaction, Mobile Commerce, Platform Ecosystem
- Methodologies:  Econometrics, Applied Machine Learning, Field/Lab Experiments


# 📋 Research Experience
## 🌎 *2018.08 – 2018.09*, United Nations World Tourism Organization (联合国世界旅游组织) - Research Assistant
Participated in a UNWTO-led sustainable tourism field study in Kaifeng, China, aimed at evaluating the city’s
cultural image and informing local policy
- Quantitative Research: Designed and conducted a large-scale tourist survey (N=1300); built a moderated
mediation model (Destination Image → Perceived Authenticity → Place Attachment, moderated by Tourist
Involvement) using PROCESS and SEM
- Qualitative Research: Performed thematic and sentiment analysis on web-scraped content and interview
transcripts (50 interviews) to identify key perceptions and explore the cognitive-affective mechanism
- Outcome: Contributed to a UNWTO-issued report submitted to the Kaifeng government as policy guidance for
sustainable tourism planning

## 🏫 *2023.04 – Present*, Skill Development & Independent Research
Engaged in structured self-training to strengthen empirical and computational research skills:
- Advanced courses: Completed Generative AI, Machine Learning, and Deep Learning specializations by Andrew
Ng.
- Transformer-based AI Practice: Applied Hugging Face Transformers to tasks in NLP, computer vision, and
speech processing; gained hands-on experience in model selection, application, and deployment.
- Kaggle Projects: Tackled real-world problems such as demand forecasting and image classification using ML/DL
techniques (e.g., XGBoost, CNNs); developed complete pipelines from data preprocessing to model evaluation.
- Research Replication: Reproduced classical empirical studies using econometric methods (e.g., PSM, DID).





# 🤹 Research Skills
- Research Methodology
  - Econometrics: DID (TWFE, Dynamic DID, CSDID, PSM-DID, Triple DID), Linear & Logistic Regression
  - AI: ML (XGBoost, AutoML), DL (CNNs: MobileNet, ResNet; RNNs: LSTM), LLMs (BERT, GPT, Hugging Face)
  - Quantitative: Lab/Field Experiments (Online Scenarios, A/B Testing), Mediation/Moderation Analysis, SEM
  - Qualitative: Content Analysis (Web Scraping), Semi-structured Interviews

- Programming: Python (TensorFlow, PyTorch, scikit-learn, pandas, NumPy, Matplotlib), R, SQL

- Software & Tools: STATA, SPSS, AMOS, EasySpider, Credamo, Prolific, LaTeX, Zotero, Git

- Languages: English (IELTS Overall 7.0 – R: 7.5, L: 7.0, W: 6.5, S: 6.0); Mandarin (Native)

<!-- 加以下这行，是因为导航栏点击Work in Progress无法成功跳转，加上具体id名就可以成功了
<span class='anchor' id='work-in-progress'></span>

# ✍️ Work in Progress
- need to write
- need to write -->

# 🏆 Honors and Awards
- *2020*, Tencent Elite Product Manager Data Analytics Certification – Score: 108/120
- *2020*, Business Excellence Award, Tencent Live Platform Cente
- *2019*, Second Prize, International University Challenge at Future Leaders Forum
- *2018*, First Prize, National Business Elite Competition
- *2016 - 2019*, National Encouragement Scholarship 
- *2016 - 2017*, The Second Outstanding Student Scholarship

# 💼 Internships
- *2019.08 - 2019.09*, Baidu (百度), Product Operations Intern
- *2019.04 - 2019.07*, Trip.com (携程), Client Manager Intern
- *2017.02 - 2018.12*, China Mobile (中国移动), Retail Operations Intern





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

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

-->





