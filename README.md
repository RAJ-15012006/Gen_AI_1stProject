:

🧠 GenAI Question Answering System
📌 Overview

--> This project demonstrates a Question-Answering (QA) system built using Hugging Face Transformers. The model reads a given passage or dataset and accurately responds to user queries based on the provided context. It highlights how transfer learning can be used to quickly build a context-aware AI application.

---

🚀 Features

--> Uses pre-trained transformer model deepset/roberta-base-squad2

--> Interactive Q&A loop where users can ask questions continuously

--> Extractive Question Answering (answers are extracted directly from text passages)

--> Demonstrates context-based inference with custom corpus (e.g., recipes, documents)

--> Simple implementation with Hugging Face pipeline API

---

🛠️ Technologies Used

--> Python 3

--> Transformers (Hugging Face)
 
--> Pre-trained model: RoBERTa fine-tuned on SQuAD2

--> Tokenization for NLP preprocessing

--> Concepts from LangChain and Ollama (mentioned for integration)

---

📂 Project Structure :- 
GenAI.ipynb   # Jupyter Notebook with full implementation

---

📝 Example Usage

Corpus: Recipe ingredients list

User Input:

Ask a question, press q to exit: What vegetables are used?


Model Output:

Answer: carrots, cabbage, or onion

---

💡 Applications

--> Document-based chatbots

--> Virtual assistants

--> Automated FAQ systems

--> Context-aware search engines



