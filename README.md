# Histopathology Classifier (Project 1)
Our project will involve developing a machine learning system that will classify histopathology images of cancerous cells.

Our dataset is based on an existing dataset, 'CRCHistoPhenotypes', and consists of 27x27 RGB images of cells.

**How to Run:**

Though this application is achievable through local Jupyter Notebook, it was more intuitive to use Google Colaboratory for a shared ML project.

- Place the `image_classification_data.zip` file in your Google Drive Folder
- Open our Application and Run all. Our application will then mount your Google Drive folder, take this `.zip` file and extract its contents into a local folder.
- Once this is done, your local Google Colab Runtime Environment will have access to `patch_images`, `data_labels_extraData.csv`, `data_labels_mainData.csv`

Alternatively a local Jupyter Notebook can be used

- Place the `image_classification_data.zip` file in the same directory as the .ipynb file.
- Ignore the Google Colab Import commands, and run from the second cell which executes unzipping from your local directory

**Dataset:**

`K. Sirinukunwattana, S. E. A. Raza, Y. Tsang, D. R. J. Snead, I. A. Cree and N. M. Rajpoot,”Locality Sensitive Deep Learning for Detection and Classification of Nuclei in Routine Colon Cancer Histology Images,” in IEEE Transactions on Medical Imaging, vol. 35, no. 5, pp. 1196-1206, May 2016, doi: 10.1109/TMI.2016.2525803.`

**Our project will perform two tasks using this dataset:**
- Classify whether a given cell image represents cancerous cells
- Classify the type of cell shown in a given cell image 

### Team 101 - Members:
- Sofya Filippova
- Mitchell Gust
