---
layout: page
permalink: /bioml/
title: BioML

bio_preprints:

bio_pubs:

    - title:   "Discordance in pleural mesothelioma response classification and modelling of impact on clinical trials"
      author:  "G.W. Cowell, J. Roche, C. Noble, D.B. Stobo, A.S. Papanastasiou, A.C. Kidd, S. Tsim and K.G. Blyth"
      journal: "Lung Cancer (2026) 221"
      doi:     "https://doi.org/10.1016/j.lungcan.2026.109624"
      year:    "2026"
      biorxiv: "https://doi.org/10.64898/2026.03.18.26348731"

    - title:   "MAPK-driven epithelial cell plasticity drives colorectal cancer therapeutic resistance"
      author:  "M. White, M.L. Mills, L.M. Millett, K. Gilroy, Y. Hong, L.B. Zeiger, R.J. Simpson, S.M. Corry, 
                A. Ligeza, T.R.M. Lannagan, S. Susanti, R.A. Ridgway, A.S. Yazgili, L. Grzesiak, R. Amirkhah, 
                C.A. Ford, N. Vlahov, H. Tovell, L. Officer-Jones, C. Ficken, R. Pennie, A.K. Najumudeen, A. Raven, 
                N. Nasreddin, E. Chauhan, A.S. Papanastasiou, C. Nixon, V. Morrison, R. Jackstadt, J.S. Graham, 
                C.J. Miller, S.J. Ross, S.T. Barry, V. Pavet, R.H. Wilson, J. Le Quesne, P.D. Dunne, S. Tejpar, 
                S. Leedham, A.D. Campbell, O.J. Sansom"
      journal: "Nature (2026) 650, 748–758"
      doi:     "https://doi.org/10.1038/s41586-025-09916-w"
      year:    "2026"
      biorxiv: ""

    - title:   "Unique functions of two overlapping PAX6 retinal enhancers"
      author:  "K. Uttley, A.S. Papanastasiou, M. Lahne, J.M. Brisbane, R.B. MacDonald, W.A. Bickmore and S. Bhatia"
      journal: "Life Science Alliance (2023) 6 (11), e202302126"
      doi:     "https://doi.org/10.26508/lsa.202302126"
      year:    "2022"
      biorxiv: "https://doi.org/10.1101/2022.11.25.517987"

    - title:   "Characterization of an Eye Field-like State during Optic Vesicle Organoid Development"
      author:  "L.J. Owen, J. Rainger, H. Bengani, F. Kilanowski, D.R. FitzPatrick and A.S. Papanastasiou"
      journal: "Development (2023) 150 (15), dev201432"
      doi:     "https://doi.org/10.1242/dev.201432"
      year:    "2022"
      biorxiv: "https://doi.org/10.1101/2022.08.16.504119"

    - title:   "Robust genetic analysis of the X-linked anophthalmic (Ie) mouse."
      author:  "B.A. Hernandez-Moran, A.S. Papanastasiou, D. Parry, A. Meynert, P. Gautier, G. Grimes, 
                I. Adams, V. Trejo-Reveles, H. Bengani, M. Keighren, I. Jackson, D.J. Adams, D.R. FitzPatrick and J. Rainger"
      journal: "Genes (2022) 13 (10), 1797"
      doi:     "https://doi.org/10.3390/genes13101797"
      year:    "2022"
      biorxiv: "https://doi.org/10.1101/2022.08.05.502661"

---

My research involves the application of Machine Learning (ML), statistical modelling and bioinformatic methods to 
large and diverse datasets, with the goal of tackling concrete questions in cancer biology. 
The data types I work with are, predominantly, single-cell and bulk sequencing datasets 
(e.g. scRNA-seq/scATAC-seq), spatial transcriptomics datasets (e.g. Xenium, CosMx) and 
increasingly imaging modalities (specifically, H&Es). 

I particularly enjoy the challenge of turning biological questions into tangible and 
actionable ML/computational tasks. 

### Modelling data to gain insights to biology  

