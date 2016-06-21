---
layout: post
date:  2016-09-08 00:00:00
type: "confpaper"
title: "The Impact of Task Granularity on Co-evolution Analyses"
authors:
- Keisuke Miura
- Shane McIntosh
- Yasutaka Kamei
- Ahmed E. Hassan
- Naoyasu Ubayashi
tags:
- software-evolution
venue: International Symposium on Empirical Software Engineering and Measurement
vtag: ESEM
pubyear: 2016
pages: To appear
preprint: http://posl.ait.kyushu-u.ac.jp/~kamei/publications/Miura_ESEM2016.pdf
acceptance: "27/122 (22%)"
abstract: "<u>Background</u>: Substantial research in the software evolution field aims to recover knowledge about development from the project history that is archived in repositories, such as a Version Control System (VCS). However, the data that is archived in these repositories can be analyzed at different levels of granularity. Although software evolution is a well-studied phenomenon at the revision-level, revisions may be too fine-grained to accurately represent development tasks.

<br />
<u>Aim</u>: In this paper, we set out to understand the impact that the revision granularity has on co-change analyses.

<br />
<u>Method</u>: We conduct an empirical study of 14 open source systems that are developed by the Apache Software Foundation. To understand the impact that the revision granularity may have on co-change activity, we study work items, i.e., logical groups of revisions that address a single issue.

<br />
<u>Results</u>: We find that work item grouping has the potential to impact co-change activity, since 29% of work items consist of 2 or more revisions in 7 of the 14 studied systems. Deeper quantitative analysis shows that, in 7 of the 14 studied systems: (1) 11% of largest work items are entirely composed of small revisions, and would be missed by traditional approaches to filter or analyze large changes,
(2) 83% of revisions that co-change under a single work item cannot be grouped using the typical configuration of the sliding time window technique
and (3) 48% of work items that involve multiple developers cannot be grouped at the revision-level.

<br />
<u>Conclusions</u>: Since the work item granularity is the natural means that practitioners use to separate development tasks, future software evolution studies, especially co-change analyses, should be conducted at the work item level.
"
---
