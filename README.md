<h1 align="center">Prithvi Kaushik</h1>

<p align="center">
  AI & ML Engineering • B.Tech AI & Data Science • Lead, GDG On Campus USAR
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prithvi-kaushik/">LinkedIn</a> •
  <a href="mailto:prithvi.k314@gmail.com">Email</a>
</p>

---

## About

I build and deploy machine learning systems, with a focus on probabilistic modeling, computer vision, and production inference backends.

- **AI/ML:** Time-series forecasting, Gaussian Processes, applied computer vision, and end-to-end model deployment
- **Engineering:** Reproducible Python pipelines, FastAPI services, Dockerized deployments, and clean system architecture
- **Community:** Organizer (Lead) at Google Developer Groups On Campus USAR, Delhi running technical workshops and industry outreach
- **Environment:** Fedora Sway Spin, Neovim, and terminal-first Linux tooling

---

## Featured Work

### [KERB](https://github.com/PrithviKaushik/kerb)
Human-in-the-loop computer vision system that turns motorsport footage into structured evidence for track-limit steward review (built in 24h at TrackShift 2026).

[![KERB demo video](https://img.youtube.com/vi/0A50hWYAvR0/maxresdefault.jpg)](https://youtu.be/0A50hWYAvR0)
<br>
<sub>▶ Click to watch the demo</sub>

- Built a spatio-temporal pipeline using fine-tuned **YOLO11n**, **ByteTrack**, calibrated boundary geometry, and temporal aggregation to classify incidents as `VIOLATION_CANDIDATE`, `NO_VIOLATION`, or `UNCERTAIN`
- Fine-tuned YOLO11n on camera-specific race footage (0.035 → 0.995 mAP@50 on a 10-image held-out split from the target camera view) with ~12.1 FPS end-to-end tracking on CPU-only hardware
- Served evidence timelines and review workflows via **FastAPI** and **Next.js**

### [daybreak-gp](https://github.com/PrithviKaushik/daybreak-gp)
Time-series forecasting framework using Gaussian Processes in GPyTorch.

- Implemented and compared RBF, Periodic, and Gibbs kernel compositions on the SOLETE dataset
- Exposed forecasting and uncertainty estimates through a FastAPI inference service

---

## Stack

**Machine Learning & Data**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Backend & Deployment**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**Systems & Tooling**
<br>
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

<sub>Also worked with: cross-platform development (Flutter, Dart, Firebase, SQL, FastAPI)</sub>

---

## Current Focus

- **Probabilistic forecasting:** Evaluating kernel compositions (RBF, Periodic, Gibbs) and uncertainty calibration on solar/weather time-series in `daybreak-gp`
- **Production ML systems:** Moving models past notebooks—reproducible evaluation, FastAPI inference services, and containerized deployment
- **Applied LLM systems:** Building reliable, evaluation-driven LLM pipelines and structured tool-use workflows
- **Open source:** Contributing to Python infrastructure and ML tooling repositories

---

## GitHub Activity

<p align="center">
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api?username=PrithviKaushik&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"
  />
  <img
    height="165"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=PrithviKaushik&layout=compact&theme=tokyonight&hide_border=true&hide=dart,html,css"
  />
</p>
