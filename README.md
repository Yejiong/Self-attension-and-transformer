# Self-attension-and-transformer

Use the multi-head self attention and transformer to classify the speakers of a vocie

- Build a basic tranformer model as the baseline.
- Construct [conformer](https://arxiv.org/abs/2005.08100) which is a variety of transformer. 
- Implement [Self-Attention Pooling](https://arxiv.org/pdf/2008.01077v1.pdf) & [Additive Margin Softmax](https://arxiv.org/pdf/1801.05599.pdf) to further boost the performance.

## Download dataset
- Data is [here](https://drive.google.com/drive/folders/1vI1kuLB-q1VilIftiwnPOCAeOOFfBZge?usp=sharing)

## Introduction of the conformer

The conformer has a burge-like architecture containing two harf feed forward modules as two bread, the convolution module as tomato, and the Multi-head self attention module as a steak. As we know, convolution layer can extract local information from the data, and the self-attention layer can get the global information from the data. 
The conformer combines the advantage of the convolution layer and the self-attention layer, and is able to extract both local and global information from the data.

