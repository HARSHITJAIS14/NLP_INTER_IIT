# NLP\_INTER\_IIT

In this repo, I was getting ready for my INTER-IIT contest. I set up hands-on NLP experiments to learn more about LLMs, fine-tuning, RAG, and agents—all while diving into my ESC201 electronics material.
##  🚀 Project Overview

Here’s what I played with:

* Fine-tuned Falcon (Guanaco) with LoRA & QLoRA on five ESC201 textbooks.
* Built simple and advanced RAG pipelines on the combined ESC201 text to boost answer quality.
* Created a lightweight web-search agent to experiment with tool integration.

## 📂 What’s Inside

```
harshitjais14-nlp_inter_iit/
├── Agents/
│   └── web-search-agent-tavily.ipynb    # My web-search agent notebook
├── FIne_tuning/
│   ├── blogs.txt                       # Notes and blog links
│   ├── Finetuning_Falcon_Guanaco.ipynb # Fine-tuning steps for Falcon
│   └── Electronics_finetuned/
│       ├── concatenated_books.txt      # Combined ESC201 books
│       ├── electronics-finetuned.ipynb # Results and evaluation
│       └── qa_dataset.json             # Created QA pairs
├── RAG/
│   ├── old.txt                         # Basic RAG scripts
│   ├── new.txt                         # Improved RAG notes
│   ├── rag-esc_old.ipynb               # Simple RAG notebook
│   └── RAG_ESC_new.ipynb               # Advanced RAG notebook
└── RAG_chatbot_promptengineering/
    └── rag-advanced.ipynb              # Prompt tweaks for RAG chatbot
```

## 🔧 Fine-Tuning

* **Models:** Falcon (Guanaco) with LoRA and QLoRA.
* **Data:** Five textbooks for ESC201, cleaned and combined.
* **Goal:** Get the model to answer electronics questions well.

Check out `FIne_tuning/Finetuning_Falcon_Guanaco.ipynb` to see how I did it.

## 📚 RAG Experiments

* **Basic RAG:** simple retrieval + generation (see `rag-esc_old.ipynb`).
* **Advanced RAG:** ranking and custom prompts to pick the best context (`RAG_ESC_new.ipynb`).

## 🤖 Agents

I made a tiny web-search agent to chain together searches and LLM prompts.

* Notebook: `Agents/web-search-agent-tavily.ipynb`

---
