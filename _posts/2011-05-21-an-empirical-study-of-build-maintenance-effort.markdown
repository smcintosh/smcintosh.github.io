---
layout: post
date:  2011-05-21 00:00:00
type: "confpaper"
title: "An Empirical Study of Build Maintenance Effort"
authors:
- Shane McIntosh
- Bram Adams
- Thanh H. D. Nguyen
- Yasutaka Kamei
- Ahmed E. Hassan
tags:
- build-systems
venue: International Conference on Software Engineering
vtag: ICSE
pages: 141-150
pubyear: 2011
acceptance: "62/441 (14%)"
preprint: "http://sail.cs.queensu.ca/Downloads/ICSE2011_AnEmpiricalStudyOfBuildMaintenanceEffort.pdf"
slides: "<iframe src='http://www.slideshare.net/slideshow/embed_code/8089833' width='427' height='356' frameborder='0' marginwidth='0' marginheight='0' scrolling='no' style='border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;' allowfullscreen> </iframe>"
abstract: "The build system of a software project is responsible for transforming source code and other development artifacts into executable programs and deliverables. Similar to source code, build system specifications require maintenance to cope with newly implemented features, changes to imported Application Program Interfaces (APIs), and source code restructuring. In this paper, we mine the version histories of one proprietary and nine open source projects of different sizes and domain to analyze the overhead that build maintenance imposes on developers. We split our analysis into two dimensions: (1) Build Coupling, i.e., how frequently source code changes require build changes, and (2) Build Ownership, i.e., the proportion of developers responsible for build maintenance. Our results indicate that, despite the difference in scale, the build system churn rate is comparable to that of the source code, and build changes induce more relative churn on the build system than source code changes induce on the source code. Furthermore, build maintenance yields up to a 27% overhead on source code development and a 44% overhead on test development. Up to 79% of source code developers and 89% of test code developers are significantly impacted by build maintenance, yet investment in build experts can reduce the proportion of impacted developers to 22% of source code developers and 24% of test code developers."
---
