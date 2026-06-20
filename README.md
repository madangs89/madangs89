<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=260&section=header&text=MADANA%20GS&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%7C%20AI%2FML%20Systems&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=600&lines=Backend+Developer+%7C+Node.js+%26+Redis;Building+AI-Powered+Job+Queue+Pipelines;LLM+Integration+%2B+Real-Time+Systems" alt="Typing SVG" />
</a>

<br/>

![CGPA](https://img.shields.io/badge/CGPA-8.3%2F10-6D28D9?style=flat-square&logo=bookstack&logoColor=white)
![Location](https://img.shields.io/badge/Location-Bengaluru,_India-7C3AED?style=flat-square&logo=googlemaps&logoColor=white)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-4C1D95?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madangs89)
[![Email](https://img.shields.io/badge/Email-Contact_Me-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madangsnaik@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/madangs89)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=madangs89&style=flat-square&color=8B5CF6&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/madangs89?style=flat-square&color=7C3AED&label=FOLLOWERS&logo=github)
![Stars](https://img.shields.io/github/stars/madangs89?style=flat-square&color=6D28D9&label=STARS&logo=github)

</div>

---

## About Me

I'm a B.Tech CS student (CGPA 8.3) who builds backend systems for a living, mostly by accident of liking hard problems more than easy ones. My work sits at the overlap of **AI/LLM pipelines**, **real-time systems**, and **distributed backend architecture** — things like job queues, WebSocket-based services, and schema-validated AI outputs.

Most of what I know comes from shipping actual projects rather than tutorials: building an AI resume pipeline that has to survive real LLM latency, designing a multi-database schema generator that has to work across five different databases, architecting a social platform split into independent services that still need to talk to each other reliably.

I did a virtual internship with **1M1B × IBM SkillsBuild** on AI and sustainability (Dec 2025–Jan 2026), where I worked on responsible AI practices and designed RAG systems for SDG-aligned problems.

**Currently open to:** Backend Engineering roles · AI/ML Engineering roles · Full-stack opportunities · Internships

---

## Tech Stack

**Languages**
![JavaScript](https://skillicons.dev/icons?i=javascript&theme=dark)
![TypeScript](https://skillicons.dev/icons?i=typescript&theme=dark)
![Cpp](https://skillicons.dev/icons?i=cpp&theme=dark)

**Frontend**
![React](https://skillicons.dev/icons?i=react&theme=dark)
![Redux](https://skillicons.dev/icons?i=redux&theme=dark)
![TailwindCSS](https://skillicons.dev/icons?i=tailwind&theme=dark)
![Bootstrap](https://skillicons.dev/icons?i=bootstrap&theme=dark)
![HTML](https://skillicons.dev/icons?i=html&theme=dark)

**Backend & Databases**
![Nodejs](https://skillicons.dev/icons?i=nodejs&theme=dark)
![Express](https://skillicons.dev/icons?i=express&theme=dark)
![MongoDB](https://skillicons.dev/icons?i=mongodb&theme=dark)
![Redis](https://skillicons.dev/icons?i=redis&theme=dark)
![Prisma](https://skillicons.dev/icons?i=prisma&theme=dark)
![Socketio](https://skillicons.dev/icons?i=socketio&theme=dark)

**Tools & Platforms**
![Git](https://skillicons.dev/icons?i=git&theme=dark)
![GitHub](https://skillicons.dev/icons?i=github&theme=dark)
![Docker](https://skillicons.dev/icons?i=docker&theme=dark)
![Postman](https://skillicons.dev/icons?i=postman&theme=dark)
![Vercel](https://skillicons.dev/icons?i=vercel&theme=dark)
![VSCode](https://skillicons.dev/icons?i=vscode&theme=dark)

---

## AI / LLM Work

| Area | What I've Actually Done |
|:--|:--|
| **LLM Integration** | Used Google Gemini API to power resume rewriting and natural-language-to-schema conversion |
| **Structured Output** | Enforced schema validation on LLM outputs so downstream systems never have to guess the shape of the response |
| **RAG Systems** | Designed RAG systems for sustainability use cases during the 1M1B × IBM internship |
| **Async AI Pipelines** | Decoupled LLM calls from request lifecycle using Redis + BullMQ queues, with progress streamed over Socket.IO |
| **Prompt Engineering** | Converted natural language prompts into structured JSON schemas for backend code generation |

---

## Featured Projects

<details>
<summary><b>AI Career Platform — Resume, LinkedIn & Interview Prep</b></summary>
<br/>

An AI tool that takes a resume (PDF/DOCX), parses it into structured data, and rewrites sections like skills, projects, and experience using LLM APIs — with schema-enforced validation so the output is always usable, not just plausible-looking text.

| | |
|:--|:--|
| **Stack** | Node.js, Express, MongoDB, Redis, BullMQ, Socket.IO, Razorpay, LinkedIn OAuth |
| **Architecture** | Async AI job processing via Redis + BullMQ worker queues, with real-time progress over Socket.IO |
| **Data Layer** | Write-behind Redis caching for resume edits, scheduled MongoDB bulk flushes |
| **Monetization** | Credit-based AI quota system integrated with Razorpay payments |
| **Extra Module** | Interview prep covering DSA, OOPS, DBMS, OS, CN — with per-topic progress tracking, bookmarks, and difficulty analytics |
| **Repo** | [GitHub →](https://github.com/madangs89) |

</details>

<details>
<summary><b>Schema Genius — Intelligent Backend Automation System</b></summary>
<br/>

Takes a plain-English prompt and turns it into a structured JSON schema, then generates a production-ready backend codebase from it — CRUD APIs, auth, dummy data, and a README, automatically.

| | |
|:--|:--|
| **Stack** | Node.js, Socket.IO, Redis Pub/Sub, GitHub OAuth |
| **Database Support** | PostgreSQL, MySQL, MongoDB, DynamoDB, Neo4j |
| **Real-Time Layer** | Socket.IO + Redis Pub/Sub for live schema editing updates |
| **Repo Automation** | GitHub OAuth + REST API for one-click repo creation and automated code push |
| **Caching** | Redis-based prompt and data caching for faster repeat generation |
| **Repo** | [GitHub →](https://github.com/madangs89) · [Live →](https://github.com/madangs89) |

</details>

<details>
<summary><b>InstaClone — Real-Time Social Media Platform</b></summary>
<br/>

A social media backend split into independent microservices for Users, Posts, Stories, and Messaging, with real-time delivery across all of them.

| | |
|:--|:--|
| **Stack** | Node.js, Microservices, Socket.IO, Redis Pub/Sub, JWT, Cloudinary |
| **Real-Time** | Distributed messaging and notifications via Socket.IO + Redis Pub/Sub across services |
| **Auth** | JWT-based authentication securing both client-server and inter-service communication |
| **Features** | Reels, stories with view tracking, likes, comments, follow/unfollow, and an integrated chatbot |
| **Media** | Cloudinary integration for uploads across services |
| **Repo** | [GitHub →](https://github.com/madangs89) · [Live →](https://github.com/madangs89) |

</details>

---

## Experience

**AI for Sustainability — Virtual Intern**
1M1B × IBM SkillsBuild (AICTE-supported) · Remote, Bengaluru, India
`Dec 2025 – Jan 2026`

Completed a structured internship covering AI, responsible AI practices, and UN SDG-aligned sustainability concepts. Designed AI and RAG systems aimed at real-world sustainability problems.

`AI` `Responsible AI` `RAG Systems` `Sustainability`

---

## Achievements

| Recognition | Details |
|:--|:--|
| 🥇 1st Place — CosmoHack 1.0 | Solo participant, 700+ participants |
| 🥈 2nd Place — Battle of Bytes Hackathon | AI-powered Resume Analysis System, among 36 teams |
| 🎖️ Honorable Mention — Schema Genius | Recognized for innovation and system-level engineering design |
| 🏐 Kabaddi | Represented local teams in 30+ tournaments |

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=madangs89&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9&ring_color=7C3AED" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=madangs89&theme=tokyonight&hide_border=true&background=0D1117&ring=7C3AED&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=madangs89&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" width="49%"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=madangs89&theme=darkhub&no-frame=true&row=1&column=7&margin-w=8" width="100%"/>

</div>

---

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=madangs89&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9" width="100%"/>

</div>

---

## Current Focus

```yaml
focus:
  learning:
    - System design for high-throughput backends
    - Production-grade RAG architectures
  building:
    - AI Career Platform (resume + interview prep)
    - Schema Genius (AI-driven backend automation)
  exploring:
    - Event-driven microservice patterns
    - LLM orchestration at scale
  open_to:
    - Backend Engineering roles
    - AI/ML Engineering roles
    - Full-stack internships
```

---

## Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-madangsnaik@gmail.com-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:madangsnaik@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-madangs89-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/madangs89)
[![GitHub](https://img.shields.io/badge/GitHub-madangs89-8B5CF6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/madangs89)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=140&section=footer" width="100%"/>

</div>
