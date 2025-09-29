
# BLP Task 2: Dataset and Model Files

This repository contains the code and dataset for **BLP Task 2**, which includes datasets for training and testing, model files for various LLMs, preprocessing scripts, and scoring files.

## Project Structure

The repository contains the following main directories and files:

```
BLP TASK 2/
│
├── Datasets/
│   ├── Custom/
│   │   ├── dev_translated.xlsx
│   │   ├── dev_translated_generated_with_assert.xlsx
│   │   ├── test_translated.xlsx
│   │   ├── trial_translated.csv
│   │
│   ├── Original/
│       ├── dev.csv
│       ├── test.csv
│       ├── trial.csv
│
├── Models/
│   ├── Opensource Models/
│   │   ├── deepseek-prompt.ipynb
│   │   ├── Deepseek.ipynb
│   │   ├── Llama.ipynb
│   │   ├── Tiger_LLM.ipynb
│   │
│   ├── Paid Models/
│   │   ├── Paid_Model.ipynb
│   │
│   ├── Preprocessing/
│   │   ├── Generated_Human_Annotation.ipynb
│   │
│   └── Scorer/
│       ├── Scorer.ipynb
```

## Datasets

### **Custom Datasets**
These are translated versions of the original datasets used for the task:
- `dev_translated.xlsx`: Development dataset (translated)
- `dev_translated_generated_with_assert.xlsx`: Development dataset with assertions (translated)
- `test_translated.xlsx`: Test dataset (translated)
- `trial_translated.csv`: Trial dataset (translated)

### **Original Datasets**
These are the original versions of the datasets:
- `dev.csv`: Development dataset (original)
- `test.csv`: Test dataset (original)
- `trial.csv`: Trial dataset (original)

## Models

### **Opensource Models**
These are models based on open-source LLMs:
- `deepseek-prompt.ipynb`: Notebook for DeepSeek prompt generation
- `Deepseek.ipynb`: Notebook for training or inference with the DeepSeek model
- `Llama.ipynb`: Notebook for using the Llama model
- `Tiger_LLM.ipynb`: Notebook for using the Tiger LLM model

### **Paid Models**
This section contains notebooks for paid models:
- `Paid_Model.ipynb`: Notebook for using a paid model

### **Preprocessing**
This section contains preprocessing scripts:
- `Generated_Human_Annotation.ipynb`: Notebook for generating human annotations

### **Scorer**
This section contains the scoring script:
- `Scorer.ipynb`: Notebook for scoring model predictions

## Setup

To get started, you need to have the following dependencies:

- Python 3.x
- Jupyter Notebook (for running the `.ipynb` files)
- Required libraries: `pandas`, `numpy`, `sklearn`, etc.

You can install the required libraries using `pip`:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```bash
git clone <repo_url>
cd BLP TASK 2
```

2. Run the Jupyter notebooks for training, inference, or scoring.

For example, to use the Deepseek model:

```bash
jupyter notebook Models/Opensource Models/Deepseek.ipynb
```

3. Add or modify models and datasets as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
