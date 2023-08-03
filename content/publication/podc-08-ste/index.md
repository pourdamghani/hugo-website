---
title: "Distributed Computation of the Mode"
date: 2008-08-01
publishDate: 2023-08-03T14:03:31.931134Z
authors: ["Fabian Kuhn", "Thomas Locher", "Stefan Schmid"]
publication_types: ["1"]
abstract: "This paper studies the problem of computing the most frequent element (the mode) by means of a distributed algorithm where the elements are located at the nodes of a network. Let ıt k denote the number of distinct elements and further let ıt m_i be the number of occurrences of the element ıt e_i in the ordered list of occurrences ıt m_1>m_2>=...>=m_k. We give a deterministic distributed algorithm with time complexity ıt O(D+k) where ıt D denotes the diameter of the graph, which is essentially tight. As our main contribution, a Monte Carlo algorithm is presented which computes the mode in ıt O(D + F_2/m_1^2 log k) time with high probability, where the frequency moment ıt F_l is defined as ıt F_l = Sum_(i=1)^k m_i^l. This algorithm is substantially faster than the deterministic algorithm for various relevant frequency distributions. Moreover, we provide a lower bound of ıt $Ømega$(D + F_5/(m_1^5 B)), where ıt B is the maximum message size, that captures the eect of the frequency distribution on the time complexity to compute the mode."
featured: false
publication: "*27th ACM Symposium on Principles of Distributed Computing (PODC)*"
url_pdf: "http://www.net.t-labs.tu-berlin.de/papers/KLS-DCM-08.pdf"
doi: "http://dx.doi.org/10.1145/1400751.1400756"
---

