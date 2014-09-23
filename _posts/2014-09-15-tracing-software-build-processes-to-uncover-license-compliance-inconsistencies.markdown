---
layout: post
date:  2014-09-15 00:00:00
type: "confpaper"
title: "Tracing Software Build Processes to Uncover License Compliance Inconsistencies"
authors: "Sander van der Burg, Eelco Dolstra, <u>Shane McIntosh</u>, Julius Davies, Daniel M. German, and Armijn Hemel"
tags: ["build-systems", "software-licensing"]
venue: Proc. of the 29th International Conference on Automated Software Engineering (ASE)
pages: pp. 731-741
pubyear: 2014
acceptance: "55/276 (20%)"
slides: "<iframe src='http://www.slideshare.net/slideshow/embed_code/39283036' width='476' height='400' frameborder='0' marginwidth='0' marginheight='0' scrolling='no'></iframe>"
preprint: "/assets/ase2014_vanderburg.pdf"
abstract: "Open Source Software (OSS) components form the basis for many software systems. While the use of OSS components accelerates development, client systems must comply with the license terms of the OSS components that they use. Failure to do so exposes client system distributors to possible litigation from copyright holders. Yet despite the importance of license compliance, tool support for license compliance assessment is lacking. In this paper, we propose an approach to extract and analyze the Concrete Build Dependency Graph (CBDG) of a software system by tracing system calls that occur at build-time. Through a case study of seven open source systems, we show that the extracted CBDGs: (1) accurately classify sources as included in or excluded from deliverables with 88%-100% precision and 98%-100% recall, and (2) can uncover license compliance inconsistencies in real software systems - two of which prompted code fixes in the CUPS and FFmpeg systems."
---
@inproceedings{vanderburg2014ase,
	Author={Sander van der Burg and Eelco Dolstra and Shane McIntosh and Julius Davies and Daniel M. German and Armijn Hemel},
	Title = {Tracing Software Build Processes to Uncover License Compliance Inconsistencies},
	Booktitle = {Proc. of the 29th Int'l Conf. on Automated Software Engineering (ASE)},
	Pages = {731-741},
	Year = {2014}
}
