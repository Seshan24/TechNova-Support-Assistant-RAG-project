# 🤖 TechNova Support Assistant

An AI-powered customer support chatbot built using **LangChain**, **OpenAI GPT-4.1 Nano**, **Chroma Vector Database**, and **Gradio**. The chatbot answers questions about TechNova products and policies using a Retrieval-Augmented Generation (RAG) approach.

---

## 🚀 Features

- 📚 Loads Markdown files from a knowledge base
- ✂️ Splits documents into chunks for efficient retrieval
- 🔎 Generates embeddings using Sentence Transformers
- 🗄️ Stores vectors in Chroma DB
- 🤖 Answers questions using OpenAI GPT models
- 💬 Interactive chat interface built with Gradio
- 🎯 Supports category-based document filtering

---

## 🛠️ Tech Stack

- Python
- LangChain
- OpenAI GPT-4.1 Nano
- Chroma Vector Database
- HuggingFace Embeddings - odel_name="all-MiniLM-L6-v2"
- Gradio
- Sentence Transformers

---

## 📂 Project Structure

```text
project/
│
├── knowledge-base/
│   ├── products/
│   ├── policies/
│   └── support/
│
├── vector_db/
├── app.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/technova-support-assistant.git
cd technova-support-assistant
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_api_key
```

---

## 📚 Prepare Knowledge Base

Store your Markdown files inside the `knowledge-base` directory.

Example:

```text
knowledge-base/
├── products/
│   ├── nova_phone_x1.md
│   └── nova_laptop_pro.md
├── policies/
│   ├── return_policy.md
│   └── warranty_policy.md
```

---

## 🔄 How It Works

1. Load Markdown documents
2. Split documents into chunks
3. Generate embeddings using HuggingFace
4. Store embeddings in Chroma DB
5. Retrieve relevant information
6. Send context to GPT-4.1 Nano
7. Return an accurate response through Gradio

---

## 💬 Example Questions

- What is the return policy?
- What are the specifications of Nova Phone X1?
- Does TechNova provide warranty support?
- How can I contact customer support?


---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Seshan Rodrigo**

- LinkedIn: https://www.linkedin.com/in/your-profile
- GitHub: https://github.com/yourusername
