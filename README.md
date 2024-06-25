Skincare Chatbot with LLM Integration
Overview
This project is a chatbot application that leverages the strengths of Large Language Models (LLM) to handle natural language queries specifically related to skin care. The chatbot is developed using Flowise and integrates the LLaMA3 LLM. The application allows users to interact with the chatbot through a user-friendly interface and provides accurate responses about skin care.

Features
Domain: The chatbot focuses on skin care, providing information and answering queries related to skin care routines, products, and common skin concerns.
LLM Integration: Utilizes the LLaMA3 model integrated into Flowise for query processing.
Components Used
Ollama Embeddings: For embedding queries and context.
ChatOllama: The main chat interface for interaction.
Conversational Retrieval QA Chain: For retrieving relevant information.
In-Memory Vector Store: To store and retrieve embeddings.
User Base
The application is designed for individuals seeking advice, information, and solutions related to skin care. It helps users by providing quick and accurate responses to their queries about skin care routines, products, and treatments.

Getting Started
Prerequisites
Node.js (v14 or higher)
npm
Flowise
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/LissaRodrigues/Skincare-Chatbot-with-LLM-Integration.git
Navigate to the project directory:

bash
Copy code
cd Skincare-Chatbot-with-LLM-Integration
Running the Application
Start Flowise:

bash
Copy code
npx flowise start
Open your browser and navigate to http://localhost:3000 to access the chatbot interface.

Make sure your Ollama app is running at http://127.0.0.1:11434/.

Now run chatbot.html using Live Server.

Usage
Type your query related to skin care into the input box.
The chatbot will process your query and provide a relevant response based on the LLaMA3 model.
Evaluation and Testing
The application has been tested with a variety of queries related to skin care to ensure its performance, accuracy, and usability. Below are some example queries:

"What is the best moisturizer for dry skin?"
"How should I layer my skin care products?"
"How can I reduce acne scars?"
By following these steps, you will be able to set up and interact with a skin care-focused chatbot that leverages the power of LLaMA3 and Flowise for comprehensive and accurate responses.

Repository
You can clone the repository using the following command:

bash
Copy code
git clone https://github.com/LissaRodrigues/Skincare-Chatbot-with-LLM-Integration.gi
