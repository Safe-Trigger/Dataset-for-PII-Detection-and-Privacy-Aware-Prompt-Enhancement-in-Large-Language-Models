# Dataset-for-PII-Detection-and-Privacy-Aware-Prompt-Enhancement-in-Large-Language-Models

The privacy awareness prompt enhancement dataset is designed to identify, classify, and remove the PII data present in user prompts for LLM applications. It further provides an improved, privacy-safe prompt version with enhanced responsible AI interactions. Synthetic Data as a key enabler for fair and privacy-preserving AI research. A significant advantage of the proposed dataset is the extensive use of synthetically generated prompts, representing 75% of all records. There are two files in the dataset, one for training and the other for testing. 

## Dataset Content

There are two dataset files for training and testing purposes. Formally, the dataset presents both CSV and Excel file formats. Sample raw data in both table and CSV format is shown in Table I and Figure 1 in the accompanying paper.

Each categorization includes 2,000 samples, where 1,000 samples are for anonymization, while 1,000 serve as clean reference prompts. This structure ensures a balanced dataset suitable for both binary classification (PII vs non-PII) and multi-class anonymization analysis.

## Columns Description

| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Original           | The original user prompt for LLM.                                           |
| Need Anonymization | Indicates if the prompt contains PII requiring anonymization (YES/NO).      |
| Detect PII Values  | The detected PII values of the prompt with type (age, gender, etc.) in JSON format. |
| Improved Prompt     | The suggested improved prompt excluding sensitive information while preserving meaning. |

- The dataset presents 5,000 prompts that need anonymization and 5,000 prompts that do not.
- The detected PII values show types and exact values using JSON object notation.
- Anonymization techniques employed include generalization, pseudonymization, and masking, either individually or in combination.

## Usage

This dataset can be used for developing and evaluating privacy-preserving anonymization techniques on user prompts for LLMs. The improved prompts are designed to exclude sensitive information without damaging the original prompt meaning.

## License

[Specify your license here]

## Citation

Please cite the accompanying research paper when using this dataset.
