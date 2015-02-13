---
layout: post
date:  2015-05-16 00:00:00
type: "confpaper"
title: "Revisiting the Impact of Classification Techniques on the Performance of Defect Prediction Models"
authors: "Baljinder Ghotra, <u>Shane McIntosh</u>, and Ahmed E. Hassan"
tags: ["software-quality"]
venue: International Conference on Software Engineering
vtag: ICSE
pubyear: 2015
preprint: http://sail.cs.queensu.ca/publications/pubs/icse2015-ghotra.pdf
pages: "to appear"
acceptance: "84/452 (19%)"
abstract: "Defect prediction models help software quality assurance teams to effectively allocate their limited resources to the most defect-prone software modules. A variety of classification techniques have been used to build defect prediction models ranging from simple (e.g., logistic regression) to advanced techniques (e.g., Multivariate Adaptive Regression Splines (MARS)). Surprisingly, recent research on the NASA dataset suggests that the performance of a defect prediction model is not significantly impacted by the classification technique that is used to train it. However, the dataset that is used in the prior study is both: (a) noisy, i.e., contains erroneous entries and (b) biased, i.e., only contains software developed in one setting. Hence, we set out to replicate this prior study in two experimental settings. First, we apply the replicated procedure to the same (known-to-be noisy) NASA dataset, where we derive similar results to the prior study, i.e., the impact that classification techniques have appear to be minimal. Next, we apply the replicated procedure to two new datasets: (a) the cleaned version of the NASA dataset and (b) the PROMISE dataset, which contains open source software developed in a variety of settings (e.g., Apache, GNU). The results in these new datasets show a clear, statistically distinct separation of groups of techniques, i.e., the choice of classification technique has an impact on the performance of defect prediction models. Indeed, contrary to earlier research, our results suggest that some classification techniques tend to produce defect prediction models that outperform others."
---
@inproceedings{ghotra2015icse,
	Author={Baljinder Ghotra and Shane McIntosh and Ahmed E. Hassan},
	Title = {Revisiting the Impact of Classification Techniques on the Performance of Defect Prediction Models},
	Booktitle = {Proc. of the 37th Int'l Conf. on Software Engineering (ICSE)},
	Pages = {To appear},
	Year = {2015}
}
