# IBM RAG & Agentic AI — Learning-to-Earning Market Execution Plan

**File:** `IBM_RAG_Agentic_AI_Learning_to_Earning_Plan.md`

## North Star

> **We are not doing this certificate to learn coding syntax.
> We are using it to become capable of understanding, building, testing, demonstrating, and selling real AI business solutions.**

Our target is:

**COURSE → IMPLEMENT → TRANSFORM → PRODUCTIZE → PROVE → PUBLISH → SELL**

The certificate is a **learning source**.

The actual destination is:

**Market Capability + Working Products + Client Proof + Income**

---

# 1. Final Capability We Want

By the end of this program, we should be able to say:

> Give us a business problem, documents, data, workflows, APIs, or repetitive work.
> We can work out whether RAG, agents, automation, multimodal AI, MCP, or a simpler solution is appropriate — and build a working system.

We are NOT trying to become:

* LangChain specialists only
* CrewAI specialists only
* prompt engineers only
* IBM product specialists only
* tutorial coders

We are becoming:

## AI-Assisted Solution Builders

Core capabilities:

* RAG
* document intelligence
* vector search
* embeddings
* LLM applications
* tool calling
* structured outputs
* API integration
* LangChain
* LangGraph
* agentic workflows
* human-in-the-loop systems
* multi-agent orchestration
* multimodal AI
* MCP
* AI evaluation
* security
* deployment
* business workflow integration

---

# 2. Operating Rule for Every Lecture

For every meaningful lecture:

* [ ] Watch the lecture
* [ ] Identify the capability being taught
* [ ] Open the same or equivalent tool
* [ ] Reproduce the implementation
* [ ] Understand what each major component is doing
* [ ] Replace toy data with our own business problem
* [ ] Use AI to improve/refactor/debug the implementation
* [ ] Test failure cases
* [ ] Try an open/local alternative where practical
* [ ] Save the working implementation
* [ ] Screen-record our implementation
* [ ] Extract one reusable component
* [ ] Ask: **Who would pay for this capability?**
* [ ] Add it to a real product or portfolio case study

We do NOT move forward merely because:

> "Lesson completed."

We move forward when:

> **"Capability demonstrated."**

---

# 3. Permanent Output From Every Course

Every course should create at least:

* [ ] 1 working application or substantial product feature
* [ ] 1 reusable code/component asset
* [ ] 1 real business use case
* [ ] 1 screen-recorded demonstration
* [ ] 1 GitHub/project record
* [ ] 1 portfolio/case-study entry
* [ ] 1 possible LFDS/MNI service
* [ ] 1 lesson idea for DeTLeng AI Learning Lab

---

# 4. Course 1 — Develop Generative AI Applications

## Market Capability

Build useful LLM-powered applications rather than simply chatting with an AI model.

## Skills to Extract

* prompt templates
* structured prompts
* chains
* JSON outputs
* model comparison
* Flask/web interface
* tool calling basics
* application architecture

## Market Tasks

* [ ] Create an application that converts unstructured user requests into structured JSON
* [ ] Build an AI-powered business problem intake form
* [ ] Compare at least 2 different models/providers
* [ ] Make the model provider replaceable
* [ ] Create validation for AI-generated structured outputs
* [ ] Build a simple web interface
* [ ] Log prompts, outputs, errors, and execution time

## Product 1

### AI Business Intake Assistant

Input:

> "Customers send quotation requests by WhatsApp and I keep losing track."

Output:

```json
{
  "problem_type": "lead_management",
  "priority": "high",
  "current_process": "WhatsApp",
  "pain_point": "requests are lost",
  "possible_solution": "central enquiry and quotation workflow"
}
```

## Who Could Buy It?

* consultants
* tradespeople
* agencies
* service businesses
* support teams
* professional services

## Revenue Gate

After this course we should already be capable of offering:

**AI-assisted forms, classification, extraction, and structured business intake prototypes.**

---

# 5. Course 2 — Build RAG Applications

## Market Capability

Make AI answer questions using a client's own information.

## Skills to Extract

* document ingestion
* chunking
* embeddings
* retrieval
* RAG
* LangChain
* LlamaIndex
* Gradio/UI
* answer grounding

## Market Tasks

