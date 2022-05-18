# NLU_S22_Project
Repository for NLU Spring 22 Final Project - Kanika Agarwal (ka2522), Maitreya Sonawane (mss9240), Nishanth Sanjeev (ns5287), Sumit Mamtani (sm9669)
The repository contains baseline results for 2 datasets:
1. Twiiter Sarcasm Dataset - found in folder Reddit_Twitter_Dataset/twitter. It contains .jsonl files for training and testing 
2. News Headline Sarcasm Dataset - found in folder News_dataset. It contains two files, Sarcasm_Headlines_Dataset.json and Sarcasm_Headlines_Dataset_v2.json, out of which the latter contains more sarcastic headlines and is conveniently balanced for our use case.

The baseline models chosen to evaluate was 'T5-base', a finetuned version on Twitter Sarcasm Dataset can be found on https://huggingface.co/mrm8488/t5-base-finetuned-sarcasm-twitter, and hence the same was used for testing on the Twitter Sarcasm Dataset. For News Dataset, we had to finetune the T5-base model ourselves and then test it against the test set. The model weights for the same can be found here: https://drive.google.com/file/d/1gnp1zv2t4xkYcRqmCPbaDjfgmyg8cw6Q/view?usp=sharing

In comparison, we have experimented on the following token-free models until now:

1) CANINE - finetuned and tested on the Twitter Sarcasm Dataset. The model weights can be found here: https://drive.google.com/file/d/1N0yQ2do5OqbgzHxP68Ikpyi0mDd2kNYA/view?usp=sharing

2) CANINE - finetuned and tested on the News Dataset. The model weights can be found in the following zip file: 
https://drive.google.com/file/d/11DREflBk89GdhoG5fQAYoStxOR2RNUhH/view?usp=sharing

3) ByT5-small model- finetuned and tested on the Twitter Sarcasm Dataset. The model weights can be found here:
https://drive.google.com/file/d/117QtlzOmz3QpZAliWyC8KeUkV5MolVeM/view?usp=sharing

4) ByT5-small model- finetuned and tested on the News Headline Sarcasm Dataset. The model weights can be found here:
https://drive.google.com/file/d/1riiKnmi8XFcSSokJvrKwmFgRDDlEr4vY/view?usp=sharing

5) ByT5-base model- finetuned and tested on the News Headline Sarcasm Dataset. The model weights can be found here:
https://drive.google.com/file/d/1-vAHkwUX0LNiZ-ymKtk9gFRsdfJNWWDk/view?usp=sharing

6) ByT5-base model - finetuned and tested on the Twitter Sarcasm dataset. The Jupyter Notebook and model weights can be found here:
https://drive.google.com/file/d/1MxXZZmM_yG0D5fVfxgsZxtRoEp0Aebvc/view?usp=sharing

7) Charformer model- Trained and tested on Twitter Sarcasm dataset. The model weights can be found here: https://drive.google.com/file/d/17tssC1wV_bxlVhz6v5TBT4MYPRRkNppb/view?usp=sharing

8) Charformer model - Trained and tested on News Headline Sarcasm dataset. The model weights can be found here: https://drive.google.com/file/d/1vhDF3kKtSbcYGQLO9XH4iMAMy5R8fv6F/view?usp=sharing
