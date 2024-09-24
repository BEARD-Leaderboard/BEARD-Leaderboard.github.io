# Website of BEARD: Benchmarking the Adversarial Robustness for Dataset Distillation

**Leaderboard website**: [https://BEARD-Leaderboard.github.io/](https://BEARD-Leaderboard.github.io)

<!-- **Model Zoo**: [https://github.com/RobustBench/robustbench](https://github.com/RobustBench/robustbench)

**Paper:** [https://arxiv.org/abs/2010.09670](https://arxiv.org/abs/2010.09670) -->


## Abstract

**Dataset Distillation (DD)** is an emerging technique that compresses large-scale datasets into significantly smaller synthesized datasets while preserving high test performance and enabling the efficient training of large models. However, current research primarily focuses on enhancing evaluation accuracy under limited compression ratios, often overlooking critical security concerns such as adversarial robustness. A key challenge in evaluating this robustness lies in the complex interactions between distillation methods, model architectures, and adversarial attack strategies, which complicate standardized assessments.  To address this, we introduce **BEARD**, an open and unified benchmark designed to systematically assess the adversarial robustness of DD methods, including DM, IDM, and BACON. **BEARD** encompasses a variety of adversarial attacks (e.g., FGSM, PGD, C&W) on distilled datasets like CIFAR-10/100 and TinyImageNet. Utilizing an adversarial game framework, it introduces three key metrics: Robustness Ratio (RR), Attack Efficiency Ratio (AE), and Comprehensive Robustness-Efficiency Index (CREI). Our analysis includes unified benchmarks, various Image Per Class (IPC) settings, and the effects of adversarial training. Results are available on the [BEARD Leaderboard](https://beard-leaderboard.github.io/), along with a library providing model and dataset pools to support reproducible research. Access the code at [BEARD](https://github.com/zhouzhengqd/BEARD).


## Contributions
Contributions both to the website and code are very welcome, as well as any suggestions for improving the project! We would be happy to hear any feedback on how to make it better and more comprehensive.
