<div align="center">

<img src="assets/banner.svg" width="100%" alt="Vaishnavi Kanade – Software Engineer" />

<a href="https://github.com/Vaishnavi-1525">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=36BCF7&center=true&vCenter=true&width=760&height=45&lines=Hi%2C+I'm+Vaishnavi+Kanade+%F0%9F%91%8B;Software+Engineer+Trainee+%40+ESDS;Java+%E2%80%A2+Android+%E2%80%A2+Full-Stack+%E2%80%A2+RAG;AWS+Academy+Graduate+%E2%98%81%EF%B8%8F;Building+things+that+work+end+to+end+%F0%9F%9A%80" alt="typing" />
</a>

<br/>

<a href="https://www.linkedin.com/in/vaishnavi-kanade-b92a08224"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://vaishnavi-1525.github.io/"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:vaishnavikanade1525@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=Vaishnavi-1525&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="views"/>

</div>

<br/>

## 👩‍💻 whoami

```bash
vaishnavi@github:~$ whoami
Vaishnavi Kanade — Software Engineer

vaishnavi@github:~$ cat profile.txt
🎓 B.E. Information Technology Graduate (2026) · PVGCOE Nashik
💼 Software Engineer Trainee @ ESDS Software Solutions [Working]
📊 Ex-Data Science Intern @ Infosys Springboard
☁️ AWS Academy Graduate — Cloud Foundations & Cloud Architecting
🔭 Focus: Full-Stack · Mobile · AI (RAG & Multi-Agent Systems)

vaishnavi@github:~$ status
🟢 Starting my journey as a Software Engineer
```

---

## 💡 About Me

I'm an Information Technology graduate with an interest in software development, AI-powered applications, and backend technologies. I enjoy building practical projects and understanding how software systems work end-to-end.

My experience includes working with **Java, C++ and SQL**, web and mobile development, along with AI technologies such as **RAG, LangChain, LangGraph, and Pinecone**. I gained industry experience during my internship at ESDS Software Solutions and I'm now stepping into a **Software Engineer** role.

Some of my key projects include **ClauseAI**, a multi-agent AI-based contract risk analyzer, and **GramLink-AI**, a web and Android platform designed to connect rural citizens with government services.

---

## 🚀 Technologies & Concepts I've Applied

| 🔥 Concept | What it is | Where I applied it |
|:--|:--|:--|
| **RAG Pipelines** | Grounding LLM answers in your own documents | ClauseAI |
| **Multi-Agent Systems** | Specialist AI agents working together on one task | ClauseAI |
| **Vector Search** | Semantic retrieval with Pinecone | ClauseAI |
| **Android Development** | Native mobile apps with Java & Firebase | GramLink-AI |
| **Role-Based Access Control** | Separate dashboards & permissions per user type | GramLink-AI · Alumni Tracking System |
| **Full-Stack Web Development** | React / Node.js and PHP / MySQL applications | NextStep · Alumni Tracking System |
| **Data Structures & Algorithms** | Problem solving in Java | DSA-Java · 100 Days Challenge |
| **Cloud Fundamentals** | Core AWS services & architecture | AWS Academy (Cloud Foundations & Architecting) |

---

## 🛠️ Projects

> 👇 Click any project to expand it and see how it works.

<details open>
<summary><b>🤖 ClauseAI — AI Contract Risk Analysis</b></summary>
<br/>

AI system that reads and analyzes legal contracts using a **multi-agent architecture** (compliance, finance, operations agents), flags risky clauses, and auto-generates reports.

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

```mermaid
flowchart LR
    A["📄 Contract Upload"] --> B["🔎 Retriever<br/>Pinecone + RAG"]
    B --> C["⚖️ Compliance Agent"]
    B --> D["💰 Finance Agent"]
    B --> E["⚙️ Operations Agent"]
    C --> F["🧠 Orchestrator<br/>LangGraph"]
    D --> F
    E --> F
    F --> G["📊 Risk Report"]
    classDef agent fill:#1f6feb,stroke:#58a6ff,color:#ffffff;
    classDef core fill:#8250df,stroke:#d2a8ff,color:#ffffff;
    class C,D,E agent
    class F core
```

