---
layout: post
date:  2016-05-14 00:00:00
type: "shortconfpaper"
title: "The Dispersion of Build Maintenance Activity across Maven Lifecycle Phases"
authors:
- Casimir Désarmeaux 
- Andrea Pecatikov
- Shane McIntosh
tags:
- software-evolution
- build-systems
venue: Working Conference on Mining Software Repositories
vtag: MSR
track: Mining challenge
pages: 492-495
pubyear: 2016
preprint: /assets/msr2016_desarmeaux.pdf
acceptance: "10/24 (42%)"
abstract: "Build systems describe how source code is translated into deliverables. Developers use build management tools like Maven to specify their build systems. Past work has shown that while Maven provides invaluable features (e.g., incremental building), it introduces an overhead on software development. Indeed, Maven build systems require maintenance. However, Maven build systems follow the build lifecycle, which is comprised of validate, compile, test, packaging, install, and deploy phases. Little is known about how build maintenance activity is dispersed among these lifecycle phases. To bridge this gap, in this paper, we analyze the dispersion of build maintenance activity across build lifecycle phases. Through analysis of 1,181 GitHub repositories that use Maven, we find that: (1) the compile phase accounts for 24% more of the build maintenance activity than the other phases; and (2) while the compile phase generates a consistent amount of maintenance activity over time, the other phases tend to generate peaks and valleys of maintenance activity. Software teams that use Maven should plan for these shifts in the characteristics of build maintenance activity."
---
