# Linguagem Natural: NLP com Análise de Sentimento

This repository contains a project focused on Natural Language Processing (NLP) to perform sentiment analysis on movie reviews. The dataset used consists of 49,459 user reviews that can be either positive or negative. The goal of this project is to create an NLP model that identifies whether a review is positive or negative.

## Project Overview

### Initial Approach
- **Model:** Logistic Regression
- **Accuracy:** Approximately 65% (without preprocessing)

### Improved Approach
- **Preprocessing with NLTK:**
  - Removal of stopwords
  - Removal of punctuation
  - Stemming: Converting words to their root form (e.g., "correr" and "corrida" to "corr")
- **TF-IDF Vectorization:**
  - Normalizes and considers term frequency to classify relevance
  - Applied with and without n-grams (considering word pairs)
- **Final Accuracy:** Approximately 88%

## Course Details
This project was completed as part of the 'Advanced Machine Learning' course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-machine-learning-avancada).

## Objectives Achieved
- Learn fundamental concepts of Natural Language Processing (NLP).
- Perform automated Sentiment Analysis.
- Develop an architecture for sentiment classification.
- Create visualizations to facilitate the analysis of textual data.
- Start using NLTK, one of the main Python libraries for NLP.
- Learn best practices for NLP.

## Technologies Used
- Python
- Jupyter Notebook
- NLTK
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

## Project Structure
The directory structure of the project is as follows:
```
linguagem-natural-nlp-com-análise-de-sentimento/
│   database-project-05-small.csv
│   project-05.ipynb
│   README.md
```
**Note:** The original dataset has been replaced with a smaller dataset named `database-project-05-small.csv` to comply with GitHub's file size limitations.

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/linguagem-natural-nlp-com-analise-de-sentimento.git
   ```
2. Navigate to the project directory:
   ```sh
   cd linguagem-natural-nlp-com-analise-de-sentimento
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install the required libraries:
   ```sh
   pip install matplotlib numpy pandas seaborn wordcloud scikit-learn nltk
   ```
5. Download additional NLTK data (if not already done):
   ```python
   import nltk
   nltk.download('all')  # Uncomment and run this in the notebook if needed
   ```

## Running the Notebook
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run the `project-05.ipynb` notebook to see the analysis and sentiment classification in action.

## Language
The language used in this project is Brazilian Portuguese (pt-br).

## Author
GitHub Username: [goosekiing](https://github.com/goosekiing)
