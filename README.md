## Sinhala QA/MRC 

This repository contains:

- **Scripts for training and evaluating Sinhala fine-tuned models** on QA tasks.
- A `data/` folder with the **Sinhala QA datasets**, including training, validation, and test sets used for model development and benchmarking.
- 📦 The translated dataset used for training is publicly available on Hugging Face: [SiQuAD](https://huggingface.co/datasets/janani-rane/SiQuAD)


## Related Repositories

Below are key companion repositories used in this workflow:

### [QA Annotator](https://github.com/j-ranasinghe/qa_annotator)

- Tool developed for **manually annotating QA pairs** in Sinhala.
- Used to create the **Sinhala QA test set** for evaluation.
- Supports context selection, question writing, and answer span marking.

### [SQuAD Translation](https://github.com/j-ranasinghe/SQuAD-Translation)

- Scripts and pipeline used for **translating the SQuAD dataset into Sinhala**.
- Includes preprocessing, automatic translation, post-editing, and alignment verification steps.

### [Web Scraping News Articles](https://github.com/j-ranasinghe/Web-Scraping-News-Articles)

- Contains scripts for **scraping Sinhala news articles**.
- Data gathered was used to **build a seed context dataset** to support Sinhala QA development and fine-tuning of models
- 📦 The full dataset used for training is publicly available on Hugging Face: [Sinhala-News-Wiki-text-corpus](https://huggingface.co/datasets/janani-rane/Sinhala-News-Wiki-text-corpus)



