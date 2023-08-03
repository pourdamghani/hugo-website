---
title: "A DoS-Resilient Information System for Dynamic Data Management"
date: 2009-08-01
publishDate: 2023-08-03T14:03:31.932176Z
authors: ["Matthias Baumgart", "Christian Scheideler", "Stefan Schmid"]
publication_types: ["1"]
abstract: "Denial of service (DoS) attacks are arguably one of the most cumbersome problems in the Internet. This paper presents a distributed information system (over a set of completely connected servers) called Chameleon which is robust to DoS attacks on the nodes as well as the operations of the system. In particular, it allows nodes to efficiently look up and insert data items at any time, despite a powerful ``past-insider adversary'' which has complete knowledge of the system up to some time point t0 and can use that knowledge in order to block a constant fraction of the nodes and inject lookup and insert requests to selected data. This is achieved with a smart randomized replication policy requiring a polylogarithmic overhead only and the interplay of a permanent and a temporary distributed hash table. All requests in Chameleon can be processed in polylog-arithmic time and work at every node."
featured: false
publication: "*21st ACM Symposium on Parallelism in Algorithms and Architectures (SPAA)*"
url_pdf: "http://www.net.t-labs.tu-berlin.de/papers/BSS-DRISDDM-09.pdf"
doi: "http://dx.doi.org/10.1145/1583991.1584064"
---

