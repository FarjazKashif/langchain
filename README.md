# 🚀 **LangChain Crash Course**

Welcome to the **LangChain Crash Course** repository! This repo contains all the code examples you'll need to follow along with the **LangChain Master Class for Beginners**. By the end of this course, you'll be able to:

✅ Build your own **AI agents**  
✅ Create **RAG chatbots**  
✅ Automate tasks using **AI**  

---

## 📌 **Course Outline**

1. **Setup Environment**
2. **Chat Models**
3. **Prompt Templates**
4. **Chains**
5. **RAG (Retrieval-Augmented Generation)**
6. **Agents & Tools**

---

## 🚀 **Getting Started**

### **🔹 Prerequisites**

Ensure you have the following installed:

- **Python 3.10 or 3.11**
- **Poetry** (Follow the [Poetry installation tutorial](https://python-poetry.org/docs/#installation))

### **🔹 Installation**

1️⃣ Clone the repository:

```sh
git clone https://github.com/bhancockio/langchain-crash-course
cd langchain-crash-course
```

2️⃣ Install dependencies using Poetry:

```sh
poetry install --no-root
```

3️⃣ Set up your environment variables:

```sh
mv .env.example .env
```

4️⃣ Activate the Poetry shell:

```sh
poetry shell
```

5️⃣ Run the example scripts:

```sh
python 1_chat_models/1_chat_model_basic.py
```

---

## 📂 **Repository Structure**

### 🔹 **1. Chat Models**  
📌 Learn to interact with **ChatGPT, Claude, and Gemini**.

```sh
1_chat_model_basic.py
2_chat_model_basic_conversation.py
3_chat_model_alternatives.py
4_chat_model_conversation_with_user.py
5_chat_model_save_message_history_firestore.py
```

### 🔹 **2. Prompt Templates**  
📌 Understand **prompt engineering** and optimize model responses.

```sh
1_prompt_template_basic.py
2_prompt_template_with_chat_model.py
```

### 🔹 **3. Chains**  
📌 Automate tasks by chaining **Chat Models & Prompts**.

```sh
1_chains_basics.py
2_chains_under_the_hood.py
3_chains_extended.py
4_chains_parallel.py
5_chains_branching.py
```

### 🔹 **4. RAG (Retrieval-Augmented Generation)**  
📌 Work with **documents, embeddings, vector stores**.

```sh
1a_rag_basics.py
1b_rag_basics.py
2a_rag_basics_metadata.py
2b_rag_basics_metadata.py
3_rag_text_splitting_deep_dive.py
4_rag_embedding_deep_dive.py
5_rag_retriever_deep_dive.py
6_rag_one_off_question.py
7_rag_conversational.py
8_rag_web_scrape_firecrawl.py
8_rag_web_scrape.py
```

### 🔹 **5. Agents & Tools**  
📌 Build AI agents and custom tools.

```sh
1_agent_and_tools_basics.py
agent_deep_dive/
1_agent_react_chat.py
2_react_docstore.py
tools_deep_dive/
1_tool_constructor.py
2_tool_decorator.py
3_tool_base_tool.py
```

---

## 📖 **How to Use This Repository**

1️⃣ **📺 Watch the Video**: Start with the **LangChain Master Class for Beginners** on YouTube.
2️⃣ **💻 Run the Code**: Follow along with the examples in this repository.
3️⃣ **👥 Join the Community**: Connect with AI developers in the **FREE Skool community**.

---

## ❓ **FAQ**

❓ **What is LangChain?**  
💡 LangChain is a framework designed to simplify building applications with **language models**.

❓ **How do I set up my environment?**  
💡 Follow the **"Getting Started"** steps above to install dependencies and configure the environment.

❓ **I'm getting an error when running the examples. What should I do?**  
💡 Ensure all dependencies are installed correctly, and your **.env** file is properly set up. If issues persist, join the **Skool community** or open a GitHub issue.

❓ **Can I contribute to this repository?**  
💡 Yes! **Pull requests and issues** are welcome.

❓ **Where can I find more info on LangChain?**  
💡 Check out the **[official LangChain documentation](https://docs.langchain.com/)**.

---

## 🔗 **Support & Contributions**

If you find this project useful, consider **starring 🌟 the repo** and contributing. Feel free to open an issue or **join the discussion** in the Skool community.

---

## 📜 **License**

This project is licensed under the **MIT License**.
