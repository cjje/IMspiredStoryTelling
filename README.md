# Image-inspired storytelling

The repository contains the following main folders:

1. Notebooks
(2. Datasets - not in the codebase, too large)

The Notebooks folder contains the following key notebooks for generating the training data and finetuning the model (other notebooks are more experimental / to get model stats):

**Data related notebooks**

1. VIST_process_*: the notebooks for processing VIST training/testing/validation datasets
2. bookSumm_*: the notebooks for cleaning the bookSumm text + generating image prompt + generating images using stable diffusion model 
3. childrenBook_*: the notebooks for cleaning the children's book blurb text + generating image prompt + generating images using stable diffusion model

**Training related notebooks**

4. BaselinePerformance_VIST_plus_finetune.ipynb: Finetuning the model on VIST data and then further finetuning on children's book blurb
5. BaselinePerformance_BookSumm.ipynb: Finetuning VIST fine-tuned model then further finetuning on BookSumm data

**Evaluation related notebooks**

6. calculate_data_stats.ipynb: generating model performance stats (sentence length, tokens, sentence overlaps etc.)
