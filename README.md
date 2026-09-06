# AIGentDemo

**Session 8 Codebasics AI Bootcamp Project**

AIGentDemo is a demonstration project showcasing AI agent interactions and utilities developed during the Codebasics AI Bootcamp. This repository contains example code, scripts, and resources to help participants understand and experiment with AI-driven agents.

---

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

The project provides a minimal yet functional setup for building and testing AI agents. It includes:

- Core agent classes and utilities.
- Example scripts demonstrating agent interactions.
- Configuration files for easy setup.
- Tests to validate functionality.

---

## Installation

### Prerequisites

- **Python 3.9+** (recommended 3.10)
- **Git**
- **Virtual environment** tool (`venv` or `conda`)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/aigentdemo.git
   cd aigentdemo
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. **Verify the installation**
   ```bash
   python -m pytest
   ```
   All tests should pass, confirming a successful setup.

---

## Usage

### Running the Demo Script

The primary entry point is `demo.py`. After installation, execute:

```bash
python demo.py
```

This will start a simple interactive session where you can issue commands to the AI agent and observe responses.

### Available Scripts

- `demo.py` – Runs the interactive agent demo.
- `train_agent.py` – Example script for training a custom agent (placeholder).
- `utils/` – Helper utilities used by the demo.

### Configuration

Configuration options are stored in `config.yaml`. Modify parameters such as model selection, temperature, and API keys as needed before running the scripts.

---

## Project Structure

```
aigentdemo/
├── README.md               # Documentation (this file)
├── demo.py                 # Interactive demo script
├── train_agent.py          # Training script (example)
├── config.yaml             # Configuration file
├── requirements.txt        # Python dependencies
├── utils/                  # Utility modules
│   ├── __init__.py
│   └── agent.py            # Core agent implementation
├── tests/                  # Test suite
│   └── test_agent.py
└── .gitignore
```

---

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. **Fork the repository** on GitHub.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes** and ensure the code style follows PEP 8.
4. **Write or update tests** as needed.
5. **Run the test suite** to confirm everything passes:
   ```bash
   pytest
   ```
6. **Commit your changes** with a clear, concise commit message.
7. **Push to your fork** and open a Pull Request (PR) against the `main` branch.

### Pull Request Guidelines

- Provide a descriptive title and summary.
- Reference any related issues (e.g., `closes #12`).
- Ensure all CI checks pass.
- Follow the existing documentation style.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or suggestions, please open an issue or contact the maintainer:

- **Name:** Your Name
- **Email:** your.email@example.com
- **GitHub:** [your-username](https://github.com/your-username)

---

*Happy coding!*
