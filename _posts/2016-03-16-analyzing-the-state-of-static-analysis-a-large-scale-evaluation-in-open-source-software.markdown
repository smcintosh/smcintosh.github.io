---
layout: post
date:  2016-03-16 00:00:00
type: "confpaper"
title: "Analyzing the State of Static Analysis: A Large-Scale Evaluation in Open Source Software"
authors: "Moritz Beller, Radjino Bholanath, <u>Shane McIntosh</u>, and Andy Zaidman"
tags: ["static-analysis", "software-evolution"]
venue: International Conference on Software Analysis, Evolution, and Reengineering
vtag: SANER
pubyear: 2016
pages: To appear
acceptance: "52/140 (37%)"
abstract: "Automatic Static Analysis is an integral part of today's Software Engineering best practices. However, we still do not know a lot about its use in real-world software projects: How prevalent is the use of Automated Static Analysis Tools (ASATs) such as FindBugs and JSHint? How do developers use these tools, and how does their use evolve over time? In our study, we research these questions in the context of nine different ASATs for Java, JavaScript, Ruby, and Python on 168,214 open-source projects. To be able to compare warnings across the ASATs, we introduce the General Defect Classification (GDC) and provide a grounded-theory-derived mapping of their 1,825 different finding types to the 16 top-level GDC classes. Our results show that ASAT use is widespread across projects, but not ubiquitous, and that projects typically do not enforce a strict policy on ASAT use. Most ASAT configurations in the projects deviate slightly from the default, but hardly any introduce new custom analyses. The analyses that are changed deviate per project; only a very small set of default analyses is widely changed. Finally, most ASAT configurations, once introduced, never change. If they do, the changes are small and have a tendency to occur within one day of the configuration's initial introduction."
---
@inproceedings{beller2016saner,
	Author={Moritz Beller and Radjino Bholanath and Shane McIntosh and Andy Zaidman},
	Title = {Analyzing the State of Static Analysis: A Large-Scale Evaluation in Open Source Software},
	Booktitle = {Proc. of the 23rd Int'l Conf. on Software Analysis, Evolution, and Reengineering (SANER)},
	Pages = {To appear},
	Year = {2016}
}
