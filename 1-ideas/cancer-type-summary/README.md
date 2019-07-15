# Cancer Type Summary Barchart

[cBioPortal](https://www.cbioportal.org) provides a way to show mutations in a
single gene across cancer types:

![cancer_types_summary](https://user-images.githubusercontent.com/1334004/61241744-2136cc00-a712-11e9-8c9a-9a3aa839dc6e.png)

We would like to recreate this plot in a Jupyter notebook using the cBioPortal
APIs, so people familiar with Python can easily customize the plot themselves.
The next step would be to annotate the mutations with [Genome
Nexus](https://www.genomenexus.org/), so one can color the bars by any
annotation found in Genome Nexus e.g. SIFT or Polyphen.

In summary create a notebook that:

- recreate the cancer types summary plot
- annotate the mutations with genome nexus and color the barchart by an
  annotation found in Genome Nexus (e.g. SIFT or Polyphen)

Extensions:

- Color barchart by whether or not they have hotspots 
