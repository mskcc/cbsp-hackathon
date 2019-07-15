# Genome Nexus' Post-Translational Modification (PTM) Annotations
[Genome Nexus](https://www.genomenexus.org) provides [Post-translational
Modification](https://en.wikipedia.org/wiki/Post-translational_modification)
annotations for each gene. See e.g.
(https://twitter.com/cbioportal/status/1126489748938395649):

![Genome Nexus PTM](https://user-images.githubusercontent.com/1334004/61243230-80e2a680-a715-11e9-8a8b-1c6d81a3ad2a.png)

We would like to annotate
[MAF](https://github.com/genome-nexus/genome-nexus-annotation-pipeline/blob/master/test/data/minimal_example.in.txt)
files with whether or not the are in the exact area of a PTM site (e.g.
ubiquitination). Once we have that we can make a bar chart that shows whether a
particular gene is often mutated in a particular PTM site.

In summary, make a jupyter notebook that:

- Annotates a MAF file with Genome Nexus. You can also use the
  https://github.com/genome-nexus/genome-nexus-annotation-pipeline and assume
  the MAF is already partially annotated. Only PTM annotations are missing.
- Check whether the mutations is in any PTM site
- Check whether mutations is in a specific PTM site (e.g. ubiquitination site).
- Check whether a mutation is 5 bases upstream of a PTM site
- Plot how often a mutation occurs in a PTM site in the input MAF

Alternatives/extensions:

- Instead of annotating a MAF file use the
  [cBioPortal](https://www.cbioportal.org) API to get the mutation data
