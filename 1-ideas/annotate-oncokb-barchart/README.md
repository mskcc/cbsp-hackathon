# Annotate MAF with OncoKB

[OncoKB](https://www.oncokb.org/) is a precision oncology knowledge base and
contains information about the effects and treatment implications of specific
cancer gene alterations.

The idea is to create a notebook that annotates a [MAF
file](https://github.com/oncokb/oncokb-annotator/blob/master/data/example_maf.txt)
with [OncoKB](https://www.oncokb.org/) and plots a distribution of the
mutations that have an OncoKB annotation with their corresponding
[level](https://www.oncokb.org/levels) e.g.:

![OncoKB barchart per level](https://user-images.githubusercontent.com/840895/48211952-9f073400-e348-11e8-8dcd-d00e7df63abd.png)

In summary make a Jupyter notebook that:

- annotates or describes how to annotate a MAF file with OncoKB. You can use
  the annotator here: https://github.com/oncokb/oncokb-annotator. You can
  either assume the MAF has been annotated before using that command line
  client. Alternatively, you can import the package into the notebook and do
  the annotation there.
- Plot the distribution as in the example above. As a first plot the x axis
  could show the gene names instead of the cancer types. The next plot could
  try to break it down per cancer type.
 
Extensions/alternative ideas:

- Instead of using a MAF, use a study from cBioPortal to annotate. You can also
  use the clinical data endpoint for `CANCER_TYPE` and `CANCER_TYPE_DETAILED`
  to get the cancer type information of each sample.
