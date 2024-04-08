# vcf2snp

This is a ruby script to convert your vcf files from a whole genome sequence (from say, nebula) into the snp file used by genotyping companies like 23andMe.  Sameness not guaranteed, there are edge cases with transpositions.

Written on ruby 3.1.2 -- if you see errors on not finding methods like tally, upgrade your ruby.  Or, install a new one and change the top line from `#!/usr/bin/ruby` to `#!<wherever you installed your newer ruby>`

## Example

After cloning this repository:

```
<path to this repository>/vcf2snp example.vcf
```
