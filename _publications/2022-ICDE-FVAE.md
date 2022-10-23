---
title: "Field-aware Variational Autoencoders for Billion-scale User Representation Learning"
collection: publications
permalink: /publication/2022-ICDE-FVAE
excerpt: 'User representation learning plays an essential role in Internet applications, such as recommender systems. Though developing a universal embedding for users is demanding, only few previous works are conducted in an unsupervised learning manner. The unsupervised method is however important as most of the user data is collected without specific labels. In this paper, we harness the unsupervised advantages of Variational Autoencoders (VAEs), to learn user representation from large-scale, high-dimensional, and multi-field data. We extend the traditional VAE by developing Field-aware VAE (FVAE) to model each feature field with an independent multinomial distribution. To reduce the complexity in training, we employ dynamic hash tables, a batched softmax function, and a feature sampling strategy to improve the efficiency of our method. We conduct experiments on multiple datasets, showing that the proposed FVAE significantly outperforms baselines on several tasks of data reconstruction and tag prediction. Moreover, we deploy the proposed method in real-world applications and conduct online A/B tests in a look-alike system. Results demonstrate that our method can effectively improve the quality of recommendation. To the best of our knowledge, it is the first time that the VAE-based user representation learning model is applied to real-world recommender systems.'
date: 2022-05-09
venue: 'Journal 31'
paperurl: 'http://fange.pro/files/2022FVAE.pdf'
citation: 'Fan, Ge, et al. "Field-aware Variational Autoencoders for Billion-scale User Representation Learning." 2022 IEEE 38th International Conference on Data Engineering (ICDE), 2022.'

---
In this paper, we propose a novel model FVAE to learn users' representations from large-scale, high-dimensional, and multi-field user features. We model input data with several independent multinomial distributions, bijectively mapping to different fields.  This effectively extends Mult-VAE to multi-field features. We utilize dynamic hash tables, the batched softmax, and a feature sampling strategy to improve the efficiency of FVAE during training.  We further evaluate the performance of our method on several tasks, including reconstruction and tag prediction and recommender systems. Offline experiments on 3 large-scale datasets show that our method can learn user embedding efficiently and effectively. Our FVAE achieves $12.40\%$ relative improvement on AUC score than state-of-the-art baselines in tag prediction task on a billion-scale dataset. We also conduct experiments on online lookalike systems. Results show that the FVAE outperforms baseline methods in all metrics, demonstrating that the embedding learned by our method can effectively improve the performance of online applications.


Recommended citation: 'Fan, Ge, et al. "Field-aware Variational Autoencoders for Billion-scale User Representation Learning."  2022 IEEE 38th International Conference on Data Engineering (ICDE), 2022.'

```
@INPROCEEDINGS{9835571,
  author={Fan, Ge and Zhang, Chaoyun and Chen, Junyang and Li, Baopu and Xu, Zenglin and Li, Yingjie and Peng, Luyu and Gong, Zhiguo},
  booktitle={2022 IEEE 38th International Conference on Data Engineering (ICDE)}, 
  title={Field-aware Variational Autoencoders for Billion-scale User Representation Learning}, 
  year={2022},
  volume={},
  number={},
  pages={3413-3425},
  doi={10.1109/ICDE53745.2022.00321}}
```

[Download paper here](http://fange.pro/files/2022FVAE.pdf)
