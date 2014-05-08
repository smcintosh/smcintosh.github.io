---
layout: post
date:  2014-05-31 01:00:00
type: "confpaper"
title: "An Empirical Study of Just-In-Time Defect Prediction Using Cross-Project Models"
authors: "Takafumi Fukushima, Yasutaka Kamei, <u>Shane McIntosh</u>, Kazuhiro Yamashita, and Naoyasu Ubayashi"
tags: ["software-quality"]
venue: Proc. of the 11th Working Conference on Mining Software Repositories (MSR)
pages: pp. 172-181
pubyear: 2014
acceptance: "29/85 (34%)"
preprint: "http://posl.ait.kyushu-u.ac.jp/~kamei/publications/Fukushima_MSR2014.pdf"
abstract: "Prior research suggests that predicting defect-introducing changes, i.e., Just-In-Time (JIT) defect prediction is a more practical alternative to traditional defect prediction techniques, providing immediate feedback while design decisions are still fresh in the minds of developers. Unfortunately, similar to traditional defect prediction models, JIT models require a large amount of training data, which is not available when projects are in initial development phases. To address this flaw in traditional defect prediction, prior work has proposed cross-project models, i.e., models learned from older projects with sufficient history. However, cross-project models have not yet been explored in the context of JIT prediction. Therefore, in this study, we empirically evaluate the performance of JIT cross-project models. Though a case study on 11 open source projects, we find that in a JIT cross-project context: (1) high performance within-project models rarely perform well; (2) models trained on projects that have similar correlations between predictor and dependent variables often perform well; and (3) ensemble learning techniques that leverage historical data from several other projects (e.g., voting experts) often perform well. Furthermore, we attain the highest performance from cross-project models when the training data is weighted based on similarity with the testing data prior to applying ensemble techniques. Our findings empirically confirm that JIT cross-project models learned using other projects are a viable solution for projects with little historical data. However, JIT cross-project models perform best when the data used to learn them is carefully selected."
---
@inproceedings{fukushima2014msr,
	Author={Takafumi Fukushima and Yasutaka Kamei and Shane McIntosh and Kazuhiro Yamashita and Naoyasu Ubayashi},
	Title = {An Empirical Study of Just-In-Time Defect Prediction Using Cross-Project Models},
	Booktitle = {Proc. of the 11th Working Conf. on Mining Software Repositories (MSR)},
	Pages = {11-20},
	Year = {2014}
}
