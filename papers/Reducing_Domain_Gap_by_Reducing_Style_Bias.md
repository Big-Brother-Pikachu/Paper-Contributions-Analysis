# Contributions in my words

1. As previous work claimed, supervised trained CNN has style bias, which leads to poor generalization ability. They proposed a general framework called Style-Agnostic Networks(SagNets), which aims to make the network agnostic to styles in an end-to-end manner.
2. They divided the network into three parts: a feature extractor, a content-biased network, and a style-biased network. A randomization module and an adversarial learning framework are used to seperate contents and styles. They only use the feature extractor and the content-biased network during inference phase.
3. Experiment results verified the ability of SagNets to reduce the style bias. And they showed that SagNets can perform well on several cross-domain tasks including domain generalization, unsupervised domain adaptation and semi-supervised domain adaptation.

# Contributions they claim

# Contributions in my words modified