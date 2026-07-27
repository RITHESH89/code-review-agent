# Code Review Agent

An AI agent that reviews code for bugs, security issues, performance problems, and style violations.

**Framework**: LangChain  
**LLM**: GPT-4o  

## Setup


python agent.py --code "def divide(a, b): return a / b"

# Review non-Python code
python agent.py --file app.js --language javascript
```


### 3. Improvements
- Add type hints: `def divide(a: float, b: float) -> float`
- Raise `ValueError` for `b == 0` with descriptive message
```# code-review-agent

