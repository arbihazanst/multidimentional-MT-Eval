# Beyond BLEU: GPT–5, Human Judgment, and Classroom Validation for Multidimensional Machine Translation Evaluation

This repository contains the data, evaluation rubric, and analysis materials supporting the paper:

**Beyond BLEU: GPT–5, Human Judgment, and Classroom Validation for Multidimensional Machine Translation Evaluation**  
Published in *Digital* (MDPI), Volume 6, Issue 1, Article 8.

---

## 📄 Abstract

This study investigates the use of large language models (LLMs) as evaluators in multidimensional machine translation (MT) assessment, focusing on the English–Indonesian language pair. Building on established evaluation frameworks, we adopt an MQM-aligned rubric that assesses translation quality along morphosyntactic, semantic, and pragmatic dimensions.

Three LLM-based translation systems (Qwen 3 (0.6B), LLaMA 3.2 (3B), and Gemma 3 (1B)) are evaluated using both expert human judgments and an LLM-based evaluator (GPT–5), enabling a detailed comparison of alignment, bias, and consistency between human and AI-based assessments. In addition, a classroom calibration study is conducted to examine how rubric-guided evaluation supports alignment among novice evaluators.

The results show that GPT–5 demonstrates strong agreement with human evaluators in terms of relative quality ranking, while systematic differences in absolute scoring reveal calibration challenges. Overall, this work highlights the potential of LLMs as reference-free evaluators for MT and demonstrates how multidimensional rubrics can support both research-oriented evaluation and pedagogical applications in a mid-resource language setting.

---

## ✨ What is inside this repo?

- **Jupyter notebooks** for MT evaluation and BLEU baseline analysis  
- **Human evaluation results** (CSV)  
- **GPT-based evaluation results** (CSV) for three open LLM translation systems  
- Materials that enable **reproducibility** and **extension** of the analysis

---

## 📌 Repository structure (current)

> This tree reflects the **actual directory structure** shown in the repository.

```text
.
├── Bleu_Evaluation.ipynb
├── MT_Evaluation.ipynb
├── README.md
├── gpt_evaluation_result_gemma3_1b_EN_ID_0_1*.csv
├── gpt_evaluation_result_llama3.2_3b_EN_ID_0_10*.csv
├── gpt_evaluation_result_qwen3_0.6b_EN_ID_0_10*.csv
└── human_evaluation_result.csv
```

**File descriptions**
- `Bleu_Evaluation.ipynb`  
  Notebook for BLEU-based baseline evaluation.
- `MT_Evaluation.ipynb`  
  Main notebook for MQM-aligned multidimensional evaluation analysis.
- `human_evaluation_result.csv`  
  Aggregated human expert scores (anonymized), used as the primary reference for analysis.
- `gpt_evaluation_result_*.csv`  
  GPT-based evaluator output scores for each model system:
  - **Gemma 3 (1B)**
  - **LLaMA 3.2 (3B)**
  - **Qwen 3 (0.6B)**

---

## 📊 Evaluation Framework

The evaluation follows an **MQM-aligned multidimensional rubric** with the following dimensions:

- **Morphosyntactic Quality**  
  Grammatical correctness, word order, and morphological accuracy.

- **Semantic Adequacy**  
  Faithfulness of meaning, completeness, and correctness of information transfer.

- **Pragmatic Appropriateness**  
  Naturalness, register, cultural appropriateness, and discourse-level coherence.

Each dimension is scored independently to allow fine-grained analysis and calibration.

---

## 🧪 Models Evaluated

- Qwen 3 (0.6B)  
- LLaMA 3.2 (3B)  
- Gemma 3 (1B)

Evaluation is conducted using expert human evaluators, GPT–5 as an LLM-based evaluator, and undergraduate students for classroom calibration.

---

## 🎓 Educational Use

This repository is suitable for classroom-based MT evaluation, rubric calibration exercises, and comparative analysis between human and LLM-based judgments.

---

## 📜 Citation

If you use this repository, please cite the associated MDPI article.

**BibTeX**
```bibtex
@article{nasution2026_beyondbleu,
AUTHOR = {Shalawati, Shalawati and Nasution, Arbi Haza and Monika, Winda and Derin, Tatum and Onan, Aytug and Murakami, Yohei},
TITLE = {Beyond BLEU: GPT–5, Human Judgment, and Classroom Validation for Multidimensional Machine Translation Evaluation},
JOURNAL = {Digital},
VOLUME = {6},
YEAR = {2026},
NUMBER = {1},
ARTICLE-NUMBER = {8},
URL = {https://www.mdpi.com/2673-6470/6/1/8},
ISSN = {2673-6470},
DOI = {10.3390/digital6010008}
}
```

**APA Style**
Shalawati, S., Nasution, A. H., Monika, W., Derin, T., Onan, A., & Murakami, Y. (2026). Beyond BLEU: GPT–5, Human Judgment, and Classroom Validation for Multidimensional Machine Translation Evaluation. Digital, 6(1), 8. https://doi.org/10.3390/digital6010008

## 📬 Contact

**Prof. Dr. Arbi Haza Nasution**  
Universitas Islam Riau  
Email: arbi@eng.uir.ac.id

---

## 📄 License

This repository is intended for academic and research use.
