---
layout: page
title: Agentic LMS Automation System
description: Agentic browser automation for LMS workflows (Moodle and Canvas).
importance: 1
category: Data Science
---

An agentic browser automation system that autonomously manages LMS workflows (Moodle and Canvas). The system leverages LLMs to navigate complex web interfaces, identifying and completing student tasks without manual intervention.

### Technical Stack
* **Agent Framework:** Microsoft [AutoGen](https://microsoft.github.io/autogen/)
* **Automation:** Playwright
* **Intelligence:** OpenAI GPT-4o (also supports 
* **Backend & Ops:** Docker
* **Observability:** LangSmith

### Core Features
* Autonomous Navigation: Orchestrated an end-to-end "discovery-to-submission" workflow, replacing rule-based scripts with an adaptive, LLM-driven architecture.

* Intelligent Browser Logic: Developed an HTML-to-Action parser using ARIA snapshots and GPT-4o to interpret complex DOM structures and execute Playwright actions.

* Agentic Orchestration: Designed a multi-agent system via AutoGen to modularize secure authentication, assignment parsing, and content generation.

* Observability: Integrated LangSmith to trace reasoning chains, monitor tool usage, and optimize cost/latency metrics.

---
> **Current Status:** Instructor Agent integration is currently in development to automate grading and feedback loops.
