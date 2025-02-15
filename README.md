
🤖 AI-Agent-Chatbot  
🚀 An AI chatbot that supports multiple LLMs (**Groq, OpenAI**) with real-time interaction using **LangGraph** and **Streamlit**. It also features **web search integration** for enhanced responses.

## 📌 Features
- 🧠 Supports **Groq** (`Llama3`, `Mixtral`) and **OpenAI** (`GPT-4o-mini`)
- 🌐 **Optional Web Search** (Tavily API) for better responses
- ⚡ **Streamlit UI** for a smooth user experience
- 🔗 **FastAPI Backend** for handling AI agent interactions
- 🔒 Uses **.env** for API key security

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repo  
```sh
git clone https://github.com/your-username/AI-Agent-Chatbot.git
cd AI-Agent-Chatbot
```

### 2️⃣ Create a Virtual Environment  
```sh
python -m venv venv
source venv/bin/activate  # For MacOS/Linux
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables  
Create a `.env` file in the root directory and add:  
```
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
OPENAI_API_KEY=your_openai_api_key
```

### 5️⃣ Start the Backend (FastAPI)
```sh
uvicorn backend:app --host 127.0.0.1 --port 8000 --reload
```

### 6️⃣ Run the Frontend (Streamlit)
```sh
streamlit run frontend.py
```

---

## 🔥 Usage
1. Open `http://127.0.0.1:8501/` in your browser.
2. Enter a **system prompt** to define the chatbot’s behavior.
3. Choose **Groq** or **OpenAI** as the LLM provider.
4. Enable **Web Search** if required.
5. Ask your question and get an instant AI response!

---

## 📜 Technologies Used
- **Backend:** FastAPI, LangChain, LangGraph
- **Frontend:** Streamlit
- **LLMs:** Groq, OpenAI
- **Web Search:** Tavily API

---

## 🎯 Future Enhancements
- [ ] Add more LLM providers (Anthropic, Mistral, etc.)
- [ ] Implement memory for multi-turn conversations
- [ ] Deploy on cloud (Render, Hugging Face Spaces, etc.)

---

## 🛠️ Contribution Guidelines

🚨 **Direct push to `main` is restricted!** 🚨  
To contribute, follow these steps:

1. **Fork** the repository.
2. Create a **new branch** (`feature-branch`) in your fork.
3. Make changes and **commit** them.
4. Open a **Pull Request (PR)** to merge your branch into `main`.
5. Wait for review and approval before merging.

✔️ PRs without approvals **will not be merged**.  


---
