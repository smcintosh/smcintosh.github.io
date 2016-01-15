---
layout: post
date:  2016-03-16 01:00:00
type: "confpaper"
title: "Predicting Build Co-Changes with Source Code Change and Commit Categories"
authors: "Christian Macho, <u>Shane McIntosh</u>, and Martin Pinzger"
tags: ["build-systems"]
venue: International Conference on Software Analysis, Evolution, and Reengineering
vtag: SANER
pages: To appear
pubyear: 2016
acceptance: "52/140 (37%)"
award: "Nominated for best paper award"
abstract: "When software is maintained and evolved the build configuration also needs to be updated. Knowing when to update the build configuration is typically done manually with the risk of missing an update and breaking the build. To mitigate this risk, previous work has investigated prediction models to help developers to identify commits that will likely involve an update of the build configuration.
<p>
In this paper, we investigate whether we can improve these existing prediction models by taking into account detailed information on source code changes and commit categories. Our main hypothesis is that such detailed information on changes will significantly improve the prediction of build co-changes.
</p>
<p>
To that extent, we extract information on changes from 10 Java open source projects and use a random forest classifier to train models that predict build co-changes within and across projects. Our results show significant improvements over existing prediction models: the AUC for intra- and cross-project prediction improves by 11.54% and 9.46% respectively. In addition, we investigate advanced resampling techniques to explore the effect of unbalanced data on our models. The results show that SMOTE can particularly improve prediction models with low performance that were trained on unbalanced data. Our models improve the prediction and enable a better understanding of build co-changes.
</p>
"
---
@inproceedings{macho2016saner,
	Author={Christian Macho and Shane McIntosh and Martin Pinzger},
	Title = {Predicting Build Co-Changes with Source Code Change and Commit Categories},
	Booktitle = {Proc. of the 23rd Int'l Conf. on Software Analysis, Evolution, and Reengineering (SANER)},
	Pages = {To appear},
	Year = {2016}
}
