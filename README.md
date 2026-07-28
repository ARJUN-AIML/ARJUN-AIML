<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=230&section=header&text=ARJUN%20S&fontSize=64&fontColor=C9B8FF&fontAlignY=36&desc=AI%20Systems%20Engineer%20·%20Machine%20Learning%20Engineer%20·%20Full-Stack%20AI%20Developer&descAlignY=56&descAlign=50&animation=fadeIn" />

</div>

<br/>

```
$ whoami --verbose

> arjun.s
> role         : AI/ML Engineer, Full-Stack Developer
> location     : Tiruchirappalli, India
> education    : B.E. CSE (AI & ML), 3rd Year — Saranathan College of Engineering
> uptime       : shipping systems, not scripts, since 2023
> last_metric  : 270ms → 132ms CPU inference latency (-51%) on YOLO-Vision-X
> status       : OPEN_TO_INTERNSHIP [ AI/ML · Software Engineering · Research ]
```

<div align="center">

<a href="mailto:arjunselvaraj0107@gmail.com"><img src="https://img.shields.io/badge/Email-5B21B6?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/arjun-s-aiml"><img src="https://img.shields.io/badge/LinkedIn-4C1D95?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/ARJUN-AIML"><img src="https://img.shields.io/badge/GitHub-6D28D9?style=flat-square&logo=github&logoColor=white" /></a>
<a href="https://leetcode.com/u/Arjun_AIML/"><img src="https://img.shields.io/badge/LeetCode_165+-2D1B4E?style=flat-square&logo=leetcode&logoColor=FFA116" /></a>
<img src="https://komarev.com/ghpvc/?username=ARJUN-AIML&label=views&color=6D28D9&style=flat-square" />

</div>

<br/>

## Why this profile, not another AI portfolio

Most student AI repos stop at "the model trained." Mine stop at **"the system holds up under real constraints"** — latency budgets, CPU-only hardware, concurrent users, zero-downtime failure modes. Every project below ships with a number, because a claim without a benchmark is just a vibe.

<table>
<tr><td width="33%" align="center"><b>51%</b><br/><sub>inference latency cut<br/>(YOLO-Vision-X, GPU→CPU)</sub></td>
<td width="33%" align="center"><b>&lt;14ms</b><br/><sub>query response, zero backend<br/>(AnswerFlow)</sub></td>
<td width="33%" align="center"><b>0</b><br/><sub>production errors<br/>(Velora, 42 languages)</sub></td></tr>
</table>

<br/>

## Systems I've built

<details open>
<summary><b>🎯 YOLO-Vision-X</b> — real-time object detection engineered for CPU-only edge hardware</summary>
<br/>

Replaced the standard Ultralytics wrapper with a hand-tuned native OpenVINO IR pipeline, removing the GPU dependency entirely.

```diff
- baseline (Ultralytics wrapper, GPU-assumed): 270ms / inference
+ optimized (native OpenVINO IR, CPU-only):    132ms / inference   (-51%)
```

- 80-class COCO tracking with persistent IDs across concurrent camera streams, ~7.5 FPS real-time
- Validate-before-commit camera switching — stream never drops to black on hardware failure
- Multi-model switching persists detector state across streams without restarting FastAPI
- Intrusion-zone alerts · 20Hz SSE telemetry dashboard · auto snapshot gallery · CSV export

