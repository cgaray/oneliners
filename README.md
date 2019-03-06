# Useful one-liners for the command line

## Bioinformatics

* Sort a VCF with grep and sort:

```
grep '^#' in.vcf > sorted.vcf && grep -v '^#' in.vcf |  sort -k1,1 -k2,2n >> sorted.vcf
```
