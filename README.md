

# 🤖 Local LLM Explorer: Search & Translate with Ollama

This project provides a complete, automated setup for running a **Local Large Language Model (LLM)** inside Google Colab. It features an integrated web search agent and a specialized translation engine, all accessible via a user-friendly Gradio web interface.

## 🌟 Key Features

* **Background Ollama Server:** Automatically installs and runs the Ollama engine in a non-blocking background thread.
* **Web-Grounded Chat:** Uses **LangChain** and **DuckDuckGo** to allow the LLM to access real-time information from the internet.
* **Specialized Translation:** Features the `translategemma:4b` model, specifically pulled for high-quality language translation tasks.
* **Interactive Web UI:** Includes a built-in **Gradio** interface so you can chat with your local model through a public URL.

## 🛠️ Technology Stack

* **Core Engine:** Ollama
* **Framework:** LangChain (Community & Ollama)
* **Search Provider:** DuckDuckGo Search
* **UI/UX:** Gradio
* **Hardware:** Optimized for Google Colab T4 GPUs

## 🚀 Quick Start

1. **Open the Notebook:** Upload `kevin_local_llm.ipynb` to Google Colab.
2. **Configure Hardware:** Go to `Edit` > `Notebook settings` and ensure **T4 GPU** is selected.
3. **Run Dependencies:** The first cell installs system tools like `zstd` and all necessary Python libraries.
4. **Initialize Ollama:** The second cell starts the server and pulls the `translategemma:4b` model.
5. **Launch Chat:** Run the final cell to generate your unique `gradio.live` link and start chatting.

## 📋 Requirements

The notebook handles most installations automatically, but relies on the following key packages:

* `langchain-ollama`
* `langchain-community`
* `duckduckgo-search`
* `gradio`

---

**Created by Kevin** | *Part of the AI with Joy Series*
