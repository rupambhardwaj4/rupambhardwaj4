# Hi, Nice to Meet You! 👋

[![Email](https://img.shields.io/badge/-Email-0D1117?style=for-the-badge&logo=gmail&logoColor=D14836)](mailto:rupambhardwaj4@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0078D4)](https://www.linkedin.com/in/rupam-bhardwaj-260b61319/)
[![GitHub](https://img.shields.io/badge/-GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white)](https://github.com/rupambhardwaj4)

## 🏋 About Me

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class Student:

    def __init__(self):
        self.name = "Rupam Bhardwaj"
        self.role = "B.Tech Computer Science Engineering Student"
        self.location = "Delhi, India"
        self.focus = ["Frontend Development", "AI Integration", "Data Annotation & LLM Evaluation"]
        self.languages_spoken = ["en_IN", "hi_IN"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find my profile interesting :)")

me = Student()
me.say_hi()
```

Detail-oriented Computer Science student with hands-on experience in frontend development, AI integration, and structured data workflows. Currently pursuing a B.Tech in CSE at Meerut Institute of Technology (2023–2027). Eager to bring meticulous attention to quality, strong written/verbal English, and a solid grasp of AI systems to LLM training pipelines, data annotation, and evaluation work.

---

## 💼 Experience

- **Frontend Developer Intern** — Qualithar Consultancy (OPC) Pvt. Ltd. · *July 2025*
- **Frontend Developer** — QT Consultants Limited (Remote) · *Sept – Nov 2024*
- **Web Development Virtual Intern** — Future Skills Prime (NASSCOM) · *July – Aug 2024*
- **Android Developer Virtual Intern** — EduSkills & Google for Developers · *Jan – Mar 2025*
- **Frontend Developer** — Hackspire 2024 Hackathon · improved user engagement by 40% via CSS3 animations

---

## 🛠️ Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Frontend & Frameworks**

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Framer Motion](https://img.shields.io/badge/-Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![jQuery](https://img.shields.io/badge/-jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Netlify](https://img.shields.io/badge/-Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

**AI / ML Awareness**

![OpenAI](https://img.shields.io/badge/-OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
`LLM concepts` · `Prompt evaluation` · `AI-powered app development`

---

## 🚀 Featured Projects

| Project | Description | Live |
|---|---|---|
| [CampusCode](https://github.com/rupambhardwaj4/CampusCode) | Online code compiler & judge platform — see full breakdown below | — |
| [Portfolio](https://github.com/rupambhardwaj4/Portfolio) | Personal portfolio with smooth animations, lazy loading, and performance optimization across all devices | [Live](https://rupambhardwaj4.github.io/Portfolio/) |
| [Zeost](https://github.com/rupambhardwaj4) | Modern landing page prototype built with React & Framer Motion, deployed via NASSCOM internship CI/CD workflow | [Live](https://zesot.netlify.app/) |
| [Yum Maker](https://github.com/rupambhardwaj4/Yum-Maker) | Recipe generator web app with clean UI/UX — 95+ Google PageSpeed score | [Live](https://yum-maker.netlify.app/) |
| [Velliton HR](https://github.com/rupambhardwaj4/VellitonHr) | HR management platform for recruitment, payroll & compliance with a process-driven interface | — |
| [QT Consultancy](https://github.com/rupambhardwaj4/QT-consultancy) | Consultancy website with responsive design, Privacy Policy & Terms pages | [Live](https://rupambhardwaj4.github.io/QT-consultancy/) |

---

### 🎯 CampusCode — Online Code Compiler & Judge Platform

**[Repository](https://github.com/rupambhardwaj4/CampusCode)** · Node.js · Express · PostgreSQL · Docker · Piston Execution Engine

CampusCode is a full-stack **online code execution and judging platform**, built to let users write, run, and test code directly in the browser — similar in spirit to platforms like HackerRank/LeetCode's code runner, but self-hosted using the open-source **Piston** engine for secure, sandboxed multi-language execution.

#### ✨ Key Features

- **🖥️ In-Browser Code Execution** — Users can write and run code directly on the platform without needing a local dev environment.
- **🐳 Sandboxed Execution via Piston** — Code runs inside an isolated Docker container running the [Piston](https://github.com/engineer-man/piston) engine, preventing unsafe code from affecting the host system.
- **🌐 Multi-Language Support** — Piston's runtime API supports executing code across multiple programming languages through a single unified API (`/api/v2/runtimes`).
- **✅ Automated Test Case Validation** — A dedicated `testcases/` module runs submitted code against predefined inputs/outputs to automatically judge correctness — the core mechanic of a coding-judge system.
- **🗄️ PostgreSQL-Backed Data Layer** — Persistent storage for users, submissions, problems, and results, with a custom migration system (`migrate.js`) to version-control the database schema.
- **🔐 Middleware-Driven Request Pipeline** — Dedicated middleware layer for handling authentication, input validation, and centralized error handling before requests reach route handlers.
- **🛣️ RESTful Route Structure** — Clean separation of concerns via an Express `routes/` layer, keeping API endpoints and page-serving logic organized and maintainable.
- **🖼️ Server-Rendered Views** — Uses a `views/` templating layer to render dynamic pages server-side.
- **🐋 Fully Dockerized Setup** — Two separate Docker Compose files (`docker-compose.piston.yml` and `docker-compose.postgres.yml`) allow the execution engine and database to be spun up independently and reproducibly.
- **⚙️ Developer Utility Scripts** — A `scripts/` folder houses automation helpers (e.g., environment setup, DB seeding, or maintenance tasks) to streamline local development.
- **🧪 Built-in Test Scripts** — Includes `test-conversion.js` and `test-query.js` for verifying data conversion logic and database query correctness during development.

#### 🧰 Tech Stack

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

---

## 🎓 Education

**Meerut Institute of Technology** — B.Tech, Computer Science Engineering *(Sept 2023 – May 2027)**
Coursework: Data Structures, Algorithms, Web Development, Database Management, OOP · Current SGPA: 7.8

**St. Columbus School** — Senior Secondary (CBSE) *(2021 – 2023)*

---

## 📜 Certifications

- Web Development Training — IBM *(July 2025)*
- Python Zero to Hero — GUVI *(Oct 2024)*
- Cybersecurity Essentials — Cisco Networking Academy *(Aug 2023)*
- Android Developer Virtual Internship — Google for Developers *(Jan–Mar 2025)*
- Certificate of Excellence — Unstop Talent Park 2025
- Microsoft Learn Certifications *(June 2024)*
- MongoDB Certifications — Credly Verified *(Aug 2023)*

---

## 🌟 Fun Facts

- I love building **smooth UI animations** and interactive experiences.
- Currently deepening my knowledge of **LLM training pipelines & data annotation**.
- Comfortable with fully remote/async collaboration — reliable setup, multiple remote internships completed independently.

---

> "Coding is not just building applications, it's creating experiences."
