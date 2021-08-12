[**Can Subnetwork Structure be the Key to Out-of-Distribution Generalization?**](/README.md#1._can_subnetwork_structure_be_the_key_to_out-of-distribution_generalization?)

# Contributions in my words

1. They found a sparse classifier is good for Out-of-distribution(OOD) generalization.
2. They found simple Exception Risk Minimization(ERM) trained model has subnetwork that only utilizes non-spurious features. And a modified lottery tickets hypothesis holds that we can retrain the subnetwork with the same initialization values to reach better generalization ability.
3. They proposed a method called Modular Risk Minimization(MRM) to find the desired subnetwork with sparsity regularzation, and retrain the subnetwork to get a model with good out-distribution generalization performance. Also, this method is orthogonal to other OOD algorithms. Experiment results domenstrate the effectness of this method.

# Contributions they claim
1. We show that large trained networks that exploit spurious correlations contain subnetworks that are less susceptible to these spurious shortcuts.
2. We propose a novel functional lottery ticket hypothesis: there exists a subnetwork that can achieve better OOD and commensurate in-distribution accuracy in a comparable number of iterations when trained in isolation.
3. We propose Modular Risk Minimization (MRM), a straightforward and effective algorithm to improve OOD generalization. MRM helps select subnetworks and can be used in conjunction with other methods (e.g., IRM) and boosts their performance as well.

# Contributions in my words modified

1. ~~They found a sparse classifier is good for Out-of-distribution(OOD) generalization.~~
2. They found simple Exception Risk Minimization(ERM) trained model has subnetwork that ~~only utilizes non-spurious features~~ **exploits less spurious correlations**. And a modified lottery tickets hypothesis holds that we can retrain the subnetwork with the same initialization values to reach better generalization ability **with compareable in-distribution accuracy and training time**.
3. They proposed a method called Modular Risk Minimization(MRM) to find the desired subnetwork with sparsity regularzation, and retrain the subnetwork to get a model with good out-distribution generalization performance. Also, this method is orthogonal to other OOD algorithms. Experiment results domenstrate the effectness of this method **and its enhancement to other algorithms**.