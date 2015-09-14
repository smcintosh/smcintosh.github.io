---
layout: post
date:  2015-09-15 00:00:00
type: "journalpaper"
title: "Studying Just-In-Time defect prediction using cross-project models"
authors: "Yasutaka Kamei, Takafumi Fukushima, <u>Shane McIntosh</u>, Kazuhiro Yamashita, Naoyasu Ubayashi, and Ahmed E. Hassan"
tags: ["software-quality"]
venue: Empirical Software Engineering
vtag: EMSE
preprint: "http://posl.ait.kyushu-u.ac.jp/~kamei/publications/Kamei_EMSE2015.pdf"
pages: Accepted
pubyear: 2015
abstract: "Unlike traditional defect prediction models that identify defect-prone modules, Just-In-Time (JIT) defect prediction models identify defect-inducing changes. As such, JIT defect models can provide earlier feedback for developers, while design decisions are still fresh in their minds. Unfortunately, similar to traditional defect models, JIT models require a large amount of training data, which is not available when projects are in initial development phases. To address this limitation in traditional defect prediction, prior work has proposed cross-project models, i.e., models learned from other projects with sufficient history. However, cross-project models have not yet been explored in the context of JIT prediction. Therefore, in this study, we empirically evaluate the performance of JIT models in a cross-project context. Through an empirical study on 11 open source projects, we find that while JIT models rarely perform well in a cross-project context, their performance tends to improve when using approaches that: (1) select models trained using other projects that are similar to the testing project, (2) combine the data of several other projects to produce a larger pool of training data, and (3) combine the models of several other projects to produce an ensemble model. Our findings empirically confirm that JIT models learned using other projects are a viable solution for projects with limited historical data. However, JIT models tend to perform best in a cross-project context when the data used to learn them are carefully selected."
---
@article{kamei2015emse,
	Author={Yasutaka Kamei and Takafumi Fukushima and Shane McIntosh and Kazuhiro Yamashita and Naoyasu Ubayashi and Ahmed E. Hassan},
	Title = {Studying Just-In-Time defect prediction using cross-project models},
	Journal = {Empirical Software Engineering},
	Pages = {To appear},
	Year = {2015}
}
