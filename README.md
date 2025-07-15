🤖 AI Agents: Building Practical LLM-Powered Tools
This repository contains hands-on examples and mini-projects that demonstrate how to build AI agents using LLMs (like OpenAI's GPT) and frameworks such as LangChain and LangGraph. These agents can perform real-world tasks like analyzing a codebase, reading files, calling tools, and even generating README files automatically.

🚀 What You'll Learn
How to design LLM-powered agents that use memory, context, and tools.

How to use LangChain and LangGraph to structure and manage agent behavior.

How to build agents that:

Analyze GitHub repositories

Read code and documentation

Generate structured output (like README.md)

🧰 Tech Stack
Python

OpenAI GPT models

LangChain

LangGraph

Custom Tool definitions (for reading files, analyzing repos, etc.)

📂 Folder Structure
bash
Copy
Edit
ai-agents/
│
├── langgraph/         # LangGraph-based agent examples
├── potpie-readme/     # Agent that reads repo files and generates README
├── tool_usage/        # Tool-calling examples with LLMs
├── utils/             # Utility functions for agents
└── README.md          # This file
✅ How to Use
Clone the repo:

bash
Copy
Edit
git clone https://github.com/codebasics/ai-agents.git
cd ai-agents
Set up a Python environment and install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Add your OpenAI API key:

bash
Copy
Edit
export OPENAI_API_KEY=your_key_here
Run an example:

bash
Copy
Edit
python langgraph/main.py
💡 Inspiration
This project was inspired by the growing need to build intelligent agents that can assist developers and teams by automating menial tasks like documentation, code analysis, and information extraction. With the power of LLMs, we're now able to prototype useful tools faster than ever.

📌 Credits
Created by codebasics — check out the YouTube video for a full walkthrough.
