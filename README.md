# NLI Batch Optimization

Batch optimizations for NLI. Project done for DS-GA 1011.

This project presents a method to organize mini-batches for training models on Natural Language Inference (NLI) task in order to accelerate convergence speeds and in some cases better accuracy. Techniques such as batch normalization and neural data filter which augment and adapt the varying mini-batches often result in accelerating training time. Inspired by these techniques we propose a method for creating mini-batches for NLI task. We test our proposed method on different models published for solving NLI. We fine tune these models and compare convergence rate and validation accuracy achieved to gather quantitative data to support our claim. Experiments show that using our method can accelerate the convergence speed of NLI models as is seen in case ESIM, Parikh et. al., Chen et. al. and others by 2-5 times. We also present fine-tuned results of several models that were trained on SNLI for MultiNLI.

## Models tested

- Parikh et. al. 2016 (Decomposable Attentional Model for NLI)
- ESIM (Chen et. al. 2016)
- Chen et. al. 2017a
- BiLSTM with Max Pooling


## Installation

- In this project, run `conda env create`
- `source activate nlu-project`

This will install all of the dependencies needed to run the project

## Pretrained Models

Check each model's respective folder to find link to pretrained models. 

## LICENSE

MIT
