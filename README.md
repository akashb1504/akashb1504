<h1 align="center">Hi there, I'm Akash B 👋</h1>
<h3 align="center">Data Science Postgrad · ML/DL Engineer · Building AI systems that reason, retrieve, and explain</h3>

<p align="center">
  <a href="mailto:akash2481810@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://linkedin.com/in/akashb1504"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/akashb1504"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

I'm completing my **Integrated MSc in Data Science** at Amrita University (2021 – Aug 2026). I build end-to-end ML/DL systems and applied Generative AI products — from research-grade intrusion detection models to production-ready RAG chatbots and multi-agent LLM pipelines — with hands-on experience applying these skills at ISRO's National Remote Sensing Centre and MARS Telecom Systems.

---

### 🛠️ Technical Skills

**Programming:** Python, SQL, Git
**Machine Learning & Deep Learning:** Classification, Regression, Time Series Forecasting, Imbalanced Learning, Model Evaluation, Hyperparameter Tuning, TensorFlow/Keras, PyTorch
**Generative AI & LLMs:** Transformers, Hugging Face, LangChain, Retrieval-Augmented Generation (RAG), Prompt Engineering, Agentic AI, Multi-Agent Systems, Function Calling, Embeddings, Semantic Search, Vector Databases
**Data Engineering & Analysis:** ETL Pipelines, Data Preprocessing, EDA, Feature Engineering, Statistical Testing, PDF Parsing, Information Retrieval
**Deployment & Tools:** FastAPI, Streamlit, REST APIs, Docker, AWS, Pinecone, GitHub Actions
**Visualization / BI:** Power BI, Excel, Matplotlib, Seaborn

---

## 💼 Experience

**Project Intern — National Remote Sensing Centre, ISRO** · Jun 2025 – Apr 2026 · Hyderabad, Telangana
- Processed and analyzed large-scale geospatial satellite datasets to derive long-term (2003–2017) global and regional atmospheric trends across monthly, seasonal, and annual scales
- Designed a scalable preprocessing pipeline converting ~69M HDF5 records (2021–2024) to optimized Parquet format, achieving ~90% storage reduction and enabling efficient large-scale analytics and ML workflows
- Validated satellite-derived retrievals against ground observations using regression (R² = 0.83) and delivered uncertainty/bias analysis to support Land Surface Temperature (LST) algorithm development

**Data Analyst Intern — MARS Telecom Systems Pvt. Ltd** · May 2024 – Jul 2024 · Hyderabad, Telangana
- Analyzed four years (2020–2024) of municipal property tax data to identify seasonal, zone-wise, and usage-based revenue trends
- Built and optimized time-series forecasting models (ARIMA, SARIMA, SARIMAX, Prophet, Exponential Smoothing) with hyperparameter tuning, improving forecast accuracy by ~20% for FY 2024–2026
- Developed interactive dashboards and delivered data-driven recommendations supporting tax planning, resource allocation, and operational decision-making

---

## 🚀 Featured Projects

### 🩺 [MediBot — AI Medical Assistant Chatbot](https://github.com/akashb1504/Medical-Chatbot)
An end-to-end medical Q&A system combining general LLM reasoning with **PDF-grounded RAG**.
- Engineered an NLP retrieval pipeline — PDF parsing, recursive text chunking, dense vector embeddings, and semantic search — using FastEmbed and Pinecone for context-aware retrieval
- Built a hybrid response framework with source attribution and automatic fallback to general LLM reasoning when document evidence is unavailable
- Interactive Streamlit interface supporting multi-document conversational querying
- **Tech:** LLaMA 3.1 (Groq) · LangChain · Pinecone · FastEmbed · FastAPI · Streamlit

### 🔬 [Agentic AI Research Copilot](https://github.com/akashb1504/Research-Copilot)
A **multi-agent AI research assistant** (Planner, Search, Reader, Verifier, Writer, Critic, Revision) that autonomously generates structured, cited research reports from any topic.
- Built an end-to-end agent orchestration pipeline integrating web search, source scraping, cross-source verification, and iterative report refinement with LangChain and Groq-hosted LLaMA models
- Implemented production-grade resilience: source prioritization, state management, automatic retry with exponential backoff, model fallback, and Markdown export
- **Tech:** LangChain · LLaMA 3.3 70B (Groq) · Streamlit · BeautifulSoup · DuckDuckGo Search

