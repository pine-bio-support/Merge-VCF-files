RLN-MBP-2016:BRCA raghav$ python3 merge_vcf_dict_RLN.py -i1 BRCA_freebayes.vcf -i2 clinVar_all_BRCA1_BRCA2.vcf -o BRCA_fb_clinvar.vcf
Reading BRCA_freebayes.vcf
Reading clinVar_all_BRCA1_BRCA2.vcf
Merging header information
Merging variant calls
Done !!! The VCF output is in the file BRCA_fb_clinvar.vcf
Done !!! The table output is in the file BRCA_fb_clinvar_table.txt

RLN-MBP-2016:BRCA raghav$ python3 merge_vcf_dict_RLN.py -i1 BRCA_mutect.vcf -i2 clinVar_all_BRCA1_BRCA2.vcf -o BRCA_mu_clinvar.vcf
Reading BRCA_mutect.vcf
Reading clinVar_all_BRCA1_BRCA2.vcf
Merging header information
Merging variant calls
Done !!! The VCF output is in the file BRCA_mu_clinvar.vcf
Done !!! The table output is in the file BRCA_mu_clinvar_table.txt

RLN-MBP-2016:BRCA raghav$ python3 merge_vcf_dict_RLN.py -i1 BRCA_freebayes.vcf -i2 ClinicaldbSNP_BRCA1_BRCA2.vcf -o BRCA_fb_dbsnp.vcf
Reading BRCA_freebayes.vcf
Reading ClinicaldbSNP_BRCA1_BRCA2.vcf
Merging header information
Merging variant calls
Done !!! The VCF output is in the file BRCA_fb_dbsnp.vcf
Done !!! The table output is in the file BRCA_fb_dbsnp_table.txt

RLN-MBP-2016:BRCA raghav$ python3 merge_vcf_dict_RLN.py -i1 BRCA_mutect.vcf -i2 ClinicaldbSNP_BRCA1_BRCA2.vcf -o BRCA_mu_dbsnp.vcf
Reading BRCA_mutect.vcf
Reading ClinicaldbSNP_BRCA1_BRCA2.vcf
Merging header information
Merging variant calls
Done !!! The VCF output is in the file BRCA_mu_dbsnp.vcf
Done !!! The table output is in the file BRCA_mu_dbsnp_table.txt
