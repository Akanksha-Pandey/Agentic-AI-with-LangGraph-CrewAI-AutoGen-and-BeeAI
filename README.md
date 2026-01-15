# Agentic AI with LangGraph, CrewAI, AutoGen, and BeeAI

A learning repository for practicing and implementing concepts from the **Agentic AI with LangGraph, CrewAI, AutoGen, and BeeAI** course on Coursera.

## Purpose

This repository serves as a practical workbench for exploring and implementing agentic AI architectures. Through hands-on exercises and projects, you'll learn how to:

- Build intelligent agents using **LangGraph** for orchestrating complex workflows
- Create multi-agent systems with **CrewAI** for collaborative problem-solving
- Implement autonomous agents with **AutoGen** for interactive development
- Leverage **BeeAI** for specialized agent capabilities
- Combine multiple frameworks to build robust, scalable agentic applications

## Course Information

**Course:** [Agentic AI with LangGraph, CrewAI, AutoGen, and BeeAI](https://www.coursera.org/learn/agentic-ai-with-langgraph-crewai-autogen-and-beeai)

**Platform:** Coursera

## Directory Structure

```
.
├── LICENSE                          # Repository license
├── README.md                        # This file
├── notebooks/                       # Jupyter notebooks for exploration and learning
│   └── [Course exercises and experiments]
├── notes/                           # Personal notes and documentation
│   └── [Learning materials and insights]
└── [Future: src/, configs/, etc.]   # Additional directories as needed
```

### Directory Details

- **`notebooks/`** - Jupyter notebooks containing:
  - Course exercises and hands-on labs
  - Experiments with LangGraph, CrewAI, AutoGen, and BeeAI
  - Code examples and prototypes
  - Data analysis and visualization

- **`notes/`** - Documentation and personal notes:
  - Key concepts and learning summaries
  - Configuration guides
  - Troubleshooting and best practices
  - References and useful resources

## Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.9+** - Core programming language
- **pip** - Python package manager
- **Jupyter Notebook** or **JupyterLab** - For running interactive notebooks
- **Git** - For version control

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Agentic-AI-with-LangGraph-CrewAI-AutoGen-and-BeeAI.git
cd Agentic-AI-with-LangGraph-CrewAI-AutoGen-and-BeeAI
```

### 2. Create a Virtual Environment (Recommended)

```bash
# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
# On macOS/Linux:
source venv/bin/activate

# On Windows:
# venv\Scripts\activate
```

### 3. Install Dependencies

Create a `requirements.txt` file in the root directory with the necessary packages:

```bash
pip install --upgrade pip
pip install jupyter notebook
pip install langchain langraph
pip install crewai
pip install pyautogen
pip install python-dotenv
```

Or install dependencies directly:

```bash
pip install jupyter notebook langchain langraph crewai pyautogen python-dotenv
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory for API keys and configuration:

```bash
# Example .env file (do not commit sensitive credentials)
OPENAI_API_KEY=your_openai_api_key_here
ANTHROPIC_API_KEY=your_anthropic_api_key_here
# Add other API keys as needed
```

**Important:** Add `.env` to your `.gitignore` file to avoid committing sensitive credentials.

### 5. Start Jupyter Notebook

```bash
jupyter notebook
```

This will open Jupyter in your default browser. Navigate to the `notebooks/` directory to begin working on exercises.

## Getting Started

1. **Review the Course:** Start with the official Coursera course material
2. **Explore Notebooks:** Check out the `notebooks/` directory for structured exercises
3. **Take Notes:** Use the `notes/` directory to document your learning journey
4. **Experiment:** Create new notebooks to test concepts and build projects
5. **Commit Your Work:** Regularly commit your progress with meaningful commit messages

## Key Frameworks Overview

### LangGraph
- Builds stateful, multi-actor applications with LLMs
- Ideal for complex workflows and agent orchestration

### CrewAI
- Framework for assembling multi-agent teams
- Focuses on collaborative problem-solving

### AutoGen
- Microsoft's framework for building multi-agent conversations
- Great for interactive, autonomous agent development

### BeeAI
- Specialized framework for specific AI agent capabilities
- Enhanced extensibility and customization

## Resources

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [AutoGen Documentation](https://microsoft.github.io/autogen/)
- [BeeAI Documentation](https://github.com/i-am-bee/bee-agent-framework)
- [Coursera Course](https://www.coursera.org/learn/agentic-ai-with-langgraph-crewai-autogen-and-beeai)

## Best Practices

- **Document Your Learning:** Add notes and summaries to the `notes/` directory
- **Organize Your Notebooks:** Use descriptive naming conventions (e.g., `01_langraph_basics.ipynb`)
- **Version Control:** Commit frequently with clear, descriptive messages
- **Environment Management:** Always use a virtual environment
- **Security:** Never commit API keys or sensitive information

## Tips for Success

1. **Start Small:** Begin with simple examples before tackling complex agents
2. **Experiment Freely:** Use notebooks to prototype and test ideas
3. **Read Documentation:** Refer to official docs for in-depth understanding
4. **Join Communities:** Engage with Coursera forums and GitHub discussions
5. **Build Projects:** Apply concepts to real-world problems

## License

This repository is licensed under the [LICENSE](LICENSE) file. Ensure compliance with the license terms.

## Contributing

This is a personal learning repository. Feel free to fork, modify, and adapt the content for your own educational purposes.

---

**Happy Learning! 🚀**

_Last Updated: January 2026_