* [ ] Upload business PDFs
* [ ] Split and index documents
* [ ] Ask questions against those documents
* [ ] Return source references
* [ ] Test questions whose answers do not exist
* [ ] Reduce hallucination
* [ ] Add "I don't know" behaviour
* [ ] Build usable web UI
* [ ] Test at least 20 business questions

## Product 2

# Company Knowledge Assistant

Example data:

* employee handbook
* procedures
* FAQs
* technical manuals
* training documents
* policies
* product information

User asks:

> "What is our procedure when a supplier delivery is damaged?"

AI searches company information and responds with grounded information.

## Who Could Buy It?

* manufacturing companies
* training centres
* SMEs
* professional offices
* community organisations
* educational organisations

## Revenue Gate

This should become our **first serious sellable AI product**.

---

# 6. Course 3 — Vector Databases for RAG

## Market Capability

Build intelligent semantic search rather than simple keyword search.

## Skills to Extract

* embeddings
* similarity search
* ChromaDB
* vector storage
* collections
* indexing
* update/delete
* recommendation logic

## Market Tasks

* [ ] Create vector database from real documents
* [ ] Compare keyword vs semantic search
* [ ] Build similarity scoring
* [ ] Add metadata filtering
* [ ] Support document updates
* [ ] Support deletion/re-indexing
* [ ] Measure retrieval relevance
* [ ] Build a semantic recommendation feature

## Product Feature

### Intelligent Business Search

Examples:

* find similar previous customer problems
* find related maintenance incidents
* find similar products
* find related policies
* find similar support tickets
* find relevant training material

## Commercial Lesson

**Vector databases are infrastructure.**

Do not sell:

> "ChromaDB setup."

Sell:

> "Your staff can find the right information even when they don't know the exact words."

---

# 7. Course 4 — Advanced RAG

## Market Capability

Turn a basic chatbot into a reliable business knowledge system.

## Skills to Extract

* advanced retrieval
* FAISS
* Chroma
* HNSW
* retrievers
* ranking
* query improvement
* retrieval optimization
* RAG quality

## Market Tasks

* [ ] Compare multiple retrieval strategies
* [ ] Create retrieval benchmark questions
* [ ] Measure answer accuracy
* [ ] Measure retrieval relevance
* [ ] Add metadata filtering
* [ ] Experiment with chunk sizes
* [ ] Add source citations
* [ ] Add confidence/uncertainty handling
* [ ] Implement fallback when evidence is insufficient

## Product 2.0

### Reliable Company Knowledge Assistant

Must support:

* citations
* source documents
* controlled answers
* no-answer behaviour
* document filtering
* retrieval quality testing
* admin updating

## Market Proof Required

Create a case study:

### Basic RAG vs Production-Oriented RAG

Show:

* before
* errors
* improvements
* retrieval changes
* final performance

---

# 8. Course 5 — Multimodal Generative AI

## Market Capability

Process more than text.

Business information may arrive as:

* PDFs
* photographs
* screenshots
* audio
* scanned forms
* diagrams
* video
* text

## Market Tasks

* [ ] Extract information from images
* [ ] Process audio/transcription
* [ ] Analyse screenshots
* [ ] Combine image + text context
* [ ] Convert multimodal input to structured JSON
* [ ] Validate extracted information
* [ ] Route outputs into business workflows

## Product 3

# AI Document & Media Processor

Possible inputs:

**invoice photo → structured data**

**inspection photo → issue description**

**voice note → task/request**

**document → summary + structured fields**

**product image → classification**

## Who Could Buy It?

* warehouses
* manufacturers
* field workers
* tradespeople
* administration teams
* accountants
* property businesses

---

# 9. Course 6 — Fundamentals of Building AI Agents

## Market Capability

Move from:

**AI answers**

to:

**AI performs controlled tasks.**

## Skills to Extract

* tool calling
* agent reasoning
* APIs
* SQL/database tools
* data visualisation
* external actions
* structured workflows

## Market Tasks

Build an agent capable of:

* [ ] receiving a request
* [ ] deciding which tool is required
* [ ] querying data
* [ ] performing calculations
* [ ] generating a result
* [ ] asking for human approval when appropriate
* [ ] recording actions
* [ ] handling tool failure

## Product 4

# Business Operations Agent

Example:

Manager asks:

> "Show me this month's delayed orders and prepare a summary."

Agent:

1. queries database
2. calculates delayed orders
3. creates chart
4. identifies trends
5. produces management summary

