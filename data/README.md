# GRIT Dataset Contents

This folder contains key components of the GRIT dataset, prepared to ensure our fine-tuning results are fully reproducible. Below are the contents and their descriptions:

- **`grit.jsonl`**: The original dataset containing annotated documents. This file serves as the foundational resource for group reference recognition studies within the GRIT project.

- **`segmented_sentences_less_sparse.pkl`**: Derived from `grit.jsonl`, this file contains the dataset segmented into individual sentences, preserving the original annotations of group references.

- **`segmented_sentences_less_sparse_short.pkl`**: Also derived from `grit.jsonl`, this version of the dataset is segmented into individual sentences with initial function words removed from the group references. For more detailed information, refer to Section 4, Paragraph "Data Selection and Preprocessing" in the paper.

