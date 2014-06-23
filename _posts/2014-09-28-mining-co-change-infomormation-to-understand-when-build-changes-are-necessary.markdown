---
layout: post
date:  2014-09-28 01:00:00
type: "confpaper"
title: "Mining Co-Change Information to Understand when Build Changes are Necessary"
authors: "<u>Shane McIntosh</u>, Bram Adams, Meiyappan Nagappan, and Ahmed E. Hassan"
tags: ["build-systems"]
venue: Proc. of the 30th International Conference on Software Maintenance and Evolution (ICSME)
pages: Accepted
pubyear: 2014
acceptance: "40/210 (19%)"
abstract: "As a software project ages, its source code is modified to add new features, restructure existing ones, and fix defects. These source code changes often induce changes in the build system, i.e., the system that specifies how source code is translated into deliverables. However, since developers are often not familiar with the complex and occasionally archaic technologies used to specify build systems, they may not be able to identify when their source code changes require accompanying build system changes. This can cause build breakages that slow development progress and impact other developers, testers, or even users. In this paper, we mine the source and test code changes that required accompanying build changes in order to better understand this co-change relationship. We build random forest classifiers using language-agnostic and language-specific code change characteristics to explain when code-accompanying build changes are necessary based on historical trends. Case studies of the Mozilla C++ system, the Lucene and Eclipse open source Java systems, and the IBM Jazz proprietary Java system indicate that our classifiers can accurately explain when build co-changes are necessary with an AUC of 0.60-0.88. Unsurprisingly, our highly accurate C++ classifiers (AUC of 0.88) derive much of their explanatory power from indicators of structural change (e.g., was a new source file added?). On the other hand, our Java classifiers are less accurate (AUC of 0.60-0.78) because roughly 75% of Java build co-changes do not coincide with changes to the structure of a system, but rather are instigated by concerns related to release engineering, quality assurance, and general build maintenance."
---
@inproceedings{mcintosh2014icsme,
	Author={Shane McIntosh and Bram Adams and Meiyappan Nagappan and Ahmed E. Hassan},
	Title = {Mining Co-Change Information to Understand when Build Changes are Necessary},
	Booktitle = {Proc. of the 30th Int'l Conf. on Software Maintenance and Evolution (ICSME)},
	Pages = {To appear},
	Year = {2014}
}
