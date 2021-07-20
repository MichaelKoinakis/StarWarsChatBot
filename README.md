# StarWarsChatBot
Themed chatbot implementation.

# Implementation
MSC team project for Natural Language Processing.
Many thanks to the team. Elena Fengou and Eleni Ntokou.

# How to run the files
If you are interested in training the model and playing around the hyperparameters to achieve better results, use the PyTorch_Chatbot file.

Since the path of files redirects to Google Drive, make sure the paths are corrected for your own attempts.

The conversation files can be found to the following link:<br>
https://drive.google.com/drive/folders/1p0BH580Tvm734G-kcJbUE44ecZKRSuGp?usp=sharing

For testing the file and chatting with the bot, run directly ChatWithChatbot file. Load one of the .tar files, which were created with different Luong Attention methods. Make sure below Configure models comment, the same attention model and the same respective .tar files are loaded.<br>
<b>dot attention:</b> https://drive.google.com/file/d/1VmeJIVGChW4dtssvpyhXu8Vg-B1hkDh4/view?usp=sharing <br>
<b>general attention:</b> https://drive.google.com/file/d/1-HF-QomcfnaRFet5dqc5iIYimSinZ05X/view?usp=sharing <br>
<b>concat attention:</b> https://drive.google.com/file/d/1m8W2CWTsPlB8AaYTxn8UinoOxZBqz0oK/view?usp=sharing <br>

For better results, load the files in Google Drive, since they are directly linked with the file.

# References
Code and general model architecture was taken from this excellent tutorial on chatbots.<br>
https://colab.research.google.com/github/pytorch/tutorials/blob/gh-pages/_downloads/chatbot_tutorial.ipynb#scrollTo=0AhW5CesrfBu
