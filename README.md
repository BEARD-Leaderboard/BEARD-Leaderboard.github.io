# Website of BEARD: Benchmarking the Adversarial Robustness for Dataset Distillation

**Leaderboard website**: [https://BEARD-Leaderboard.github.io/](https://BEARD-Leaderboard.github.io)

<!-- **Model Zoo**: [https://github.com/RobustBench/robustbench](https://github.com/RobustBench/robustbench)

**Paper:** [https://arxiv.org/abs/2010.09670](https://arxiv.org/abs/2010.09670) -->


## Abstract
  
Dataset Distillation (DD) aims to compress large-scale datasets into significantly smaller counterparts while preserving strong training performance. Most current DD methods primarily focus on achieving high test performance with a limited data budget, but the adversarial robustness of models trained on distilled datasets has not been thoroughly investigated. This gap is primarily due to the lack of an open-source, unified benchmark for evaluating adversarial robustness in the context of DD and the absence of a metric for measuring the robustness of distilled datasets against multiple adversarial attacks. To address this gap, we introduce **BEARD**, an open and unified benchmark designed to systematically evaluate the adversarial robustness of existing DD methods, such as DM, IDM, and BACON. We apply various attacks (i.e., FGSM, PGD, and C&W) on DD methods generated from commonly used datasets like TinyImageNet and CIFAR-10/100. To thoroughly assess the adversarial robustness of DD methods, we propose the Robustness Score (RS) and Attack Efficiency Score (AES) as the primary evaluation metrics. Furthermore, we have developed an easy-to-use library for training and evaluating the adversarial robustness of different DD methods, and we have released a model pool and dataset pool to facilitate reproducible research.



## Contributions
Contributions both to the website and code are very welcome, as well as any suggestions for improving the project! We would be happy to hear any feedback on how to make it better and more comprehensive.
