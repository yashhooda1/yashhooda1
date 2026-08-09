<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b3d91,100:4caf50&height=200&section=header&text=Yash%20Hooda&fontSize=70&fontColor=ffffff&fontAlignY=32&desc=AI%20%2B%20Data%20Engineer%20·%20Production%20LLM%20Systems&descAlignY=52&descSize=18&animation=fadeIn" width="100%" />

<a href="https://yashhooda.ai">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=19&pause=1200&color=4CAF50&center=true&vCenter=true&width=900&height=45&lines=Production+LLM+systems.+Not+notebooks.;RAG+%2B+agents+%2B+evals+%E2%80%94+shipped%2C+serving+traffic.;Pipelines+that+run+daily+without+me.;Rate+limiters%2C+kill+switches%2C+real+traffic." alt="Typing SVG" />
</a>

<br/>

<a href="https://yashhooda.ai"><img src="https://img.shields.io/badge/Portfolio-yashhooda.ai-4caf50?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://linkedin.com/in/yash-hooda-384430242"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:yash.hooda6@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=yashhooda1&label=Profile%20views&color=4caf50&style=flat-square" alt="views" />

</div>

---

### `> whoami`

**Data & Software/AI Engineer** building **production** systems — the kind with rate limiters, kill switches, and a 3 a.m. pager, not the kind that lives in a notebook.

- Ship full-stack AI — multi-model LLM gateways, hybrid RAG with reranking, agentic loops, and vector search — all live in production on real traffic.
- Build data pipelines that run themselves: scheduled ingestion, incremental caching, validation floors, and CI that catches bad data before it lands.
- Fine-tune and evaluate — QLoRA adapters, golden test sets, offline eval harnesses.

📍 Richmond, TX · 🎓 BS Computer Science, UT Dallas

---

### `> systems.ls --production`

#### 🧠 [yashhooda.ai](https://yashhooda.ai) — flagship platform
**Full-stack AI application · Node.js · Vercel · Upstash**

Not a portfolio site — an AI application that happens to have my resume in it. A hybrid RAG chatbot (dense + sparse retrieval, RRF, CRAG grading, cross-encoder reranking), a multi-model gateway (Claude, GPT, Grok, Gemini, Llama), live ADS-B data ingestion, and a 7-layer security gateway. Survived a sustained real-world attack campaign — defenses held.

<table>
<tr>
<td width="50%" valign="top">

#### 🌎 [ClimatePulse](https://github.com/yashhooda1/climatepulse)
**Python · pandas · scikit-learn · NOAA · GitHub Actions**

57-year (1970–2026) Bronze→Silver→Gold climate pipeline across 13 global stations, auto-refreshed daily via GitHub Actions. Incremental per-station caching cut the run from 741 NOAA API calls to 13. Trend regressions, heat-day counts, station-level validation floors, and freshness checks. Houston warming: +0.79°F/decade.

</td>
<td width="50%" valign="top">

#### 🤖 [Offline SLM Agent](https://github.com/yashhooda1/slm-offline-ai-agent)
**Python · ReAct · stdlib-only**

A fully offline ReAct agent on a local small language model — hand-written loop, six sandboxed tools, no API key, no CDN dependencies. Testable without a model loaded; 10/10 tests green. Published to Ollama under the `hoodarunner/` namespace.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⌚ [Garmin MCP Server](https://github.com/yashhooda1/mcp-garmin)
**Python · MCP · FastMCP · Docker**

Model Context Protocol server that lets Claude read Garmin activities and push structured workouts and full training plans straight to a watch. Reverse-engineered Garmin's workout-service schema into a typed, LLM-friendly spec — garth SSO auth, a bearer-secured transport, offline tests, and CI.

</td>
<td width="50%" valign="top">

#### 🛰️ [Live Flight Tracker](https://github.com/yashhooda1/IF-Flight-Tracker)
**Python · FastAPI · Leaflet · Live API**

Real-time geospatial ingestion and visualization: live aircraft map coloured by flight phase, origin→destination cards with computed ETAs, arrival weather + 5-day forecast, and layered map tiles. FastAPI backend proxies and caches the upstream API so keys never touch the browser.

</td>
</tr>
</table>

---

### `> stack.json`

<details open>
<summary><b>AI / LLM Engineering</b></summary>
<br/>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

`RAG (hybrid + RRF + reranking)` · `CRAG` · `Agentic loops / ReAct` · `QLoRA fine-tuning` · `MLflow` · `Evals` · `Vector search (Upstash, FAISS, Chroma)`

</details>

---

### `> git log --stat`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=yashhooda1&show_icons=true&hide_border=true&bg_color=0d1117&title_color=4caf50&icon_color=4caf50&text_color=c9d1d9&include_all_commits=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yashhooda1&layout=compact&hide_border=true&bg_color=0d1117&title_color=4caf50&text_color=c9d1d9&langs_count=8" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=yashhooda1&bg_color=0d1117&color=c9d1d9&line=4caf50&point=ffffff&area=true&hide_border=true" />

</div>

---

### `> cat interests.txt`

**Running** — marathoner chasing sub-3:00, which is why half my side projects are running infrastructure. Also: weather systems, aviation data, NBA, independent science, and open-ended research rabbit holes that end at 2 a.m. with a new repo.

<div align="center">
<br/>

**Building AI that ships. Open to what's next.**

<a href="mailto:yash.hooda6@gmail.com"><img src="https://img.shields.io/badge/Let's_talk-yash.hooda6@gmail.com-4caf50?style=for-the-badge&logo=minutemailer&logoColor=white" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4caf50,50:0b3d91,100:0d1117&height=120&section=footer" width="100%" />

</div>

<!---
yashhooda1/yashhooda1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
