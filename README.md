# Fine-Tuning BERT For Named Entity Recognition

## Introduction
The project aims to fine-tune the pre-trained BERT model, which will then be used to build a robust NER model. NER is a task where we identify and classify named entities (persons, organizations, locations, misc.) in text. This project used the CoNLL-2003 dataset, a popular dataset for NER tasks.

<img width="646" alt="BERT" src="https://github.com/user-attachments/assets/e21f42fe-087b-4306-80cb-b127aceb6697">

(Source - https://medium.com/ubiai-nlp/mastering-named-entity-recognition-with-bert-ca8d04b67b18#:~:text=Fine%2Dtuning%20BERT%20for%20Named,entities%20in%20a%20given%20domain.)

## Methodology
Firstly, the ‘bert-base-cased’ model was chosen for fine-tuning, which benefits NER tasks. Secondly, the fine-tuning was performed using Hugging Face's Trainer API.

<img width="327" alt="Epochs Loss" src="https://github.com/user-attachments/assets/c9aa0124-394a-4baf-bc4c-7f7c33bd90ff">

## Results
We demonstrated the NER model’s effectiveness by performing inferences on sample sentences.

<img width="528" alt="Output for NER task" src="https://github.com/user-attachments/assets/0de03e5e-f733-4d80-a488-7f8ec24de507">
