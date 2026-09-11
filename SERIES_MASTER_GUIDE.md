# Python for AI & GenAI Developers
## Series Master Guide
### From Fundamentals to Agentic AI

**Series length:** 80 posts  
**Primary audience:** Python beginner → AI / GenAI developer  
**Primary publishing channels:** LinkedIn and Facebook  
**Future publishing channel:** GitHub  
**Visual identity:** Professional dark technology-themed  
**Advanced platform focus:** Microsoft Foundry and Gemini Enterprise Agent Platform (historically known as Vertex AI)
**Primary agent frameworks:** Microsoft Agentic Framework and Google ADK  
**Core philosophy:** Learn the concept first, then plain Python, then the SDK, then the agent framework, then the managed platform.

---

# 1. Series Vision

This series is designed to take a learner from basic Python programming to building practical AI, GenAI, RAG, tool-using, agentic, MCP-enabled, and production-ready applications.

The course must never become a generic Python tutorial.

Every topic should answer at least one of these questions:

- Why does an AI developer need this?
- Where will this concept appear later in GenAI development?
- How does this concept connect to LLMs, RAG, tools, agents, or production AI?
- What will we build with it?

The series should feel like one continuous journey rather than 80 disconnected posts.

---

# 2. Core Learning Philosophy

Use this progression wherever possible:

```text
Concept
  ↓
Plain Python
  ↓
SDK
  ↓
Framework
  ↓
Managed Platform
```

For example:

```text
Similarity
  ↓
Embeddings
  ↓
Python Vector Search
  ↓
Vector Store
  ↓
Azure AI Search
  ↓
Microsoft Foundry Retrieval
```

And:

```text
Function Calling
  ↓
Tool Use
  ↓
Agent Loop
  ↓
Agent Framework
  ↓
Microsoft Agentic Framework / Google ADK
  ↓
Multi-Agent Architecture
```

Do not introduce a framework before the learner understands the underlying concept.

---

# 3. 80-Day Curriculum

## Phase 1 — Python Foundations
### Days 1–10

1. Why Python for AI? Setting Up Your AI Development Environment
2. Your First Python Program: Variables, Values and Data Types
3. Working with Strings — Essential for AI Prompts and Text
4. Numbers, Booleans and Python Operators
5. Making Decisions with `if`, `elif` and `else`
6. Loops: Automating Repetitive Work with `for` and `while`
7. Python Lists — Your First Real Data Structure
8. Dictionaries — The Data Structure Every AI Developer Needs
9. Tuples, Sets and When to Use Them
10. Functions — Turning Python Code into Reusable Logic

**Milestone:** Prompt Builder CLI

---

## Phase 2 — Practical Python
### Days 11–18

11. Function Arguments, Return Values and Type Hints
12. Modules and Packages — Organizing Python Projects
13. Managing Python Dependencies with `uv`
14. Virtual Environments and `pyproject.toml`
15. Exception Handling — Writing Code That Doesn't Break
16. Reading and Writing Files
17. Object-Oriented Python for AI Developers
18. Dataclasses, Pydantic and Structured Data

**Milestone:** AI Configuration Manager

---

## Phase 3 — Data, JSON and APIs
### Days 19–24

19. Understanding JSON — The Language of AI APIs
20. Working with CSV and Structured Data
21. Introduction to HTTP and REST APIs
22. Calling APIs with Python
23. Environment Variables, `.env` and API Keys
24. `async` / `await` — Why Async Programming Matters for AI

**Milestone:** API-Powered Information Assistant

---

## Phase 4 — AI and ML Foundations
### Days 25–30

25. AI vs Machine Learning vs Deep Learning vs Generative AI
26. How Machine Learning Learns from Data
27. Training, Validation, Testing and Inference
28. Neural Networks Explained for Python Developers
29. From Neural Networks to Transformers
30. How Generative AI Changed Software Development

---

## Phase 5 — LLM and GenAI Fundamentals
### Days 31–38

31. What Exactly Is a Large Language Model?
32. Tokens, Context Windows and Tokenization
33. Transformer Architecture Without the Mathematics
34. System, User and Assistant Messages
35. Your First LLM Call from Python
36. Temperature, Max Tokens and Model Parameters
37. Structured Outputs and JSON Responses
38. Streaming LLM Responses

---

## Phase 6 — Prompt Engineering
### Days 39–44

