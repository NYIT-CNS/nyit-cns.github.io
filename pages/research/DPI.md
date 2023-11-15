--- 
title: "Deep packet inspection (DPI) for high-speed network intrusion detection and prevention"
layout: single 
permalink: /research/DPI/ 
---

![](/assets/images/research/DPI-top.png)

Traffic on the internet is growing fast and a significant portion of it poses a security risk or is unwanted. Software products cannot cope with high-speed requirements. Hardware products provide high speed but are expensive. The goal of this project is to develop hardware for high-speed deep packet inspection for network intrusion detection and prevention. We have developed several methods to provide robust, and high speed DPI targeting 40-100 Gbps networks without cost inflation.

# LaFA (Lookahead Finite Automata) for Regular Expression Detection

<p align="center">
  <img src="/assets/images/research/lafa1.png" />
</p>

Modern DPI attack signatures are defined as regular expressions (RegExes). However, the complexity of the RegExes limit the scalability of existing DPIs due to the reliance on the per-character, and in-order state processing paradigms. Lookahead Finite Automata (LaFA) provides scalable RegEx detection reaching to 40 Gbps throughput with up to 25,000 RegExes on a single chip without the need for off-chip memory for signature storage. LaFA's scalability is mainly due to its departure from traditional processing paradigms, and using specialized multi-character modules, and out-of-order state processing.  

# TriBiCa (Trie Bitmap Content Analyzer)

<p align="center">
  <img src="/assets/images/research/tribica1.png" />
</p>

TriBiCa is a high-speed, single-chip DPI core that is scalable and configurable through memory updates. Its unique hardware implementation of minimal perfect hashing, which uses a trie structure with a hash function performed at each layer, boosts the performance without the need of off-chip memory for signature storage. TriBiCa is implemented on a Xilinx Virtex II Pro FPGA chip with 10 Gbps throughput. With modern FPGA technology, it can easily scale to support 100 Gbps and higher links.  

# Selected Related Publications

1.  M. Bando, **N. Sertac Artan**, and H. J. Chao, “Scalable Lookahead Regular Expression Detection System for Deep Packet Inspection,” _IEEE/ACM Transactions on Networking_, vol. 20, no. 3, pp. 699-714, Jun. 2012. \[ [bib](sertac_bib.html#BAC) \]
2.  M. Bando, **N. Sertac Artan**, N. Mehta, Y. Guan, and H. J. Chao, “Hardware Implementation for Scalable Lookahead Regular Expression Detection,” in _17th Reconfigurable Architectures Workshop (RAW 2010) at IEEE International Parallel & Distributed Processing Symposium (IPDPS 2010)_, Atlanta, GA, Apr. 2010. \[ [bib](sertac_bib.html#BAC10) \| [pdf](pubs/BandoEtAlLaFA_Hw_IPDPS_RAW2010.pdf) \]
3.  M. Bando, **N. Sertac Artan**, and H. J. Chao, “LaFA: Lookahead Finite Automata for Scalable Regular Expression Detection,” in _ACM/IEEE Symposium on Architectures for Networking and Communications Systems (ANCS 2009)_, Princeton, NJ, Oct. 2009. \[ [bib](sertac_bib.html#BAC09b) \| [pdf](pubs/BandoEtAlLaFA_ANCS09.pdf) \]
4.  **N. Sertac Artan**, M. Bando, and H. J. Chao, “Boundary Hash for Memory-Efficient Deep Packet Inspection,” in _IEEE International Conference on Communications (ICC 2008)_, Beijing, China, May 2008. \[ [bib](sertac_bib.html#ABC08) \| [pdf](pubs/ArtanEtAlBoundaryICC2008.pdf) \]
5.  **N. Sertac Artan** and H. J. Chao, “TriBiCa: Trie Bitmap Content Analyzer for High-Speed Network Intrusion Detection,” in _26th Annual IEEE Conference on Computer Communications (INFOCOM 2007)_, 2007, pp. 125-133. \[ [bib](sertac_bib.html#AC07) \| [pdf](pubs/ArtanChaoTriBiCaInfocom2007.pdf) \| [slides](pubs/ArtanChaoTriBiCaInfocom2007Slides.pdf) \]
6.  **N. Sertac Artan** and H. J. Chao, “Design and Analysis of a Multi-packet Signature Detection System,” _Int. J. Security and Networks_, vol. 2, no. 1/2, pp. 122-136, Mar. 2007. \[ [bib](sertac_bib.html#JSec07) \]

