# Agentic AI Project

## Overview

This project demonstrates a basic Agentic AI system that connects a Large Language Model (LLM) with external tools.

The agent can understand a user's request, select an appropriate tool, observe the result, and continue the process when additional work is required.

The project follows the Agentic AI workflow:

**THINK → ACT → OBSERVE → REPEAT → FINAL**

## Objectives

- Understand the basic concept of Agentic AI.
- Connect an LLM with external tools.
- Implement safe tool execution.
- Validate tool arguments before execution.
- Handle multiple tasks in a single request.
- Implement error handling.
- Add automated tests.

## Architecture

```text
User Request
     |
     v
Groq LLM Agent
    THINK
     |
     v
Tool Selection
   /       \
  v         v
Calculator  Word Counter
   \       /
     v
   OBSERVE
     |
     v
REPEAT / FINAL
     |
     v
Final Answer
