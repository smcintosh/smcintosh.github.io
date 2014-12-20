---
layout: post
date:  2015-05-16 00:00:00
type: "confpaper"
title: "Revisiting the Impact of Classification Techniques on the Performance of Defect Prediction Models"
authors: "Baljinder Ghotra, <u>Shane McIntosh</u>, and Ahmed E. Hassan"
tags: ["software-quality"]
venue: Proc. of the 37th International Conference on Software Engineering (ICSE)
pubyear: 2015
pages: "to appear"
acceptance: "84/452 (19%)"
abstract: "Defect prediction models help software quality assurance teams in effectively allocating their limited resources to defect-prone software modules. A variety of classification techniques have been used to build defect prediction models ranging from simple (e.g., logistic regression) to advanced techniques (e.g., Multivariate Adaptive Regression Splines (MARS)). Surprisingly, recent research on the NASA dataset suggests that the performance of a defect prediction model is not significantly impacted by the technique used to train it. However, the dataset, that is used in the prior study is both: (a) noisy, i.e., contains erroneous entries and (b) biased, i.e., only contains software developed in one setting. Hence, we set out to replicate this prior study using a cleaned version of the original NASA dataset, as well as on a new dataset containing open source software developed in a variety of settings (e.g., Apache, GNU). Our study shows the same pattern of statistical grouping (i.e., the impact of techniques is minimal) of techniques as found by the previous study. However, using the cleaned NASA dataset and the open source datasets from the PROMISE repository, we observe a clear separation of statistical groups of techniques (i.e., techniques impact the performance of classification models). Contrary to earlier research, we find that some classification techniques produce models that outperform others on the cleaned version of the NASA dataset and open source datasets."
---
@inproceedings{ghotra2015icse,
	Author={Baljinder Ghotra and Shane McIntosh and Ahmed E. Hassan},
	Title = {Revisiting the Impact of Classification Techniques on the Performance of Defect Prediction Models},
	Booktitle = {Proc. of the 37th Int'l Conf. on Software Engineering (ICSE)},
	Pages = {To appear},
	Year = {2015}
}
