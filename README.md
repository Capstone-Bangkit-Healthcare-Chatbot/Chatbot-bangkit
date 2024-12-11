# Chatbot-bangkit
Healthcare Chatbot about General Health Information

# About the model
- Mental Health Chatbot: The chatbot leverages Long Short-Term Memory (LSTM) neural networks to understand and respond to user inputs effectively. It aims to offer a conversational interface that can help users navigate through their emotional well-being, offering empathy and guidance in a non-judgmental environment. LSTM is suitable for chatbots or simple text generation with limited data.
- General Disease Chatbot: The chatbot functionality in this project is powered by the GPT-2 pre-trained model. GPT-2, developed by OpenAI, is renowned for its ability to generate human-like text based on the input it receives. In this project, GPT-2 is utilized to create an interactive chatbot that can engage users in meaningful conversations about various diseases and medical conditions. The model's architecture enables it to understand context, recall previous interactions, and provide informative and accurate responses, contributing to a dynamic and educational user experience.

# Machine Learning Task
* Searching for datasets to be used for both chatbots
* Cleaning data to eliminate null values, duplicates, and ambiguities
* Creating a mental health chatbot model using LSTM architecture
* Creating a general disease chatbot model using a pre-trained GPT-2 model

# Machine Learning Members
- M505B4KY3694 – Raphael Hanley – Institut Sains dan Teknologi Terpadu Surabaya | m505b4ky3694@bangkit.academy
- M505B4KY1554 – Frederico – Institut Sains dan Teknologi Terpadu Surabaya | m505b4ky1554@bangkit.academy
- M505B4KY1777 – Hieronimus William Tandhia – Institut Sains dan Teknologi Terpadu Surabaya | m505b4ky1777@bangkit.academy

#Installation
1. Mental Health Chatbot
   - Install the required dependencies
     `pip install -r requirements.txt`
   - Load the Model and Tokenizer
     ```
     import pickle
      from keras.models import load_model
      
      # Load the model
      model = load_model('mentalhealth_chatbot_model_final.h5')
      
      # Load the tokenizer
      with open('tokenizer.pickle', 'rb') as handle:
          tokenizer = pickle.load(handle)
      
      # Load the label encoder
      with open('label_encoder.pickle', 'rb') as handle:
          label_encoder = pickle.load(handle)
      ```
   - Run the Jupyter Notebook
     `jupyter notebook mental-notebook.ipynb`
2. General Disease Chatbot
   - Install the required dependencies
     `pip install -r requirements.txt`
   - Install the model.safetensor on the link provided in .txt
   - Run the jupiter notebook and make sure in the testing section to put the correct folder path
     example `./Model` 

