[**Reducing Domain Gap by Reducing Style Bias**](/README.md#2._reducing_domain_gap_by_reducing_style_bias)

# Contributions in my words

1. As previous work claimed, supervised trained CNN has style bias, which leads to poor generalization ability. They proposed a general framework called Style-Agnostic Networks(SagNets), which aims to make the network agnostic to styles in an end-to-end manner.
2. They divided the network into three parts: a feature extractor, a content-biased network, and a style-biased network. A randomization module and an adversarial learning framework are used to seperate contents and styles. They only use the feature extractor and the content-biased network during inference phase.
3. Experiment results verified the ability of SagNets to reduce the style bias. And they showed that SagNets can perform well on several cross-domain tasks including domain generalization, unsupervised domain adaptation and semi-supervised domain adaptation.

# Contributions they claim

1. We present Style-Agnostic Networks (SagNets) that are robust against domain shift caused by style variability across domains. 
2. By randomizing styles in a latent feature space and adversarially disentangling styles from class categories, SagNets are trained to rely more on contents rather than styles in their decision making process. 
3. Our extensive experiments confirm the effectiveness of SagNets in controlling the inductive biases of CNNs and reducing domain discrepancy in a broad range of problem settings.
4. Our work is orthogonal to many existing domain adaptation approaches that explicitly align the distributions of different domains, and achieves further improvements by complementing those methods.

# Contributions in my words modified

1. As previous work claimed, supervised trained CNN has style bias, which leads to poor generalization ability. They proposed a general framework called Style-Agnostic Networks(SagNets), which aims to make the network agnostic to styles in an end-to-end manner.
2. They divided the network into three parts: a feature extractor, a content-biased network, and a style-biased network. A randomization module and an adversarial learning framework are used to seperate contents and styles. During inference phase they only use the feature extractor and the content-biased network **which are trained to rely more on contents rather than styles**.
3. Experiment results verified the ability of SagNets to reduce the style bias **and reduce domain discrepancy**. And they showed that SagNets can perform well on several cross-domain tasks including domain generalization, unsupervised domain adaptation and semi-supervised domain adaptation.
4. **Their work is orthogonal to many existing domain adaptation approaches, and can achieve further improvements by complementing those methods.**