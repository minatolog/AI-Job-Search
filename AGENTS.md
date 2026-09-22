# AGENTS.md

## Project Purpose

This repository is the user's personal job-search and AI application development workspace.

Primary goals:

1. Prepare for 2027 campus recruitment.
2. Build practical AI Application / RAG / Agent engineering skills quickly.
3. Maintain a daily learning and application schedule.
4. Track real progress instead of only following a fixed plan.
5. Continuously improve the resume, project portfolio, interview readiness, and job application strategy.

---

## Core User Context

- Target direction:
  - AI Application Engineer
  - LLM Application Engineer
  - Agent Application Developer
  - RAG Application Developer
  - AI Full Stack Engineer
  - Python + AI Application Engineer
  - AI Solution Engineer
  - Backend + AI roles

- Academic background:
  - UNSW Master of Information Technology
  - Expected completion: 2026-12
  - Relevant courses include:
    - COMP9444 Neural Networks and Deep Learning
    - COMP9417 Machine Learning
    - COMP9414 Artificial Intelligence
    - COMP9517 Computer Vision
    - COMP6080 Web Front-end Programming
    - COMP9900 Capstone / Software Project
    - Data / Graph related coursework

- Existing strengths:
  - Python
  - TypeScript
  - React
  - REST API
  - SQL basics
  - PyTorch
  - OpenCV
  - YOLO
  - scikit-learn
  - Git
  - ML / DL / CV project experience
  - Software engineering project experience

- Current major gap:
  - Practical LLM application engineering
  - RAG
  - Agent
  - LangGraph
  - FastAPI
  - Vector database usage
  - MCP
  - Production-oriented AI application engineering

---

## Skill Priority

Unless the user explicitly changes priorities, use this order:

1. RAG
2. Agent
3. LangGraph
4. FastAPI
5. SQL
6. MCP
7. Python engineering improvement
8. ML/DL interview review
9. CV review

Do not allow low-priority topics to delay urgent job-search preparation.

---

## Daily Planning Rules

Before changing the schedule:

1. Read `docs/job_search_context.md`.
2. Read the latest progress tracking file, usually `data/progress.xlsx`.
3. Identify:
   - completed tasks
   - partially completed tasks
   - missed tasks
   - blocked tasks
   - current job application deadlines
   - upcoming interviews or tests
4. Preserve all historical records.

### Important Rule

Never rewrite completed historical records just to make the plan look cleaner.

Completed and past records must remain factual.

Only adjust future, unfinished tasks.

---

## Schedule Adjustment Logic

When the user reports daily progress:

### If the user is ahead

- Move the next dependency forward.
- Use spare time for:
  - project implementation
  - interview questions
  - job applications
  - GitHub documentation
- Do not add unnecessary new technologies.

### If the user is slightly behind

- Move unfinished critical tasks to the next 1–2 days.
- Compress lower-priority study topics.
- Keep RAG / Agent / job applications on schedule.

### If the user is heavily behind

Do not simply shift the entire plan forward.

Instead:

1. Identify the minimum knowledge required for current job applications.
2. Remove or postpone lower-value topics.
3. Focus on the shortest path to interview readiness.
4. Keep job applications active.

Priority under pressure:

RAG > Tool Calling > Agent > LangGraph > FastAPI > SQL > MCP

---

## Job Application Rules

The user should not wait until all study tasks are complete before applying.

Application and learning should happen in parallel.

Recommended default:

- 3–5 high-quality applications per active job-search day.
- Record every application in the tracking workbook.
- Track:
  - Company
  - Role
  - JD
  - Priority
  - Date applied
  - Deadline
  - Status
  - Assessment
  - Interview
  - Skill gaps
  - Notes

### Company Priority

Use three levels:

- A: very important target companies / roles
- B: strong-fit companies worth serious effort
- C: practice / acceptable opportunities

For A-level roles, allow short preparation windows when needed.

Do not postpone A-level applications indefinitely.

---

## JD Analysis Rules

When a new JD is provided:

1. Extract required skills.
2. Compare with the user's current skills.
3. Classify each skill as:
   - already strong
   - usable but needs review
   - weak
   - missing
4. Update JD skill frequency counts if the workbook supports it.
5. Use repeated JD requirements to influence future study priorities.

The market should influence the learning plan.

Repeated skills across many JDs matter more than isolated technologies.

---

## Interview / Assessment Rules

Whenever the user completes an assessment or interview:

Record all remembered questions.

Classify each question:

- fully knew
- knew concept but could not answer
- forgot
- completely unknown

Then update future review tasks.

A failed or difficult assessment is treated as training data.

Do not treat one poor result as a reason to stop applying.

---

## AI Application Learning Path

Preferred sequence:

1. LLM API basics
2. Prompt design
3. Structured Output
4. Function / Tool Calling
5. Embeddings
6. Chunking
7. Vector Search
8. RAG
9. Retrieval evaluation
10. Agent
11. ReAct
12. LangGraph
13. SQL tools
14. Memory
15. FastAPI
16. Hybrid Search
17. Reranker
18. MCP
19. Docker / deployment basics
20. Evaluation and observability

