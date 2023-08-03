---
title: "Cryptree: A Folder Tree Structure for Cryptographic File Systems"
date: 2006-10-01
publishDate: 2023-08-03T14:03:31.929322Z
authors: ["Dominik Grolimund", "Luzius Meisser", "Stefan Schmid", "Roger Wattenhofer"]
publication_types: ["1"]
abstract: "We present Cryptree, a cryptographic tree structure which facilitates access control in file systems operating on untrusted storage. Cryptree leverages the file system's folder hierarchy to achieve efficient and intuitive, yet simple, access control. The highlights are its ability to recursively grant access to a folder and all its subfolders in constant time, the dynamic inheritance of access rights which inherently prevents scattering of access rights, and the possibility to grant someone access to a file or folder without revealing the identities of other accessors. To reason about and to visualize Cryptree, we introduce the notion of cryptographic links. We describe the Cryptrees we have used to enforce read and write access in our own file system. Finally, we measure the performance of the Cryptree and compare it to other approaches."
featured: false
publication: "*25th IEEE Symposium on Reliable Distributed Systems (SRDS)*"
---

