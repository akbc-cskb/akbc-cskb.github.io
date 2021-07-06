---
layout: default
title: CSKB@AKBC21
nav_order: 1
description: "Workshop on Common-Sense Knowledge Bases at AKBC 2021"
permalink: /
last_modified_date: July 5th 2021
toc_list: true
---


 
 
# Workshop on Commonsense Reasoning and Knowledge Bases (CSKB) at AKBC 2021
{: .fs-8 .fw-800 .text-green-300 .no_toc style="font-family: 'Agency FB Bold';"}
 

<span class="fs-2">
<!-- [Paper](XCSR_paper.pdf){: target="_blank" .btn .btn-green .mr-1 .fs-3} -->
<!-- [Github](https://github.com/INK-USC/XCSR/){: target="_blank" .btn .btn-purple .mr-1 .fs-3 } -->
<!-- [Download MickeyCorpus](https://forms.gle/fCxN1YAyqKpQ4cXNA){: target="_blank" .btn .btn-blue .mr-1 .fs-3 } -->
<!-- [Download X-CSR Datasets](https://forms.gle/gVCNgVXr1tyYkDya9){: target="_blank" .btn .btn-blue .mr-1 .fs-3 } -->
<!-- [Video](https://mega.nz/file/5SpQjJKS#J82pfZVDzy3r4aWdNF4R6O8EP5gsepbY20vYihANfgE){: target="_blank" .btn .btn-blue .mr-1 .fs-3 }
[Slides](opencsr_naacl_slides.pptx){: target="_blank" .btn .btn-red .mr-1 .fs-3 } -->
</span> 

---
 

Recent advances in large pre-trained language models have shown that machines can directly learn large quantities of commonsense knowledge through self-supervised learning on raw text. However, they still fall short of human-like understanding capabilities: they make inconsistent predictions, learn to exploit spurious patterns, and fail to robustly apply learned knowledge to downstream applications. Consequently, the development and integration of unpaired, outside knowledge representation sources remains critically important to provide machine commonsense engines with scaffolding to learn structured reasoning. We organize this workshop to encourage discussion of current progress on building machines with commonsense knowledge and reasoning abilities, with special focus on commonsense knowledge bases (CSKBs). The workshop will be collocated with [**AKBC 2021**](https://www.akbc.ws/2021/){: target="_blank"}. 

### Latest News
{: .no_toc}

- ***July 6, 2021.*** The first version of our [call for papers](#call-for-papers) is out.

### Important Dates
{: .no_toc}

- All paper submissions due – ***August 5, 2021***{: .text-red-300}
- Notification of acceptance – ***Sep 10, 2021***{: .text-red-300}
- Camera-ready papers due – ***September 30, 2021***{: .text-red-300}
- Workshop – ***October 7, 2021***{: .text-red-300}


### Organizers
{: .no_toc}

<!-- - [***Vered Shwartz***](https://vered1986.github.io/){: target="_blank"}, Allen Institute for AI (AI2) and the University of Washington. 
- [***Antoine Bosselut***](https://atcbosselut.github.io/){: target="_blank"}, Allen Institute for AI (AI2) and Stanford University.
- [***Xiang Lorraine Li***](https://people.cs.umass.edu/~xiangl/){: target="_blank"}, UMass Amherst.
- [***Bill Yuchen Lin***](https://yuchenlin.xyz/){: target="_blank"}, University of Southern California. -->


![Organizers](images/ognzers.png)
 
<details markdown="block">
  <summary>
    <a href="https://vered1986.github.io/" target="_blank"><strong><em>Vered Shwartz</em></strong></a>, Allen Institute for AI (AI2) & the University of Washington.
  </summary>
  {: .fs-3 .fw-500 .text-blue-300}
<table><td>
Vered Shwartz is a postdoctoral researcher at the Allen Institute for AI (AI2) and the Paul G. Allen School of Computer Science & Engineering at the University of Washington. She will join the Department of Computer Science at the University of British Columbia as an Assistant Professor in fall 2021. Her research interests include computational semantics and pragmatics, and commonsense reasoning. She co-organized the ACL 2018 Student Research Workshop, the SemEval 2018 shared task on hypernymy discovery, the AAAI 2020 Workshop on Reasoning for Complex Question Answering (Special Edition on Commonsense Reasoning), and the EMNLP 2020 workshop on Simple and Efficient NLP, and co-instructed the ACL 2020 tutorial on commonsense reasoning.
</td></table>
</details> 

<details markdown="block">
  <summary>
    <a href="https://atcbosselut.github.io/" target="_blank"><strong><em>Antoine Bosselut</em></strong></a>, Stanford University & EPFL.
  </summary>
  {: .fs-3 .fw-500 .text-blue-300}
<table><td>
Antoine Bosselut is a postdoctoral researcher at Stanford University and at the Allen Institute for AI (AI2). He will join the School of Computer and Communication Sciences at EPFL as an Assistant Professor in Fall 2021. His research interests are in the intersection of knowledge representation, reasoning, and NLP. He organized the West Coast NLP (WeCNLP) from 2018 to 2020, the NeuralGen workshop at NAACL 2019, the GEM workshop at ACL 2021, and co-instructed the ACL 2020 tutorial on commonsense reasoning, the EMNLP 2020 tutorial on neural text generation, and the AAAI 2021 tutorial on commonsense reasoning.
</td></table>
</details> 

<details markdown="block">
  <summary>
    <a href="https://people.cs.umass.edu/~xiangl/" target="_blank"><strong><em>Xiang Lorraine Li</em></strong></a>, UMass Amherst.
  </summary>
  {: .fs-3 .fw-500 .text-blue-300}
<table><td>
Xiang Lorraine Li is a Ph.D. student at UMass Amherst advised by Andrew McCallum. Previously, she completed her Master's from the University of Chicago while researching with Kevin Gimpel at TTIC. Her research interest mainly lies in learning efficient commonsense knowledge representations with specific build-in model biases (e.g., transitivity bias of Is-A relations) and examining commonsense knowledge in large language models. She serves as a program committee (reviewer) for multiple conferences and workshops, including AKBC, EMNLP, ACL, AAAI, etc. 
</td></table>
</details> 

<details markdown="block">
  <summary>
    <a href="https://yuchenlin.xyz/" target="_blank"><strong><em>Bill Yuchen Lin</em></strong></a>, University of Southern California.
  </summary>
  {: .fs-3 .fw-500 .text-blue-300}
<table><td>
Bill Yuchen Lin is a Ph.D. candidate at the University of Southern California, advised by Prof. Xiang Ren. His research goal is to teach machines to think, talk, and act with commonsense knowledge and commonsense reasoning ability like humans do. Towards this ultimate goal, he has been developing knowledge-aware reasoning methods (e.g., KagNet, MHGRN, DrFact) and constructing benchmark datasets (e.g., CommonGen and RiddleSense).
He also initiated an online compendium of commonsense reasoning  research, which serves as a portal site for the community. He has been serving as program committee members for ACL, EMNLP, NAACL, ICLR, NeurIPS, etc.
</td></table>
</details> 
---
## Call for papers 


### Topics of Interest
{: .no_toc}

The topics of interest include, but are not limited to: 

- ***Resources***{: .text-red-300}: acquiring commonsense knowledge (from text corpora, images, videos, pre-trained neural models, etc.); constructing and completing (semi-)structured CSKBs; consolidating CSKBs under unified schemas. 
- ***Benchmarks***{: .text-red-300}: designing challenging tasks and building datasets to evaluate models' commonsense knowledge and reasoning abilities; designing new evaluation schemas and metrics for commonsense reasoning tasks, particularly for open-ended and generative tasks. 
- ***Methods***{: .text-red-300}: methods for commonsense reasoning tasks; methods that integrate CSKBs and neural models; methods that use CSKBs to improve the interpretability and explainability of neural models for commonsense reasoning and more. 
- ***Analysis***{: .text-red-300}: methods to probe commonsense knowledge from NLP models; methods to understand reasoning mechanisms of existing methods; methods that identify limitations of existing methods for AI applications (including but not limited to NLP, CV and robotics) due to lack of commonsense knowledge. 


### Submission Formats
{: .no_toc}
We solicit two categories of papers:
- ***Workshop papers***{: .text-red-300}: describing new, previously unpublished research in this field. The submissions should follow [***the AKBC 2021 style guidelines***](https://github.com/akbc-conference/style-files/blob/master/akbc-latex.zip?raw=true){: target="_blank"}. and contain up to 10 pages, excluding references and appendices (which should be put after references).  Submissions will be subject to a single-blind review process (i.e. they need not be anonymized). Final versions of accepted papers will be allowed 1 additional page of content so that reviewer comments can be taken into account. 

- ***Published papers***{: .text-red-300}:  papers on topics relevant to the workshop theme, previously published at NLP or ML conferences. These papers can be submitted in their original formats. Submissions will be reviewed for fit to the workshop topics.

In both categories, accepted papers will be published on the workshop website (note that the workshop is ***non-archival***{: .text-red-300}), and will be presented at the workshop either as a talk or a poster. 

--- 
<!-- 
## Invited Talks and Panel Discussion
{:.no_toc} -->


![Speakers](images/speakers.png)

## Invited Talks

We’re excited to have the following keynote speakers at CSKB 2021:

- [***Rachel Rudinger***](https://rudinger.github.io/){: target="_blank"}, University of Maryland
- [***Sara Hooker***](https://www.sarahooker.me/){: target="_blank"}, Google Brain  
- [***Maarten Sap***](https://homes.cs.washington.edu/~msap/){: target="_blank"}, Allen Institute for AI (AI2) & CMU
- [***Xiang Ren***](http://ink-ron.usc.edu/xiangren/){: target="_blank"}, University of Southern California

<!-- Abstracts will be added here. -->

## Panel Discussion
<!-- {: .fs-8 .fw-800 .text-green-300 } -->

We will also be holding a panel discussion with the invited speakers as well as the following panelists:

- [***Mohit Bansal***](https://www.cs.unc.edu/~mbansal/){: target="_blank"}, University of North Carolina at Chapel Hill
- [***Greg Durrett***](https://www.cs.utexas.edu/~gdurrett/){: target="_blank"}, UT Austin
- [***Sameer Singh***](https://sameersingh.org/){: target="_blank"}, UC Irvine
- [***Aida Nematzadeh***](http://www.aidanematzadeh.me/){: target="_blank"}, DeepMind


---

## Accepted Papers 

TBD

---

## Contact

Please email to [***cskb-akbc21@googlegroups.com***](mailto:cskb-akbc21@googlegroups.com) if you have any questions.