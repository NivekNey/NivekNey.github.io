---
layout: cv
title: Kevin Yen
---
# Kevin Yen

#### Senior Principal Research Engineer

<h4 id="webaddress">
yenkevin1203@gmail.com
⸱ <a href="https://www.linkedin.com/in/kevinyen91">LinkedIn</a>
⸱ <a href="https://github.com/kevinyen">GitHub</a>
⸱ <a href="https://kevinyen.net/media/kevinyen_resume.pdf">Resume</a>
⸱ NYC
</h4>


## About

I build systems that connect millions of people with content they care about. Currently leading development of Yahoo's next-generation recommendation infrastructure—modernizing how we serve personalized content with LLM-powered systems that enable faster iteration and better user experiences.

**How I work:** I do whatever the project needs to succeed. Sometimes that means leading design discussions and coordinating across teams. Sometimes it means writing production code at 11pm to hit a launch deadline. Sometimes it means diving into research papers to figure out if a new technique will actually work at scale. I've led projects, written papers, debugged distributed systems, and refactored legacy codebases—whatever moves the work forward.

**What I do:** End-to-end applied ML and systems work, from initial exploration to production deployment. My work spans recommendation systems, ad tech optimization, content moderation, and infrastructure that enables other engineers to move faster. I'm comfortable being hands-on with code or stepping back to design architecture and coordinate execution.

**Background:** U.S. citizen with 8+ years at Yahoo, working across research and engineering. Deep expertise in ML, data science, and Python that naturally evolved into technical leadership across multiple efforts. MS from Ohio State, BS from National Central University (Taiwan).


## Recent Work

### Yahoo News Recommendation Systems (2024–present)

Co-leading the design of Yahoo's next-generation recommendation system—rethinking how we serve personalized content at scale.

**The opportunity:** Build cloud-native, Python-first systems that integrate modern ML techniques including LLMs. Focus on faster experimentation cycles while maintaining performance standards and improving personalization quality.

**What we're building:** Complete stack from notebooks to data pipelines to production traffic handling. Advanced techniques include customized MMR diversification, two-tower retrieval modeling, dimension reduction for knowledge distillation, UMAP/HDBSCAN clustering, and LLM-based feature extraction. The system powers content feeds across multiple surfaces.

**The Artifact integration:** Following Yahoo's acquisition of Artifact (the AI news app from Instagram co-founders Kevin Systrom and Mike Krieger), I led technical aspects of integrating their technology into Yahoo's ecosystem. A 2.5-month sprint to adapt their backend to Yahoo's scale—the primary challenge was that Yahoo has significantly higher content volume and daily active users than Artifact was designed for. We refactored and connected services to internal systems (content ingestion, user data storage) while working directly with the founding team to understand their product and engineering approaches. Successfully launched as the new Yahoo News mobile experience.

*Kevin Systrom and Mike Krieger previously founded Instagram; Mike Krieger is now Chief Product Officer at Anthropic*


## Selected Projects

### Ad Tech & Optimization

**Traffic Optimization** — Redesigned traffic handling for Yahoo's ad exchange. Developed ML-based outbound throttling that replaces random rate limiting with value-aware traffic allocation, and co-owned inbound throttling that substantially increased throttle rates while improving revenue—generating significant infrastructure savings at scale.

**Offline Estimation Framework** — Built systems for running multiple experiments and estimating impacts before creating online test buckets. This enabled efficient communication with business teams and helped product owners fully understand potential outcomes before deployment.

**Business Metrics Optimization** — Designed and prototyped optimization models for key ad exchange metrics (eCPM, RPM), providing clear impact analysis that informed strategic business decisions.

### Content Moderation & Safety

**Ad Creative Policy Systems** — Built classification models for political ads and policy violations that dramatically reduced manual review volume while enabling high-precision auto-clearing. Developed LSH-based creative hashing that further reduced review workload and improved training data quality through noisy label identification.

**User-Generated Content Systems** — Developed multiple generations of text and image classifiers for content moderation:

- Early BERT adoption (2019): trained from scratch with custom vocabulary on months of user comments—full pre-training, not fine-tuning. Built ensemble systems that significantly outperformed external vendors; later variants were much smaller and faster while maintaining accuracy.
- Transfer learning with modern architectures (Xception, EfficientNet) for image classification
- Proactive toxic comment prediction to manage high-engagement content
- Search suggestion moderation with improved coverage of emerging problematic terms

**Ad Creative Tools** — Deployed BERT-based optimization service with kNN search enabling advertisers to improve creative quality. Achieved significant latency reduction making real-time recommendations viable in production.

### Enterprise Security

**Threat Detection Systems** — Co-designed semi-supervised anomaly detection framework for large-scale DNS flow analysis, using entropy and Isolation Forest methods to surface data-theft indicators—supporting security and compliance requirements.

**Network Security** — Designed data pipelines for enterprise-scale network events, enriching NetFlow with DNS metadata for anomaly detection and forensics.

**Authentication Security** — Led development of adversarial and LSTM-based login-risk scoring models for Yahoo's membership security systems, reducing account-takeover risk across consumer accounts.

### Developer Infrastructure

**Systems & Tools** — Contributions that improved team productivity:

- Established JupyterHub infrastructure with custom PySpark kernels for native notebook experience with remote Spark
- Integrated Horovod for multi-GPU distributed training on internal Kubernetes clusters
- Led early AWS/SageMaker enablement that lowered barriers to ML experimentation
- Modernized ML monitoring dashboards and reporting
- Implemented CICD pipelines and conducted major codebase refactoring
- Built notebook automation for reproducible workflows


## LLM Experience

Currently using LLMs extensively in the recommendation system:

- **Completion/infilling** for feature generation and content moderation
- **LLM embeddings** as training features for downstream models
- **Vector search** for labeled data expansion
- **Prompt engineering** through manual iteration and systematic evaluation via Langfuse


## Publications & Patents

**10+ peer-reviewed publications** at venues including EMNLP, CIKM, IEEE TNNLS, and IEEE Big Data. Topics span text moderation, creative optimization, graph neural networks, and distributed AutoML systems.

**4 patents and trade secrets** covering content moderation systems, ad creative optimization, and security technologies.

See [full publication list on Google Scholar](https://scholar.google.com/citations?user=YnP8rS4AAAAJ&hl=en).


## Technologies

**Currently:** Python, LLMs, GCP, AWS, Spark, TensorFlow, PyTorch, Kubernetes

**Experience with:** Scala, Java, TypeScript, JavaScript, C++, PHP, Rust, Go, Lua, SQL

**Languages:** English, Chinese


## Timeline

- **2023–present** — Senior Principal Research Engineer, Yahoo (NYC)
- **2020–2023** — Principal Research Engineer, Yahoo (NYC)
- **2019–2020** — Senior Research Engineer, Yahoo (NYC)
- **2018–2019** — Research Engineer, Yahoo (NYC)
- **2017–2018** — Associate Research Engineer, Yahoo (NYC)
- **2016–2017** — Part-time Contractor, Yahoo (Remote)
- **Summer 2016** — Research Intern, Yahoo (NYC)
- **2015–2017** — MS Computer Science, Ohio State University
- **2010–2014** — BS Computer Science, National Central University (Taiwan)
