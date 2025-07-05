# ThinkSpec

**ThinkSpec** is a modular, AI-assisted requirements engineering tool that leverages **LangChain**, **Ollama**, and structured prioritization and evaluation frameworks (**SOLID**, **MoSCoW**, **RUST**) to generate, refine, and assess software requirements efficiently.

---

## 🧠 Key Features

- ✍️ **AI-Generated Requirements**  
  Uses **LangChain** with local models via **Ollama** to auto-generate structured user stories from prompts or project descriptions.

- 🧱 **Modular Design**  
  Requirements are crafted with **SOLID** principles to ensure maintainable and extendable architecture.

- 🎯 **MoSCoW Prioritization**  
  Stories are categorized using the MoSCoW method:
  - Must-have
  - Should-have
  - Could-have
  - Won’t-have

- 🔎 **RUST Evaluation**  
  User stories are evaluated using the RUST framework:
  - **R**eadability  
  - **U**niqueness  
  - **S**pecificity  
  - **T**echnical soundness

---

## 🚀 Quick Start

### Prerequisites

- Python 3.10+
- [Ollama](https://ollama.com) installed and running
- Required Python packages: `langchain`, `ollama`

### Installation

```bash
git clone https://github.com/yourusername/thinkspec.git
cd thinkspec
pip install -r requirements.txt
