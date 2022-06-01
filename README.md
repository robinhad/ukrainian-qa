# Ukrainian Question and Answering
Scripts for finetuning models for Question Answering task

## [Ukrainian Extractive Question Answering model](https://huggingface.co/robinhad/ukrainian-qa)
This model is a fine-tuned version of [ukr-models/xlm-roberta-base-uk](https://huggingface.co/ukr-models/xlm-roberta-base-uk) on the [UA-SQuAD](https://github.com/fido-ai/ua-datasets/tree/main/ua_datasets/src/question_answering) dataset.

Example (generated):  
Question: `Що відправлять для ЗСУ?`  
Context: `Про це повідомив міністр оборони Арвідас Анушаускас. Уряд Литви не має наміру зупинятися у військово-технічній допомозі Україні. Збройні сили отримають антидрони, тепловізори та ударний безпілотник. «Незабаром Литва передасть Україні не лише обіцяні бронетехніку, вантажівки та позашляховики, але також нову партію антидронів та тепловізорів. І, звичайно, Байрактар, який придбають на зібрані литовцями гроші», - написав глава Міноборони.`  
Answer: ` антидрони, тепловізори та ударний безпілотник.`  

## Ukrainian Generative Question Answering model (TBD)