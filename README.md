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

## 📁 Repository Contents

```
.
├── rubric/
│   └── MQM_multidimensional_rubric.pdf
├── data/
│   ├── human_scores_anonymized.csv
│   ├── gpt5_scores.csv
│   └── student_evaluation_data.csv
├── analysis/
│   ├── agreement_analysis.py
│   ├── correlation_plots.ipynb
│   └── statistical_tests.py
├── results/
│   ├── figures/
│   └── tables/
└── README.md
```

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

## 🔁 Reproducibility

1. Clone the repository:
```bash
git clone https://github.com/arbihazanst/multidimentional-MT-Eval.git
cd multidimentional-MT-Eval
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run analysis:
```bash
python analysis/agreement_analysis.py
```

---

## 📂 Data Availability

The data supporting the findings of this study are openly available in this repository and include the evaluation rubric, anonymized scoring data, analysis scripts, and reproduction instructions.

Accessed on: 12 January 2026.

---

## 🎓 Educational Use

This repository is suitable for classroom-based MT evaluation, rubric calibration exercises, and comparative analysis between human and LLM-based judgments.

---

## 📜 Citation

If you use this repository, please cite the associated MDPI article.

Shalawati, S., Nasution, A. H., Monika, W., Derin, T., Onan, A., & Murakami, Y. (2026). Beyond BLEU: GPT–5, Human Judgment, and Classroom Validation for Multidimensional Machine Translation Evaluation. Digital, 6(1), 8. https://doi.org/10.3390/digital6010008
---

## 📬 Contact

**Prof. Dr. Arbi Haza Nasution**  
Universitas Islam Riau  
Email: arbi@eng.uir.ac.id

---

## 📄 License

This repository is intended for academic and research use.
