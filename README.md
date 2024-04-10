# NMT-Master-Thesis

This is a repository that contains all steps that support the Master thesis Neural Machine Translator for Low-Resource Languages Croatian and Dutch

The structure of this repository follows the structure of the Master thesis, so it has Data gathering and cleaning, Evaluation of pretrained multilingual models, and lastly, Fine tuning of those multilingual models first on public and then on dictionary dataset.

.

├── Data_gathering_and_cleaning

│   ├── Data_Analysis_of_Public_and_Evaluation_Dataset.ipynb

│   ├── Data_Cleaning.ipynb

│   ├── Data_Gathering.ipynb

│   └── Evaluation_dataset.ipynb

├── Evaluation_of_pretrained_multilingual_models

│   ├── m2m100_418M_evaluation_1.ipynb

│   ├── mbart50_large_evaluation_1.ipynb

│   └── nllb200_distilled_600m_evaluation_1.ipynb

├── Fine-tuning_Dictionary_dataset

│   ├── m2m100

│   │   ├── m2m100_2_hr_nl.ipynb

│   │   └── m2m100_2_nl_hr.ipynb

│   ├── mbart50_large

│   │   ├── mbart50_large_hr_nl_2.ipynb

│   │   └── mbart50_large_nl_hr_2.ipynb

│   └── nllb200

│       ├── nllb200_2_hr_nl.ipynb

│       └── nllb200_2_nl_hr.ipynb

├── Fine-tuning_Public_dataset

│   ├── m2m100

│   │   ├── m2m100_1_hr_nl_evaluation.ipynb

│   │   ├── m2m100_1_nl_hr_evaluation.ipynb

│   │   ├── m2m100_hr_nl.ipynb

│   │   └── m2m100_nl_hr.ipynb

│   ├── mbart50_large

│   │   ├── mbart50_1_hr_nl_evaluation.ipynb

│   │   ├── mbart50_1_nl_hr_evaluation.ipynb

│   │   ├── mbart50_large_hr_nl.ipynb

│   │   └── mbart50_large_nl_hr.ipynb

│   └── nllb200

│       ├── nllb200_1_hr_nl_evaluation.ipynb

│       ├── nllb200_1_nl_hr_evaluation.ipynb

│       ├── nllb200_hr_nl.ipynb

│       └── nllb200_nl_hr.ipynb

├── Post_fine-tuning_analysis

│   ├── Post_training_analysis.ipynb

│   └── t_test_post_analysis.ipynb

└── README.md

Notebooks in the Fine-tuning_Public_dataset folder contain separate notebooks for training (fine-tuning) and evaluation of the model. In the Fine-tuning_Dictionary_dataset folder, notebooks contain both training (fine-tuning) of the model and evaluation in one notebook.
