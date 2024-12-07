<!-- PROJECT TITLE -->
<h1 align="center">Email Spam Detection</h1>

<!-- PROJECT DESCRIPTION -->
## <br>**➲ Project description**
An email spam detection system identifies spam emails using a machine learning technique known as natural language processing, implemented in Python. We have a dataset containing numerous emails, and by extracting key words, we can utilize a naive classifier to determine whether an email is spam or not.

<!-- PREREQUISTIES -->
## <br>**➲ Prerequisites**
This is list of required packages and modules for the project to be installed :
* <a href="https://www.python.org/downloads/" target="_blank">Python 3.x</a>
* Pandas 
* Numpy
* Scikit-learn
* NLTK

Install all required packages :
 ```sh
  pip install -r requirements.txt
  ```

<!-- THE DATASET -->
## <br>**➲ The Dataset**
The human activities dataset contains about 5728 records, a sample of an email, and a target column "spam" which describes the state of email spam.<br>

<!-- CODING SECTIONS -->
## <br>**➲ Coding Sections**
In this part we will see the project code divided into sections as follows:
<br>

- Section 1 | The Data :<br>
In this section we aim to do some operations on the dataset before training the model on it,
processes like :
  1. Data Loading: Load the dataset
  2. Data Visualization: Visualize dataset features
  3. Data Cleaning: Remove stopwords and duplicates values
  4. Data Splitting: Split the dataset into training and testing sets<br><br>

- Section 2 | The Model :<br>
The dataset is ready for training, so we create a naive classifier using sci-kit-learn and thin-fit it to the data, and finally, we evaluate the model by getting accuracy, classification report and confusion matrix<br>

<!-- INSTALLATION -->
## ➲ Installation
1. Clone the repo
   ```sh
   git clone https://github.com/omaarelsherif/Email-Spam-Detection-Using-Machine-Learning.git
   ```
2. Open 'main. ipynb' in Google Colab or VScode and enjoy

<!-- REFERENCES -->
## <br>**➲ References**
These links may help you to a better understanding of the project idea and techniques used :
1. Spam detection in machine learning: https://bit.ly/3nwiKtA
2. Naive-Bayes algorithm: https://bit.ly/3zc9SLH
3. Model evaluation: https://bit.ly/3B12VOO
