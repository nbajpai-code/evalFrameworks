# AI Evaluation Frameworks: Agentic AI & Classical ML

This repository contains a comprehensive list of resources, frameworks, tools, and readings for evaluating both next-generation **Agentic AI (LLMs, Multi-Agent Systems, RAGs)** and **Classical Machine Learning** models. 

## Table of Contents
1. [Agentic AI & LLM Evaluation Frameworks](#agentic-ai--llm-evaluation-frameworks)
   - [Open Source Frameworks & GitHub Repos](#open-source-frameworks--github-repos)
   - [Agent-Specific Benchmarks](#agent-specific-benchmarks)
   - [Tech Giant Implementations](#tech-giant-implementations)
   - [Key Reads & Articles](#key-reads--articles)
2. [Classical ML Evaluation Frameworks](#classical-ml-evaluation-frameworks)
   - [Open Source Frameworks & MLOps Tools](#open-source-frameworks--mlops-tools)
   - [Essential Classical Metrics](#essential-classical-metrics)
   - [Key Reads & YouTube Channels](#key-reads--youtube-channels)

---

## Agentic AI & LLM Evaluation Frameworks

As AI moves from single-prompt interactions to autonomous "**Agentic**" workflows, evaluating these systems requires assessing multi-step reasoning, tool usage, memory, and hallucination rates.

### Open Source Frameworks & GitHub Repos
*   [**Promptfoo**](https://github.com/promptfoo/promptfoo): CLI and library for testing, evaluating, and red-teaming LLM apps and Agents. Excellent for CI/CD integrations.
*   [**DeepEval** (Confident AI)](https://github.com/confident-ai/deepeval): An open-source evaluation framework for LLMs offering unit-testing style assertions for hallucination, faithfulness, and relevancy.
*   [**TruLens** (TruEra)](https://github.com/truera/trulens): Introduces the concept of "Feedback Functions" to programmatically evaluate and track LLM applications.
*   [**RAGAS**](https://github.com/explodinggradients/ragas): Specifically tailored for evaluating Retrieval Augmented Generation (RAG) pipelines.
*   [**LangSmith** (LangChain)](https://smith.langchain.com/): The premier observability and evaluation platform for LLM applications built on LangChain.
*   [**Agentica Framework** (Symbolica)](https://github.com/symbolica-ai/agentica): Used by leading researchers to construct "code-mode" agents and evaluate reasoning capabilities on complex benchmarks like ARC-AGI.

### Agent-Specific Benchmarks
*   [**SWE-bench**](https://github.com/princeton-nlp/SWE-bench): The gold standard for evaluating AI software engineering agents (tests an agent's ability to resolve real GitHub issues).
*   [**WebArena**](https://github.com/webarena-ai/webarena): A highly realistic web environment for evaluating autonomous web-browsing agents.
*   [**GAIA** (General AI Assistants)](https://huggingface.co/spaces/gaia-benchmark/leaderboard): A benchmark introduced by Meta and Yann LeCun for testing general-purpose AI assistants on reasoning and tool usage.
*   [**AgentBench**](https://github.com/THUDM/AgentBench): A comprehensive framework designed to evaluate LLM-as-Agent on reasoning and decision-making capabilities across various environments.

### Tech Giant Implementations
*   [**OpenAI Evals**](https://github.com/openai/evals): The official open-source framework used by OpenAI to evaluate their own LLMs. 
*   [**Microsoft Promptflow**](https://microsoft.github.io/promptflow/): A suite of tools to build, evaluate, and operationalize LLM workflows (integrated tightly with Azure AI).

### Key Reads & Articles (Medium/Internet)
*   **Medium:** ["The State of AI Agent Evaluation"](https://towardsdatascience.com/evaluating-llm-agents-a-complete-guide-4f9db21eb521) - Towards Data Science breakdowns on moving past simple LLM metrics.
*   **Anthropic Research:** [Evaluating AI Systems](https://www.anthropic.com/research) - Deep dives into constitutional AI and how Anthropic tests Claude.
*   **Hugging Face Blog:** Comprehensive guides on evaluating RAG systems and building proper agent task definitions.

---

## Classical ML Evaluation Frameworks

Classical Machine Learning requires a different approach—focusing strongly on mathematical metrics (F1-score, RMSE, ROC-AUC), data drift, test set validation, and continuous model observability.

### Open Source Frameworks & MLOps Tools
*   [**MLflow**](https://github.com/mlflow/mlflow): Started by Databricks, the canonical open-source platform for managing the ML lifecycle (including Tracking and Evaluation).
*   [**Evidently AI**](https://github.com/evidentlyai/evidently): Evaluates, tests, and monitors data and ML models from validation to production. Specializes in detecting *Data Drift* and *Concept Drift*.
*   [**Deepchecks**](https://github.com/deepchecks/deepchecks): Excellent open-source library for continuous validation and testing of ML models and data. Generates visual evaluation reports.
*   [**Weights & Biases (W&B)**](https://wandb.ai/): The developer-first MLOps platform for tracking experiments, visualizing evaluation metrics, and hyperparameter tuning.
*   [**Great Expectations**](https://github.com/great-expectations/great_expectations): Not strictly model eval, but the standard for evaluating and profiling *Data Quality* before training.

### Essential Classical Metrics
*   **Scikit-Learn (`sklearn.metrics`)**: The fundamental backbone for classical evaluation. 
    *   *Classification*: `accuracy_score`, `f1_score`, `roc_auc_score`, `confusion_matrix`
    *   *Regression*: `mean_squared_error`, `r2_score`, `mean_absolute_error`

### Key Reads & YouTube Channels
*   **YouTube - MLOps Community:** [The MLOps Community Channel](https://www.youtube.com/c/MLOpsCommunity) represents the cutting edge of how enterprises evaluate and monitor live classical ML systems.
*   **YouTube - Andrew Ng:** DeepLearning.AI courses covering Structuring ML Projects and establishing evaluation metrics.
*   **Medium (Towards Data Science):** Articles covering bias-variance tradeoff, cross-validation strategies, and managing concept drift in production systems.

---

## Academia, Top Tier Research & PhD Theses

Bridging the gap between empirical engineering and academic rigor, the following resources capture cutting-edge and seminal work from top institutions (MIT, CMU, Stanford, UC Berkeley), focusing on Agentic Ecosystems, ML evaluation, and Pervasive Computing.

### Key Preprints & Publications (arXiv, ACM, IEEE)
*   [**AgentBench: Evaluating LLMs as Agents** (arXiv)](https://arxiv.org/abs/2308.03688): Foundational paper from Tsinghua University outling multidimensional evaluation of LLMs acting as agents across OS, Web, and Database environments.
*   [**WebArena: A Realistic Web Environment for Building Autonomous Agents** (arXiv / CMU)](https://arxiv.org/abs/2307.13854): Carnegie Mellon research establishing deeply simulated benchmarks for web-browsing agents.
*   [**SWE-bench: Can Language Models Resolve Real-World GitHub Issues?** (Princeton NLP)](https://arxiv.org/abs/2310.06770): The core academic paper introducing the most widely adopted agentic software engineering benchmark.
*   [**GAIA: A Benchmark for General AI Assistants** (arXiv / Meta / HuggingFace)](https://arxiv.org/abs/2311.12983): Research assessing tool use, multi-modal reasoning, and multi-turn interaction for General AI evaluation.
*   [**ACM/IEEE Transactions on Autonomous and Adaptive Systems (TAAS)**](https://dl.acm.org/journal/taas): The premier academic journal for rigorous evaluation metrics on self-managing, autonomous, and multi-agent systems.

### Pervasive Computing & Edge AI (PhD Theses & Labs)
Pervasive computing (Ubiquitous Computing) intersects deeply with multi-agent systems and ML at the edge.
*   [**Project Aura (CMU)**](https://www.cs.cmu.edu/~aura/): Foundational CMU pervasive computing research on user mobility and context-aware systems—critical reading for grounding physical ML agents.
*   [**Responsive Environments & Fluid Interfaces (MIT Media Lab)**](https://www.media.mit.edu/groups/responsive-environments/overview/): PhD work and ongoing research into scaling sensor networks, wearable agents, and pervasive ML ecosystems.
*   [**Berkeley RISELab / Sky Computing**](https://sky.cs.berkeley.edu/): Leading academic output on distributed, secure execution and edge pervasive state management (the academic precursor to modern cloud-scaling LLM infrastructures).
*   **Cutting-Edge PhD Theses Streams in Pervasive Computing:**
    *   *Carnegie Mellon (CMU) HCI & ISR*: Dissertations on context-aware smart environments, privacy-preserving ubiquitous computing, and adaptive agent architectures.
    *   *Stanford HCI Group*: Theses exploring the intersection of ubiquitous computing, mobile AI interactions, and human-in-the-loop (HITL) evaluation.
    *   *IEEE Pervasive Computing Journal*: A must-read venue for PhD researchers transitioning from embedded systems / edge ML into LLM-driven pervasive architectures.
