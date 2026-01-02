<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,30,45,2334D0&height=320&section=header&text=Bohan%20Su&fontSize=80&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Building%20Agents%20%7C%20Optimizing%20Systems%20%7C%20Exploring%20Vision&descAlignY=55&descAlign=50" width="100%" />
</div>

<div align="center">
  
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=24&pause=800&color=2334D0&center=true&vCenter=true&width=900&lines=Software+Engineering+Student+@+Wuhan+University;Rank+1+Scholarship+Winner+%7C+GPA+3.7%2F4.0;Researching+Multi-Agent+Systems+%26+ReID;National+IoT+Contest+1st+Prize+Winner;Developing+Real-World+AI+Solutions" alt="Typing SVG" />
  </a>

  <p>
    <a href="mailto:2023302143001@whu.edu.cn">
      <img src="https://img.shields.io/badge/Email_Me-2023302143001%40whu.edu.cn-d14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/BohanSu">
      <img src="https://img.shields.io/badge/GitHub-BohanSu-181717?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <img src="https://img.shields.io/badge/Location-Wuhan,%20China-ff69b4?style=for-the-badge&logo=google-maps&logoColor=white" />
  </p>
</div>

---

### 👨‍💻 **About Me & Highlights**

<table>
  <tr>
    <td width="55%" valign="top">
      <h3>👋 Who I Am</h3>
      <p>
        I am a senior undergraduate majoring in <b>Software Engineering</b> at <b>Wuhan University (National Characteristic Demonstration Software College)</b>.
      </p>
      <p>
        My passion lies in bridging the gap between <b>Academic Algorithms</b> and <b>Production Engineering</b>. I specialize in designing robust <b>Multi-Agent Systems</b> and optimizing <b>Embedded AI</b> pipelines. Currently, I am conducting research on <b>2D-3D Person Re-Identification (ReID)</b> targeting IJCAI submission.
      </p>
      <br />
      <h3>🔭 Core Competencies</h3>
      <ul>
        <li><b>🤖 Multi-Agent Architect:</b> Experienced in dynamic orchestration (A4R), workflow debugging, and tool-use optimization.</li>
        <li><b>⚡ Engineering Optimization:</b> Proven track record in reducing Audio E2E latency to <b>&lt;1.5s</b> and handling concurrency in IoT systems.</li>
        <li><b>📊 Mathematical Modeling:</b> H-Prize winner in MCM, capable of cleaning <b>100k+</b> data rows and building differential equation models.</li>
      </ul>
    </td>
    <td width="45%" valign="top">
      <h3>📈 Academic Stats</h3>
      <img src="https://img.shields.io/badge/GPA-3.7%20%2F%204.0-success?style=social&logo=cachet" /><br/>
      <img src="https://img.shields.io/badge/Major%20Rank-Top%2025%25-blue?style=social&logo=google-scholar" /><br/>
      <img src="https://img.shields.io/badge/Scholarship-Rank%201%20(Grade)-yellow?style=social&logo=authy" /><br/>
      <br/>
      <b>🏆 Top Awards:</b>
      <ul>
        <li>🥇 <b>National 1st Prize</b>, IoT Design Contest (Top 6)</li>
        <li>🥈 <b>National 2nd Prize</b>, "Jiebang Guashuai" Challenge</li>
        <li>📜 <b>Honorable Mention</b>, MCM/ICM (Math Modeling)</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🛠 **The Arsenal**

<div align="center">
  
| **Languages** | **AI & Data Science** | **Embedded & IoT** | **Tools & Dev** |
| :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white) | ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![LLM](https://img.shields.io/badge/-LLM%20API-00A67E?style=flat-square&logo=openai&logoColor=white) | ![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![STM32](https://img.shields.io/badge/-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) ![RISC-V](https://img.shields.io/badge/-RISC_V-545454?style=flat-square&logo=riscv&logoColor=white) | ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white) ![Unity](https://img.shields.io/badge/-Unity-000000?style=flat-square&logo=unity&logoColor=white) |

</div>

---

### 💻 **Featured Projects & Engineering**

> *Detailed breakdown of my key engineering challenges and solutions.*

<details open>
<summary><h3>🤖 1. A4R Multi-Agent Architecture (Holos Platform Challenge)</h3></summary>

* **Role:** Core Architect & Developer (48-hour Hackathon)
* **The Problem:** The native platform lacked state memory, couldn't handle "Intent Uncertainty" (IIUN), and failed in multi-turn interactions.
* **My Solution - A4R (Ask-for-Refine):**
    * **Intelligent Pre-processing:** Designed a trio of agents:
        * `GuideAgent`: Entry point for traffic routing.
        * `ValidateAgent`: Embedded QA validation to fix the multi-turn interaction defect.
        * `DiscernAgent`: Converts fuzzy user intents into actionable tasks.
    * **Engineering Resilience:**
        * Implemented a **"Task Fingerprint"** algorithm to deduplicate tasks and prevent redundant LLM calls.
        * Built a **"LLM + Rule Engine"** dual-track strategy to ensure availability even if the API fails.
        * Achieved full-link tracing for **8 concurrent agents** using unified context IDs.
</details>

<details>
<summary><h3>🧩 2. Modular AI Programming Robot (National 1st Prize)</h3></summary>

* **Role:** System Lead (Logic & Algorithms)
* **Tech Stack:** Python Threading, LLM Prompt Engineering, Audio Processing.
* **Key Technical Contributions:**
    * **Concurrency Control:** Solved critical conflicts between "Real-time Debugging" and "Hardware Control" using a robust Python `threading` architecture.
    * **Prompt Engineering:** Iterated prompts through 3 versions to boost user intent understanding accuracy to **92%**.
    * **Performance:** Optimized the audio end-to-end pipeline, achieving a response time of **< 1.5 seconds**.
</details>

<details>
<summary><h3>🤝 3. General AI Assistant (Jiebang Guashuai National Silver)</h3></summary>

* **Focus:** Dynamic Orchestration & Collaborative Reasoning.
* **Contributions:**
    * Developed key modules for **Agent Workflow**, specifically tool calling and decision logic.
    * Optimized **Inter-Agent Communication Protocols** to enhance robustness in multi-step complex tasks.
</details>

<details>
<summary><h3>🦾 4. Hexbot Embedded Platform</h3></summary>

* **Tech:** RISC-V, ESP32, Sensor Fusion.
* **Achievement:** Independently developed underlying drivers for a dual-architecture system (RISC-V + ESP32), adapting **6 types of sensors**.
* **Impact:** Reduced the learning curve for students by **40%** during pilot testing in experimental classes.
</details>

---

### 🌟 **Leadership & Impact**

* **Party Branch (News & Publicity Dept):** Led a team to publish **100+** articles (including 17 deep-theory pieces), achieving **1000+** avg. views/article. [cite_start]Implemented standardized management for zero errors. [cite: 54, 56]
* [cite_start]**Second Classroom Center:** Responsible for platform QA, identified and fixed **15+ bugs**, improving system stability by **30%**. [cite: 59]

---

### 📊 **My Coding Activity**

<div align="center">
  <img src="https://streak-stats.demolab.com?user=BohanSu&theme=tokyonight&hide_border=true" alt="Streak Stats" />
</div>

<div align="center">
  <sub>Let's connect and build something amazing! 🚀</sub>
</div>

---

<div align="center">
  <p><i>"Code is not just about instructions; it's about solving reality's uncertainty."</i></p>
  <sub>Last Updated: 2026</sub>
</div>
