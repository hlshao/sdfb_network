Summary
=======

Goes from raw ODNB data to R data structures used in network_estimations

Workflow
========

* Step A: /preprocess
  * Scripts to obtain ODNB HTML files
  * Compress/decompress them into .tar.gz file
  * Read HTML files into R, store as a list

* Step B: /NER
  * Code to process text files into combined versions
  * Scripts to run Stanford/Lingpipe tools
  
* Step C: /postprocess
  * Combines NER results to data structures from preprocess