Week 9
======


In week 9 we will look at some further applications of machine learning.

Machine learning is a vast field necessitating selective coverage in the past 7 weeks. As your experience increases and you venture into new areas and explore advanced techniques hopefully the material here will provide a starting point.

We will not have time to cover everything here during the class.


Deep learning
-------------

Many of the recent advancements in machine learning performance have been due to the application of deep learning techniques. Deep learning is not restricted to any particular task. Advances have been seen in classification, regression, unsupervised learning, reinforcement learning and others.

One reason we have not applied deep learning in previous classes is the requirement for more intensive computing. Deep learning models are almost always trained on GPUs, leveraging their highly parallel architecture to execute billions of calculations. Models that may take minutes on a GPU can take months on a CPU, and be infeasible.

There are two main options for working with deep learning techniques, purchase a powerful GPU or utilize cloud based resources. At NIH, the High Performance Computing group operates the biowulf cluster that has GPUs available. Outside NIH, the amazon cloud, AWS, and microsoft cloud, azure, together with many other smaller providers also provide GPU equipped servers.

* `Week 9 Deep learning  <../Wk09-Advanced-ML-tasks-Deep-Learning.ipynb>`_

Active learning
---------------

Generating labels for data can be sufficiently expensive and time consuming that completely labeling a dataset is often not possible. Active learning leverages machine learning techniques to identify the samples for which labels would be most informative.

Samples to be labeled are chosen by the active learning algorithm. The expectation is that for a given number of samples the eventual performance will be better than for a randomly chosen set of samples.

* `Week 9 Active learning  <../Wk09-Advanced-ML-tasks-Active-Learning.ipynb>`_

Recommendation systems
----------------------

Recommendation systems have seen widespread commercial use. Their use is perhaps most obvious in online retailing where they are used for recommending products to customers. These systems can either be content-based and leverage the similarities between products or collaborative and leverage the preferences of simlar users.  

* `Week 9 Recommendation systems  <../Wk09-Advanced-ML-tasks-Recommendation-Systems.ipynb>`_

Semi-supervised learning
------------------------

Correctly labeling data can often be an expensive and time consuming process resulting in large datasets that are only partially labeled. Semi-supervised learning attempts to fully utilize both the labeled and unlabeled data. Even in the absence of labels the structure and distribution of the unlabeled data can be used to refine the model.

* `Week 9 Semi-supervised learning  <../Wk09-Advanced-ML-tasks-Semi-supervised-Learning.ipynb>`_

Reinforcement learning
----------------------

Reinforcement learning focuses on optimizing the actions of software agents (programs) operating in an environment to maximize a cumulative reward. For example, optimizing control of the motors in a robot (actions) to enable walking or some other form of locomotion (reward) in an environment. Importantly, there are not clear labels assigned to actions. Sub-optimal actions can be taken and there is no explicit mechanism for correction.

Due to this uncertainty there is a trade-off that must be made between exploring different options and exploiting the options currently known. One area that has seen widespread commercial use and exposes these issues is optimizing web content to maximize user engagement. For example, selecting articles (and their titles) to show to website visitors to get them to click. These tasks are often modeled as a multi-armed bandit task. 

* `Week 9 Reinforcement learning  <../Wk09-Advanced-ML-tasks-Reinforcement-Learning.ipynb>`_

Anomaly detection
-----------------

Anomaly detection identifies samples that appear to differ from the underlying distribution of the dataset.

* `Week 9 Anomaly detection  <../Wk09-Advanced-ML-tasks-Anomaly-Detection.ipynb>`_


