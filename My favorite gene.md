# MY FAVORITE GENE
_______

# DNMT

![picture](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5W3TerO7eVUTj4C-Woz94Oa927z7a9j0wBNphipAkUs5fCxEO)
_______

By Edgar Lopez

##Is it in the Geoduck Transcriptome?

_______

First, I got a sequence from NCBI in a species with annotated genome.

This is a screenshot of the NCBI page

![imagen](DNMT.bmp)

This is a pageweb direction [link](http://www.ncbi.nlm.nih.gov/nuccore/XM_011527774.1)

The code was:

`!blastn \`

`-outfmt 6 \`

`-max_target_seqs 10 \`

`-evalue 1E-20 \`

`-query ..\Z\query\Csikamea.fasta \`

`-db ..\Z\db\Geo_Male \`

`-out out\Csikamea_blastn_M-fmt6.out`

I found many matchs from Geoduck_male database and two examples are here:

`Geo_Pool_M_CTTGTA_L006_R1_001_val_1_(paired)_contig_7892	70.52	1472	394	14	3339	4802	2334	3773	0.0	672`
`Geo_Pool_M_CTTGTA_L006_R1_001_val_1_(paired)_contig_7892	65.76	885	271	13	1242	2122	216	1072	4e-050	201`

#Today was a great bioinformatic day...Thanks instructors
