Knowledge-based Chatbot
Overview
This is a knowledge-based chatbot that interacts with users and learns new responses dynamically. The bot uses a JSON file (knowledge_base.json) to store predefined questions and answers. When the bot doesn't know the answer to a question, it prompts the user to teach it by adding new responses to the knowledge base. The chatbot can learn new answers and save them for future interactions.

Features
Knowledge Base: The bot uses a JSON file to store predefined questions and answers.

Learning Capability: When the bot encounters an unknown question, it asks the user to provide an answer and saves it to the knowledge base for future use.

Similarity Matching: The bot uses fuzzy matching to find the most similar question from its knowledge base.

Dynamic Updates: The knowledge base is updated with new questions and answers provided by users.

Requirements
Python 3.x

json (standard Python library)

difflib (standard Python library)
