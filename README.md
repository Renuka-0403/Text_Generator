# AI Text Generator

## Overview

AI Text Generator is a simple web application that uses Artificial Intelligence to generate and complete text based on a user-provided prompt. The application is built using Python, Streamlit, and Hugging Face Transformers.

## Features

* Accepts a text prompt from the user.
* Generates text based on the given prompt.
* Uses a pretrained GPT-Neo model.
* Provides a simple and interactive Streamlit interface.
* Displays the generated text directly in the application.

## Technologies Used

* Python
* Streamlit
* Hugging Face Transformers
* GPT-Neo

## Requirements

Install the required libraries using:

```bash
pip install -r requirement.txt
```

## Requirements File

```text
streamlit
transformers
torch
```

## How to Run

Run the following command in the project folder:

```bash
python -m streamlit run app.py
```

The application will open in the web browser.

## How to Use

1. Enter a sentence or prompt in the text area.
2. Click the Generate Text button.
3. The AI model generates and displays a continuation of the given prompt.

### Example

Input:

```text
Artificial Intelligence is
```

Output:

```text
Artificial Intelligence is transforming the way people learn, work, and communicate.
```

The generated output may vary for different inputs.

## Model Used

The application uses:

```text
EleutherAI/gpt-neo-125M
```

GPT-Neo 125M is a pretrained language model that can generate and complete text based on an input prompt.

## About

This project demonstrates how a pretrained Natural Language Processing model can be integrated into a simple Streamlit web application for AI-powered text generation.

## Limitations

* Generated text may sometimes be repetitive or inaccurate.
* The quality of the output depends on the input prompt and pretrained model.
* The application is intended for learning and demonstration purposes.
