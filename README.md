# Vidsum
1.Hugging Face Transformers Integration:
Utilization of Hugging Face Transformers for seamless integration with Flan-T5.
Tokenization and data collation for the language model.
Fine-Tuning Flan-T5:

2.Selection of a specific dataset (e.g., Yahoo Answers QA) for fine-tuning Flan-T5.
Implementation of Seq2Seq training with specified parameters.
Evaluation Metrics:

3.Incorporation of ROUGE score for evaluating the summarization performance.
Use of NLTK for sentence tokenization.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Getting Started

Step - 1 : Create an virtual environment 
# 1: Install virtualenv (if not already installed) : 
Open your terminal or command prompt and run the following command to install virtualenv:
-- pip install virtualenv


# 2: Create a Virtual Environment
On Windows:
-- python -m venv venv
On macOS/Linux:
-- python3 -m venv venv
Here, venv is the name of the virtual environment. You can choose a different name if you prefer.


# 3: Activate the Virtual Environment
On Windows:
-- venv\Scripts\activate
On macOS/Linux:
-- source venv/bin/activate



### Prerequisites

Import the models from the Hugging face
# importing the model.
-- git lfs install
-- git clone https://huggingface.co/MBZUAI/LaMini-Flan-T5-248M
or
-- If you want use the Finetuned Model specially descripted 
   over the prompt description and summary :  
   -- git clone https://huggingface.co/irahnarach/flan-t5-base-samsum

Step - 3 :
-- pip install -r requirement.txt





























