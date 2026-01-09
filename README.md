# Topic Modeling Project

This project implements topic modeling using various techniques in Python, focusing on **Latent Dirichlet Allocation (LDA)**. It includes the analysis of a dataset containing browsing history to extract underlying topics and visualize them.

## Project Structure

- `topicmodelling.ipynb`: The Jupyter Notebook that contains the main code for topic modeling.
- `history.txt`: A file used by the program to track previous runs or important metadata related to the analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Libraries:
  - numpy
  - pandas
  - scikit-learn
  - gensim
  - matplotlib
  - nltk
  - pyLDAvis (for LDA visualization)

You can install the necessary libraries using:

```bash
pip install -r requirements.txt
```

## Running the Project

1. Clone the repository:

```bash
git clone https://github.com/Electrobuzz/CGS616---Topic-Modeling.git
cd CGS616---Topic-Modelling
```

2. Ensure that the `history.txt` file is in the same directory as the `topicmodelling.ipynb` notebook.
Note: History file is removed due to privacy concerns

3. Open the Jupyter Notebook:

```bash
jupyter notebook topicmodelling.ipynb
```

4. Run the notebook cells to perform the topic modeling analysis.

## Usage of History File

The `history.txt` file is crucial for maintaining a log of past runs or certain key parameters in the analysis. Ensure that this file is always located in the root directory of the repository alongside the notebook. If the file is missing, some parts of the analysis might fail.

## License

This project is licensed under the MIT License.
