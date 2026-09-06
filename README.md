# aigentdemo

## Overview

`aigentdemo` is a demo project showcasing AI agent concepts developed during the CodeBasics AI Bootcamp (Session 8). The repository contains example code, utilities, and scripts that illustrate how to build, train, and interact with simple AI agents using popular Python libraries.

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/aigentdemo.git
   cd aigentdemo
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

   If a `requirements.txt` file does not exist, install the core libraries manually:
   ```bash
   pip install numpy pandas torch transformers
   ```

## Usage Examples

### Running a Sample Agent
```bash
python run_agent.py --config config/sample.yaml
```
The script will initialise the agent, load the specified model, and perform a simple interaction loop.

### Training a Model
```bash
python train.py --data data/training_dataset.csv --epochs 10
```
This command starts training using the dataset provided in the `data/` directory.

### Interactive REPL
```bash
python repl.py
```
Enter the REPL to type natural‑language commands and see the agent's responses in real time.

## Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository** and clone your fork.
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make your changes**, ensuring code style consistency (PEP‑8) and adding or updating tests as needed.
4. **Commit your changes** with a clear commit message.
5. **Push to your fork** and open a Pull Request against the `main` branch.

### Pull Request Checklist
- [ ] Code follows the project's style guidelines.
- [ ] Added/updated documentation where applicable.
- [ ] All tests pass (`pytest` or the project's test suite).
- [ ] No new linting errors (`flake8`/`pylint`).

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
