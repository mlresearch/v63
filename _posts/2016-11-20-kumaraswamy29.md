---
title: Bank of Weight Filters for Deep CNNs
abstract: Convolutional neural networks (CNNs) are seen to be extremely effective
  in many large object recognition tasks. One of the reasons for this is that they
  learn appropriate features also from the training data. The convolutional layers
  of a CNN have these feature generating filters whose weights are learnt. However,
  this entails learning millions of weights (across different layers) and hence learning
  times are very large even on the best available hardware. In some studies in transfer
  learning it has been observed that the network learnt on one task can be reused
  on another task (by some finetuning). In this context, this paper presents a systematic
  study of the exchangeability of weight filters of CNNs across different object recognition
  tasks. The paper proposes the concept of bank of weight-filters (BWF) which consists
  of all the weight vectors of filters learnt by different CNNs on different tasks.
  The BWF can be viewed at multiple levels of granularity such as network-level, layer-level
  and filter-level. Through extensive empirical investigations we show that one can
  efficiently learn CNNs for new tasks by randomly selecting from the bank of filters
  for initializing the convolutional layers of the new CNN. Our study is done at all
  the multiple levels of granularity mentioned above. Our results show that the concept
  of BWF proposed here would offer a very good strategy for initializing the filters
  while learning CNNs. We also show that the dependency among the filters and the
  layers of the CNN is not strict. One can choose any pre-trained filter instead of
  a fixed pre-trained net, as a whole, for initialization. This paper is a first step
  in the direction of creating and characterizing a Universal BWF for efficient learning
  of CNNs.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: kumaraswamy29
month: 0
firstpage: 334
lastpage: 349
page: 334-349
sections: 
author:
- given: Suresh Kirthi
  family: Kumaraswamy
- given: PS
  family: Sastry
- given: Kalpathi
  family: Ramakrishnan
date: 2016-11-20
address: The University of Waikato, Hamilton, New Zealand
publisher: PMLR
container-title: Proceedings of The 8th Asian Conference on Machine Learning
volume: '63'
genre: inproceedings
issued:
  date-parts:
  - 2016
  - 11
  - 20
pdf: http://proceedings.mlr.press/v63/kumaraswamy29.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
