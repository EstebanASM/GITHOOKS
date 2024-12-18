# GITHOOKS

## 🚀 Project Overview
This project demonstrates the implementation and usage of **GitHooks** in a repository. GitHooks are scripts that Git executes before or after events, such as commits, pushes, or merges, to automate tasks and enforce workflows.

---

## 🛠️ **GitHooks Implemented**

### 1. **Pre-commit Hook**
- Checks for trailing whitespaces and ensures code consistency.
- Prevents commits with unwanted spaces or syntax issues.

### 2. **Commit-msg Hook**
- Enforces a standardized commit message format, improving commit history readability.

### 3. **Custom Hooks**
- You can extend GitHooks to automate linting, testing, and formatting code before commits.

## 📂 **Project Structure**
```plaintext
GITHOOKS/
│
├── .gitignore         # Specifies files/folders ignored by Git
├── README.md          # Documentation of the project
├── main.py            # Example Python script
```
## Testing GitHooks execution
- git add main.py
- git commit -m "test: prueba del pre-commit hook"

## 💡 **Benefits of GitHooks**

- Automates repetitive tasks like linting, testing, or formatting.
- Enforces team standards and best practices.
- Prevents common errors before code reaches the repository.

## 👥 Contributors
- Esteban