39. Prompt Engineering Is More Than Writing Good Questions
40. Instructions, Context, Constraints and Output Formats
41. Zero-Shot, One-Shot and Few-Shot Prompting
42. Structured Prompt Design
43. Prompt Templates and Dynamic Prompts with Python
44. Prompt Testing, Evaluation and Common Failure Modes

**Milestone:** AI Content Assistant

---

## Phase 7 — Embeddings and Vector Search
### Days 45–51

45. Why Keyword Search Isn't Enough for AI
46. What Are Embeddings?
47. Embeddings as Vectors — Intuition Without Heavy Mathematics
48. Cosine Similarity Explained Visually
49. Building Your First Semantic Search
50. Vector Databases and Vector Indexes
51. Keyword vs Semantic vs Vector vs Hybrid Search

**Milestone:** Semantic Search Engine

---

## Phase 8 — RAG
### Days 52–58

52. What Problem Does RAG Solve?
53. RAG Architecture Step by Step
54. Loading and Parsing Documents
55. Chunking Strategies — Why They Matter
56. Embedding, Indexing and Retrieving Documents
57. Building a Complete RAG Pipeline
58. RAG Quality: Retrieval, Grounding, Citations and Evaluation

**Milestone:** Ask My Documents

---

## Phase 9 — Tool Calling and Agents
### Days 59–64

59. Chatbot vs AI Assistant vs AI Agent
60. What Is Tool / Function Calling?
61. Build Your First Python Tool for an LLM
62. Multiple Tools and Tool Selection
63. The Agent Loop: Think → Choose Tool → Act → Observe
64. Memory, State and Context in Agentic Applications

**Milestone:** Research Assistant Agent

---

## Phase 10 — Microsoft Foundry
### Days 65–70

65. Microsoft Foundry: From Python Prototype to Enterprise AI
66. Models, Projects, SDKs and Foundry Architecture
67. Building Your First Foundry Agent with Python
68. File Search, Vector Stores and Enterprise Knowledge
69. Azure AI Search + Foundry Agents
70. Foundry Agent Tools, Observability and Evaluation

**Milestone:** Enterprise Knowledge Agent

---

## Phase 11 — Agent Frameworks: Microsoft Agentic Framework and Google ADK
### Days 71–74

71. Agent Frameworks: Why They Matter and How They Differ from Managed Platforms
72. Build Your First Agent with Microsoft Agentic Framework
73. Build Your First Agent with Google ADK
74. Tools, State, Memory and Multi-Agent Workflows Across Both Frameworks

**Milestone:** Cross-Framework Agent Workflow

---

## Phase 12 — MCP and Multi-Agent Systems
### Days 75–77

75. Model Context Protocol: Why MCP Matters
76. Build Your First MCP Server with Python
77. Multi-Agent Architecture: Agents, MCP, Tools and Delegation

**Milestone:** MCP-Enabled Multi-Agent System

---

## Phase 13 — Production AI
### Days 78–80

78. Production GenAI Architecture: What Changes After the Prototype?
79. Security, Secrets, Guardrails, Logging, Tracing and Evaluation
80. Deploying Your Agentic AI Application — The Complete Journey

**Final milestone:** Production-Ready Agentic AI Application

---

# 4. Standard Article Template

Every article should follow the same logical rhythm while still sounding natural.

## 4.1 Header

Use:

```text
Python for AI & GenAI Developers — Day XX
From Fundamentals to Agentic AI
```

Then add the article title.

---

## 4.2 Hook / Problem

Start with a real question, problem, scenario, or surprising observation.

Avoid starting with a dictionary definition.

Good:

> A Python dictionary may look simple today, but the same structure will later hold model parameters, tool definitions, messages and API payloads.

Weak:

> A dictionary is a collection of key-value pairs.

---

## 4.3 What You'll Learn

Use 3–5 outcomes.

Example:

- What a Python dictionary is
- How to create and update one
- How dictionaries appear in AI API payloads
- How to use them in a small exercise

---

## 4.4 Why It Matters for AI Developers

Every post must explicitly connect the topic to AI development.

Examples:

- Strings → prompts and responses
- Lists → messages, retrieved chunks, tools
- Dictionaries → JSON and API payloads
- Functions → tools and reusable agent actions
- Classes → agents, services and abstractions
- Async → parallel API/tool calls
- Files → document ingestion
- Pydantic → structured AI inputs/outputs

