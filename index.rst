.. DeepEA documentation master file, created by
   sphinx-quickstart on Fri Dec 28 11:26:36 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

===============================================================================================================
DeepEA: *a Galaxy-based framework for exploration and large-scale analysis of epitranscriptome sequencing data*
===============================================================================================================

**DeepEA** is an upgrated version of `PEA <https://github.com/cma2015/PEA>`_, which is a special designed R toolkit for plant epitranscriptome analysis. In the current version of DeepEA, a variety of modules and functions including **data preparation**, **quality control**, **CMR (chemical modifications of RNA) profiling and analysis**, **CMR annotation**, **CMR prediction** and related **visualization** are implemented to enable users perform large-scale, reproducible epitranscriptome analysis. In addition, by taking advantages of multiple instance learning (MIL) algorithms, DeepEA can precisely localize CMRs in peak regions. This can reduce the false positive CMRs generated by MeRIP-Seq/m6A-Seq/m5C-RIP-Seq, as which can localize CMRs to transcript regions of 100-200 nucleotide long but fail to accurately identify CMRs at single-nucleotide solution. The DeepEA project is hosted on `Github <https://github.com/cma2015/deePEA>`_


.. image:: images/f2.jpg

There are 2 ways for using deePEA:

* **Galaxy server usage** --  our public `deePEA Galaxy server <http://bioinfo.nwafu.edu.cn:4003>`_ let's you use the DeepEA within the familiar Galaxy framework without the need to master the command line.
* **DeepEA Docker image** -- The packaged `deePEA docker image <https://hub.docker.com/r/malab/deepea/>`_ enable users build a DeepEA server in their local device without any dependencies.


Contents:
---------
.. toctree::
   :maxdepth: 1

   content/example_usage_within_galaxy


While developing DeepEA, we continuously strive to create software
that fulfills the following criteria:


-  Support **more CMR recognition**
-  More accurate method of **CMR prediction**
-  Richer and more effective **visualization**
-  make use of **multiple processors** 
-  More analysis methods focus on **the regulation of a single gene by CMR**
-  **modular approach** - compatibility, flexibility, scalability (i.e.
   we can add more and more modules and make use of established methods)


.. tip:: For support, questions, or feature requests contact: q2516581@126.com  chuangma@gmail.com




