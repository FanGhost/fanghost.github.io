---
title: "Predicting ratings in multi-criteria recommender systems via a collective factor model"
collection: publications
permalink: /publication/2021-demal-Predicting
excerpt: 'In a multi-criteria recommender system, users are allowed to give an overall rating to an item and provide a score on each of its attribute.  Finding an effective method to exploit a user's multi-criteria ratings to predict the overall rating becomes one of the most important challenges. Among traditional solutions, most of the architectures are not designed in an end-to-end manner. These approaches initially estimate a user's multi-criteria scores, and train a separate model to predict the user's overall rating. This introduces extra training overhead, and the overall prediction accuracy is usually sensitive to its multi-criteria ratings models.  In this paper, we propose a collective model to predict user's overall rating by automatically weighting each of the predicted multi-criteria sub-scores. The proposed architecture integrates the multi-criteria ratings  and the overall rating models in a unified system, which allows to train and perform multi-criteria recommendation in an end-to-end manner. Experiments on 3 real datasets show that our proposed architectures achieve up to 13.14\% lower prediction error over baseline approaches.'
date: 2021-05-01
venue: 'Journal 1'
paperurl: '../files/2021Predicting.pdf'
citation: 'Ge Fan, et al. "Predicting ratings in multi-criteria recommender systems via a collective factor model." Companion Proceedings of the Web Conference 2021: 1-6.'

---

In this paper, we propose an end-to-end collective factor model (CFM) for the multi-criteria recommender system. Our methods integrate loss functions of overall ratings and multi-criteria ratings in a linear manner, such that both overall ratings and multi-criteria ratings are exploited to train the collective factor model. Our model does not need to estimate a user's multi-criteria ratings as a sub-process, which makes the system more robust than two-stages based methods. Experiment results on 3 benchmark datasets show that our methods outperform 8 different baselines, by achieving up to 10.52% and 13.14% lower RMSE and MAE than the state-of-the-art approach CIC.
[Download paper here](../files/2018Preference.pdf)
