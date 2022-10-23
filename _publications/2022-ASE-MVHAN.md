---
title: "MV-HAN: A Hybrid Attentive Networks based Multi-View Learning Model for Large-scale Contents Recommendation"
collection: publications
permalink: /publication/2022-ASE-MVHAN
excerpt: 'Industrial recommender systems usually employ multi-source data to improve the recommendation quality, while effectively sharing information between different data sources remain a challenge. In this paper, we introduce a novel Multi-View Approach with Hybrid Attentive Networks (MV-HAN) for contents retrieval at the matching stage of recommender systems. The proposed model enables high-order feature interaction from various input features while effectively transferring knowledge between different types. By employing a well-placed parameters sharing strategy, the MV-HAN substantially improves the retrieval performance in sparse types. The designed MV-HAN inherits the efficiency advantages in the online service from the two-tower model, by mapping users and contents of different types into the same features space. This enables fast retrieval of similar contents with an approximate nearest neighbor algorithm. We conduct offline experiments on several industrial datasets, demonstrating that the proposed MV-HAN significantly outperforms baselines on the content retrieval tasks. Importantly, the MV-HAN is deployed in a real-world matching system. Online A/B test results show that the proposed method can significantly improve the quality of recommendations.'
date: 2022-10-13
venue: 'Journal 31'
paperurl: 'http://fange.pro/files/2022MVHAN.pdf'
citation: 'Fan, Ge, et al. "MV-HAN: A Hybrid Attentive Networks based Multi-View Learning Model for Large-scale Contents Recommendation
." In 37th IEEE/ACM International Conference on Automated Software Engineering (ASE ’22), 2022.'

---
In this paper, we propose a novel model called MV-HAN for the matching stage in recommender systems. We design a hybrid neural structure configured with different models, including MLPs and multi-head self-attentive neural networks. The proposed method transfers the knowledge from the source types to the target types, which helps better representation learning for users and contents. Moreover, the MV-HAN shares parameters of the bottom networks to mitigate the cold start on the spare types. Offline experiment results on industrial datasets show that the proposed method outperforms different baselines, i.e., achieving up to 4.43\% and 4.64\% higher AUC and HR than the best results of baseline methods on the SC dataset. 
Online experiment results on real-world recommender  systems show that the MV-HAN significantly improves the recommendation performance compared with baseline methods in all metrics. It verifies that the MV-HAN is able to handle multi-source asynchronous dataflows and extract information from different content types in real-world applications. 

Recommended citation: 'Ge Fan, Chaoyun Zhang, Kai Wang, and Junyang Chen. 2022. MV-HAN: A Hybrid Attentive Networks based Multi-View Learning Model for Largescale Contents Recommendation. In 37th IEEE/ACM International Conference on Automated Software Engineering (ASE ’22), October 10–14, 2022, Rochester, MI, USA. ACM, New York, NY, USA, 5 pages. https://doi.org/10.1145/3551349.3559496'

```
@INPROCEEDINGS{fan2022mvhan,
  author={Fan, Ge and Zhang, Chaoyun and Wang, Kai and Chen, Junyang},
  booktitle={37th IEEE/ACM International Conference on Automated Software Engineering (ASE ’22)}, 
  title={MV-HAN: A Hybrid Attentive Networks based Multi-View Learning Model for Largescale Contents Recommendation}, 
  year={2022},
  volume={},
  number={},
  pages={},
  doi={10.1145/3551349.3559496}}
```

[Download paper here](http://fange.pro/files/2022MVHAN.pdf)
