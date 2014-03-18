---
layout: post
date:  2014-05-31 04:00:00
type: "confpaper"
title: "Collecting and Leveraging a Benchmark of Build System Clones to Aid in Quality Assessments"
authors: "<u>Shane McIntosh</u>, Martin Poehlmann, Elmar Juergens, Audris Mockus, Bram Adams, Ahmed E. Hassan, Brigitte Haupt, and Christian Wagner"
tags: ["build-systems", "code-cloning"]
venue: Proc. of the 36th International Conference on Software Engineering (ICSE), Software Engineering In Practice (SEIP) track
pages: vol. 2, pp. 115-124
pubyear: 2014
acceptance: "25/117 (21%)"
preprint: "http://sail.cs.queensu.ca/publications/pubs/icseseip2014-mcintosh.pdf"
abstract: "Build systems specify how sources are transformed into deliverables, and hence must be carefully maintained to ensure that deliverables are assembled correctly. Similar to source code, build systems tend to grow in complexity unless specifications are refactored. This paper describes how clone detection can aid in quality assessments that determine if and where build refactoring effort should be applied. We gauge cloning rates in build systems by collecting and analyzing a benchmark comprising 3,872 build systems. Analysis of the benchmark reveals that: (1) build systems tend to have higher cloning rates than other software artifacts, (2) recent build technologies tend to be more prone to cloning, especially of configuration details like API dependencies, than older technologies, and (3) build systems that have fewer clones achieve higher levels of reuse via mechanisms not offered by build technologies. Our findings aided in refactoring a large industrial build system containing 1.1 million lines."
---
@inproceedings{mcintosh2014icseseip,
	Author={Shane McIntosh and Martin Poehlmann and Elmar Juergens and Audris Mockus and Bram Adams and Ahmed E. Hassan and Brigitte Haupt and Christian Wagner},
	Title = {Collecting and Leveraging a Benchmark of Build System Clones to Aid in Quality Assessments},
	Booktitle = {Proc. of the 36th Int'l Conf. on Software Engineering (ICSE), Software Engineering In Practice (SEIP) track},
	Volume = {2}
	Pages = {115-124},
	Year = {2011}
}
