# OpenRouter Manager
======================
### v10.2 System Bible Specification

## Overview
The OpenRouter Manager is a cutting-edge, autonomous agentic development framework. This project adheres to the v10.2 spec, ensuring meticulous standardization, exhaustive documentation, and massive ASCII data flow charts.

## ASCII Data Flow Chart
```markdown
                                      +---------------+
                                      |  User Input  |
                                      +---------------+
                                             |
                                             |
                                             v
                                      +---------------+
                                      |  Director Node  |
                                      |  (Infinite Loop)  |
                                      +---------------+
                                             |
                                             |
                                             v
                                      +---------------+
                                      |  Executor Node  |
                                      |  (Python Regex)  |
                                      +---------------+
                                             |
                                             |
                                             v
                                      +---------------+
                                      |  Syphon Node    |
                                      |  (GitHub Push)  |
                                      +---------------+
                                             |
                                             |
                                             v
                                      +---------------+
                                      |  OpenRouter    |
                                      |  Manager Core  |
                                      +---------------+
```

## Project Structure
```markdown
├──.git/
├── README.md
├── src/
│   ├── main.py
│   ├── director.py
│   ├── executor.py
│   └── syphon.py
├── tests/
│   ├── test_director.py
│   ├── test_executor.py
│   └── test_syphon.py
├── requirements.txt
├── pedagogy_cognitive.db
└── initialize_enterprise_project.py
```

## Setup Instructions
### Windows Setup
1. Install Python 3.10+ from python.org
2. Open PowerShell
3. Run: `pip install -r requirements.txt`
4. Execute: `python src/main.py`

### Android Setup (Termux)
1. Install Termux
2. `pkg install python git`
3. `pip install -r requirements.txt`
4. `python src/main.py`

## Axiomatic Breakdown
1. **UI:** User input handling and validation
2. **DB:** SQLite layer logic for token efficiency caching
3. **State:** Director Node's infinite loop for prompt routing
4. **API:** Executor Node's Python Regex for deterministic parsing

## Why OpenRouter Manager?
The OpenRouter Manager is designed to provide a robust, scalable, and maintainable framework for autonomous agentic development. By following the v10.2 spec, this project ensures that all aspects of the development process are meticulously standardized, documented, and visualized.

[CMD]
```bash
git add.
git commit -m "Standardized openrouter to v10.2 spec"
git push origin main
