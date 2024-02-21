# ChatterGen: Your Interactive Chatbot Powered by GenAI
# Overview
ChatterGen is an interactive chatbot created using GenAI technology. It leverages advanced language models to provide intelligent responses to user queries and engage in meaningful conversations. The chatbot utilizes GenAI's powerful natural language processing capabilities to understand and generate human-like responses, making interactions more intuitive and engaging.

## Key Features
Advanced Language Models: ChatterGen utilizes state-of-the-art language models to understand user queries and generate contextually relevant responses.
Interactive Conversations: Engage in interactive conversations with ChatterGen on a wide range of topics and queries.
API Integration: Seamlessly integrate with GenAI's Hugging Face Hub API to access pre-trained language models and generate responses in real-time.
Efficient Document Retrieval: ChatterGen efficiently retrieves relevant documents and information from a document repository using FAISS for similarity search.
Question Answering: Utilize ChatterGen for question answering tasks, retrieving accurate information from documents based on user queries.
## Getting Started
API Key Setup: Obtain an API key from Hugging Face Hub and set it as the environment variable HUGGINGFACEHUB_API_TOKEN.
python
Copy code
import os
os.environ["HUGGINGFACEHUB_API_TOKEN"] = 'api_token'
## Install Dependencies: Install the required dependencies for the project.
bash
Copy code
pip install langchain faiss-cpu
### Select Language Model: Choose the desired language model from GenAI's Hugging Face Hub repository.
### Load and Split Documents: Load documents from the directory and split them into smaller chunks for efficient processing.
### Generate Word Embeddings: Utilize Hugging Face Inference API to generate word embeddings for document similarity search.
### Create Vector Database: Store document embeddings in a vector database using FAISS.
### Initialize Question Answering Chain: Load the question answering chain using the selected language model.
## Usage
Interact with ChatterGen by providing queries and questions.
Retrieve intelligent responses and engage in conversational exchanges with the chatbot.
Explore various topics and query types to experience the capabilities of ChatterGen.
### Future Enhancements
Implement additional conversational features and context awareness to enhance user interactions.
Integrate with external APIs and services to provide real-time information and updates.
Improve question answering capabilities and response accuracy through model fine-tuning and optimization.
## Contributors
Suhaib Mukhtar
## Contact
suhaibmukhtar2@gmail.com
https://www.linkedin.com/in/suhaib-mukhtar-63777b217
Provide contact information for support or inquiries.
