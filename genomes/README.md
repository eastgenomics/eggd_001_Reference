# genomes

For genome files

Contents:

* /genomes/b37/hs37d5-fasta.tar
> A tarball containing the reference genome file hs37d5.fa used by the vcfeval_hap.py app. Can be found at  project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fjp4k3Q4yBGZYpQg3bgpPG95
* /genomes/b37/hs37d5-sdf.tar
> A tarball containing the reference genome file hs37d5.sdf used by the vcfeval_hap.py app. Can be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fjp4k3j4yBGpK4x73bzbG2P0
* /genomes/b37/hs37d5.fa.gz
> This is the GRCh37 reference genome file it was copied from project-F3zxk7Q4F30Xp8fG69K1Vppj:file-F403K904F30y2vpVFqxB9kz7 Reference Genome Files: AWS Germany/H. Sapiens
* /genomes/b37/hs37d5.fasta-index.tar.gz
> This is the GRCh37 reference FASTA index file it was copied from project-F3zqGV04fXX5j7566869fjFq:file-F3zxG0Q4fXX9YFjP1v5jK9jf Apps Data: AWS Germany/human.genome/1000genomes_phase2_hs37d5/
* /genomes/b37/tso500-hg19hardPAR-fasta-index.tar.gz
> A tarball containing the reference genome files genome.fa, genome.fa.fai and genome.dict. These were extracted from Illumina's pipeline docker image TSO500_v2.0.0. This tarball is specifically for running picard on TSO500 Illumina pipeline outputs. It an be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fp4BVFj4KXyyPkP90x21z29X


* /genomes/b38/GRCh38.no_alt_analysis_set_chr_mask21.fa.gz
> This is the masked GRCh38 reference genome file created by masking (bedtools maskfasta) the regions on the small arm of chromosome 21 where U2AF1 aligns to, chr21:6484123-6499748. U2AF1 should only aligne to the long arm of chromosome 21. This file is used by the sentieon-tnseq, pindel and cgppindel apps. It can be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fy4gjFj41zgGjKJ85FYYPX4qa
* /genomes/b38/GRCh38.no_alt_analysis_set_chr_mask21.fa.fai
> This is the GRCh38 masked reference FASTA index file. It was created by using samtools faidx GRCh38.no_alt_analysis_set_chr_mask21.fa.gz. This file is used by pindel and cgppindel apps and can be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-FyFGvzQ41zgBq7xf4Gy9Q28g
* /genomes/b38/GRCh38.no_alt_analysis_set_chr_mask21.fasta-index.tar.gz
> A tarball containing the reference genome files genome.fa, genome.fa.fai and genome.dict. The genom.dic file was created by java -jar picard.jar CreateSequenceDictionary R=GRCh38.no_alt_analysis_set_chr_mask21.fa  O=GRCh38.no_alt_analysis_set_chr_mask21.dict. This file is used by eggd_picard_qc and can be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fy4j2G04qB6zQK885B5Q8Pqp
* /genomes/b38/GRCh38.no_alt_analysis_set_chr_mask21.bwa-index.tar.gz
> A tar ball containing the GRCh38 BWA reference genome index file. This file was created with bwa index GRCh38.no_alt_analysis_set_chr_mask21.fa. This file is used by sentieon-tnseq app and the file can be found at project-Fkb6Gkj433GVVvj73J7x8KbV:file-Fy4p4K040Pgy8XjKG41ZqzxZ


