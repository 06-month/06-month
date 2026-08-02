<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img alt="Jun Jeon — feed-forward 3D/4D reconstruction, novel view synthesis" src="assets/banner-light.svg" width="100%">
  </picture>
</p>

<p align="center">
  <a href="https://06-month.github.io/home/"><img alt="Homepage" src="https://img.shields.io/badge/Homepage-1A3A5C?style=flat-square&logo=githubpages&logoColor=white"></a>
  <a href="https://archive-06.vercel.app/"><img alt="Research Archive" src="https://img.shields.io/badge/Research_Archive-2C5F8D?style=flat-square&logo=obsidian&logoColor=white"></a>
  <a href="https://6month.tistory.com/"><img alt="Paper Reviews" src="https://img.shields.io/badge/Paper_Reviews-4A6D8C?style=flat-square&logo=rss&logoColor=white"></a>
  <a href="mailto:junjeon@edu.hanbat.ac.kr"><img alt="Email" src="https://img.shields.io/badge/junjeon@edu.hanbat.ac.kr-63758A?style=flat-square&logo=maildotru&logoColor=white"></a>
</p>

I work on **feed-forward 3D/4D scene reconstruction** — recovering geometry and appearance from
unposed multi-view or monocular video in a single pass, without per-scene optimization.
Right now I am most interested in what breaks that promise: dynamic scenes, and inputs degraded
enough that geometry survives while appearance does not.

Fourth-year undergraduate at **Hanbat National University**, graduating Feb. 2027.
Previously an undergraduate researcher at **UNIST Vision & Learning Lab** (3D hand pose)
and **AiRLab** (segmentation, representation learning). Everything on the 3DGS side is self-taught.

---

## Currently

| ID | TRACK | STATE |
| :--- | :--- | :--- |
| `RSCH-01` | Low-light multi-view → clean novel view synthesis. Finding so far: appearance collapses well before geometry does, and feed-forward models collapse hardest | benchmarking |
| `ENGR-01` | On-device human pose estimation for real-time exercise posture assessment | capstone |

Reading in depth: `Ex4DGS` · `Grid4D` · `C3G` / `C4G` · `VGGT` · `AnySplat` · `MoSca`

---

## Selected work

| Repository | What it is | Stack |
| :--- | :--- | :--- |
| [**CLIP2FL_BKD**](https://github.com/06-month/CLIP2FL_BKD) | Balanced knowledge distillation on top of CLIP2FL for long-tail federated learning. Became a KICS 2026 paper | PyTorch |
| [**Satellite-Cloud-Semantic-Segmentation**](https://github.com/06-month/Satellite-Cloud-Semantic-Segmentation) | Three-class cloud segmentation from satellite imagery — thick cloud, thin cloud, cloud shadow | PyTorch, OpenCV |
| [**satellite-building-segmentation**](https://github.com/06-month/satellite-building-segmentation) | Building-footprint segmentation from aerial imagery | PyTorch |
| [**Offline-to-Online-RL**](https://github.com/06-month/Offline-to-Online-Reinforcement-Learning) | Online fine-tuning of offline-pretrained RL policies | PyTorch |
| [**Budgetly**](https://github.com/06-month/HBNU-SWUNIV-ossw-competition25-yee) | OCR-based personal finance web app. 1st place, HBNU Open Source Competition 2025 | Python, OCR |

---

## Publication

**Balanced Knowledge Distillation (BKD) for Long-Tail Federated Learning Based on CLIP2FL**
<samp>Jun Jeon</samp>, Minu Baek, Sangkeum Lee<sup>†</sup> — *KICS Winter Conference, 2026*

---

## Notes

I keep a linked research notebook — 135+ notes on 3D representation, rendering, and the geometry
behind them, written as I read rather than after.

[3D Gaussian Splatting](https://archive-06.vercel.app/wiki/3d-gaussian-splatting) ·
[NeRF](https://archive-06.vercel.app/wiki/nerf) ·
[4D Scaffold-GS](https://archive-06.vercel.app/wiki/4d-scaffold-gs) ·
[MoSca](https://archive-06.vercel.app/wiki/mosca) ·
[ATSplat](https://archive-06.vercel.app/wiki/atsplat) ·
[**all notes →**](https://archive-06.vercel.app/wiki-map)

---

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-1A3A5C?style=flat-square&logo=python&logoColor=white">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-1A3A5C?style=flat-square&logo=pytorch&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1A3A5C?style=flat-square&logo=numpy&logoColor=white">
  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-1A3A5C?style=flat-square&logo=opencv&logoColor=white">
  <img alt="CUDA" src="https://img.shields.io/badge/CUDA-1A3A5C?style=flat-square&logo=nvidia&logoColor=white">
  <br>
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-2C5F8D?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2C5F8D?style=flat-square&logo=docker&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-2C5F8D?style=flat-square&logo=linux&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-2C5F8D?style=flat-square&logo=git&logoColor=white">
  <img alt="Neovim" src="https://img.shields.io/badge/Vim-2C5F8D?style=flat-square&logo=vim&logoColor=white">
</p>

<sub>Working knowledge: 3D Gaussian Splatting · novel view synthesis · multi-view and camera geometry · COLMAP · semantic segmentation</sub>

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/06-month/06-month/output/snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/06-month/06-month/output/snake.svg">
    <img alt="contribution graph" src="https://raw.githubusercontent.com/06-month/06-month/output/snake.svg" width="100%">
  </picture>
</p>

---

<!-- Optional. Delete this whole block if the numbers ever read thinner than the work does. -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=06-month&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=6FA8DC&text_color=8B98A5&card_width=340">
    <img alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=06-month&layout=compact&langs_count=6&hide_border=true&bg_color=00000000&title_color=1A3A5C&text_color=63758A&card_width=340">
  </picture>
</p>

<p align="center">
  <sub><a href="https://06-month.github.io/home/">Full CV and publication list →</a></sub>
</p>
