# starMC-benchmark

This repository contains the data obtained from the comparison of three tools:

- RGMEDD3 (GreatSPN CTL symbolic model checker) [link](https://github.com/greatspn/SOURCES)
- ltsmin, in particular the CTL* mu-calculus based model checker  [link](https://ltsmin.utwente.nl/)
- starMC, a new Büchi-based CTL/LTL/CTL* model checker of GreatSPN

The data are organized into three directories:

+ 7.2-rgmedd-starMC-ctl: contains the data of the CTL benchmark
+ 7.3.1-ltsmin-starMC-ltl: data of the LTL benchmark
+ 7.3.2-ltsmin-starMC-ctlstar: data of the CTL* benchmark

The script *Plots.ipynb* is a [Jupyter notebook](https://jupyter.org/) that reads the benchmark data and produces the  plots used in the paper <em>"starMC: an automata based CTL* model checker"</em>.