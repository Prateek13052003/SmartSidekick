# Sidekick AI
## Agentic AI

### Autonomous AI Task Execution Agent

Sidekick AI is an autonomous AI agent capable of planning, executing, evaluating, and completing complex tasks with minimal human intervention. The system integrates Large Language Models, web search, browser automation, and external tools to solve multi-step problems efficiently.

---

## Overview

The project is designed to function as an AI co-worker that can independently perform research, gather information, interact with websites, execute code, and generate structured outputs. Unlike conventional chatbots, Sidekick AI continuously evaluates its progress and can refine its responses until predefined objectives are satisfied.

---

## Key Features

### Autonomous Task Execution

* Accepts user-defined objectives
* Breaks complex problems into manageable steps
* Executes tasks independently
* Produces structured outputs

### Self-Evaluation Framework

* Evaluates generated responses against success criteria
* Detects incomplete or insufficient answers
* Iteratively improves responses
* Stops only when objectives are satisfied

### Web Search Integration

* Performs real-time internet searches
* Retrieves relevant information from online sources
* Supports dynamic information gathering

### Browser Automation

* Automates website interactions using Playwright
* Opens and navigates webpages
* Extracts information from websites
* Simulates user browsing actions

### Python Execution

* Performs calculations and data processing
* Executes Python code dynamically
* Supports analytical workflows

### Knowledge Retrieval

* Integrates Wikipedia for factual information retrieval
* Combines multiple information sources for comprehensive answers

---

## System Architecture

```text
User Interface
      │
      ▼
Sidekick Agent
      │
 ┌────┼────┐
 │    │    │
 ▼    ▼    ▼
Planning
Reasoning
Evaluation
      │
      ▼
Tool Layer
      │
 ├── Web Search
 ├── Browser Automation
 ├── Wikipedia
 ├── Python Execution
 └── File Operations
      │
      ▼
Final Response
```

---

## Workflow

1. User submits a task.
2. The agent analyzes objectives and requirements.
3. Appropriate tools are selected.
4. Information is gathered and processed.
5. The response is evaluated against success criteria.
6. Additional iterations are performed if necessary.
7. The final validated output is returned.

---

## Technology Stack

| Component            | Technology |
| -------------------- | ---------- |
| Programming Language | Python     |
| Agent Framework      | LangGraph  |
| Language Model       | OpenAI GPT |
| User Interface       | Gradio     |
| Browser Automation   | Playwright |
| Search Engine        | Serper API |
| Knowledge Source     | Wikipedia  |

---

## Project Structure

```text
.
├── app.py
├── sidekick.py
├── sidekick_tools.py
├── gradio_test.py
├── requirements.txt
└── README.md
```

---

## Installation

```bash
git clone <repository-url>

cd sidekick-ai

pip install -r requirements.txt
```

---

## Running the Project

```bash
python app.py
```

---

## Applications

* Research Assistance
* Information Retrieval
* Competitive Analysis
* Web Automation
* Report Generation
* Productivity Workflows

---

## Future Enhancements

* Multi-Agent Collaboration
* Long-Term Memory
* Retrieval-Augmented Generation (RAG)
* Cloud Deployment
* Multimodal Capabilities
