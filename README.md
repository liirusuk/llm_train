# llm_train
## Week 3 Additional materials
- https://www.evidentlyai.com/classification-metrics/multi-class-metrics
- https://classifier-calibration.github.io/ecml-pkdd-2020-tutorial/
- https://scikit-learn.org/stable/modules/calibration.html
## Week 5 Additional materials
- https://openai.com/index/deep-double-descent/ That's the post I took the fancy plots from.
- https://arxiv.org/pdf/2310.18988 Here the authors discuss that after the interpolation threshold model's complexity may gain a new dimension.
- https://arxiv.org/pdf/2303.14151 Here double descent is studied with SVD :muscle:

## Week 6 Additional materials
Kernel trick:
https://towardsdatascience.com/the-kernel-trick-c98cdbcaeb3f
https://medium.com/@zxr.nju/what-is-the-kernel-trick-why-is-it-important-98a98db0961d
https://www.columbia.edu/~mh2078/MachineLearningORFE/SVMs_MasterSlides.pdf
https://indico.cern.ch/event/439520/contributions/1941519/attachments/1147353/1645460/Kernel_trick._Deep_learning.pdf
https://www.youtube.com/watch?v=Q7vT0--5VII

ReLU
Some intuition on how ReLU works and how it influences the decision boundary of a layers
https://medium.com/analytics-vidhya/how-relu-works-f317a947bdc6
https://medium.com/analytics-vidhya/how-does-relu-activation-work-part-2-8bb4feeb3b42

Some more activation functions:
https://arxiv.org/pdf/1710.05941v1
https://paperswithcode.com/method/elu#:~:text=The%20Exponential%20Linear%20Unit%20(ELU)%20is%20an%20activation%20function%20for,forward%20propagated%20variation%20and%20information
https://arxiv.org/abs/1706.02515v5
https://paperswithcode.com/method/gelu

