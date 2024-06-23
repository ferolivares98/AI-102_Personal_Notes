# Question answering solution by using Azure Ai Language

## Overview of QA

![alt text](image-235.png)

We can use the QA solution of overlap this service now with a trained OpenAI model.

![alt text](image-236.png)

When we have static information, this is the best question. **Static and having to return the same answer for the same question, always.** This is not Generative AI.

![alt text](image-237.png)

![alt text](image-238.png)

**Conversation flow** -> direct the conversation through certain paths. We can handle this with in-question answering, called **multi-turn conversation.**

## Create a QA

![alt text](image-239.png)

![alt text](image-240.png)

![alt text](image-241.png)

## Add question-and-answer pairs manually

![alt text](image-242.png)

![alt text](image-243.png)

## Import sources

![alt text](image-244.png)

Question in one line, then answer.

![alt text](image-245.png)

Also, we can read from the QA of a web page.

![alt text](image-246.png)

## Train and test a knowledge base

![alt text](image-247.png)

![alt text](image-248.png)

We have confidence score for each question/answer, based on the input!

![alt text](image-249.png)

With an unrealted question and a more realistic confidence score, we get a value of 0.0, and an id of -1.

![alt text](image-250.png)

We can also do weird questions that will not be detected as expected.

![alt text](image-251.png)

## Publish a knowledge base

![alt text](image-252.png)

Important, for the header:

![alt text](image-253.png)

![alt text](image-254.png)

## Create a multi-turn conversation

![alt text](image-255.png)

![alt text](image-256.png)

![alt text](image-257.png)

We can then add prompts for the vegetarian asking, for example, if the customer is vegan. Or other options!

![alt text](image-258.png)

![alt text](image-259.png)

## Add alternate phrasing

![alt text](image-260.png)

## Add chit-chat to a knowledge base

![alt text](image-261.png)

![alt text](image-262.png)

## Export a knowledge base

![alt text](image-263.png)

![alt text](image-264.png)

## Create a multi-language question answering solution

Has to enabled on project creation because of pricing. Even chit-chat supports multiple languages.

1. Create the QA knowledge base in one language.
2. Test, train, perfect.
3. Create a new project in a second language.
4. Test, train, perfect.
5. You will need to send users to the correct endpoint based on their language, **because we have a different endpoint for each one.**
   1. Also, we could perhaps use the Language Detection AI method to intercept the first question and determine the language.
