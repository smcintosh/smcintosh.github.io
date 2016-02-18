---
layout: post
date:  2015-07-09 00:00:00
type: "journalpaper"
title: "Identifying and Understanding Header File Hotspots in C/C++ Build Processes"
authors:
- Shane McIntosh
- Bram Adams
- Meiyappan Nagappan
- Ahmed E. Hassan
tags:
- build-systems
- build-performance
venue: Automated Software Engineering
preprint: http://sail.cs.queensu.ca/Downloads/ASE_IdentifyingAndUnderstandingHeaderFileHotspotsInC,C++BuildProcesses.pdf
vtag: AUSE
pages: To appear
pubyear: 2015
abstract: "Software developers rely on a fast build system to incrementally compile their source code changes and produce modified deliverables for testing and deployment. Header files, which tend to trigger slow rebuild processes, are most problematic if they also change frequently during the development process, and hence, need to be rebuilt often. In this paper, we propose an approach that analyzes the build dependency graph (i.e., the data structure used to determine the minimal list of commands that must be executed when a source code file is modified), and the change history of a software system to pinpoint header file hotspots --- header files that change frequently and trigger long rebuild processes. Through a case study on the GLib, PostgreSQL, Qt, and Ruby systems, we show that our approach identifies header file hotspots that, if improved, will provide greater improvement to the total future build cost of a system than just focusing on the files that trigger the slowest rebuild processes, change the most frequently, or are used the most throughout the codebase. Furthermore, regression models built using architectural and code properties of source files can explain 32%-57% of these hotspots, identifying subsystems that are particularly hotspot-prone and would benefit the most from architectural refinement."
---
