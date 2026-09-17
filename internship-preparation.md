# Internship Preparation & Skills Development Plan

## 1. Internship Opportunity

We are looking for an intern who is interested in **AI, LLMs, RAG, automation and intelligent workflows**.

The core expectation is that you develop a good foundation in programming and AI technologies, particularly:

- Basic **LLM concepts and applications**
- **RAG (Retrieval-Augmented Generation)**
- **Agentic AI / agentic workflows**
- Python/programming fundamentals
- Building simple AI-powered solutions and workflows

In addition, exposure to the following technologies will be valuable:

1. **Cypress** – automation and end-to-end testing
2. **ESTATE** – understand the tool/platform used in the target environment, its purpose and typical use cases
3. **Automation tools** – understand basic workflow/process automation
4. **C#** – basic programming and ability to understand/read simple C# code
5. **SAP Plant Maintenance (PM)** – basic understanding of SAP and how the PM module is used in real business/industrial environments

You are **not expected to become an expert in all of these areas** before the internship.

The objective is to demonstrate that you understand the fundamentals, can learn quickly, and can explain **why a particular technology is used and where it fits into a real-world solution**.

---

# 2. Recommended Learning Approach

Don't approach this as a list of technologies to memorise.

For every technology, try to answer these six questions:

### 1. What is it?
Explain the technology in simple terms.

### 2. Why is it used?
What problem does it solve?

### 3. Where is it used?
Give one or two practical examples.

### 4. How does it work?
Understand the basic architecture/workflow.

### 5. Why this technology instead of another?
Understand the main alternatives and trade-offs.

### 6. Can I demonstrate it?
Be able to describe or build a very small practical example.

This approach will help considerably in an interview.

---

# 3. Core Skill Area – Programming

## Python

Python should be your primary programming language for the AI/LLM portion.

Focus on:

- Variables and data types
- Lists, dictionaries, tuples and sets
- Conditions and loops
- Functions
- Classes and objects
- Exception handling
- Reading/writing files
- JSON
- REST APIs
- HTTP requests
- Working with libraries/packages
- Virtual environments
- Basic Git/GitHub
- Basic debugging

### Practical target

You should be able to write a small Python program that:

**takes input → processes it → calls an API → receives JSON → extracts information → produces an output.**

This is much more valuable than simply completing programming exercises.

---

# 4. LLM Fundamentals

Learn the basic concepts behind Large Language Models.

You should understand:

- What is an LLM?
- What is a token?
- What is a prompt?
- What is a context window?
- What is an embedding?
- What is inference?
- What is hallucination?
- What is temperature?
- What is structured output?
- What is function/tool calling?
- What is an LLM API?
- Difference between an LLM and a traditional software application

### Interview-level explanation

You should be able to explain something like:

> An LLM is a model trained on large amounts of data that can understand and generate language. In an application, we normally don't use the model alone; we combine it with prompts, application logic, data sources and sometimes external tools to solve a specific business problem.

---

# 5. RAG – Retrieval-Augmented Generation

RAG is particularly important for this internship.

Understand the complete flow:

**Documents → Chunking → Embeddings → Vector Database → Retrieval → Relevant Context → LLM → Answer**

Learn:

- Why RAG is required
- What embeddings are
- What a vector database is
- Document chunking
- Similarity search
- Retrieval
- Context injection
- RAG vs normal prompting
- RAG vs fine-tuning
- Basic RAG evaluation
- Problems such as poor retrieval and hallucination

### Practical example

Imagine a company has thousands of maintenance manuals.

Instead of asking an LLM:

> "What is the procedure for replacing this component?"

you build a RAG system that searches the company's approved manuals and provides the relevant sections to the LLM.

The LLM then generates an answer based on those retrieved documents.

### You should be able to answer:

**Why not simply put all the documents into the prompt?**

Because there may be too much information, context windows have limits, retrieval makes the process more scalable, and relevant information can be selected dynamically.

**Why RAG instead of fine-tuning?**

RAG is generally better suited when the goal is to give the model access to changing or private knowledge without retraining the model itself.

---

# 6. Agentic AI / Agentic Workflows

Understand the difference between a normal LLM application and an agentic workflow.

### Basic LLM application

**User → Prompt → LLM → Answer**

### Agentic workflow

**User → Agent → Reason/Plan → Select Tool → Execute → Observe Result → Continue → Final Answer**

Learn:

