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

- 📘 `Relazione LLM-Eval.pdf` – Full project report
- 📰 `Articolo.pdf` – Original paper on LLM-Eval
- 📊 `Presentazione LLM.pptx` – Slide deck
- 📝 `Traccia.pdf` – Project guidelines

All located inside `docs/`.

---

## 👥 Contributors

- Giovanni Arcangeli
- [Vittorio Ciancio](https://github.com/VittorioCiancio)
- [Marco Di Maio](https://github.com/Marco210210)

Project presented for the Artificial Intelligence course – University of Salerno (2025)

---

## ✨ Notes

This project demonstrates the limitations and potential of automatic dialogue evaluation. It highlights the differences between LLM generations and emphasizes the influence of dataset structure on evaluation performance.

For questions, feel free to contact the authors or open an issue on GitHub.