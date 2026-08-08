<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1A1A1A,100:0D0D0D&height=260&section=header&text=ARJUN%20S&fontSize=68&fontColor=F5D67B&fontAlignY=38&desc=Backend%20%2F%20ML%20Systems%20Engineer%20%E2%80%94%20Edge%20Inference%20%26%20Retrieval&descAlignY=58&descAlign=50&animation=fadeIn" />

<br/>

<a href="https://github.com/ARJUN-AIML">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=21&duration=3400&pause=1400&color=D4AF37&center=true&vCenter=true&width=780&lines=Backend+Engineer;Machine+Learning+Engineer;Full-Stack+Developer" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/B.E.-CSE_(AI_%26_ML)-141414?style=for-the-badge&labelColor=000000&color=B8860B" />
<img src="https://img.shields.io/badge/Saranathan_College_of_Engineering-141414?style=for-the-badge&labelColor=000000&color=8A6D1E" />
<img src="https://img.shields.io/badge/📍_Tiruchirappalli,_India-141414?style=for-the-badge&labelColor=000000&color=8A6D1E" />

<br/><br/>

<a href="https://www.linkedin.com/in/arjun-s-aiml"><img src="https://img.shields.io/badge/LinkedIn-1A1A1A?style=for-the-badge&logo=linkedin&logoColor=D4AF37&labelColor=000000" /></a>
<a href="mailto:arjunselvaraj0107@gmail.com"><img src="https://img.shields.io/badge/Email-1A1A1A?style=for-the-badge&logo=gmail&logoColor=D4AF37&labelColor=000000" /></a>
<a href="https://github.com/ARJUN-AIML"><img src="https://img.shields.io/badge/GitHub-1A1A1A?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=000000" /></a>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `01` About

<img align="right" width="300" src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" />

Third-year CSE undergrad, biased toward backend and inference-layer engineering over demo-layer polish.

The pattern across everything I've shipped: find a real bottleneck, build against actual constraints — latency budget, memory ceiling, cost — then measure the delta instead of assuming one. That's where `270ms → 132ms` on an edge detection pipeline and sub-14ms client-side search both came from.

I'd rather hand you one system with a benchmark than five projects with none.

<br clear="right"/>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `02` Stack

<sub>hover any icon</sub>

<br/><br/>

<img title="Python" width="48" height="48" src="https://skillicons.dev/icons?i=python" />
<img title="Java" width="48" height="48" src="https://skillicons.dev/icons?i=java" />
<img title="JavaScript" width="48" height="48" src="https://skillicons.dev/icons?i=js" />
<img title="C++" width="48" height="48" src="https://skillicons.dev/icons?i=cpp" />
<img title="MySQL" width="48" height="48" src="https://skillicons.dev/icons?i=mysql" />
<img title="React" width="48" height="48" src="https://skillicons.dev/icons?i=react" />
<img title="Vite" width="48" height="48" src="https://skillicons.dev/icons?i=vite" />
<img title="Tailwind CSS" width="48" height="48" src="https://skillicons.dev/icons?i=tailwind" />
<img title="HTML5" width="48" height="48" src="https://skillicons.dev/icons?i=html" />
<img title="CSS3" width="48" height="48" src="https://skillicons.dev/icons?i=css" />

<br/><br/>

<img title="Node.js" width="48" height="48" src="https://skillicons.dev/icons?i=nodejs" />
<img title="Express" width="48" height="48" src="https://skillicons.dev/icons?i=express" />
<img title="FastAPI" width="48" height="48" src="https://skillicons.dev/icons?i=fastapi" />
<img title="Flask" width="48" height="48" src="https://skillicons.dev/icons?i=flask" />
<img title="Spring Boot" width="48" height="48" src="https://skillicons.dev/icons?i=spring" />
<img title="MongoDB" width="48" height="48" src="https://skillicons.dev/icons?i=mongodb" />
<img title="Firebase" width="48" height="48" src="https://skillicons.dev/icons?i=firebase" />
<img title="PyTorch" width="48" height="48" src="https://skillicons.dev/icons?i=pytorch" />
<img title="TensorFlow" width="48" height="48" src="https://skillicons.dev/icons?i=tensorflow" />
<img title="OpenCV" width="48" height="48" src="https://skillicons.dev/icons?i=opencv" />
<img title="scikit-learn" width="48" height="48" src="https://skillicons.dev/icons?i=sklearn" />

<br/><br/>

<img title="Docker" width="48" height="48" src="https://skillicons.dev/icons?i=docker" />
<img title="Vercel" width="48" height="48" src="https://skillicons.dev/icons?i=vercel" />
<img title="Netlify" width="48" height="48" src="https://skillicons.dev/icons?i=netlify" />
<img title="Git" width="48" height="48" src="https://skillicons.dev/icons?i=git" />
<img title="GitHub" width="48" height="48" src="https://skillicons.dev/icons?i=github" />
<img title="VS Code" width="48" height="48" src="https://skillicons.dev/icons?i=vscode" />
<img title="Postman" width="48" height="48" src="https://skillicons.dev/icons?i=postman" />
<img title="Linux" width="48" height="48" src="https://skillicons.dev/icons?i=linux" />

<br/><br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `03` What I've Built

<br/>

