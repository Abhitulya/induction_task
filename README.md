# induction_task

This repository contains the following four sub-tasks:
1. AI vs Real Classification
2. simple GAN implementation
3. Special theme GAN implementation
4. Fine-tuning of a conversational LLM.

## AI vs Real Classification:

I tried several pre-trained models like VGG16, EfficientNetB2, MobileNetV2, ResNet50, etc. but none of them gave good test data accuracy in the competition. All of them fall in the category of 45% to 70% score in the competition. Then I tried basic and smaller CNNs and they gave an accuracy of 80 - 85. The best score was surprisingly given by a basic 3-dense layer model (falling from 92 to 98.135 in 1st competition and to 59% in 2nd competition)  


## Simple GAN implementation:

I implemented a simple GAN that generates handwritten numbers. It was trained on mnsit dataset of handwritten digits. 


## A night2day and day2night Generator (Special Themed GAN):

I implemented this using a similar technique like Conditional GAN training in which I used a CNN network to train the Discriminator first to distinguish between day and night and then used adversarial training to train the Generators to Generate day and night images

## Conversational Persona Bot:

I implemented this using a model dialogGPT and fine-tuned it to respond according to the persona of a person. I choosed this model because it is the best suited for casual conversations.
