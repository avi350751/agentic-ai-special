# agentic-ai-special

A repo for learning and experimenting with agentic AI patterns and implementations using Python and OpenAI APIs.

## 📋 Project Overview

This repository serves as a learning platform for exploring agentic AI concepts, from foundational principles to integration with OpenAI's models. The project is structured into progressive learning modules to build understanding step-by-step.

## 🗂️ Project Structure

```
ed-agentic-ai/
├── main.py              # Main entry point for the project
├── pyproject.toml       # Project configuration and dependencies
├── README.md            # This file
├── 1_foundation/        # Foundational concepts and theory
├── 2_openai/            # OpenAI integration exercises
│   └── w2d1.ipynb       # Week 2, Day 1 notebook
└── .env                 # Environment variables (API keys, etc.)
```

## 🚀 Quick Start

### Prerequisites

- Python 3.12 or higher
- [uv](https://docs.astral.sh/uv/) - Fast Python package installer (recommended)
- OpenAI API key (for 2_openai section)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ed-agentic-ai
   ```

2. **Set up the virtual environment**
   ```bash
   # Using uv (recommended)
   uv sync

   # Or using venv
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Configure environment variables**
   ```bash
   cp .env.example .env  # if available
   # Edit .env with your OpenAI API key and other settings
   ```

4. **Install dependencies**
   ```bash
   uv pip install -r requirements.txt
   # or manually install from pyproject.toml
   ```

### Running the Project

**Run the main script:**
```bash
python main.py
```

**Run Jupyter notebooks:**
```bash
jupyter notebook 2_openai/w2d1.ipynb
```

## 📚 Learning Modules

### 1_foundation/
Foundational concepts and theory for understanding agentic AI:
- Basic agent patterns
- Core principles and design patterns
- Theoretical foundations

### 2_openai/
Integration with OpenAI APIs and practical implementations:
- **w2d1.ipynb** - Week 2, Day 1 exercises and experiments

## 🔧 Dependencies

Current project dependencies are minimal. As you progress through the modules, you'll typically need:

- `python-dotenv` - For environment variable management
- `openai` - OpenAI Python client library
- `agents` - Agentic AI framework

See `pyproject.toml` for the authoritative list of dependencies.

## 📝 Development Workflow

1. Each module contains exercises and experiments
2. Use Jupyter notebooks for interactive learning
3. Main scripts demonstrate practical implementations
4. Environment variables are loaded from `.env` file

## 📋 Requirements

- Python >= 3.12
- See `.python-version` for current Python version requirement

## 🔐 Environment Variables

The project uses a `.env` file for configuration. Common variables:

- `OPENAI_API_KEY` - Your OpenAI API key
- Other API keys and configuration as needed

**Important:** Never commit `.env` to version control. It's already in `.gitignore`.

## 📖 Usage

Start with foundational concepts in `1_foundation/`, then progress to OpenAI integration in `2_openai/`.

Each day's lesson is organized in its own notebook (e.g., `w2d1.ipynb`).

## 🤝 Contributing

This is a learning project. Feel free to:
- Add new learning modules
- Enhance existing notebooks
- Document findings and insights
- Create example implementations

## 📄 License

[Specify your license here - e.g., MIT]

## 📞 Resources

- [OpenAI Documentation](https://platform.openai.com/docs)
- [Python Documentation](https://docs.python.org/3.12/)
- [Jupyter Notebooks](https://jupyter.org/)

---

**Happy learning!** 🚀
