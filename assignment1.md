# BIO650 - Special Topics in Bioinformatics - Assignment1 (Fall 2023)

## Instructor: Asscociate Prof. [Vasilis J Promponas](https://www.ucy.ac.cy/dir/el/component/comprofiler/userprofile/vprobon). [promponas.vasileios@ucy.ac.cy](mailto:promponas.vasileios@ucy.ac.cy)

### Assignment 1 - Becoming ***sequence detectives***.


#### Background information
Biomolecular sequences are produced in ever increasing rates, mainly due to the continuous reduction in sequencing costs and the availability of underlying high-throughput technologies. These sequences are routinely deposited in archival databases (e.g., [GenBank](https://www.ncbi.nlm.nih.gov/genbank/)). 
Due to our inability to perform "wet" experiments at such a large scale, gene/genome/protein sequences are often subject to computational analyses for obtaining meaningful annotations: such computational analyses aim (among others) to 
- Characterise the extent of coding regions.
- Identify exon/intron boundaries.
- Functionally characterise gene products (i.e., assign possible functions).

The functional annotation process often relies on the assumption that homologous genes/proteins perform the same function. Homology can be detected when sufficient sequence similarity is detected between two macromolecular sequences; 
then we can "transfer" existing annotations from a gene/protein of known function to a newly characterized one. Obviously, if erroneous functional information is entered for an entry in a sequence database, these errors can be propagated during annotation transfer, thus these errors will be maintained in the sequence database.

There have been several reports in the literature, highlighting the existence of database errors (and their different types), discussing their significance and studying their mode of propagation within databases [1-11].

#### Open question
A paper published in 2015 [9] presents some particular types of annotation errors identified in a survey by the authors. A trivial case considers the appearance of a typo, the misspelled word "putaitve" (instead of the correct term "putative"), across several entries in the database. The authors in [9], used all-against-all sequence comparisons, followed by sequence similarity-based clustering of the erroneously annotated sequences in order to trace back the errors to their root, i.e., the initial sources of error which were later propagated in the database. While this specific error does not harm severely the database annotations (as the term "putative" weakens any annotation it accompanies), it can be used as a test-bed to understand how other typos (e.g., in the names of proteins) can be propagated in sequence databases.

Today, almost 10 years after this publication: 
- Do you expect that this particular misspelling still exists in the database? 
- Can you predict whether the number of the misspelled entries has changed (increased or decreased)?
- Repeat the same sequence analysis steps, essentially becoming ***sequence detectives***, in order to reproduce the results shown in Figure 1 of [9], based on the current database status.
- Try and identify the possible source(s) of error.
- Compare your results to the results in [9].
- Discuss your findings, also placing them in the context of the available literature.


In this practical assignment, you will act as "sequence detective", where you are asked to:
1. Detect entries with a simple typographical error in sequence databases.
2. Use sequence comparison tools to investigate whether you are able to identify the source (i.e., the starting point of this error).
3. Conclude on whether such types of errors are easy to spot and possibly correct in the sequence databases.

In particular, you will try to 

- Whether/how we can replicate Figure 1 of the paper using sequence comparisons and freely available tools and databases
- Compare the results of that paper (published in 2015) 
- Comment on the above


#### References

1. Kyrpides NC, Ouzounis CA. Whole-genome sequence annotation: ‘Going wrong with confidence’. Mol Microbiol. 1999;32(4):886–7.

2. Devos D, Valencia A. Intrinsic errors in genome annotation. Trends Genet. 2001;17(8):429–31.

3. Gilks WR, Audit B, De Angelis D, Tsoka S, Ouzounis CA. Modeling the percolation of annotation errors in a database of protein sequences. Bioinformatics. 2002;18(12):1641–9.

4. Ouzounis CA, Karp PD. The past, present and future of genome-wide re-annotation. Genome Biol. 2002;3(2):COMMENT2001.

5. Green ML, Karp PD. Genome annotation errors in pathway databases due to semantic ambiguity in partial EC numbers. Nucleic Acids Res. 2005;33(13):4035–9.

6. Schnoes AM, Brown SD, Dodevski I, Babbitt PC. Annotation error in public databases: misannotation of molecular function in enzyme superfamilies. PLoS Comput Biol. 2009;5(12):e1000605.

7. Ben-Shitrit T, Yosef N, Shemesh K, Sharan R, Ruppin E, Kupiec M. Systematic identification of gene annotation errors in the widely used yeast mutation collections. Nat Methods. 2012;9(4):373–8.

8. Percudani R, Carnevali D, Puggioni V. Ureidoglycolate hydrolase, amidohydrolase, lyase: how errors in biological databases are incorporated in scientific papers and vice versa. Database (Oxford). 2013;2013:bat071.

9. Promponas VJ, Iliopoulos I, Ouzounis CA. Annotation inconsistencies beyond sequence similarity-based function prediction - phylogeny and genome structure. Stand Genomic Sci. 2015;10:108. 

10. Goudey B, Geard N, Verspoor K, Zobel J. Propagation, detection and correction of errors using the sequence database network. Brief Bioinform. 2022;23(6):bbac416.

11. Kress A, Poch O, Lecompte O, Thompson JD. Real or fake? Measuring the impact of protein annotation errors on estimates of domain gain and loss events. Front Bioinform. 2023 Apr 20;3:1178926.


[Bioinformatics Research Laboratory @UCY](https://vprobon.github.io/BRL-UCY) 2005-2023.
