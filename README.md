<p align="center">
  <img src="./banner.gif" alt="Prithvi Kaushik" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prithvi-kaushik/">LinkedIn</a> •
  <a href="mailto:prithvi.k314@gmail.com">Email</a> •
  <a href="https://www.instagram.com/reallyprithvi">Drums</a>
</p>

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

### [daybreak-gp](https://github.com/PrithviKaushik/daybreak-gp) *(Work in Progress)*
Controlled empirical study comparing stationary vs. non-stationary Gaussian Processes for hourly solar PV forecasting on the **SOLETE** dataset (10,968 hourly observations).

- Implementing a 1D non-stationary **Gibbs** kernel (Paciorek & Schervish, 2003) in **GPyTorch** with a neural-network-parameterized length scale $\ell(t)$ optimized via marginal likelihood
- Comparing **RBF** vs. **Gibbs** (and 24-hour **Periodic** compositions) across 24h/48h interpolation and future extrapolation, evaluating both point error (**RMSE**, **MAE**) and uncertainty calibration (**NLPD**, 95% interval coverage)
- Building a reproducible, config-driven pipeline with unit tests, artifact tracking, and a planned **FastAPI** inference service

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
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge)

**Systems & Tooling**
<br>
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

<sub>Previously shipped cross-platform apps (Flutter, Dart, Firebase)—retired from mobile, kept the habit of writing tests.</sub>

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

---

## Off the Clock

- **Drums:** Playing kit and posting covers on [Instagram](https://www.instagram.com/reallyprithvi)
- **Boxing:** Training fundamentals, bag work, and conditioning
- **Linux:** Occasionally breaking my Sway config at 2 AM and pretending it was planned

---

<p align="center">
  <sub><i>"The goal isn't to prove a fancier model wins—it's to know when it's actually worth the complexity."</i></sub>
</p>
