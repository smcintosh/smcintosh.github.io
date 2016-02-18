---
layout: post
date:  2014-05-31 04:00:00
type: "confpaper"
title: "Collecting and Leveraging a Benchmark of Build System Clones to Aid in Quality Assessments"
authors:
- Shane McIntosh
- Martin Poehlmann
- Elmar Juergens
- Audris Mockus
- Bram Adams
- Ahmed E. Hassan
- Brigitte Haupt
- Christian Wagner
tags:
- build-systems
- code-cloning
venue: International Conference on Software Engineering
vtag: ICSE
track: Software Engineering In Practice (SEIP)
pages: 145-154
volume: 2
pubyear: 2014
acceptance: "25/117 (21%)"
preprint: "http://sail.cs.queensu.ca/Downloads/ICSE2014_CollectingAndLeveragingABenchmarkOfBuildSystemClonesToAidInQualityAssessments.pdf"
slides: "<iframe src='http://www.slideshare.net/slideshow/embed_code/35521924' width='427' height='356' frameborder='0' marginwidth='0' marginheight='0' scrolling='no' style='border:1px solid #CCC; border-width:1px 1px 0; margin-bottom:5px; max-width: 100%;' allowfullscreen> </iframe>"
abstract: "Build systems specify how sources are transformed into deliverables, and hence must be carefully maintained to ensure that deliverables are assembled correctly. Similar to source code, build systems tend to grow in complexity unless specifications are refactored. This paper describes how clone detection can aid in quality assessments that determine if and where build refactoring effort should be applied. We gauge cloning rates in build systems by collecting and analyzing a benchmark comprising 3,872 build systems. Analysis of the benchmark reveals that: (1) build systems tend to have higher cloning rates than other software artifacts, (2) recent build technologies tend to be more prone to cloning, especially of configuration details like API dependencies, than older technologies, and (3) build systems that have fewer clones achieve higher levels of reuse via mechanisms not offered by build technologies. Our findings aided in refactoring a large industrial build system containing 1.1 million lines."
---
