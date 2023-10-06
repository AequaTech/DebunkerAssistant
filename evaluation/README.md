#DL models' evaluation

This section is amed to keep track of the quality of DL-based models quality over time. Benchmark corpora used for each round of evaluation are listed and latest model checkpoint for Hate Speech, stereotype, and irony detection are made available for replicability purposes.

## First Evaluation Round (2023-09-30)

### Training sets

* **HaSpeeDe 2020 training set**. Available at the following [Github Page](https://github.com/msang/haspeede)
* **DA corpus**. Directly developed [for the project](https://github.com)
* **Multilingual Racial Hoaxes Corpus**. Available upon request to the authors of [A Multilingual Dataset of Racial Stereotypes in Social Media Conversational Threads](https://aclanthology.org/2023.findings-eacl.51.pdf)

### Test set
* **HaSpeeDe 2020 test set**. Available at the following [Github Page](https://github.com/msang/haspeede)

### Results

| Phenomenon | test-set | accuracy | f1-score- macro | f1-score- weigthed avg |
| Hate Speech | news corpus | 0.772 | 0.722 | 0.75 |
| Stereotype | news corpus | 0.776 | 0.749 | 0.77 |
| Irony | news corpus | 0.769 | 0.769 | 0.77 |

### Models checkpoints
