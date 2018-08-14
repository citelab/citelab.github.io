---
author: "V. Maheshwari, A. Nourian, and M. Maheswaran"
title: "Character-based Search with Data Confidentiality in the Clouds"
journal: "International Workshop on Cloud Computing for Research Collaborations"
location: "held in conjunction with 4th IEEE International Conference on Cloud Computing (CloudCom), Taipei, Taiwan"
date: 2012-12-01
---
Recently, searching over encrypted data has become a hot research topic. Basic idea of privacy enhanced search is to generate an intermediate representation of the original text data and use it to perform the search. Prior research has used hash maps, tries, and other data structures to create the intermediate representation. We use a texture scheme for representing the characters. To enhance the privacy the textures are split and noise is added to each of the portions such that all portions of a texture needs to be collected to recover the original data in an unambiguous manner. One of the key advantages of our scheme is the ability to implement most of the search schemes (e.g., wildcard searches) that are performed with plain text searches. This paper fully describes our data representation scheme and presents the experimental data we gathered by implementing the scheme in a server cluster.