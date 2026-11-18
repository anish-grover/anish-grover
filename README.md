<p align="center">
  <img alt="Anish Grover, AI/ML Engineer" src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1f3a,55:1f6feb,100:7c3aed&height=210&section=header&text=Hey%2C%20I'm%20Anish%20%F0%9F%91%8B&fontSize=50&fontColor=ffffff&fontAlignY=36&desc=I%20love%20problem%20solving%2C%20and%20turning%20the%20answers%20into%20AI%20people%20actually%20use.&descAlignY=58&descSize=17&animation=fadeIn" />
</p>

<h3 align="center">🧩 I love problem solving. Give me a messy, real-world problem and I'll build the system that makes it boring.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/anish-grover-686741274/"><img src="https://img.shields.io/badge/LinkedIn-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anishgrover72@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Mohali%2C%20Punjab-🇮🇳-1f6feb?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=900&color=58A6FF&center=true&vCenter=true&width=720&height=36&lines=Agentic+AI+%C2%B7+Multi-Modal+Systems+%C2%B7+RL+for+LLMs;%232+in+India+out+of+39%2C000%2B+%C2%B7+Samsung+Solve+for+Tomorrow;Teaching+small+models+to+think+on+ONE+GPU;Open+source+%C2%B7+mlpack+%C2%B7+PyBaMM+%C2%B7+Metaflow+%C2%B7+Kubeflow" />
</p>

---

## 👋 A little about me

I'm **Anish Grover**, an **electronics engineer who ended up building AI agents**. I study ECE at **Thapar Institute** (Class of 2028), and most of my time goes into one question: *what's the actual problem here, and what's the smallest system that makes it go away?*

That question has taken me to stroke-recovery monitoring, hiring fairness, banking security, agent payments, real-estate sales and CRM automation for **Pepsi India**. I've done **five internships**, come **2nd out of 39,000+** in Samsung Solve for Tomorrow 2026, and I contribute to open-source ML libraries like **mlpack**, **PyBaMM**, **Netflix Metaflow** and **Kubeflow**.

> **Most student projects end at a demo video. Mine end with a user.**
> I care less about the model and more about the system around it: the alerting logic, the sync layer, the edge case that breaks it at 2 AM.

```text
🔭  Right now     →  building NeuroTrace · running Grovell · open-source PRs (mlpack, PyBaMM, Kubeflow)
🌱  Learning      →  RL for reasoning (GRPO, RLVR) · physics-constrained models
💬  Ask me about  →  multi-agent systems · multimodal AI · building for Bharat
🤝  Open to       →  internships · research · hackathon teams · open source
```

---

## 🧩 How I solve problems

<table>
<tr>
<td align="center" width="25%">🔍<br><b>Find the real pain</b><br><sub>Not "add AI". What's slow, missed or manual?</sub></td>
<td align="center" width="25%">🛠<br><b>Build the smallest fix</b><br><sub>One system, end to end, before any polish</sub></td>
<td align="center" width="25%">🚀<br><b>Put it in front of a user</b><br><sub>Real people, real data, real feedback</sub></td>
<td align="center" width="25%">🌙<br><b>Make it survive 2 AM</b><br><sub>Noisy signals, no network, edge cases</sub></td>
</tr>
</table>

<p align="center"><sub>That's why NeuroTrace waits for a persistent change in two independent domains before alerting, and why the Distribution CRM works with no internet at all.</sub></p>

---

## 📊 By the numbers

<table>
<tr>
<td align="center" width="20%"><h3>#2</h3><sub>in India · Samsung Solve for Tomorrow · 39,000+ entries</sub></td>
<td align="center" width="20%"><h3>7×</h3><sub>hackathon winner · India, UK, International</sub></td>
<td align="center" width="20%"><h3>5</h3><sub>internships before 3rd year</sub></td>
<td align="center" width="20%"><h3>~40%</h3><sub>fewer reasoning tokens with AXIOM</sub></td>
<td align="center" width="20%"><h3>48×</h3><sub>faster RFP processing with ProcurenAI</sub></td>
</tr>
</table>

---

## 🧠 The one I'm proudest of: NeuroTrace

