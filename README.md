# Waste Classification Using AI 

Our project classifies waste images into categories such as plastic, paper, metal, and glass using a Convolutional Neural Network (CNN). The goal is to improve recycling efficiency and reduce environmental impact by automating waste sorting. The system is developed using Python, TensorFlow/Keras, and Jupyter Notebook.
This project supports the UN Sustainable Development Goal 12 (Responsible Consumption and Production)

# Dataset information 
The dataset contains labeled images of plastic, paper, metal, and glass.  
Images are organized into folders by category and loaded during preprocessing.

Dataset reference:  
https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification

# How to Connect Kaggle Dataset in Google Colab
1. Create the Kaggle API Token from your Kaggle account
2. Upload the token file to Google Drive, then mount Drive in Google Colab
3. Install the Kaggle library in Colab and configure the environment by placing kaggle.json in the required directory
4. Download the dataset using the command: kaggle datasets download <sataset-identifier>
5. Unzip the downloaded file and load the data into your notebook for analysis

   
## Requirements
- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow

# How to run the model 
1. Install the required Python libraries:
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn pillow
```
2. Open the Jupyter Notebook:
```bash
jupyter notebook
```
3. Open the file Waste_Classification.ipynb.

4. Run all cells in order:
	-	Data loading
	-	Preprocessing
	-	Model training (CNN)
	-	Model evaluation (accuracy + confusion matrix)

5. Test the model by uploading an image in the notebook’s testing cell.

# Output
<img width="626" height="336" alt="Screenshot 2025-11-13 at 9 50 53 PM" src="https://github.com/user-attachments/assets/22e83a9c-bde8-4bea-b540-2a2b4caecc7b" />
