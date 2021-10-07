---
layout: default
title: CSKB@AKBC21
nav_order: 1
description: "Workshop on Common-Sense Knowledge Bases at AKBC 2021"
permalink: /
last_modified_date: July 5th 2021
toc_list: true
---

<style>
  @font-face{font-family:agency fb bold;font-style:normal;font-weight:700;src:local('Agency FB Bold'),local('AgencyFB-Bold'),url(http://allfont.net/cache/fonts/agency-fb-bold_cee84847c4ab16cf2b0952d063712724.woff) format('woff'),url(http://allfont.net/cache/fonts/agency-fb-bold_cee84847c4ab16cf2b0952d063712724.ttf) format('truetype')}

  .paper_title{
    font-size: 1em;
    color: #800080;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  }

  table{
    text-align: center;
  }

  .note{
    margin-top: 15pt;
  }
</style>
 
 
# The First Workshop on Commonsense Reasoning and Knowledge Bases (CSKB) at AKBC 2021
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


- ***Oct 1, 2021*** The program and the accepted papers are updated. 

- ***Spet 14, 2021*** Online registration of AKBC 2021 is now open! Please register [here](https://na.eventscloud.com/akbc2021){: target="_blank"}.

- ***Aug 5, 2021.*** The submission deadline is extended to ***August 20, 2021***{: .text-blue-300}.

- ***July 6, 2021.*** The first version of our [call for papers](#call-for-papers) is out.


### Registration  
{: .no_toc}
Please register AKBC 2021 via [**this link**](https://na.eventscloud.com/akbc2021){: target="_blank"} and find CSKB workshop in **Day 2 Workshop options**. There is no separate fee for workshop registration, the conference registration (*$50 for non-students, $30 for students*) will include all workshops. 

### Important Dates
{: .no_toc}

- All paper submissions due – ~~August 5~~ ***August 20, 2021***{: .text-red-300}
- Notification of acceptance – ~~Sept 10~~ ***Sep 15, 2021***{: .text-red-300}
- Camera-ready papers due – ~~September 30~~ ***Oct 5, 2021***{: .text-red-300}
- Workshop – ~~Oct 5~~ ***Oct 8, 2021***{: .text-red-300}

***All deadlines are 11.59 pm UTC -12h ("anywhere on Earth").***{: .text-blue-300}


--- 

## Program 

The workshop will be held over Zoom. Get the Zoom link from the [***AKBC workshops page***](https://akbc.apps.allenai.org/workshops.html#day2){: target="_blank"}.

| Start (PST) | End (PST) | Session |
|-------|-------| ---------------|
| 08:00 |	08:05 |	Opening remarks |
| 08:05 |	08:40 |	Invited Speaker # 1 - ***Sara Hooker*** |
| 08:40 |	09:00 |	2-minute lightning talks <br> (Paper ids: [2, 3, 4, 6, 7, 8, 14, 15, 17]) |
| 09:00 |	09:35 |	Invited Speaker # 2 - ***Maarten Sap*** |
| 09:35 |	10:05 |	Break |
| 10:05 |	10:40 |	Invited Speaker # 3 - ***Rachel Rudinger*** |
| 10:40 |	11:00 |	2-minute lightning talks  <br>  (Paper ids: [1, 5, 9, 10, 11, 12, 13, 16, 18])|
| 11:00 |	11:55 |	Panel Discussion |
| 11:55 |	12:20 |	Break |
| 12:20 |	12:55 |	Invited Speaker # 4 - ***Xiang Ren*** |
| 12:55 |	13:00 | Closing Statements |

---

--- 
<!-- 
## Invited Talks and Panel Discussion
{:.no_toc} -->

## Talks and Panel Discussion
![Speakers](images/speakers.png)

### Speakers
{: .no_toc}

We’re excited to have the following keynote speakers at CSKB 2021:

- [***Rachel Rudinger***](https://rudinger.github.io/){: target="_blank"}, University of Maryland
- [***Sara Hooker***](https://www.sarahooker.me/){: target="_blank"}, Google Brain  
- [***Maarten Sap***](https://homes.cs.washington.edu/~msap/){: target="_blank"}, Allen Institute for AI (AI2) & CMU
- [***Xiang Ren***](http://ink-ron.usc.edu/xiangren/){: target="_blank"}, University of Southern California

<!-- Abstracts will be added here. -->

### Panel Discussion
{: .no_toc}
<!-- {: .fs-8 .fw-800 .text-green-300 } -->

We will also be holding a panel discussion with the invited speakers as well as the following panelists:

- [***Mohit Bansal***](https://www.cs.unc.edu/~mbansal/){: target="_blank"}, University of North Carolina at Chapel Hill
- [***Greg Durrett***](https://www.cs.utexas.edu/~gdurrett/){: target="_blank"}, UT Austin
- [***Sameer Singh***](https://sameersingh.org/){: target="_blank"}, UC Irvine
- [***Aida Nematzadeh***](http://www.aidanematzadeh.me/){: target="_blank"}, DeepMind

---


---

## Organizers

<!-- - [***Vered Shwartz***](https://vered1986.github.io/){: target="_blank"}, Allen Institute for AI (AI2) and the University of Washington. 
- [***Antoine Bosselut***](https://atcbosselut.github.io/){: target="_blank"}, Allen Institute for AI (AI2) and Stanford University.
- [***Xiang Lorraine Li***](https://people.cs.umass.edu/~xiangl/){: target="_blank"}, UMass Amherst.
- [***Bill Yuchen Lin***](https://yuchenlin.xyz/){: target="_blank"}, University of Southern California. -->


![Organizers](images/ognzers.png)
 
<details markdown="block">
  <summary>
    <a href="https://vered1986.github.io/" target="_blank"><strong><em>Vered Shwartz</em></strong></a>, University of British Columbia.
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


## Accepted Papers 

***Please note that all papers are non-archival.***  See all information on [OpenReview](https://openreview.net/group?id=AKBC.ws/2021/Workshop/CSKB#all-submissions){: target="_blank"}.

### Regular Workshop Papers
{: .no_toc}


<ul>
<li class="note " data-id="9_oCNR6R9l2" data-number="7">
        <span class=".no_toc">   [7]       <a class="paper_title" href="https://openreview.net/forum?id=9_oCNR6R9l2">Artefact Retrieval: Overview of NLP Models with Knowledge Base Access</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Vil%C3%A9m_Zouhar1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Vilém_Zouhar1">Vilém Zouhar</a>, <a href="https://openreview.net/profile?id=~Marius_Mosbach1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Marius_Mosbach1">Marius Mosbach</a>, <a href="https://openreview.net/profile?id=~Debanjali_Biswas1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Debanjali_Biswas1">Debanjali Biswas</a>, <a href="https://openreview.net/profile?id=~Dietrich_Klakow1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Dietrich_Klakow1">Dietrich Klakow</a>
        </div>
    </li>
<li class="note " data-id="MvFv92fUFof" data-number="3">
        <span class=".no_toc">   [3]       <a class="paper_title" href="https://openreview.net/forum?id=MvFv92fUFof">Retrieve, Caption, Generate: Visual Grounding for Enhancing Commonsense in Text Generation Models</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Steven_Y._Feng1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Steven_Y._Feng1">Steven Y. Feng</a>, <a href="https://openreview.net/profile?id=~Kevin_Lu3" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Kevin_Lu3">Kevin Lu</a>, <a href="https://openreview.net/profile?id=~Zhuofu_Tao1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Zhuofu_Tao1">Zhuofu Tao</a>, <a href="https://openreview.net/profile?id=~Malihe_Alikhani2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Malihe_Alikhani2">Malihe Alikhani</a>, <a href="https://openreview.net/profile?email=teruko%40andrew.cmu.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="teruko@andrew.cmu.edu">Teruko Mitamura</a>, <a href="https://openreview.net/profile?id=~Eduard_H_Hovy1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Eduard_H_Hovy1">Eduard H Hovy</a>, <a href="https://openreview.net/profile?id=~Varun_Gangal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Varun_Gangal1">Varun Gangal</a>
        </div>
    </li>
 <li class="note " data-id="WnIpeFJgSZy" data-number="18">
        <span class=".no_toc">    [18]      <a class="paper_title" href="https://openreview.net/forum?id=WnIpeFJgSZy">Story Generation with Commonsense Knowledge Graphs and Axioms</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Filip_Ilievski1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Filip_Ilievski1">Filip Ilievski</a>, <a href="https://openreview.net/profile?id=~Jay_Pujara1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Jay_Pujara1">Jay Pujara</a>, <a href="https://openreview.net/profile?email=hanzhizh%40usc.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="hanzhizh@usc.edu">Hanzhi Zhang</a>
        </div>
    </li>
<li class="note " data-id="fn5K7VfI3MV" data-number="17">
        <span class=".no_toc">    [17]      <a class="paper_title" href="https://openreview.net/forum?id=fn5K7VfI3MV">No Need to Know Everything! Efficiently Augmenting Language Models With External Knowledge</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Jivat_Neet_Kaur1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Jivat_Neet_Kaur1">Jivat Neet Kaur</a>, <a href="https://openreview.net/profile?id=~Sumit_Bhatia1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Sumit_Bhatia1">Sumit Bhatia</a>, <a href="https://openreview.net/profile?id=~Milan_Aggarwal2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Milan_Aggarwal2">Milan Aggarwal</a>, <a href="https://openreview.net/profile?id=~Rachit_Bansal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Rachit_Bansal1">Rachit Bansal</a>, <a href="https://openreview.net/profile?id=~Balaji_Krishnamurthy1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Balaji_Krishnamurthy1">Balaji Krishnamurthy</a>
        </div>
    </li>
<li class="note " data-id="BigczdxQlGm" data-number="15">
        <span class=".no_toc">     [15]     <a class="paper_title" href="https://openreview.net/forum?id=BigczdxQlGm">COPA-SSE: Semi-Structured Explanations for Commonsense Reasoning</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Ana_Brassard1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Ana_Brassard1">Ana Brassard</a>, <a href="https://openreview.net/profile?id=~Benjamin_Heinzerling1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Benjamin_Heinzerling1">Benjamin Heinzerling</a>, <a href="https://openreview.net/profile?email=pkavumba%40ecei.tohoku.ac.jp" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="pkavumba@ecei.tohoku.ac.jp">Pride Kavumba</a>, <a href="https://openreview.net/profile?id=~Kentaro_Inui1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Kentaro_Inui1">Kentaro Inui</a>
        </div>
    </li>
    <li class="note " data-id="1yieqYLUIXj" data-number="14">
        <span class=".no_toc">     [14]     <a class="paper_title" href="https://openreview.net/forum?id=1yieqYLUIXj">CoSe-Co: Sentence Conditioned Generative CommonSense Contextualizer for Language Models</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Rachit_Bansal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Rachit_Bansal1">Rachit Bansal</a>, <a href="https://openreview.net/profile?id=~Milan_Aggarwal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Milan_Aggarwal1">Milan Aggarwal</a>, <a href="https://openreview.net/profile?id=~Sumit_Bhatia1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Sumit_Bhatia1">Sumit Bhatia</a>, <a href="https://openreview.net/profile?id=~Jivat_Neet_Kaur1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Jivat_Neet_Kaur1">Jivat Neet Kaur</a>, <a href="https://openreview.net/profile?id=~Balaji_Krishnamurthy1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Balaji_Krishnamurthy1">Balaji Krishnamurthy</a>
        </div>
    </li>
</ul>



### Previously Published Papers (Extended Abstracts)
{: .no_toc}


<ul>    
    <li class="note " data-id="8oKPQD2KZnA" data-number="1">
        <span class=".no_toc">    [1]      <a class="paper_title" href="https://openreview.net/forum?id=8oKPQD2KZnA">TellMeWhy: A Dataset for Answering Why-Questions in Narratives</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Yash_Kumar_Lal2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yash_Kumar_Lal2">Yash Kumar Lal</a>, <a href="https://openreview.net/profile?id=~Nathanael_Chambers1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Nathanael_Chambers1">Nathanael Chambers</a>, <a href="https://openreview.net/profile?id=~Ray_Mooney1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Ray_Mooney1">Ray Mooney</a>, <a href="https://openreview.net/profile?id=~Niranjan_Balasubramanian2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Niranjan_Balasubramanian2">Niranjan Balasubramanian</a>
        </div>
    </li>  
     <li class="note " data-id="vtZzRb1471-" data-number="2">
        <span class=".no_toc">    [2]   <a class="paper_title" href="https://openreview.net/forum?id=vtZzRb1471-">
              Perhaps PTLMs should go to School – A Task to Assess Open Book and Closed Book QA </a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Manuel_Rafael_Ciosici1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Manuel_Rafael_Ciosici1">Manuel Rafael Ciosici</a>, <a href="https://openreview.net/profile?email=cecil%40isi.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="cecil@isi.edu">Joe Cecil</a>, <a href="https://openreview.net/profile?id=~Dong-Ho_Lee1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Dong-Ho_Lee1">Dong-Ho Lee</a>, <a href="https://openreview.net/profile?id=~Alex_Hedges1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Alex_Hedges1">Alex Hedges</a>, <a href="https://openreview.net/profile?email=mrf%40isi.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="mrf@isi.edu">Marjorie Freedman</a>, <a href="https://openreview.net/profile?email=weisched%40isi.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="weisched@isi.edu">Ralph Weischedel</a>
        </div>                
    </li>
    <li class="note " data-id="jsuynAVoMzn" data-number="5">
        <span class=".no_toc">      [5]    <a class="paper_title" href="https://openreview.net/forum?id=jsuynAVoMzn">Modeling Worlds in Text</a></span>        
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Prithviraj_Ammanabrolu1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Prithviraj_Ammanabrolu1">Prithviraj Ammanabrolu</a>, <a href="https://openreview.net/profile?id=~Mark_Riedl1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Mark_Riedl1">Mark Riedl</a>
        </div>
    </li> 
    <li class="note " data-id="iAIP15cNLIP" data-number="16">
        <span class=".no_toc">       [16]   <a class="paper_title" href="https://openreview.net/forum?id=iAIP15cNLIP">Like hiking? You probably enjoy nature: Persona-grounded Dialog with Commonsense Expansions</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Bodhisattwa_Prasad_Majumder1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Bodhisattwa_Prasad_Majumder1">Bodhisattwa Prasad Majumder</a>, <a href="https://openreview.net/profile?id=~Harsh_Jhamtani1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Harsh_Jhamtani1">Harsh Jhamtani</a>, <a href="https://openreview.net/profile?id=~Taylor_Berg-Kirkpatrick1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Taylor_Berg-Kirkpatrick1">Taylor Berg-Kirkpatrick</a>, <a href="https://openreview.net/profile?id=~Julian_McAuley1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Julian_McAuley1">Julian McAuley</a>
        </div>
    </li> 
    <li class="note " data-id="Xh1D4dNuEp5" data-number="13">
        <span class=".no_toc">       [13]   <a class="paper_title" href="https://openreview.net/forum?id=Xh1D4dNuEp5">Do Language Models Perform Generalizable Commonsense Inference?</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~PeiFeng_Wang1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~PeiFeng_Wang1">PeiFeng Wang</a>, <a href="https://openreview.net/profile?id=~Filip_Ilievski1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Filip_Ilievski1">Filip Ilievski</a>, <a href="https://openreview.net/profile?id=~Muhao_Chen1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Muhao_Chen1">Muhao Chen</a>, <a href="https://openreview.net/profile?id=~Xiang_Ren1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Xiang_Ren1">Xiang Ren</a>
        </div>
    </li> 
    <li class="note " data-id="FH_yS0ldm-E" data-number="12">
        <span class=".no_toc">       [12]   <a class="paper_title" href="https://openreview.net/forum?id=FH_yS0ldm-E">Retrieval Enhanced Model for Commonsense Generation</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Han_Wang9" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Han_Wang9">Han Wang</a>, <a href="https://openreview.net/profile?id=~Yang_Liu50" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yang_Liu50">Yang Liu</a>, <a href="https://openreview.net/profile?id=~Chenguang_Zhu1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Chenguang_Zhu1">Chenguang Zhu</a>, <a href="https://openreview.net/profile?id=~Linjun_Shou1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Linjun_Shou1">Linjun Shou</a>, <a href="https://openreview.net/profile?id=~MING_GONG2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~MING_GONG2">MING GONG</a>, <a href="https://openreview.net/profile?id=~Yichong_Xu1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yichong_Xu1">Yichong Xu</a>, <a href="https://openreview.net/profile?id=~Michael_Zeng1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Michael_Zeng1">Michael Zeng</a>
        </div>
        </li>
    <li class="note " data-id="KFcjxSNdMBq" data-number="11">
        <span class=".no_toc">    [11]      <a class="paper_title" href="https://openreview.net/forum?id=KFcjxSNdMBq">Prompting Contrastive Explanations for Commonsense Reasoning Tasks</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Bhargavi_Paranjape1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Bhargavi_Paranjape1">Bhargavi Paranjape</a>, <a href="https://openreview.net/profile?id=~Julian_Michael1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Julian_Michael1">Julian Michael</a>, <a href="https://openreview.net/profile?id=~Marjan_Ghazvininejad1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Marjan_Ghazvininejad1">Marjan Ghazvininejad</a>, <a href="https://openreview.net/profile?id=~Hannaneh_Hajishirzi1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Hannaneh_Hajishirzi1">Hannaneh Hajishirzi</a>, <a href="https://openreview.net/profile?id=~Luke_Zettlemoyer1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Luke_Zettlemoyer1">Luke Zettlemoyer</a>
        </div>
    </li>
    <li class="note " data-id="pFRIXhSiJpq" data-number="10">
        <span class=".no_toc">      [10]    <a class="paper_title" href="https://openreview.net/forum?id=pFRIXhSiJpq">COM2SENSE: A Commonsense Reasoning Benchmark with Complementary Sentences</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Shikhar_Singh1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Shikhar_Singh1">Shikhar Singh</a>, <a href="https://openreview.net/profile?email=nuanwen%40usc.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="nuanwen@usc.edu">Nuan Wen</a>, <a href="https://openreview.net/profile?email=houyu%40usc.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="houyu@usc.edu">Yu Hou</a>, <a href="https://openreview.net/profile?email=palipoor976%40gmail.com" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="palipoor976@gmail.com">Pegah Alipoormolabashi</a>, <a href="https://openreview.net/profile?email=telinwu%40cs.ucla.edu" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="telinwu@cs.ucla.edu">Te-Lin Wu</a>, <a href="https://openreview.net/profile?id=~Xuezhe_Ma1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Xuezhe_Ma1">Xuezhe Ma</a>, <a href="https://openreview.net/profile?id=~Nanyun_Peng1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Nanyun_Peng1">Nanyun Peng</a>
        </div> 
    </li>
    <li class="note " data-id="jnIiy6AGUmo" data-number="9">
        <span class=".no_toc">    [9]      <a class="paper_title" href="https://openreview.net/forum?id=jnIiy6AGUmo">Fusing Context Into Knowledge Graph for Commonsense Question Answering</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Yichong_Xu1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yichong_Xu1">Yichong Xu</a>, <a href="https://openreview.net/profile?id=~Chenguang_Zhu1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Chenguang_Zhu1">Chenguang Zhu</a>, <a href="https://openreview.net/profile?id=~Ruochen_Xu2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Ruochen_Xu2">Ruochen Xu</a>, <a href="https://openreview.net/profile?id=~Yang_Liu50" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yang_Liu50">Yang Liu</a>, <a href="https://openreview.net/profile?id=~Michael_Zeng1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Michael_Zeng1">Michael Zeng</a>, <a href="https://openreview.net/profile?email=xdh%40microsoft.com" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="xdh@microsoft.com">Xuedong Huang</a>
        </div> 
    </li>
    <li class="note " data-id="8REVPGZVsP" data-number="8">
        <span class=".no_toc">    [8]      <a class="paper_title" href="https://openreview.net/forum?id=8REVPGZVsP">Explanations for CommonsenseQA: New Dataset and Models</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Shourya_Aggarwal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Shourya_Aggarwal1">Shourya Aggarwal</a>, <a href="https://openreview.net/profile?id=~Divyanshu_Mandowara1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Divyanshu_Mandowara1">Divyanshu Mandowara</a>, <a href="https://openreview.net/profile?email=vishwa.grawal%40gmail.com" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="vishwa.grawal@gmail.com">Vishwajeet Agrawal</a>, <a href="https://openreview.net/profile?id=~Dinesh_Khandelwal2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Dinesh_Khandelwal2">Dinesh Khandelwal</a>, <a href="https://openreview.net/profile?id=~Parag_Singla1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Parag_Singla1">Parag Singla</a>, <a href="https://openreview.net/profile?id=~Dinesh_Garg1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Dinesh_Garg1">Dinesh Garg</a>
        </div>
    </li>
    <li class="note " data-id="T9FwSfwA2Li" data-number="6">
        <span class=".no_toc">   [6]       <a class="paper_title" href="https://openreview.net/forum?id=T9FwSfwA2Li">On Commonsense Cues in BERT for Solving Commonsense Tasks</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Leyang_Cui1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Leyang_Cui1">Leyang Cui</a>, <a href="https://openreview.net/profile?id=~Sijie_Cheng1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Sijie_Cheng1">Sijie Cheng</a>, <a href="https://openreview.net/profile?email=wu.yu%40microsoft.com" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="wu.yu@microsoft.com">Yu Wu</a>, <a href="https://openreview.net/profile?email=yue.zhang%40wias.org.cn" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="yue.zhang@wias.org.cn">Yue Zhang</a>
        </div>
    </li>
    <li class="note " data-id="wOhNz5kDWZ" data-number="4">
        <span class=".no_toc">     [4]     <a class="paper_title" href="https://openreview.net/forum?id=wOhNz5kDWZ">Could you give me a hint? Generating inference graphs for defeasible reasoning</a></span>
        <div class="note-authors">
          <a href="https://openreview.net/profile?id=~Aman_Madaan1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Aman_Madaan1">Aman Madaan</a>, <a href="https://openreview.net/profile?id=~Dheeraj_Rajagopal1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Dheeraj_Rajagopal1">Dheeraj Rajagopal</a>, <a href="https://openreview.net/profile?id=~Niket_Tandon2" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Niket_Tandon2">Niket Tandon</a>, <a href="https://openreview.net/profile?id=~Yiming_Yang1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Yiming_Yang1">Yiming Yang</a>, <a href="https://openreview.net/profile?id=~Eduard_H_Hovy1" class="profile-link" data-toggle="tooltip" data-placement="top" title="" data-original-title="~Eduard_H_Hovy1">Eduard H Hovy</a>
        </div>
    </li>
</ul>




---

## Call for papers 


### Topics of Interest
{: .no_toc}

The topics of interest include, but are not limited to: 

- ***Resources***{: .text-red-300}: acquiring commonsense knowledge (from text corpora, images, videos, pre-trained neural models, etc.); constructing and completing (semi-)structured CSKBs; consolidating CSKBs under unified schemas. 
- ***Benchmarks***{: .text-red-300}: designing challenging tasks and building datasets to evaluate models' commonsense knowledge and reasoning abilities; designing new evaluation schemas and metrics for commonsense reasoning tasks, particularly for open-ended and generative tasks. 
- ***Methods***{: .text-red-300}: methods for commonsense reasoning tasks; methods that integrate CSKBs and neural models; methods that use CSKBs to improve the interpretability and explainability of neural models for commonsense reasoning and more. 
- ***Analysis***{: .text-red-300}: methods to probe commonsense knowledge from NLP models; methods to understand reasoning mechanisms of existing methods; methods that identify limitations of existing methods for AI applications (including but not limited to NLP, CV and robotics) due to lack of commonsense knowledge. 


### Submission Guide
{: .no_toc}
We solicit two categories of papers:
- ***Workshop papers***{: .text-red-300}: describing new, previously unpublished research in this field. The submissions should follow [***the AKBC 2021 style guidelines***](https://github.com/akbc-conference/style-files/blob/master/akbc-latex.zip?raw=true){: target="_blank"}. and contain up to 10 pages, excluding references and appendices (which should be put after references).  Submissions will be subject to a single-blind review process (i.e. they need not be anonymized). Final versions of accepted papers will be allowed 1 additional page of content so that reviewer comments can be taken into account. 

- ***Published papers***{: .text-red-300}:  papers on topics relevant to the workshop theme, previously published at NLP or ML conferences. These papers can be submitted in their original formats. Submissions will be reviewed for fit to the workshop topics.

In both categories, accepted papers will be published on the workshop website (note that the workshop is ***non-archival***{: .text-red-300}), and will be presented at the workshop either as a talk or a poster. 

***Submission site:***{: .text-blue-100} [https://openreview.net/group?id=AKBC.ws/2021/Workshop/CSKB](https://openreview.net/group?id=AKBC.ws/2021/Workshop/CSKB){: target="_blank"}


---

## Program Committee 
{: .no_toc}

- Faeze Brahman, University of California, Santa Cruz
- Jack Hessel, 	Allen Institute for Artificial Intelligence 
- Liwei Jiang, University of Washington
- Niket Tandon, Allen Institute for Artificial Intelligence
- Rajarshi Das, UMass
- Tuhin Chakrabarty, 	Columbia University  

---

## Contact

Please email to [***cskb-akbc21@googlegroups.com***](mailto:cskb-akbc21@googlegroups.com) if you have any questions.