## Market Rule

Do NOT sell:

> "AI agent."

Sell:

> "Ask your operational data a business question and receive an actionable answer."

---

# 10. Course 7 — LangChain + LangGraph Agentic AI

## Market Capability

Build stateful, controlled, multi-step AI workflows.

## Skills to Extract

* LangGraph
* state
* memory
* routing
* conditional logic
* ReAct
* Reflection
* Reflexion
* agentic RAG
* orchestration
* human-in-the-loop

## Market Tasks

* [ ] Create stateful workflow
* [ ] Add conditional routing
* [ ] Add retries
* [ ] Add human approval
* [ ] Add memory where genuinely useful
* [ ] Add tool failure handling
* [ ] Add audit trail
* [ ] Add agentic RAG
* [ ] Test workflow interruptions
* [ ] Resume failed/interrupted tasks

## Product 5

# AI Request-to-Action Workflow

Example:

Customer email arrives

↓

AI classifies request

↓

searches company knowledge

↓

checks customer data

↓

drafts response

↓

decides whether human approval is needed

↓

human approves

↓

system sends response

↓

activity logged

This is directly commercially relevant.

---

# 11. Course 8 — Multi-Agent Systems

## Market Capability

Break complex work into specialist AI responsibilities.

## Rule

We will NOT create multi-agent systems simply because they look impressive.

Use multiple agents only when:

**specialisation + coordination genuinely improves the solution.**

## Market Tasks

Build:

* [ ] Research Agent
* [ ] Document Agent
* [ ] Analysis Agent
* [ ] QA/Reviewer Agent
* [ ] Reporting Agent
* [ ] Supervisor/Coordinator

Then test:

* [ ] Is multi-agent better than one agent?
* [ ] Is it more reliable?
* [ ] Is it cheaper?
* [ ] Is it easier to maintain?
* [ ] Where should human judgement enter?

## Product 6

# AI Research & Proposal Team

Example:

Business request arrives

↓

Research Agent investigates

↓

Knowledge Agent searches internal data

↓

Solution Agent develops options

↓

Reviewer checks quality

↓

Proposal Agent creates structured response

↓

Human approves

## Potential Buyers

* consultants
* research organisations
* agencies
* professional services
* proposal/tender teams

---

# 12. Course 9 — MCP

## Market Capability

Allow AI applications to interact with external systems using controlled, reusable interfaces.

## Skills to Extract

* MCP servers
* MCP clients
* tools
* resources
* prompts
* STDIO
* HTTP transport
* authentication
* permissions
* approval
* security
* multi-server connection

## Market Tasks

Create our own MCP server exposing safe business tools:

* [ ] customer lookup
* [ ] inventory lookup
* [ ] document search
* [ ] task creation
* [ ] quote lookup
* [ ] report generation
* [ ] database query
* [ ] email draft request

## Product 7

# Business MCP Connector

AI can interact with:

**Documents
CRM
Database
Website
Internal tools
Reporting systems**

through controlled interfaces.

## Critical Rule

No uncontrolled destructive action.

Sensitive actions require:

**Authentication + permissions + logging + human approval**

---

# 13. Course 10 — Capstone

The IBM capstone is not our final destination.

We will complete it for learning/certificate purposes.

Then build our own flagship capstone.

# MNI Intelligence Desk

## Target Architecture

```text
                         USER
                           |
                           v
                    Intelligence Desk
                           |
          +----------------+----------------+
          |                |                |
          v                v                v
      RAG Layer       Agent Layer      Workflow Layer
          |                |                |
          v                v                v
      Documents         Tools/API        Actions
          |                |                |
          +----------------+----------------+
                           |
                           v
                     Human Approval
                           |
                           v
                         Result
```

## Capabilities

* [ ] document upload
* [ ] RAG
* [ ] citations
* [ ] semantic search
* [ ] structured extraction
* [ ] multimodal input
* [ ] tool calling
* [ ] LangGraph workflow
* [ ] human approval
* [ ] external tools
* [ ] MCP
* [ ] logging
* [ ] basic analytics
* [ ] evaluation
* [ ] security controls
* [ ] replaceable LLM provider
* [ ] local/open-model option
* [ ] cloud-model option

---

# 14. Flagship Sellable Products

By certificate completion we want these products available as working demos.

## A. Company Knowledge Agent

