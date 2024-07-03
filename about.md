## Harmonizome-KG: Bridging Enrichment Analysis Across Multiple Datasets

![Homepage](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/Example.png)

### Abstract

Gene and protein enrichment analysis is a critical step in the analysis of data collected from omics experiments. [Enrichr](https://maayanlab.cloud/Enrichr/) is a popular gene set enrichment analysis web-server search engine that contains hundreds of thousand annotated gene sets; it provides a comprehensive resource for annotated gene sets based on existing biological knowledge. While Enrichr has been useful in providing enrichment analysis against many gene set libraries from different domains, integrating enrichment results across libraries and domains of knowledge can further hypothesis generation. To this end, Enrichr-KG is a knowledge graph and web-server application that combines selected gene set libraries from Enrichr and presents these to the user for integrated analysis and visualization. Nodes in Enrichr-KG are either genes or functional terms, while edges connect genes to their enriched terms. This graphical representation of Enrichr libraries can illuminate hidden associations between genes and annotated terms from across multiple datasets. Enrichr-KG currently serves over 20 gene set libraries from different categories that include transcription, pathways, ontologies, diseases/drugs, and cell types. Enrichr-KG is freely available at https://maayanlab.cloud/enrichr-kg. 


### Processed Datasets Included in Harmonizome-KG

| Source                                   |   Genes |   Terms |   Edges |
|:-----------------------------------------|--------:|--------:|--------:|
| Achilles                                 |    4831 |     216 |  104046 |
| HuBMAP Azimuth Cell Type                 |    3560 |    1426 |   13794 |
| Biocarta                                 |    1397 |     254 |    4509 |
| BioGPS Human                             |   16379 |      84 |  205445 |
| BioGPS Mouse                             |   15437 |      74 |  170878 |
| BioGPS NCI-60                            |   12628 |      93 |  204284 |
| ABA Adult Human                          |   17979 |     414 | 1115464 |
| ABA Adult Mouse                          |   14248 |    2219 | 3178416 |
| ABA Developmental Human Microarray       |   17238 |     492 | 1270962 |
| ABA Developmental Human RNA Seq          |   15072 |     524 | 1183125 |
| ABA Prenatal Human                       |   18949 |     516 | 1464892 |
| CCLE CNV                                 |   23264 |    1036 | 1148953 |
| CCLE Gene Expression                     |   18025 |    1035 |  751223 |
| CCLE Mutations                           |    1667 |     904 |  105921 |
| CCLE Proteomics                          |    8959 |     375 |  122680 |
| CellMarker                               |   13607 |    7219 |   65981 |
| ChEA Binding Site 2022                   |   17962 |     757 |  917047 |
| ChEA TF Targets                          |   21224 |     199 |  386776 |
| ClinVar                                  |    2458 |    3291 |    3638 |
| CMAP Small Molecule Perturbations        |   12148 |    6100 | 1201897 |
| CORUM                                    |    2799 |    2066 |    9015 |
| COSMIC CNV                               |   19757 |     950 |  102249 |
| COSMIC Mutations                         |   17850 |    1026 |  746376 |
| CTD Chemical                             |   11125 |    9516 |  124344 |
| CTD Disease                              |   17255 |    5218 |  888519 |
| dbGAP                                    |    5668 |     510 |   12769 |
| DeepCoverMOA                             |    7750 |     874 |  173748 |
| DepMap Gene Dependency                   |   15946 |    1095 |  697098 |
| DEPOD                                    |     293 |     112 |     819 |
| DrugBank                                 |    2368 |    4928 |   15261 |
| ENCODE Histone Modification              |   22007 |     435 | 4454173 |
| ENCODE TF Binding                        |   22845 |    1679 | 8803973 |
| ENCODE TF Targets                        |   22452 |     181 | 1655383 |
| Roadmap Epigenomics DNA Methylation      |   13691 |      24 |   49516 |
| Roadmap Epigenomics Histone Modification |   21032 |     383 | 1201230 |
| Roadmap Epigenomics Gene Expression      |   12824 |      57 |  109318 |
| GAD Cell Line                            |   10702 |   12778 |   75029 |
| GAD High Level                           |    8016 |      18 |   28200 |
| GDSC                                     |   11704 |     624 |  280242 |
| GeneRIF                                  |   15201 |   91041 | 2549276 |
| GeneSigDB                                |   19509 |    3515 |  416256 |
| GEO Chem Perturbation                    |   21336 |     415 |  318530 |
| GEO Disease Perturbation                 |   18516 |     233 |  139800 |
| GEO Gene Perturbation                    |   22020 |     738 |  367922 |
| GEO Kinase Perturbation                  |   19789 |     285 |  171000 |
| GEO TF Perturbation                      |   19279 |     154 |  151898 |
| GEO Virus Perturbation                   |   19779 |     366 |  222682 |
| GlyGen                                   |    2231 |    1910 |   20486 |
| GO Bio Process 2023                      |   14811 |   12318 |  198050 |
| GO Cellular Component 2023               |   11089 |     926 |   41883 |
| GO Molecular Func 2023                   |   12478 |    3851 |   50339 |
| GTEx Aging Signatures                    |   16047 |     135 |   67500 |
| GTEx eQTL                                |     149 |    7815 |     149 |
| GTEx Tissue Sample                       |   19249 |    2918 | 8421702 |
| GTEx Tissue 2023                         |   17369 |      53 |  108000 |
| Guide To Pharm Chem                      |     899 |    4894 |    9380 |
| Guide To Pharm Protein                   |     187 |     211 |     410 |
| GWAS Catalog                             |    4356 |    1007 |    8255 |
| GWASdb Disease                           |   11804 |     585 |  217330 |
| GWASdb Phenotype                         |   12487 |     822 |  274574 |
| Heiser                                   |   15144 |      56 |  196872 |
| HMDB                                     |    5326 |   22137 |  845725 |
| HPA Cell Lines                           |   15372 |      43 |  102943 |
| HPA Tissue Samples                       |   16658 |     121 |  303282 |
| HPA Tissues mRNA                         |   17426 |      31 |   81092 |
| HPA Tissue Protein                       |   15706 |      44 |  138585 |
| HPM                                      |    4362 |       4 |    4362 |
| HPO                                      |    3158 |    6842 |  304995 |
| Hub Proteins                             |    9362 |     289 |   58327 |
| HuGE Navigator                           |   12055 |    2715 |  141799 |
| HumanCYC Pathways                        |     932 |     286 |    1839 |
| InterPro                                 |   18002 |   11015 |   62614 |
| JASPAR PWMs                              |   21375 |     111 |  148069 |
| COMPARTMENTS Curated                     |   16736 |    1463 |  328753 |
| COMPARTMENTS Expts                       |    6495 |      59 |   91061 |
| COMPARTMENTS Text Mining                 |   14375 |    2081 |  546634 |
| DISEASES Curated                         |    2252 |     770 |   18144 |
| DISEASES Expts                           |    4055 |     350 |   35164 |
| DISEASES Text Mining                     |   15309 |    4628 |  832622 |
| TISSUES Curated                          |   16215 |     643 |  357465 |
| TISSUES Expts                            |   15505 |     243 |  274154 |
| TISSUES TextMining                       |   16184 |    4187 | 1836577 |
| KEA                                      |    3406 |     457 |   12161 |
| KEGG                                     |    3947 |     200 |    9324 |
| Kinase Library                           |    5046 |     303 |   30299 |
| LINCS KiNativ                            |     102 |      23 |     149 |
| LINCS KinomeScan                         |     277 |      71 |    2057 |
| Klijn CNV                                |   24922 |     668 | 2495888 |
| Klijn mRNA                               |   13944 |     650 | 1357992 |
| Klijn Mutations                          |   14367 |     676 |  133818 |
| KnockTF                                  |   17963 |     566 |  108820 |
| IMPC Knockout                            |    6763 |     667 |   36451 |
| LINCS L1000 Chem Pert                    |   12126 |   23913 | 5086167 |
| LINCS L1000 CRISPR                       |    9551 |    5049 | 2524500 |
| LINCS CMAP Chemical                      |    8347 |   31028 | 4189677 |
| LOCATE Curated Protein                   |    9639 |      78 |   79181 |
| LOCATE Predicted Protein                 |   19747 |      24 |  154700 |
| MGI MPO                                  |    7798 |    8579 |  466673 |
| MGI Phenotype                            |   12894 |   10234 |  252920 |
| MiRTarBase                               |   12086 |     596 |   37415 |
| MotifMap                                 |   20432 |     331 |  158860 |
| MoTrPAC                                  |   12426 |     142 |   95052 |
| MSigDB Comp Signatures                   |    4869 |     356 |   41327 |
| MSigDB Oncogenic Signatures              |   10765 |      90 |   29967 |
| MW Metabolites                           |    1068 |     731 |    5042 |
| OMIM                                     |    4553 |    5540 |    6666 |
| PANTHER                                  |    1962 |     145 |    4255 |
| Pathway Commons                          |   15747 |   15747 | 3527164 |
| WikiPathways PFOCR                       |   13173 |   35464 |  307416 |
| PhosphoSitePlus Kinase                   |    2447 |     359 |    6013 |
| PhosphoSitePlus Disease                  |     212 |     140 |     356 |
| Phosphosite Textmining                   |    2857 |     881 |  159580 |
| PID Pathways                             |    2510 |     223 |    8027 |
| Proteomics DB                            |    2776 |      53 |   21921 |
| Reactome                                 |    7535 |    1638 |   83680 |
| Sanger Dep Map                           |    8230 |     949 |  189800 |
| SILAC Drug Perturbation                  |    2770 |      23 |    5808 |
| SILAC Gene Perturbation                  |     203 |      10 |     840 |
| SILAC Ligand Perturbation                |    2022 |       9 |    5439 |
| Tabula Sapiens                           |    8184 |     469 |   46900 |
| TargetScan Conserved                     |   14923 |    1537 |  513997 |
| TargetScan Nonconserved                  |   18048 |    1539 |  627985 |
| TCGA                                     |   19794 |    5904 | 4367061 |
| VirusMINT Virus                          |     706 |      68 |    1036 |
| VirusMINT Viral Protein                  |     706 |     185 |    1140 |
| WikiPathways Pathways                    |    6093 |     427 |   22242 |
### Using Enrichr-KG

#### 1. Performing enrichhment analysis
##### 1.1 Submitting a query
![Input Form](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/input.png)

A typical analysis with Enrichr-KG begins by inputting a gene set in the text box shown above, and selecting up to 5 Enrichr libraries to query. You can further control the results by tweaking the following parameters:
* **Minimum libraries per gene:** Filters out genes that are not enriched in multiple libraries.
* **Minimum links per gene:** Filters out genes that do not overalap with multiple terms.
* **Minimum links per term:** Filters out terms that only overlap with few genes.
* **Subgraph size limit:** Controls the size of the subgraph by only keeping the top genes that are connected to multiple terms across libraries.

Furthermore, users can add a description to their gene set and control the number of terms returned per library. By default this is set to 5. In the screenshot above, we used the example gene set and selected the two LINCS-related datasets for enrichment analysis.

##### 1.2 Navigating the results
![Enrichment Result](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/enrichment_result.png)
Upon clicking submit, the user is redirected to the results page which should look like the image above. Nodes are colored based on their type. The results can be displayed as a bar chart showing the top enrichred terms ordered by p-value. The icons on the upper right corner enable users to: (1) display the legend; (2) refresh, re-orient, or clear the graph; (3) display the edge labels; (4) download the graph as an image (JPG, PNG, or SVG); (5) share a permanent link; and (6) enter full screen mode.

![Hover Node](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/hover.png)
Hovering over the nodes and edges invokes a text box on the top left containing the metadata of the node or edge. The has buttons to: (1) delete a node from the subnetwork; (2) go to the node's page to view its immediate neighbors; and (3) close the box.

##### 1.3 Augmenting the enrichment subnetwork with co-expressed genes

You can augment your subnetwork with additional genes that are co-expressed with the genes in the subnetwork. This option sends the overlapping gene to [Geneshot's](https://maayanlab.cloud/geneshot/) API that uses the gene co-expression matrix from [ARCHS4](https://maayanlab.cloud/archs4/) to return the genes with the top mean correlation scores with all of the overlapping genes in the subnetwork.

![enrich_augmentation](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/augment_enrichment.png)

##### 1.3 Viewing PPI and Co-expression links between genes

Enrichr-KG hosts gene-gene links using co-expression data from [ARCHS4](https://maayanlab.cloud/archs4/) and PPI data from [STRING](https://string-db.org/). By selecting this option, you can view the connections between the overlapping and augmented genes in the network.

![enrich_gene_links](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/gene_links_enrichment.png)



#### 2. Querying terms or genes
Enrichr-KG also implements the Enrichr's gene and term search functionality. This enables viewing the immediate neighbors for a gene, i.e., what annotated gene sets include that gene; or the immediate neighbors of a term, i.e., the genes associated with the term. Control icons in this display are similar to ones that are present in the enrichment results interface. Importantly, the user can control how many neighbors to display.
![Single Term](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/single-term.png)

Furthermore, users can view selected relationships of interest by using the relations filter.
![Relation](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/relation.png)

You can expand the network by clicking the + sign to find the shortest path between a start term and a type of end node or an end term.
![form_options](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/form_option.png)


To view the shortest path between a start term (the gene COPB2) and a type of node (Human Phenotype Ontology), you can select the `node_type` on the "End with" select form.
![Single To Node](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/start_end_node.png)


Furthermore, Enrichr-KG also provides the ability to perform two term/gene search. This function finds all the shortest paths between any two entities within the Enrichr-KG knowledge graph. This fucntionality facilitates the discovery of hidden connections between functional terms and genes.
![Two Term](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/two-term.png)

Augmentation and gene links via PPI and co-expression are also available in the term and gene search page:

![Augment Search](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/augment_search.png)

![Gene Link Search](https://s3.amazonaws.com/maayan-kg/enrichr-kg/assets/060624/gene_links_search.png)



## Please acknowledge Enrichr-KG in your publications by citing the following reference:

[Evangelista JE, Xie Z, Marino GB, Nguyen N, Clarke DJB, Ma'ayan A. Enrichr-KG: bridging enrichment analysis across multiple libraries. Nucleic Acids Res. 2023 May 11:gkad393. doi: 10.1093/nar/gkad393. PMID: 37166973.](https://academic.oup.com/nar/article/51/W1/W168/7160192)