# **Building Controllable AI Agents with LangGraph**

## **Project Overview**

In this project, I explored the capabilities of LangGraph, an extension of the LangChain framework designed to build highly controllable AI agents. Guided by experts like Harrison Chase and Rotem Weiss, I learned how to construct agents from the ground up, enhance their performance with agentic search, and implement state management to ensure consistency across interactions.

## **Notebooks Overview**

### **1. Building an Agent from Scratch**
- **Objective:** The first step was to build a simple agent using Python and an LLM, gaining a deep understanding of how tasks are divided between the language model and the surrounding code.
- **Key Activities:**
  - Constructed an agent from scratch, learning how to balance responsibilities between the LLM and custom logic.
  - Focused on understanding the foundational elements that make an AI agent effective.

### **2. Implementing the Agent with LangGraph**
- **Objective:** After building the initial agent, I rebuilt it using LangGraph to leverage its powerful components and flow-based design.
- **Key Activities:**
  - Reconstructed the agent with LangGraph, which allowed for more control and flexibility.
  - Learned how to combine different components within LangGraph to create a seamless workflow.

### **3. Enhancing the Agent with Agentic Search**
- **Objective:** The goal here was to integrate agentic search capabilities, enabling the agent to retrieve multiple, well-structured answers to queries, improving its built-in knowledge.
- **Key Activities:**
  - Integrated agentic search into the agent, allowing it to gather and process multiple responses in a predictable format.
  - Experimented with using this enhanced search to boost the quality and relevance of the agent’s output.

### **4. Implementing Persistence and State Management**
- **Objective:** I aimed to add persistence to the agent, allowing it to manage state across multiple interactions, switch contexts, and reload previous states when needed.
- **Key Activities:**
  - Implemented state management, enabling the agent to maintain continuity across conversations.
  - Added features like conversation switching and the ability to resume past interactions, making the agent more robust.

### **5. Developing an Essay Writing Agent**
- **Objective:** To put everything together, I developed an agent designed to assist with essay writing, simulating the workflow of a researcher.
- **Key Activities:**
  - Built an agent that could guide the essay writing process, from gathering information to drafting content.
  - Incorporated human-in-the-loop elements to allow for real-time feedback and refinement during the writing process.

## **Technologies Used**

- **LangChain & LangGraph:** The core frameworks used to build and manage the AI agents.
- **Python:** The primary programming language used throughout the project.
- **LLMs (Large Language Models):** Powered the agents, providing the intelligence behind their decision-making processes.
- **Agentic Search:** Enhanced the agent’s ability to retrieve and process relevant information.
- **State Management Tools:** Implemented to allow agents to maintain context and continuity across sessions.

## **Key Concepts and Techniques Learned**

- **LangGraph Components:** Learned how to use LangGraph’s components to build flow-based, controllable AI applications.
- **Agentic Search:** Integrated agentic search to improve the quality and structure of data retrieved by the agents.
- **Persistence & State Management:** Implemented techniques for managing agent state across multiple threads and sessions, enhancing the agent’s continuity.
- **Human-in-the-Loop:** Incorporated human oversight into the agent’s workflow, allowing for real-time adjustments and improvements.
- **Essay Writing Workflow:** Developed an agent that could assist in the research and writing process, simulating the work of a researcher.
