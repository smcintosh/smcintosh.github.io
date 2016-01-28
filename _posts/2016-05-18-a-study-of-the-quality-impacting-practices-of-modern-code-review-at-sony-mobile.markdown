---
layout: post
date:  2016-05-18 00:00:00
type: "confpaper"
title: "A Study of the Quality-Impacting Practices of Modern Code Review at Sony Mobile"
authors: "Junji Shimagaki, Yasutaka Kamei, <u>Shane McIntosh</u>, Ahmed E. Hassan, and Naoyasu Ubayashi"
tags: ["code-review", "software-quality"]
venue: International Conference on Software Engineering
vtag: ICSE
track: Software Engineering In Practice (SEIP)
pubyear: 2016
pages: To appear
acceptance: "28/108 (26%)"
abstract: "Code review, i.e., the practice of having other team members critique software changes, is a pillar of the modern software quality approach. Nowadays, the variant of the code review process that is adopted by open source and proprietary software projects is flexible, lightweight, and tool-supported (e.g., Gerrit). While this flexibility is a blessing (enabling code reviews to span the globe), it does not mandate minimum review quality criteria like the formal code inspections of the past. Recent work shows that lax reviewing can impact the quality of open source systems. Yet, little is known about the impact that lax reviewing has on the software quality of proprietary systems.

<p>
In this paper, we investigate the impact that code reviewing practices have on the software quality of a large proprietary system that is developed by Sony Mobile. We begin by replicating our open source analyses of the relationship between software quality (as approximated by post-release defect-proneness) and: (1) code review coverage, i.e., the proportion of code changes that have been reviewed and (2) code review participation, i.e., the degree of reviewer involvement in the code review process. We also perform a qualitative analysis, with a survey of 93 stakeholders, semi-structured interviews with 15 stakeholders, and a follow-up survey of 25 senior engineers. Our results indicate that while past measures of review coverage and participation do not share a relationship with defect-proneness at Sony Mobile, reviewing metrics that are aware of the Sony Mobile development context (e.g., the integration of externally developed code, which is not reviewed by Sony Mobile engineers) are associated with defect-proneness. Our results have lead to improvements of the Sony Mobile code review process.
</p>
"
---
@inproceedings{shimagaki2016icseseip,
	Author={Junji Shimagaki and Yasutaka Kamei and Shane McIntosh and Ahmed E. Hassan and Naoyasu Ubayashi},
	Title = {A Study of the Quality-Impacting Practices of Modern Code Review at Sony Mobile},
	Booktitle = {Proc. of the 38th Int'l Conf. on Software Engineering (ICSE)},
  Volume = {2},
	Pages = {To appear},
	Year = {2016}
}
