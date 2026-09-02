<div align="center">

# Hi, I'm Oluwajomiloju 👋

### Full-Stack Developer — MERN Stack · Backend Systems · Applied Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwajomiloju-ajani/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Na-bra)

</div>

<br>

## 🧭 About Me

I build web applications end to end — REST APIs, database schemas, authentication, and the frontend that sits on top of it. Most of my production work is Node.js/Express/MongoDB/React, but I'm not tied to the stack — I also work in Python, mostly for backend tooling and, more recently, computer vision.

I'm currently a software engineering student, splitting time between coursework, an internship focused on infrastructure and deployment for a production business application, and independent projects where I get to make my own architectural calls. The independent projects tend to be where I push furthest technically — that's where a marketplace app with real role-based auth turned into a Python video pipeline with its own face-detection and clustering logic.

<br>

## 🚧 What I'm Working On

<table>
<tr>
<td width="50%" valign="top">

**🎬 FluxCutter**

A desktop tool that finds a specific person across a video and cuts their appearances into one reel. The full pipeline — detect → track → group → export — runs end to end via CLI and a desktop UI. Current focus is keyframe-based seeking, to cut down on the decode cost that dominates runtime today.

</td>
<td width="50%" valign="top">

**⚙️ Deployment Infrastructure**

Evaluating self-hosted PaaS setups (Coolify on Hetzner Cloud) for internship deployment work, alongside writing up the architecture decisions as I go.

</td>
</tr>
</table>

<br>

## 🛠️ Tech Stack

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**AI / ML & Computer Vision**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Tools & Platforms**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

<br>

## 🌟 Featured Projects

<details open>
<summary><b>🎬 FluxCutter</b></summary>
<br>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

A desktop application that isolates one person's appearances across a video and compiles them into a single exported reel. It detects faces (OpenCV YuNet), links detections into tracks, groups tracks into identities using ArcFace embeddings, and exports a merged clip through an in-process PyAV pipeline.

What makes it worth pointing to isn't just that it works — it's the engineering behind getting it to work reliably: memory profiling that cut peak usage from ~5GB to ~1GB, a documented RGB/BGR channel-swap bug that was silently dropping detections, and 115 tests covering the pipeline without needing a display.

🔗 **[github.com/Na-bra/flux-cutter](https://github.com/Na-bra/flux-cutter)**

</details>

<details>
<summary><b>🛒 Nile Market</b></summary>
<br>

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

A full-stack campus marketplace connecting student buyers and sellers, deployed live. Built with proper production concerns in mind: JWT auth, role-based access control, rate limiting, Helmet for secure headers, and listing moderation before anything goes public.

🔗 **[github.com/Na-bra/nilemarket](https://github.com/Na-bra/nilemarket)** · [nilemarket.vercel.app](https://nilemarket.vercel.app)

</details>

<details>
<summary><b>🥗 NutritionOS</b></summary>
<br>

![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

A MERN-based meal planning and health tracking platform — BMI/calorie monitoring with personalized meal recommendations, secure authentication, and progress tracking on a responsive dashboard.

🔗 **[github.com/Na-bra/nutritionOS](https://github.com/Na-bra/nutritionOS)**

</details>

<details>
<summary><b>🎥 Recommendation Agent</b></summary>
<br>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

A content-based movie recommendation system using similarity scoring over user preferences, built in a Jupyter notebook and deployed as an interactive app via Streamlit.

🔗 **[github.com/Na-bra/recommendation-agent](https://github.com/Na-bra/recommendation-agent)** · [live demo](https://recommendation-agent-jet.vercel.app)

</details>

<br>

## 🤝 Open Source

Outside of my own repos, I've contributed pull requests to other developers' projects that have been merged in (reflected in GitHub's Pull Shark achievement).

<br>

## 📚 Currently Learning / Exploring

- Keyframe-based video seeking, to replace brute-force frame decoding in FluxCutter
- Backend architecture and system design at a deeper level
- Self-hosted deployment infrastructure — Coolify on Hetzner Cloud

<br>

<div align="center">

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/oluwajomiloju-ajani/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Na-bra)

</div>