In broad terms, the majority of my day-to-day work can be described as applying 
ML approaches to infer latent structures from biological datasets, in order to 
to probe or answer specific biological questions. Recent examples of this include: 

 - **Alignment of pre-clinical models with human tumours.** 
   Two important questions in pre-clinical cancer modelling (e.g. GEMM models) include: 
   how well do models recapitulate key events in human cancers, and how do we rank different 
   models of of a given cancer? To begin to answer these, I have developed a framework that compares 
   celltype-specific gene programs across species. This uses scRNA-seq datasets together 
   with matrix-factorization algorithms (e.g. NMF or archetypal analysis), optimal transport 
   and protein-language models (e.g. ESM2).

 - **Quantifying gene-program gradients in tumours.**
   A typical approach to analysing data is to place data points (e.g. cells) into discrete categories, 
   using clustering methods. While useful, these methods can often miss continuous variation
   amongst cells, and this can be particularly important in tumour biology where cells can 
   lie on a continuum spectrum of states. With the advent of spatial transcriptomics (ST), there is 
   an opportunity to quantify the spatial distributions of these states and their gradients. 
   I am combining ideas from the Implicit Neural Representations (INRs) and Latent Factor Models
   to learn continuous, spatial functions of gene-program expression and the associated gradients
   across tissues, from ST datasets. 
 
 - **Non-coding variants and Sequence-to-function modelsi.**
   The research I performed during my XDF (see below) left me fascinated by how the combinatorial 
   interactions of transcription factors with non-coding regions of the genome regulate the expression 
   of genes. Modelling epigenetic data using sequence-to-function models has 
   begun providing insights into these *enhancer codes* and I am interested in using this kind of 
   modelling to begin interpreting the effects non-coding variants have on tumour gene expression.
   I have gained experience training these models in the context of pancreatic cancer, using 
   publicly-available scATAC-seq datasets. I am also interested in exploring the use of these models
   for comparison of pre-clinical models with human tumours. 


As part of my role at the CRUK-SI, I am priviledged to be able to co-supervise multiple 
talented PhD students within the Computational Biology group. 
We are currently working on a number of exciting projects involving the integration of 
spatial transcriptomics and H&E images. 
Specifically, we combine standard ML or DL approaches with modern pathology Foundation 
Models, with the aim of quantifying links between cellular/tissue morphology and 
molecular events during tumour progression (across colorectal & pancreatic cancer, 
and mesothelioma). 

### Mammalian eye development

During my XDF (2018-2022), my work focussed on quantifying the neccessary molecular changes 
required for the stable formation of the mammalian eye-field -- the earliest known stage of 
eye development.
The main goal of this research was to identify how a key set of eye-field transcription factors 
is switched-on in a coordinated manner in the developing neural plate during gastrulation. 

Specifically, the main project I was involved with during this period used time-course data 
generated from mESC-derived optic-vescicle organoids, generated within the FitzPatrick lab. 
Using integrated analyses of matched RNA-seq and ATAC-seq time-course data, I helped developed 
a systematic approach to identify candidate transcription factors and cis-regulatory elements 
important for controlling the transition of stem cells to the eye-field state. Full details of 
this project can be found in our article in [Development](https://doi.org/10.1242/dev.201432).

During this period I was also very grateful to be awarded a small grant (*Wellcome/UoE ISSF*) titled
"*Coupled transcriptome-chromatin dynamics and regulation of cell state in early eye development*". 
The grant funded the generation of 10X Multiome data on optic-cup organoids and enabled the development
of computational approaches for the integrated analysis of scRNA-seq and scATAC-seq data. 
The key aims of this were to generate hypotheses of principles of chromatin-regulated 
gene-expression and cell differentiation, during eye-field specification.  


## Biology/Biomedical Pre-prints

{% for pub in page.bio_preprints %}
**{{pub.title}}**<br />
{{pub.author}}<br />
 *{{pub.year}}* 
{% if pub.biorxiv %}[[bioRxiv]({{pub.biorxiv}})]{% endif %}

{% endfor %}


## Biology/Biomedical Publications (peer reviewed)

{% for pub in page.bio_pubs %}
**{{pub.title}}**<br />
{{pub.author}}<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}
{% if pub.biorxiv %}[[bioRxiv]({{pub.biorxiv}})]{% endif %}

{% endfor %}


