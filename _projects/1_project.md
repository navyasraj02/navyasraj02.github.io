---
layout: page
title: Agentic LMS Automation System
description: Agentic browser automation for LMS workflows (Moodle and Canvas).
importance: 1
category: Data Science
---

An agentic browser automation system that autonomously manages LMS workflows (Moodle and Canvas). The system leverages LLMs to navigate complex web interfaces, identifying and completing student tasks without manual intervention.

### ⚙️ Technical Stack
* **Agent Framework:** Microsoft [AutoGen](https://microsoft.github.io/autogen/)
* **Automation:** Playwright
* **Intelligence:** OpenAI GPT-4o
* **Backend & Ops:** Docker
* **Observability:** LangSmith

### 🚀 Key Contributions
* **Autonomous Navigation:** Transitioned from fragile, rule-based scripts to a fully autonomous, LLM-driven architecture capable of dynamic "discovery-to-submission" workflows.
* **Student Agent Workflow:** Developed a core agent capable of secure login, assignment identification, and content submission.
* **HTML-to-Action Logic:** Implemented decision-making logic that allows agents to parse complex HTML and execute precise browser tools.

---
> **Current Status:** Instructor Agent integration is currently in development to automate grading and feedback loops.