[🔗 View repository](https://github.com/Vaishnavi-1525/ClauseAI-AI-Contract-Risk-Analysis)

</details>

<details>
<summary><b>🏘️ GramLink-AI — Rural Citizen–Government Portal</b></summary>
<br/>

Web + mobile portal bridging rural citizens with government schemes, with role-based access for citizens, admins and officers.

<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

```mermaid
flowchart LR
    U1["👤 Citizen"] --> L["🔐 Role-Based Login"]
    U2["🛡️ Admin"] --> L
    U3["📋 Officer"] --> L
    L --> W["🌐 Web Portal<br/>HTML · CSS · JS"]
    L --> M["📱 Android App<br/>Java"]
    W --> D[("🗄️ Data Layer<br/>Firebase · MySQL")]
    M --> D
    D --> S["🏛️ Government Schemes<br/>& Services"]
    classDef client fill:#1f6feb,stroke:#58a6ff,color:#ffffff;
    classDef core fill:#8250df,stroke:#d2a8ff,color:#ffffff;
    class W,M client
    class L core
```

[🔗 View repository](https://github.com/Vaishnavi-1525/GramLink-AI)

</details>

<details>
<summary><b>🎯 NextStep — Smart Job & Placement Tracker</b></summary>
<br/>

Tracks aptitude tests, interviews and placement drives with auto-sorting and deadline tracking.

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>

```mermaid
flowchart LR
    A["👤 Student"] --> B["⚛️ React.js Interface"]
    B --> C["🟢 Node.js Backend"]
    C --> D["📝 Aptitude Tests"]
    C --> E["🎤 Interviews"]
    C --> F["🏢 Placement Drives"]
    D --> G["⏰ Auto-Sort &<br/>Deadline Tracking"]
    E --> G
    F --> G
    G --> B
    classDef core fill:#8250df,stroke:#d2a8ff,color:#ffffff;
    class G core
```

[🔗 View repository](https://github.com/Vaishnavi-1525/NextStepTracker)

</details>

<details>
<summary><b>🎓 Alumni Tracking System — Mentorship & Networking</b></summary>
<br/>

Connects alumni with students for mentorship and networking, with role-based dashboards for Admin, Students and Alumni.

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>

```mermaid
flowchart LR
    A["🛡️ Admin"] --> L["🔐 Role-Based Login"]
    S["🎓 Student"] --> L
    U["👥 Alumni"] --> L
    L --> DA["📊 Admin Dashboard"]
    L --> DS["📚 Student Dashboard"]
    L --> DU["🤝 Alumni Dashboard"]
    DA --> DB[("🗄️ MySQL")]
    DS --> DB
    DU --> DB
    DS <-->|"Mentorship & Networking"| DU
    classDef core fill:#8250df,stroke:#d2a8ff,color:#ffffff;
    class L core
```

[🔗 View repository](https://github.com/Vaishnavi-1525/Alumni_Tracking_System)

</details>

<details>
<summary><b>🚦 Traffic Congestion Predictor — Real-Time Prediction</b></summary>
<br/>

Predicts traffic levels from time and weather inputs in real time.

<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>

```mermaid
flowchart LR
    A["🕒 Time of Day"] --> C["⚙️ C++ Prediction Logic"]
    B["🌦️ Weather Input"] --> C
    C --> D["🚦 Predicted<br/>Congestion Level"]
    classDef core fill:#8250df,stroke:#d2a8ff,color:#ffffff;
    class C core
```

[🔗 View repository](https://github.com/Vaishnavi-1525/Traffic-Congestion-Predictor)

</details>

---

## 📘 Practice & Consistency

| | Repository | Details |
|:-:|:--|:--|
| 🧮 | [**DSA-Java**](https://github.com/Vaishnavi-1525/DSA-Java) | Data structures & algorithms implemented in Java |
| 🔥 | [**100 Days DSA Challenge**](https://github.com/Vaishnavi-1525/100-Days-Challenge) | ✅ **Completed 🎉** Day 1 → Day 100, daily Java practice |

---

## 💼 Experience Timeline

```mermaid
timeline
    title My Journey
    2022 : Software Development Intern @ Phoenix Computers, Nashik
    2024 : Software Development Intern @ Talent Battle
    2025 : Trainee, S.Dot Training Program @ ETHNUS
    2026 : Data Science Intern @ Infosys Springboard 6.0
         : Software Engineer @ ESDS Software Solutions
```

> 👇 Click a role to see its details.

<details open>
<summary><b>🚀 Software Engineer</b> — ESDS Software Solutions Limited <code>2026 · Working</code></summary>
<br/>

- 🏢 **Organization:** ESDS Software Solutions Limited, Nashik
- 📅 **Duration:** 2026 – Present
- 🎯 **Role:** Software Engineer

</details>

<details>
<summary><b>📊 Data Science Intern (Virtual)</b> — Infosys Springboard Internship 6.0 <code>Jan 2026 – Apr 2026</code></summary>
<br/>

- 🏢 **Organization:** Infosys Springboard Internship 6.0
- 📅 **Duration:** Jan 2026 – Apr 2026
- 🎯 **Role:** Data Science Intern (Virtual)

</details>

<details>
<summary><b>🎓 Trainee, S.Dot Training Program</b> — ETHNUS <code>Jun 2025 – Jul 2025</code></summary>
<br/>

- 🏢 **Organization:** ETHNUS
- 📅 **Duration:** Jun 2025 – Jul 2025
- 🎯 **Role:** Trainee, S.Dot Training Program

</details>

<details>
<summary><b>💻 Software Development Intern</b> — Talent Battle <code>Dec 2024 – Jan 2025</code></summary>
<br/>

- 🏢 **Organization:** Talent Battle
- 📅 **Duration:** Dec 2024 – Jan 2025
- 🎯 **Role:** Software Development Intern

</details>

<details>
<summary><b>💻 Software Development Intern</b> — Phoenix Computers, Nashik <code>Jul 2022 – Aug 2022</code></summary>
<br/>

- 🏢 **Organization:** Phoenix Computers, Nashik
- 📅 **Duration:** Jul 2022 – Aug 2022
- 🎯 **Role:** Software Development Intern

</details>

---

## 🧰 Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=java,cpp,c" alt="Languages"/>

**AI / NLP**<br/>
<img src="https://img.shields.io/badge/RAG%20Pipelines-8A2BE2?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white"/>

<br/><br/>

**Web, Mobile & Backend**<br/>
<img src="https://skillicons.dev/icons?i=react,nodejs,php,androidstudio,firebase,mysql,html,css" alt="Web, mobile and backend"/>

**Cloud & Tools**<br/>
<img src="https://skillicons.dev/icons?i=aws,git,jira" alt="Cloud and tools"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Vaishnavi-1525&theme=tokyonight&hide_border=true" alt="GitHub streak"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Vaishnavi-1525&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Vaishnavi-1525/Vaishnavi-1525/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Vaishnavi-1525/Vaishnavi-1525/output/github-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/Vaishnavi-1525/Vaishnavi-1525/output/github-snake.svg" />
</picture>

</div>

---

<div align="center">

### 📬 Let's Connect

[Email](mailto:vaishnavikanade1525@gmail.com) · [LinkedIn](https://www.linkedin.com/in/vaishnavi-kanade-b92a08224) · [Portfolio](https://vaishnavi-1525.github.io/)

*Excited to build, learn and ship — always happy to talk Java, Android, full-stack or AI — Open to Software Developer roles* 🚀

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" alt="footer"/>

</div>
