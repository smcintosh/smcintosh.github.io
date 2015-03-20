---
layout: post
date:  2015-03-02 00:00:00
type: "confpaper"
title: "Cross-Project Build Co-change Prediction"
authors: "Xin Xia, David Lo, <u>Shane McIntosh</u>, Emad Shihab, and Ahmed E. Hassan"
tags: ["build-systems"]
venue: International Conference on Software Analysis, Evolution, and Reengineering
vtag: SANER
pubyear: 2015
pages: "pp. 311-320"
preprint: "http://sail.cs.queensu.ca/publications/pubs/saner2015-xia.pdf"
acceptance: "46/144 (32%)"
slides: "<iframe src='//www.slideshare.net/slideshow/embed_code/45524826' width='425' height='355' frameborder='0' marginwidth='0' marginheight='0' scrolling='no' style='border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;' allowfullscreen> </iframe> <div style='margin-bottom:5px'> </div>"
abstract: "Build systems orchestrate how human-readable source code is translated into executable programs. In a software project, source code changes can induce changes in the build system (aka. build co-changes). It is difficult for developers to identify when build co-changes are necessary due to the complexity of build systems. Prediction of build co-changes works well if there is a sufficient amount of training data to build a model. However, in practice, for new projects, there exists a limited number of changes. Using training data from other projects to predict the build co-changes in a new project can help improve the performance of the build co-change prediction. We refer to this problem as cross-project build co-change prediction.
<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this paper, we propose CroBuild, a novel cross-project build co-change prediction approach that iteratively learns new classifiers. CroBuild constructs an ensemble of classifiers by iteratively building classifiers and assigning them weights according to its prediction error rate. Given that only a small proportion of code changes are build co-changing, we also propose an imbalance-aware approach that learns a threshold boundary between those code changes that are build co-changing and those that are not in order to construct classifiers in each iteration. To examine the benefits of CroBuild, we perform experiments on 4 large datasets including Mozilla, Eclipse-core, Lucene, and Jazz, comprising a total of 50,884 changes. On average, across the 4 datasets, CroBuild achieves a F1-score of up to 0.408. We also compare CroBuild with other approaches such as a basic model, AdaBoost proposed by Freund et al., and TrAdaBoost proposed by Dai et al.. On average, across the 4 datasets, the CroBuild approach yields an improvement in F1-scores of 41.54%,  36.63%, and 36.97% over the basic model, AdaBoost, and TrAdaBoost, respectively."
---
@inproceedings{xia2015saner,
	Author={Xin Xia and David Lo and Shane McIntosh and Emad Shihab and Ahmed E. Hassan},
	Title = {Cross-Project Build Co-change Prediction},
	Booktitle = {Proc. of the 22nd Int'l Conf. on Software Analysis, Evolution, and Reengineering (SANER)},
	Pages = {311-320},
	Year = {2015}
}