**Problem:** Staff waste time searching documents.

**Solution:** Ask company knowledge naturally.

---

## B. Document Intelligence Processor

**Problem:** Humans manually read/extract information from documents.

**Solution:** Extract, classify, structure and route information.

---

## C. Research Agent

**Problem:** Research across many sources takes too much time.

**Solution:** Search → analyse → organise → produce evidence-backed output.

---

## D. Operations Agent

**Problem:** Managers manually collect operational information.

**Solution:** Agent uses tools/data and produces actionable outputs.

---

## E. AI Workflow Assistant

**Problem:** Requests move manually between emails, people and systems.

**Solution:** Understand → route → retrieve → act → approve → record.

---

## F. Business Knowledge + Action System

**Problem:** Chatbots answer questions but cannot perform work.

**Solution:** RAG + tools + workflows + human approval.

This should become our strongest commercial offer.

---

# 15. Target Markets

## Longford / Ireland

Explore problems in:

* manufacturing
* factories
* warehouses
* training organisations
* professional services
* community organisations
* SMEs
* administration-heavy companies
* trades
* hotels/services

Do NOT lead with:

> "Do you need AI?"

Ask:

* What takes too much time?
* What information is difficult to find?
* What are staff repeatedly searching for?
* What data has to be manually copied?
* Which requests repeatedly arrive?
* What documents have to be manually processed?
* What work depends on one knowledgeable employee?
* What process creates delays?
* What should work better?

---

# 16. Freelance Market Offers

Search/propose around outcomes such as:

### RAG

* company document chatbot
* custom knowledge assistant
* PDF Q&A
* internal documentation AI
* vector search implementation

### Agents

* LangGraph workflow agent
* AI business workflow
* API-connected AI agent
* tool-calling assistant
* research agent
* SQL/data agent

### Automation

* AI document extraction
* email classification
* support automation
* workflow routing
* report generation
* AI-assisted operations

### MCP

* MCP server development
* tool integration
* LLM-to-business-system integration
* secure agent tool access

---

# 17. Portfolio Standard

A project is NOT portfolio-ready merely because it runs.

Every serious portfolio project needs:

* [ ] Business problem
* [ ] Target user
* [ ] Before-state
* [ ] Architecture
* [ ] Why AI was appropriate
* [ ] Why this architecture was chosen
* [ ] Implementation
* [ ] Test cases
* [ ] Failure cases
* [ ] AI limitations
* [ ] Security/privacy considerations
* [ ] Cost considerations
* [ ] Demo
* [ ] Screenshots/video
* [ ] Outcome
* [ ] Possible next version

---

# 18. YouTube / Screen Recording Strategy

We are NOT reproducing IBM/Coursera lectures.

We screen-record **our implementation**.

Format:

## Video Structure

**Problem**

What are we trying to accomplish?

↓

**Course Capability**

What technical idea are we applying?

↓

**Tool**

Open actual environment.

↓

**Implementation**

Build it.

↓

**AI Collaboration**

Use AI visibly for:

* coding
* debugging
* architecture
* testing
* refactoring

↓

**Transformation**

Convert tutorial-style example into real business use.

↓

**Test**

Break it.

↓

**Improve**

Fix weaknesses.

↓

**Result**

Show working output.

↓

**Commercial Question**

Who might use/pay for this?

---

# 19. DeTLeng AI Learning Lab

The same work will eventually become an original learning platform.

Working philosophy:

# Learn AI by Building AI

Suggested learning rhythm:

**UNDERSTAND
→ IMPLEMENT
→ TRANSFORM
→ BREAK
→ DEBUG
→ TEST
→ SHIP**

Each lesson should eventually include:

* explanation
* architecture
* implementation
* runnable/example code
* experiment
* challenge
* business scenario
* AI collaboration
* debugging
* security consideration
* final working result

---

# 20. Open / Vendor-Neutral Strategy

We should understand the IBM implementation but avoid unnecessary vendor lock-in.

Preferred principle:

```text
Application
    |
    v
AI Provider Layer
    |
    +---- Local Model
    +---- OpenAI
    +---- Gemini
    +---- Azure
    +---- IBM
    +---- Other Provider
```

Likewise:

```text
Vector Store
    |
    +---- Chroma
    +---- FAISS
    +---- Other DB
```

And:

