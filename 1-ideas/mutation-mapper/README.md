# MAF Visualization by Mutation Mapper
MAF files can be used in all kinds of tools, one example would be visualize MAF data in Mutation Mapper, so the idea is to create a notebook that get MAF of subsets of samples and feed into MutationMapper Component. 
### Mutation Mapper
[Mutation Mapper](https://www.cbioportal.org/mutation_mapper) maps mutations on a linear protein and its domains (lollipop plots). We have online Mutation Mapper tool available on [cBioPortal](https://www.cbioportal.org/mutation_mapper).

![image](https://user-images.githubusercontent.com/16869603/124818796-77255f80-df39-11eb-93f6-707b44952b1c.png)

Mutation Mapper accepts tab-delimited or space-delimited mutation data as input, and should at least have the genomic location headers in the first line for a successful annotation. 

- Chromosome
- Start_Position
- End_Position
- Reference_Allele
- Variant_Allele

For example:
```
Sample_ID	Cancer_Type	Chromosome	Start_Position	End_Position	Reference_Allele	Variant_Allele
TCGA-49-4494-01	Lung Adenocarcinoma	7	55249071	55249071	C	T
TCGA-L9-A50W-01	Lung Adenocarcinoma	7	55249071	55249071	C	T
TCGA-38-4627-01	Lung Adenocarcinoma	7	55259515	55259515	T	G
TCGA-49-4490-01	Lung Adenocarcinoma	7	55259515	55259515	T	G
```

For more information about data format, please visit https://www.cbioportal.org/mutation_mapper.

### MAF files
MAF(Mutation Annotation Format) is a tab-delimited text file with aggregated mutation information from VCF Files and are generated on a project-level. You can download MAF data for individual studies on the [Data Sets Page](https://www.cbioportal.org/datasets) or the study view page for the study of interest, our [Data Hub](https://github.com/cBioPortal/datahub) also provides all studies for download. 

