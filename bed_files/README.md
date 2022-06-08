# bed

For BED files

Contents:

* :sleeping_bed: /bed_files/b37/kits/CEN/CEN_capture_v1.0.0.bed
> This bed file contains the capture regions for the CEN assay. It is based on the Twist CEN capture bed but converted from b38 to b37.
* :sleeping_bed: /bed_files/b37/kits/CEN/CEN_genes_v1.0.0.bed
> This bed file contains the regions of the target genes/transcripts of the CEN assay.
* :sleeping_bed: /bed_files/b37/kits/CEN/CEN_CNV_targets_b37_v1.0.0.bed
> This bed file contains target regions for CNV calling for the CEN assay. It is based on the Twist CEN capture bed v1.0.0, b37 but modified by merging overlapping regions, removal of regions of length 1, 2 and 3, merging resulting regions if within 10 bp and lastly splitting regions into equal length if longer than 250 bp.

* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_203.bed
> This is the bed file containing RefSeq exons +/- 0bp, extracted from the Nirvana 2.0.3 Cache GRCH37 RefSeq .gff. This file delineates the regions for coverage analysis in Gemini/Dias. Obsolete.
* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_203_100bp_flank.bed
> This is the bed file containing RefSeq exons +/- 100bp, extracted from the Nirvana 2.0.3 Cache GRCH37 RefSeq .gff. This file delineates the regions that are variant called by Gemini/Dias. Obsolete.

* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10.bed
> This is the bed file containing RefSeq exons +/- 0bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff.
* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10_5bp.bed
> This is the bed file containing RefSeq exons +/- 5bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff.
* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10_100bp.bed
> This is the bed file containing RefSeq exons +/- 100bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff.

* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10_no_PAR_Y.bed
> This is the bed file containing RefSeq exons +/- 0bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff. Regions in PAR on Y have been removed.
* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10_5bp_no_PAR_Y.bed
> This is the bed file containing RefSeq exons +/- 5bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff. Regions in PAR on Y have been removed. This file delineates the regions for coverage analysis in Gemini/Dias.
* :sleeping_bed: /bed_files/b37/kits/gemini/refseq_nirvana_2.0.10_100bp_no_PAR_Y.bed
> This is the bed file containing RefSeq exons +/- 100bp, extracted from the Nirvana 2.0.10 Cache GRCH37 RefSeq .gff. Regions in PAR on Y have been removed. This file delineates the regions that are variant called by Gemini/Dias.

* :sleeping_bed: /bed_files/b37/kits/gemini/regions.unique_sorted_merged_5bp.bed
> This bed file is based on Illimina Trusight Expanded clinical exome but delineates that regions that are analysed by CUH.
* :sleeping_bed: /bed_files/b37/kits/gemini/regions_tested_5bp_200521.bed
> This bed file is based on Illimina Trusight Expanded clinical exome but delineates that regions that are analysed by CUH. Updated 200521 to align with Nirvana 2.0.10 transcripts. Used with hap.py to assess variant calling performance.

* :sleeping_bed: /bed_files/b37/kits/gemini/TruSightOne.bed
> This is the bed file from Illumina containing regions captured by the TSO kit. This file is used when assessing capture wide performance (e.g. eggd_vcf_qc).
* :sleeping_bed: /bed_files/b37/kits/gemini/TSOnePlus.bed
> This is the bed file from Illumina containing regions captured by the TSO Expanded kit. This file is used when assessing capture wide performance (e.g. eggd_vcf_qc).

* :sleeping_bed: /bed_files/b37/kits/tso500/TST500C_manifest.bed
> This is the bed file provided by Illumina for Trusight Oncology 500
* :sleeping_bed: /bed_files/b37/kits/tso500/tso500_exons_nirvana_210813_511_genes_v1_0.bed
> This is the bed file was created based on the TST500C_manifest.bed and intersected with the exons_nirvana bed to allow for coverage report creation (eggd_athena).

* :sleeping_bed: /bed_files/b38/kits/myeloid/coding_unrestricted_GRCh38_myeloid_v1.0.bed
> This bed file contains all exons of the genes included in the panel +/- 5bp. It was created using the gff_to_bed.py (https://github.com/eastgenomics/nirvana_gff_to_bed) where the GRCh38 nirvana gff file (GRCh38_RefSeq_26.gff.gz) was specified as an input, additionally 5bp padding was specified. This was further filtered to include only genes in the panel and MANE refseq IDs. The final bed file contains the following columns: chromosome, start position, end position, gene symbol, Refseq transcript ID, exon number. 
* :sleeping_bed: /bed_files/b38/kits/myeloid/coding_restricted_GRCh38_myeloid_v1.0.bed
> This bed file contains only exons that are of clinical significance, selected by the Haem-Onc clinical team, +/- 5bp. To create this bed file the coding_unrestricted_GRCh38_myeloid_v1.0.bed was filtered further based on the restricted exon list. This bed file contains the following columns: chromosome, start position, end position, gene symbol, Refseq transcript ID, exon number.
* :sleeping_bed: /bed_files/b38/kits/myeloid/probes_GRCh38_myeo_v1.0.bed
> This is the bed file provided by TWIST and includes all probes coordinates for the myeloid panel. This file is used by eggd_picardqc_v1.0.0 
* :sleeping_bed: /bed_files/b38/kits/myeloid/pindel_cgppindel_filtering_coordinates_v1.0.bed
> This bed file contains only regions of genes that the myeloid clinical team has deemed relevant for the detection of FLT3 ITDs and CEBPA/CALR Indels. It includes the  exon 13, intron 13-14, exon 14, intron 14-15, exon 15 of FLT3. It also includes exon 9 of CALR and exon 1 of CEBPA +/- 20bp padding. The coordinates were retrieved using Ensembl GRCh38.  The bed file contains the following columns: chromosome, start position, end position, gene symbol, Refseq transcript ID. 


* :sleeping_bed: /bed_files/b38/kits/snp_genotyping/snp_genotyping_GRCh38_v1.0.bed
> This is the bed file provided by NimaGen and includes all SNP positions. This bed file contains the following columns: chromosome, SNP position -1, SNP position, SNP RS ID
* :sleeping_bed: /bed_files/b38/kits/snp_genotyping/snp_genotyping_amplicon_GRCh38_v1.0.bed
> This is the bed file provided by NimaGen that includes all amplicon coordinates. This file is used by eggd_picardqc_v1.0.0. This bed file contains the following columns: chromosome, probe start position, probe end position, SNP RS ID, SNP position

* :sleeping_bed: /bed_files/b37/kits/twist_exome/panelapp_GMS_transcripts_210408.bed
> This is the bed file containing RefSeq exons +/- 5bp of transcripts within /eggd_001_Reference/dynamic_files/nirvana_genes2transcripts/210408_g2t.tsv. This file delineates regions used to assess Twist WES performance using hap.py.

* :sleeping_bed: /bed_files/b37/PAR_X.bed
> This bed file contains the PAR regions on chromosome X
* :sleeping_bed: /bed_files/b37/PAR_Y.bed
> This bed file contains the PAR regions on chromosome Y
