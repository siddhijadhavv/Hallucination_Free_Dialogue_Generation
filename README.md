# Faithful Benchmark for Information-Seeking Dialogue

This repository consists of Baseline and Final project implementation. 

## Milestone 3
The final project code implementation is in the 'Milestone3' directory.
The files in Milestone3 directory are as listed below:
1. BEGIN_BERT.ipynb (Implementation of the Hallucination Critic by classifying BEGIN classes)
2. VRM_Bert.ipynb (Implementation of the VRM taxonomy classification)
3. Text_generation.ipynb (Implementation of the Hallucination-free text generation)

Things to take care of before executing the files:
1. The files already have pre-saved outputs from the previous run.
2. As the size of the data is above 18,000 it would take atleast 45-60mins to train so please make sure you have adequate resources to execute the code.

Steps to check ouputs of all the files:
1. Download the file.
2. Run the entire ipynb file in either Colab or Kaggle environment by importing the file in either of the environments.

Specific instructions for Text_generation.ipynb:
1. The file has a function called 'generate_response' which requires manual input from the user.
2. When the cell is executed, input a query for example: "Do you like pizza?". 
3. Next you will be prompted to enter the associated knowledge. Enter the associated knowledge with respect to the query asked in setp 2 for example: "Pizza is a dish of Italian origin consisting of a usually round, flat base of leavened wheat-based dough topped with tomatoes, cheese, and often various other ingredients, which is then baked at a high temperature, traditionally in a wood-fired oven.".
4. The response will then be generated using the model trained which will be printed as a model output response.

## Milestone 2
The Baseline implementation of the prject is in the 'Milestone2' directory. 
The files in Milestone2 directory are as listed below:
1. GPT2_implementation.ipynb
2. Hallucination_critic_BERT_SVM_NB.ipynb 
3. Text_generation_GPT2.ipynb 

Steps to check ouputs of all the files:
1. Download the file.
2. Run the entire ipynb file in either Colab or Kaggle environment by importing the file in either of the environments.
