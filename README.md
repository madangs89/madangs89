<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=260&section=header&text=MADANA%20GS&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%7C%20AI%2FML%20Systems&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=600&lines=Backend+Developer+%7C+Node.js+%26+Redis;Building+AI-Powered+Job+Queue+Pipelines;LLM+Integration+%2B+Real-Time+Systems" alt="Typing SVG" />
</a>

<br/>

![CGPA](https://img.shields.io/badge/CGPA-8.6%2F10-6D28D9?style=flat-square&logo=bookstack&logoColor=white)
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

I'm a CS student in Bengaluru with a habit of asking "wait, how would this actually break?" — which is mostly how I ended up in backend work instead of frontend.

What pulls me in is the messy middle of a system: what happens when an LLM call takes 4 seconds but your user is still on the page, how five different databases can share one schema definition without someone crying, how a "social media app" is secretly four small apps pretending to be one. Backend problems are mostly invisible until they break, and then suddenly very visible — I like that part.

I spent Dec 2025–Jan 2026 in a virtual internship with **1M1B × IBM SkillsBuild**, poking at responsible AI practices and building RAG systems aimed at sustainability problems — a nice change from job queues and CRUD APIs.

Right now I'm looking at backend, AI/ML, and full-stack roles — basically anything where I get to ask "how would this actually break?" professionally.

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

## Things I've Built With LLMs

| Area | The Actual Problem I Was Solving |
|:--|:--|
| **LLM Integration** | Used Google Gemini to rewrite resume content — turns out "make this sound better" is a surprisingly hard prompt to get consistent |
| **Structured Output** | Forced LLM responses into a strict schema so the rest of the app never has to guess what shape came back |
| **RAG Systems** | Built retrieval-based systems during the 1M1B internship, pointed at sustainability questions instead of the usual chatbot demo |
| **Async AI Pipelines** | LLM calls are slow, users don't want to stare at a spinner — so I queue the work with Redis + BullMQ and stream progress over Socket.IO instead |
| **Prompt → Schema** | Built a pipeline that turns a plain English sentence into a working JSON schema and backend code — genuinely still feels like magic when it works |

---

## Featured Projects

<details>
<summary><b>AI Career Platform — Resume, LinkedIn & Interview Prep</b></summary>
<br/>

The interesting problem here: LLM calls are slow and unpredictable, but nobody wants to sit on a loading screen waiting for their resume to get rewritten. So instead of calling the LLM directly in the request, I queue the job (Redis + BullMQ), let the user keep doing other things, and stream progress back over Socket.IO as it finishes.

It parses an uploaded PDF/DOCX, rewrites the skills/projects/experience sections with an LLM, and forces the output into a fixed schema so it's never just "AI rambling" — it's always something the rest of the app can actually use.

| | |
|:--|:--|
| **Stack** | Node.js, Express, MongoDB, Redis, BullMQ, Socket.IO, Razorpay, LinkedIn OAuth |
| **The async problem** | Job queue decouples slow LLM work from the page the user is staring at |
| **Data layer** | Write-behind Redis caching for edits, with scheduled MongoDB bulk flushes so writes aren't hammering the DB constantly |
| **Payments** | Credit-based AI usage tied to Razorpay, so people pay for what they actually use |
| **Bonus module** | An interview prep tracker (DSA, OOPS, DBMS, OS, CN) that flags your weak topics instead of just listing questions |
| **Repo** | [GitHub →](https://github.com/madangs89) |

</details>

<details>
<summary><b>Schema Genius — Intelligent Backend Automation System</b></summary>
<br/>

What if you described a backend in plain English and it just... existed? That's the question this project chases. You type something like "users have posts, posts have comments," and it generates an actual JSON schema and a working backend off of it — CRUD APIs, auth, dummy data, a README — across five different databases (PostgreSQL, MySQL, MongoDB, DynamoDB, Neo4j).

The fun part was making the schema editor live: changes sync over Socket.IO + Redis Pub/Sub so multiple edits don't stomp on each other, and a GitHub OAuth integration pushes the generated code straight to a new repo.

| | |
|:--|:--|
| **Stack** | Node.js, Socket.IO, Redis Pub/Sub, GitHub OAuth |
| **Databases supported** | PostgreSQL, MySQL, MongoDB, DynamoDB, Neo4j |
| **Live editing** | Socket.IO + Redis Pub/Sub keeps schema edits in sync in real time |
| **Repo automation** | GitHub OAuth + REST API — one click, and the generated code lands in a new repo |
| **Caching** | Redis caches prompts and data so regenerating doesn't redo work it's already done |
| **Repo** | [GitHub →](https://github.com/madangs89) · [Live →](https://github.com/madangs89) |

</details>

<details>
<summary><b>InstaClone — Real-Time Social Media Platform</b></summary>
<br/>

Cloning Instagram sounds simple until you realize it's not one app — it's four. Users, Posts, Stories, and Messaging all got split into their own services here, which meant the actual challenge wasn't the features, it was making four strangers talk to each other reliably without one going down and taking the rest with it.

Messaging and notifications run on Socket.IO + Redis Pub/Sub across services in real time, JWT handles both user logins and the service-to-service trust, and Cloudinary deals with media so the app itself isn't storing images.

| | |
|:--|:--|
| **Stack** | Node.js, Microservices, Socket.IO, Redis Pub/Sub, JWT, Cloudinary |
| **The hard part** | Keeping four independent services talking in real time without coupling them tightly |
| **Auth** | JWT secures both client logins and the service-to-service requests behind the scenes |
| **Features** | Reels, stories with view tracking, likes, comments, follow/unfollow, and a built-in chatbot |
| **Media** | Cloudinary handles uploads so services stay lightweight |
| **Repo** | [GitHub →](https://github.com/madangs89) · [Live →](https://github.com/madangs89) |

</details>

---

## Experience

**AI for Sustainability — Virtual Intern**
1M1B × IBM SkillsBuild (AICTE-supported) · Remote, Bengaluru, India
`Dec 2025 – Jan 2026`

Spent six weeks on AI and responsible AI practices, then put it to use designing RAG systems aimed at UN SDG-aligned sustainability problems — a different kind of "AI project" than the usual chatbot.

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

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=madangs89&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9" width="100%"/>

</div>

---

## Current Focus

```yaml
focus:
  learning:
    - How to design backends that don't fall over under load
    - Better ways to structure RAG pipelines
  building:
    - AI Career Platform (resume + interview prep)
    - Schema Genius (prompt-to-backend generator)
  exploring:
    - Splitting things into services without overcomplicating them
    - Getting more out of LLMs without burning tokens
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
