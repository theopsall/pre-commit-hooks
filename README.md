# Pre-Commit Configuration for Python Projects

This repository contains a pre-commit configuration tailored for Python projects. It integrates tools like `black`, `isort`, `flake8`, and `autoflake` to enforce code quality and style consistency.

## Description

This pre-commit setup is designed to streamline Python code formatting and linting processes. It ensures your code is clean, readable, and adheres to best practices before every commit.

## Installation

To use this pre-commit configuration in your project, follow these steps:

1. **Install pre-commit**:

   If not already installed, install pre-commit globally with:

   ```bash
   pip install pre-commit
   ```

2. **Clone This Repository**:

   Clone this repository into your local machine:

   ```bash
   git clone https://github.com/theopsall/pre-commit-hooks
   ```

3. Copy Configuration to Your Project:

   Copy the .pre-commit-config.yaml file from this repository to the root of your project.

4. Install Hooks:

   Navigate to your project's root directory and install the pre-commit hooks:

   ```bash
   pre-commit install
   ```

## Usage

Once installed, pre-commit will run automatically on git commit. However, you can also run it manually on all files:

- To run on all files:
  ```bash
  pre-commit run --all-files
  ```
- To format a specific file:
  Run pre-commit for a specific file with:
  ```bash
  pre-commit run --files your-file.py
  ```

# Updating Hooks

To update the hooks to their latest versions:

```bash
pre-commit autoupdate
```

Helpful medium [article](https://gatlenculp.medium.com/effortless-code-quality-the-ultimate-pre-commit-hooks-guide-for-2025-57ca501d9835)

https://github.com/astral-sh/ruff-pre-commit

https://github.com/astral-sh/uv-pre-commit