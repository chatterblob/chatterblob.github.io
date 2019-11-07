# Chatterblob

Chatterblob is using artificial intelligence to complete a text.

This is not an easy task for a computer, let alone the chatbot. A bot must be able to learn and adapt. We use a very powerful machine learning framework named Vowpal Wabbit to train the bot, a neural network for text recognition. We also train our chatbot using an automated conversation protocol called RACL that simulates the human conversation style, with the intent that it will be able to replicate human conversation.

Here is a demo of the RACL bot with a very simple sentence.

[bot_quote]It is my birthday today.[/bot_quote]

The bot is then told what to do by sending a human conversation. The bot can not understand all the syntax. We train the bot using a pre-defined vocabulary and the responses it gets are based on this vocabulary. We have a few test conversations to train our bot and get feedback from it. 
