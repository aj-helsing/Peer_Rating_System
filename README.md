# Peer Rating System
  
- **Offensive Language Identification**, [SemEval 2019 - OffensEval](https://www.aclweb.org/anthology/S19-2010/) (Zampieri et al., 2019)- 2 labels: `offensive`, `not offensive`


# Evaluating your system

For evaluating your system, you simply need an individual predictions file for each of the tasks. The format of the predictions file should be the same as the output examples in the predictions folder (one output label per line as per the original test file). The predictions included as an example in this repo correspond to the best model evaluated in the paper, i.e., RoBERTa re-trained on Twitter (RoB-Rt in the paper).  

- [Twitter-RoBERTa-offensive](https://huggingface.co/cardiffnlp/twitter-roberta-base-offensive)
- [Twitter-RoBERTa-sentiment](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment)



```
# License

TweetEval is released without any restrictions but restrictions may apply to individual tasks (which are derived from existing datasets) or Twitter (main data source). We refer users to the original licenses accompanying each dataset and Twitter regulations.


```
#### Offensive Language Identification:
```
@inproceedings{zampieri2019semeval,
  title={SemEval-2019 Task 6: Identifying and Categorizing Offensive Language in Social Media (OffensEval)},
  author={Zampieri, Marcos and Malmasi, Shervin and Nakov, Preslav and Rosenthal, Sara and Farra, Noura and Kumar, Ritesh},
  booktitle={Proceedings of the 13th International Workshop on Semantic Evaluation},
  pages={75--86},
  year={2019}
}
```

#### Sentiment Analysis:
```
@inproceedings{rosenthal2017semeval,
  title={SemEval-2017 task 4: Sentiment analysis in Twitter},
  author={Rosenthal, Sara and Farra, Noura and Nakov, Preslav},
  booktitle={Proceedings of the 11th international workshop on semantic evaluation (SemEval-2017)},
  pages={502--518},
  year={2017}
}
```


```
