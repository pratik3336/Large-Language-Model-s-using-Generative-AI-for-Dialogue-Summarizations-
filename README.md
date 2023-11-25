# Large-Language-Models-using-Generative-AI-for-Dialogue-Summarizations-
Using Medical Counsel Chat Data for Dialogue Summarization Using LLM's

The Dataset Used- https://huggingface.co/datasets/nbertagnolli/counsel-chat

Scraped out of Counselchat.com's forum.
It is a platform to help counselors build their reputation and make meaningful contact with potential clients.
On the site, therapists respond to questions posed by clients, and users can like responses that they find most helpful.
**It’s a nice idea and lends itself to some interesting data. This data contains expert responses by licensed clinicialns to questions posed by individuals.**

![image](https://github.com/pratik3336/Large-Language-Model-s-using-Generative-AI-for-Dialogue-Summarizations-/assets/76115015/f2a1378a-6b0b-40a8-bcf7-da22f4ca2c5d)

# 1-Role-Play-Scenario Using LLM's using GPT2 model


A role-play scenario using a Language Model (LLM) involves simulating a conversation or interaction between multiple participants, where the LLM generates responses for one or more of the participants based on a given context or prompt.

This technique is commonly used for various purposes, including training chatbots, creating interactive storytelling, and generating creative content.

 **Use Cases**:
   - **Training Chatbots**: Role-play scenarios can be used to train chatbots and virtual assistants to handle customer inquiries or provide support.
   - **Content Generation**: They can be used to generate dialogues for storytelling, interactive games, or screenplay writing.
   - **Language Understanding**: Role-play scenarios can be used to evaluate the language understanding and generation capabilities of LLMs.


# 2- Generating Dialogue Continuations using LLM's (GPT2 model)
 This involves a pre-trained model to generate text that continues a given dialogue prompt.
 It demonstrates how the model can be used to generate human-like text based on input prompts.

 Generating dialogue continuations involves using language models, like GPT-2, to generate text that continues a given dialogue or conversation.
 This is a useful application for chatbots, virtual assistants, and natural language understanding tasks.

 # 3- Translating dialogues into different languages
 #**MarianMTModel**

MarianMTModel is a pre-trained multilingual machine translation model from the Transformers library. It is specifically designed for translating between many different languages, including English and Spanish. The model is trained on a massive dataset of text and code, and it can effectively translate a wide range of text formats, including dialogues.

**MarianTokenizer**

MarianTokenizer is a pre-trained tokenizer for MarianMTModel. It is responsible for breaking down text into tokens, which are the basic units of information that the model can understand. The tokenizer also adds special tokens to the input text, which helps the model to better understand the context of the translation.
This helps in translating Dialogues from English to Spanish

# 4- Dialogue Summarization Using Abstractice Summarization

![image](https://github.com/pratik3336/Large-Language-Model-s-using-Generative-AI-for-Dialogue-Summarizations-/assets/76115015/29389fb4-bf14-4f85-ae15-5b0d6bfe04aa)


Dialogue summarization is a process where the content of a conversation, whether it's written text or spoken dialogue, is condensed into a shorter form while preserving the key points and essential meaning. Abstractive summarization, in particular, goes beyond simply extracting key phrases or sentences from the original dialogue. 
Instead, it involves understanding the context and the substance of the conversation and then expressing the main ideas in new words.

This process can be highly complex, as it requires advanced natural language understanding and generation capabilities. Machine learning, and specifically deep learning, models like sequence-to-sequence architectures are often employed to perform abstractive summarization. They are trained on large datasets of dialogues and their corresponding summaries to learn how to generate concise and meaningful abstracts of conversations.

# 5- Toxicity Detection (Support Vector Machine (SVM) for Toxicity Detection)

This is a machine learning model that is  used for classification tasks due to its effectiveness and efficiency, especially in high-dimensional spaces.
In the context of toxicity detection, SVM can be trained to classify text as toxic or non-toxic based on features extracted from the text.

![image](https://github.com/pratik3336/Large-Language-Model-s-using-Generative-AI-for-Dialogue-Summarizations-/assets/76115015/7a421517-c267-4727-8770-791b14308a07)


**How SVM Works for Toxicity Classification**:
- SVM works by finding the hyperplane that best separates the classes in the feature space.
- It relies on the concept of margins and support vectors, which are the data points closest to the decision boundary. The goal is to maximize the margin between these points and the hyperplane.
- Text data is transformed into a numerical format using techniques like TF-IDF, which allows the SVM to process and classify it.



