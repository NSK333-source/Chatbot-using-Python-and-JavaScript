# Chatbot-using-Python-and-JavaScript
Chatbot Deployment with Flask and JavaScript

**Project Credits to https://github.com/patrickloeber/chatbot-deployment.You can visit this repo to get more info about the project**

Important step :
Create a virtual environment befor dowloading the dependesces :
 python3 -m venv venv
 .\venv\Scripts\activate       (for windows)

Install dependencies:
 pip install Flask torch torchvision nltk

python
>>> import nltk
>>> nltk.download('punkt')

(You will probablyfind it difficut to download the punkt package , you can try the different solutions found online like downloading the punkt package manually and adding it to your path)



Modify intents.json with different intents and responses for your Chatbot
   python train.py


This will dump data.pth file. And then run the following command to test it in the console.
   python chat.py


You can watch this youtube video for complete explaination: https://www.youtube.com/watch?v=a37BL0stIuM&t=82s
