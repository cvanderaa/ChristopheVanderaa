---
layout: single
title: My research
permalink: /research/
entries_layout: grid
---

*(Updated on March 2025)*

My research mainly focuses on the development of tools and practices
to analyze mass spectrometry-based single-cell proteomics (SCP) data.
I achieved several milestones during my PhD at Prof. Laurent Gatto's
lab.

I established the first standardized data structure for mass
spectrometry-based single-cell proteomics with the development of
`scp`, an R/Bioconductor package for storing and processing
single-cell proteomics data. I am the head maintainer of the sofware
which cumulates over 8500 downloads. In parallel, I actively
contributed and still am an official maintainer of `QFeatures`, an
R/Bioconductor package to store and process MS-based quantitative data
(cumulating over 58000 downloads). You may read more in

> Vanderaa & Gatto (2021). Replication of single-cell proteomics data
> reveals important computational challenges. In Expert Review of
> Proteomics (Vol. 18, Issue 10, pp. 835–843). Cited by 33.

Next, I created a database of curated data sets that are ready for
analysis. The aim of the database is to guide computational
development based on real data. I have published the software as
another R/Bioconductor package, `scpdata`. Currently, the database
contains 29 data sets and cumulates over 4000 downloads. You can read
more in

> Vanderaa & Gatto (2023). The Current State of Single‐Cell Proteomics
> Data Analysis. In Current Protocols (Vol. 3, Issue 1). Cited by 14.

Thanks to `scp` and `scpdata`, I replicated various SCP data analyses.
I report these replication efforts in my `SCP.replication` website.
Replicating the analysis offered me many benefits. First, I repurposed
these replications efforts as didactic material, increasing the
visibility of my software. Second, replicating data analyses increases
the trust in published results or to highlight potential flaws,
effectively moving the field forward. It allowed me to grow an
international reputation which materialized in an important
collaboration among pioneers of the field, read more in

> Gatto, Aebersold, Cox, Demichev, Derks, Emmott, Franks, Ivanov,
> Kelly, Khoury, Leduc, MacCoss, Nemes, Perlman, Petelski, Rose,
> Schoof, Van Eyk, Vanderaa, Yates 3rd, Slavov (2023). Initial
> recommendations for performing, benchmarking and reporting
> single-cell proteomics experiments. In Nature Methods (Vol. 20,
> Issue 3, pp. 375–386). Cited by 101.

A last benefit from replicating analyses was to pinpoint the key
challenges of SCP data analysis and the current bottlenecks. One major
bottleneck I identified was the high prevalence of missing values. You
can find my recommendation on how to handle missing values in SCP data
in

> Vanderaa & Gatto (2023). Revisiting the Thorny Issue of Missing
> Values in Single-Cell Proteomics. In Journal of Proteome Research
> (Vol. 22, Issue 9, pp. 2775–2784). Cited by 15.

Finally, my main achievement was the developement of scplainer, a
principled approach that lays the ground for rigourous analysis of SCP
data. Since the publication of the preprint, it already initiated
several collaborations across the world. To read more

> Vanderaa & Gatto (2024). Scplainer: Using Linear Models to
> Understand Mass Spectrometry-Based Single-Cell Proteomics Data.
> bioRxiv (submitted, not peer-reviewed).

