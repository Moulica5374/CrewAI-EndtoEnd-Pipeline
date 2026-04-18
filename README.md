# CrewAI End-to-End Pipeline

A collection of production-grade multi-agent AI pipelines built with [CrewAI](https://github.com/crewAIInc/crewAI). Each project in this repo demonstrates a real-world use case — from document intelligence to data engineering automation — using autonomous agents that collaborate to complete complex tasks.

---

## Repository Structure

```
CrewAI-EndtoEnd-Pipeline/
├── project-1/               # First CrewAI project (coming soon)
├── project-2/               # Second CrewAI project (coming soon)
├── shared/                  # Shared utilities, base agents, common tools
├── LICENSE
└── README.md
```

Each project is self-contained with its own `README.md`, `requirements.txt`, and `.env.example`.

---

## Projects

| # | Project | Description | Status |
|---|---------|-------------|--------|
| 1 | Multimodal OCR Agent | Extract healthcare IDs from document images using Claude multimodal | 🚧 In Progress |
| 2 | Coming soon | — | 📅 Planned |
| 3 | Coming soon | — | 📅 Planned |

---

## What is CrewAI?

CrewAI is a Python framework for orchestrating **role-playing autonomous AI agents**. Agents collaborate as a crew — each with a defined role, goal, and set of tools — to tackle tasks that would be too complex for a single LLM call.

```
Crew
 ├── Agent 1 (Researcher)   → searches, gathers context
 ├── Agent 2 (Analyst)      → processes, extracts insights
 └── Agent 3 (Writer)       → formats and delivers output
```

---

## Tech Stack

| Layer | Tool |
|---|---|
| Agent framework | [CrewAI](https://github.com/crewAIInc/crewAI) |
| LLM backbone | Anthropic Claude / OpenAI GPT-4 |
| Tool use | CrewAI Tools, custom tools |
| Language | Python 3.10+ |
| Environment | python-dotenv |

---

## Getting Started

### Prerequisites

- Python 3.10+
- An Anthropic or OpenAI API key

### Install base dependencies

```bash
pip install crewai crewai-tools python-dotenv
```

### Clone the repo

```bash
git clone https://github.com/Moulica5374/CrewAI-EndtoEnd-Pipeline.git
cd CrewAI-EndtoEnd-Pipeline
```

Then navigate into any individual project folder and follow its own README.

---

## Environment Variables

Each project uses a `.env` file. Copy the `.env.example` in each project folder:

```bash
cp .env.example .env
```

Common variables across projects:

```bash
ANTHROPIC_API_KEY=
OPENAI_API_KEY=
```

---

## Roadmap

- [ ] Multimodal OCR Agent — healthcare document ID extraction
- [ ] Resume Screening Agent — multi-agent JD matching pipeline
- [ ] Data Engineering Agent — automated pipeline generation with CrewAI + dbt
- [ ] Research Agent — web search + summarization crew
- [ ] RAG Agent — document Q&A with retrieval-augmented generation

---

## Contributing

This is an active portfolio repo. New projects are added regularly. Each project follows the same structure:

```
project-name/
├── agents/
├── tasks/
├── tools/
├── crew.py
├── main.py
├── .env.example
├── requirements.txt
└── README.md
```

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---

*Built by [Moulica](https://github.com/Moulica5374) — exploring production-grade agentic AI pipelines across healthcare, data engineering, and beyond.*# CrewAI-EndtoEnd-Pipeline