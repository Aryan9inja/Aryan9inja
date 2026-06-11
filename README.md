<h1 align="center">Hey 👋, I'm Aryan Singh Thakur</h1>
<h3 align="center">Backend Engineer • Systems Programming • AI Systems</h3>

---

### 🚀 About Me

- ⚙️ Backend engineer with **6 months of production experience** at a London-registered B2B SaaS startup (SvaraAI)
- 🔧 Built systems from scratch — **14K req/sec HTTP server in C** and **17.04K req/sec distributed job queue in Go**
- 🧠 Work across **systems programming, distributed systems, AI pipelines, and full-stack SaaS**
- 🐧 Linux enthusiast who reads kernel docs for fun

---

### 🔥 Featured Projects

#### ⚙️ GoTaskQ — Distributed Job Queue
→ Redis-backed job queue built from scratch in **Go**
- Priority scheduling via lexicographic score encoding on Sorted Sets
- Atomic Lua-scripted dequeue — eliminates race conditions under concurrent load
- Retry engine with **exponential backoff + jitter**, Dead Letter Queue, job replay
- Prometheus metrics: queue depth, job duration histograms, worker utilization
- Multiple queue support using round robin polling for job processing.
- **76,800 req/sec across 3 queues** zero failed requests (in memory interface)
- **17,040 req/sec across 3 queues** zero failed requests (redis based interface)

🔗 https://github.com/Aryan9inja/gotaskq

---

#### ⚙️ Raw HTTP/1.1 Server in C
→ Event-driven HTTP server built using **POSIX sockets and epoll**, zero external libraries
- Non-blocking I/O with request state machine
- Keep-alive, zero-copy sendfile(), request pipelining
- Full GET/POST parsing, headers, static file serving, EAGAIN/EWOULDBLOCK handling
- **14,000+ req/sec**, sub-millisecond latency — **38% throughput improvement** over fork model

🔗 https://github.com/Aryan9inja/raw-http-c

---

#### 🌾 Krishi Setu — Voice AI for Farmers *(Hackathon Project)*
→ Farmers call one number, speak Hindi or English, get crop/pest/mandi guidance in **under 2 seconds**
- Twilio Conversation Relay for real-time STT/TTS
- Hybrid **BM25 + vector retrieval** over 1,000+ knowledge entries — sub-millisecond query latency
- Swappable LLM client (Groq/OpenAI), stateless WebSocket layer

🔗 https://github.com/Aryan9inja/Krishi-Setu | [Demo](https://youtu.be/o92L3jVlEbw)

---

#### ⚖️ LexGenAI — AI Legal Document Generator
→ RAG-based platform that generates and reviews legal documents
- Classifies every contract clause into Low/Medium/High risk — cuts manual review time by **60%+**
- MongoDB Atlas Vector Search for semantic retrieval
- Live in production with PDF export

🔗 https://github.com/Aryan9inja/LexGenAI | [Live](https://lex-gen-ai.vercel.app/)

---

### 💼 Experience

**Full-Stack Developer Intern @ SvaraAI** *(Oct 2025 – Mar 2026)*
London-registered B2B SaaS startup — Remote
- Developed microservice for domain based email architecture. Created Inbound SMTP using node.js and Outbound
using Azure email services. Created a schema based routing for inbound and outbound email.
- Spotted unauthorized user on companies VM, got to know it was because of open ports. Removed the user using
sudo privelages, also removed the cron job he created. After that secured the system by blocking unused ports and
increased firewall strictness on used ports.
- Completed auth migration from per user based auth to organization based auth with RBAC, zero downtime DB
migrations.
- Created a CI/CD pipeline from scratch that used github webhooks and ran bash scripts on server for deployment.
- Created a custom text editor with font support and style support like lists that converted text to html to be shared
in email for proper rendering.
- Wrote NGINX setup scripts for different services with domain certificate registration.

---

### 🛠 Tech Stack

**Languages:** Go, Typescript, C/C++, SQL (MySQL/PostgreSQL), JavaScript, HTML, CSS

**Frameworks:** React, Next.js, Nest.js, Express, TailwindCSS

**Databases:** MySQL, PostgreSQL, MongoDB, Redis

**Developer Tools:** Git, Github, Azure Cloud, Postman, AWS, Linux, Docker

**Artificial Intelligence:** LLM API’s, Prompt Engineering, Gen-AI, RAG

---

### 🌌 Fun Facts

- 🚀 Fascinated by **Space & Astronomy**
- 🧩 Enjoy reverse engineering and understanding software internals
- ☕ Can debug almost anything with enough coffee

---

### 📫 Connect

<p>
<a href="https://x.com/Aryan_fullstack"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" width="30"/></a>
<a href="https://www.linkedin.com/in/singharyanthakur/"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" width="30"/></a>
</p>

---

⭐ *I build systems to understand how software really works — from the kernel up.*
