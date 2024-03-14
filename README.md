# Hate-Speech-Detection-Thesis
This is the Hate Speech Detection task i did for my thesis in Computer Science and Informatics Department of University Of Patras


# Hate Speech Detection with DistilBERT - Running Instructions

This repository contains code for training a hate speech detection model using the DistilBERT architecture. The model is fine-tuned on a combination of datasets to effectively identify hate speech in textual data.

## Running the Code

### Google Colab

1. **Open in Google Colab**: Click on the "Open in Colab" badge at the top of the notebook to open the code in Google Colab.

2. **Runtime Type**: Ensure that the runtime type is set to "GPU" to leverage GPU acceleration for faster training. Go to `Runtime` -> `Change runtime type` and select `GPU` as the hardware accelerator.

3. **Execute Cells**: Execute each cell in the notebook sequentially by pressing `Shift + Enter` or clicking the play button on the left of each cell. Follow the prompts and wait for the execution to complete.

### Kaggle

1. **Open in Kaggle**: If you're on GitHub, click the "Open in Kaggle" button to import the notebook directly into a Kaggle kernel. If you're on Kaggle, create a new kernel and copy-paste the code into it.

2. **Add Dataset (if necessary)**: If the code relies on external datasets, ensure that they are available in the Kaggle dataset directory. You can add datasets by clicking on `+ Add Data` in the kernel editor.

3. **Enable GPU (if available)**: By default, Kaggle kernels come with GPU support. However, if it's disabled, you can enable it by navigating to `Settings` -> `Accelerator` -> `GPU`.

4. **Execute Code**: Execute each cell in the notebook sequentially by clicking the play button on the left of each cell. Follow the prompts and wait for the execution to complete.

## Requirements

Ensure that you have the following dependencies installed:

- Python 3.6+
- PyTorch
- Transformers library (Hugging Face)
- TensorFlow (for TensorFlow I/O)
- scikit-learn
- pandas
- numpy
- matplotlib
- tqdm
- spacy
- nltk
- imbalanced-learn
- datasets (Hugging Face)

You can install the required packages using the following command:

!pip install -r requirements.txt


## Notes

- The code provided in the notebook trains a hate speech detection model using the DistilBERT architecture. Ensure that you have sufficient computational resources (such as GPU) for training the model, especially if you're working with large datasets.
- Feel free to modify hyperparameters, adjust the dataset, or experiment with different preprocessing techniques to optimize the model's performance for your specific use case.
- For any questions or issues, please open an issue in the GitHub repository or contact the repository owner directly.



Model's Architecture:
![vPFDRjim48JlV8gv571kFLjraVedRG6dC2AxzmsriWXGf42k7AHFNz9oLLND6-GaSVVJpeoml8z2GVhMAZ5Y6Tz866N7h1jiMLYByGuFrh_e9e5APJuzbdjF5ROa55bYePQ7m5tmccESLZU-VJQEfwMoiqR60emJZsCWuq2kma-ofg8iMYXbQYo-7aum4NGXO-dPyXsaOOV5AySx1InFaP6P](https://github.com/nraptisss/Hate-Speech-Detection-Thesis/assets/104900174/65cb21b0-985a-4d8c-a60e-80caa86457f6)
