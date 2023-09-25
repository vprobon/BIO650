# BIO650 - Special Topics in Bioinformatics - Assignment1 (Fall 2023)

## Instructor: Asscociate Prof. [Vasilis J Promponas](https://www.ucy.ac.cy/dir/el/component/comprofiler/userprofile/vprobon). [vprobon@ucy.ac.cy](mailto:vprobon@ucy.ac.cy)

### Assignment 1 

Your first assignment calls you to become *sequence detectives*.


#### Background information
Biomolecular sequences are produced in ever increasing rates, mainly due to the continuous reduction in sequencing costs and the availability of underlying technologies. 
Such sequences are routinely deposited in archival databases (e.g., [GenBank](https://www.ncbi.nlm.nih.gov/genbank/)). 
Due to our inability to perform "wet" experiments at such a large scale, gene/genome/protein sequences are often subject to computational analyses for obtaining meaningful annotations: such computational analyses aim (among others) to 
- Characterise the extent of coding regions
- Identify exon/intron boundaries
- Functionally characterise gene products (i.e., assign possible functions)

The functional annotation process often relies on the assumption that homologous genes/proteins perform the same function. Homology can be detected when sufficient sequence similarity is detected between two macromolecular sequences; 
then we can "transfer" existing annotations from a gene/protein of known function to a newly characterized one.

Obviously, if erroneous functional information is entered for an entry in the sequence databases, these errors can be propagated during annotation transfer and such errors will be entered anew in the database.

There have been several reports in the literature, highlighting the existence of database errors (and their different types), discussing their significance and studying their mode of propagation within databases.


In this practical assignment, you will act as "sequence detective", where you are asked to:
1. Detect entries with a simple typographical error in sequence databases.
2. Use sequence comparison tools to investigate whether you are able to identify the source (i.e., the starting point of this error).
3. Conclude on whether such types of errors are easy to spot and possibly correct in the sequence databases.

In particular, you will try to 

- Whether/how we can replicate Figure 1 of the paper using sequence comparisons and freely available tools and databases
- Compare the results of that paper (published in 2015) 
- Comment on the above


#### References



[Bioinformatics Research Laboratory @UCY](https://vprobon.github.io/BRL-UCY) 2005-2023.
