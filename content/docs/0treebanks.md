---
section_id: New in Perseus 6.0
nav_order: 2
title: Treebanks
topics: Linguistic Annotation
---

We first announced plans to develop treebanks for Greek and Latin in 2002, but the idea went back to work on Morpheus in 1984. Morpheus was able to identify that _mênin_, "wrath," was in an accusative singular form of the Greek noun _mênis_, but morphology could not, by itself, to us why _mênin_ was in the accusative. Is it governed by a preposition? Is it an internal accusative ("with respect to wrath") or (for example) simply, as in this case, the direct object of a verb? 

Treebanks are textual databases which record linguistic annotation the defines such features for each word. The XML serialization of the Greek Treebank for the first sentence of the Iliad, below, records the following: (1) the position of each form in a sentence, (2) its inflected form, (3) its dictionary form (_mênis_); (4) its part of speech (n-s---fa- = "noun, singular, feminine, accusative"), (5) the word it depends on (in this case _ennepe_, "sing!"), and (6) its syntactic role (the object of _ennepe_), and (7) the citation in which that word appears.

{% include figure.html img="treebank01.jpg" alt="intro image here" caption="left: the opening sentence of the Iliad; right: opening three words as a tree" width="75%" %}


