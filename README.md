<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,100:8c52ff&height=120&section=header" width="100%"/>
</p>

<div align="center">
  
# Adnan Oktar · Oka · 安宇寬

### Applied Data Scientist & Machine Learning Pipeline Engineer
**Politeknik Elektronika Negeri Surabaya (PENS) — Applied Data Science**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adnanoktar-ds/)
[![Email](https://img.shields.io/badge/Email-adnanoktar.ds%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:adnanoktar.ds@gmail.com)
[![Location](https://img.shields.io/badge/Location-Surabaya%2C%20Indonesia-gray?style=flat&logo=googlemaps&logoColor=white)](#)
[![Website](https://img.shields.io/badge/Website-adnanoktar.vercel.app-8c52ff?style=flat&logo=vercel&logoColor=white)](https://adnanoktar.vercel.app)
[![Portfolio](https://img.shields.io/badge/Technical_Portfolio-4_Flagship_Systems-111111?style=flat&logo=git&logoColor=white)](#-featured-engineering-systems)

<br/>

> *"In everyone's life, at some time, our inner fire goes out. It is then burst into flame by an encounter with another human being."* — *Albert Schweitzer*

Applied Data Science practitioner focused on building production-grade machine learning pipelines, multimodal computer vision systems, and resilient cloud architectures.

</div>

---

## ◇ Core Engineering Competencies

* **Multimodal Computer Vision & High-Dimensional Search:** Dense visual representation extraction via OpenAI CLIP (ViT-B/32), FAISS vector indexing (< 200 ms GPU latency across 20,400+ cards), and local texture verification via ORB keypoints and RANSAC homography.
* **Applied Machine Learning & Resilient LLM Orchestration:** Dual-pass structured prompting, 6-tier cascading failover circuit breakers mitigating cloud quota exhaustion (HTTP 429), and Two-Stage Retrieval pipelines with real-time SSE token streaming.
* **Data Engineering & Production Cloud Pipelines:** Autonomous scheduled ETL workflows via APScheduler and GitHub Actions, fault-tolerant batch checkpointing (	ry...finally), serverless database connection pool persistence, and PostgreSQL/Supabase management.

---

## ◇ Technical Stack & Tools

<div align="center">
  <p>
    <strong>Machine Learning & Deep Learning</strong><br/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI_CLIP-412991?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=flat&logo=ultralytics&logoColor=black" />
  <img src="https://img.shields.io/badge/FAISS-00599C?style=flat&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  
    </p>
  <p>
    <strong>LLM & Generative AI Systems</strong><br/>
  <img src="https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=flat&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Structured_Prompting-JSON-009688?style=flat" />
  <img src="https://img.shields.io/badge/Protocol-Server--Sent_Events_(SSE)-blue?style=flat" />
  
    </p>
  <p>
    <strong>Data Engineering & Backend Architecture</strong><br/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy_ORM-D71F00?style=flat&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask_REST_API-000000?style=flat&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Scheduler-APScheduler-336791?style=flat" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />

    </p>
  <p>
    <strong>Analytics, Cloud & DevOps</strong><br/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=black" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" />
  </p>
</div>

---

## ◇ Featured Engineering Systems

### 1. [REGOKEMON](https://github.com/Bejochan/pokemon-card-value-analytic-tool) — Multimodal Visual Retrieval & Card Valuation Engine
> **Computer Vision & High-Dimensional Vector Search**  
> Python 3.12 · PyTorch (CUDA) · OpenAI CLIP (ViT-B/32) · FAISS · YOLOv8 · OpenCV · Supabase · GitHub Actions

* **High-Throughput Vector Retrieval:** Indexes **20,400+ card variations** using 512-dimensional CLIP visual embeddings, executing cosine similarity search via FAISS IndexFlatIP with **< 200 ms GPU latency**.
* **Dual-Model Inference & Verification:** Combines global semantic classification (Model 1 CLIP) with localized physical defect detection (Model 2 YOLOv8) and fine-grained ORB/RANSAC keypoint re-ranking across top 150 candidates.
* **Automated Data Ingestion:** Engineered unattended GitHub Actions cron pipeline executing scheduled batch upserts of live TCGPlayer & Cardmarket pricing into a Supabase PostgreSQL instance.

🔗 **[View Repository](https://github.com/Bejochan/pokemon-card-value-analytic-tool)**

<br/>

### 2. [ELYSIA](https://github.com/Bejochan/conversational-video-game-recommendation-assistant) — Conversational Recommender & 6-Tier Cascading Failover Engine
> **Conversational AI & High-Availability Architecture**  
> Python 3.10 · Google Gemini API · Flask (SSE) · NumPy · Pandas · Vanilla JS · Render

* **6-Tier Cascading Failover Architecture (Commit 9ed7315):** Automated sequential fallback circuit breaker (gemini-3.5-flash primary &rarr; 3.6-flash &rarr; 3.7-flash &rarr; 3.8-flash &rarr; 3.5-flash-lite &rarr; lash-latest) completely mitigating HTTP 429 quota exhaustion.
* **Two-Stage Hybrid Retrieval:** Stage 1 fast mathematical candidate pruning (< 50 ms across 24,082 titles via 3D Euclidean DNA distance + Jaccard genre similarity) paired with Stage 2 Neural LLM Re-Ranking strictly enforcing negative conversational constraints.
* **Real-Time Streaming UX:** Zero-dependency word-by-word token delivery via Server-Sent Events (SSE) and client-side dynamic SVG 3D Playstyle DNA polygon rendering, deployed live on Render.

🔗 **[View Repository](https://github.com/Bejochan/conversational-video-game-recommendation-assistant)** · 🌐 **[Live Cloud Demo](https://elysia-video-game-recommendation.onrender.com/)**

<br/>

### 3. [VibePlay](https://github.com/Bejochan/video-games-recommendation-system) — Interactive Storefront & Hybrid Recommender System
> **Applied Machine Learning & Resilient Data Ingestion**  
> Python 3.10 · Scikit-Learn · Flask REST API · RAWG API · Steam Web API · Vanilla JS · Vercel

* **Fault-Tolerant Checkpoint Scraping:** Persistent 	ry...finally extraction pipeline with automated batch state auto-flushing every 50 games to progress_temp.csv, regex Steam IDR currency normalization, and lexical NSFW content filtering.
* **Psychographic Profiling & Mood Modulation:** Maps player temperament across 3 continuous polar axes via a 12-item situational questionnaire with dynamic real-time mood vector coordinate shifting (15%–35%).
* **Multidimensional Radar Visualization:** Projects hybrid similarity scores (Euclidean playstyle distance + Jaccard genre overlap + soft-constraint budget penalty) onto interactive 6-axis hexagonal polygon radar charts.

🔗 **[View Repository](https://github.com/Bejochan/video-games-recommendation-system)** · 🌐 **[Live Web App](https://vibeplay-recommendation-system.vercel.app/)**

<br/>

### 4. [Sistem Prediksi ISPU](https://github.com/tegarkusuma12/Web-ISPU) — Regional Air Quality Forecasting & Streaming Pipeline
> **Time-Series Data Engineering & Streaming Architecture**  
> Python 3.10 · APScheduler · Docker · PostgreSQL (Supabase) · SQLAlchemy ORM · Flask REST API · Leaflet.js

* **Autonomous Scheduled Ingestion:** Concurrent hourly worker via APScheduler daemon pulling real-time atmospheric data across all 38 regencies and cities in East Java with **99.9% pipeline uptime**.
* **Database Resilience & Timezone Integrity:** Configured SQLAlchemy connection recycling (pool_recycle=280, pool_pre_ping=True — Commit fb5ef20) eliminating cloud cold-start TCP dropouts and enforced UTC timestamp casting (Commit 2fb9994) for deterministic 24-hour rolling windows.
* **Interactive GIS Dashboard:** Dynamic choropleth map with time-slider machine vision forecasting 6 criteria air pollutants (PM2.5, PM10, CO, NO2, SO2, O3) under Indonesian environmental ministry standards.

🔗 **[View Repository](https://github.com/tegarkusuma12/Web-ISPU)** · 🌐 **[Live Dashboard](https://web-prediksi-ispu.vercel.app/)**

---

## ◇ GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=Bejochan&show_icons=true&bg_color=0a0a0a&title_color=8c52ff&text_color=e2e8f0&icon_color=8c52ff&border_color=8c52ff" alt="Adnan Oktar's GitHub Stats" />
  <br/><br/>
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Bejochan&layout=compact&bg_color=0a0a0a&title_color=8c52ff&text_color=e2e8f0&icon_color=8c52ff&border_color=8c52ff" alt="Adnan Oktar's Top Languages" />
</p>

---

## ◇ Off-Duty Logs & Culture Fit

When I'm not architecting pipelines or fine-tuning models, you can find me exploring cinema, books, and gaming backlogs:

<p align="center">
  <a href="https://backloggd.com/u/Bejo/"><img src="https://img.shields.io/badge/Backloggd-%235F85FF?style=flat&logo=retroarch&logoColor=white" /></a>
  <a href="https://letterboxd.com/Bejochan/"><img src="https://img.shields.io/badge/Letterboxd-%23FF8000?style=flat&logo=Letterboxd&logoColor=white" /></a>
  <a href="https://www.goodreads.com/user/show/182595097-bejo"><img src="https://img.shields.io/badge/Goodreads-%23754214?style=flat&logo=goodreads&logoColor=white" /></a>
  <a href="https://steamcommunity.com/profiles/76561198847624087/"><img src="https://img.shields.io/badge/Steam-%2300ADEE?style=flat&logo=Steam&logoColor=white" /></a>
  <a href="https://open.spotify.com/user/312ablatv2yks3ugfrjx4hwvrbhm?si=32dbc7dda30943f1"><img src="https://img.shields.io/badge/Spotify-%231ED760?style=flat&logo=Spotify&logoColor=white" /></a>
  <a href="https://www.instagram.com/adnan._oktar/"><img src="https://img.shields.io/badge/Instagram-%23E4405F?style=flat&logo=Instagram&logoColor=white" /></a>
  <a href="https://discord.com"><img src="https://img.shields.io/badge/Discord-bejochan-%235865F2?style=flat&logo=Discord&logoColor=white" /></a>
</p>

### ↳ Curated Coding Playlists
Atmospheric playlists curated for deep focus during model training and data analysis sessions:
* 🫐 **[Blueberry Cheesecake](https://open.spotify.com/playlist/6mZDThXiUq5Eo7tAWcUEvW)**
* 🍨 **[Cassis Affogato](https://open.spotify.com/playlist/5dxWhbv5Egq39CqkONp5rh)**
* 🍎 **[Apple Strudel](https://open.spotify.com/playlist/7meEffakruv51EDBHAuNuX)**

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,100:8c52ff&height=100&section=footer" width="100%"/>
</p>