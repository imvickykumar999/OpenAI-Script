# YouTube-Channel

------------------

- Script : ['Just Cause 4' gets lost in its own storm](https://mashable.com/article/just-cause-4-review)
- Editor : [Article to Video](https://app.pictory.ai/textinput)
- Video  : [Just Cause 4 review Play || Video Created by pictory.ai](https://youtu.be/N78eiyfkDTY)

---------------------------------

> [![image](https://user-images.githubusercontent.com/50515418/223028493-ded7c88b-e9c9-4d64-9740-118d64fa145d.png)](https://youtu.be/N78eiyfkDTY)

------------------------

- Script : [Video script for my new youtube channel on new video games](https://chat.openai.com/chat)
- Editor : [Script to Video](https://app.pictory.ai/textinput)
- Video  : [Example of Video made from pictory.ai and openai](https://youtu.be/Zu5lhwfNCew)

----------------------------

> [![image](https://user-images.githubusercontent.com/50515418/223026451-248e2b89-9cc1-48df-8d65-8c03ce7d6cc9.png)](https://youtu.be/Zu5lhwfNCew)

------------------------

# Coming Soon [...](https://www.geeksforgeeks.org/convert-text-speech-python/)

    # Import the required module for text
    # to speech conversion
    from gtts import gTTS

    # This module is imported so that we can
    # play the converted audio
    import os

    # The text that you want to convert to audio
    mytext = 'Welcome to geeksforgeeks!'

    # Language in which you want to convert
    language = 'en'

    # Passing the text and language to the engine,
    # here we have marked slow=False. Which tells
    # the module that the converted audio should
    # have a high speed
    myobj = gTTS(text=mytext, lang=language, slow=False)

    # Saving the converted audio in a mp3 file named
    # welcome
    myobj.save("welcome.mp3")

    # Playing the converted file
    os.system("mpg321 welcome.mp3")
