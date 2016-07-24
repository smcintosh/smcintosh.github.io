---
layout: post
date: 2016-07-24 00:00:00
type: "journalpaper"
title: "The Use of Summation to Aggregate Software Metrics Hinders the Performance of Defect Prediction Models"
authors:
- Feng Zhang
- Ahmed E. Hassan
- Shane McIntosh
- Ying Zou
tags:
- software-quality
- defect-prediction
venue: IEEE Transactions on Software Engineering
vtag: TSE
pages: To appear
pubyear: 2016
abstract: "Defect prediction models help software organizations to anticipate where defects will appear in the future. When training a defect prediction model, historical defect data is often mined from a Version Control System (VCS, e.g., Subversion), which records software changes at the file-level. Software metrics, on the other hand, are often calculated at the class- or method-level (e.g., McCabe's Cyclomatic Complexity). To address the disagreement in granularity, the class- and method-level software metrics are aggregated to file-level, often using summation (i.e., McCabe of a file is the sum of the McCabe of all methods within the file). A recent study shows that summation significantly inflates the correlation between Source Lines Of Code (SLOC) and Cyclomatic Complexity (CC) in Java projects. While there are many other aggregation schemes (e.g., central tendency, dispersion), they have remained unexplored in the scope of defect prediction.<br />
<br />
In this study, we set out to investigate how different aggregation schemes impact defect prediction models. Through an analysis of 11 aggregation schemes using data collected from 255 open source projects, we find that: (1) aggregation schemes can significantly alter correlations among metrics, as well as the correlations between metrics and the defect count; (2) when constructing models to predict defect proneness, applying only the summation scheme (i.e., the most commonly used aggregation scheme in the literature) only achieves the best performance in 11% of the studied projects, while applying all of the studied aggregation schemes achieves the best performance in 40% of the studied projects; (3) when constructing models to predict defect rank or count, either applying only the summation or applying all of the studied aggregation schemes achieves similar performance, with both achieving the closest to the best performance more often than the other studied aggregation schemes; and (4) when constructing models for effort-aware defect prediction, the mean or median aggregation schemes yield performance values that are significantly closer to the best performance than any of the other studied aggregation schemes. Broadly speaking, the performance of defect prediction models are often underestimated due to our community's tendency to only use the summation aggregation scheme. Given the potential benefit of applying additional aggregation schemes, we advise that future defect prediction models should explore a variety of aggregation schemes."
---
