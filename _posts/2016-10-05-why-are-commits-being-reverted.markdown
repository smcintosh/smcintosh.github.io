---
layout: post
date:  2016-10-05 00:00:00
type: "confpaper"
title: "Why are Commits being Reverted? A Comparative Study of Industrial and Open Source Projects"
authors:
- Junji Shimagaki
- Yasutaka Kamei
- Shane McIntosh
- David Pursehouse
- Naoyasu Ubayashi
tags:
- software-evolution
venue: International Conference on Software Maintenance and Evolution
vtag: ICSME
preprint: http://posl.ait.kyushu-u.ac.jp/~kamei/publications/Shimagaki_ICSME2016.pdf
pubyear: 2016
pages: To appear
acceptance: "37/127 (29%)"
abstract: "Software development is a cyclic process of integrating new features while introducing and fixing defects. During development, commits that modify source code files are uploaded to the version control systems of projects. Occasionally, these commits need to be reverted, i.e., the code changes need to be completely backed out of the software project. While one can often speculate about the purpose of reverted commits (e.g., the commit may have caused integration or build problems), little empirical evidence exists to substantiate such claims. The goal of this paper is to better understand why commits are reverted in large software systems. To that end, we quantitatively study two proprietary and four open source projects to measure: (1) the proportion of commits that are reverted, (2) the amount of time that commits that are eventually reverted persist within a codebase, and (3) the most frequent reasons why commits are reverted. Our results show that 1%-5% of the commits in the studied systems are reverted. Those commits that are eventually reverted persist within the codebase for 1-35 days (median). Furthermore, we identify 13 common reasons for reverting commits, and the distribution of reasons for reverted commits varies broadly from project to project. A complementary qualitative analysis suggests that many reverted commits could have been avoided with better team communication and change awareness. These results have been used to make improvements to the Sony Mobile development process."
---
