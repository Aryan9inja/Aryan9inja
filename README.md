<h1 align="center">Hey 👋, I'm Aryan Singh Thakur</h1>
<h3 align="center">Backend Engineer • Systems Programming • AI Systems</h3>

---

### 🚀 About Me

- ⚙️ Backend engineer with **6 months of production experience** at a London-registered B2B SaaS startup (SvaraAI)
- 🔧 Built systems from scratch — **14K req/sec HTTP server in C**, **18.8K req/sec distributed job queue in Go**
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
- **18,800 req/sec** with 100K jobs, 100 concurrent workers — p99 latency **33ms**, zero failed requests

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
- NestJS/Node.js microservices handling **1,000+ API requests/day** across **5+ business clients**
- Production email pipeline via Azure Email Services — **500+ emails/day**, SPF/DKIM/DMARC configured
- AWS EC2 + NGINX + MySQL infrastructure, CI/CD with GitHub Actions

---

### 🛠 Tech Stack

**Languages:** C • C++ • Go • JavaScript • TypeScript

**Backend:** Node.js • NestJS • Express • REST APIs • WebSockets • Microservices

**Frontend:** React • Next.js • TailwindCSS

**Databases:** MySQL • MongoDB • Redis • Vector Search

**AI / Data:** RAG Systems • BM25 Retrieval • LLM Integration (OpenAI, LLaMA) • Semantic Search • OCR

**Infrastructure:** AWS EC2 • NGINX • Linux • Docker • Prometheus • Azure Email Services • GitHub Actions

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