- What is an AI agent?
- What is a tool?
- Tool/function calling
- Planning
- Memory
- State
- Multi-step workflows
- Human-in-the-loop
- Agent orchestration
- When agents are useful
- When agents are unnecessary

### Important interview point

Do not say:

> "Agents are better because they are autonomous."

Instead explain the trade-off.

For a simple deterministic process, a normal automation/workflow may be better.

An agent becomes useful when the system needs to make decisions dynamically, select tools, interpret results and determine the next action.

---

# 7. Cypress – Automation Testing

You don't need to become a Cypress expert.

Understand:

### What is Cypress?

Cypress is a tool used primarily for **automated testing of web applications**, particularly end-to-end and component testing.

### Why is it used?

Instead of manually testing a website every time a new version is released, automated tests can reproduce user actions and verify expected behaviour.

For example:

**Open application → Login → Navigate to page → Enter information → Click Submit → Verify result**

### Understand these concepts

- Test cases
- Test suites
- Assertions
- Selectors
- Browser automation
- End-to-end testing
- Component testing
- Test execution
- Screenshots/logs
- CI/CD integration

### Be prepared for:

**Why Cypress rather than manual testing?**

Automation provides repeatability, speed and regression coverage.

**Why not use another automation framework?**

You should understand at a high level that alternatives such as Selenium, Playwright and others exist, with differences in browser support, architecture, language ecosystem, features and developer experience.

You don't need to memorise every difference.

### Small practical exercise

Create a simple test that:

1. Opens a website
2. Logs in
3. Navigates to a page
4. Performs an action
5. Verifies the expected result

---

# 8. Basic Automation

Understand the concept before learning a particular automation product.

Automation means taking a process that is repeatedly performed by a person and allowing software to perform some or all of it automatically.

### Example

Manual:

**Receive email → Download attachment → Read information → Enter information into system → Send confirmation**

Automated:

**Email arrives → Workflow detects email → Extracts information → Updates system → Sends confirmation**

Understand:

- Trigger
- Action
- Condition
- Workflow
- API
- Data transformation
- Error handling
- Logging
- Notifications
- Human approval

Also understand the difference between:

### RPA

Automates interaction with applications, often mimicking human actions.

### API-based automation

Uses APIs to communicate directly between systems.

### Workflow automation

Connects multiple applications/services into a business process.

### Important interview question

**Why use an API instead of UI automation?**

If a reliable API is available, API-based automation is usually more robust than automating clicks and screen elements.

---

# 9. C# Fundamentals

You don't need advanced C# initially.

Focus on being able to **read and understand simple C# programs** and write basic programs.

Learn:

- Variables
- Data types
- Conditions
- Loops
- Methods
- Classes
- Objects
- Interfaces – basic concept
- Exception handling
- Collections
- LINQ – basic awareness
- JSON
- REST APIs
- .NET basics

### Practical target

You should be able to understand something like:

**C# application → calls REST API → receives JSON → processes data → returns result**

Also understand at a high level why C#/.NET is widely used for enterprise applications.

---

# 10. SAP Basics – Plant Maintenance (PM)

This is where you should focus more on **business understanding** than programming.

First understand:

### What is SAP?

SAP is an enterprise software platform used by organisations to manage business processes and data.

Then understand the concept of **SAP modules**.

Different modules support different business functions.

For example:

- Finance
- Materials Management
- Sales
- Production
- Plant Maintenance
- Human Resources

---

# 11. SAP Plant Maintenance – Why It Exists

SAP PM is used to manage **maintenance activities for physical assets/equipment**.

Think about a factory containing:

- Pumps
- Motors
- Compressors
- Conveyors
- Electrical equipment
- Production machinery

These assets need:

- Preventive maintenance
- Corrective maintenance
- Inspections
- Repairs
- Spare parts
- Maintenance planning
- Maintenance history

SAP PM helps organisations manage these processes systematically.

### Basic maintenance scenario

A pump fails.

The process could be:

**Equipment failure → Maintenance notification → Maintenance order → Technician assigned → Spare parts required → Repair performed → Work recorded → Order completed → Maintenance history updated**

Understand this flow.

---

# 12. SAP PM Concepts to Learn

At a basic level, understand:

- Equipment
- Functional Location
- Maintenance Notification
- Maintenance Order
- Preventive Maintenance
- Corrective Maintenance
- Work Centre
- Maintenance Plan
- Maintenance Task List
- Spare parts/materials
- Maintenance history

