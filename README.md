# Hey, I'm Sanidhya Sharma 👋

### Full-Stack Developer · AI/ML Enthusiast · Freelancer

I build **production-grade web applications** that solve real-world problems — from AI-powered railway optimization engines to intelligent travel platforms serving real users. Currently a CS student who ships code that works at scale.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanidhya-sharma-43894a430)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sanidhyasharma50005@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](https://voyage-ai-orpin.vercel.app/)

---

## 🔥 What I Bring to the Table

```
✅ Full-stack apps from architecture to deployment
✅ AI/ML integration (Google Gemini, OR-Tools, Constraint Solvers)
✅ Real-time systems (WebSockets, live dashboards)
✅ Production databases with RLS security policies
✅ Payment integration (Razorpay)
✅ Docker containerization & CI/CD
✅ Clean, tested, documented code
```

---

## 🚀 Featured Projects

### 🚂 [BlockOptim — AI Railway Block Planning System](https://github.com/Sanidhyasharma50005/blockoptim-ai-assistant)
> **SIH-Level Full-Stack Decision Support System for Indian Railways**

An **AI-powered optimization engine** that automates railway block section scheduling using **Google OR-Tools CP-SAT constraint programming**. Built for division controllers managing 22+ trains across complex single/double-line networks.

🔴 **[Live Demo →](https://blockoptim-ai-assistant.onrender.com/)**

**What makes this impressive:**
- 🧠 **Exact Constraint Solver** — OR-Tools CP-SAT with multi-objective optimization (not heuristics)
- 📊 **Interactive D3.js Gantt Charts** — Real-time time-distance string charts with animated re-optimization
- ⚡ **Sub-60ms Warm-Start Re-solve** — Rolling horizon with `AddHint()` warm-starting
- 🔒 **100% Hard Safety Compliance** — Zero constraint violations (headway, crew HOS, track mutual exclusion)
- 🤖 **AI Chat Assistant** — Context-aware railway operations chatbot
- 🐳 **Dockerized** — Production-ready with `docker-compose`
- ✅ **Tested** — Full pytest suite covering solver, baseline, and explainer modules

**Tech:** `Python` `FastAPI` `OR-Tools CP-SAT` `WebSockets` `D3.js` `Docker` `NumPy` `SciPy`

<details>
<summary>📸 Screenshots (click to expand)</summary>
<br>

| Time-Distance Gantt Chart | Network Topology |
|:---:|:---:|
| ![Gantt](https://github.com/Sanidhyasharma50005/blockoptim-ai-assistant/blob/main/slide_assets/1_time_distance_gantt.png?raw=true) | ![Topology](https://github.com/Sanidhyasharma50005/blockoptim-ai-assistant/blob/main/slide_assets/2_network_topology.png?raw=true) |

| AI Explainability Drawer | KPI Benchmark Dashboard |
|:---:|:---:|
| ![Explainer](https://github.com/Sanidhyasharma50005/blockoptim-ai-assistant/blob/main/slide_assets/3_ai_explainability_drawer.png?raw=true) | ![KPI](https://github.com/Sanidhyasharma50005/blockoptim-ai-assistant/blob/main/slide_assets/4_kpi_benchmark_dashboard.png?raw=true) |

</details>

---

### 🌴 [Voyage — Smart India Travel Assistant & AI Trip Planner](https://github.com/Sanidhyasharma50005/travel-assistant)
> **Production SaaS Platform with Auth, Payments, and AI-Powered Itineraries**

A **full-featured travel platform** with AI trip planning, real-time train/flight/bus booking advisors, live weather, GPS-based "Near Me" discovery, and integrated Razorpay payments — deployed on Vercel with zero cold starts.

🟢 **[Live App →](https://voyage-ai-orpin.vercel.app/)**

**What makes this impressive:**
- 🤖 **AI Trip Planner** — Google Gemini 2.0 Flash generates day-by-day itineraries with cost estimates
- 🚆 **Train Booking Engine** — Custom railway fare calculator, 120-day IRCTC availability engine, 600+ stations
- ✈️ **Flight & Bus Advisors** — Airport/terminal matching with nearest-station geolocation
- 🔐 **Full Auth + RLS** — Supabase Auth with PostgreSQL Row-Level Security & privilege escalation prevention triggers
- 💳 **Razorpay Payments** — Pro subscription system with replay-attack-proof order ledger
- 📱 **Responsive Design** — Mobile-first with bottom nav, dark luxury theme + tropical identity fusion
- 🌦️ **Live APIs** — Open-Meteo weather, real-time currency converter, Haversine distance sorting

**Tech:** `Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `Supabase` `PostgreSQL` `Google Gemini AI` `Razorpay` `Vercel`

---

## 🛠️ Tech Stack

<table>
<tr>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React" />
<br><b>React 19</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="Next.js" />
<br><b>Next.js 16</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript" />
<br><b>TypeScript</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=tailwind" width="48" height="48" alt="Tailwind" />
<br><b>Tailwind CSS</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=python" width="48" height="48" alt="Python" />
<br><b>Python</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" alt="FastAPI" />
<br><b>FastAPI</b>
</td>
</tr>
<tr>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=supabase" width="48" height="48" alt="Supabase" />
<br><b>Supabase</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL" />
<br><b>PostgreSQL</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker" />
<br><b>Docker</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=vercel" width="48" height="48" alt="Vercel" />
<br><b>Vercel</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=d3" width="48" height="48" alt="D3.js" />
<br><b>D3.js</b>
</td>
<td align="center" width="110">
<img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git" />
<br><b>Git</b>
</td>
</tr>
</table>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sanidhyasharma50005&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sanidhyasharma50005&theme=tokyonight&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanidhyasharma50005&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" />
</p>

---

## 💼 Open for Freelance Work

I'm available for **freelance web development** projects. Whether you need a landing page, a full-stack SaaS, or an AI-integrated application — I deliver production-ready code, on time.

| What I Build | |
|:---|:---|
| 🌐 Full-Stack Web Apps | React, Next.js, Python backends |
| 🤖 AI-Integrated Products | LLM APIs, optimization engines, chatbots |
| 📊 Dashboards & Data Viz | D3.js, real-time WebSocket dashboards |
| 🔐 Auth & Payment Systems | Supabase Auth, Razorpay, Stripe |
| 🐳 Deployment & DevOps | Docker, Vercel, Render, CI/CD |

### 📩 Let's Work Together
**Email:** [sanidhyasharma50005@gmail.com](mailto:sanidhyasharma50005@gmail.com)  
**LinkedIn:** [Sanidhya Sharma](https://www.linkedin.com/in/sanidhya-sharma-43894a430)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Sanidhyasharma50005&style=flat-square&color=blue" alt="Profile Views" />
</p>

<p align="center"><i>⚡ "I don't just write code — I ship products."</i></p>
