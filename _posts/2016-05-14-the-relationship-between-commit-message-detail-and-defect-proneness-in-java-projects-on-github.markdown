---
layout: post
date:  2016-05-14 01:00:00
type: "shortconfpaper"
title: "The Relationship between Commit Message Detail and Defect Proneness in Java Projects on GitHub"
authors:
- Jacob G. Barnett
- Charles K. Gathuru
- Luke S. Soldano
- Shane McIntosh
tags:
- software-quality
venue: Working Conference on Mining Software Repositories
vtag: MSR
award: "Mining challenge runner-up"
track: Mining challenge
pages: To appear
preprint: /assets/msr2016_barnett.pdf
pubyear: 2016
acceptance: "10/24 (42%)"
abstract: "Just-In-Time (JIT) defect prediction models aim to predict the commits that will introduce defects in the future. Traditionally, JIT defect prediction models are trained using metrics that are primarily derived from aspects of the code change itself (e.g., the size of the change, the author’s prior experience). In addition to the code that is submitted during a commit, authors write commit messages, which describe the commit for archival purposes. It is our position that the level of detail in these commit messages can provide additional explanatory power to JIT defect prediction models. Hence, in this paper, we analyze the relationship between the defect proneness of commits and commit message volume (i.e., the length of the commit message) and commit message content (approximated using spam filtering technology). Through analysis of JIT models that were trained using 342 GitHub repositories, we find that our JIT models outperform random guessing models, achieving AUC and Brier scores that range between 0.63-0.96 and 0.01-0.21, respectively. Furthermore, our metrics that are derived from commit message detail provide a statistically significant boost to the explanatory power to the JIT models in 43%-80% of the studied systems, accounting for up to 72% of the explanatory power. Future JIT studies should consider adding commit message detail metrics."
---
