# Develop Generative AI Applications

This README summarizes the key concepts I learned while completing an introductory course on Generative AI, prompt engineering, and LangChain.

---

## 🚀 What I Learned

### Generative AI Basics

* **Generative AI models**: AI systems that generate text, images, audio, or code.
* **Foundational models**: A subset of generative AI, including **large language models (LLMs)**.
* **Prompts**: Instructions given to an LLM to guide its output.


### Prompt Engineering

* **Components of a prompt:**

  * Instructions → clear, specific commands
  * Context → background info that supports the task

* **Prompting techniques:**

  * Zero-shot → no examples
  * One-shot → single example
  * Few-shot → multiple examples for generalization
  * Chain of Thought (CoT) → step-by-step reasoning
  * Self-consistency → multiple reasoning paths, select most consistent

### LangChain Basics

* Open-source framework to build applications with LLMs.
* Key components: language models, chat models, response templates, output parsers.
* **Chains:** sequences of calls

  * Sequential chain → step 1 output = step 2 input
* **Agents:** dynamic systems where LLMs decide next actions (using chains, tools, databases, search engines).

### LangChain Expression Language (LCEL)

* Uses the **pipe operator** to connect components.
* Cleaner and more intuitive than traditional `RunnableSequence`.
* Example:

  ```
  input | prompt | llm | parser
  ```

### AI Models Explored

* **Llama 3** → strong reasoning, handles nuanced problems.
* **Granite (IBM Watsonx)** → enterprise-focused, strong in business/technical tasks.
* **Mixtro** → mixture of experts, efficient and adaptable (activates only the experts needed).

---


## 🛠️ Tools & Frameworks Practiced

* **LangChain** for chaining LLM calls.
* **Flask** for building simple GenAI-powered web applications.
* **Prompt engineering** with different techniques (zero-shot, few-shot, CoT).

---

## 📌 Next Steps

* Apply RAG (Retrieval-Augmented Generation) to real-world projects.
* Explore **LangChain agents** with integrated tools like vector databases.
* Build more GenAI apps with Flask and Gradio.
* Continue experimenting with multiple models (Llama 3, Granite, Mixtral) to compare trade-offs.

---

## 🎓 Reflection

This course gave me a **practical foundation in Generative AI** — not just how LLMs work, but how to design prompts, structure workflows, and deploy apps. The mix of theory and hands-on labs helped me understand how to **turn abstract AI concepts into working projects**.

---