---

## 4.5 Concept Explained

Explain the concept simply before showing code.

Use one idea at a time.

Avoid dense theory unless necessary.

---

## 4.6 Python Code Example

Start with the smallest useful example.

Then progressively improve it.

---

## 4.7 Understand the Code

Explain only the important lines.

Do not explain obvious syntax line by line unless the learner genuinely needs it.

---

## 4.8 AI Connection

Show how today's concept appears later in GenAI.

This section is mandatory.

---

## 4.9 Try It Yourself

Provide a small hands-on exercise.

It should take approximately 5–10 minutes.

---

## 4.10 Mini Challenge

Give one slightly harder exercise that requires modification rather than copying.

---

## 4.11 Common Beginner Mistakes

Include 2–5 common mistakes when applicable.

---

## 4.12 What We Built Today

Summarize the outcome in 3–5 bullets.

---

## 4.13 Tomorrow's Hook

End with one short forward-looking hook.

The learner should understand why the next post logically follows.

---

# 5. Article-Writing Rules

## Rule 1 — Teach for beginners

Assume no Python knowledge at the beginning.

Do not assume familiarity with:

- classes
- APIs
- JSON
- async
- tokens
- embeddings
- vector databases
- RAG
- agents
- MCP

Introduce terminology before using it deeply.

---

## Rule 2 — Keep AI relevance visible

Do not let early Python posts feel disconnected from the final goal.

Every article should include at least one AI-related example, analogy, or preview.

---

## Rule 3 — One primary concept per post

Avoid turning one article into a chapter covering five unrelated concepts.

---

## Rule 4 — Prefer progressive examples

Use:

```text
Simple Example
   ↓
Improved Example
   ↓
AI-Oriented Example
```

---

## Rule 5 — Avoid framework-first teaching

Do not hide concepts behind LangChain, ADK, Foundry, or another framework before explaining the mechanics.

---

## Rule 6 — Avoid unnecessary mathematics

For embeddings, cosine similarity, transformers, etc., explain intuition first.

Add mathematical detail only when it improves understanding.

---

## Rule 7 — Use real AI development vocabulary

Introduce professional terminology gradually:

- inference
- context
- tokens
- grounding
- retrieval
- tool calling
- orchestration
- state
- observability
- evaluation
- latency
- guardrails

---

## Rule 8 — Maintain continuity

Where possible, reuse concepts and code from earlier posts.

Readers should feel that the system is evolving.

---

## Rule 9 — Keep social posts readable

Recommended length:

- Standard article: 800–1,500 words
- Complex architecture article: up to ~2,000 words
- Avoid unnecessary long-form theory

---

## Rule 10 — Always end with forward momentum

The final paragraph should make the next post feel useful and inevitable.

---

# 6. Code Conventions

## 6.1 Python Version

Prefer modern Python 3.x syntax.

Use features only after they have been explained.

---

## 6.2 Package Management

Use **`uv` as the package manager throughout the entire series**.

Do not use `pip` in the tutorial commands, setup instructions, project guides, or milestone projects.

Use commands such as:

```bash
uv init
```

```bash
uv add package-name
```

```bash
uv sync
```

```bash
uv run python script.py
```

For notebooks or development dependencies, continue to use `uv`-based project management so the learner experiences one consistent workflow from Day 1 through Day 80.

---

## 6.3 Project Configuration

Prefer:

```text
pyproject.toml
```

Avoid teaching legacy dependency management as the main path.

---

## 6.4 File Naming

Use lowercase snake_case.

Good:

```text
prompt_builder.py
document_loader.py
vector_search.py
research_agent.py
```

Avoid:

```text
PromptBuilder.py
My Script.py
test123.py
```

---

## 6.5 Variable Naming

Use descriptive names.

Good:

```python
user_prompt = "Explain embeddings"
retrieved_documents = []
```

Avoid:

```python
x = "Explain embeddings"
d = []
```

---

## 6.6 Function Naming

Use verbs where practical.

```python
load_document()
build_prompt()
generate_response()
search_documents()
```

---

## 6.7 Type Hints

Introduce type hints gradually and use them consistently after Day 11.

Example:

```python
def build_prompt(topic: str, tone: str) -> str:
    ...
```

---