`Python` `FastAPI` `YOLOv8n-seg` `Intel OpenVINO` `WebSocket/SSE` `Tailwind CSS`
→ [github.com/ARJUN-AIML/YOLO-Vision-X](https://github.com/ARJUN-AIML/YOLO-Vision-X)

</details>

<details>
<summary><b>🔎 AnswerFlow</b> — semantic search that never leaves the browser</summary>
<br/>

Proof that not every retrieval system needs a server round-trip. Vectorization, ranking, and fuzzy correction all run client-side.

| Property | Value |
|---|---|
| Query latency | **< 14ms**, precomputed magnitude vectors |
| Ranking | BM25-style IDF weighting over TF-IDF |
| Typo tolerance | Damerau-Levenshtein fuzzy correction + synonym expansion |
| Infrastructure | Zero — 100% offline-functional after first load |

`React 19` `Vite 8` `Tailwind v4` `Framer Motion` `Vanilla NLP`
→ [github.com/ARJUN-AIML/AnswerFlow](https://github.com/ARJUN-AIML/AnswerFlow) · [Live](https://answerflow-chi.vercel.app)

</details>

<details>
<summary><b>🌐 Velora</b> — 42-language AI translator, sub-second, zero production errors</summary>
<br/>

Groq's low-latency inference paired with cultural/linguistic context, deployed serverless on a 111 kB gzipped bundle.

- 3-stage JSON extraction pipeline absorbs LLM response variance instead of breaking on it
- `useRef`-based race-condition guards prevent stale state on rapid concurrent requests
- 4-tier TTS voice fallback chain · one call returns translation + explanation + cultural context

`React 19` `Vite` `Netlify Functions` `Groq API`
→ [github.com/ARJUN-AIML/Velora](https://github.com/ARJUN-AIML/Velora) · [Live](https://velora-ai-translator.netlify.app)

</details>

<details>
<summary><b>📚 StudyOS</b> — full-stack AI study planner, built in a single 6-hour hackathon</summary>
<br/>

Pomodoro, flashcards, mock tests, analytics, and Groq-driven scheduling recommendations — ideated, built, and deployed inside one competition window.

`React` `Node.js` `Flask` `Firebase` `Groq API`
→ [github.com/ARJUN-AIML/AI-Study-Planner](https://github.com/ARJUN-AIML/AI-Study-Planner)

</details>

<br/>

## Where my AI depth actually sits

```
Computer Vision         ████████████████████  Applied      — production edge pipeline shipped
LLM Integration          ████████████████░░░░  Applied      — Groq + Gemini, multi-provider
Information Retrieval    ████████████████░░░░  Applied      — zero-dependency TF-IDF/BM25 engine
Agentic AI                ██████████████░░░░░░  Applied      — Google ADK, multi-agent orchestration
Generative AI              ██████████████░░░░░░  Applied      — structured extraction under variance
Classical ML                ████████████░░░░░░░░  Foundational — LightGBM, Random Forest, sklearn
Deep Learning                ████████████░░░░░░░░  Foundational — TF/Keras CNNs, transfer learning
```

<br/>

## Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,java,js,cpp,mysql,react,vite,tailwind,nodejs,express,fastapi,flask,mongodb,firebase,git,github,linux,vscode&theme=dark&perline=9" />
</div>

<br/>

## Experience

**Java Programming Intern** — CodeAlpha
*Feb 2026 · Virtual · Cert ID CA/DF1/21283*

Delivered 3 production-ready Java modules — OOP architecture, custom exception hierarchies, Collections-based data pipelines — all cleared code review with **zero critical defects**.

<br/>

## Track record

| | |
|---|---|
| 🏆 Smart India Hackathon 2025 | National-level team submission, full problem-to-solution build |
| ⚡ 6-Hour AI Hackathon | Shipped StudyOS end-to-end inside the competition window |
| 🧮 Competitive Programming | 165+ problems — Arrays, DP, Hash Tables, Trees, Divide & Conquer |
| 🔐 Cyber Security Workshop | NIT Tiruchirappalli — threat landscape & fundamentals |
| 📈 Systems Engineering | 51% inference latency reduction, production edge CV pipeline |

<details>
<summary><b>Certifications</b></summary>
<br/>

- Oracle — Generative AI Professional
- Oracle — AI Foundations Associate
- NPTEL — GPU Architectures & Programming
- NPTEL — Programming in Java
- IBM SkillsBuild — AI Fundamentals
- Infosys Springboard — Artificial Intelligence
- MongoDB — AI Fundamentals

</details>

<br/>

## Live from GitHub

<div align="center">
<img width="49%" src="https://github-readme-stats.vercel.app/api?username=ARJUN-AIML&show_icons=true&theme=radical&hide_border=true&bg_color=0F0C29&title_color=A78BFA&icon_color=8B5CF6&text_color=C9B8FF" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ARJUN-AIML&layout=compact&theme=radical&hide_border=true&bg_color=0F0C29&title_color=A78BFA&text_color=C9B8FF" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=ARJUN-AIML&theme=react-dark&hide_border=true&bg_color=0F0C29&color=A78BFA&line=8B5CF6&point=C9B8FF" />

<img width="98%" src="https://raw.githubusercontent.com/ARJUN-AIML/ARJUN-AIML/output/github-contribution-grid-snake-dark.svg" />
</div>

<br/>

## Currently

```yaml
building:
  - Tasketic         # MERN productivity system — Milestone 2C+
  - RCMS             # Java/Spring Boot MVC, role-based paper workflows
learning:
  - Distributed systems design for AI-heavy backends
  - ONNX Runtime & advanced OpenVINO optimization
open_to:
  - AI/ML Internship · Software Engineering Internship · Research Internship
```

<br/>

<div align="center">

*Production quality is not a feature — it's the default.*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243E,50:302B63,100:0F0C29&height=120&section=footer" />

</div>
