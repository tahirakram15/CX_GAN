# Counterfactual Explanation and Instance-Generation using Cycle-Consistent Generative Adversarial Networks
This Repository contains the code of our submitted paper titled **Counterfactual Explanation and Instance-Generation using Cycle-Consistent Generative Adversarial Networks** at [IEEE Transactions on Image Processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=83). In this paper, we present two separate methods to address the counterfactual explanations (CX). A counterfactual explanation (CX) explicates a casual reasoning process of the form: “if X had not happened, then Y would not have happened”. However, existing CX
approaches are deficient at supplementing counterfactual explanations with plausible counterfactual instances (CIs). To address the issue, we develop a novel CX/CI generation method in which we view CI generation as unpaired imageto-image translation and CX as image-to-image conversion mapping. The method is built on generative adversarial networks (GANs) with a cyclically-consistent loss function. Initially, we develop a [Cascaded Model](#cascaded-model) to learn CX and CI generation individually. Then, we develop an [Integrated End-to-End Model](##integrated-end-to-end-model) for joint learning of both CX and CI. We evaluate our proposed method on three different datasets: [Synthetic](#synthetic-dataset), [Tuberculosis](#tuberculosis-dataset) and [BraTS](#brats-dataset). All experiments confirm the efficacy of the proposed method in generating accurate CX and CI.

## Table of Contents
  + [Cascaded Model](#cascaded-model)
  + [Integrated End-to-End Model](#integrated-end-to-end-model)
  
### Cascaded Model:


### Integrated End-to-End Model:

  


