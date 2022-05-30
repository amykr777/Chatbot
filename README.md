# Chatbot
In this Python project, we have built a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We have used a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses. The dataset we have used is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user. 

    • Intents.json – The data file which has predefined patterns and responses. 
    • train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot. 
    • Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary. 
    • Classes.pkl – The classes pickle file contains the list of categories. 
    • Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons. 
    • Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot. 
