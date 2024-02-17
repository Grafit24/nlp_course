__Lecture [slides](./lecture.pdf)__

# More materials

* ✅ Russian videos (2021): [lecture and practice](https://disk.yandex.ru/i/Phpjg0S7UYthGQ)
* ✅ Materials '2020 : [lecture](https://yadi.sk/i/Zewa7ZmKoyvEPQ), [seminar](https://yadi.sk/i/sbQXa4gh1xh77g)
* An overview of proxy-label approaches for semi-supervised learning - [blog post](http://ruder.io/semi-supervised/)
* A Little Review of Domain Adaptation in 2017 - [blog post](https://artix41.github.io/static/domain-adaptation-in-2017/index.html)
* Awesome Transfer Learning  - list of papers [repo](https://github.com/artix41/awesome-transfer-learning)
* Awesome Domain Adaptation - list of papers [repo](https://github.com/zhaoxin94/awsome-domain-adaptation)

## Practice

✅ homework.ipynb

## Videos

* __The Future of Natural Language Processing__ by Thomas Wolf [[youtube]](https://www.youtube.com/watch?v=G5lmya6eKtc)

* __Tutorial on Domain Adaptation__ by Hal Daumé III [[youtube]](https://www.youtube.com/watch?v=F2OJ0fAK46Q)
* __Domain Adaptation with Structural Correspondence Learning__ by John Blitzer [[youtube]](https://www.youtube.com/watch?v=HhA8MZbi9rA)
* __Learning with Scarce and Biased Data in Natural Language Processing__ by Barbara Plank [[youtube]](https://www.youtube.com/watch?v=MgrOKmfvxoQ)

## Articles

### General articles

* __Neural Unsupervised Domain Adaptation in NLP---A Survey__ by Alan Ramponi, Barbara Plank, 2021 [[article]](https://arxiv.org/abs/2006.00632)

#### Theory

* __Learning Bounds for Domain Adaptation__ Blitzer et al. 2007 [[article]](https://papers.nips.cc/paper/3212-learning-bounds-for-domain-adaptation)

* __A theory of learning from different domains__ Shai Ben-David, John Blitzer 2010 [[article]](https://link.springer.com/article/10.1007/s10994-009-5152-4)
* __Analysis of Representations for Domain Adaptation__ Ben-Daivid et al. 2006 [[article]](https://papers.nips.cc/paper/2983-analysis-of-representations-for-domain-adaptation)

#### In-domain vs out-domain generalization

* __Learning and Evaluating General Linguistic Intelligence__ Yogatama et al. 2019 [[article]](https://arxiv.org/abs/1901.11373)

* __BERTs of a feather do not generalize together: Large variability in generalization across models with similar test set performance__ R. Thomas McCoy, Junghyun Min, Tal Linzen 2019 [[article]](https://arxiv.org/abs/1911.02969)

### Data-centric methods for unsupervised domain adaptation

#### Unsupervised pre-training

* __Don't Stop Pretraining: Adapt Language Models to Domains and Tasks__ Gururangan et al. 2020 [[article]](https://arxiv.org/abs/2004.10964)

* __Unsupervised Domain Adaptation of Contextualized Embeddings for Sequence Labeling__ Xiaochuang Han, Jacob Eisenstein 2020 [[article]](https://arxiv.org/abs/1904.02817)
* __UDALM: Unsupervised Domain Adaptation through Language Modeling__ Constantinos Karouzos et al. 2021 [[article]](https://arxiv.org/abs/2104.07078)

#### Instance weighting/Data selection

* __Instance Weighting for Domain Adaptation in NLP__ Jiang, Zhai 2007 [[pdf]](http://sifaka.cs.uiuc.edu/czhai/pub/acl07.pdf)

* __Instance Weighting for Neural Machine Translation Domain Adaptation__ Wang et al. 2017 [[pdf]](http://aclweb.org/anthology/D17-1155)
* __Cost Weighting for Neural Machine Translation Domain Adaptation__ Chen et al. 2017 [[pdf]](http://www.aclweb.org/anthology/W17-3205)
* __Learning to select data for transfer learning with Bayesian Optimization__ by Ruder, Plank 2017 [[article]](https://arxiv.org/abs/1707.05246)

#### Proxy-label methods

* __Asymmetric Tri-training for Unsupervised Domain Adaptation__ Saito et al. 2017 [[arxiv]](https://arxiv.org/abs/1702.08400)

* __Strong Baselines for Neural Semi-supervised Learning under Domain Shift__ Sebastian Ruder, Barbara Plank 2018 [[arxiv]](https://arxiv.org/abs/1804.09530)

#### Back-translation

* __Improving Neural Machine Translation Models with Monolingual Data__ Sennrich et al. 2016 [[arxiv]](https://arxiv.org/abs/1511.06709)

* __Iterative Back-Translation for Neural Machine Translation__ Hoang et al. 2018 [[pdf]](http://aclweb.org/anthology/W18-2703)

### Model-centric methods for unsupervised domain adaptation

#### Deep Feature Alignment/Adversarial methods

* __Unsupervised Domain Adaptation by Backpropagation__ Yaroslav Ganin, Victor Lempitsky 2014 [[arxiv]](https://arxiv.org/abs/1409.7495)

* __Learning Transferable Features with Deep Adaptation Networks__ Long et al. 2015 [[arxiv]](https://arxiv.org/abs/1502.02791)
* __Adversarial and Domain-Aware BERT for Cross-Domain Sentiment Analysis__ Du et al. 2020 [[article]](https://aclanthology.org/2020.acl-main.370/)
* __Domain Adaptation with Structural Correspondence Learning__ Blitzer et al. 2007 [[article]](https://aclanthology.org/W06-1615/)

#### Pivot

##### Batch Normalization-like

* __Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift__ Sergey Ioffe, Christian Szegedy, 2015 [[arxiv]](https://arxiv.org/abs/1502.03167)

* __Revisiting Batch Normalization For Practical Domain Adaptation__  Li et al. 2016 [[arxiv]](https://arxiv.org/abs/1603.04779)
* __AutoDIAL: Automatic DomaIn Alignment Layers__ Carlucci et al. 2017 [[arxiv]](https://arxiv.org/abs/1704.08082)

#### Knowledge Distillation

* __Distilling the Knowledge in a Neural Network__ Hinton et al. 2015 [[arxiv]](https://arxiv.org/abs/1503.02531)

* __Fine-Tuning for Neural Machine Translation with Limited Degradation across In- and Out-of-Domain Data__ Dakwale, Monz 2017 [[pdf]](https://staff.science.uva.nl/c.monz/ltl/publications/mtsummit2017.pdf)
