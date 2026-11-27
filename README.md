<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1200&color=6E56CF&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Jiale+(Charles)+Chen+%F0%9F%91%8B;AI+Agent+Engineer+%40+OpenDesign;Multi-Agent+%C2%B7+RAG+%C2%B7+MCP+%C2%B7+Agent+Eval;Do+the+hard+and+right+thing." alt="Typing intro" />

<a href="https://www.linkedin.com/in/jiale-chen-532856410/"><img src="https://img.shields.io/badge/LinkedIn-Jiale_Chen-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Shenzhen-UTC%2B8-555?style=flat-square" />

</div>

### `$ cat agent.manifest.yaml`

```yaml
agent: jiale-chen
role: AI Agent Engineer @ OpenDesign
based_in: Shenzhen, China
motto: "Do the hard and right thing."

runtime:                       # what I build
  - production multi-agent systems, 0 → 1 → prod
  - workflow orchestration with HITL gates, checkpoints, replay
  - RAG · MCP tool ecosystems · agent eval · observability

memory:                        # where I come from
  - BitKernel: Senior SDE / Platform Architect, promoted twice
  - Huawei 2012 Labs: network chip co-optimization
  - IEEE RTSS 2022 (CCF-A), first author

guardrails:                    # how I work
  - deterministic orchestration around non-deterministic models
  - every agent run is traceable, evaluable and replayable
  - measure quality and cost before calling it done
```

### 🧩 What a typical system of mine looks like

```mermaid
flowchart LR
    U([Request]) --> G{Intent Gate}
    G --> S[Supervisor]
    S <--> K[Knowledge Agent<br/>RAG]
    S <--> T[Tool Agent<br/>MCP]
    S <--> C[Config Agent<br/>Plan & Execute]
    C -.-> H{{Human approval}}
    S --> Y[Synthesis] --> P[Compliance] --> R([Answer])
    E[(Eval set · OTel traces)] -.-> S
```

### 🚀 Selected work

| Project | What I built | Result |
|---|---|---|
| **Novel-to-Video AIGC Agent Platform** | 6 stage-expert agents behind a deterministic workflow with 4 HITL gates · manifest-driven Agent Runtime · multi-provider media task runtime | 1,500+ AI short dramas · **~90% cost down** |
| **GooseOTT Multi-Agent Support** | Supervisor multi-agent · RAG (BGE-M3 + Milvus + rerank) · 32 MCP tools · golden-set eval used as a CI gate | 20K+ requests/month · **97% accuracy** |
| **RDNS: Reliable DNS (DNS + DHT)** | Cross-platform C++ engine · DHT nodes · multi-level cache · lock-free queue | 15M resolutions/day · **99.9% success** |
| **SPOT: Network Chip Design Optimization** | HW/SW modeling · NSGA-II / MOTS search · PPA evaluation | **−20.6% latency, −23.7% power** |

### 🛠️ Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=py,java,cpp,ts,fastapi,spring,react,postgres,redis,mysql,docker,kubernetes,linux&perline=13" />
</p>

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000?style=flat-square)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![DeepEval](https://img.shields.io/badge/DeepEval-6E56CF?style=flat-square)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

<sub>🎓 M.S. Shenzhen University × Huawei joint program · B.S. Guangzhou University (ranked 1/102)</sub>
