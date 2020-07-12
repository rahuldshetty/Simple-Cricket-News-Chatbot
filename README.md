# Simple Cricket Info Bot

I wanted to test out this NLU framework called "RASA NLU" which is used in creating custom chatbots. So did some research and found out this [Build Chat Bot Blog](https://www.analyticsvidhya.com/blog/2019/04/learn-build-chatbot-rasa-nlp-ipl/) on Analaytics Vidhta.

Based on that I made this simple chatbot where you can have conversations and ask for some cricket news.

# How to run?
0. If you want to train the bot from scratch, use the following command:
    `rasa train`

1. Start the action server with the following command:
    `python -m rasa_sdk.endpoint --actions actions`

2. Start the interactive shell for chatting with your bot with the following command:
    `rasa shell`