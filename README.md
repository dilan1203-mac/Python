# Iris Dataset Classification with SVM
A machine learning experiment demonstrating classification on the Iris dataset using a Support Vector Machine (SVM). This project includes preprocessing, training, and checking the model.
# Getting Started
Follow these steps to install and run the project on your local PC for development and testing.
# Prerequisites
Make sure you have the required applications and libraries installed:
Python version 3.6 or  higher
Required Python libraries:
<li>numpy</li>
<li>pandas</li>
<li>matplotlib</li>
<li>scikit-learn</li>
<li>jupyter</li>
<hr/>
<text>*** Install these libraries using pip: ***</text>
<hr/>
Code : [ pip install numpy pandas matplotlib scikit-learn jupyter ]
<br/>
<hr/>

### Installing
Clone the repository on your local workplace:
```bash
git clone [https://github.com/your-username/svm-iris-classification.git](https://github.com/dilan1203-mac/Python/tree/main) 
```
<br/>
<hr/>

# Navigate to the project directory:
<li>[ cd svm-iris-classification ]</li>
<br/>
<hr/>
#Open the Jupyter Notebook
<li>[ jupyter notebook Week06-SVM-Example.ipynb ]</li>
<br/>
<hr/>

# Running the Tests
<br/>
1. Load and preprocess the Iris dataset:
  <li>The dataset is split into training (80%) and testing (20%) sets.</li>
  <li>Features are standardized using StandardScaler</li>
2. Train the SVM model:
  <li>A linear kernel is used for simplicity and effectiveness.</li>
3. Evaluate the model:
<li>Confusion matrices and classification reports are generated for detailed performance metrics</li>
<br/>
<hr/>

# Breakdown of Tests
<br/>
1. Data Preprocessing
<li>Standardizes features for better SVM performance.</li>
2. Model Training
<li>Trains an SVM classifier with the training data.</li>
3. Performance Metrics
<li>Calculates precision, recall, F1-score, and accuracy for all three classes (setosa, versicolor, virginica).</li>
<br/>
<hr/>

# Deployment
<br/>
This project is a demonstration and is not intended for deployment. For deployment, consider:
<li>Exporting the model using joblib or pickle.</li>
<li>Building a REST API with frameworks like Flask or FastAPI for predictions.</li>
<br/>
<hr/>

# <u>Author</u>
<br/>
GitHub: dilan1203-mac
<br/>
<hr/>

# License
This project is licensed under the MIT License.
<br/>
<hr/>

# Acknowledgement
<li>Dataset: The Iris dataset introduced by R.A. Fisher.</li>
<li>Tools: Built using Python </li>
<li>Inspiration: This project was inspired by academic and practical machine learning tutorials.</li>
