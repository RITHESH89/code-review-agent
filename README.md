# Code Review Agent

An AI agent that reviews code for bugs, security issues, performance problems, and style violations.

**Framework**: LangChain  
**LLM**: GPT-4o  

## Setup

## Run

```bash
# Review a file
python agent.py --file path/to/your/code.py





## Sample Output

```
🔍 Reviewing: example.py

============================================================
📋 CODE REVIEW
============================================================
## Overall: 🟡 Needs Work

### 1. Bugs & Correctness
- `divide(a, b)` has no zero-division check → `ZeroDivisionError` on `b=0`

### 2. Security Issues
- No input validation on external parameters

### 3. Improvements
- Add type hints: `def divide(a: float, b: float) -> float`
- Raise `ValueError` for `b == 0` with descriptive message
```# code-review-agent

