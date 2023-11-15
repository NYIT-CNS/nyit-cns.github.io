--- 
title: "Data Structures for High-Speed Networks"
layout: single 
permalink: /research/algorithmics/ 
---
![](/assets/images/research/algorithmics-top2.png)

<p align="center">
  <img src="/assets/images/research/ABF.png" />
</p>

<p align="center">
  <img src="/assets/images/research/range-hash.png" />
</p>

Routers and other appliances running at the core of the Internet requires to process traffic at dazzling speeds, where packets should be processed within time frames of picoseconds to nanoseconds. A good portion of this processing is done in dedicated hardware implementing highly optimized and customized data structures and algorithms to address specific problems ranging from route lookup, to security and traffic measurement. Light-weight data structures such as Bloom Filters, and other hashing-based structures, as well as finite automata are suitable for various tasks. In this project, we develop hashing, and automata-based data structures targeting link speeds 10-100 Gbps and beyond and show their feasibility on FPGAs with replayed real-traffic.

# Selected Related Publications

1.  M. Bando, **N. Sertac Artan**, R. Wei, X. Guo, and H. J. Chao, “Range Hash for Regular Expression Pre-Filtering,” in _ACM/IEEE Symposium on Architectures for Networking and Communications Systems (ANCS 2010)_, La Jolla, CA, Oct. 2010. \[ [bib](sertac_bib.html#BAWGC10) \| [pdf](pubs/BandoEtAlRangeHashANCS2010.pdf) \]
2.  **N. Sertac Artan**, H. Yuan, and H. J. Chao, “A Dynamic Load-Balanced Hashing Scheme for Networking Applications,” in _IEEE Global Communications Conference (GLOBECOM 2008)_, New Orleans, LA, Nov-Dec 2008. \[ [bib](sertac_bib.html#AYC08) \| [pdf](pubs/ArtanEtAlDynamicHashGlobecom2008.pdf) \]
3.  **N. Sertac Artan** and H. J. Chao, “Design and Analysis of a Multi-packet Signature Detection System,” _Int. J. Security and Networks_, vol. 2, no. 1/2, pp. 122-136, Mar. 2007. \[ [bib](sertac_bib.html#JSec07) \]
4.  **N. Sertac Artan**, K. Sinkar, J. Patel, and H. J. Chao, “Aggregated Bloom Filters For Intrusion Detection And Prevention Hardware,” in _50th Annual IEEE Global Communications Conference (GLOBECOM 2007)_, Washington, DC, Nov. 2007. \[ [bib](sertac_bib.html#ASPC07) \| [pdf](pubs/ArtanEtAlAggGlobecom2007.pdf) \]

