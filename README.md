# NLP Topic Modelling
Uncovering Hidden Themes in Text Data Using Topic Modeling and Dependency Parsing

## Project Background:

In this self-initiated project, I aim to explore and analyze a large textual dataset using advanced natural language processing (NLP) techniques. The goal is to extract meaningful topics from the dataset, understand the structure of sentences, and gain deeper insights into the underlying patterns in the text.

As part of this initiative, I will be using topic modeling, specifically Latent Dirichlet Allocation (LDA), to identify hidden themes within the dataset. Additionally, I will implement dependency parsing to analyze the grammatical structure of sentences, providing a comprehensive linguistic view of the text.

## Project Objectives:

1. **Dataset Exploration and Preprocessing:**
   - Perform an in-depth exploratory data analysis (EDA) to understand the dataset and clean the data.
   - Preprocess the textual data by handling missing values, removing noise, and preparing it for modeling.
   
2. **Topic Modeling using LDA:**
   - Use the Latent Dirichlet Allocation (LDA) algorithm to uncover at least 10 distinct topics within the dataset's text.
   - Focus on the **Title** column to generate meaningful topics.

3. **Evaluation with Coherence Score:**
   - Compute the coherence score to evaluate the quality of the topics extracted by LDA.
   - Print and analyze the extracted topics based on coherence to determine the most meaningful ones.

4. **Topic Visualization:**
   - Visualize the topics generated through LDA using tools such as word clouds or distribution plots.
   - Use these visualizations to understand the key themes within the data.

5. **Dependency Parsing:**
   - Perform dependency parsing on two randomly selected sentences (with a minimum of 10 words) from the dataset.
   - Visualize the syntactic structure of these sentences to demonstrate the relationships between words.

## Approach & Methodology:

1. **Data Selection and Preparation:**
   - The dataset is sourced from a Google Drive link, and I will focus on the first 5,000 rows to ensure efficient processing.
   - The **Title** column will serve as the main text data for analysis.
   - Text preprocessing will include removing stopwords, punctuation, lemmatizing the text, and converting everything to lowercase.

2. **Exploratory Data Analysis (EDA):**
   - Perform initial analysis to explore word frequency, sentence lengths, and overall distribution.
   - Visualizations such as histograms and bar plots will be used to understand the characteristics of the text.

3. **LDA Topic Modeling:**
   - Apply the LDA algorithm to generate at least 10 topics from the **Title** column.
   - The coherence score will be calculated to ensure the relevance and interpretability of the topics.

4. **Topic Visualization:**
   - Visualization techniques, such as word clouds and bar charts, will be used to represent the generated topics visually.
   - t-SNE or other dimensionality reduction techniques may also be employed to map the distribution of topics.

5. **Dependency Parsing:**
   - Two random sentences (with a minimum of 10 words) will be selected for dependency parsing.
   - Using SpaCy, I will generate visual diagrams that display the syntactic relationships between words in the sentences.

## Tools & Technologies:

- **Python**: Primary programming language for the project.
- **Libraries**:
  - **Pandas**, **NumPy**: For data handling and analysis.
  - **NLTK**, **SpaCy**, **Gensim**: For text preprocessing, topic modeling, and dependency parsing.
  - **Matplotlib**, **Seaborn**, **WordCloud**, **PyLDAVis**: For visualizations.