## 6.8 Docstrings

Use short docstrings for reusable functions/classes in later phases.

---

## 6.9 Secrets

Never hardcode API keys.

Use:

```text
.env
```

and:

```text
.env.example
```

for public examples.

---

## 6.10 Error Handling

Show realistic error handling after the exception-handling lesson.

Avoid hiding all errors with broad `except Exception:` unless explaining why.

---

## 6.11 Code Complexity

Keep each article's main code sample small enough to understand.

Move larger implementations into milestone projects.

---

# 7. Visual and Infographic Specification

## 7.1 Core Style

Use a consistent professional dark technology theme.

Preferred visual language:

- dark charcoal / near-black background
- cyan and electric blue accents
- subtle purple highlights
- white primary text
- thin glowing borders
- restrained gradients
- clean technical icons
- high contrast
- spacious layout

Avoid excessive neon, clutter, or generic robot artwork.

---

## 7.2 Branding

Every hero visual should include:

```text
Python for AI & GenAI Developers
Day XX
Article Title
From Fundamentals to Agentic AI
```

---

## 7.3 Hero Card

Use for every article.

Purpose:

- identify the topic
- maintain series recognition
- create consistency in social feeds

---

## 7.4 Concept Infographic

Use when explaining:

- AI vs ML vs GenAI
- tokens
- context windows
- embeddings
- vector similarity
- prompt structure
- RAG
- agent concepts

---

## 7.5 Architecture Diagram

Use for:

- APIs
- semantic search
- RAG
- tool calling
- agents
- Microsoft Foundry
- Google ADK
- MCP
- multi-agent systems
- production architecture

---

## 7.6 Code Flow Visual

Use when a beginner may struggle to understand execution order.

Example:

```text
Input
  ↓
Function
  ↓
Processing
  ↓
Return Value
```

---

## 7.7 Visual Rule

Do not create an infographic merely because a post exists.

Create one when it improves understanding, memory, or engagement.

---

# 8. Diagram Conventions

Use left-to-right or top-to-bottom flows.

Avoid crossing arrows wherever possible.

Use consistent semantics.

Recommended shapes:

- Rectangle → process / component
- Rounded rectangle → service / application
- Cylinder → database / vector store
- Cloud → managed platform / external service
- Circle → user / trigger
- Arrow → data or execution flow

---

## 8.1 Example: RAG

```text
User Question
      ↓
Retriever
      ↓
Vector Search
      ↓
Relevant Chunks
      ↓
Prompt + Context
      ↓
LLM
      ↓
Grounded Answer
```

---

## 8.2 Example: Agent

```text
User Request
     ↓
Agent
     ↓
Decide
 ┌───┼────────┐
 ↓   ↓        ↓
Tool API   Search
 └───┼────────┘
     ↓
Observation
     ↓
Final Response
```

---

# 9. Naming Conventions

## Series Name

**Python for AI & GenAI Developers**

## Series Subtitle

**From Fundamentals to Agentic AI**

---

## Article Naming

Use:

```text
Day XX — Topic
```

Example:

```text
Day 46 — What Are Embeddings?
```

---

## Phase Folder Naming

Use:

```text
phase01_python_foundations
phase02_practical_python
phase03_data_apis
...
phase13_production
```

---

## Daily Folder Naming

Use:

```text
day01_environment_setup
day02_variables
day03_strings
```

---

## Image Naming

Use:

```text
day46_hero.png
day46_embeddings_flow.png
day46_vector_space_infographic.png
```

---

## Article File Naming

Use:

```text
day46_what_are_embeddings.md
```

---

# 10. Repository Conventions

Recommended repository:

