# 🧮 Math Problem Solver

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Ollama](https://img.shields.io/badge/Ollama-Compatible-green)](https://ollama.com)
[![Gemma 3](https://img.shields.io/badge/Gemma%203-4B%20Model-orange)](https://ollama.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Privacy First](https://img.shields.io/badge/Privacy-First-blueviolet)](https://privacy-first.ai)

Step-by-step math problem solving for learning

> Breaks down math problems with detailed solution steps and educational explanations

## What It Does

- Solve math problems with complete step-by-step solutions
- Show pedagogical reasoning for each calculation step
- Support algebra, geometry, calculus, and statistics problems
- Provide alternative solution methods for conceptual understanding


## Tech Stack

- **Language**: Python 3.8+
- **LLM Runtime**: [Ollama](https://ollama.com)
- **Model**: [Gemma 3](https://ollama.com) (4B variant for optimal performance)
- **Key Libraries**: requests, json, logging
- **Architecture**: Privacy-first local processing

## Quick Start

### Prerequisites
- Python 3.8 or higher
- [Ollama](https://ollama.com) installed and running
- 4GB+ RAM (Gemma 3 4B model)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kennedyraju55/math-problem-solver.git
   cd math-problem-solver
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Pull the Gemma 3 model**
   ```bash
   ollama pull gemma3:4b
   ```

4. **Run the application**
   ```bash
   python main.py
   ```

## Architecture

This tool operates entirely on your local machine using Gemma 3 running via Ollama. The architecture ensures:

- **Local Processing**: All inference runs on your hardware
- **No External Dependencies**: No data leaves your device
- **Extensible**: Easy to swap models or add custom processors
- **Teacher-Friendly**: Designed with educator workflows in mind

```
Input → Local Ollama (Gemma 3) → Processing Pipeline → Output
  ↑                                                          ↓
  └──────────── Your Computer (No Cloud Calls) ────────────┘
```

## Why Local?

### 🔒 Privacy & Compliance
- **FERPA Compliant**: No student data transmitted externally
- **COPPA Compliant**: Safe for K-12 environments
- **Works Offline**: Perfect for schools with limited connectivity

### 💪 Performance
- Instant responses without network latency
- Works reliably in low-bandwidth environments
- Fully functional during internet outages

### 💰 Cost-Effective
- No API fees or usage charges
- One-time model download (~2GB)
- Run unlimited queries

## Contributing

We welcome contributions! Please:

1. Fork the repository
2. Create a feature branch (\git checkout -b feature/improvement\)
3. Commit your changes (\git commit -am 'Add feature'\)
4. Push to the branch (\git push origin feature/improvement\)
5. Open a Pull Request

For major changes, please open an issue first to discuss proposed modifications.

## License

This project is licensed under the **MIT License** — see [LICENSE](./LICENSE) file for details.

---

**Part of 114+ privacy-first AI tools by [Nrk Raju](https://github.com/kennedyraju55)**

Built with ❤️ for educators who care about student privacy.