<div align="center">

<img src="https://capsule-render.vercel.app/api?type=wave&color=7b2cbf&height=200&section=header&text=Enterprise%20Software%20Engineer&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Building%20Intelligent%20and%20Scalable%20Systems&descAlignY=58&descAlign=62" width="100%" alt="Header Banner"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=9D4EDD&center=true&vCenter=true&width=600&lines=Senior+Software+Engineer;AI%2FML+Specialist;Full-Stack+Product+Builder;Distributed+Systems+Architect" alt="Typing SVG" />

<br/>

[![Degree](https://img.shields.io/badge/M.S._Computer_Science-7B2CBF?style=for-the-badge&logo=googlescholar&logoColor=white)](#)
[![Location](https://img.shields.io/badge/San_Francisco,_CA-5A189A?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-3C096C?style=for-the-badge&logo=web&logoColor=white)](#)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-240046?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-10002B?style=for-the-badge&logo=gmail&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-7B2CBF?style=for-the-badge&logo=github&logoColor=white)](#)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=9D4EDD&style=flat-square&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/YOUR_USERNAME?color=7B2CBF&style=flat-square&logo=github&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/YOUR_USERNAME?color=5A189A&style=flat-square&logo=github&label=STARS)

</div>

---

## ✦ About Me

I am a **Senior Software Engineer** with a deep product-engineering mindset, specializing in architecting scalable, high-availability distributed systems and integrating state-of-the-art **Artificial Intelligence and Machine Learning** capabilities into enterprise applications. 

My engineering philosophy centers on writing clean, highly optimized, and maintainable code that drives measurable business impact. With extensive experience across the **Full Stack**, I bridge the gap between complex backend infrastructure and seamless user experiences.

*   **Engineering Focus:** Distributed Systems, Cloud-Native Architecture, API Design.
*   **AI/ML Expertise:** LLM Orchestration, RAG Pipelines, Predictive Modeling, Computer Vision.
*   **Product Mindset:** Translating ambiguous product requirements into robust technical specifications and delivering iteratively.
*   **Open To:** Senior Engineering Roles, Architecture Positions, Open Source Collaborations in the AI/Systems space.

---

## ✦ Tech Stack

### Languages
<div align="left">
  <img src="https://skillicons.dev/icons?i=python,go,rust,typescript,java,cpp,sql&theme=dark" alt="Languages"/>
</div>

### Frontend
<div align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,vue,tailwind,redux,webpack&theme=dark" alt="Frontend"/>
</div>

### Backend & Databases
<div align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,django,fastapi,spring,postgres,mongodb,redis,cassandra,kafka&theme=dark" alt="Backend and DB"/>
</div>

### Cloud, DevOps & Tooling
<div align="left">
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,githubactions,linux,bash,nginx,prometheus&theme=dark" alt="Cloud and DevOps"/>
</div>

---

## ✦ AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :---: | :--- |
| **Large Language Models (LLMs)** | Advanced | Custom fine-tuning, RAG architecture, Prompt Engineering, LangChain, LlamaIndex |
| **Computer Vision** | Intermediate | Object detection, Image segmentation, OpenCV, PyTorch, YOLOv8 |
| **Predictive Analytics** | Advanced | Time-series forecasting, XGboost, Scikit-learn, Feature Engineering |
| **MLOps** | Advanced | Model deployment, A/B testing, MLflow, AWS SageMaker, TensorFlow Serving |

---

## ✦ Featured Projects

<details>
<summary><b>1. Enterprise RAG Analytics Engine</b> <i>(Click to expand)</i></summary>
<br/>

> A highly concurrent, distributed Retrieval-Augmented Generation system designed for real-time querying across millions of enterprise documents.

| Attribute | Specification |
| :--- | :--- |
| **Stack** | Python, FastAPI, Go, PostgreSQL (pgvector), Redis, AWS EKS |
| **Scale** | 10M+ documents, 5k+ concurrent users |
| **Performance** | < 200ms latency for vector similarity search |
| **Security** | Role-Based Access Control (RBAC), End-to-End Encryption, SOC2 compliant |
| **Impact** | Reduced cross-departmental data retrieval time by 85% |
| **Repository** | `Private Enterprise Repo` |

**Engineering Overview:**
Architected a microservices-based ingestion pipeline using Go for high-throughput document processing and embedding generation. Utilized FastAPI for the user-facing inference layer, backed by heavily tuned PostgreSQL with pgvector for semantic search. Orchestrated the entire infrastructure via Terraform and deployed on Kubernetes for horizontal scalability.

</details>

<details>
<summary><b>2. Global Distributed Task Scheduler</b> <i>(Click to expand)</i></summary>
<br/>

> A fault-tolerant, high-throughput distributed scheduling system built for executing background jobs at massive scale.

| Attribute | Specification |
| :--- | :--- |
| **Stack** | Rust, Apache Kafka, gRPC, Cassandra |
| **Scale** | 5B+ jobs executed monthly |
| **Performance** | 99.999% uptime, at-least-once delivery guarantee |
| **Security** | mTLS for inter-node communication |
| **Impact** | Replaced legacy Celery infrastructure, saving $40k/MRR in compute costs |
| **Repository** | [![GitHub](https://img.shields.io/badge/View_on-GitHub-7B2CBF?style=flat-square&logo=github)](https://github.com) |

**Engineering Overview:**
Built entirely in Rust to ensure memory safety and zero-cost abstractions. The system leverages Apache Kafka as a persistent commit log for jobs and Cassandra for distributed state management. Implemented custom Raft consensus logic for leader election among worker nodes to ensure no single point of failure.

</details>

<details>
<summary><b>3. Real-Time Fraud Detection Network</b> <i>(Click to expand)</i></summary>
<br/>

> An event-driven machine learning pipeline for detecting fraudulent transactions in real-time financial streams.

| Attribute | Specification |
| :--- | :--- |
| **Stack** | Python, PyTorch, Apache Flink, AWS Kinesis, DynamoDB |
| **Scale** | 100k+ TPS (Transactions Per Second) |
| **Performance** | Sub-50ms inference latency |
| **Security** | PII Tokenization, PCI-DSS Compliant Infrastructure |
| **Impact** | Prevented $2.4M in fraudulent chargebacks within Q1 |
| **Repository** | `Confidential` |

**Engineering Overview:**
Designed an asynchronous streaming architecture using Apache Flink and AWS Kinesis. Trained a Graph Neural Network (GNN) in PyTorch to identify complex fraud rings based on transactional relationships. Deployed the model using AWS SageMaker endpoints auto-scaled based on incoming Kinesis traffic.

</details>

---

## ✦ Experience

### Senior Software Engineer
**FAANG / Tier-1 Tech Company** • *Jan 2022 - Present*

Led a squad of 6 engineers in the Core Infrastructure team, focusing on optimizing high-traffic microservices and integrating AI-driven insights into the main product lifecycle.
*   Architected and migrated a monolithic user-service into 14 distinct microservices, improving deployment frequency by 300%.
*   Designed a unified API gateway utilizing GraphQL, reducing client-side over-fetching and decreasing mobile app load times by 40%.
*   Spearheaded the integration of an LLM-based customer support copilot, deflecting 25% of level-1 support tickets.

`Go` `Python` `GraphQL` `Kubernetes` `AWS` `PyTorch`

### Software Engineer II
**FinTech Unicorn** • *Jun 2019 - Dec 2021*

Developed and maintained critical paths in the payment processing engine, handling billions in daily transaction volume.
*   Implemented a distributed locking mechanism using Redis to prevent double-spending anomalies in high-concurrency environments.
*   Optimized complex PostgreSQL queries, reducing P99 latency on the dashboard API from 1.2s to 150ms.
*   Set up comprehensive CI/CD pipelines via GitHub Actions, enforcing strict code coverage and security scanning.

`TypeScript` `Node.js` `PostgreSQL` `Redis` `Docker` `Terraform`

---

## ✦ Achievements

<div align="center">

| Recognition | Details |
| :--- | :--- |
| 🏆 **Top 1% Contributor** | Recognized as a top open-source contributor on GitHub (Global) in 2023. |
| 🥇 **Hackathon Winner** | 1st Place out of 200+ teams at the Global AI Innovation Hackathon (2022). |
| 🚀 **Patent Holder** | Co-authored a patent on "Distributed Vector Search Optimization Algorithms." |
| 🌟 **Speaker** | Keynote speaker at AWS re:Invent side-events on "Scaling ML Workloads." |

</div>

---

## ✦ Certifications

**AWS**  
[![AWS Solutions Architect Professional](https://img.shields.io/badge/AWS-Solutions_Architect_Professional-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](#) 
[![AWS Machine Learning Specialty](https://img.shields.io/badge/AWS-Machine_Learning_Specialty-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](#)

**Oracle**  
[![Oracle Certified Professional Java](https://img.shields.io/badge/Oracle-Certified_Professional_Java-F80000?style=for-the-badge&logo=oracle&logoColor=white)](#)

**Cisco**  
[![Cisco CCNA](https://img.shields.io/badge/Cisco-CCNA-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](#)

**NPTEL**  
[![NPTEL Advanced Algorithms](https://img.shields.io/badge/NPTEL-Advanced_Algorithms-FF9900?style=for-the-badge)](#)

---

## ✦ Coding Profiles

<div align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/LeetCode-Top_2%25-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/GeeksforGeeks-Institute_Rank_1-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/HackerRank-5_Star_Gold-00EA64?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/CodeChef-4_Star-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef"/>
  </a>
</div>

---

## ✦ GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&title_color=9D4EDD&icon_color=7B2CBF&text_color=ffffff&bg_color=0D0D0D&hide_border=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=radical&title_color=9D4EDD&icon_color=7B2CBF&text_color=ffffff&bg_color=0D0D0D&hide_border=true" width="48%" alt="Top Languages" />
</div>
<br/>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=radical&ring=7B2CBF&fire=9D4EDD&currStreakLabel=7B2CBF&background=0D0D0D&border=0D0D0D&stroke=ffffff" width="100%" alt="GitHub Streak" />
</div>

---

## ✦ GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=radical&column=7&margin-w=15&margin-h=15&no-bg=true&no-frame=true&title-text-color=9D4EDD" alt="Trophies" />
</div>

---

## ✦ Contribution Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=0D0D0D&color=9D4EDD&line=7B2CBF&point=ffffff&area=true&hide_border=true" width="100%" alt="Contribution Graph" />
</div>

---

## ✦ Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## ✦ Current Focus

```yaml
learning: 
  - Advanced Distributed Consensus Algorithms
  - CUDA / GPU Programming for ML Acceleration
building:
  - Open-Source Rust-based Vector Database
  - Multi-Agent LLM Frameworks
exploring:
  - WebAssembly (Wasm) in Cloud-Native environments
  - Zero-Knowledge Proofs (ZKP)
open_to:
  - Technical Advisory Roles
  - Enterprise Architecture Consulting
  - Speaking Engagements
