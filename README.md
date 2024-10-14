# Awesome-Weakly Supervised Facial Behavior Analysis

A curated list of weakly supervised learning methods for facial behavior analysis in both classification and regression tasks based on our survey paper "Weakly Supervised Learning for Facial Behavior Analysis: A Review". In addition, this repository includes basic datasets widely used in the framework of weakly supervised learning for facial behavior analysis. 

[[arXiv]](https://arxiv.org/abs/2101.09858)

If you find this work useful in your research, please consider citing our work :pencil: and giving a star :star2: :
```bibtex
@article{granger2021weakly,
  title={Weakly supervised learning for facial behavior analysis: A review},
  author={Praveen, R. Gnana and Cardinal, Patrick and Granger, Eric},
  journal={arXiv preprint arXiv:2101.09858},
  year={2021}
}
```


👀 Update frequently!

## 📋 What's New

- [May. 2024] Create awesome-Weakly Supervised Facial Behavior Analysis repository.

## 👥 Contributing
Please feel free to refer this repository for your FER research/development and send me [pull requests](https://github.com/kdhht2334/awesome-SOTA-FER/pulls) or email [Praveen](praveenrgp1988@gmail.com) to add links.


## Table of Contents

- [Classification](#seven-emotion) <a id="seven-emotion"></a>
  - [Inexact Supervised Learning](#2024-c)
  - [Incomplete Supervised Learning](#2023-c)
  - [Inaccurate Supervised Learning](#2022-c)


## Classification <a id="seven-emotion"></a>

### Inexact Supervised Learning <a id="2024-c"></a>

| Paper | Venue | Year | Code | Task
| :---  | :---: | :---:  | :---:| :---:|
| [Weakly supervised pain localization using multiple instance learning](https://ieeexplore.ieee.org/document/6553762) | FG | 2013 | N/A | Pain |
| [Multi-instance Hidden Markov Model for facial expression recognition](https://ieeexplore.ieee.org/document/7163116) | FG | 2015 | N/A | Expression |
| [Learning pain from au combinations: A weakly supervised approach via multiple instance learning](https://ieeexplore.ieee.org/document/8887215) | IEEE TAFFC | 2022 | N/A | Pain |
| [Regularized Multi-Concept MIL for weakly-supervised facial behavior categorization](https://www.upf.edu/documents/8407855/8409953/RMCMIL_BMVC2014.pdf/70cf3e1b-e407-31a7-434f-bbad149c9966) | BMVC | 2014 | N/A | Expression
| [Lomo: Latent ordinal model for facial analysis in videos](https://ieeexplore.ieee.org/document/7780971) | CVPR | 2016 | N/A | Expression
| [Identifying user-specific facial affects from spontaneous expressions with minimal annotation](https://ieeexplore.ieee.org/abstract/document/7308029) | IEEE TAFFC | 2016 | N/A | Expression
| [From Emotions to Action Units with Hidden and Semi-Hidden-Task Learning](https://ieeexplore.ieee.org/document/7410779) | ICCV | 2015 | N/A | AU
| [Exploring Domain Knowledge for Facial Expression-Assisted Action Unit Activation Recognition](https://ieeexplore.ieee.org/abstract/document/8329513) | IEEE TAFFC | 2020 | N/A | AU
| [Weakly supervised facial action unit recognition through adversarial training](https://ieeexplore.ieee.org/document/8578331) | CVPR | 2018 | N/A | AU
| [Weakly Supervised Facial Action Unit Recognition With Domain Knowledge](https://ieeexplore.ieee.org/abstract/document/8472814) | IEEE TCYB | 2018 | N/A | AU
| [Classifier Learning With Prior Probabilities for Facial Action Unit Recognition](https://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Classifier_Learning_With_CVPR_2018_paper.html) | CVPR | 2018 | N/A | AU


### Incomplete Supervised Learning <a id="2024-c"></a>

| Paper | Venue | Year | Code | Task
| :---  | :---: | :---:  | :---:| :---:|
| [A Weakly Supervised learning technique for classifying facial expressions](https://www.sciencedirect.com/science/article/abs/pii/S0167865518304161) | PRL | 2019 | N/A | Expressions
| [Towards Semi-Supervised Deep Facial Expression Recognition With an Adaptive Confidence Margin](https://ieeexplore.ieee.org/document/9880204) | CVPR | 2022 | [Github](https://github.com/hangyu94/Ada-CM) | Expressions
| [Boosting Facial Expression Recognition by A Semi-Supervised Progressive Teacher](https://ieeexplore.ieee.org/abstract/document/9629313) | IEEE TAFFC | 2023 | N/A | Expressions
| [Margin-Mix: Semi–Supervised Learning for Face Expression Recognition](https://link.springer.com/chapter/10.1007/978-3-030-58592-1_1) | ECCV | 2020 | N/A | Expressions
| [Rethinking Pseudo-Labeling for Semi-Supervised Facial Expression Recognition With Contrastive Self-Supervised Learning](https://ieeexplore.ieee.org/abstract/document/10121455) | IEEE Access | 2023 | N/A | Expressions
| [Semi-supervised facial expression recognition using reduced spatial features and Deep Belief Networks](https://www.sciencedirect.com/science/article/abs/pii/S0925231219311579) | Neurocomputing | 2019 | N/A | Expressions
| [Exploiting Sparsity and Co-occurrence Structure for Action Unit Recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7163081) | FG | 2015 | N/A | AU
| [Multi-label learning with missing labels for image annotation and facial action unit recognition](https://www.sciencedirect.com/science/article/abs/pii/S0031320315000412) | PR | 2015 | N/A | AU
| [Facial action unit recognition under incomplete data based on multi-label learning with missing labels](https://www.sciencedirect.com/science/article/abs/pii/S0031320316301583) | PR | 2016 | N/A | AU
| [Handling missing labels and class imbalance challenges simultaneously for facial action unit recognition](https://link.springer.com/article/10.1007/s11042-018-6836-1) | MTA | 2019 | N/A | AU
| [Expression-assisted facial action unit recognition under incomplete AU annotation](https://www.sciencedirect.com/science/article/abs/pii/S0031320316301765) | PR | 2017 | N/A | AU
| [Dual Semi-Supervised Learning for Facial Action Unit Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/4909) | AAAI | 2019 | N/A | AU
| [Deep Facial Action Unit Recognition From Partially Labeled Data](https://openaccess.thecvf.com/content_iccv_2017/html/Wu_Deep_Facial_Action_ICCV_2017_paper.html) | ICCV | 2017 | N/A | AU
| [Multi-label Co-regularization for Semi-supervised Facial Action Unit Recognition](https://proceedings.neurips.cc/paper_files/paper/2019/hash/cf67355a3333e6e143439161adc2d82e-Abstract.html) | NeurIPS | 2019 | [Github](https://github.com/nxsEdson/MLCR) | AU


### Inaccurate Supervised Learning <a id="2024-c"></a>

| Paper | Venue | Year | Code | Task
| :---  | :---: | :---:  | :---:| :---:|
| [Suppressing Uncertainties for Large-Scale Facial Expression Recognition](https://openaccess.thecvf.com/content_CVPR_2020/html/Wang_Suppressing_Uncertainties_for_Large-Scale_Facial_Expression_Recognition_CVPR_2020_paper.html) | CVPR | 2020 | [Github](https://github.com/kaiwang960112/Self-Cure-Network) | Expressions
| [Relative Uncertainty Learning for Facial Expression Recognition](https://proceedings.neurips.cc/paper/2021/hash/9332c513ef44b682e9347822c2e457ac-Abstract.html) | NeurIPS | 2021 | [Github](https://github.com/zyh-uaiaaaa/Relative-Uncertainty-Learning) | Expressions
| [Dive Into Ambiguity: Latent Distribution Mining and Pairwise Uncertainty Estimation for Facial Expression Recognition](https://openaccess.thecvf.com/content/CVPR2021/html/She_Dive_Into_Ambiguity_Latent_Distribution_Mining_and_Pairwise_Uncertainty_Estimation_CVPR_2021_paper.html) | CVPR | 2021 | N/A | Expressions
| [Teaching with Soft Label Smoothing for Mitigating Noisy Labels in Facial Expressions](https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/2267_ECCV_2022_paper.php) | ECCV | 2022 | [Github](https://github.com/toharl/soft) | Expressions
| [Self-Paced Label Distribution Learning for In-The-Wild Facial Expression Recognition](https://dl.acm.org/doi/abs/10.1145/3503161.3547960) | ACM MM | 2022 | N/A | Expressions
| [Training deep networks for facial expression recognition with crowd-sourced label distribution](https://dl.acm.org/doi/abs/10.1145/2993148.2993165) | ACM ICMI | 2016 | N/A | Expressions
| [Facial Expression Recognition with Inconsistently Annotated Datasets](https://openaccess.thecvf.com/content_ECCV_2018/html/Jiabei_Zeng_Facial_Expression_Recognition_ECCV_2018_paper.html) | ECCV | 2018 | N/A | Expressions
| [MAN: Mining Ambiguity and Noise for Facial Expression Recognition in the Wild](https://www.sciencedirect.com/science/article/abs/pii/S0167865522003105) | PRL | 2022 | N/A | Expressions
| [Learn from All: Erasing Attention Consistency for Noisy Label Facial Expression Recognition](https://link.springer.com/chapter/10.1007/978-3-031-19809-0_24) | ECCV | 2022 | [Github](https://github.com/zyh-uaiaaaa/Erasing-Attention-Consistency) | Expressions
| [Reliable Crowdsourcing and Deep Locality-Preserving Learning for Expression Recognition in the Wild](https://openaccess.thecvf.com/content_cvpr_2017/html/Li_Reliable_Crowdsourcing_and_CVPR_2017_paper.html) | CVPR | 2017 | N/A | Expressions









