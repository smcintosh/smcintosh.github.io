---
layout: post
date:  2016-05-18 00:00:00
type: "confpaper"
title: "Automated Parameter Optimization of Classification techniques for Defect Prediction Models"
authors:
- Chakkrit Tantithamthavorn
- Shane McIntosh
- Ahmed E. Hassan
- Kenichi Matsumoto
tags:
- software-quality
venue: International Conference on Software Engineering
vtag: ICSE
pubyear: 2016
preprint: http://sail.cs.queensu.ca/Downloads/2016icse_AutomatedParametersOptimizationOfClassificationTechniquesForDefectPredictionModels.pdf
pages: 321-332
acceptance: "101/530 (19%)"
abstract: "Defect prediction models are classifiers that are trained to identify defect-prone software modules. Such classifiers have configurable parameters that control their characteristics (e.g., the number of trees in a random forest classifier). Recent studies show that these classifiers may underperform due to the use of suboptimal default parameter settings.  However, it is impractical to assess all of the possible settings in the parameter spaces. In this paper, we investigate the performance of defect prediction models where Caret, an automated parameter optimization technique, has been applied. Through a case study of 18 datasets from systems that span both proprietary and open source domains, we find that (1) Caret improves the AUC performance of defect prediction models by as much as 40 percentage points; (2) Caret-optimized classifiers are at least as stable as (with 35% of them being more stable than) classifiers that are trained using the default settings; and (3) Caret increases the likelihood of producing a top-performing classifier by as much as 83%. Hence, we conclude that parameter settings can indeed have a large impact on the performance of defect prediction models. Indeed, automated parameter optimization should be considered for use in future defect prediction studies."
---
