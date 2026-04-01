# 👋 Hi there, I'm Gavin (张家玮)

**Go Backend Developer | Passionate about High Concurrency, Infra & AI**

[cite_start]I am a Software Engineering undergraduate at Ocean University of China (Class of 2027)[cite: 4, 5, 8], focusing on backend development, distributed systems, and infrastructure. I enjoy building robust applications and exploring how to integrate AI (like RAG) into traditional backend architectures.

### 🚀 About Me
* [cite_start]🎓 **Education:** Pursuing a Bachelor's degree in Software Engineering[cite: 5].
* [cite_start]💻 **Tech Focus:** Deep diving into Go internals (Goroutines, Channels, GC) [cite: 10] and high-concurrency network programming.
* [cite_start]🧠 **Currently Learning:** Cloud-native ecosystems (Docker, K8s)[cite: 16], Microservices, and Advanced Algorithm Design.
* [cite_start]📫 **Contact me:** [gavinzhang.cc@gmail.com](mailto:gavinzhang.cc@gmail.com) 

---

### 🛠️ Tech Stack
* [cite_start]**Languages:** Go [cite: 10] (Primary)
* [cite_start]**Frameworks:** Gin, Gorm [cite: 11]
* [cite_start]**Databases & Middleware:** MySQL [cite: 13][cite_start], Redis (Pub/Sub, Lua)[cite: 13], WebSocket
* [cite_start]**Architecture & Concepts:** RESTful API [cite: 11][cite_start], JWT [cite: 11][cite_start], RAG (Retrieval-Augmented Generation) [cite: 16, 27][cite_start], Cache-Aside Pattern [cite: 29]
* [cite_start]**Tools:** Git, Docker, Linux [cite: 16]

---

### 💡 Featured Projects

#### ⚡ [DanmakuX](Link-to-your-repo) - High-Concurrency Real-time Danmaku System
[cite_start]A multi-room real-time messaging system built with **Go** and **WebSocket**[cite: 19].
* [cite_start]**Architecture:** Designed a cross-node message synchronization mechanism using **Redis Pub/Sub**[cite: 22].
* [cite_start]**Performance:** Achieved 100% connection success rate and P95 latency < 10ms under local k6 load testing (80VU).
* [cite_start]**Reliability:** Implemented a 3-layer rate-limiting strategy using Redis Lua scripts and asynchronous MySQL persistence via Channels[cite: 23, 24].

#### 🧠 [Currency Exchange Forum](Link-to-your-repo) - RESTful Backend with RAG
[cite_start]A financial forum backend integrating standard RESTful services with an intelligent QA system[cite: 26, 28].
* [cite_start]**Core Backend:** Developed user authentication, article management, and concurrency-safe like-counting using **Redis INCR**[cite: 28, 30].
* [cite_start]**AI Integration:** Built a custom **RAG** pipeline supporting text chunking, vector retrieval, and automated service degradation[cite: 31].
* [cite_start]**Optimization:** Utilized Cache-Aside strategies to minimize dirty reads and database pressure[cite: 29].

---

### 📊 GitHub Stats
[![Gavin's GitHub stats](https://github-readme-stats.vercel.app/api?username=Gavlnnn&show_icons=true&theme=radical)](https://github.com/Gavlnnn)
