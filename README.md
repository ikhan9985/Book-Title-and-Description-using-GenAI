# Book-Title-and-Description-using-GenAI
This project demonstrates a simple example of text generation using Hugging Face's GPT-2 model. It generates a dataset of book titles and descriptions, tokenizes the text, and trains a GPT-2 language model to generate similar content.

## Features
- Generates a dataset of book titles and descriptions.
- Tokenizes the dataset using GPT-2 tokenizer.
- Trains a GPT-2 model on the dataset.
- Allows for text generation based on book titles.

## Files
- book_titles_and_descriptions.csv: The generated dataset of book titles and descriptions.
- Python script to train the GPT-2 model and generate text.

## Dependencies
Make sure you have the following dependencies installed:

- transformers
- pandas
- datasets

You can install them using:

- pip install transformers pandas datasets

## How to Use
Clone the repository:

- git clone https://github.com/ikhan9985/Book-Title-and-Description-using-GenAI.git
- cd book-title-description-gen
- Run the script to generate a dataset of book titles and descriptions, tokenize them, and train the GPT-2 model:

After training, you can use the trained model to generate text based on book titles by providing input text.

## Example Output
For an input like:
The Forgotten Temple

The generated output might be:
The Forgotten Temple - A mysterious and ancient structure lost in time, filled with untold secrets and challenges.
