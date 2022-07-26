
# Annotating *Myriopathes ulex*

**Objective:** Re-visit *Myriopathes ulex* annotations. We received feedback from GenBank saying that *ND5* was missing a legal start codon.

**Methods:** The mitogenome we submitted to GenBank (NODE_5_length17838_cov_59.388403 from SPAdes assembly) was edited (repeat sequences at the start and end of the linear sequence removed) and then circularized. Annotations were then transferred from *M. japonica* onto the circularized sequence. This mitogenome submission (2022-07-21) (ID: 2605514) was 17,711 bp. See below.

![Myriopathes ulex](M_ulex_it1.jpg)

Contigs.fasta file that SPAdes generated was mapped to *M. japonica* in Geneious Prime. A BLAST was performed on the consensus sequence (17,758 bp) that was created in Geneious Prime. BLAST results revealed *M. ulex* to be more similar to *Tanacetipathes thamnea* (JX45649.1) (Per. Ident: 99.52%) than to *Myriopathes japonica* (NC_046843.1) (Per. Ident: 98.68%). Both were identical in Query Cover (98%).

Given BLAST results I returned to Geneious Prime and mapped contigs.fasta to *Tanacetipathes thamnea*. BLAST results of this consensus sequcence (17,758 bp) revealed that *M. ulex* was more similar to *T. thamnea* with a Query Cover of 99% and Per. Ident 99.38% compared to *M. japonica* (Query Cover 98%; Per. Ident: 99.59%).