```text
Agent Orchestration
    |
    +---- LangGraph
    +---- CrewAI
    +---- AG2
    +---- direct Python
```

## Rule

**Learn the capability more deeply than the tool.**

Tools will change.

Business problems remain.

---

# 21. Revenue Milestones

## Milestone 1 — First Working Demo

After Courses 1–2.

Target:

**AI Business Intake + Company Knowledge Assistant**

* [ ] working locally
* [ ] video demo
* [ ] simple landing page
* [ ] case study
* [ ] show to real people

---

## Milestone 2 — First Market Test

After Courses 3–4.

* [ ] identify 10 potential businesses/use cases
* [ ] show demo
* [ ] collect feedback
* [ ] ask about existing process
* [ ] identify willingness to pilot
* [ ] adjust product around genuine problems

Learning starts interacting with the market here.

Do NOT wait until Course 10.

---

## Milestone 3 — First Paid Pilot Target

After Courses 4–6.

Candidate offer:

### "I will turn your business documents/process into a small working AI prototype."

Focus:

* small scope
* limited risk
* real data
* measurable problem
* quick demonstration

---

## Milestone 4 — Agent Workflow Projects

After Course 7.

Sell outcomes such as:

* request handling
* document lookup
* report generation
* information routing
* controlled business actions

---

## Milestone 5 — Advanced AI Integration

After Courses 8–9.

Target:

* multi-agent workflows
* MCP
* internal tool integration
* advanced business systems
* larger freelance projects

---

## Milestone 6 — Flagship Proof

After Course 10.

Release:

# MNI Intelligence Desk v1

Then create:

* [ ] live demo
* [ ] case study
* [ ] architecture page
* [ ] demo video
* [ ] GitHub/project evidence
* [ ] LFDS offer
* [ ] MNI capability page
* [ ] freelance portfolio entry
* [ ] LinkedIn project
* [ ] IBM certificate

---

# 22. Weekly Learning-to-Earning Scorecard

At the end of every week answer:

### Learning

* [ ] What new capability did I understand?

### Building

* [ ] What actually works now that did not work last week?

### Transformation

* [ ] What did I change beyond the course implementation?

### Market

* [ ] What real business problem does it address?

### Proof

* [ ] Can another person see/test it?

### Content

* [ ] Did we create a recording, case study, or lesson asset?

### Commercialisation

* [ ] Could this capability be offered to someone today?

### Next Step

* [ ] What is the ONE highest-value thing to build next?

---

# 23. Things We Will NOT Do

* [ ] chase certificates without implementation
* [ ] memorise code unnecessarily
* [ ] build endless toy projects
* [ ] create agents for problems that do not need agents
* [ ] force AI where simple automation works
* [ ] become dependent on one LLM vendor
* [ ] blindly trust AI-generated code
* [ ] publish copied Coursera/IBM training material
* [ ] wait until the full certificate is complete before testing market interest
* [ ] confuse technical sophistication with customer value

---

# 24. What Success Looks Like

At the end of this learning path:

## Learning

We understand modern RAG and agentic systems.

## Technical

We can direct AI to build, test and improve them.

## Portfolio

We have multiple real working systems.

## Business

We can translate business problems into AI solutions.

## Freelance

We can apply for RAG, agent, automation and integration projects with proof.

## LFDS

We can discuss practical AI opportunities with local businesses.

## MNI

AI becomes a serious solution-provider capability.

## DeTLeng

The implementation journey becomes original educational material.

## Income

Learning begins producing:

**demos → conversations → pilots → projects → reusable products → revenue**

---

# 25. The Rule Above All Rules

> **Never ask only: "What did this lesson teach?"**

Always ask:

> **"What capability did this give us, what can we build with it, who has this problem, and how can we prove we can solve it?"**

---

# MASTER FORMULA

```text
LEARN
  ↓
IMPLEMENT
  ↓
TRANSFORM
  ↓
TEST
  ↓
PRODUCTIZE
  ↓
PROVE
  ↓
PUBLISH
  ↓
SHOW TO MARKET
  ↓
PILOT
  ↓
SELL
  ↓
IMPROVE
  ↓
REUSE
```

# FINAL TARGET

**The certificate must not remain education.**

It must become:

# CAPABILITY → PROOF → PRODUCT → CLIENT → INCOME

**Learning is the input.
Working solutions are the output.
Market value is the test.
Income is the validation.**
