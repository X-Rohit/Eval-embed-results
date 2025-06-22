# 📊 Eval-Embed-Results

This repository presents the **evaluation results of fine-tuned language models** on the **ARMOR Embedded Systems dataset**. The goal is to assess the reasoning and response generation capabilities of small language models (SLMs) in the embedded systems domain after domain-specific fine-tuning.

---

## 📦 Dataset: [ARMOR (ARM Embedded Reasoning)](https://huggingface.co/datasets/PulkundwarP/ARMor)

**Description**:  
The ARMOR dataset is a specialized instruction-based dataset focused on **embedded systems**. It consists of two key columns:

- `input`: Context blocks of ~200 words derived from engineering **ebooks, research papers, PDFs, articles, and notes** related to embedded systems, ARM architecture, and microcontrollers.
- `description`: Human-curated summaries or explanations of the given context blocks.

This dataset serves as a **fine-tuning and evaluation benchmark** for educational and technical language model training in the embedded systems domain.

---

## 🧠 Fine-Tuning & Evaluation

### ✅ Fine-Tuned Models
The models were fine-tuned using Hugging Face Transformers on Google Colab with techniques such as:
- LoRA (Low-Rank Adaptation) for efficient training
- 8-bit quantization for memory optimization
- Instruction tuning using prompt-response format

The fine-tuned models are hosted on Hugging Face and optimized for embedded domain-specific queries.

### 🧪 Evaluation Dataset
The evaluation was performed using a **question-answer format dataset**, derived from academic assessments, MCQs, and conceptual tests related to ARM-based embedded systems.

Evaluation focused on:
- Instruction-following ability
- Technical accuracy
- Option selection capability (where applicable)

---