### [NeuroTrace](https://neuro-trace-v1.vercel.app): a stroke recovery monitor that lives in your phone
🥈 **Runner-up, Samsung Solve for Tomorrow 2026: 2nd out of 39,000+ applications nationwide** · Founder · [Live prototype ↗](https://neuro-trace-v1.vercel.app)

**The problem:** after a stroke, recovery is checked in clinic visits weeks apart, and any decline between visits goes unseen.
**My answer:** a 3–4 minute daily check on the phone the family already owns, with a deeper 6–12 minute session when a clinician wants one.

```text
Daily Pulse (3-4 min) ─┬─► 😐 Face & speech    ─┐
 camera · mic · touch  ├─► ✋ Finger tapping    ─┼─► Personal baseline ─► 3 safety gates ─► Caregiver & clinician
   (all on-device)     └─► ⚡ Reaction & mood   ─┘   (14-21 days,          persistence ·      report in Hindi,
                                                      median / MAD)        2+ domains ·       Punjabi or English
                                                                           laterality
```

- **Personal, not population, baselines:** every patient is compared against *their own* normal, built over 14–21 days.
- **One bad day can't cry wolf:** a change has to persist across sessions and show up in two independent domains before anyone is alerted.
- **Privacy by architecture:** raw audio, video and images never leave the phone, and it works offline.
- **The model explains, it never decides:** a deterministic engine makes the call; a small language model only words it.
- **My part includes Awaaz:** an on-device Whisper speech assistant for patients with aphasia.

---

## 🛠 Things I've built

> Each one started with a problem someone actually had.

| | Project | The problem → what I built | Result |
|---|---|---|---|
| ⚡ | [**AXIOM**](https://axiom123.vercel.app/) | Frontier reasoning needs clusters → RL fine-tuning (GRPO + RLVR) with a 5-head process reward model, on **one GPU** | **~40% fewer** reasoning tokens |
| 💳 | **IntentProof** | AI agents can now spend money → an **MCP payment firewall** that checks every cart against the user's signed intent before PayPal sees it · *PayPal AI Hackathon* | Attack success **92.4% → 0%** on our scripted benchmark |
| 🔎 | **TokenLens** | Nobody knows what a prompt costs until it's sent → **local-first token counter** with code-safe, meaning-preserving compression | Open-source CLI + library |
| 🔐 | **Citadel** | Banks trust whoever holds the session → continuous **behavioural-biometric** authentication, from first keypress to logout | 🥉 3rd, Univ. of Derby |
| 🤖 | **ProcurenAI** | RFPs eat whole afternoons → **multi-agent LLM** pipeline with semantic SKU matching | **~4 h → <5 min** |
| ⚖️ | [**CORTEX**](https://github.com/anishgrover72-droid/cortex) | Black-box hiring is a liability → evidence-based ranking with a **plain-language reason for every decision** and a fairness self-audit | Accountable by design |
| 🏠 | [**Real Talk AI**](https://github.com/anishgrover72-droid/real-talk-ai-site) | In real estate the first reply wins → **WhatsApp LLM agent** that qualifies and books visits in **Hindi, Punjabi & English** | Booked in **<1 min** |
| 📦 | **Distribution CRM** | Sales reps work where the network doesn't → **offline-first** React Native ledger with a Node/TS + PostgreSQL sync engine | **2 h → 10 min** daily |
| 🥤 | **CRM Automation, Pepsi India** | Manual CRM entry and reporting → an **automated pipeline** a real business team uses | In production |
| 🛡 | [**CyberSentinel**](https://github.com/anishgrover72-droid/CyberSentinel) | Hostile traffic hides in normal traffic → ML intrusion detection and response | **92%+** accuracy |

🔬 **Research:** a paper in progress on **battery remaining-useful-life prediction** with physics-constrained generative models.

---

## 🌍 Open source

I fix real bugs in ML libraries people depend on.

| Project | What I've contributed | Status |
|---|---|---|
| **mlpack** (C++) | Fixed heap-buffer-overflow reads in the ARFF loader on malformed headers | ✅ Merged |
| **PyBaMM** | Fixed swapped names in the diffusivity deprecation warning; logging and docs fixes | ✅ Merged · more in review |
| **Netflix Metaflow** | Runtime fixes: non-blocking task-log reads, bounded metadata requests, macOS kqueue timeout | In review |
| **Kubeflow** (Katib, Kale) | Early-stopping status-patch race; comprehension locals in pipeline marshalling | In review |
| **aeon** | numba float32 TypingError in DTW distances; class-tag caching | In review |

---

## 💼 Where I've worked

**🧠 Founder · NeuroTrace** · *Sep 2026 - Present*<br>
Building the stroke-recovery monitor above with a cross-functional team and two neurosurgeon advisors.

**🏗 Founder · [Grovell](https://grovell-website.vercel.app)** · *Present*<br>
My software and AI automation studio, building ERP, inventory and workflow systems for manufacturers, distributors and SMEs in India and abroad.

**🤖 AI/ML Intern · CogNerd** · *May - Jul 2026*<br>
Shipped features in the production Python codebase, from requirements through review and release. Built **Content Studio**, an LLM-assisted content generation and search-visibility feature, tuned against live client feedback.

**🚀 Founder's Office Intern · Welzin AI** · *Mar - Apr 2026*<br>
Tech and strategy support at an early-stage AI startup: competitor analysis of AI products, KPI tracking and process docs.

<details>
<summary><b>Earlier roles</b> (click to expand)</summary>
<br>

**📦 B2B Sales & Data Insights Lead · Leorit India** · *Oct - Dec 2025*<br>
Owned pricing, sales and operational analytics for 2,000+ B2B orders; dashboards improved margin predictability by **~35%**.

**📈 BD & Data Intern · HITGOC** · *Aug - Oct 2025*<br>
Built ML lead-quality scoring models and SQL-backed dashboards that told sales who to call first.

**📊 Data Systems & BD Intern · Orygin AI** · *Jun - Aug 2025*<br>
Automated recurring reports and lead-funnel dashboards, cutting manual effort by **~70%**.

**🤝 BD Intern · Glyptika Studios** · *Jan - Apr 2025*<br>
Funnel analysis and client proposals. This is where I learned to sell what I build.

</details>

---

## 🏆 Wins

| | Result | Event |
|---|---|---|
| 🥈 | **Runner-up, 2nd of 39,000+** | Samsung Solve for Tomorrow 2026 · *NeuroTrace* · 🇮🇳 National |
| 🏆 | **Winner** | Agentic AI Hackathon, University of Ulster · 🇬🇧 UK |
| 🏆 | **Winner** | BIOS Hackathon 2025 · 🎓 University |
| 🥉 | **3rd Place** | Cybersecurity Hackathon, University of Derby · *Citadel* · 🌍 International |
| 🥉 | **3rd Place** | Hackathon, University of Derby · 🌍 International |
| 🏅 | **Top 9 All India** | Case Competition, IIM Bangalore · 🇮🇳 National |

---

## 🌱 Beyond code

- 👥 **Founder, CollabSphere:** I put together a student dev team that delivered **₹90,000** in paid client projects.
- 🚀 **Ambassador, Innovation Mission Punjab** · 🎓 **Campus Ambassador, GeeksforGeeks** · 📋 **McKinsey Forward Program**

---

## 🧰 My toolbox

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

<details>
<summary><b>Full stack</b> (click to expand)</summary>
<br>

| Area | Tools |
|---|---|
| **Languages** | Python · C++ · SQL · JavaScript / TypeScript |
| **AI / ML** | LLMs · RL (GRPO / RLVR) · process reward models · QLoRA / PEFT · vLLM · TRL · multi-agent systems · MCP · RAG · hybrid retrieval (FAISS + BM25) · multimodal models (MediaPipe, Whisper, ViT) · PyTorch · TensorFlow · HuggingFace Transformers |
| **Backend & Infra** | FastAPI · Flask · Node.js / TypeScript · PostgreSQL · REST APIs · Docker · Git · CI · Vercel · Railway |
| **Frontend & Mobile** | React · React Native · offline-first data sync |
| **Data** | SQL analytics · ETL & report automation · KPI dashboards · ML lead scoring |

</details>

---

## 🎓 Education

**Thapar Institute of Engineering & Technology**: B.Tech, Electronics & Communication Engineering · *2024 - 2028 (expected)*<br>
**GMSSS Sector 46, Chandigarh**: Higher Secondary, Science · *2022 - 2024*

---

<p align="center">
  <img src="https://streak-stats.demolab.com?user=anishgrover72-droid&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" />
</p>

---

<h3 align="center">Got a hard problem? I'd love to hear about it.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/anish-grover-686741274/"><img src="https://img.shields.io/badge/LinkedIn-Anish%20Grover-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anishgrover72@gmail.com"><img src="https://img.shields.io/badge/Email-anishgrover72%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center"><i>"A model is a guess. A system is a promise. I build promises."</i></p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anishgrover72-droid&label=Visitors&color=1f6feb&style=flat-square" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,45:1f6feb,100:0b1f3a&height=110&section=footer" />
</p>