You should be able to explain the difference between an **Equipment** and a **Functional Location** at a basic level.

You should also understand why maintenance history is valuable.

For example:

> If a particular pump repeatedly fails, historical maintenance data can help identify recurring problems, maintenance cost and potential replacement requirements.

---

# 13. Connecting SAP + Automation + AI

This is where you can differentiate yourself in the interview.

Don't learn each technology as an isolated topic.

Think about how they can work together.

For example:

### Scenario

A technician reports:

> "Pump P-102 is vibrating and making unusual noise."

A future intelligent system could:

1. Receive the maintenance description
2. Use an LLM to understand the issue
3. Retrieve relevant maintenance manuals using RAG
4. Search historical maintenance records
5. Identify similar previous failures
6. Suggest possible causes
7. Create or assist with an SAP maintenance notification
8. Recommend next actions
9. Ask for human approval before creating an order

This combines:

**LLM + RAG + Agentic workflow + Automation + SAP**

That is the kind of thinking I would like you to develop.

---

# 14. Suggested Mini-Projects

Rather than only watching courses, build small projects.

## Project 1 – LLM Application

Build a simple Python application that:

**User question → LLM API → Answer**

---

## Project 2 – RAG Application

Create a small knowledge base from several documents.

Build:

**Documents → Embeddings → Retrieval → LLM → Answer**

The system should answer questions based on the documents.

---

## Project 3 – Agentic Workflow

Build a simple agent that can use two or three tools.

For example:

**User asks a question → Agent decides which tool to use → Tool executes → Agent interprets result → Final response**

---

## Project 4 – Cypress

Create a basic automated test for a web application.

---

## Project 5 – Automation

Create a simple workflow such as:

**Email/file/input → Extract information → Process → Store → Notification**

---

## Project 6 – SAP PM Conceptual Exercise

You don't necessarily need an SAP system.

Take a hypothetical factory and define:

- 5 pieces of equipment
- Functional locations
- Example maintenance notifications
- Maintenance orders
- Preventive maintenance scenarios
- Spare parts
- Maintenance history

Then explain how SAP PM would manage them.

---

# 15. How to Prepare for the Interview

For each technology, prepare a **2-minute explanation**.

Use this structure:

### "What is it?"

One simple definition.

### "Why do we need it?"

Explain the problem it solves.

### "How does it work?"

Explain the basic workflow.

### "Where would I use it?"

Give one practical example.

### "What are the alternatives?"

Mention one or two alternatives.

### "Why would I choose this?"

Explain the trade-off.

---

# 16. Example Interview Answer

If asked:

**"What is RAG and why would you use it?"**

A good answer would be:

> "RAG stands for Retrieval-Augmented Generation. It combines an LLM with an external knowledge source. Instead of expecting the model to know everything, we first retrieve relevant information from documents or a knowledge base and provide that information as context to the model. This is useful for company-specific or frequently changing information. For example, we could use RAG to allow an AI assistant to answer questions from maintenance manuals and procedures. I would consider RAG rather than fine-tuning when I mainly need to provide the model with access to external or changing knowledge."

That demonstrates **understanding**, rather than simply memorising a definition.

---

# 17. Priority Order

Don't spend equal time on every technology.

### Priority 1 – Become strong

- Python
- LLM fundamentals
- RAG
- Agentic workflows
- APIs
- Git/GitHub
- Basic software engineering

### Priority 2 – Become comfortable

- C#
- Automation concepts
- Cypress

### Priority 3 – Understand the business/domain

- SAP fundamentals
- SAP Plant Maintenance
- Maintenance processes
- Equipment/asset management

The goal is to become **strong in AI/programming and conversationally competent in the supporting enterprise technologies**.

---

# 18. Final Preparation Goal

By the time you interview, you should be able to confidently explain a solution such as:

> "I can build a Python-based application using an LLM API. If the application needs access to company-specific documents, I can use RAG to retrieve relevant information before generating the response. If the application needs to perform actions across systems, I can introduce an agentic workflow with tools and APIs. For UI testing I understand where Cypress fits, and I have basic C# knowledge. I also understand how SAP PM manages equipment, maintenance notifications and maintenance orders, and I can see how AI and automation could be used to improve maintenance processes."

That level of understanding would demonstrate **good internship readiness**, even without being an expert in every individual technology.