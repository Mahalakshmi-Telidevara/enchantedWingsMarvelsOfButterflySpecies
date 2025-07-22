# 🦋 Enchanted Wings Marvels Of Butterfly Species

This project focuses on classifying butterfly species using a Convolutional Neural Network (CNN). The model is trained on labeled butterfly images and can predict the species of a butterfly from an uploaded image.

---

## 📥 Dataset

Download the dataset from the following link:  
👉 **[Download Dataset](https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification)**

---

## 📂 Upload Datasets to Colab

Once you have the dataset:
1. Go to [Google Colab](https://colab.research.google.com/)
2. Upload the following files and folders:
   - `Training_set.csv`
   - `Testing_set.csv`
   - `train/` folder (contains training images)
   - `test/` folder (contains testing images)

You can upload folders by zipping them first and using:

```python
from google.colab import files
uploaded = files.upload()  # Select your zipped files
import zipfile

with zipfile.ZipFile("your_zipped_file.zip", 'r') as zip_ref:
    zip_ref.extractall("extracted_folder_name")
```
## ▶️ Run the Notebook

  - Open the butterfly_classification.ipynb file in Colab.
  - Run each cell sequentially to:
      ~ Load and preprocess the dataset
      ~ Build and train the CNN model
      ~ Evaluate model performance
      ~ Make predictions on test images
## 📁 Project Structure

├── train/                          # Training images
├── test/                           # Testing images
├── Training_set.csv                # Training labels
├── Testing_set.csv                 # Testing labels
├── butterfly_classification.ipynb  # CNN model notebook

## 📧 Contact
Feel free to contact me for any questions, suggestions, or collaboration opportunities:
👩‍💻 Name: Telidevara S V S Kanaka Mahalakshmi
📩 Mail ID: srikanakamahalakshmitelidevara@gmail.com

