
# Advance Sign Language to Speech using Transformers

This project converts sign language gestures into speech using advanced transformer models. The provided Jupyter notebook runs on Google Colab and uses a custom dataset that can be downloaded from a specified website and stored in Google Drive.


## Prerequisites
To run this project, you will need:
- A Google account
- Access to Google Drive
- Google Colab
- The dataset (instructions on downloading are below)

## How to Run the Notebook

1. **Open the Notebook in Colab:**
   - Click the following link to open the notebook directly in Google Colab:  
     [Open the Colab Notebook](https://colab.research.google.com/drive/1oINQU0pUNZOnYaHMRNMFivQgw6jO2DCv?usp=sharing)

2. **Mount Your Google Drive:**
   - The notebook contains code to automatically mount your Google Drive. Just run the cell that contains:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

3. **Download the Dataset to Google Drive:**
   - You will need to download the dataset from the website see the [Dataset](https://data.mendeley.com/datasets/kcmpdxky7p/1) .
   - Save the dataset in your Google Drive in a specific folder (e.g., `MyDrive/sign_language_dataset/`). 

4. **Load the Dataset:**
   - The notebook will load the dataset from the specified folder on Google Drive. If you use the suggested folder structure (`/content/drive/MyDrive/sign_language_dataset/`), you **do not need to change anything**.
   - If you save the dataset in a different folder, update the dataset path in the notebook as needed.

## Dataset Download

To run the notebook, you must download the dataset from the following link:

[Dataset](https://data.mendeley.com/datasets/kcmpdxky7p/1) 

After downloading the dataset, either upload it manually to your Google Drive or use the code provided in the notebook to download it directly from the website into your Google Drive.

## Google Colab Notebook Link

[Open the Colab Notebook](https://colab.research.google.com/drive/1oINQU0pUNZOnYaHMRNMFivQgw6jO2DCv?usp=sharing)

## Installing Required Libraries

Before running the notebook, ensure that the required libraries are installed. These dependencies are listed in the `requirements.txt` file. To install them in your environment, run:

```bash
pip install -r requirements.txt







