# Hi, I'm Srimant

**Biologist → Bioinformatician → Data & AI**

**M.Tech Bioinformatics** · Delhi Technological University  |  **Project Intern** · IIIT Allahabad

I build things at th eintersection of biology, data, and code- Data is the common thread. I follow it wherever it leads.

![Bioinformatics](https://img.shields.io/badge/Bioinformatics-1D9E75?style=flat&logoColor=white)
![Data & AI](https://img.shields.io/badge/Data_%26_AI-185FA5?style=flat&logoColor=white)
![Plant Tissue Culture](https://img.shields.io/badge/Plant_Tissue_Culture-534AB7?style=flat&logoColor=white)
![Open to remote](https://img.shields.io/badge/Open_to_remote_%26_freelance-555?style=flat&logoColor=white)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Srimant_Bhardwaj-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srimant-bhardwaj-13s23a)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--6395--1216-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-6395-1216)
[![Email](https://img.shields.io/badge/Email-bhardwajsrimant7@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:bhardwajsrimant7@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Srimant1323-181717?style=flat&logo=github&logoColor=white)](https://github.com/Srimant1323)
![Profile Views](https://komarev.com/ghpvc/?username=Srimant1323&color=1D9E75&style=flat&label=Profile+views)

---

## Deployed Apps & Live Projects

Built and shipped — not just notebooks. Each one started with zero knowledge of the stack and was figured out through documentation, videos, and iteration.

| Project | What I Built | Key Result |
|---|---|---|
| [🏍️ HandRide — Bike Game](https://github.com/Srimant1323/handride-bike-game) | Gesture-controlled browser bike racing game — MediaPipe tracks 21 hand landmarks at 30+ FPS. Tilt palm to steer, fist to brake, open hand to boost. Procedurally generated road, 5 obstacle types, dynamic difficulty, particle exhaust, 3 lives. Built entire game engine from scratch with no prior game dev experience. | 21 landmarks · 30+ FPS · 5 obstacle types · zero backend |
| [🤖 AI Gesture Mirror](https://github.com/Srimant1323/ai-gesture-mirror) · [Live →](https://brahmastra-303193.netlify.app/) | Real-time hand gesture recognition — fire, plasma, aura, hearts, stars, butterflies triggered by gesture classification built from scratch using landmark positions. First time I shipped something anyone could open in a browser and use immediately. | 2000 particles/frame · 21 landmarks · browser-native |
| [🧬 BioCalc App](https://github.com/Srimant1323/biocalc-app) · [Live →](https://biocalc-app-six.vercel.app) | No-code web toolkit for DNA, RNA & protein sequence analysis — built because I kept running the same calculations manually during coursework and wanted a tool biologists without coding skills could use. | GC content · transcription · translation · ORF detection · deployed |
| [🧠 MindBridge App](https://github.com/Srimant1323/MindBridge-app) · [Live →](https://mind-bridge-app-rho.vercel.app) | Full-stack ML web app for mental health risk assessment — first time I connected a trained model to a web frontend. Learned backend, API design, and deployment by building this. | Python backend · scikit-learn · HTML/JS frontend · Vercel |

---

### 🏍️ HandRide — Gesture Controlled Bike Game

| | |
|---|---|
| **Stack** | MediaPipe · HTML5 Canvas · JavaScript ES6 · CSS3 · Netlify |
| **Controls** | Tilt palm → steer · Fist → brake · Open hand → boost |
| **Features** | Procedural road · 5 obstacle types · Dynamic difficulty · Particle exhaust · 3 lives · Keyboard fallback |

I wanted to build a game I could play in the browser without downloading anything. I had zero game development experience — no Unity, no Pygame, nothing. I started watching YouTube videos on HTML5 Canvas and realised you could animate things directly in the browser with just JavaScript. That became the foundation.

The hand tracking came from experimenting with MediaPipe after using it in my Gesture Mirror project. I thought — if I can already detect 21 hand landmarks in real time, why not use that to control a game? The hardest part was translating hand position into reliable game controls without false triggers. The wrist X-coordinate controls steering; fingertips above or below knuckles determines boost vs brake. Getting that logic stable took a lot of trial and error.

I built the entire game engine from scratch — road perspective rendering, obstacle spawning, collision detection, particle exhaust trail, boost flame, lives system. No game tutorial, just Canvas API documentation and figuring it out piece by piece. The moment it actually worked — hand tilted left, bike moved left — was one of the best moments I've had building something.

---

### 🤖 AI Gesture Mirror · [Live →](https://brahmastra-303193.netlify.app/)

| | |
|---|---|
| **Stack** | MediaPipe · HTML5 Canvas · Vanilla JavaScript · Netlify |
| **Landmarks tracked** | 21 per hand at 30+ FPS |
| **Effects** | Fire · Plasma · Aura · Hearts · Stars · Butterflies · 2000 particles/frame |

This started as pure curiosity about MediaPipe. I kept seeing hand tracking demos online and wanted to understand how it actually works, not just call a library. So I set up MediaPipe Hands, got the 21 landmarks rendering on screen, and thought — what if something visual happened based on gestures?

I had no experience with particle systems. I learned how particles work in JavaScript — position, velocity, decay, colour — and built my own from scratch. Getting 2000 particles to render per frame without the browser freezing required understanding `requestAnimationFrame` and canvas clearing properly. The fire, plasma, aura, hearts, stars, and butterflies are all driven by gesture classification I wrote myself using landmark positions.

Deploying it on Netlify was the first time I shipped something anyone in the world could open in a browser and use instantly. That felt completely different from just pushing code to GitHub.

---

### 🧬 BioCalc App · [Live →](https://biocalc-app-six.vercel.app)

| | |
|---|---|
| **Stack** | HTML · CSS · JavaScript · Vercel |
| **Tools inside** | GC content · Transcription · Translation · Reverse complement · ORF detection |
| **Target user** | Biology students and researchers who don't code |

During my bioinformatics coursework I kept running the same sequence calculations over and over — GC content, reverse complement, transcription, translation. Every time I had to write a Python script or look something up. I thought: why isn't there just a simple web tool anyone can open and use?

I had basic HTML and CSS knowledge but had never built a complete multi-function web app. I learned how to structure JavaScript so each tool was modular, handle user input validation, and display results dynamically. The goal was that a biology student with zero coding background could use it without reading any instructions.

Deploying on Vercel taught me the difference between code that works on your machine and code that works for everyone. I also realised that designing for the user — not just getting the algorithm right — is a completely different skill.

---

### 🧠 MindBridge App · [Live →](https://mind-bridge-app-rho.vercel.app)

| | |
|---|---|
| **Stack** | Python · scikit-learn · HTML · JavaScript · Vercel |
| **Architecture** | Trained ML model → Python backend → REST API → HTML/JS frontend |

Mental health data interested me because it sits at the crossroads of biology, behaviour, and ML. But I didn't want to stop at a Jupyter notebook — I wanted to actually deploy the model so someone could interact with it.

I had never connected a Python ML model to a web frontend before. I learned how to serve a trained model through a backend, handle POST requests, return predictions as JSON, and consume that from JavaScript. Every piece of that pipeline was new to me. There were a lot of moments where the frontend and backend just wouldn't talk — CORS errors, JSON formatting issues, Vercel deployment config problems.

Getting it fully working end-to-end — user fills a form, data hits the model, result comes back — was the moment I understood what "full-stack" actually means in practice, not just as a phrase.

---

## Research & Analytics Projects

Built across clinical trials, transcriptomics, and environmental science — the problem domains that matter most in biotech and healthcare.

| Project | What I Built | Key Result |
|---|---|---|
| [🏥 Clinical Data Analysis](https://github.com/Srimant1323/Clinical-data-analysis) | End-to-end analysis of a simulated 600-patient Phase II oncology trial. Spent days learning MCAR/MAR/MNAR — missing data in clinical trials isn't random, it means something. Built 3 structured notebooks: missing data audit, EDA + statistical inference, XGBoost + SHAP. Went and read oncology literature when SHAP showed EGFR as top predictor, to make sure the result made biological sense. | XGBoost CV AUC ~0.86 · Top predictor: EGFR expression · χ² p < 0.001 · PFS/OS survival curves |
| [🦠 COVID-19 RNA-seq PBMC Analysis](https://github.com/Srimant1323/COVID19_rnaseq_pbmc_analysis) | Full RNA-seq pipeline on PBMCs — COVID-19 patients vs healthy controls. Learned what a count matrix was, why you can't run a t-test on raw counts, and what normalisation means before writing a single line of code. | PyDESeq2 · ORA · GSEA · differential expression · immune pathway enrichment |
| [💧 Water Quality Data Analysis](https://github.com/Srimant1323/Water-Quality-Data-Analysis) | EDA on water potability across 10 chemical parameters. First proper data analysis project — picked a real public health dataset deliberately. Learned that EDA is not a step before the analysis, it is the analysis. | 10 parameters · correlation heatmaps · distribution analysis · missing value handling |
| [🧬 Bioinformatics Basic Practice](https://github.com/Srimant1323/Bioinformatics-Basic-Practice) | Core bioinformatics algorithms implemented from scratch in Python — not imported from Biopython, written to internalise the logic. GC content was first. ORF detection took several attempts across all six reading frames. | GC content · ORF detection · reverse complement · Hamming distance · motif search · RNA translation |

---

### 🏥 Clinical Data Analysis

| | |
|---|---|
| **Dataset** | Simulated 600-patient Phase II oncology trial |
| **Stack** | Python · XGBoost · SHAP · scikit-learn · pandas · scipy · matplotlib · seaborn |
| **Notebooks** | 3 structured notebooks + modular `src/` |
| **Best result** | XGBoost CV AUC ~0.86 · Top SHAP predictor: EGFR expression · χ² p < 0.001 |

Clinical trial data was the most complex dataset I had ever worked with. Real patient data is messy in ways that are completely different from Kaggle datasets — missing values aren't random, they mean something. I had to learn the difference between MCAR, MAR, and MNAR from scratch — reading papers, watching explanations, understanding that each type requires a different imputation strategy. That alone took me days.

I built the analysis across three structured notebooks: missing data audit, EDA and statistical inference, then ML and explainability. I used χ² and Mann-Whitney U tests for group comparisons, built survival curves for PFS and OS, then trained XGBoost and used SHAP to explain what drove predictions. When the SHAP beeswarm showed EGFR expression as the top predictor, I went and read about why EGFR matters in oncology — to make sure the result made biological sense, not just statistical sense.

This is the project that taught me that analysis without interpretation is just numbers.

---

### 🦠 COVID-19 RNA-seq PBMC Analysis

| | |
|---|---|
| **Dataset** | PBMCs — COVID-19 patients vs healthy controls |
| **Stack** | Python · PyDESeq2 · pandas · matplotlib · seaborn |
| **Pipeline** | QC → normalisation → differential expression → ORA → GSEA |

RNA-seq was completely new territory. I started with no idea what a count matrix was, what normalisation meant here, or why you couldn't just run a t-test on raw counts. I spent time learning the biology first — what PBMCs are, why they're used in COVID-19 research, what differential expression tells you about immune response.

I worked through the full pipeline step by step: loading raw counts, QC filtering, normalisation via PyDESeq2, identifying differentially expressed genes, then ORA and GSEA for pathway enrichment. Going from a list of gene names to understanding which immune mechanisms were activated in COVID-19 patients felt like actual biological discovery.

The hardest part was understanding the statistics behind DESeq2 — negative binomial distribution, shrinkage estimation — well enough to trust the results. I didn't just run the function. I read the documentation until I understood why each step existed.

---

### 💧 Water Quality Data Analysis

| | |
|---|---|
| **Dataset** | Water potability — 10 chemical parameters |
| **Stack** | Python · pandas · seaborn · matplotlib · Google Colab |

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Srimant1323/Water-Quality-Data-Analysis/blob/main/H20_Potability_EDA.ipynb)

This was one of my first proper data analysis projects. I picked water quality deliberately — it's a real public health problem, not a toy dataset. I wanted to understand what EDA actually means in practice, beyond just plotting a histogram.

I learned to handle missing values properly, build correlation heatmaps that tell you something, and analyse distributions across chemical parameters like pH, hardness, chloramines, and sulfate. The messiness of real environmental data was eye-opening — values were missing in patterns, distributions were skewed, and parameters that should have been correlated weren't. I had to learn to question what I was seeing, not just describe it.

This is the project where I first understood that EDA is not a step before the analysis — it is the analysis.

---

### 🧬 Bioinformatics Basic Practice

| | |
|---|---|
| **Stack** | Python · sequence analysis |
| **Covers** | GC content · ORF detection · Reverse complement · Hamming distance · Motif search · RNA translation |

When I started M.Tech Bioinformatics I could write basic Python but had no idea how biological sequences were computationally processed. I decided the best way to learn was to implement every fundamental algorithm myself — not import Biopython, not copy code, write it from scratch.

GC content was first — simple, but it forced me to think about DNA strings as data. Then reverse complement, which requires understanding base pairing rules. Then ORF detection — scanning all six reading frames for start and stop codons — which took several attempts to get right. Hamming distance, motif search, RNA translation — each one built on the previous.

This repo exists to show that I understand what's happening underneath the tools I use in my bigger projects. Anyone can call a function. Not everyone knows what it's actually computing.

---

## Dashboard & Analytics Tools

### 🏥 Healthcare Analytics Dashboard

| | |
|---|---|
| **Stack** | Microsoft Excel · COUNTIFS · AVERAGEIFS · Pivot Charts |
| **Dataset** | 200 patient records · 2024 |
| **Dashboard** | 6 KPI cards · 6 auto-updating charts · Ward, doctor, diagnosis, outcome breakdowns |

| KPI | Chart |
|---|---|
| Total patients · Avg length of stay · Avg billing | Summary cards — auto-calculated |
| Avg satisfaction · Recovery rate · Active wards | Summary cards — formula-driven |
| Patients by diagnosis | Horizontal bar chart |
| Patient outcomes breakdown | Pie chart |
| Admissions by ward | Column chart |
| Avg satisfaction by doctor | Horizontal bar chart |

I built this to understand how healthcare data is actually used in clinical operations — not in a research notebook, but in the kind of dashboard a hospital administrator opens every morning. Excel was a deliberate choice because most real-world healthcare analytics still runs on Excel, not Python.

I created the 200-patient dataset from scratch and built the entire dashboard on top of it using COUNTIF, COUNTIFS, AVERAGEIF, AVERAGEIFS, and IFERROR in a way where every KPI and chart updates automatically when new patient data is added. The hardest part was designing the summary metrics — figuring out which combinations of conditions gave the most actionable clinical insight. That's a thinking problem, not a technical one.

---

## Technical Skills

*M.Tech Bioinformatics student — biology is my foundation. I've been learning computational tools progressively, applying them to real problems, and taking help from AI, documentation, and online resources wherever needed.*

| Area | Skills | How I got here |
|---|---|---|
| **Wet Lab — Plant Tissue Culture** | Surface sterilisation · explant preparation · MS medium formulation · callus induction · organogenesis · subculturing · aseptic technique · growth regulator optimisation (auxins/cytokinins) | Core academic training — hands-on lab work |
| **Bioinformatics** | RNA-seq · NGS pipelines · variant analysis (VCF) · metagenomics · gene expression analysis · PyDESeq2 · ORA · GSEA · PBMC transcriptomics · sequence analysis · ORF detection | M.Tech coursework + self-built projects |
| **Data Analytics** | Python · pandas · NumPy · SciPy · EDA · data cleaning · missing value imputation (MCAR/MAR/MNAR) · feature engineering · statistical inference · matplotlib · seaborn | Learned through projects — documentation, videos, trial and error |
| **Machine Learning** | scikit-learn · XGBoost · Random Forest · Logistic Regression · SHAP explainability · SMOTE · survival analysis · classification · clustering | Applied to biological and clinical data problems — still learning |
| **Visualisation & BI** | matplotlib · seaborn · Tableau · Power BI · Excel dashboards · Jupyter · Google Colab | Built while making projects readable and presentable |
| **Databases** | SQL · DuckDB | Basic querying — picked up as needed |
| **Web & Deployment** | HTML · CSS · JavaScript · Python backend · Vercel · Netlify | Self-taught to ship projects as live tools, not just notebooks |
| **AI & Browser Tools** | MediaPipe · real-time gesture detection · HTML5 Canvas · particle systems | Explored out of curiosity — learned by building HandRide and Gesture Mirror |
| **Dev Tools** | Git · GitHub · VS Code · virtual environments | Used across all projects |
| **Languages** | Python *(primary)* · SQL · R *(basic)* · JavaScript *(picked up for web projects)* | Python first, others as needed |
| **Domain Knowledge** | Clinical trials · oncology · COVID-19 transcriptomics · healthcare operations · plant biology · environmental data · mental health ML · computational genomics | Driven by project topics I found genuinely interesting |

---

## Currently Working On - Building something at the intersection of healthcare, AI, and data analytics                         

- **Hospital-facing ML app** — designing a tool that brings together patient data, clinical patterns, and ML predictions to support real operational decisions at the ward level. Still in the thinking and architecture phase — figuring out what would actually be useful to a clinician, not just technically impressive.

---

## Contact

📧 [bhardwajsrimant7@gmail.com](mailto:bhardwajsrimant7@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srimant-bhardwaj-13s23a)
[![ORCID](https://img.shields.io/badge/ORCID-Profile-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-6395-1216)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/Srimant1323)
