---
layout: single
title: About me
permalink: /about/
---

I am a postdoctoral researcher at Ghent University, working under the
supervision of Prof. Lieven Clement in the [statOmics
group](https://statomics.github.io/). My research currently focuses on
the analysis of mass spectrometry-based single-cell proteomics.

I have a background in biomedical sciences and in bioinformatics,
which I combined during a PhD in Prof. Laurent Gatto's lab. During
this academic track, I contributed [several articles]({% link
_pages/research.md %}#list-of-publications) in scientific journals,
but I must admit that my biggest scientific contribution are the
[software tools]({% link _pages/research.md %}#list-of-software) that
I develop and maintain. My goal is to use the knowledge and skills
that developed to solve real-life problem and help improve society.

I am a happy husband and a happy father of two boys. Strangely enough,
my high-tech and innovation-driven career is counter-balanced by a
low-tech and back-to-nature lifestyle at home. I am really passionate
about growing my own food, with a fascination for agro-ecology that
aims to produce food while having a positive environmental impact
(from an ecological point of view). Still, a scientific mindset is
what drives me day after day.

You are very welcome to get in touch with me in English, French, or
Dutch through any of the channels listed at the bottom of this
website.

*(checkout my one-page resume [here]({% link _pages/about.md %}#resume))*

## Career path

My Biomedical Science background allowed me to gain insights in the
intricate biological processes involved in human physiology and
disease. During my first master's thesis in the lab of Prof. Sophie
Lucas (UCLouvain), my interest grew towards bioinformatics as my
project on protein structure modelling involved advanced data
analysis. However, the frustration associated with my lack of
computational background led me to pursue a second master's in
Bioinformatics. I developed a fascination for single-cell technologies
through an integrated project with Prof. Rob Jelier (KULeuven) where I
analyzed a C.elegans scRNA-seq data set. In parallel, I conducted my
second master's thesis with Prof. Tom Wenseleers (KULeuven) where I
processed mass spectrometry (MS) data to characterize the chemical
composition of over 200 Belgian beers. Tom hired me for another year,
during which I met Prof. Laurent Gatto who offered me a PhD position
to work on single-cell proteomics (SCP), effectively combining my
passions for single-cell and MS-based technologies.

During my PhD, we quickly realized that the emerging field of SCP was
lacking computational standards. We, therefore, developed the
[`scp`](https://www.bioconductor.org/packages/release/bioc/html/scp.html)
software that provides standardized SCP data storage and manipulation
and the
[`scpdata`](https://www.bioconductor.org/packages/release/data/experiment/html/scpdata.html)
software that provides curated SCP data sets. With our tools, we could
replicate current workflows, offering a bird's-eye view on current
practices and highlighting bottlenecks of SCP data analysis. These
efforts positioned us as experts in the field, which we marked by
contributing to a pioneering paper on initial recommendations for SCP
experiments, lead by Prof. Nikolai Slavov. Finally, we developed a
novel approach that lays the foundation to the analysis of SCP data.

I foresee a prosperous future for SCP and aspire to play a pivotal
role in the adoption of SCP in biomedical research. However, the
current computational developments need to be extended beyond
proof-of-concept experiments to address the challenges associated with
biological replication. Therefore, I turned to Prof. Lieven Clement
and his statOmics lab who is internationally renowned for developing
comprehensive statistical methods for single-cell transcriptomics data
and proteomics data. Moreover, the lab has a close connection with the
VIB-UGent proteomics core facility, a Belgian leader in
proteomic-based biomedical and clinical research. This represents an
ideal work environment for building upon my skills in setting up data
analysis infrastructure for SCP and expanding these towards developing
novel statistical methods and tools that exploit SCP data to their
full potential, as well as to further develop myself towards an
independent academic researcher in proteomics research.

I hope to ultimately apply the skills and knowledge I will have
developed to solve real-life problems and concretely contribute to
improving patient's life, either through developing novel therapeutics
or boosting prevention.

## Resume

<img
  src="/assets/images/CV_Christophe_Vanderaa.svg"
  alt="Christophe Vanderaa's resume"
  style="border: 1px solid grey;"/>

<button
  onclick="downloadImage()"
  style="background-color: #FFA94D;
      color: white;
      padding: 20px 40px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;">
  <i class='fas fa-download'></i> Download my resume
</button>

<script>
  function downloadImage() {
    var link = document.createElement('a');
    link.href = '/assets/images/CV_Christophe_Vanderaa.pdf';
    link.download = 'CV_Christophe_Vanderaa.pdf';
    link.click();
  }
</script>
