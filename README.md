# Merge-VCF-files
Find intersection of two VCF files

Usage:
python merge_vcf_dict_RLN.py -i1 diploid_samples.vcf -i2 clinVar_pathogenic_tp53_edt.vcf -o common_dip_clvar_tp53.vcf

The python script merges two VCF files based on the chromosomal number, position and the reference nucleotide. 
While merging, the output file is populated with the variants, qscore from the first vcf file.

A tab-serparated txt file of the list of all variants common between the two input files are also print out.

E.g.,

RLN-MBP-2016:aneuploid diploid raghav$ python merge_vcf_dict_RLN.py -i1 diploid_samples_freebayes.vcf -i2 clinVar_all_tp53_edt.vcf -o comm_dip_fb_clnvar.vcf
Reading diploid_samples_freebayes.vcf
Reading clinVar_all_tp53_edt.vcf
Merging header information
Merging variant calls
Done !!! The VCF output is in the file comm_dip_fb_clnvar.vcf
Done !!! The table output is in the file comm_dip_fb_clnvar_table.txt

