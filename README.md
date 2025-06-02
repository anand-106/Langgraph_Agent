# 🤖 Langchain Routed Agent Chatbot

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Langchain](https://img.shields.io/badge/🦜Langchain-Latest-green.svg)](https://python.langchain.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A sophisticated chatbot implementation using Langchain and LangGraph that intelligently routes conversations between emotional and logical responses. The system uses advanced LLM models to provide context-aware, empathetic, or analytical responses based on the user's input.

## ✨ Features

- 🎯 **Intelligent Message Classification**: Automatically detects whether user input requires emotional or logical handling
- 🧠 **Dual Agent System**: 
  - Emotional agent for empathetic responses
  - Logical agent for fact-based answers
- 🔄 **Dynamic Routing**: Seamlessly switches between response types
- 🔌 **Flexible Model Support**: Works with Google's Gemini and Ollama models
- 🛠️ **Easy to Extend**: Modular architecture for adding new agent types

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- pip or poetry for package management

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Langchain-new.git
cd Langchain-new
```

2. Set up a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up your environment variables:
```bash
cp .env.example .env
# Edit .env with your API keys
```

## 💻 Usage

### Simple Agent

Run the basic chatbot implementation:
```bash
python simple_agent.py
```

### Routed Agent

Run the advanced routed agent implementation:
```bash
python routed_agent.py
```

Example interactions:
```
Message: I'm feeling really overwhelmed with work lately
Assistant: (emotional) I hear how overwhelmed you're feeling...

Message: What is the capital of France?
Assistant: (logical) The capital of France is Paris...
```

## 🏗️ Architecture

The project consists of two main implementations:

1. **Simple Agent** (`simple_agent.py`):
   - Basic chatbot implementation
   - Single LLM model
   - Direct question-answer flow

2. **Routed Agent** (`routed_agent.py`):
   - Advanced implementation with message classification
   - Dual agent system (emotional/logical)
   - Dynamic response routing
   - State management using LangGraph

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Langchain](https://python.langchain.com/) for the excellent LLM framework
- [LangGraph](https://python.langchain.com/docs/langgraph) for the graph-based orchestration
- Google's Gemini and Ollama for providing the LLM models

---

<div align="center">
Made with ❤️ using Langchain and LangGraph
</div>
