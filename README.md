# Text Generation using GPT-2 Model
This project demonstrates a web application that generates text using OpenAI's GPT-2 model. Users can input a text prompt and specify the maximum length for the generated text, with real-time results shown on the web page.

## Introduction
Text generation is an essential task in natural language processing (NLP). This project utilizes GPT-2, a pre-trained language model by OpenAI, to generate human-like text based on user input. We built a web application using Flask that allows users to enter a prompt and receive generated text as output.

## Features
- Web-based interface to generate text using GPT-2.
- Input a text prompt and specify the length of generated text.
- Real-time text generation and display.
- Uses the transformers library for GPT-2 model handling.
- Deployed with Flask.
  
## Technologies Used:
Python: For scripting the backend logic.\
Flask: Web framework for the user interface.\
Transformers: Library to load and use the GPT-2 model.\
Torch: For GPU/CPU model execution.

## Installation
Make sure you have the following installed:

Python 3.x\
Pip\
A GPU setup (if available) for faster processing (optional).

## Steps
1. Clone the repository:
 ### git clone https://github.com/FariaRaghib/text-generation/new/main
 ### cd gpt2-text-generation

2.Create a virtual environment:
 ### python3 -m venv venv
 ### source venv/bin/activate

3.Install the required packages:
 ### pip install -r requirements.txt

4.Run the application:
 ### python app.py

5.Usage\
o Open a browser and navigate to http://127.0.0.1:5000/.\
o Enter a text prompt and specify the maximum length for the generated text.\
o Click "Generate Text" to see the output on the page.\

## Dataset
This project uses the GPT-2 model, which is pre-trained on a large corpus of text data consisting of books, articles, and websites. The model is capable of generating diverse language patterns and styles.

## Results
The web application successfully generates contextually relevant text based on user input. The application is capable of handling various text prompts and outputs coherent results within the specified maximum length.

## Future Enhancements
Control Generation Parameters: Add options for controlling parameters like temperature and seed for reproducibility.\
User Authentication: Implement a login system for personalization.\
Fine-Tuning: Train the GPT-2 model on specific datasets for better domain-specific results.\
Scalability: Optimize the application for deployment on cloud platforms.\
User Feedback: Implement surveys and A/B testing to improve the user 
