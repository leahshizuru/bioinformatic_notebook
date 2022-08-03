
# Annotating *Aphanipathes* sp. 

**Objective:** Annotate *Apahnipathes* sp.(130-W-Maui) collected in the Au'Au Channel.

**Methods:**

1. Inspect large_contigs_130.fasta produced by SPAdes.
2. Export as a .fasta file and then BLAST NODE_1_length_16557_cov_5.095557 and NODE_3_length_14543_cov_8.299022.
3. BLAST results revealed NODE_1_length_16557_cov_5.095557 to be the most appropriate candidate for downstream analysis because it aligned with antipatharians. Results yielded 100% Per. Ident to all *Aphanipathes* partial mitogenome sequences.
4. BLAST results yielded the following: Query Cover 94%, Per. Ident 92.70% to Stichopathes sp. SCBUCN-8850 (MZ157399), Query Cover 94%, Per. Ident 92.21% to (JX023266), and 92% to Stichopathes sp. SCBUCN-8849 (MZ157400). Other matches were 80% or less for both Quer Cover and Per. Ident.
5. Download relevant *Apahnipathes* material from GenBank; place these files into the "Reference Features" subfolder labeled "antipatharians".
6. In Geneious Prime: "Find Repeats". No repeats were found, further suggesting this is a partial mitochondrial genome.
7. Create two iterations: one will contain Mitos2 dictated annotations and the other will be results of annotations that were transferred from library.
8. Transfer annotations from database. (See Figure 1)
9. Submit .fasta file to Mitos2 (job settings: RefSeq 89 Metazoa, Genetic code: 4 Mold). Compare output to transferred annotations.
10. "Find ORFs" and locate start codons.
11. Input "500" for "Minimum size"; select "Mold Protozoan Mitochondrial transl_table 4" for "Genetic code". This will auto-populate the relevant start codons.
