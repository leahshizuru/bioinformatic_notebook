
# Annotating *Myriopathes ulex*

**Objective:** Re-visit *Myriopathes ulex* annotations. We received feedback from GenBank saying that *ND5* was missing a legal start codon.

**Background:** The mitogenome we submitted to GenBank (NODE_5_length17838_cov_59.388403 from SPAdes assembly) was edited (repeat sequences at the start and end of the linear sequence removed) and then circularized. Annotations were then transferred from *Myriopathes japonica* onto the circularized sequence. This mitogenome submission (2022-07-21) (ID: 2605514) was 17,711 bp. See below.

![Myriopathes ulex](M_ulex_it1.jpg)

**Methods:** 
1. scp results from QUAST (report.pdf) to local to assess quality of SPAdes assembly. 
2. Re-evaluate annotations that were given via "Live Annotate & Predict" and compare these to Mitos2 output. 
3. Instead of selecting one contig from the SPAdes assembly try mapping trimmed reads to reference genomes (*M. japonica* (NC_027667) and *Tanacetipathes thamnea* (NC_046843.1)). 
