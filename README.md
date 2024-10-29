# CSE 5243 HW3
## Folder Structure
```
├─src
│  ├─hw3.ipynb
│  ├─requirements.txt       
│  ├─imdb_labelled.txt                            
│  ├─amazon_labelled.txt   
│  ├─imdb_labelled.txt          
│  └─yelp_labelled.txt         
└─README.md
```
## How to Run
### 1. Virtual Environment
#### Create a Virtual Environment
```
python3 -m venv env # Linux/Mac
python -m venv env # Windows
```
#### Activate the Virtual Environment
```
source env/bin/activate # Linux/Mac
env\Scripts\activate # Windows - Command Prompt
.\env\Scripts\Activate # Windows - PowerShell
```
#### Deactivate the Environment
```
deactivate
```
### 2. Installation
```
pip install -r requirements.txt
```
### 3a. Using Jupyter Notebook
1. Navigate to the directory where .ipynb file is located.
2. Run the following command:
```
jupyter notebook
```
3. A browser window should open with the Jupyter interface. You can then open your .ipynb file from there.
### 3b. Using Google Colab (Online)
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click on "File" → "Upload notebook" and upload your .ipynb file.
3. Google Colab will open your notebook, and you can run it there.
## How to Interpret Output
There are two parts in hw3.ipynb: HW#2 and HW#3. HW#3 part is dependent on HW#2 part.
### HW#2
#### Output of Cell 2: 
- Number of sentences.
- A sample of processed sentence & label pair.
#### Output of Cell 3:
- Size of word to number table (this table maps each seen word to a distinct integer).
- 5 samples of word & number pair.
#### Output of Cell 4:
- Number of rows and columns.
- First 20 entries in the first row of the matrix.
### HW#3
#### Output of Cell 5:
- num2word's size (num2word is a dictionary that maps encoded values of words to original words).
- First 5 entries in num2word.
#### Output of Cell 6:
- First 5 column sums in D (get frequencies of each word).
#### Output of Cell 7:
- 5 stop words.
#### Output of Cell 8:
- Number of words after removing stop words.
- First 5 words in filtered_words.
#### Output of Cell 9:
- Top 5 most frequent words (stop words excluded).
#### Output of Cell 10:
- Show first 5 features after sorting.
#### Output of Cell 11:
- x.shape (D but no stop words).
- x_reduced.shape (D but no stop words and feature selection applied).
#### Output of Cell 12:
- Number of labels.
- First 5 labels.
#### Output of Cell 13:
- Shapes of labels, training data, validation data, and testing data with and without feature selection
#### Output of Cell 14:
- Performance of decision tree classifier on training/validation data with and without feature selection.
#### Output of Cell 15:
- Performance of decision tree classifier on testing data with and without feature selection.
#### Output of Cell 16:
- Performance of KNN classifier provided by scikit-learn on training/validation data with and without feature selection.
#### Output of Cell 17:
- Performance of KNN classifier provided by scikit-learn on testing data with and without feature selection.
#### Output of Cell 18:
- Performance of KNN classifier implemented by myself on training/validation data with and without feature selection.
#### Output of Cell 19:
- Performance of KNN classifier implemented by myself on testing data with and without feature selection.