```text
python-ai-genai/
│
├── README.md
├── SERIES_MASTER_GUIDE.md
├── pyproject.toml
├── uv.lock
├── .env.example
├── .gitignore
│
├── Python/
│   ├── phase01_python_foundations/
│   ├── phase02_practical_python/
│   ├── phase03_data_apis/
│   ├── phase04_ai_foundations/
│   ├── phase05_llm/
│   ├── phase06_prompt_engineering/
│   ├── phase07_embeddings/
│   ├── phase08_rag/
│   ├── phase09_agents/
│   ├── phase10_microsoft_foundry/
│   ├── phase11_google_adk/
│   ├── phase12_mcp_multi_agent/
│   └── phase13_production/
│
├── NoteBooks/
│   ├── embeddings/
│   ├── rag/
│   ├── vector_search/
│   └── experiments/
│
├── Projects/
│   ├── prompt_builder/
│   ├── configuration_manager/
│   ├── api_information_assistant/
│   ├── ai_content_assistant/
│   ├── semantic_search/
│   ├── ask_my_documents/
│   ├── research_agent/
│   ├── enterprise_knowledge_agent/
│   └── multi_agent_system/
│
├── Data/
│   └── samples/
│
├── Assets/
│   ├── hero/
│   ├── diagrams/
│   ├── infographics/
│   └── screenshots/
│
└── Articles/
    ├── phase01/
    ├── phase02/
    ├── phase03/
    ├── ...
    └── phase13/
```

---

# 11. Milestone Project Rules

Each milestone project must:

1. Reuse concepts taught previously.
2. Introduce as few new concepts as possible.
3. Be runnable.
4. Have a clear README.
5. Have a simple architecture diagram when applicable.
6. Include setup instructions.
7. Include expected output.
8. Include one suggested extension challenge.
9. Avoid unnecessary framework complexity.
10. Prepare the learner for the next phase.

---

# 12. Platform and Framework Strategy

## Beginner and Intermediate Phases

Remain vendor-neutral wherever possible.

Use generic Python, AI, LLM, retrieval, and agent concepts before introducing vendor-specific tooling.

---

## Advanced Retrieval, RAG and Enterprise AI Platforms

Teach the concepts first.

Then introduce the two target enterprise platforms:

- **Microsoft Foundry**
- **Gemini Enterprise Agent Platform** (historically known as Vertex AI)

Where relevant, Azure AI Search may be used with Microsoft Foundry for enterprise retrieval and vector/hybrid search scenarios.

The learner should understand retrieval, embeddings, chunking, grounding, and RAG before using managed platform abstractions.

---

## Agent Frameworks

Teach plain Python functions, tool calling, the agent loop, state, memory, orchestration, and delegation first.

Then introduce the two target agent frameworks:

- **Microsoft Agentic Framework**
- **Google ADK**

The frameworks must be presented as implementations of transferable agentic concepts, not as the concepts themselves.

---

## Multi-Agent and Interoperability

Introduce:

- MCP
- delegation
- orchestration
- state
- memory
- tool ecosystems
- agent-to-agent collaboration
- framework-to-platform integration

---

# 13. Microsoft Foundry Platform Usage Rule

Do not make Foundry the explanation for the concept.

The learner should first understand:

```text
What the concept is
→ Why it exists
→ How to build a simplified version
→ What Foundry manages for us
```

This avoids vendor lock-in while still preparing learners for enterprise use.

---

# 14. Agent Framework Usage Rules

## 14.1 Microsoft Agentic Framework

Use Microsoft Agentic Framework to demonstrate how transferable agent concepts are implemented in the Microsoft ecosystem.

Focus on:

- agent definition
- tools
- state
- memory
- orchestration
- delegation
- multi-agent workflows
- integration with Microsoft Foundry where appropriate

Do not use the framework as a substitute for explaining the underlying agent loop.

---

## 14.2 Google ADK

Use Google ADK to reinforce the same transferable agent concepts in the Google ecosystem.

Focus on:

- agent definition
- tools
- sessions
- state
- memory
- delegation
- multi-agent workflows
- integration with Gemini Enterprise Agent Platform where appropriate

Avoid presenting Google ADK as the only way to build agents.

---

# 16. Gemini Enterprise Agent Platform Usage Rule

Treat **Gemini Enterprise Agent Platform** as a managed enterprise AI platform, historically associated with the Vertex AI platform lineage.

The learner should first understand the underlying concepts before platform-specific implementation:

```text
Concept
→ Plain Python
→ SDK / API
→ Agent Framework
→ Managed Platform
```

Use Gemini Enterprise Agent Platform for advanced enterprise scenarios such as managed model access, agent deployment, enterprise integration, observability, and production AI workflows where appropriate.

---

# 16. Tomorrow Hook Rule

The “Tomorrow” hook is a core engagement mechanism.

It must do three things:

1. Reference what the learner achieved today.
2. Identify a limitation, missing capability, or next logical question.
3. Reveal enough about tomorrow to create curiosity.

---

## 15.1 Standard Pattern

