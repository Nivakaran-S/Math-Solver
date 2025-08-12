# 🧮 Text to Math Problem Solver & Data Search Assistant

An intelligent AI-powered assistant that interprets natural language math and reasoning problems, performs complex calculations, and fetches relevant factual information from Wikipedia — all in one conversational interface.

Built with **Groq’s Gemma2-9b-It model** and **LangChain**, this project demonstrates my expertise in:

- **Natural Language Understanding**: Parsing and converting everyday language into mathematical expressions.
- **Hybrid Tool Integration**: Seamlessly combining a calculator, reasoning chain, and web search in a single AI agent.
- **Conversational UI Design**: Streamlit-based interactive chat that retains context for smooth multi-turn conversations.
- **Advanced Prompt Engineering**: Tailored prompts that enable detailed, stepwise, and logically structured explanations.

---

## 🚀 Project Highlights

- **Multifunctional AI Agent**: Combines math problem-solving, logical reasoning, and factual lookup.
- **Stepwise Explanations**: Answers include detailed, pointwise reasoning to enhance understanding.
- **LangChain Agent Framework**: Utilizes Zero-Shot ReAct agent for dynamic tool selection based on the question.
- **Real-time Streaming**: User-friendly responses delivered with progress feedback in Streamlit.
- **Robust Error Handling**: Gracefully manages parsing errors to improve user experience.

---

## 🛠️ Tech Stack & Skills

| Aspect            | Technologies & Concepts                                  |
|-------------------|---------------------------------------------------------|
| **AI/LLM**        | Groq LLM (Gemma2-9b-It), LangChain Chains & Agents     |
| **Mathematics**   | LLMMathChain for symbolic math and arithmetic reasoning |
| **Data Retrieval**| WikipediaAPIWrapper for real-time knowledge integration |
| **Frontend**      | Streamlit for interactive chat UI                        |
| **Agent Logic**   | Zero-shot ReAct agent for tool orchestration             |

---

## 📦 Installation & Setup

```bash
git clone https://github.com/yourusername/math-solver-assistant.git
cd math-solver-assistant
pip install -r requirements.txt
```
1. Obtain a Groq API Key at Groq Console.
2. Set your API key in a .env file or directly input in the Streamlit sidebar.
3. Launch the app with:
```bash

streamlit run app.py

```

## 🎯 Usage
- Enter natural language math or reasoning questions (e.g., "How many fruits do I have if...").
- The assistant interprets, calculates, and provides detailed stepwise answers.
- Also fetches relevant background information from Wikipedia if needed.
- Clear chat history anytime and explore a variety of question types.

💡 This project is a core part of my AI portfolio, illustrating real-world problem-solving capabilities using state-of-the-art language models and tools.