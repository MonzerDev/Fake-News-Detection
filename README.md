# Fake News Detection for Business Stability

This project implements a robust fake news detection system aimed at enhancing business stability by identifying and mitigating the spread of political misinformation. The system uses advanced machine learning models, including Support Vector Machines (SVM) and Random Forest, with optimized preprocessing techniques to ensure high accuracy and reliability.

---

## Project Structure

- **SVM_RF_CountVec_Dataset1.ipynb**: Implements SVM and Random Forest classifiers using CountVectorizer for Dataset1.
- **SVM_RF_CountVec_WELFAKE.ipynb**: Implements SVM and Random Forest classifiers using CountVectorizer for the WELFAKE dataset.
- **SVM_RF_TFIDF_Dataset1.ipynb**: Implements SVM and Random Forest classifiers using TF-IDF for Dataset1.
- **SVM_RF_TFIDF_WELFAKE.ipynb**: Implements SVM and Random Forest classifiers using TF-IDF for the WELFAKE dataset.

---

## How to Run the Project

### 1. Install Dependencies

Ensure Python is installed on your system. Install the required Python packages using:


```bash
pip install numpy pandas scikit-learn matplotlib
```

### 2. Download Datasets

The datasets used in this project are large and are hosted on Google Drive. Download them using the following link:

[Download Datasets](https://drive.google.com/file/d/127zwpZPnoWBx17vOKPgRC5rUcT1J01KQ/view?usp=sharing)

Ensure the datasets are placed in the appropriate directory before running the scripts.

### 3. Running the Models

Run the appropriate Jupyter notebooks to train and test the models:

- For SVM and Random Forest with CountVectorizer:
  - Dataset1: `SVM_RF_CountVec_Dataset1.ipynb`
  - WELFAKE: `SVM_RF_CountVec_WELFAKE.ipynb`

- For SVM and Random Forest with TF-IDF:
  - Dataset1: `SVM_RF_TFIDF_Dataset1.ipynb`
  - WELFAKE: `SVM_RF_TFIDF_WELFAKE.ipynb`

### 4. Training the Models (Optional)

To retrain the models from scratch, execute the respective notebooks and ensure the datasets are correctly preprocessed.

---

## How It Works

1. **Data Preprocessing:**
   - Large datasets are preprocessed using techniques such as text normalization, tokenization, and vectorization (CountVectorizer and TF-IDF).

2. **Model Training:**
   - Machine learning classifiers (SVM and Random Forest) are trained on the preprocessed datasets to learn patterns and detect fake news.

3. **Evaluation:**
   - The models are evaluated on separate test datasets using metrics such as accuracy, precision, recall, and F1-score.

4. **Results:**
   - The trained models achieve high performance, with precision, recall, and F1-scores exceeding 98% in most cases.

---

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## Notes

- The project focuses on political misinformation but can be extended to other domains.
- Ensure datasets are preprocessed and formatted correctly before training or testing the models.
- Pre-trained models and results can be accessed in the provided notebooks.

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

---

## Contact

For any questions or suggestions, feel free to contact me at [monzerkoukou@gmail.com](mailto:monzerkoukou@gmail.com).

