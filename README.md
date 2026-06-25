<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,30,45,2334D0&height=320&section=header&text=Bohan%20Su&fontSize=80&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Computer%20Vision%20%7C%20LLM%20Reasoning%20%7C%20Multi-Agent%20Systems&descAlignY=55&descAlign=50" width="100%" />
</div>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=23&pause=1000&color=2334D0&center=true&vCenter=true&width=1100&lines=Software+Engineering+Student+%40+Wuhan+University;ECCV+2026+Accepted+%7C+WAICA+Workshop+Accepted+%7C+TPAMI+Survey;Computer+Vision+%7C+Structured+Reasoning+%7C+Multi-Agent+Systems;National+IoT+Contest+1st+Prize+(Top+6)+%7C+MCM+2026+Finalist" alt="Typing SVG" style="max-width: 100%; height: auto;" />
  </a>

  <p>
    <a href="mailto:2023302143001@whu.edu.cn">
      <img src="https://img.shields.io/badge/Email-2023302143001%40whu.edu.cn-d14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/BohanSu">
      <img src="https://img.shields.io/badge/GitHub-BohanSu-181717?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a href="https://BohanSu.github.io" target="_blank">
      <img src="https://img.shields.io/badge/Website-BohanSu.github.io-181717?style=for-the-badge&logo=githubpages&logoColor=white" />
    </a>
    <img src="https://img.shields.io/badge/Location-Wuhan,%20China-ff69b4?style=for-the-badge&logo=google-maps&logoColor=white" />
  </p>
</div>

---

## 👋 Positioning
I am an undergraduate in **Software Engineering** at **Wuhan University**. My work runs on three parallel tracks: **visual representation under appearance variation**, **small-model structured scientific reasoning**, and **multi-agent systems for real tasks**. I care more about methods that turn into reproducible, analyzable, deployable systems than isolated benchmark gains.

---

## 🗓 Recent Updates
- **2026.06** — *Reliability-Aware 3D Geometric Injection for Universal Person Re-identification* was **accepted to ECCV 2026**.
- **2026.04** — TPAMI appearance-variation ReID survey §2–§8 drafted with **231 references**; §1 introduction and literature alignment still iterating.
- **2026.03** — PEARL workshop version was accepted by **WAICA Workshop**; the full extension now targets **AAAI**.
- **2026.02** — *SmartPhone Battery: The Moment of Depletion* earned **MCM 2026 Finalist Award** with dual-branch ECM-EKF + PINN approach.
- **2025.11** — Built an A2A-protocol multi-agent system on Holos with routing, validation, fallback, and observability for end-to-end task demos.

---

## 🔬 Research & Ongoing Work

### 1. Reliability-Aware 3D Geometric Injection for Universal Person Re-identification
- **Status:** **ECCV 2026 accepted** (2025.10 – 2026.03)
- **Focus:** Universal ReID under occlusion, clothing change, and cross-modality, with monocular 3D geometry treated as conditionally useful evidence rather than an always-trusted auxiliary.
- **Contributions:** Proposed **UniGeo**, decoupled SMPL parameters into global shape and joint topology, introduced a **Reliability-Aware Gate**, and designed adaptive residual fusion between 2D visual features and 3D structural features.
- **Evidence:** Unified training, comparisons, ablations, gate-correlation analysis, fusion-complexity checks, and perturbation-stability verification across **9 benchmarks**.

### 2. PEARL: Verifiable Curation and Small-Model Learning for Scientific Reasoning Graph Extraction
- **Status:** **WAICA Workshop accepted**; extended version targeting **AAAI** (2026.03 – present)
- **Framework:** Positioned as a complete framework for scientific reasoning graph extraction, organized around "generation-verification decoupling" with training-free data construction layer and student SFT layer.
- **Contributions:** Designed **`graph_spec` intermediate representation** and two-stage semantic-closure workflow in training-free layer; introduced LoRA training pipeline with curriculum learning (nodes → reasoning units → graph_spec → DOT) for small models like Qwen3.5-4B in student SFT layer.
- **Training plan:** Curriculum learning with high-quality supervision from PEARL-produced graphs targeting small-model scientific reasoning graph generation.
- **Progress:** Workshop version accepted; Phase 1 mainline code ready, Gate B local metrics passed, and the full AAAI extension is in progress.

### 3. Appearance Variations in Person Re-Identification: A Survey
- **Status:** Ongoing, **TPAMI survey preparation** (2026.03 – present)
- **Framework:** Reconstructed the field through a three-branch taxonomy of **short-term / long-term / compound** appearance variation and reorganized existing methods through a **robustness vs. generalization** lens.
- **Progress:** Completed §2–§8 main text and **231 references**; current work focuses on evaluation blind spots and metric transferability under appearance variation.

---

## 🚀 Project Experience

### Modular Robot System Development (2023.11 – 2025.08)
- Worked on software architecture for a modular intelligent hardware system and a dual-bus power-communication platform.
- Implemented module coordination, bus arbitration, hot-plug, and bus-merging control logic; supported three PCB iterations and 24V industrial-environment adaptation.
- Achieved **98.5% communication success rate** and about **40% efficiency gain** over traditional solutions.
- Result: **National First Prize (Top 6)** in the National University IoT Design Competition and completion of a provincial innovation project.

