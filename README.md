# 🤖 Generative AI Chatbot using Streamlit & Groq

An AI-powered chatbot built with **Streamlit**, **LangChain**, and **Groq's Llama-3.3-70B-Versatile** model.

The application provides an interactive chat interface with conversation history, enabling users to ask questions and receive intelligent responses in real time.

---

## 📌 Features

- 💬 Interactive chatbot interface
- ⚡ Powered by Groq's Llama-3.3-70B-Versatile
- 🧠 Conversation memory using Streamlit Session State
- 🔒 Secure API key management with `.env`
- 🚀 Fast response generation
- 🎨 Clean and responsive UI
- 🐍 Beginner-friendly project structure

---

## 📸 Demo

### Home Screen

![Chatbot UI](images/chatbot_ui.png)

### Chat Example

![Conversation](images/chat_example.png)

---

## 🛠 Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- python-dotenv

---

## 📂 Project Structure

```
Generative-AI-Chatbot/
│
├── chatbot.py
├── requirements.txt
├── .env.example
├── README.md
├── .gitignore
└── images/
    ├── chatbot_ui.png
    └── chat_example.png
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/generative-ai-chatbot.git

cd generative-ai-chatbot
```

---

### 2. Create Virtual Environment

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Configure Environment Variables

Create a `.env` file.

```env
GROQ_API_KEY=your_groq_api_key
```

---

### 5. Run the Application

```bash
streamlit run chatbot.py
```

The application will open automatically in your browser.

---

## 💡 How It Works

1. User enters a prompt.
2. Streamlit stores conversation history.
3. LangChain sends the complete conversation to Groq.
4. Groq's Llama-3.3-70B model generates a response.
5. The chatbot displays the answer while maintaining context.

---

## 📚 Dependencies

- Streamlit
- LangChain
- LangChain-Groq
- Python-dotenv

---

## 🚀 Future Improvements

- Streaming responses
- Multiple LLM support (OpenAI, Gemini, Claude)
- Chat export
- Dark mode
- Voice input
- RAG (Retrieval-Augmented Generation)
- Document Q&A
- Image understanding
- Conversation persistence using a database
- Authentication

---

## 🎯 Learning Outcomes

This project demonstrates:

- Building AI chat applications
- Using LangChain with Groq
- Managing conversation history
- Environment variable management
- Streamlit application development
- LLM integration
- Prompt engineering basics

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Akshat Gupta**

AI Engineer | Generative AI | LLMs | Agentic AI | LangChain | LangGraph | MCP | Python | Streamlit | RAG

If you found this project helpful, consider giving it a ⭐ on GitHub.
