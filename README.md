# Angelic Conversations: Emulating John Dee's Enochian Language With AI
-*An Interactive Experimental Art Piece by [KaliYuga_ai](https://twitter.com/KaliYuga_ai)*-

**About:** 
In the late 16th century, a time of great intellectual and cultural transformation, Dr. John Dee (a prominent English mathematician, astronomer, and advisor to Queen Elizabeth I) made the extraordinary claim of having established contact with angelic beings. Through a series of scrying sessions, Dee engaged in deep and intricate conversations with these celestial entities, which he diligently recorded in an enigmatic (and likely constructed) language known as Enochian. This complex linguistic system was, according to Dee, a divine revelation bestowed upon him by the angels themselves, further adding to the mystique surrounding his extraordinary experiences.

This Colab notebook provides the code for an interactive AI-powered art piece which attempts to emulate the overall spirit of John Dee's angelic conversations. It allows users to ask questions and receive responses in an approximation of the mysterious Enochian language, followed by a translation into English. Furthermore, this notebook generates an image via diffusion to visually represent the angelic message.

To do this, I used the following technologies:

* OpenAI's GPT-3.5-turbo model for generating pseudo-Enochian and English responses in-app.
* spaCy library for natural language processing tasks such as extracting subjects and objects from the text.
* Gradio library for creating a simple and user-friendly web interface.
* Stable Diffusion v 2.1 for generating images based on the angelic messages.
* OpenAI's ChatGPT Premium to code this whole thing.
-------

**How to Use:**

* Enter your [OpenAI API key](https://platform.openai.com/account/api-keys) in the provided field below.
* Run all cells to activate API key/install dependencies/ launch the Gradio app
* Click the generated link to open the Gradio app in a new tab. You can run in Colab, too, but the app gets cut off on smaller screens. 
 
--Once In the Gradio App--

* Enter your question in the input textbox and hit the submit button

The application will generate an Enochian response, followed by a translation into English. An image will also be generated to visually represent the angelic message.
 
*Disclaimer:* This application is created for artistic and entertainment purposes **only**. The generated Enochian responses and images are not historically accurate and, it goes without saying, *should not be considered authentic angelic messages.*

-------
**Further Reading:** For more information on John Dee's angelic conversations and their historical context, check out Deborah Harkness's excellent book [John Dee's Conversations with Angels: Cabala, Alchemy, and the End of Nature](https://www.amazon.com/John-Dees-Conversations-Angels-Alchemy/dp/0521027489). I re-read it every few years. 
