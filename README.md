# bioinformatics-utils
Repository to share useful scripts for bioinformatics and SPLASH post-processing

## Utilities
### `anchors_from_fasta.py`
This script can be used to generate a set of anchors from a fasta file (or a single record in a fasta file).

### `convert_satc_format.py`
This script can be used to convert a plain text 3-column (count,anchor and target, sample) SATC file into a 4 column SATC file (sample, anchor, target, count)
Must provide the original anchor length used when running SPLASH (default: 27)