More on neural networks:
A book [“Make your own neural network”](https://www.amazon.co.uk/Make-Your-Own-Neural-Network/dp/1530826608). First couple of chapters tell about the structure of fully-connected NN and its training in a very understandable format with illustrations.
[DeepLearningBook chapter 6](https://www.deeplearningbook.org/contents/mlp.html) (quite thorough, mathematical and formal)
[Conspect on backpropagation for a Linear Layer](https://cs231n.stanford.edu/handouts/linear-backprop.pdf) from Stanford course cs231n
[A Neural Network Playground](https://playground.tensorflow.org/#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.85255&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false) — here you can build simple fully-connected neural networks using UI, train them on toy tasks and visualize decision boundaries

Matrix derivatives:
[The matrix cookbook](https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)
[Matrix derivatives cheat sheet](https://www.gatsby.ucl.ac.uk/teaching/courses/sntn/sntn-2017/resources/Matrix_derivatives_cribsheet.pdf)
[Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf)

## Week 7 Additional materials

Convolutional Neural Networks (CNNs):
[Materials from cs231n course in Stanford](https://cs231n.github.io/convolutional-networks/)
[Play with CNNs in your browser](https://poloclub.github.io/cnn-explainer/)

[A comprehensive paper on Representation engineering (steering vectors)](https://arxiv.org/abs/2310.01405)
[A comprehensive paper on Task vectors](https://arxiv.org/abs/2212.04089)
[A paper investigating the maths behind task vectors](https://arxiv.org/abs/2212.04089)
[A blogpost about finding many orthogonal steering vectors](https://jacobgw.com/blog/ml/2024/07/14/melbo-ortho.html)

[Regularization in Deep Learning](https://www.deeplearningbook.org/contents/regularization.html) (chapter from deeplearningbook)
Here Dropout is 7.12

## Week 8 Additional materials

These are links and additional materials to this week’s class:

[TF-IDF (Wikipedia)](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://en.wikipedia.org/wiki/Tf%25E2%2580%2593idf&ved=2ahUKEwi7lZiYhO6KAxU2RUEAHYWMO6kQFnoECBYQAQ&usg=AOvVaw08xPM4769KY8FMfa7TLTfJ)
[Understanding TF-IDF (Capital One)](https://www.capitalone.com/tech/machine-learning/understanding-tf-idf/)

[Latent Semantic Analysis (Wikipedia)](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://en.wikipedia.org/wiki/Latent_semantic_analysis&ved=2ahUKEwi6nuD-he6KAxVNSEEAHVSrGdwQFnoECA4QAQ&usg=AOvVaw1dsgbiqXG0_n5xva0r7FBg)

[An Illustrated Word2Vec (Jay Alammar blog)](https://jalammar.github.io/illustrated-word2vec/)
[Embedding Projector from Tensorflow](https://projector.tensorflow.org/) (Interactive point cloud of word embeddings projected into 3D-space using dimensionality reduction techniques. You can see how embeddings of different words relate to each other)
[How to work with word2vec embeddings in Gensim](https://radimrehurek.com/gensim/models/word2vec.html) (a popular library for working with word embeddings)
[Some tricks that are used when training word embeddings + GloVe](https://jonathan-hui.medium.com/nlp-word-embedding-glove-5e7f523999f6)
[GloVe paper](https://nlp.stanford.edu/pubs/glove.pdf)
[FastText library](https://fasttext.cc/)
[Using FastText in HuggingFace](https://huggingface.co/blog/fasttext)

[Bidirectional RNN](https://d2l.ai/chapter_recurrent-modern/bi-rnn.html)
[LSTM & GRU](https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21)

[BPE Encoding explanation](https://huggingface.co/learn/nlp-course/en/chapter6/5)

[Post about State Space Models (Nebius blog)](https://nebius.com/blog/posts/model-pre-training/transformer-alternatives-2024)
[Introduction to State Space Models (HuggingFace)](https://huggingface.co/blog/lbourdois/get-on-the-ssm-train)


## Week 9 Additional materials


[A very nice article about the history of machine translation from 1950 till modern neural networks](https://www.freecodecamp.org/news/a-history-of-machine-translation-from-the-cold-war-to-deep-learning-f1d335ce8b5/)
[Paper “Neural Machine Translation by Jointly Learning to Align and Translate”](https://arxiv.org/pdf/1409.0473.pdf) (the paper where Attention mechanism was presented)
[Paper “Attention is all you need”](https://arxiv.org/pdf/1706.03762.pdf) (the paper where Transformer architecture was presented): 
[A visual explanation of position encodings:](https://www.youtube.com/watch?v=dichIcUZfOw) why we need this and how build them
[A very thorough article about position encodings](https://kazemnejad.com/blog/transformer_architecture_positional_encoding/) (a video above is based on it). It explains why the form of position encodings discussed in our class helps the attention mechanism to extract information about relative positions of the tokens
[An article with visual explanation of the Transformer architecture](http://jalammar.github.io/illustrated-transformer/) (might be useful to “see” the explanation of Transformer from different angle
[Building your own Transformer with code examples](https://towardsdatascience.com/build-your-own-transformer-from-scratch-using-pytorch-84c850470dcb)
[An article explaining the following phenomenon:](https://lessw.medium.com/what-layernorm-really-does-for-attention-in-transformers-4901ea6d890e#:~:text=Normalization%20via%20LayerNorm%20has%20been,and%20gradients%20on%20the%20backward.) if LayerNorm layer is placed before the Attention layer in Transformer, LayerNorm helps the Attention component craft an attention query such that all keys are equally accessible. I.e. it makes things easier for the attention mechanism, making Transformer architecture more efficient
There’re tools for visualization of Transformer’s attention outputs. One of them is BertViz. In [this article](https://www.comet.com/site/blog/explainable-ai-for-transformers/) it’s explained how to use it

## Future reads

https://github.com/Nebius-Academy/LLM-Engineering-Essentials/tree/main