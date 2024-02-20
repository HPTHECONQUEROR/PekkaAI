# PekkaAI Small Language Model 

## PekkaAI

This project implements a small language model using Python. The language model generates sentences based on bi-gram frequency distribution from provided text data. It utilizes NLTK (Natural Language Toolkit) for text processing and Tkinter for creating a simple GUI interface.

## Dependencies

The following dependencies are required to run the project:
- Python 3.x
- NLTK (Natural Language Toolkit)
- Tkinter (for GUI)

## Imports

The project utilizes the following Python libraries:
- random
- nltk
- os
- string
- time
- tkinter

## Short Notes

- **Bi-gram**: A bi-gram is a sequence of two adjacent elements (typically words) from a corpus of text. In this project, bi-grams are used to model the probability of a word occurring after another word.
- **FreqDist (Frequency Distribution)**: FreqDist is a class in NLTK used to count the frequency of items in a list. It's particularly useful for analyzing the distribution of words or other elements in a corpus.
- **ConditionalFreqDist (Conditional Frequency Distribution)**: ConditionalFreqDist is another class in NLTK that extends FreqDist. It's used to count frequencies of occurrences, but in the context of conditions or contexts. For example, it can be used to count the frequency of words given their preceding words.

## File Structure
project_root/
│
├── PekkaAI.ipynb # Jupyter Notebook implementing the language model
├── DataFromReuters.ipynb # Jupyter Notebook for extracting text data from Reuters corpus
├── data/ # Directory containing text data files
│ ├── file1.txt
│ ├── file2.txt
│ └── ...
└── README.md # README file providing an overview of the project
The Data Folder will be Automatically Generated when you run both the files.


## License

This project is licensed under the terms of the MIT license. 





