# English-to-French Machine Translation with T5

Fine-tuned Google’s T5-small model on the OPUS Books dataset for English-to-French translation. Built using Hugging Face’s Transformers and Trainer API.

## 🧾 Results
- BLEU score improved from 0.038 to 0.061
- Validation loss reduced from 2.14 to 1.47 in 3 epochs

## 🛠 Tech Stack
- Hugging Face Transformers
- PyTorch
- Datasets
- BLEU scoring (evaluate)

## 📦 Features
- Prompt-based tokenization
- FP16 mixed precision training
- Custom compute metrics using `evaluate` BLEU

## 💬 Sample Translation
- Input: `translate English to French: I am Reza Mirjalili, PhD student.`
- Output: `Je suis Reza Mirjalili, étudiante au doctorat.`

## 📚 Dataset
- OPUS Books (English-French parallel corpus)

## 🧠 Next Steps
- Fine-tune on domain-specific corpora
- Extend to multilingual translation
