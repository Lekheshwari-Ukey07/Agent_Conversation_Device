
## Google Drive Link :
https://drive.google.com/drive/folders/1UefBwJXkW9tlW0L-9ClJipqgbMOScyDC?usp=sharing


## 🎥 Project Demo Video

https://drive.google.com/file/d/1X9M_hxjtV2Ea_vSwSEsiWgvoVjceiVI0/view?usp=sharing

# Conversation Agent 🚀

A **powerful AI-powered conversational agent** that integrates multiple tools to provide intelligent, context-aware responses. This project demonstrates hands-on experience with **LangChain, OpenAI APIs, and agentic AI systems**, making it a showcase of practical AI engineering skills.

---

## 🌟 Key Features

- **Multi-Tool Integration:** Seamlessly interacts with various tools:
  - Document Retrieval (knowledge-based Q&A)
  - Real-Time News Updates
  - Weather Information (via OpenMeteo API)
  - Python Code Execution (on-the-fly evaluation)
- **Context-Aware Conversations:** Maintains chat history to provide meaningful, relevant responses.
- **Agentic AI System:** Uses LangChain’s function-calling agents to intelligently decide which tool to use based on the query.
- **Extensible Architecture:** Easily add new tools and functionalities.

---

## 🛠️ Tech Stack

- **Python** – Core programming language
- **LangChain** – Agent creation, prompt management, and tool integration
- **OpenAI GPT-3.5-turbo** – Conversational LLM
- **Custom Tools:** Python REPL, news fetcher, weather tool, document retrieval
- **Environment Management:** Configurable via `.env` or `app.config`

---

## ⚙️ How It Works

1. **LLM Agent Setup:**  
   A GPT-3.5-turbo LLM is initialized with a system prompt and integrated tools.

2. **Tool Integration:**  
   Queries are intelligently routed to the appropriate tool:
   - If the query is about weather → `openmeteo_weather_tool`  
   - If the query requires code execution → `python_repl_tool`  
   - If the query requires news → `news_tool`  
   - For knowledge retrieval → `retrieval_tool`

3. **Execution & Response:**  
   The agent processes the input, interacts with the tools as needed, and returns a coherent response to the user.
🚀 Usage


### Example Queries:

"Show me the latest news about AI"

"What's the weather in Mumbai?"

"Write a Python function to reverse a string"

"Explain agentic AI in simple terms"

 ## Highlights & Skills Demonstrated

Practical agentic AI implementation with multi-tool orchestration

LLM integration for real-world applications

Hands-on experience with LangChain, Python REPL, APIs, and retrieval systems

Clean, modular code architecture with extensibility for future tools


## 📌 Connect With Me

Linkedin : https://www.linkedin.com/in/lekheshwari-ukey-data-scientist/
