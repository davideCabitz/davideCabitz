## Hi, I'm Davide Cabitza!

MSc student in **Artificial Intelligence Systems** at the University of Trento, with a BSc in Computer Science from the University of Camerino (104/110) and industry experience in digital transformation consulting.

I've worked on **LLM agent architectures & evaluation**, **vision-language models**, and **probabilistic retrieval systems**. I care about building AI systems with statistical rigor, measurable benchmark performance and cost-efficient trade-offs.

**Currently seeking AI/ML or Software Engineering roles & internships (fully flexible on setup, ready to relocate).**

[LinkedIn](https://www.linkedin.com/in/davide-cabitza-ai-student) · [Email](mailto:davidecabitz@gmail.com) · [GitHub](https://github.com/davideCabitz)

---

### Projects at a glance

| Project | Area | Stack |
|---|---|---|
| [Compositional Image Retrieval (A-BAP)](#compositional-image-retrieval-with-clip-and-bayesian-attribute-scoring) | Deep learning · Vision-Language · Probabilistic AI | Python, PyTorch, CLIP, HuggingFace |
| [Angry Agents](#angry-agents-multi-agent-persona-simulation--evaluation) | LLM agents · Multi-Agent Systems · Evaluation | Python, OpenAI API, RAG, SciPy |
| [Autonomous Delivery Agents](#autonomous-llm-powered-delivery-agents-bdi--gpt-4o) | Multi-agent systems · BDI · Planning · LLMs | JavaScript (Node.js), OpenAI SDK, LiteLLM, PDDL |

---

### AI and Machine Learning

#### Compositional Image Retrieval with CLIP and Bayesian Attribute Scoring
[`davideCabitz/Deep-Learning-Project`](https://github.com/davideCabitz/Deep-Learning-Project) · MSc AI Systems, UniTrento

Engineered a PyTorch multi-modal image retrieval pipeline conditioning frozen CLIP (ViT-B/32) embeddings with complex multi-attribute constraints to solve geometric failure modes in state-of-the-art CVPR baselines.

- **Algorithmic Innovation:** Developed **A-BAP** (Amortized Bayesian Attribute-Posterior scoring), combining 40 calibrated logistic attribute probes, a Poisson-binomial dynamic program for exact identity preservation, Chow-Liu dependency trees, and ListNet listwise ranking loss.
- **Results:** Achieved $R@10 = 0.413$ ($4\times$ gain over vanilla CLIP and $+61\%$ over non-probabilistic models, $p < 0.001$, Holm–Bonferroni corrected) on CelebA. Broke the $0\%$ retrieval floor on pure-negation queries (`-Male`, `-Mustache`), raising $R@5$ from $0.000$ to $0.222$.
- **Stack:** Python, PyTorch, CLIP (ViT-B/32), Hugging Face Transformers

#### Angry Agents: Multi-Agent Persona Simulation & Evaluation
[`davideCabitz/AngryAgents`](https://github.com/davideCabitz/AngryAgents) · Designing Large Scale AI Systems, UniTrento

Engineered a multi-agent web application for real-time group chat simulations across 100+ LLM-scraped AI persona agents, backed by an automated multi-LLM evaluation pipeline.

- **Statistical Rigor & Judge Pipeline:** Validated judge agreement using Cohen's Kappa ($\kappa = 0.66$, "Good" reliability) and achieved a $4.83/5.0$ mean persona fidelity score across 21 multi-turn benchmark chats ($95\%$ CI $[4.74, 4.93]$).
- **Model & Cost Tradeoff:** Quantified trade-offs between models, demonstrating that upgrading to flagship models raised character accuracy from $53.8\%$ (Macro F1: $0.656$) to $97.5\%$ (Macro F1: $0.975$, $p < 0.001$) at a $17\times$ cost multiplier.
- **Stack:** Python, OpenAI API, LLMs, RAG, SciPy

#### Autonomous LLM-Powered Delivery Agents (BDI + GPT-4o)
[`davideCabitz/AMS---Autonous-Software-Agents-for-Deliveroo.js`](https://github.com/davideCabitz/AMS---Autonous-Software-Agents-for-Deliveroo.js) · Autonomous Software Agents, UniTrento

Engineered two cooperating autonomous BDI agents competing in a grid game that dynamically select among 8 strategies to optimize time-decaying parcel delivery.

- **Architecture:** Combined $A^*$ graph navigation, PDDL planning for spatial puzzles, and probabilistic opponent modeling with a decay-aware value function.
- **LLM Integration:** Built a ReAct GPT-4o command layer with ~40 tools to parse and cost-price natural language missions, alongside a custom JSON coordination protocol enabling inter-agent parcel handoffs.
- **Stack:** JavaScript (Node.js), OpenAI SDK, LiteLLM, PDDL, $A^*$ Search

---

### Professional Experience

**Junior Consultant Intern · Business Integration Partners (BIP) S.p.A.** (Milano, Italy) · May 2025 – Sep 2025 
Supported public sector digital transformation and modernization initiatives under the National Recovery and Resilience Plan (NRRP / PNRR). Mapped AS-IS/TO-BE processes, conducted data analysis and KPI tracking for executive performance monitoring, and managed cross-functional stakeholder coordination.

---

### Tech Stack & Skills

- **AI/ML & Vision:** PyTorch, CLIP (ViT-B/32), Hugging Face, RAG, Probabilistic Modeling
- **LLMs & Multi-Agent Systems:** OpenAI API, BDI Agents, ReAct Tooling (~40 tools), PDDL Planning, LiteLLM, Automated Multi-LLM Judge Pipelines
- **Languages:** Python, JavaScript (Node.js), C++, Java, SQL
- **Languages Spoken:** English (IELTS Academic 7.0 / C1), Japanese (JLPT N4 / B1 equivalent), Italian (Native)
