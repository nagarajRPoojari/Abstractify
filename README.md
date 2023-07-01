# Abstractify 
### Multilabel sequential sentence classifier for Research paper abstracts
![abst](https://github.com/nagarajRPoojari/Abstractify/assets/116948655/0f776ed8-26de-47ae-86d0-038784d0cfae)

Above model follows the architecture mentioned [Neural Networks for Joint Sentence Classification in Medical Paper Abstracts](https://arxiv.org/abs/1612.05251) paper with approx 100k trainable parameters .
Model uses combination od character, token and positional embedding where token embedding uses pretrained Universal sentence encoder making 250M parameter huge model.
Our model is trained on [PubMed 200k RCT](https://arxiv.org/abs/1710.06071) dataset and managed to achive **85.7** validation accuracy.


