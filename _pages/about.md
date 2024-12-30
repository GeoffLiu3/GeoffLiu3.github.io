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

Hello! My name is **Gufeng Liu**, and I am currently pursuing a **[Dual Master’s Degree in Business Analytics](https://masters.sem.tsinghua.edu.cn/en/qhdx_glbydxswfxsssxwxm/Program_Content.htm)** at **Columbia University** and **Tsinghua University**. My focus lies in **data analysis**, **statistical modeling**, and **machine learning**, with a passion for transforming complex datasets into clear, actionable strategies.  

Through hands-on experience in diverse projects, I have honed my ability to bridge the technical and business worlds, crafting solutions that drive measurable outcomes. I thrive on tackling challenges that require both analytical rigor and creative problem-solving, and I am excited to contribute my skills to the fast-evolving intersection of technology and decision-making.  

# 🔥 News

- *2024.11*: 🎉 Awarded the **2024 Tsinghua Graduate Excellence Scholarship** (Top 20%) and the **Overseas Study Excellence Scholarship**.
- *2024.8*: Started the **M.S. in Business Analytics** program at Columbia University.
- *2024.3*: Joined **Apple** as a Data Scientist Intern.
- *2023.12*: Published an empirical study on energy economics as the first student author in *[Resources Policy](https://doi.org/10.1016/j.resourpol.2023.104559)*.
- *2023.9*: Began the **M.S. in Management Science & Engineering** program at Tsinghua University.
- *2023.6*: Graduated with a **B.S. in PPE (Philosophy, Politics, and Economics)** from Wuhan University.
- *2022.9*: Pre-admitted to the dual master's program in Business Analytics at Tsinghua and Columbia University.
- *2021.12*: Honored as one of **Wuhan University's Top Ten Musicians** for keyboard performances.

# 📖 Educations

- **Columbia University**, M.S. in Business Analytics, GPA: 4.00/4.00 (Expected Dec 2025)
- **Tsinghua University**, M.S. in Management Science & Engineering, GPA: 3.90/4.00 (Jun 2024)
- **Wuhan University**, B.S. in PPE (Philosophy, Politics, and Economics), GPA: 3.88/4.00 (Jun 2023)

# 🎖 Honors and Awards

- *2024*: **Tsinghua Graduate Excellence Scholarship** (Top 20%), Tsinghua University
- *2024*: **Overseas Study Excellence Scholarship**, Tsinghua University
- *2019-2023*: **Scholarship for Outstanding Students**, Wuhan University (awarded annually)
- *2021*: Recognized among the **'Top Ten Musicians'**, Wuhan University

# 📝 Projects

- **[Publication](https://doi.org/10.1016/j.resourpol.2023.104559)**  

  **How does ESG performance affect green transformation of resource-based enterprises: Evidence from Chinese listed enterprises**  

  *Resources Policy*, Volume 89, February 2024, Article 104559  

  Xiujie Tan, **Gufeng Liu**, Si Cheng  

- **[IT Automation Prediction Project](https://medium.com/analytics-in-action-columbia-business-school/from-data-to-automation-revolutionizing-it-support-at-electric-4661ab08cf57)**  
  *Sep 2024 - Dec 2024*  
  - Undertaken as part of the **[Analytics in Action](https://daniel.guetta.com/ana)** course, a selective program combining real-world projects and cross-functional collaboration with MBA teammates.  
  - Collaborated with **[Electric](https://www.electric.ai)** (a New York-based IT service provider) to automate the classification of **737K IT tickets** (10M+ messages), reducing repetitive workload and identifying automation opportunities, saving **$2M+ annually** by automating 15.2% of monthly tickets.  
  - Executed the full data pipeline:  
    - Downloaded and processed raw data from the **Snowflake platform**, ensuring data integrity and accessibility.  
    - Maintained and optimized **notebook code files**, enhancing reproducibility and enabling team collaboration on analytics tasks.  
    - Cleaned and balanced data using **SMOTE**.  
    - Fine-tuned ML models (**LightGBM**, etc.) with **Bayesian optimization**, achieving **86% average precision** and refining outputs to **95% accuracy** with a threshold-based approach.  
  - Collaborated with Electric's Head of Data and MBA teammates to align project goals and deliver insights for scalable automation strategies, improving efficiency and cutting operational costs.  

# 💻 Internships

## Apple Inc. | Data Scientist Intern 🍎
### *Beijing, China | Mar 2024 - Aug 2024*
- **Sales Performance Monitoring**
  - Monitored and assessed sales performance metrics (GMV, SO, etc.) across 4 live streams and 5 storefronts.
  - Identified anomalies and conducted 10+ attribution analyses, providing actionable insights to support management in refining live stream strategies.
- **Data Processing & Automation**
  - Utilized Selenium for data scraping and Pandas for real-time sales data processing.
  - Maintained 20+ reusable code files, enabling streamlined data workflows and consistent reporting for team operations.
- **Empirical Analysis & Strategic Insights**
  - Designed econometric models to analyze GMV/GPM drivers and violation impacts.
  - Used tools like lagged analysis and inter-group coefficient difference tests, reducing violations by 50%, boosting GPM by 3.4%, and providing insights for A/B testing to further refine strategies.
- **Reporting & Visualization**
  - Produced 30+ reports visualizing sales and operational metrics, including discounted cash flow models to quantify and compare promotional effects.
  - Delivered clear, actionable insights for management to drive strategic decisions effectively.
- **Collaboration with Stakeholders**
  - Partnered with product managers, data scientists, and external data engineering teams to align business requirements with technical solutions.
  - Collaborated with external teams to create business-oriented dashboards, improving non-technical stakeholders’ ability to interpret performance metrics and make informed decisions.

## Nestlé S.A. | Data Analyst Intern ☕
### *Beijing, China | Apr 2024 - Jun 2024*
- **Investment Impact Analysis**
  - Investigated the impact of online and offline investments on sales performance over 24 months and 20+ coffee product categories using 130+ variables.
  - Applied linear regression to identify key influences on sales, emphasizing **heterogeneity** (e.g., differences across investment types) and **lag effects** to uncover delayed responses in sales performance.
- **Machine Learning & Predictive Modeling**
  - Built and optimized ML models (e.g., XGBoost, causal random forest) to analyze **predictive relationships**, achieving **2024 sales forecasts** with an **R² of 0.70**.
  - Conducted **feature importance analysis** to highlight impactful variables, such as Consumer Experience and Digital Paid Media, driving data-driven decisions.
- **Strategic Recommendations**
  - Recommended cross-channel investment strategies by evaluating **synergies** between online and offline channels, contributing to **15-20% potential sales growth**.
  - Provided actionable insights to enhance **long-term brand impact** and **market expansion** through tailored investment strategies in China.

## SAS Institute Inc. | Data Engineer Intern 🔍
### *Beijing, China | Dec 2023 - Feb 2024*
- **Data Processing & Feature Engineering**
  - Processed and analyzed **50 billion business records** for a major state-owned bank, leveraging **SAS** to enhance data quality and customer interaction management.
  - Standardized **627 features** using feature engineering techniques, including resolving logical conflicts in data definitions and handling missing values to improve usability and consistency.
- **Interaction Cycle Tagging & Data Automation**
  - Designed a **five-dimensional interaction cycle tagging system**, classifying customer behaviors into actionable categories (e.g., *Decaying*, *Occasional*, *Frequent*).
  - Automated workflows with SAS macros to calculate interaction metrics, such as quarterly averages and normalized contributions, reducing manual effort and accelerating data preparation by one week.
  - Delivered actionable insights by establishing data-driven standards for customer segmentation, laying a foundation for regression analysis and predictive modeling to support the bank’s digital transformation initiatives.

# 💫 Interests

## 🎹 Music

- Started learning **piano** in 2012 and became a **keyboard player** in 2019.
- Played keyboard for two bands:
  - ***Aftermath Candy***: Focused on pop punk style. [Watch Performance](https://www.bilibili.com/video/BV1TP411X7Xo/)
  - ***Antidote***: Specialized in gothic metal. [Watch Performance](https://www.bilibili.com/video/BV1iM411g7Fp/)
- Enjoy exploring various genres such as blues, cool jazz, and British rock. Favorite bands include **The Beatles**, **Blur**, and **Oasis**.
- Recognized among **Wuhan University's Top Ten Musicians** for keyboard performances. [Watch Performance](https://www.bilibili.com/video/BV1vQ4y1e7hX/)
- Interested in **improvisation** and **accompaniment exploration**, with a strong curiosity about the integration of **AI and music** in the future.

---

## ⚽ Football

- Became a football fan in 2015, supporting:
  - Clubs: **Barcelona** and **Manchester City**.
  - National Teams: **Argentina**, especially when **China's national team** doesn't qualify for the World Cup 😄.
- Huge admirer of **Leo Messi** 🐐!
- Passionate about **football data analysis**, with interests in models like:
  - **Expected Goals (xG)** Model: Measures scoring opportunities.
  - **Player Contribution Model**: Quantifies each player's contribution during the game, from defense to attack. This method enables fair evaluations for midfield and defensive players, avoiding reliance solely on goals and assists for player assessment.

---

## 🤖 AI and Technology

- Expertise in **machine learning**, **deep learning**, and **large language models (LLMs)** through my dual master's degree programs in Management Science & Business Analytics.
- Actively exploring AI applications in daily life, including:
  - Chatting with GPT to learn prompt engineering and testing advanced AI use cases.
  - Engaging in thoughtful discussions about AI's future.

### 🌟Thoughts on AI's Impact:

1. **AI and Job Creation**:

   - A common concern today is the impact of AI on industries and employment. However, history offers valuable lessons. When computers were first introduced, there were widespread fears about job loss in fields like accounting and manual calculations. Contrary to these fears, computers created an abundance of new roles and opportunities.
   - Similarly, AI has the potential to create new opportunities in two key ways:
     - **Validation Roles**: As AI becomes integrated into every industry, a new class of jobs could emerge around validating AI-generated outputs. Today, users frequently review and verify AI-generated content, and in the future, this process may evolve into a standard professional function.
     - **Domain Expertise**: Effective use of AI requires domain-specific knowledge to validate outputs accurately. Professionals will need to master their fields to ensure AI-generated content aligns with industry standards and best practices. Additionally, this expertise can contribute to creating higher-quality training data, improving AI systems over time.
   - In essence, while AI may disrupt traditional roles, it will likely lead to the creation of complementary positions that focus on working alongside AI, ensuring accuracy, and maximizing its potential within specialized fields.
2. **AI’s Time Complexity Advantage**:

   - AI drastically reduces task complexity by transforming **optimizer-level thinking** (finding answers from scratch) into **verifier-level thinking** (evaluating AI-generated answers).
   - This shift mirrors algorithmic principles, where verification is often faster and less complex than optimization.

<!-- # 💬 Invited Talks

- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
