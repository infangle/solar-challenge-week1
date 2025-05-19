# solar-challenge-week1

## Task 1: Git & Environment Setup

### Reproducing the Environment Setup

To reproduce the development environment setup, follow these steps:

1. Clone the repository and checkout the `setup-task` branch.

2. Create a Python virtual environment using venv:

```bash
python3 -m venv venv
```

3. Activate the virtual environment:

```bash
source venv/bin/activate
```

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Merge the `setup-task` branch into `main` via a Pull Request.

### Suggested Folder Structure

```
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```

### Key Performance Indicators (KPIs)

- Dev Environment Setup