### A4R: Guided Smartphone AI Assistant (2025.05 – 2025.08)
- Designed and implemented the **A4R (Ask for Refine)** interaction scheme for ambiguous smartphone-agent requests.
- Built **150+** real interaction samples covering **6 domains** and **16 apps**; designed Guide, Discern, and Validate collaboration.
- On China Unicom real-world tasks, the system reached **64.68% completion rate** and outperformed baselines such as MobileAgent-V2, MobA, and GUI-Explorer on key metrics.

### Xiaomi Quadruped Robot Intelligent Logistics Delivery System (2025.03 – 2025.08)
- Built a complete logistics delivery system on **Xiaomi Quadruped Development Platform** for complex-environment scenarios.
- Decomposed delivery tasks into departure, pickup, path navigation, storage identification, unloading, return, and secondary delivery stages.
- Focused on state transitions, action timing coordination, and reducing failure propagation to improve closed-loop completion rate within time constraints.
- Result: **National Third Prize** in National University Computer System Capability Competition (Xiaomi Cup).

### A2A Protocol Multi-Agent System Development (2025.11.08 – 2025.11.10)
- Built a multi-agent system on **Holos** and **A2A v0.3.0** for uncertain-requirement scenarios.
- Implemented GuideAgent, DiscernAgent, and **8 functional agents**, covering requirement clarification, decomposition, execution, and verification.
- Completed protocol adaptation, SSE streaming response, task-fingerprint deduplication, LLM/rule fallback, and observability debugging for travel-planning and email-collaboration demos.

### SmartPhone Battery: The Moment of Depletion (2026.01 – 2026.02)
- Built a unified physical layer mapping screen, CPU/GPU, communication, and sensor loads to total power consumption, constrained by coulomb-counting dynamics and thermal equilibrium.
- Implemented dual-branch solvers: **2RC equivalent circuit model + Extended Kalman Filter (ECM-EKF)** for real-time SOC estimation and drift correction; **PINN** with identical dynamics in loss function for nonlinear fitting and factor attribution.
- Validated on 8 heterogeneous data sources with over 120,000 time steps, achieving PINN SOC RMSE of 1.24% and overall TTE prediction MAPE of 8.7%.
- Result: **MCM 2026 Finalist Award**.

---

## 🎓 Education
- **Wuhan University**, B.Eng. in Software Engineering — 2023.09 – 2027.06 (expected)
- GPA **3.74 / 4.0**
- **Core courses:** Computer Vision, Frontier Technologies in Artificial Intelligence, Computer Networks, Operating Systems, Software Engineering, Software Quality Assurance and Testing, Database Systems, Object-Oriented Programming
- **Research interests:** visual representation under appearance variations · structured scientific reasoning with small models · multi-agent systems and real-world task systems

---

## 🏆 Selected Awards & Honors
- **National University IoT Design Competition (Huawei Cup)** — National First Prize (**Top 6**)
- **China Youth Sci-Tech Innovation Challenge** — National Second Prize
- **National University Computer System Capability Competition (Xiaomi Cup)** — National Third Prize
- **MCM 2026** — **Finalist**
- **MCM 2025** — Honorable Mention
- **CUMCM Hubei Division** — Second Prize
- **Zheng Geru First-Class Scholarship** — ranked **1st** in the grade-level defense and sole recipient
- **Wuhan University First-Class Scholarship** — twice
- **Merit Student** — twice
- **Outstanding Student Cadre**, **Outstanding Youth League Branch Leader**, **Future College Outstanding Trainee**

---

## 🤝 Student Activities
- **Vice Minister of Publicity**, Student Party Branch Secretaries Joint Council, Wuhan University (2024.09 – 2025.09)
- Supported undergraduate Party-building publicity work and contributed to **100+ published articles**, including theoretical pieces and process optimization work.
- **Project Team Member**, Second Classroom Center, University Youth League Committee (2023.10 – 2024.09)
- Participated in platform quality monitoring, issue investigation, reporting, and fix follow-through for multiple platform issues.

---

## 🛠 Core Skills
- **Programming Languages & Tools:** Python, C/C++, Java, Git, MATLAB
- **Computer Vision & 3D Modeling:** Person Re-ID, SMPL body modeling, 3D Gaussian Splatting, experimental design, ablation analysis, academic writing
- **LLMs & Multi-Agent Systems:** orchestration, routing, validation, observability, and application development with GPT, Claude, and Gemini APIs
- **Embedded Systems:** embedded driver development, modular hardware protocol design, RISC-V / ESP32 dual-architecture platform development

---

## 📫 Contact
- Email: **[2023302143001@whu.edu.cn](mailto:2023302143001@whu.edu.cn)**
- GitHub: **[BohanSu](https://github.com/BohanSu)**
- Website: **[BohanSu.github.io](https://BohanSu.github.io)**
- English Resume: **[CV PDF](https://BohanSu.github.io/files/Bohan_Su_CV_en.pdf)**
- Chinese Resume: **[中文简历 PDF](https://BohanSu.github.io/files/%E8%8B%8F%E6%B8%A4%E6%B6%B5%E7%AE%80%E5%8E%86.pdf)**
