<div align="center">

# Hi, I'm Oluwajomiloju

**Full-Stack Developer — MERN Stack · Backend Systems · Applied Python**

</div>

<br>

## About Me

I build web applications end to end: REST APIs, database schemas, authentication, and the frontend that sits on top of it. Most of my production work is Node.js/Express/MongoDB/React, but I'm not tied to the stack — I also work in Python, mostly for backend tooling and, more recently, computer vision.

I'm currently a software engineering student, splitting time between coursework, an internship focused on infrastructure and deployment for a production business application, and independent projects where I get to make my own architectural calls. The independent projects tend to be where I push furthest technically — that's where a marketplace app with real role-based auth turned into a Python video pipeline with its own face-detection and clustering logic.

<br>

## What I'm Working On

<table>
<tr>
<td width="50%" valign="top">

**FluxCutter**

A desktop tool that finds a specific person across a video and cuts their appearances into one reel. The full pipeline — detect → track → group → export — runs end to end via CLI and a desktop UI. Current focus is keyframe-based seeking, to cut down on the decode cost that dominates runtime today.

</td>
<td width="50%" valign="top">

**Deployment Infrastructure**

Evaluating self-hosted PaaS setups (Coolify on Hetzner Cloud) for internship deployment work, alongside writing up the architecture decisions as I go.

</td>
</tr>
</table>

<br>

## Tech Stack

<table>
<tr>
<td valign="top"><b>Languages</b></td>
<td>JavaScript (ES6+) · Python · Java · HTML · CSS</td>
</tr>
<tr>
<td valign="top"><b>Frontend</b></td>
<td>React · Tailwind CSS</td>
</tr>
<tr>
<td valign="top"><b>Backend</b></td>
<td>Node.js · Express.js · REST APIs · JWT Authentication</td>
</tr>
<tr>
<td valign="top"><b>Databases</b></td>
<td>MongoDB · Mongoose</td>
</tr>
<tr>
<td valign="top"><b>AI / ML &amp; CV</b></td>
<td>OpenCV · scikit-learn · Pandas — content-based filtering, face detection/embedding, identity clustering</td>
</tr>
<tr>
<td valign="top"><b>Tools &amp; Platforms</b></td>
<td>Git · GitHub · GitHub Actions · Vercel · Render · Cloudinary · Swagger / OpenAPI</td>
</tr>
</table>

<br>

## Featured Projects

<details open>
<summary><b>FluxCutter</b> — Python · OpenCV · ArcFace/ONNX · PyAV · CustomTkinter</summary>
<br>

A desktop application that isolates one person's appearances across a video and compiles them into a single exported reel. It detects faces (OpenCV YuNet), links detections into tracks, groups tracks into identities using ArcFace embeddings, and exports a merged clip through an in-process PyAV pipeline. What makes it worth pointing to isn't just that it works — it's the amount of real engineering behind getting it to work reliably: memory profiling that cut peak usage from ~5GB to ~1GB, a documented RGB/BGR channel-swap bug that was silently dropping detections, and 115 tests covering the pipeline without needing a display.

🔗 [github.com/Na-bra/flux-cutter](https://github.com/Na-bra/flux-cutter)

</details>

<details>
<summary><b>Nile Market</b> — React · Node.js · Express · MongoDB · JWT</summary>
<br>

A full-stack campus marketplace connecting student buyers and sellers, deployed live. Built with proper production concerns in mind: JWT auth, role-based access control, rate limiting, Helmet for secure headers, and listing moderation before anything goes public.

🔗 [github.com/Na-bra/nilemarket](https://github.com/Na-bra/nilemarket) · [nilemarket.vercel.app](https://nilemarket.vercel.app)

</details>

<details>
<summary><b>NutritionOS</b> — MongoDB · Express · React · Node.js</summary>
<br>

A MERN-based meal planning and health tracking platform — BMI/calorie monitoring with personalized meal recommendations layered on top of a standard auth/data-model foundation.

🔗 [github.com/Na-bra/nutritionOS](https://github.com/Na-bra/nutritionOS)

</details>

<details>
<summary><b>Recommendation Agent</b> — Python · Pandas · scikit-learn</summary>
<br>

A content-based movie recommendation system using similarity scoring over user preferences — a smaller project, but a useful data-science-adjacent counterpart to the web app work.

🔗 [github.com/Na-bra/recommendation-agent](https://github.com/Na-bra/recommendation-agent)

</details>

<br>

## Open Source

Outside of my own repos, I've contributed pull requests to other developers' projects that have been merged in (reflected in GitHub's Pull Shark achievement).

<br>

## Currently Learning / Exploring

- Keyframe-based video seeking, to replace brute-force frame decoding in FluxCutter
- Backend architecture and system design at a deeper level
- Self-hosted deployment infrastructure — Coolify on Hetzner Cloud

<br>

<div align="center">

## Connect

[LinkedIn](https://www.linkedin.com/in/oluwajomiloju-ajani/) &nbsp;·&nbsp; [GitHub](https://github.com/Na-bra)

</div>
