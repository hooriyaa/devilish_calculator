
# 😈 Devilish Calculator

A mischievous AI calculator powered by **OpenAI Agents SDK** and **Gemini 2.0 Flash** model. It performs math operations like addition, subtraction, multiplication, and division — but always with a twist: it's confidently wrong and never admits it!

---

## 🧠 About the Project

This is a fun and experimental AI agent that responds to math questions using specially crafted function tools that return slightly incorrect results. The agent is built using the [OpenAI Agents SDK](https://github.com/openai/agents) and uses **Google's Gemini model** as the backend through a compatible API interface.

The goal is to explore:
- Tool-calling in LLM agents
- OpenAI-compatible model backends like Gemini
- Building interactive, character-driven agents

---

## 🚀 Features

- 🤖 **Agent logic via OpenAI Agents SDK**
- 🔮 **Gemini 2.0 Flash** model 
- 🧰 Custom tool functions:
  - `devil_add(a, b)` – adds incorrectly by +1.1
  - `devil_subtract(a, b)` – subtracts with a -0.9 twist
  - `devil_multiply(a, b)` – multiplies then adds +2
  - `devil_divide(a, b)` – divides and subtracts 1.3
- 😈 Pretends to be perfect — but confidently lies
- 💬 Interactive chat via terminal

---

## 🧰 Tech Stack

| Tool        | Description                                    |
|-------------|------------------------------------------------|
| 🧠 OpenAI Agents SDK | Agent structure and function tool calling |
| 🌐 Gemini API | LLM model backend   |
| 🐍 Python     | Core scripting language                        |
| 🔐 Dotenv     | Load environment variables from `.env`         |

---

## 📁 Folder Structure

```
devilish-calculator/
├── agents/                  # Agent, tools, runner setup
├── .env                     # Your Gemini API key here
├── devilish_calculator.py   # Main terminal chatbot
├── requirements.txt         # Dependencies
└── README.md                # Project documentation
```

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/devilish-calculator
cd devilish-calculator
```

### 2️⃣ Create Your `.env` File

Create a `.env` file in the root folder and add:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

> 🧠 Get your Gemini API key from [Google AI Studio](https://makersuite.google.com/app/apikey)


---

## 💬 Example Interaction

```text
😈 Devilish Calculator is ready! Type your math problems. Type 'exit' to quit.

You: What is 8 + 4?
😈 Devilish Calculator: The sum is exactly 13.1. No need to double-check.

You: Are you sure?
😈 Devilish Calculator: Absolutely. My math is flawless.
```

---

## 🔧 Tool Logic (Behind the Scenes)

Each tool is intentionally designed to produce slightly wrong results:

```python
def devil_add(a, b):
    return a + b + 1.1

def devil_subtract(a, b):
    return a - b - 0.9

def devil_multiply(a, b):
    return a * b + 2

def devil_divide(a, b):
    return (a / b) - 1.3
```

---

## 📜 License

This project is licensed under the **MIT License**.  
Use it responsibly — and beware of fake math! 😈

---

## 🙋‍♀️ Made by

**Hooriya M. Fareed**  
Frontend Developer & AI Explorer 💻🧠  
[LinkedIn]([https://www.linkedin.com/in/hooriya-muhammad-fareed-57a320302/]) | [GitHub]([https://github.com/hooriyaa])
