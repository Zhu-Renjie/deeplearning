# 深度学习与tensorflow学习笔记
## 一个简单的alexnet     
+ 主页[http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/] 
+ 代码[http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/myalexnet.py]
+ 模型参数 bvlc_alexnet.npy[https://drive.google.com/open?id=0B7Wy478uBsx8eTI4OTVOeGxtcVE]

## RNN & lstm 网络
+ 手写数字识别[lstm_mnist_28x28x10.py]
+ Caltech101分类-灰度[lstm_caltech_227x227x101L.py]
+ 图片生成 -- DRAW: A Recurrent Neural Network For Image Generation by Gregor et al. (Review by Tim Cooijmans)[https://github.com/tensorflow/magenta/blob/master/magenta/reviews/draw.md]
+ 序列生成 -- Generating Sequences with Recurrent Neural Networks by Graves. (Review by David Ha)[https://github.com/tensorflow/magenta/blob/master/magenta/reviews/summary_generation_sequences.md]

## Pixel RNN
+ 笔记 Pixel Recurrent Neural Networks by Van den Oord et al. (Review by Kyle Kastner)[https://github.com/tensorflow/magenta/blob/master/magenta/reviews/pixelrnn.md]
+ 代码 [https://github.com/carpedm20/pixel-rnn-tensorflow]
+ 论文 [https://arxiv.org/abs/1601.06759] 

## Matching Networks for One Shot Learning
+ 论文 Matching Networks for One Shot Learning [https://arxiv.org/abs/1606.04080]
+ 笔记 [https://github.com/karpathy/paper-notes/blob/master/matching_networks.md]
+ 代码 code with tensorflow [https://github.com/zergylord/oneshot]
+ 代码 code with theano [https://github.com/tristandeleu/ntm-one-shot]
+ 双向lstm bidirectional-lstm 代码 [https://github.com/hycis/bidirectional_RNN]
+ sequence to sequence lstm 笔记 [https://github.com/jxieeducation/DIY-Data-Science/blob/master/research/seq2seq.md]
+ set to set lstm 论文 order matters sequence to sequence for sets [https://arxiv.org/abs/1511.06391]
+ pointer network 代码[https://github.com/pradyu1993/seq2set-keras] 讲解 [http://pradyu1993.github.io/2016/10/03/ptr-net-post.html]
 
##Generative Adversarial Networks 网络
+ Ian Goodfellow--2016talk [https://www.youtube.com/watch?v=HN9NRhm9waY]
+ Ian Goodfellow--Review by Max Strakhov [https://github.com/tensorflow/magenta/blob/master/magenta/reviews/GAN.md]
+ Improved Techniques for Training GANs [https://arxiv.org/abs/1606.03498]
+ 各种GAN改进的概览--CGAN-LAPGAN-DCGAN-GRAN-VAEGAN-- [http://chuansong.me/n/317902651864] 

## DCGAN 生成网络
+ Image Completion with Deep Learning in TensorFlow ---- Brandon Amos [https://bamos.github.io/2016/08/09/deep-completion/]
+ Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks[https://arxiv.org/abs/1511.06434]
+ DCGAN - How does it work? [https://www.youtube.com/watch?v=VAeEt9df-hQ]
+ DCGAN with SVHN dataset github code [https://github.com/shuyo/iir/blob/master/dnn/dcgan-svhn.py]
+ 代码 [dcgan_svhn_32x32x3.py]
+ 结果 [https://drive.google.com/open?id=0B7Wy478uBsx8ekhVbEVqeXU5cTA]
+ 优化DCGAN网络 论文:Improved Techniques for Training GANs [https://arxiv.org/abs/1606.03498] 代码 [https://github.com/openai/improved-gan]  \ppt


##Deep Belief Networks
+ 文档[http://deeplearning.net/tutorial/DBN.html]

##Deep Residual Networks
+ He Kaiming----MSRA 2015 [https://github.com/KaimingHe/deep-residual-networks]
+ He Kaiming----CVPR 2016 [https://www.youtube.com/watch?v=C6tLw-rPQ2o]

# 数据库 Dataset as tfrecords form
##Caltech101
+ files: train28x28.tfrecords test28x28.tfrecords train.tfrecords test.tfrecords
+ 生成脚本 [utils/save_dirs_to_tfrecords.py] [utils/save_dirs_to_tfrecords_28x28.py]
+ google drive[https://drive.google.com/open?id=0B7Wy478uBsx8YWpLWEQyLVVQRjA]

# Topic
##生成艺术品和音乐 Magenta
+ 主页 [https://github.com/tensorflow/magenta]
+ 相关论文 [https://github.com/tensorflow/magenta/tree/master/magenta/reviews]

#lecture
## Yann LeCun Informatics and Computational Sciences (2015-2016)
+ Yann LeCun Lecture 1/8 Why Deep Learning ? [https://www.youtube.com/watch?v=ChLEJA6J2b8]
+ Yann LeCun Lecture 2/8 Multilayered Networks and Gradient-based Backpropagation [https://www.youtube.com/watch?v=oX58hCamkwM]
+ Yann LeCun Lecture 3/8 Deep Learning in Practice [https://www.youtube.com/watch?v=FWdybkCarv0]
+ Yann LeCun Lecture 4/8 Convolutional Neural Networks [https://www.youtube.com/watch?v=LrUYRwAJXKM]
+ Yann LeCun Lecture 5/8 Convolutional Networks and their Applications in Vision [https://www.youtube.com/watch?v=zHosOTMScnA]
+ Yann LeCun Lecture 6/8 Recurrent Neural Networks and their Applications in NLP [https://www.youtube.com/watch?v=C-ChIA009zk]
+ Yann LeCun Lecture 7/8 Reasoning, Attention, Memory [https://www.youtube.com/watch?v=TrV_PMPpQ6Q]
+ Yann LeCun Lecture 8/8 Unsupervised Learning [https://www.youtube.com/watch?v=RftTFBmOrrY&t=5254s]

## CS294-129 Designing, Visualizing and Understanding Deep Neural Networks
+ 主页 [https://bcourses.berkeley.edu/courses/1453965/pages/cs294-129-designing-visualizing-and-understanding-deep-neural-networks]
+ youtube playlist [https://www.youtube.com/playlist?list=PLkFD6_40KJIxopmdJF_CLNqG3QuDFHQUm]

## CS 294-131: Special Topics in Deep Learning 
+ 主页 https://berkeley-deep-learning.github.io/cs294-dl-f16/
+ Oriol Vinyals: Sequences and one-shot learning 相关视频 Stanford Seminar - Recent Advances in Deep Learning [https://www.youtube.com/watch?v=UAq961jQjYg]