```text
Today we learned/built [X].

But [limitation or unanswered question].

Tomorrow, we'll [next capability].
```

---

## 15.2 Example — Variables to Strings

> Today we learned how Python stores information in variables.
>
> But AI applications work heavily with text — prompts, instructions, responses and documents.
>
> Tomorrow, we'll learn how Python works with strings and begin handling the kind of data every GenAI application depends on.

---

## 15.3 Example — Dictionaries to Functions

> Today we used dictionaries to organize structured information.
>
> But copying the same logic every time would quickly make our programs messy.
>
> Tomorrow, we'll start turning repeated logic into reusable Python functions.

---

## 15.4 Example — Embeddings to Similarity

> Today we converted meaning into vectors.
>
> But a vector alone is not useful until we can compare it with another vector.
>
> Tomorrow, we'll see how cosine similarity lets us measure which pieces of text are semantically close.

---

## 15.5 Example — RAG to Agents

> Today our application retrieved relevant knowledge before generating an answer.
>
> But it still follows a fixed workflow.
>
> Tomorrow, we'll begin giving the model the ability to choose what action to take by introducing tool calling.

---

## 15.6 Hook Constraints

Keep it:

- 2–4 sentences
- concise
- specific
- connected to the next lesson
- free from exaggerated clickbait

Avoid:

- “You won't believe what happens tomorrow.”
- vague hype
- unrelated teasers

---

# 17. Social Publishing Format

Recommended LinkedIn / Facebook post structure:

```text
Series Header
↓
Hook
↓
Today's Learning
↓
Core Explanation
↓
Code / Diagram
↓
AI Connection
↓
Try It Yourself
↓
Key Takeaways
↓
Tomorrow's Hook
↓
Relevant Hashtags
```

Keep hashtags limited and relevant.

---

# 18. Engagement Strategy

Do not rely on engagement tricks.

Build engagement through progression.

Use:

- recurring milestone projects
- “Try It Yourself” tasks
- mini challenges
- before/after architecture
- “we built this earlier, now we improve it” moments
- tomorrow hooks
- visual continuity

The strongest retention strategy is learner progress.

---

# 19. Quality Checklist for Every Article

Before publishing, verify:

- [ ] Is the topic appropriate for the learner's current level?
- [ ] Is the AI relevance explicit?
- [ ] Is there one primary learning objective?
- [ ] Is the explanation understandable without previous expertise?
- [ ] Is the code runnable?
- [ ] Are all package-management commands based exclusively on `uv`?
- [ ] Are secrets handled safely?
- [ ] Are naming conventions consistent?
- [ ] Is the code sample unnecessarily complex?
- [ ] Is there a Try It Yourself section?
- [ ] Is there a mini challenge where appropriate?
- [ ] Are common mistakes explained?
- [ ] Is a visual genuinely useful?
- [ ] Does the article connect to earlier material?
- [ ] Does the Tomorrow hook logically lead to the next article?

---

# 20. Quality Checklist for Visuals

Before publishing any visual, verify:

- [ ] Dark professional theme
- [ ] Consistent series branding
- [ ] Day number visible
- [ ] Topic title readable on mobile
- [ ] High contrast
- [ ] Minimal clutter
- [ ] No unnecessary decorative AI robots
- [ ] Correct terminology
- [ ] Clear visual hierarchy
- [ ] Architecture arrows make sense
- [ ] Visual adds learning value

---

# 21. The Series Promise

Every post should move the learner one visible step forward.

The learner should gradually progress from:

```text
I can write Python
        ↓
I can call APIs
        ↓
I understand LLMs
        ↓
I can build GenAI apps
        ↓
I understand embeddings
        ↓
I can build RAG
        ↓
I can add tools
        ↓
I can build agents
        ↓
I can use Microsoft Agentic Framework and Google ADK
        ↓
I can work with Microsoft Foundry and Gemini Enterprise Agent Platform
        ↓
I understand MCP
        ↓
I can design multi-agent systems
        ↓
I can think about production AI
```

The ultimate goal is not simply to teach Python.

It is to build the learner's confidence and engineering intuition so they can understand, build and evolve modern AI systems.

---

# 22. Guiding Principle

> **Same Python. Bigger possibilities.**

Learn the language.

Understand the concepts.

Build real systems.

Progress from fundamentals to agentic AI.
