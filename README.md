# Agentic AI Project

## Project Description

This project demonstrates a simple Agentic AI system built using Python,
Google Colab, and the Groq API.

The agent can understand a user's request, decide which action is required,
use an appropriate tool, observe the result, and provide a final answer.

## Objective

- Understand the basic concept of Agentic AI.
- Connect an AI model using the Groq API.
- Create and use tools with an AI agent.
- Implement the THINK, ACT, OBSERVE and REPEAT process.
- Build an agent capable of selecting between different tools.
- Test the agent using different tasks.

## Technologies Used

- Python
- Google Colab
- Groq API
- Groq Python SDK

## Tools Implemented

### 1. Calculator Tool

The Calculator Tool performs mathematical calculations based on the
expression provided by the user.

### 2. Word Counter Tool

The Word Counter Tool counts the number of words present in a given text.

## Agent Workflow

The agent follows the basic Agentic AI loop:

**THINK → ACT → OBSERVE → REPEAT → FINAL ANSWER**

1. **THINK** – The agent understands the user's request.
2. **ACT** – The agent selects and uses the required tool.
3. **OBSERVE** – The agent examines the result returned by the tool.
4. **REPEAT** – The agent performs another action if required.
5. **FINAL ANSWER** – The agent provides the completed response.

## Testing

The agent was tested using:

- Mathematical calculations.
- Word counting.
- A combined task requiring both tools.

## Security

The Groq API key is not hardcoded in the source code.

The API key is stored securely using Google Colab Secrets with the secret
name:

`GROQ_API_KEY`

## Conclusion

This project demonstrates the basic working of an Agentic AI system.
The agent can select appropriate tools, process their results, and complete
tasks through an iterative agent loop.
