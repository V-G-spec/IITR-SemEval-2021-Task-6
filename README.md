# IITR SemEval-2021 Task-6
Code for ACL-IJCNLP 2021 paper titled [RoBERTa Model with Data
Augmentation for Persuasion Techniques Detection](https://aclanthology.org/2021.semeval-1.147/), by Vansh Gupta and Raksha Sharma.  
I did this project during my internship at IIT Roorkee (January 2021 - February 2021) under the supervision of Professor [Raksha Sharma](https://www.rakshasharma.com/).
The aim of the project was detection of Persuasive Techniques in Texts and Images as part of the submission for [SemEval-2021](https://semeval.github.io/SemEval2021/) [Task-6](https://propaganda.math.unipd.it/semeval2021task6/index.html) organized by Giovanni Da San Martino, Hamed Firooz, Preslav Nakov and Fabrizio Silvestri.  

The website of the shared task, with the submission instructions, updates on the competition and the live leaderboard can be found [here](https://propaganda.math.unipd.it/semeval2021task6/).  
The corpus for this task is hosted on the [shared github page](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus). The same page can be used for information on:
- [List of Versions](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#list-of-versions)
- [Task Description](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#task-description)
- [Data Format](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#data-format)
- [Format checkers](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#format-checkers)
- [Scorers](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#scorers)
- [Baseline](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#baseline)
- [Licensing](https://github.com/di-dimitrov/SEMEVAL-2021-task6-corpus/blob/main/README.md#licensing)

**Note**: [FINAL.csv](https://github.com/V-G-spec/IITR-SemEval-2021-Task-6/blob/main/FINAL.csv) in this repository is an augmented version of the given train and dev data.

## Citation
```bibtex
@inproceedings{gupta-sharma-2021-nlpiitr,
    title = "{NLPIITR} at {S}em{E}val-2021 Task 6: {R}o{BERT}a Model with Data Augmentation for Persuasion Techniques Detection",
    author = "Gupta, Vansh  and
      Sharma, Raksha",
    booktitle = "Proceedings of the 15th International Workshop on Semantic Evaluation (SemEval-2021)",
    month = aug,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.semeval-1.147",
    doi = "10.18653/v1/2021.semeval-1.147",
    pages = "1061--1067",
    abstract = "This paper describes and examines different systems to address Task 6 of SemEval-2021: Detection of Persuasion Techniques In Texts And Images, Subtask 1. The task aims to build a model for identifying rhetorical and psycho- logical techniques (such as causal oversimplification, name-calling, smear) in the textual content of a meme which is often used in a disinformation campaign to influence the users. The paper provides an extensive comparison among various machine learning systems as a solution to the task. We elaborate on the pre-processing of the text data in favor of the task and present ways to overcome the class imbalance. The results show that fine-tuning a RoBERTa model gave the best results with an F1-Micro score of 0.51 on the development set.",
}
```

## Author
[Vansh Gupta](https://github.com/V-G-spec)  
Undergraduate student, Electrical Engineering Department  
Indian Institute of Technology, Delhi
