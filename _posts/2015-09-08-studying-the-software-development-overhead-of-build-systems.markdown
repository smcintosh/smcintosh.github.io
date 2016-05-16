---
layout: post
date:  2015-09-08 00:00:00
type: "thesis"
vtag: "Theses"
title: "Studying the Software Development Overhead of Build Systems"
phd: yes
authors:
- Shane McIntosh
tags:
- build-systems
- build-performance
address: 557 Goodwin Hall, Kingston, ON, Canada
month: September
venue: "Queen's University"
pages: 1-236
pubyear: 2015
award: "Governor General's academic gold medal"
preprint: "http://hdl.handle.net/1974/13570"
abstract: "Software is developed at a rapid pace. Software development techniques like continuous delivery have shortened the time between official releases of a software system from months or years to a matter of minutes. At the heart of this rapid release cycle of continuously delivered software is the <i>build system</i>, i.e., the system that specifies how source code is translated into deliverables. An efficient build system that quickly produces updated versions of a software system is required to keep up with market competitors. However, the benefits of an efficient build system come at a cost &#8212; build systems introduce overhead on the software development process.
<p>
In this thesis, we use historical data from a large collection of software projects to perform four empirical studies. The focus of these empirical studies is on two types of software development overhead that are introduced by the build system.
</p>
<p>
We first present three empirical studies that focus on the <i>maintenance overhead</i> introduced by the need to keep the build system in sync with the source code that it builds. We observe that: (1) although modern build technologies like Maven provide additional features, they tend to be prone to additional build maintenance activity and more prone to <i>cloning</i>, i.e., duplication of build logic, than older technologies like <tt>make</tt>; (2) although typical cloning rates are higher in build systems than in other software artifacts (e.g., source code), there are commonly-adopted patterns of creative build system abstraction that can keep build cloning rates low; and (3) properties of source and test code changes can be used to train accurate classifiers that indicate whether a co-change to the build system is necessary.
</p>
<p>
We then present an empirical study that focuses on the <i>execution overhead</i> introduced by the slow nature of (re)generating system deliverables using a build system. We find that build optimization effort: (1) will yield more build performance improvement by focusing on <i>build hotspots</i>, i.e., files that are not only slow to rebuild, but also tend to change frequently; and (2) should be aligned with architectural refinement in order to yield the most benefit.
</p>
"
---
