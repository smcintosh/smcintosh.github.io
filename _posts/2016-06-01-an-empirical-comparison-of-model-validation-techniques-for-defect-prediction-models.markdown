---
layout: post
date: 2016-06-01 00:00:00
type: "journalpaper"
title: "An Empirical Comparison of Model Validation Techniques for Defect Prediction Models"
authors:
- Chakkrit Tantithamthavorn
- Shane McIntosh
- Ahmed E. Hassan
- Kenichi Matsumoto
tags:
- software-quality
- defect-prediction
venue: IEEE Transactions on Software Engineering
vtag: TSE
preprint: http://chakkrit.com/assets/papers/tantithamthavorn2016mvt.pdf
pages: To appear
pubyear: 2016
abstract: "Defect prediction models help software quality assurance teams to allocate their limited resources to the most defect-prone modules. Model validation techniques, such as k-fold cross-validation, use historical data to estimate how well a model will perform in the future. However, little is known about how accurate the estimates of model validation techniques tend to be. In this paper, we investigate the bias and variance of model validation techniques in the domain of defect prediction. Analysis of 101 public defect datasets suggests that 77% of them are highly susceptible to producing unstable results—selecting an appropriate model validation technique is a critical experimental design choice. Based on an analysis of 256 studies in the defect prediction literature, we select the 12 most commonly adopted model validation techniques for evaluation. Through a case study of 18 systems, we find that single-repetition holdout validation tends to produce estimates with 46%-229% more bias and 53%-863% more variance than the top-ranked model validation techniques. On the other hand, out-of-sample bootstrap validation yields the best balance between the bias and variance of estimates in the context of our study. Therefore, we recommend that future defect prediction studies avoid single-repetition holdout validation, and instead, use out-of-sample bootstrap validation."
---
