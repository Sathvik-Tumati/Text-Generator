# Text Generation Using GPT-2

This project demonstrates how to generate text using the GPT-2 model from Hugging Face's transformers library. It allows users to input a prompt, and the model generates text based on that prompt.

Table of Contents
Description

1. Installation

2. Usage

3. Requirements

4. Contributing

Description:-
This Python script uses the transformers library by Hugging Face to load the pre-trained GPT-2 model and generate text. It prompts the user for an input, feeds it to the model, and outputs the generated text.

Installation
1. Clone the Repository
Clone this repository to your local machine:

--> git clone https://github.com/Sathvik-Tumati/Text-Generator.git
--> cd Text-Generator
2. Set Up a Virtual Environment

It is recommended to create a virtual environment:

--> python -m venv venv

Activate the virtual environment:

--> On Windows: venv\Scripts\activate

--> On macOS/Linux: source venv/bin/activate

3. Install Dependencies
Install the required dependencies using requirements.txt:

-->pip install -r requirements.txt

If you don't have requirements.txt, you can manually install the necessary libraries:

--> pip install transformers torch

Usage
Run the script:

--> python generate_gpt2.py

Input a prompt: The script will ask for a prompt to begin generating text from.

Generated Text: The model will generate and display text based on the input prompt.

Requirements
Python 3.6+

transformers: For using the GPT-2 model from Hugging Face's transformers library.

torch: Required to run the GPT-2 model.

To install all dependencies at once, you can use the requirements.txt file:

--> pip install -r requirements.txt

Generating requirements.txt

If you don't have the requirements.txt file, you can generate it by running:

--> pip freeze > requirements.txt

Contributing
We welcome contributions! If you'd like to help improve this project, feel free to fork the repository, make changes, and submit a pull request.
