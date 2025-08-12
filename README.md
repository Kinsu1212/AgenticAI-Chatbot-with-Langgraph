# Agentic AI Chatbot with LangGraph

A conversational AI chatbot built using **LangGraph**, **LangChain**, and **Groq API**, designed to demonstrate stateful conversation flows with human feedback integration.

## 🚀 Features
- **LangGraph State Management** – Keeps track of messages and updates conversation state dynamically.
- **Multi-turn Conversations** – Maintains chat history for contextual responses.
- **Groq API Integration** – Leverages high-speed LLM inference.
- **Environment-based API Keys** – Secure API key storage using `.env`.
- **Extensible Structure** – Easy to add new tools, nodes, and API integrations.

## 📂 Project Structure
```
AgenticAI/
│── 1-BasicChatbot/                # Jupyter notebook for chatbot demo
│── main.py                        # Python entry script
│── requirements.txt               # Python dependencies
│── pyproject.toml                  # Project metadata
│── README.md                      # Project documentation
│── .gitignore                     # Ignored files (e.g., venv, .env)
│── .venv/                         # Virtual environment (ignored in Git)
```

## 🛠️ Tech Stack
- **Python 3.9+**
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [LangChain](https://github.com/hwchase17/langchain)
- [Groq API](https://groq.com)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Kinsu1212/AgenticAI-Chatbot-with-Langgraph.git
cd AgenticAI-Chatbot-with-Langgraph
```

### 2️⃣ Create a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set up your `.env` file
Create a `.env` file in the root directory:
```env
GROQ_API_KEY=your_groq_api_key_here
WAVILY_API_KEY=your_wavily_api_key_here
```

## ▶️ Usage

**Run via Notebook**
- Open `1-basicchatbot + human feedback.ipynb` in Jupyter or VS Code and execute cells in order.

**Run via Python**
```bash
python main.py
```

## 🔮 Next Steps
- Add more tools and actions for richer conversations.
- Integrate external APIs for task automation.
- Enhance UI for web-based deployment.

## 📜 License
This project is licensed under the MIT License.

---

**Author:** Dhvanil Sanjay Shah  
**GitHub:** [Kinsu1212](https://github.com/Kinsu1212)  