**YOLO-Vision-X** — real-time object detection, CPU-only. Swapped the Ultralytics wrapper for a hand-optimized OpenVINO IR pipeline: `270ms → 132ms`, 51% cut, no GPU. 80-class tracking with persistent IDs, multi-stream switching that doesn't restart the server, intrusion-zone alerts over SSE.
[`repo`](https://github.com/ARJUN-AIML/YOLO-Vision-X)

**Mirage** — "Discern the Real." Browser-based scam detector, five scanner modules doing genuine SSL inspection and live DNS resolution — not a cached blacklist lookup.
[`repo`](https://github.com/ARJUN-AIML)

**Self-Correcting Code Review Agent** — built on Google ADK as root-agent → sub-agent → tool, not one long prompt. The agent critiques and revises its own review before returning it.
[`repo`](https://github.com/ARJUN-AIML)

**SCE Student Portal** — live, multi-role campus platform (with Madhav Padmesh S). Retrieval-grounded answers instead of a static FAQ. In actual use.
[`repo`](https://github.com/ARJUN-AIML)

**AnswerFlow** — semantic search that never leaves the browser. Zero backend, zero API calls, sub-14ms per query via precomputed vectors + BM25-style weighting + fuzzy correction.
[`repo`](https://github.com/ARJUN-AIML/AnswerFlow) · [`demo`](https://answerflow-chi.vercel.app)

**Velora** — 42-language translator on Groq inference, 111kB bundle, zero production errors. Race-condition guards on rapid concurrent requests.
[`repo`](https://github.com/ARJUN-AIML/Velora) · [`demo`](https://velora-ai-translator.netlify.app)

**StudyOS** — full-stack study planner, ideated and deployed inside a 6-hour hackathon window. Pomodoro, flashcards, analytics-driven scheduling.
[`repo`](https://github.com/ARJUN-AIML/AI-Study-Planner)

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `04` Experience

<br/>

**Java Programming Intern** · CodeAlpha · Feb 2026
*Virtual · MSME Registered · Cert CA/DF1/21283*

Three production Java modules — OOP hierarchies, custom exceptions, Collections-based pipelines. Zero critical defects across code review.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `05` Numbers

<br/>

<div align="center">

| | |
|---|---|
| **165+** | LeetCode problems — arrays, DP, hash tables, trees, divide & conquer |
| **51%** | Inference latency cut on a production edge CV pipeline |
| **0** | Production errors across Velora's live deployment |
| **SIH 2025** | Smart India Hackathon — national-level team submission |
| **6h** | Time to ship StudyOS, start to deploy |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `06` Certifications

<br/>

<div align="center">

<img src="https://img.shields.io/badge/Oracle-Generative_AI_Professional-141414?style=for-the-badge&logo=oracle&logoColor=F80000&labelColor=000000" />
<img src="https://img.shields.io/badge/Oracle-AI_Foundations_Associate-141414?style=for-the-badge&logo=oracle&logoColor=F80000&labelColor=000000" />
<br/>
<img src="https://img.shields.io/badge/NPTEL-GPU_Architectures-141414?style=for-the-badge&logo=googlescholar&logoColor=D4AF37&labelColor=000000" />
<img src="https://img.shields.io/badge/NPTEL-Java-141414?style=for-the-badge&logo=googlescholar&logoColor=D4AF37&labelColor=000000" />
<br/>
<img src="https://img.shields.io/badge/IBM_SkillsBuild-141414?style=for-the-badge&logo=ibm&logoColor=054ADA&labelColor=000000" />
<img src="https://img.shields.io/badge/Infosys_Springboard-141414?style=for-the-badge&logo=infosys&logoColor=007CC3&labelColor=000000" />
<img src="https://img.shields.io/badge/MongoDB-141414?style=for-the-badge&logo=mongodb&logoColor=47A248&labelColor=000000" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `07` Activity

<br/>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=ARJUN-AIML&show_icons=true&theme=radical&hide_border=true&bg_color=000000&title_color=D4AF37&icon_color=D4AF37&text_color=F5D67B" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ARJUN-AIML&layout=compact&theme=radical&hide_border=true&bg_color=000000&title_color=D4AF37&text_color=F5D67B" />

<br/>

<img width="98%" src="https://github-readme-streak-stats.herokuapp.com/?user=ARJUN-AIML&theme=radical&hide_border=true&background=000000&ring=D4AF37&fire=F5D67B&currStreakLabel=F5D67B" />

<br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=ARJUN-AIML&theme=react-dark&hide_border=true&bg_color=000000&color=D4AF37&line=B8860B&point=F5D67B" />

<br/>

<img width="98%" src="https://raw.githubusercontent.com/ARJUN-AIML/ARJUN-AIML/output/github-contribution-grid-snake-dark.svg" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

## `08` Right Now

<br/>

```yaml
building:
  - Tasketic — MERN productivity system, milestone 2C+
  - RCMS — conference management, Java / Spring Boot

exploring:
  - Multi-agent orchestration (Google ADK)
  - Edge deployment on constrained hardware

open_to:
  - Backend / ML systems internship
  - Research internship
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />

<br/>

<div align="center">

<a href="mailto:arjunselvaraj0107@gmail.com"><img src="https://img.shields.io/badge/Email-1A1A1A?style=for-the-badge&logo=gmail&logoColor=D4AF37&labelColor=000000" /></a>
<a href="https://www.linkedin.com/in/arjun-s-aiml"><img src="https://img.shields.io/badge/LinkedIn-1A1A1A?style=for-the-badge&logo=linkedin&logoColor=D4AF37&labelColor=000000" /></a>
<a href="https://github.com/ARJUN-AIML"><img src="https://img.shields.io/badge/GitHub-1A1A1A?style=for-the-badge&logo=github&logoColor=D4AF37&labelColor=000000" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=400&size=15&duration=4000&pause=2000&color=8A6D1E&center=true&vCenter=true&width=600&lines=Production+quality+is+not+a+feature.+It's+the+default." alt="signature" />

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,50:1A1A1A,100:000000&height=140&section=footer" />
