# 🧠 LangGraph Learning Hub (CampusX Implementations)

This repository serves as a dedicated workspace for learning, experimenting, and implementing concepts related to **LangGraph**.

LangGraph is a powerful library built on top of LangChain that enables the construction of stateful, multi-actor, and cyclic applications, offering robust control over flow and logic in Large Language Model (LLM) based systems.

---

## 💡 Motivation and Context

This project is a direct outcome of the specialized curriculum provided by **CampusX**. The primary goal is to master advanced LLM application architecture by:

1.  Understanding the core concepts of graph-based programming for LLMs.
2.  Implementing various complex workflows (agents, planning, tool usage) using nodes and edges.
3.  Developing robust, stateful applications that can run in loops or follow conditional logic.

## 🚀 Core Concepts Covered

The examples and implementations within this repository focus on the fundamental building blocks of LangGraph:

* **State:** Defining the central object that is passed between nodes and holds the context of the entire graph run.
* **Nodes:** Functions or agents that perform a specific task (e.g., calling an LLM, performing a web search, routing).
* **Edges:** The connections between nodes, defining the execution path.
* **Conditional Edges:** Logic that determines the next node based on the output of the current node.
* **Cycles:** Building loops for iterative refinement (e.g., planning, self-correction, or tool-calling loops).
* **Agents:** Implementing multi-agent workflows where different LLMs or tools collaborate.

## 🛠️ Installation and Setup

To run the implementations locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/sayyedsabirali/LangGraph.git](https://github.com/sayyedsabirali/LangGraph.git)
    cd LangGraph
    ```

2.  **Create a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # .\venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Environment Variables:**
    You will need to set your API key for the chosen LLM (e.g., OpenAI, Google, Anthropic).
    ```bash
    # Example for OpenAI
    export OPENAI_API_KEY="YOUR_API_KEY"
    ```

5.  **Run an example:**
    ```bash
    # Replace with the name of the file you want to test
    python basic_graphs/simple_router.py
    ```

## 📈 Learning Progress Tracker

This section will be updated as new concepts and examples are mastered:

| Module / Concept | Status | File Location | Notes |
| :--- | :--- | :--- | :--- |
| **Basic Graph Builder** | ✅ Completed | `basic_graphs/builder_example.py` | Sequential flow execution. |
| **Conditional Edge Logic** | ⏳ In Progress | `basic_graphs/conditional_router.py` | Routing based on LLM output. |
| **Self-Correcting Agent** | ⬜ To Do | `agents/self_correct_agent.py` | Implementing a loop for tool usage. |
| **Multi-Agent Workflow** | ⬜ To Do | `agents/collaborative_team.py` | Two or more agents passing tasks. |

---

## 🎓 Learning Source

All concepts and implementations in this repository are learned via the comprehensive program provided by:

**CampusX**
https://www.youtube.com/playlist?list=PLKnIA16_RmvYsvB8qkUQuJmJNuiCUJFPL

---

## 🤝 Contribution

This repository is for personal learning, but suggestions and feedback are always welcome!
