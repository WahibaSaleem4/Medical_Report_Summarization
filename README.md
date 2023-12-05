# Medical_Report_Summarization
This repository contains a complete code of Fine-Tuning biobart model for summarization of Medical Reports.This model is a sequence-to-sequence model based on BioBart, specifically trained on a custom dataset comprising 70,000 radiology reports. Its primary function is to summarize radiology findings into concise impressions. The training process utilized the 70,000 reports to teach the model how to generate impressions effectively.

![Colorful Minimalist Linear Steps Circular Infographic](https://github.com/WahibaSaleem4/Medical_Report_Summarization/assets/111902250/c93531ed-a5c4-461b-9e0b-4684911a5679)

## Usage

Designed exclusively for generating radiology impressions, this model should not be employed for any other purposes. Users can input radiology findings, and the model will produce a summarized impression based on that information. It is crucial to refrain from utilizing the model for tasks outside the realm of radiology report summarization.

## Getting Started with the Model

To commence using the model, refer to the provided code below:


![code](https://github.com/WahibaSaleem4/Medical_Report_Summarization/assets/111902250/4ed27596-18f3-427d-b631-1844458c1b5f)

## Training Details

### Training Data

The training dataset comprised 70,000 radiology reports, meticulously cleaned to eliminate any personal or confidential information. Tokenization and normalization were also applied. The dataset was divided into a training set (63,000 reports) and a validation set (7,000 reports).

### Training Procedure

The model underwent training using the Hugging Face Transformers library, employing the AdamW optimizer with a learning rate of 5.6e-5, over a span of 10 epochs.

### Training Hyperparameters

![Hyperparameters](https://github.com/hamza4344/biobart_summarization/assets/62426973/c2c23b1a-c37b-419e-a372-f3577bd3771b)

## Evaluation

### Testing Data

The testing data set consisted of 10,000 radiology reports.

### Factors Evaluated

The evaluation considered the following factors: 
- ROUGE-1
- ROUGE-2
- ROUGE-L
- ROUGELSUM

### Metrics Used

Metrics employed for evaluation included:
- ROUGE-1 score: 44.857
- ROUGE-2 score: 29.015
- ROUGE-L score: 42.032
- ROUGELSUM score: 42.038


### Results

The model demonstrated a ROUGE-L score of 42.032 on the testing data, indicating its ability to generate summaries closely resembling human-written summaries.

## Author Details

- **Developed by:** Wahiba Saleem
- **Demo:** [WahibaSaleem/medical_report_summarizer]
- **LinkedIn:** [Wahiba Saleem](https://www.linkedin.com/in/wahiba-saleem-52b14a233/)
- **HuggingFace:** [WahibaSaleem](https://huggingface.co/WahibaSaleem)
