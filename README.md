<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0e75b6&height=200&section=header&text=Hassan%20Khaled&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Verification%20Engineer%20%7C%20AI%2FML%20for%20IC%20Verification&descAlignY=58&descSize=18&descColor=c9d1d9" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=0e75b6&center=true&vCenter=true&width=600&lines=4%2B+Years+Engineering+Confidence+in+Silicon;UVM+%7C+SystemVerilog+%7C+High-Speed+SerDes;AI-Driven+Verification+Automation;Zero-Defect+Silicon+Through+Intelligent+Verification)](https://git.io/typing-svg)

<p>
  <img src="https://komarev.com/ghpvc/?username=HassanKhaled11&label=Profile+Views&color=0e75b6&style=flat-square" />
  <img src="https://img.shields.io/github/followers/HassanKhaled11?label=Followers&style=flat-square&color=0e75b6" />
</p>

</div>

---

## About

I am a **Verification Engineer** specializing in **High-Speed SerDes** and **SoC verification**, with 4+ years of experience engineering confidence into silicon before tapeout. My work sits at the intersection of classical verification discipline — UVM, SVA, constrained-random — and modern AI-driven tooling that scales what a single engineer can achieve.

I am currently building **VeriAware**, an AI-powered IC verification platform that combines compiler-accurate RTL extraction (slang), knowledge graph analysis (KuzuDB), and LangGraph agent orchestration to automate root cause analysis, coverage closure, and debug workflows that today require hours of manual trace.

My conviction is that the next generation of verification engineers will not write more testbench code — they will build systems that write it for them.

---

## What I Build

```
┌─────────────────────────────────────────────────────────────────┐
│                Agentic Verification Platform                    │
│                                                                  │
│   RTL Source  ──►  slang compiler  ──►  KuzuDB Graph DB          │
│      .v / .sv      (exact AST JSON)    (Cypher queries)          │
│                                              │                   │
│                                              ▼                   │
│                                    LangGraph Agents              │
│                              ┌───────────────────────┐           │
│                              │  Debug  │  Coverage   │           │
│                              │  Agent  │    Agent    │           │
│                              │─────────│─────────────│           │
│                              │   CDC   │  Hierarchy  │           │
│                              │  Agent  │    Agent    │           │
│                              └───────────────────────┘           │
│                                              │                   │
│                                              ▼                   │
│                              LLM Synthesiser (Claude / Ollama)   │
│                                              │                   │
│                                              ▼                   │
│                         Engineer-readable answers in seconds     │
└─────────────────────────────────────────────────────────────────┘
```

---

## Core Expertise

### Silicon Verification

| Domain | Skills |
|---|---|
| **Methodology** | UVM (Universal Verification Methodology), Constrained Random Verification (CRV), Coverage-Driven Verification (CDV), Gate-Level Simulation (GLS) |
| **Languages** | SystemVerilog, Verilog, VHDL, TCL |
| **Assertions** | SVA (SystemVerilog Assertions), formal property specification, assertion-based debug |
| **Protocols** | AXI4, AHB, APB, PCIe, High-Speed SerDes (PAM4, NRZ), USB, I2C, SPI |
| **EDA Tools** | Synopsys VCS, Verdi, Cadence Xcelium, QuestaSim |
| **Coverage** | Functional coverage, code coverage, cross coverage, coverage closure automation |
| **Debug** | Waveform analysis, signal tracing, root cause analysis, regression triage |

### AI / ML for Verification

| Domain | Skills |
|---|---|
| **Knowledge Graphs** | KuzuDB, GraphRAG, Cypher query design, RTL-to-graph extraction pipelines |
| **Agent Frameworks** | LangGraph, LangChain, multi-agent orchestration, tool-use patterns |
| **LLM Integration** | Claude API, Ollama (local models), prompt engineering, RAG pipelines |
| **RTL Parsing** | slang compiler (C++ AST), pyslang, AST traversal, JSON schema extraction |
| **ML** | Python, PyTorch, scikit-learn, HDBSCAN clustering, LightGBM |
| **Vector DBs** | embeddings, semantic search over RTL descriptions |

### Software Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=py,cpp,git,linux,docker,pytorch,tensorflow,vscode" />
</p>

---

## Flagship Project — VeriAware

> **Compiler-accurate RTL knowledge graph for AI-driven IC verification**

Traditional LLM-based RTL analysis guesses at structure from source text — it gets widths wrong, misses implicit connections, and hallucinates relationships. VeriAware takes a different approach:

**1. Exact extraction via slang**
The slang SystemVerilog compiler front-end elaborates the design — resolving all parameters, unrolling generates, building the full hierarchy — and serializes the result to JSON. Every signal has its exact bit-width. Every port connection is traced. No guessing.

**2. Graph database via KuzuDB**
The elaborated design loads into KuzuDB as a typed property graph. Signals, ports, FSM states, always blocks, covergroups, assertions, and their relationships become queryable in Cypher. A fanout cone query takes milliseconds instead of a manual trace through waveforms.

**3. AI agents via LangGraph**
Specialized agents — Debug, Coverage, CDC, Hierarchy — each own a query domain. A router classifies the engineer's question and dispatches to the right agent. The agent selects a parameterized Cypher template, executes it against KuzuDB, and passes structured results to an LLM synthesiser that produces a natural-language answer.

**Result:** Questions that take 30 minutes of waveform digging are answered in seconds with full RTL traceability.

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=HassanKhaled11&theme=tokyonight&hide_border=true&background=00000000" width="49%" />
<img src="https://github-readme-stats.vercel.app/api?username=HassanKhaled11&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&count_private=true" width="49%" />

</div>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HassanKhaled11&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000&langs_count=8" width="49%" />
</div>

---

## Experience Snapshot

```
Timeline ──────────────────────────────────────────────────────────►

 2020          2021          2022          2023          2024-25
  │             │             │             │               │
  ▼             ▼             ▼             ▼               ▼
UVM/SV       SerDes        SoC-level    AI-driven       Full Agentic/ML
foundations  verification  regression   automation      platform for DV
             & protocol    & GLS        research        development
             analysis      debug
```

---

## Current Focus

- Building VeriAware agent pipeline: slang → KuzuDB → LangGraph → Claude
- Designing Cypher query templates for RTL debug and coverage closure
- Exploring formal methods integration with AI-assisted property generation
- Contributing to open-source EDA tooling

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hassan%20Khaled-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hassan-khaled-898359219/)
[![Email](https://img.shields.io/badge/Email-Hassankhaled006%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Hassankhaled006@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-HassanKhaled11-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HassanKhaled11)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0e75b6&height=100&section=footer" />

</div>
