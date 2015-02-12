---
layout: post
date:  2015-05-16 00:00:00
type: "confpaper"
title: "The Impact of Mislabelling on the Performance and Interpretation of Defect Prediction Models"
authors: "Chakkrit Tantithamthavorn, <u>Shane McIntosh</u>, Ahmed E. Hassan, Akinori Ihara, and Ken-ichi Matsumoto"
tags: ["software-quality"]
venue: International Conference on Software Engineering
vtag: ICSE
pubyear: 2015
preprint: http://sail.cs.queensu.ca/publications/pubs/icse2015-tantithamthavorn.pdf
pages: "to appear"
acceptance: "84/452 (19%)"
abstract: "The reliability of a prediction model depends on the quality of the data from which it was trained. Therefore, defect prediction models may be unreliable if they are trained using noisy data. Recent research suggests that randomly-injected noise that changes the classification (label) of software modules from defective to clean (and vice versa) can impact the performance of defect models. Yet, in reality, incorrectly labelled (i.e., mislabelled) issue reports are likely non-random. In this paper, we study whether mislabelling is random, and the impact that realistic mislabelling has on the performance and interpretation of defect models. Through a case study of 3,931 manually-curated issue reports from the Apache Jackrabbit and Lucene systems, we find that: (1) issue report mislabelling is not random; (2) precision is rarely impacted by mislabelled issue reports, suggesting that practitioners can rely on the accuracy of modules labelled as defective by models that are trained using noisy data; (3) however, models trained on noisy data typically achieve 56%-68% of the recall of models trained on clean data; and (4) only the metrics in top influence rank of our defect models are robust to the noise introduced by mislabelling, suggesting that the less influential metrics of models that are trained on noisy data should not be interpreted or used to make decisions."
---
@inproceedings{tantithamthavorn2015icse,
	Author={Chakkrit Tantithamthavorn and Shane McIntosh and Ahmed E. Hassan and Akinori Ihara and Ken-ichi Matsumoto},
	Title = {The Impact of Mislabelling on the Performance and Interpretation of Defect Prediction Models},
	Booktitle = {Proc. of the 37th Int'l Conf. on Software Engineering (ICSE)},
	Pages = {To appear},
	Year = {2015}
}
