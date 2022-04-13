# BLASTHits
# Language: Perl
# Input: TXT
# Output: TXT
# Tested with: PluMA 1.1,  Perl 5.18.2
# Dependency: BioPerl 1.006923

PluMA plugin that takes a summary of BLAST output
and screens out the hits.

The summary is provided as an input TXT file,
in addition to a forward and reverse primer.

The input file for the plugin specifies these three inputs
in a TXT file, one per line.

Metadata is returned in a TXT file for hits containing
both the forward and reverse primer.

