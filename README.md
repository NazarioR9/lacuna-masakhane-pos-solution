# Lacuna Masakhane Parts of Speech Challenge

This solution ranked [8th](https://zindi.africa/competitions/lacuna-masakhane-parts-of-speech-classification-challenge/leaderboard) on Zindi.

## Brief Challenge Description

The objective of this challenge is to develop a solution to classify 17 parts of speech from languages (Luo and Setwana) unseen from the training set .   
For more information about this challenge, have a look on [Zindi](https://zindi.africa/competitions/lacuna-masakhane-parts-of-speech-classification-challenge/data).   

## Repo Structure

|----Pos-Training (contains all the training notebooks)  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      |--- . . .   
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      |--- *{notebook}.ipynb*   
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      |--- . . .   
| \
|----pseudos (placeholder for pseudo labeling data)   
| \
|----submissions (models predictions on the test data)   
| \
|----masakhane-pos (repo containing the training data)  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      |--- data/     
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      |--- . . .  \
| \
|----lacuna_pos_ner (repo with all the monolingual corpus)  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       |--- data/  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       |--- language_corpus  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       |--- translation_corpus   
| \  
|---- Test.csv   
|---- SampleSubmission.csv   
|---- ./install.sh   
|---- requirements.txt   
|---- Readme.md   

PS: This isn't the definitive structure. During the code execution, new directories will be created.

## How to run the code

```
# 1. Make sure to follow the repo structure
# 2. Run 'chmod +x install.sh' and then run './install.sh'
# 3. Run 'Pos-Trainging/Training-ner.ipynb'
# 4. Run 'Pos-Trainging/Pseudo-1stRound.ipynb'
# 5. Run all the 'Pos-Training/1stRound-*-ner.ipynb' notebooks
# 6. Run 'Pos-Training/Pseudo-2ndRound.ipynb'
# 7. Run 'Pos-Training/2ndRound-Afroxlmr75L-ner.ipynb'
```

PS: #7 will generate final submission file.
