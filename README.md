# Neural-Machine-Translation

## Running the models:

* Run `train_and_test.ipynb` to train and test all models
* To use them on command line, do:
    * `jupyter nbconvert --to=script train_and_test.ipynb`
    * `ipython train_and_test.py`
    
## Architecture Diagrams:

* seq2seq: [Sequence to Sequence Learning with Neural Networks](https://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf)
![image](./images/seq2seq.svg)
* attention: [Neural Machine Translation By Jointly Learning To Align And Translate](https://arxiv.org/pdf/1409.0473.pdf)
![image](./images/seq2seq_with_attention.svg)
* effective approaches: [Effective Approaches to Attention-based Neural Machine Translation](http://aclweb.org/anthology/D15-1166)
![image](./images/effective_approaches.png)
* coverage: [Modeling Coverage for Neural Machine Translation](http://www.aclweb.org/anthology/P16-1008)

## Results obtained on the dataset (english -> tamil):

| Model (Seq2Seq) | Score |
| -----------------------------------|------------|
| General attention | 0.087 |
| Vanilla | 0.082 |
| Dot attention | 0.079 |
| MLP attention | 0.072 |
| Concat attention | |
| Linguistic coverage |
