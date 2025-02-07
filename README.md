# **LangChain Crash Course**

Welcome to the **LangChain Crash Course** repository! This repo contains all the code examples you'll need to follow along with the **LangChain Master Class for Beginners**. By the end of this course, you'll be able to:

- Build your own **AI agents**  
- Create **RAG chatbots**  
- Automate tasks using **AI**  

---

## **Course Outline**

1. **Setup Environment**
2. **Chat Models**
3. **Prompt Templates**
4. **Chains**
5. **RAG (Retrieval-Augmented Generation)**
6. **Agents & Tools**

---

## **Getting Started**

### **Prerequisites**

Ensure you have the following installed:

- **Python 3.10 or 3.11**
- **Poetry** (Follow the [Poetry installation tutorial](https://python-poetry.org/docs/#installation))

### **Installation**

1. Clone the repository:

```sh
git clone https://github.com/FarjazKashif/langchain
cd langchain-crash-course
```

2. Install dependencies using Poetry:

```sh
poetry install --no-root
```

3. Set up your environment variables:

```sh
mv .env.example .env
```

4. Activate the Poetry shell:

```sh
poetry shell
```

5. Run the example scripts:

```sh
python 1_chat_models/1_chat_model_basic.py
```

---

## **Repository Structure**

### **1. Chat Models**  
- Learn to interact with **ChatGPT, Claude, and Gemini**.

```sh
1_chat_model_basic.py
2_chat_model_basic_conversation.py
3_chat_model_alternatives.py
4_chat_model_conversation_with_user.py
5_chat_model_save_message_history_firestore.py
```

### **2. Prompt Templates**  
Understand **prompt engineering** and optimize model responses.

```sh
1_prompt_template_basic.py
2_prompt_template_with_chat_model.py
```

### **3. Chains**  
- Automate tasks by chaining **Chat Models & Prompts**.

```sh
1_chains_basics.py
2_chains_under_the_hood.py
3_chains_extended.py
4_chains_parallel.py
5_chains_branching.py
```

### **4. RAG (Retrieval-Augmented Generation)**  
- Work with **documents, embeddings, vector stores**.

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

### **5. Agents & Tools**  
- Build AI agents and custom tools.

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

## **FAQ**

Q1. **What is LangChain?**  
Ans. LangChain is a framework designed to simplify building applications with **language models**.

Q2. **How do I set up my environment?**  
Ans Follow the **"Getting Started"** steps above to install dependencies and configure the environment.

Q3. **I'm getting an error when running the examples. What should I do?**  
Ans. Ensure all dependencies are installed correctly, and your **.env** file is properly set up. If issues persist, join the **Skool community** or open a GitHub issue.

Q4. **Can I contribute to this repository?**  
Ans. Yes! **Pull requests and issues** are welcome.

Q5. **Where can I find more info on LangChain?**  
Ans. Check out the **[official LangChain documentation](https://docs.langchain.com/)**.

---

## 📜 **License**

This project is licensed under the **MIT License**.
