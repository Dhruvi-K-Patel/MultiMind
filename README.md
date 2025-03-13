# MultiMind: AI-Powered Multi-Agent System with LangGraph & Gemini  

## Table of Contents  
1. [Project Overview](#project-overview)  
2. [Key Features](#key-features)  
3. [Technology Stack](#technology-stack)   
4. [Usage Instructions](#usage-instructions)  
5. [Agent Capabilities](#agent-capabilities)  
6. [Future Enhancements](#future-enhancements)  
7. [Conclusion](#conclusion)  

---

## Project Overview  
**MultiMind** is an **AI-powered multi-agent system** that integrates **LangGraph** and **Google Gemini AI** to enable intelligent task execution. This system models **collaborative AI agents**, each specializing in different tasks such as **mathematical calculations, text processing, and more**.  

By leveraging **LangGraph**, MultiMind enables **multi-agent collaboration**, where different AI agents communicate and coordinate to solve complex tasks efficiently.  

---

## Key Features  
✅ **Multi-Agent Collaboration** – AI agents interact and execute tasks dynamically.  
✅ **Mathematical Computation** – Perform **addition, multiplication, and squaring** of numbers.  
✅ **Text Processing** – Convert text to **uppercase, lowercase**, and **add smileys**.  
✅ **Customizable Prompts** – Configure agent behavior using **system messages**.  
✅ **Scalable & Modular** – Easily extendable for **new agent capabilities**.  

---

## Technology Stack  
- **Programming Language**: Python  
- **AI Frameworks**:  
  - **Google Gemini AI** (via `ChatVertexAI`)  
  - **LangGraph** for multi-agent interactions  
- **Libraries Used**:  
  - `langchain_google_vertexai` – AI model integration  
  - `langchain` – Multi-agent system implementation  

---

## Usage Instructions

### 1. Start the Multi-Agent System
- Run the Jupyter Notebook to initialize AI agents.

### 2. Execute AI-Driven Tasks
- Input mathematical or text-processing tasks, and the relevant agent will handle execution.

### 3. Monitor Agent Collaboration
- Agents communicate via LangGraph, executing tasks collaboratively.

## Agent Capabilities

### Mathematical Computation Agents
| Agent       | Task                          |
|------------|------------------------------|
| `add(a, b)` | Adds two numbers             |
| `multiply(a, b)` | Multiplies two numbers     |
| `square(a)` | Calculates the square of a number |

### Text Processing Agents
| Agent       | Task                          |
|------------|------------------------------|
| `make_upper_case(text)` | Converts text to uppercase |
| `make_lower_case(text)` | Converts text to lowercase |
| `add_smiley(text)` | Appends a smiley emoji to text |

## Future Enhancements
✅ **Enhanced AI Reasoning** – Implement reinforcement learning for better decision-making.  
✅ **Real-Time Interaction** – Develop an interactive chatbot interface for agent interaction.  
✅ **Expanded Agent Roles** – Introduce data processing and analytical AI agents.  
✅ **Cloud Deployment** – Deploy the system to Google Cloud for scalability.  

## Conclusion
**MultiMind** showcases the power of multi-agent AI collaboration, allowing AI models to work together seamlessly. By leveraging LangGraph and Google Gemini AI, it provides a modular, scalable, and efficient solution for task execution automation.
