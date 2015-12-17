---
layout: post
date:  2015-09-02 00:00:00
type: "confpaper"
title: "An Empirical Study of goto in C Code from GitHub Repositories"
authors: "Meiyappan Nagappan, Romain Robbes, Yasutaka Kamei, Éric Tanter, <u>Shane McIntosh</u>, Audris Mockus, and Ahmed E. Hassan"
tags: ["software-quality"]
venue: Joint meeting of the European Software Engineering Conference and the International Symposium on the Foundations of Software Engineering
vtag: FSE
pubyear: 2015
pages: pp. 404-414
preprint: "http://www.se.rit.edu/~mei/publications/publications/FSE2015-Nagappan.pdf"
acceptance: "74/291 (25%)"
abstract: "It is nearly 50 years since Dijkstra argued that goto obscures the flow of control in program execution and urged programmers to abandon the goto statement. While past research has shown that goto is still in use, little is known about whether goto is used in the unrestricted manner that Dijkstra feared, and if it is 'harmful' enough to be a part of a post-release bug. We, therefore, conduct a two part empirical study: (1) qualitatively analyze a statistically representative sample of 384 files from a population of almost 2 million C programming language files collected from over 11K GitHub repositories and find that developers use goto in C files for error handling (80.21 ± 5%) and cleaning up resources at the end of a procedure (40.36 ± 5%); and (2) quantitatively analyze the commit history from the release branches of six OSS projects and find that no goto statement was removed/modified in the post-release phase of four of the six projects. We conclude that developers limit themselves to using goto appropriately in most cases, and not in an unrestricted manner like Dijkstra feared, thus suggesting that goto does not appear to be harmful in practice."
---
@inproceedings{nagappan2015esecfse,
Author={Meiyappan Nagappan and Romain Robbes and Yasutaka Kamei and \'{E}ric Tanter and Shane McIntosh and Audris Mockus and Ahmed E. Hassan},
	Title = {An Empirical Study of goto in C Code from GitHub Repositories},
	Booktitle = {Proc. of the 10th joint meeting of the European Software Engineering Conference and the Int'l Symposium on the Foundations of Software Engineering (ESEC/FSE)},
  Pages = {404-414},
	Year = {2015}
}
