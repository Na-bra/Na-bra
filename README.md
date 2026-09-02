# Hi, I'm Oluwajomiloju 👋

I'm a full-stack developer working mainly in the MERN stack, with a growing focus on backend systems and applied Python. I like taking an idea from a rough spec to something that actually runs in production — APIs, auth, data models, and the deployment pipeline that gets it all live.

## About Me

I build web applications end to end: REST APIs, database schemas, authentication, and the frontend that sits on top of it. Most of my production work is Node.js/Express/MongoDB/React, but I'm not tied to the stack — I also work in Python, mostly for backend tooling and, more recently, computer vision.

Right now I'm a software engineering student, splitting time between coursework, an internship focused on infrastructure and deployment for a production business application, and independent projects where I get to make my own architectural calls. The independent projects tend to be where I push furthest technically — that's where a marketplace app with real role-based auth turned into a Python video pipeline with its own face-detection and clustering logic.

## What I'm Working On

- **FluxCutter** — a desktop tool that finds a specific person across a video and cuts their appearances into one reel. The full pipeline (detect → track → group → export) runs end to end via CLI and a desktop UI. Current focus is keyframe-based seeking, to cut down on the decode cost that dominates runtime today.
- **Deployment infrastructure** — evaluating self-hosted PaaS setups (Coolify on Hetzner Cloud) for internship deployment work, alongside writing up the architecture decisions as I go.

## Tech Stack

**Languages**
`JavaScript (ES6+)` `Python` `Java` `HTML` `CSS`

**Frontend**
`React` `Tailwind CSS`

**Backend**
`Node.js` `Express.js` `REST APIs` `JWT Authentication`

**Databases**
`MongoDB` `Mongoose`

**AI / ML & CV**
`OpenCV` `scikit-learn` `Pandas` — content-based filtering, face detection/embedding, identity clustering

**Tools & Platforms**
`Git` `GitHub` `GitHub Actions` `Vercel` `Render` `Cloudinary` `Swagger / OpenAPI`

## Featured Projects

### [FluxCutter](https://github.com/Na-bra/flux-cutter)
A Python desktop application that isolates one person's appearances across a video and compiles them into a single exported reel. It detects faces (OpenCV YuNet), links detections into tracks, groups tracks into identities using ArcFace embeddings, and exports a merged clip through an in-process PyAV pipeline. What makes it worth pointing to isn't just that it works — it's the amount of real engineering behind getting it to work reliably: memory profiling that cut peak usage from ~5GB to ~1GB, a documented RGB/BGR channel-swap bug that was silently dropping detections, and 115 tests covering the pipeline without needing a display.
**Tech:** Python, OpenCV, ArcFace/ONNX, PyAV, CustomTkinter, PyInstaller, GitHub Actions

### [Nile Market](https://github.com/Na-bra/nilemarket)
A full-stack campus marketplace connecting student buyers and sellers, deployed live. Built with proper production concerns in mind: JWT auth, role-based access control, rate limiting, Helmet for secure headers, and listing moderation before anything goes public.
**Tech:** React, Node.js, Express, MongoDB, JWT
🔗 [nilemarket.vercel.app](https://nilemarket.vercel.app)

### [NutritionOS](https://github.com/Na-bra/nutritionOS)
A MERN-based meal planning and health tracking platform — BMI/calorie monitoring with personalized meal recommendations layered on top of a standard auth/data-model foundation.
**Tech:** MongoDB, Express, React, Node.js

### [Recommendation Agent](https://github.com/Na-bra/recommendation-agent)
A content-based movie recommendation system using similarity scoring over user preferences — a smaller project, but a useful data-science-adjacent counterpart to the web app work.
**Tech:** Python, Pandas, scikit-learn

## Open Source

Outside of my own repos, I've contributed pull requests to other developers' projects that have been merged in (reflected in GitHub's Pull Shark achievement).

## Currently Learning / Exploring

- Keyframe-based video seeking (to replace brute-force frame decoding in FluxCutter)
- Backend architecture and system design at a deeper level
- Self-hosted deployment infrastructure — Coolify on Hetzner Cloud

## GitHub Stats

![Oluwajomiloju's GitHub stats](https://github-readme-stats.vercel.app/api?username=Na-bra&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Na-bra&layout=compact&hide_border=true)

## Connect With Me

- LinkedIn: [linkedin.com/in/oluwajomiloju-ajani](https://www.linkedin.com/in/oluwajomiloju-ajani/)
- GitHub: [@Na-bra](https://github.com/Na-bra)
