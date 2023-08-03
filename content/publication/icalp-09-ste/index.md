---
title: "A Distributed and Oblivious Heap"
date: 2009-07-01
publishDate: 2023-08-03T14:03:31.931881Z
authors: ["Christian Scheideler", "Stefan Schmid"]
publication_types: ["1"]
abstract: "This paper shows how to build and maintain a distributed heap which we call SHELL. In contrast to standard heaps, our heap is oblivious in the sense that its structure only depends on the nodes currently in the network but not on the past. This allows for fast join and leave operations which is desirable in open distributed systems with high levels of churn and frequent faults. In fact, a node fault or departure can be fixed in SHELL in a constant number of communication rounds, which significantly improves the best previous bound for distributed heaps. SHELL has interesting applications. First, we describe a robust distributed information system which is resilient to Sybil attacks of arbitrary scale. Second, we show how to organize heterogeneous nodes of arbitrary non-uniform capabilities in an overlay network such that the paths between any two nodes do not include nodes of lower capacities. This property is useful, e.g., for streaming. All these features can be achieved without sacrificing scalability: our heap has a de Bruijn like topology with node degree ıt O(log^2 n) and network diameter ıt O(log n), ıt n being the total number of nodes in the system."
featured: false
publication: "*36th International Colloquium on Automata, Languages and Programming (ICALP)*"
url_pdf: "http://www.net.t-labs.tu-berlin.de/papers/SS-DOH-09.pdf"
doi: "http://dx.doi.org/10.1007/978-3-642-02930-1_47"
---

