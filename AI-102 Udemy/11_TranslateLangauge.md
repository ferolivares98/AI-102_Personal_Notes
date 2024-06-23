# Translate language

## Translate text and documents by suing the Azure AI translator service.

100-160+ languages and dialects.

Customizable translation -> technical words, keywords...

We can use:

- Synchronous translation.
- -Asynchronous translation.
- Real-time translation. Quite difficult.

## Create an AI Translator resource

![alt text](image-190.png)

![alt text](image-191.png)

![alt text](image-192.png)

![alt text](image-193.png)

## Azure AI Language Studio for translation

![alt text](image-194.png)

![alt text](image-195.png)

![alt text](image-196.png)

Careful with the limits.

![alt text](image-197.png)

**Glosary file** -> specific translation requirements.

![alt text](image-198.png)

![alt text](image-199.png)

![alt text](image-200.png)

![alt text](image-201.png)

## Implement custom translation

![alt text](image-202.png)

Parallel documents -> already translated documents used as training set. 10.000 sentences needed.

Dictionary data -> One text file for each language and translations line by line.

BLEU score (0-100). **From 40-60 is already high quality.** 60+ is very, very good.

![alt text](image-203.png)

![alt text](image-204.png)

## Translate speech-to-speech by using the Azure AI Speech Service

![alt text](image-205.png)

Behind the scenes, multiple resources being uised from one API call.

Using the Speech API.

![alt text](image-206.png)

![alt text](image-207.png)

![alt text](image-208.png)

Sort of real-time!

Another example with a file instead of microphone:

![alt text](image-209.png)

## Translate speech-to-text by using the Azure AI Speech Service

Easier than speech-to-speech (no speech synthesis).

![alt text](image-210.png)

## Translate to multiple languages simultaneously

![alt text](image-211.png)

![alt text](image-212.png)

Same in text-to-text (REST API):

![alt text](image-213.png)