### 🔐 IoMT Intrusion Detection — Benchmarking ML, DL & Lightweight Transformers
An intrusion detection system for healthcare IoMT networks under extreme class imbalance, benchmarked on 9M+ traffic records (CICIoMT2024 dataset).
- Designed a tabular-to-text transformation pipeline enabling TinyBERT and ELECTRA on network traffic features, alongside Random Forest and CNN baselines
- Improved minority-class (benign) recall from 0.06 (Random Forest) to 0.24 (TinyBERT), achieving 97.3% accuracy while identifying performance/inference-throughput trade-offs for deployment
- **Tech:** PyTorch · Hugging Face Transformers · Scikit-learn · TensorFlow/Keras

### 🕸️ Darknet Traffic Detection and Characterization
A research paper applying deep learning to classify darknet vs. benign network traffic.
- Benchmarked five feature selection methods (Mutual Information, Random Forest, RFE, XGBoost, Autoencoder)
- Implemented and compared CNN, LSTM, and a hybrid CNN+LSTM classifier
- **Tech:** Python, TensorFlow, Keras, Scikit-learn

### 📧 Email Spam Detection — Hybrid Random Forest + LSTM
A confidence-routed hybrid classifier: fast Random Forest handles high-confidence cases, low-confidence predictions are escalated to a deep LSTM model.
- Random Forest (TF-IDF, 97.8% accuracy) with a 0.8 confidence threshold routing ~12% of samples to LSTM (95.7% accuracy on rejected samples)
- Combines shallow-model speed with deep-model accuracy on ambiguous cases
- **Tech:** Scikit-learn, TensorFlow/Keras, NLTK

### 🎓 JEE Closing Rank Prediction
An ML/DL system predicting JEE closing ranks from ~15,000 historical admission records (2019–2024, web-scraped from RankMatrix).
- Compared Linear Regression, Random Forest, XGBoost, LightGBM, and an MLP — LightGBM performed best (R² 0.988, MAE 240.88)
- Includes trend analysis by institute, category, branch, and seat pool
- **Tech:** Scikit-learn, XGBoost, LightGBM, TensorFlow/Keras

### 🩺 Breast Cancer Prediction
A diagnostic ML pipeline classifying tumors as malignant or benign, deployed as an interactive Streamlit app.
- Random Forest feature importance for feature selection; benchmarked Logistic Regression, SVM, XGBoost (up to 97.4% accuracy)
- Live prediction interface with pre-saved scaler and model
- **Tech:** Scikit-learn, XGBoost, Streamlit

---

## 📊 Other Notable Work
- **Corn Leaf Disease Detection** — CNN + Compact Convolutional Transformer (CCT) for crop disease classification
- **Used Car Price Prediction** — Regression modeling with statistical significance testing (T-test, F-test)
- **Rainfall Prediction** — Comparative ML modeling (SVC, Random Forest, XGBoost, Logistic Regression) with class balancing
- **Power BI Weather & Air Quality Dashboard** — Real-time weather/AQI dashboard using WeatherAPI
- **Ferns & Petals Sales Analysis** — Excel-based sales and customer behavior dashboard for a gifting retailer

---

## 🎓 Education
**Integrated MSc Data Science** — Amrita University, Coimbatore (2021 – Aug 2026)
Higher Secondary & Secondary Education — Kendriya Vidyalaya Adoor

## 📜 Certifications
- Python for Data Science and Machine Learning Bootcamp — Udemy
- Google Prompting Essentials — Coursera
- Business Analytics with Excel: Elementary to Advanced — Coursera
- Google Data Analytics Professional Certificate — Coursera
- Data Analysis and Visualization with Power BI — Coursera

## 📫 Get in Touch
- 📧 akash2481810@gmail.com
- 💼 [linkedin.com/in/akashb1504](https://linkedin.com/in/akashb1504)

Open to collaborating on ML/DL, Generative AI, and data-driven projects — feel free to reach out!
