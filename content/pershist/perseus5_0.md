---
section: Earlier Versions of Perseus
nav_order: 6
title: Perseus 5.0 -- 2018-  
topics: Perseus; History
---

{% include figure.html img="perseus5-scaife.jpg" alt="intro image here" caption="Perseus 5: the Scaife Viewer" width="75%" %}

In 2018, Perseus introduced the Scaife Viewer. We list Scaife as Perseus 5.0. Strictly speaking, however, Scaife was not a new, complete version of Perseus because it does not fully replicate the functionality of Perseus 4.  Scaife represented a first step towards Beyond Translation. 

Scaife accomplished several goals.

First, Scaife gave us an updated codebase that we could more easily maintain. The code for Perseus 4 had grown increasingly more complex and creating new versions of Perseus 4 had become unsustainably complex. We can, and do, regularly update the content in the Scaife Viewer and we could quickly address issues such as security problems that might appear.

Second, Scaife allowed us to expand the amount of Greek and Latin as well as to update existing texts.

Third, Scaife uses the [CapiTainS software suite](http://capitains.org/) to implement the Canonical Text Services data model. Perseus decided to adopt CTS in 2013 to standardize the way it organized and cited its holdings. CTS allows us to cite texts not only by conventional citation scheme (e.g., book/line in Homeric Epic, book/chapter/section in Thucydides) but also by edition. We can thus describe the third instance of "et" in a particular section of a particular edition of Livy -- which could be the second instance of that word in another edition or may not even appear at all in yet another edition. CTS allows us to create machine actionable annotations that are precise and easily computed.

Fourth, Scaife provided a new front end framework, based upon [Vue.js]((https://vuejs.org/), upon which we could build Beyond Translation. 


