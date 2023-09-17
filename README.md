# Travel_planner_chatbot

TravelPal is an interactive chatbot designed to assist travelers in planning their trips. Whether you need destination recommendations, flight booking assistance, accommodation suggestions, or activity and restaurant recommendations, TravelPal has got you covered.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features
- Provides destination recommendations based on user preferences.
- Assists in booking flights by gathering departure and arrival information.
- Helps users find suitable accommodations based on check-in and check-out dates.
- Recommends activities and restaurants tailored to user interests and dietary preferences.
- Easy-to-use chat interface for natural interactions.

## Prerequisites
- Python 3.x
- Required Python libraries (specified in `requirements.txt`)
- TensorFlow and Keras for model training and prediction.

## Getting Started
1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/KIN156/travel_planner_chatbot.git
   cd travel_planner_chatbot

Install the required Python libraries:
pip install -r requirements.txt

Prepare your training data by creating an intents.json file with chatbot intents, patterns, and responses.

Train the chatbot model as described in Training the Model.

Start a conversation with Travel planeer chatbot using the provided chat interface:

python chat_interface.py

Usage
Start the chat interface as mentioned in the Getting Started section.
Engage in a conversation by typing messages and receiving travel-related recommendations and information from Travel Planner.
Training the Model
Prepare your training data in the intents.json file with intents, patterns, and responses.

Run the model training script:
python train_chatbot.py
This will train the chatbot model and save it as "chat_model" for later use.




