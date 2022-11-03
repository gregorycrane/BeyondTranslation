---
section_id: Earlier Versions of Perseus
nav_order: 3
title: Perseus 0.0 -- 1982-1986 
topics: Perseus; History
---

Several earlier projects led to the Perseus Digital Library.
## Harvard Classics Computing Project

The Perseus Digital Library has its origins in the summer of 1982, when Gregory Crane, then a PhD student in the Department of Classics at Harvard, begin, as 
he was told, to help advice programmers on the tweaks needed to adapt the Unix operating system to the study of Ancient Greek language and literature. 

The first task to search the first Greek texts that were published by the TLG. The medium was 9-track magnetic tape and there were a relative handful of texts but this was the first time anyone had distributed machine readable texts of Greek. I can remember that the first file of the first author was Aeschylus' Suppliant Women and I immediately had to deal with non-standard line numbers. Ultimately, I used Michael Lesk's bibliographic Unix utility, Refer, as a model but I could not reuse the code. Lesk had used a technique called hashing that was not nearly so suitable to highly inflected languages such as Greek. In the end, we had a 10,000 line set of programs, written in the C programming language, that could index and search the texts available from the Thesaurus Linguae Graecae (then led by its founder, Ted Brunner). This introduced the idea of automated text processing.

In that summer of 1982, the Classics Deparmented invested in 40,000 in running cable through steam tunnels from William James Hall into Widener Library. These were the first network cables ever installed in Widener. They were heavy twisted pair and each cable could support (if memory serves) 32 connections. The cable came in a wooden spool that was c. 5 feet tall. This introduced the possiblity of leaving the machine room establishing remote networks. It would be years before I began to have limited access to Arpanet, the predecessor to the world Wide Web.

We also were asked to address the spiraling costs of typesetting Greek. We adapted the Unix publishing utliity TROFF to Ancient Greek. A consortium involving the Loeb Classical Library, Harvard Studies in Classical Philology, the Russian Review and the Harvard Theological Review assembled $8,000 to buy a used, film based typesetter. Gary Bisbee created a Greek font and we reduced typesetting costs from c. $25/page to c. $10/page. This project introduced the idea of computer-based publication of secondary sources, editions, translations, and reference works.

## Isocrates (with Paul Kahn of Brown University)

In 1983, I had a chance to begin a collaboration with the Scholarly Workstation Project funded by IBM at Brown University. Paul Kahn led the effort. We exploited a new medium, CD ROM, that could store more than 500 megabytes on a single, cheap (< $5), lightweight plastic disk. At the time, a 100 megabyte read-write hard disk cost c. $20,000. The CD ROM opened up the possibility of inexpensive publication of unprecedentd amounts of data. We adapted the TLG search system to work on a CD ROM (which required optimization for the slow disk). I received a Unix workstation as payment that would have cost $15,000. That was the first time I had a serious (by the standards of the time) development machine.

Helgerson, Linda W. “CD-ROM and Scholarly Research in the Humanities.” Computers and the Humanities, vol. 22, no. 2, 1988, pp. 111–16, https://www.jstor.org/stable/30200107.

## Aristarchus and Xerox Lisp Machines

In spring 1985, when I was finishing my Phd and preparing to begin as an Assistant Professor of Classics at Harvard at Harvard, I attended a seminar on Natural Language Processing by [Bill Woods]([url](https://en.wikipedia.org/wiki/William_Aaron_Woods)), an effort that opened my eyes to more advanced approaches to textual analysis. I was able to participate in a conference at Xexox' Palo Alto Research Center (PARC), a pioneering institution that was instrumental in developing laser printing and the graphical user interfaces that we all now take for granted. This visit had two impacts. First, I saw for the first time color digital images and realized that we could publish everything in a digital environent that we could in print -- only we could publish more material and link it all together. It was possible to imagine integrating the material and the textual records.

I managed to win an equipment grant from Xerox: four Lisp machines and a server and printer, roughly $100,000 worth of equipment. Lisp machines were, however, going out of fashion and being replaced by standard Unix workstations and I believe the equipment grants were a way to remove older inventory with a tax write-off but the machines served three functions. First, they got us a lab in the Van Serg building and the enormous power consumption of the worstations kept the old space warm in the winter. Second, we were able to experiment with a real hypertext system, the [NoteCards]([url](https://en.wikipedia.org/wiki/NoteCards)) system, which was written in Lisp. Third, I was able to use Lisp to write my first morphologial anlayzer and generetor for Ancient Greek. The visit to Xerox Parc and subsequent equipment grant made it possible to imagine what would become the Perseus Digital Library.

## Morpheus
