Fake News Detection
	This project involves developing models to detect fake news articles using various machine learning techniques. The models used include Deep Neural Networks, Support Vector Machines (SVM), and Ensemble methods (Random Forest). The project is implemented using Python and several libraries including scikit-learn, PyTorch, and nltk.

Project Structure
	Fake_News_Detection_DNN_SVM_Ensemble.ipynb: The main Jupyter Notebook containing all the code for data preprocessing, model training, evaluation, and testing.
	Datasets: This directory is supposed to contain the datasets used in this project. The datasets are too large to be stored on GitHub, so they are hosted on Google Drive.

Datasets
	Due to their large size, the datasets are hosted on Google Drive. Please download them from the link below:
	https://drive.google.com/file/d/1kClWEaFzwgBxRrgJP6-JYkR8Sv9V30nE/view?usp=sharing
	
	Once downloaded, place the extracted CSV files (stemmed_dataset1_40k.csv and
	stemmed_WELFake_70k.csv) in the Datasets/ directory within the project folder.

Project Workflow
	1. Data Preprocessing
	The dataset is preprocessed to remove noise and irrelevant information. The preprocessing steps include:
	- Removing URLs.
	- Converting text to lowercase.
	- Removing stopwords.
	- Stemming words.

	2. Model Training
	Three different models were trained on the preprocessed data:
	- Deep Neural Network (DNN): A multi-layer perceptron with dropout regularization.
	- Support Vector Machine (SVM): A linear SVM model.
	- Ensemble Method (Random Forest): A random forest ensemble model with bootstrapped sampling.

	3. Results
	For detailed results, including accuracy, precision, recall, and F1-score metrics for the various 
	models used in this project, as well as additional information, please refer to the full paper
	available via the Google Drive link below:
	https://drive.google.com/file/d/1uMsjUeO1GI4E-n8p22hN6CHvjil2QTLm/view?usp=sharing

How to Use
	To run this project, follow these steps:

	1. Clone the repository:
		git clone https://github.com/MonzerDev/Fake-News-Detection.git

	2. Navigate to the project directory:	
		cd Fake-News-Detection

	3. Install the required Python packages:
		pip install -r requirements.txt
	Note: You need to manually create a requirements.txt file if it's not already included.
	This file should list all the necessary Python packages.

	4. Download the datasets from the link provided above and extract them into the Datasets/ directory.

	5. Run the Jupyter Notebook to execute the code and reproduce the results:
		jupyter notebook Fake_News_Detection_DNN_SVM_Ensemble.ipynb

Contributing
	Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

Contact
	For any inquiries, please contact me at monzerkoukou@gmail.com