Thanks to Prof. Laurent Gatto’s mentorship, I developed a strong
commitment to open and reproducible science. Prof. Laurent Gatto is
internationally renowned for his exemplary research practices
concerning open and reproducible science. All my projects and software
packages are available on GitHub (https://github.com/cvanderaa and
https://github.com/UCLouvain-CBIO/) and my analyses are reproducible
through Docker images (https://hub.docker.com/u/cvanderaa, see also
https://uclouvain-cbio.github.io/SCP.replication/).

The next goal for me is to unlock SCP for biomedical research as my
ultimate goal is to apply my research to help answering tangible
health-related questions. Therefore, I joined the lab of Prof. Lieven
Clement to extend the current tools. I will solve the key data
analysis bottlenecks of current workflows by (1) identifying unknown
source of variation through dimension reduction while accounting for
technical effects and the high prevalence of missing values; (2)
addressing the hierarchical correlation structure of multiple cells
within each sample in multi-sample SCP data; and (3) revolutionize SCP
data analysis by building tools to infer on differences that go beyond
the mean, i.e. for differential variance, skewness, multimodality and
presence/absence without relying on harmful imputation strategies.
Thanks to Prof. Lieven Clement's mentorship, I plan to perfect my
statistical skills and acquire rigourous method benchmarking
practices.

## Scientific meetings

You can find a [comprehensive list]({% link
_posts/2024-05-03-attending-conferences.md%}) of my attendence to
different scientific meetings. Below are some highlights:

- I was an invited speaker at the European symposium on single-cell
  proteomics 2024.
- I presented several short talks: SCP2020, RSG symposium 2020,
  Eurobioc2020, IB2 research day 2021, EuroBioc2023.
- I presented several workshops providing hands-on tutorials on my
  software: Bioc2021, SCP2021, BiocAsia2021. I'm also invited to
  provide workshops in Strasbourg and Liverpool in 2025.
- I have presented up to 7 posters during different conferences.

## Supervision

I enjoyed supervising the following students:

- Samuel Grégoire: Master student in Biomedical Sciences
- Charlotte Léonard: Master student in Applied Mathematics
- Théo Christopher Borremans: bachelor student in Biology
- Léopold Guyot: Master student in Bioinformatics

## Scientific awards and research funding

- ASP-FNRS fellowship (graded A+: outstanding, 2019)
- EURASIP, best poster award,  2018, Tensor-based Signal Processing
- Best poster award during the de Duve PhD day (2020).

## List of software

#### Software I still maintain

- Vanderaa C, Gatto L (2024). _scp: Mass Spectrometry-Based
  Single-Cell Proteomics Data Analysis_. R package version 1.15.2,
  <https://www.bioconductor.org/packages/release/bioc/html/scp.html>.

- Vanderaa C, Gatto L, Ayar E, Grégoire S (2024). _scpdata:
  Single-Cell Proteomics Data Package_. R package version 1.13.1,
  <https://www.bioconductor.org/packages/release/data/experiment/html/scpdata.html>.

- Gatto L, Vanderaa C (2024). _QFeatures: Quantitative features for
  mass spectrometry data_. R package version 1.15.2,
  <https://www.bioconductor.org/packages/release/bioc/html/QFeatures.html>.

#### Software I contributed

- Ramos M, Argelaguet R, Abadi A, Righelli D, Vanderaa C, EckenrodeK,
  Geistlinger L, Waldron L (2024). _SingleCellMultiModal: Integrating
  Multi-modal Single Cell Experiment datasets_. R package version
  1.19.0,
  <https://bioconductor.org/packages/release/data/experiment/html/SingleCellMultiModal.html>.

- Wenseleers T, Vanderaa C (2022). _export: Streamlined Export of
  Graphs and Data Tables_. R package version 0.3.0,
  <https://CRAN.R-project.org/package=export>.

#### Reviewing software

I am an official Bioconductor reviewer. 

## List of publications

#### First author

<!-- Note to self. Citations were fromatted using the "Taylor &
Francis - AMA" style -->

- Vandenbulcke* S, Vanderaa* C, Crook O, Martens L, Clement L.
  msqrob2TMT: robust linear mixed models for inferring differential
  abundant proteins in labelled experiments with arbitrarily complex
  design. bioRxiv. Published online March 29, 2024:2024.03.29.587218.
  doi:10.1101/2024.03.29.587218

- Vanderaa C, Gatto L. scplainer: using linear models to understand
  mass spectrometry-based single-cell proteomics data. bioRxiv.
  Published online January 10, 2024:2023.12.14.571792.
  doi:10.1101/2023.12.14.571792

- Thesis: Vanderaa C. A Principled Approach and Standardised Software
  for Mass Spectrometry-Based Single-Cell Proteomics Data Analysis.
  UCL-Université Catholique de Louvain; 2024.

- Vanderaa C, Gatto L. Revisiting the Thorny Issue of Missing Values
  in Single-Cell Proteomics. J Proteome Res. 2023;22(9):2775-2784.

- Vanderaa C, Gatto L. The Current State of Single-Cell Proteomics
  Data Analysis. Curr Protoc. 2023;3(1):e658.

- Vanderaa C, Gatto L. Replication of single-cell proteomics data
  reveals important computational challenges. Expert Rev Proteomics.
  2021;18(10):835-843.

#### Co-author

- Dzialo MC, Arumugam S, Piampongsant S, Cool L, Vanderaa C,
  Herrera-Malaver B, et al. Drosophila suzukii and Drosophila
  melanogaster prefer distinct microbial and plant aroma compounds in
  a complex fermented matrix. iScience. 2024;27(11):111141.

- Schreurs M, Piampongsant S, Roncoroni M, Cool L, Herrera-Malaver B,
  Vanderaa C, et al. Predicting and improving complex beer flavor
  through machine learning. Nat Commun. 2024;15(1):2368.

- Grégoire S, Vanderaa C, Ruys SPD, Mazzucchelli G, Kune C, Vertommen
  D, et al. Mass Spectrometry Based Single Cell Proteomics. Springer
  US; 2023.

- Eckenrode KB, Righelli D, Ramos M, Argelaguet R, Vanderaa C,
  Geistlinger L, et al. Curated single cell multimodal landmark
  datasets for R/Bioconductor. PLoS Comput Biol. 2023;19(8):e1011324.

- Gannoun L, De Schrevel C, Belle M, Dauguet N, Achouri Y, Loriot A,
  et al. Axon guidance genes control hepatic artery development.
  Development. 2023;150(16). doi:10.1242/dev.201642

- Gatto L, Aebersold R, Cox J, Demichev V, Derks J, Emmott E, et al.
  Initial recommendations for performing, benchmarking and reporting
  single-cell proteomics experiments. Nat Methods. 2023;20(3):375-386.

- Lecomte S, Devreux J, de Streel G, van Baren N, Havelange V,
  Schröder D, et al. Therapeutic activity of GARP:TGF-β1 blockade in
  murine primary myelofibrosis. Blood. 2023;141(5):490-502.

- Moulis M, Runser SVM, Glorieux L, Dauguet N, Vanderaa C, Gatto L, et
  al. Identification and implication of tissue-enriched ligands in
  epithelial-endothelial crosstalk during pancreas development. Sci
  Rep. 2022;12(1):12498.

- Goelen T, Sobhy IS, Vanderaa C, Wäckers F, Rediers H, Wenseleers T,
  et al. Bacterial phylogeny predicts volatile organic compound
  composition and olfactory response of an aphid parasitoid. Oikos.
  2020;129(9):1415-1428.

- Goelen T, Sobhy IS, Vanderaa C, Boer JG, Delvigne F, Francis F, et
  al. Volatiles of bacteria associated with parasitoid habitats elicit
  distinct olfactory responses in an aphid parasitoid and its
  hyperparasitoid. Funct Ecol. 2020;34(2):507-520.

- Liénart S, Merceron R, Vanderaa C, Lambert F, Colau D, Stockis J, et
  al. Structural basis of latent TGF-β1 presentation and activation by
  GARP on human regulatory T cells. Science. 2018;362(6417):952-956.

#### Reviewing papers

I reviewed the following articles: 

- One article for Nature Communications (not published)
- One article for Nature Methods (under revision)
- One article for Bioinformatics (under revision)
- (co-revision with Laurent) Kong, Weijia, Harvard Wai Hann Hui, Hui
  Peng, and Wilson Wen Bin Goh. 2022. “Dealing with Missing Values in
  Proteomics Data.” Proteomics 22 (23-24): e2200092.
- (co-revision with Laurent) Li, Wei, Fan Yang, Fang Wang, Yu Rong,
  Bingzhe Wu, Han Zhang, and Jianhua Yao. 2023. “A Versatile Deep
  Graph Contrastive Learning Framework for Single-Cell Proteomics
  Embedding.” bioRxiv.
- (co-revision with Laurent) Wang, Fang, Chunpu Liu, Jiawei Li, Fan
  Yang, Jiangning Song, Tianyi Zang, Jianhua Yao, and Guohua
  Wang.2023. “SPDB: A Comprehensive Resource and Knowledgebase for
  Proteomic Data at the Single-Cell Resolution.” Nucleic Acids
  Research.

<br>

## Related posts

{% for post in site.posts %}
  {% if post.tags contains "research" %}
    {% include archive-single.html type="grid"%}
  {% endif %}
{% endfor %}
