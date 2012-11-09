ns3-yanci
=========

Yet Another Network Coding Implementation

Short Intro
=========

This is an simplified implementation of wireless network coding in a single-radio scenario. It is based on COPE[1], but the probabilistic guessing is not implemented, yet.

[1]S. Katti, H. Rahul, W. Hu, D. Katabi, M. Medard, and J. Crowcroft, “Xors in the air: practical wireless network coding,” SIGCOMM Comput. Commun. Rev., vol. 36, pp. 243–254, August 2006.
www.cs.cmu.edu/~dga/15-744/S07/papers/xor.pdf

Installation
============

Put yanci into {Your ns-3 folder}/src/ directory. Then run "./waf configure" + "./waf". To enable examples programs, use "./waf configure --enable-examples" instead of "./waf configure".