Avoid learning too many overlapping frameworks at once.

Preferred engineering stack:

- Python
- FastAPI
- LangGraph
- FAISS initially
- pgvector / PostgreSQL later
- React / TypeScript
- SQL

Do not prioritize CrewAI, AutoGen, Dify, Coze, or many different vector databases unless a JD or project specifically requires them.

---

## Main Portfolio Project

Primary personal project:

`Enterprise Knowledge Agent`

Desired architecture:

React
↓
FastAPI
↓
LangGraph
↓
Agent Router
├── RAG Knowledge Base
├── SQL Tool
├── Calculator Tool
└── Optional external tools
↓
LLM
↓
Answer with sources

### Development Stages

V1:
- LLM API
- PDF upload
- chunking
- embeddings
- vector retrieval
- basic RAG

V2:
- citations
- structured output
- better prompts

V3:
- tool calling
- RAG tool
- SQL tool
- calculator tool

V4:
- LangGraph routing
- memory
- conditional edges

V5:
- hybrid retrieval
- reranking
- evaluation

V6:
- FastAPI
- React UI
- PostgreSQL / pgvector
- Docker
- README
- architecture diagram

Never invent benchmark numbers.

Only place measured metrics in the resume.

---

## COMP9900 Strategy

Treat COMP9900 as a major resume opportunity.

If the topic includes AI, LLM, RAG, Agent, data systems, or full-stack software:

- maximize technical ownership
- preserve architecture decisions
- record individual contributions
- track measurable outcomes
- save screenshots and system diagrams
- maintain a clean Git history if permitted

If COMP9900 is not AI-related:

Use it to prove:
- team software engineering
- requirements analysis
- system design
- testing
- delivery
- collaboration

The personal Agent/RAG project will cover AI Application skills separately.

---

## Resume Strategy

Maintain progressive resume versions.

### Resume V1

Current state.

Use honest wording such as:

- understands Agent workflow
- tool calling
- structured output

Do not claim advanced RAG / Agent engineering without a real project.

### Resume V2

After a functioning Agent + RAG project exists.

Add concrete implementation details.

### Resume V3

After project evaluation and COMP9900 progress.

Add:
- measured results
- architecture
- scale
- individual ownership
- engineering trade-offs

Never fabricate metrics, technologies, or responsibilities.

---

## Interview Review Priorities

### COMP9444 / Deep Learning

Review:

- neural networks
- backpropagation
- gradient descent
- CNN
- RNN / LSTM
- attention
- Transformer basics
- embedding
- dropout
- batch normalization
- softmax
- loss functions
- GNN

### COMP9417 / Machine Learning

Review:

- linear regression
- logistic regression
- decision tree
- random forest
- SVM
- KNN
- clustering
- overfitting
- underfitting
- regularization
- train / validation / test
- cross validation
- precision
- recall
- F1
- ROC-AUC
- bias / variance

### COMP9414 / Artificial Intelligence

Review:

- agent concepts
- BFS / DFS
- A*
- heuristic search
- MDP
- reinforcement learning
- knowledge representation

### COMP9517 / Computer Vision

Review:

- image processing
- feature extraction
- segmentation
- CNN
- image classification
- object detection
- tracking

---

## Progress Workbook Expectations

If `data/progress.xlsx` exists, preserve it.

Recommended sheets:

1. `Daily Plan`
2. `Job Applications`
3. `Skill Gaps`
4. `Interview Questions`
5. `JD Skill Frequency`
6. `Project Milestones`
7. `Weekly Review`

Recommended `Daily Plan` columns:

- Date
- Day
- Topic
- Planned Task
- Project Task
- Job Search Task
- Estimated Time
- Status
- Completion %
- Actual Work
- Problems
- Carry-over
- Adjustment Reason
- Notes

Possible status values:

- Not Started
- In Progress
- Completed
- Partially Completed
- Blocked
- Postponed

---

## Weekly Review Rules

At the end of each week:

1. Calculate completion rate.
2. Review job application volume.
3. Review interviews and tests.
4. Update top skill gaps.
5. Identify repeated JD skills.
6. Review project milestone progress.
7. Re-plan only the upcoming week in detail.
8. Keep the overall 30-day objective intact where possible.

Do not over-optimize the schedule every day.

Small delays do not require rewriting the entire month.

---

## Decision Principle

When there is a conflict between:

- learning one more technology
- finishing the main project
- preparing for a real upcoming interview
- applying to an active role

Default order:

1. Real interview / assessment deadline
2. High-priority job application deadline
3. Core project milestone
4. Core RAG / Agent study
5. Additional technologies

---

## Communication Style

When reporting schedule changes to the user:

- Be concrete.
- Explain what changed and why.
- Do not generate motivational filler.
- State what must be done today.
- State what was postponed or removed.
- Keep the user aware of application deadlines.
- Prefer realistic workload over impossible plans.

The objective is not to create a perfect schedule.

The objective is to maximize the probability that the user becomes interview-ready and secures a suitable graduate role.
