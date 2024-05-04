# # NLP-Lab2

# 🎋 Intro:
Lab 2 focuses on NLP Rule-based, Regex, and NLP Word Embedding techniques. In the first part, a Python code utilizing Regex is implemented to generate a bill from user-provided text. The second part involves the application of various word embedding techniques on a dataset collected during Lab 1.

📦 Tech Stack:
Python
Regex
NLTK
Sklearn
Google Colab or Kaggle
GitLab/GitHub

# 👩🏽‍🍳 Features:
Part 1: Rule-Based NLP and Regex:
Utilizes Regex to parse user-provided text and generate a bill.
Extracts product names, quantities, and prices from the text.
Generates a formatted bill displaying product details and total prices.
Emphasizes preprocessing to enhance accuracy, including tokenization and removal of stopwords.
Implements additional cleaning steps to exclude non-essential words such as measurements and product adjectives.
Focuses on improving the calculation of total prices by applying logical rules to handle cases like fractions of kilograms and additional product attributes.

Part 2: Word Embedding:
Applies one-hot encoding, bag of words, and TF-IDF techniques on the dataset collected during Lab 1.
Implements Word2Vec (Skip Gram, CBOW), GloVe, and FastText approaches on the same dataset.
Utilizes t-SNE algorithm to visualize the encoded/vectorized vectors.
Evaluates the effectiveness of each approach and provides a general conclusion.

# 💭 Process:
The lab began with understanding the objectives and requirements of both parts. In the first part, we implemented a Python script using Regex to extract relevant information from user-provided text and generate a bill. The experience involved experimenting with various Regex patterns to accurately parse the text. In the second part, we applied different word embedding techniques such as one-hot encoding, bag of words, TF-IDF, Word2Vec (Skip Gram, CBOW), GloVe, and FastText on the dataset collected during Lab 1. Each technique was implemented and evaluated for its effectiveness in capturing semantic relationships between words. Overall, the lab provided valuable insights into NLP techniques and their applications.

# 📚 Learnings:
Enhanced understanding of Regex and its application in text processing.
Gained practical experience in implementing various word embedding techniques.
Learned to evaluate and compare different word embedding approaches based on their performance and suitability for the given dataset.

# ✨ Improvement:
Further optimization of preprocessing techniques to handle complex text structures and edge cases.
Enhance the calculation of total prices by implementing logic to handle fractions of kilograms, grams, and other measurement units.
Refine the bill generation process to incorporate rules for handling additional product attributes, such as size variations and special pricing scenarios.
Experimentation with different hyperparameters and configurations for word embedding models to improve performance.
Exploration of additional word embedding techniques and algorithms to expand knowledge in NLP.

# 🚦 Running the Project:
Clone the project repository from GitHub.
Ensure all required libraries and dependencies are installed.
Run the Python script for Part 1 to generate bills using Regex.
Execute the code for Part 2 to apply word embedding techniques and visualize the results.


#📸 Images:


🎋 Intro:
This project focuses on two main components: Rule-based NLP and Word Embedding techniques. The first part involves generating a bill from a given text using regular expressions. The second part explores various text encoding techniques and visualizes their embeddings using t-SNE.

📦 Tech Stack:

Python
NLTK
Gensim
scikit-learn
Matplotlib
👩🏽‍🍳 Features:

Rule-Based NLP (Part 1):
Generates a bill from a given text using regular expressions.
Preprocesses the text by removing stopwords, product adjectives, and measurement units.
Extracts quantity, product name, and price information.
Calculates the total price for each item in the bill.


Word Embedding (Part 2):
Applies one-hot encoding, bag of words, and TF-IDF techniques on the dataset.
Trains Word2Vec, GloVe, and FastText models on the same dataset.
Visualizes the encoded/vectorized vectors using t-SNE.
💭 Process:

Part 1 (Rule-Based NLP):
Focused on preprocessing to ensure accurate bill generation.
Implemented logic to remove stopwords, product adjectives, and measurement units from the text.
Identified potential improvements in handling fractions and special pricing scenarios.
Part 2 (Word Embedding):
Utilized various text encoding techniques such as one-hot encoding, bag of words, and TF-IDF.
Trained Word2Vec, GloVe, and FastText models on the dataset.
Applied t-SNE to visualize the encoded vectors and evaluate their performance.

📚 Learnings:
Enhanced understanding of Regex and its application in text processing.
Enhanced understanding of rule-based NLP techniques, including preprocessing and regular expressions.
Explored different text encoding methods and their applications in NLP tasks.
Gained insights into training and visualizing word embedding models.

✨ Improvement:
Further optimize preprocessing techniques for handling complex text structures and edge cases.
Enhance the calculation of total prices by incorporating logic to handle fractions and additional product attributes.
Refine the bill generation process to handle special pricing scenarios more effectively.
Experimentation with different hyperparameters and configurations for word embedding models to improve performance.
Exploration of additional word embedding techniques and algorithms to expand knowledge in NLP.

🚦 Running the Project:
Clone the repository.
Ensure the required libraries are installed (NLTK, Gensim, scikit-learn, Matplotlib).
Execute each Jupyter Notebook file (Part1_Bill_Generation.ipynb, Part2_Word_Embedding.ipynb).
Ensure dataset.json is present in the project directory.

📸 Video or Image:






