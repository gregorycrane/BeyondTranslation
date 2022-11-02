---
section: History
nav_order: 5
title: 2005- -- Perseus 4.0 
topics: Perseus; History
---



## Original Announcement for Perseus 4.0
Perseus 4.0
May 26, 2005
Features of Perseus 4.0

<ul>
<li>_New back-end digital library software_: This involves fewer software dependencies and simplified design. While the Perl production system managed a number of mirror sites and was used by other sites to support their own collections, it was difficult to install and maintain. We also focused consistently on making the digital library system faster. Many of the functions involved in the system are complex and inherently demanding, but we have been able to speed up almost every aspect of the digital library.
<li>_More modern look and feel_: The new interface makes previously hard-to-find resources that have been available for years more visible. Categories of data previously dispersed between multiple pages are now brought together in an integrated reading environment. The new system is now in closer compliance with current web standards. Display and content have been more consistently separated.
<li>_Services_: Perseus 4.0 is designed to support several services. These include distributed catalog services based on emerging XML standards such as MODS/MADS/SRU/OAI. The Perseus reading environment now also offers discrete XML services for morphological analysis, tables of contents, chunking of larger documents into smaller units, and various categories of searching.
<li>_Interoperability_: The shift to Java has resulted in a much more transparent, object oriented structure, which has resulted in a clearer and readily documented API. Tools such as Jython bring together the clarity of the Java API with the convenience of a scripting language.
<li>_Features to be implemented_: Some of the more advanced searches and other features have not yet been written, but the core functions of the Perseus Digital Library have been implemented. The timeline visualization tool has been completely rewritten. Although substantial progress has been made, the Perseus Atlas remains the single most important component not yet fully implemented in Java. We would prefer to use a third party solution for GIS visualization but have not yet found a solution that is, in our view, adequate.
<li>_Open source_: All versions of the Perseus Digital Library system were designed to be open- source. Third parties did make use of the HyperTalk, Tcl/TK and Perl code underlying the three previous versions, but each of these systems was increasingly complex and difficult to document. Perseus 4.0 was designed from the start to be simpler and to facilitate sharing of code. As the code stabilizes, we plan to publish it on SourceForge. Anyone who wishes to collaborate at an earlier stage should contact us at collections@perseus.tufts.edu.
  
  </ul>
Background
Welcome to Perseus 4.0 -- the fourth and (we hope) final digital library system produced for Perseus. Work on Perseus first began in the late 1980s and used Apple Computer's Hypercard system as a distribution mechanism. Hypercard Perseus underwent extensive development and supported two different CD-ROM versions of Perseus, published by Yale University Press. A second version of the Perseus digital library system, portable over Windows, Macintosh and various forms of Unix, was written in the language Tcl/Tk. Published in 1999 by Yale University Press, this release concluded support for a CD-ROM based Perseus.

Work had already begun in 1995 to create a Web based version of Perseus. Written mostly in Perl, the production version of Perseus evolved over eight years, adding more services and becoming a uniquely powerful platform, capable of ingesting heterogeneous source materials and performing a range of automatic services.

Digital libraries have evolved substantially: the Perl code base reflected organic growth and experimentation -- there were often no real precedents to build on and we felt our way forward. By 2002, digital library systems reflected considerable development and we began looking for third party solutions. We found that most digital libraries concentrated on locating objects and then left it to the users to make what sense they could of what they had found. We were increasingly focused on giving users the tools to understand what the digital library gave them. We depended upon a range of automatic linking, information extraction and visualization services that existing, largely catalogue-oriented systems could not support.

We developed a two-fold strategy.

On the one hand, we identified a long term platform that could provide a home for all the digital objects that we had collected. The Tufts Digital Collections and Archives, with our encouragement, chose FEDORA (Flexible Extensible Digital Object and Repository Architecture) as the foundation for its university repository. An increasing set of Perseus functionality will shift to FEDORA, with the Perseus Digital Library group focusing on new applications and research.

At the same time, the Tufts FEDORA repository was not yet ready to support the demands of our production digital library, where traffic exceeds 10 million pages a month. Most of those pages are constructed dynamically from a range of sources and databases. We chose to build a new digital library system, designing it in such a way that we could move segments of it into FEDORA, as the repository matured.

Transition to Perseus 4.0
Perseus is an experimental digital library, offered freely to users as is, but with no warranty or guarantees. That said, we expect the transition to Perseus 4.0 to be gradual. The version released in May 2005 is very much a work in progress -- some important features have not yet been implemented and some links will fail. We hope that our user community will help us identify problems and work with us to improve this initial effort. To report problems, email bugs@perseus.tufts.edu.

Initially, Perseus 4.0 will have distinct links from the Perl production Perseus, but old links will lead to the new Perseus instead as it becomes more stable. We will do our best to maintain backward compatibility from older links.

Perseus 4.0 does not manage individual images. At present, when you select a thumbnail and call up a full-sized image, you will be taken back to the Perl production version of Perseus. Fedora already has better tools for viewing large scale images than production Perseus and therefore we chose not to rewrite this component of the Perseus digital library. We regret any confusion this more decentralized approach may cause.

We will for now try to maintain the Perl production servers fully while the transition takes place -- we have no plans to remove any existing server capacity. Perl Perseus will be phased out, however, no later than July 1, 2006.
