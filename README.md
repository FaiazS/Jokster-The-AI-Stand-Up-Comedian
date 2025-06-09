# Jokster-The-AI-Stand-Up-Comedian

Ever wondered what would happen if GPT-4o became a stand-up comedian?  
Meet **Jokster** — an AI agent who turns cutting-edge language models into a laughter machine.

---
## 🎯 Project Overview

**Jokster** is a persona-driven AI agent built using the `openai-agents` library and `gpt-4o`.  
It performs hilarious stand-up comedy routines based on a variety of prompt topics related to AI and human workforce dynamics.

This project explores:

- 🧠 Agent abstraction using OpenAI's `Agent`, `Runner`, and `trace`
  
- 🔐 Secure API usage via `google.colab.userdata`
  
- ⚙️ Prompt engineering and persona modeling
  
- 🧾 Tracing agent behavior with [OpenAI Traces](https://platform.openai.com/traces)

 This is a fun, creative demonstration of building real-world agentic systems in AI — perfect for showcasing applied skills.
---

## 🧪 Sample Output

> **Prompt:** *"Perform a standup comedy about AI against human workforce!"*

AI walks into a job interview. The manager says, "Tell me your strengths."
AI replies, "I never sleep, never ask for a raise, and I don’t have lunch breaks."
The manager hires AI... and AI immediately replaces him.

Humans now have weekly therapy sessions just to hear someone say, "You still matter."
---

## 🚀 How It Works

1. ✅ **Create an agent** using the `Agent` class (e.g., Jokster).
   
2. 🧠 Provide **custom instructions** to give the agent a comedic personality.
   
3. 🔐 Securely load your OpenAI API key in Google Colab using `userdata`.
   
4. 🏃 Run prompts using `Runner.run()` and log traces with `trace()`.
   
5. 🎤 Display the final output of each performance.

---

## 🛠️ Technologies & Concepts

| Tool / Concept          | Usage                                  |
|-------------------------|----------------------------------------|
| `openai-agents`         | Agent abstraction (`Agent`, `Runner`)  |
| `gpt-4o`                | Language model powering Jokster        |
| `trace()`               | Observability for prompt execution     |
| `Google Colab`          | Notebook-based execution environment   |
| `os.environ`            | Secure API key injection               |
| Prompt Engineering      | Crafting inputs for persona behavior   |

---

## 🧰 Requirements

- Google Colab (or any Python 3.8+ environment)
- OpenAI API key with GPT-4o access

---

## 📦 Setup Instructions

1. Clone the repo or open in Google Colab.
2. Install the agentic tools:

   ```python
   !pip install openai-agents
