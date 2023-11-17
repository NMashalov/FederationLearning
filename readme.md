# Gradient Free

My participation in project on gradient free methods

I researched impact of stochastic noise on efficacy of federated algorithms

|Algorithm | Error estimation |
|--------|--|
|Mb-Ac-SGD|$\frac{LR^2}{N^2} + \frac{\sigma R}{\sqrt{BNK}}$ |
|SM-Ac-SGD|$\frac{LR^2}{N^2K^2} + \frac{\sigma R}{\sqrt{BNK}}$ |
|Local-AC-CA| $\frac{LR^2}{N^2K^2} + \frac{\sigma R}{\sqrt{BNK}}$| 
|FedAc|$\frac{LR^2}{N^2K^2} + \frac{\sigma R}{\sqrt{BNK}}$|



Presentation:
[here](Convex_optim.pdf)

Datasets are represented in:
- https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/


Sources:
- "Безградиентные методы федеративного обучения с l1 и l2-рандомизацией
для задач негладкой выпуклой стохастической оптимизации" [paper](https://arxiv.org/pdf/2211.10783.pdf)
- "Stochastic Adversarial Noise in the “Black Box”
Optimization Problem" [paper](https://arxiv.org/pdf/2304.07861.pdf)

Auxiliary materials:
- The Power of First-Order Smooth Optimization for Black-Box Non-Smooth
Problems
[paper](https://proceedings.mlr.press/v162/gasnikov22a/gasnikov22a.pdf)
- The min-max complexity of distributed stochastic convex optimization with intermittent
communication [paper](https://arxiv.org/pdf/2102.01583.pdf)

