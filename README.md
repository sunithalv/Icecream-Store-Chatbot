# Icecream Store Chatbot

## Overview
This is a custom chatbot that answers ice-cream-related questions and fetches information from a fictional ice-cream store's API. Using LangChain and OpenAI's text model, alongside a Flask web service, the chatbot can provide users with details on flavors, toppings, and store offers. Everything is put together with Chainlit for easy web application integration.

![Screenshot_IcecreamChatbot](https://github.com/sunithalv/Icecream-Store-Chatbot/assets/28974154/2bd84c4f-fd28-4b44-bc41-5b9494ae26c2)


## Getting Started

### Prerequisites
- Python 3.8 or later
- An OpenAI API key

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sunithalv/Icecream-Store-Chatbot.git
  
2. **Set Up a Conda Environment (Recommended)**
* Create a new Conda environment:
   ```bash
   conda create -p venv python=3.10 -y
* Activate the environment:
   ```bash
   conda activate venv/

3. **Install Dependencies**
* Install the required packages using the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt

4. **Set Up Your OpenAI API Key**
* Create a .env file in the root directory of the project.
* Add your OpenAI API key to the `.env` file:
   ```bash
   OPENAI_API_KEY='Your-OpenAI-API-Key-Here'

### Usage
To run the fictional store's API, execute the following command:
   ```bash
   python ice_cream_store_app.py
```
The fictional store's API will be accessible at http://localhost:5000/{endpoint_name}

Run the fictional store's application before running the chatbot. To run app, 
simply execute the `chatbot.py` script:
   ```bash
   chainlit run chatbot.py -w --port 8000
```

To run the chatbot application, navigate to  http://localhost:8000

