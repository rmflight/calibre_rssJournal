# Calibre RSS Journal

In addition to PDF, many research journal articles are made available as HTML files on journal websites. Reading these on e-readers is currently hampered by the way the original html is set up.

This currently parses a set of URL's in a single text file hosted on the web (use the "dl." link for dropbox).

This file would contain an article on each line like this:

Iterative rank-order normalization of gene expression microarray data|http://www.biomedcentral.com/1471-2105/14/153

Combining MEDLINE and publisher data to create parallel corpora for the automatic translation of biomedical text|http://www.biomedcentral.com/1471-2105/14/146

Investigating the concordance of Gene Ontology terms reveals the intra- and inter-platform reproducibility of enrichment analysis|http://www.biomedcentral.com/1471-2105/14/143

OKVAR-Boost: a novel boosting algorithm to infer nonlinear dynamics and interactions in gene regulatory networks|http://bioinformatics.oxfordjournals.org/content/29/11/1416.full

NetworkPrioritizer: a versatile tool for network-based prioritization of candidate disease genes or other molecules|http://bioinformatics.oxfordjournals.org/content/29/11/1471.full

Currently can handle BMC Journals (tested on BMC Bioinformatics and BioData Mining) and Oxford Journals.

## Planned Improvements

Handle other journals (Pubmed Central (this might be through download of the epub versions that PMC is making available), PeerJ, eLife, PNAS, CSHL, Nature, Science, Wiley)

Remove the extra fluff on the HTML page that isn't actually part of the article
