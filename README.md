# LLM-Eval – Automatic Evaluation of Dialogues with LLMs

**LLM-Eval** is a two-phase research project that explores how Large Language Models (LLMs) can be used to **automatically evaluate the quality of dialogues** between humans and conversational agents.

The project investigates the use of the **LLM-EVAL framework**, testing its ability to reproduce human-like evaluations across different models and datasets.

---

## 🌐 Project Overview

- Phase 1: Evaluate four LLMs on a benchmark dataset (`ConvAI2`):
  - Claude 3
  - Claude 3.5
  - GPT-4o
  - GPT-4o-mini
- Phase 2: Evaluate how dataset structure affects performance (using Claude 3):
  - FED
  - PC
  - TC
  - DSTC9
- Metrics: Accuracy, Cohen’s Kappa, Pearson, Spearman, Kendall-Tau correlations
- Evaluation schema follows the paper: *LLM-Eval: Unified Multi-Dimensional Automatic Evaluation for Open-Domain Conversations*

---

## 🛠️ Technologies & Tools

- **Programming Language**: Python 3
- **API Access**: OpenAI + Anthropic APIs
- **Environment Management**: `venv` + `.env` for keys
- **Libraries**: `json`, `os`, `tqdm`, `anthropic`, `openai`, `sklearn`, `pandas`, `matplotlib`

---

## 📁 Repository Structure

```plaintext
LLM-Eval/
├── docs/                    → Project report, presentation, paper
├── prog/
│   ├── dataset1/            → Phase 1: Model-based evaluation (Claude, GPT)
│   │   ├── Claude3/
│   │   ├── Claude3-5/
│   │   ├── GPT-4o/
│   │   ├── GPT-4o-mini/
│   │   └── convai2_data.json
│   ├── dataset2/            → Phase 2: Dataset-based evaluation (FED, TC, etc.)
│   │   ├── DSTC9/
│   │   ├── FED/
│   │   ├── PC/
│   │   └── TC/
├── README.md               → Project documentation (this file)
```

---

## 📄 Documentation

- 📘 [LLM-Eval_Report.pdf](docs/LLM-Eval_Report.pdf) – Full project report  
- 📰 [LLM-Eval_Paper.pdf](docs/LLM-Eval_Paper.pdf) – Original paper on LLM-Eval  
- 📊 [LLM-Eval_Presentation.pptx](docs/LLM-Eval_Presentation.pptx) – Slide deck  
- 📝 [LLM-Eval_Guidelines.pdf](docs/LLM-Eval_Guidelines.pdf) – Project guidelines

All located inside `docs/`.

---

## 👥 Contributors

- [Arcangeli Giovanni](https://github.com/GiovanniArcangeli)
- [Ciancio Vittorio](https://github.com/VittorioCiancio)
- Marco Di Maio

Project presented for the Artificial Intelligence course – University of Salerno (2025)

---

## 📄 License

This project is licensed under the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/)  
[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)  

You may share and adapt this work for non-commercial purposes only, **as long as you give appropriate credit** and **distribute your contributions under the same license**.  
For commercial use, **explicit permission from the authors is required**.

