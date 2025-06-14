---
permalink: /
title: "Siyuan Chen (陈思元)"
excerpt: "Siyuan Chen (陈思元)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a second year Ph.D. student at computer science department at Carnegie Mellon University, happily advised by [Phil Gibbons](https://www.cs.cmu.edu/~gibbons/) and [Heather Miller](https://heather.miller.am/), and I am closely working with [Ben Titzer](https://s3d.cmu.edu/people/core-faculty/titzer-ben.html). I am a member of [PDL](https://www.pdl.cmu.edu/index.shtml) and [Catalyst](https://catalyst.cs.cmu.edu/) at CMU. I finished my undergraduate at Turning Class of Peking University, where I was fortunately advised by [Yun (Eric) Liang](https://ericlyun.github.io/).

My research interests lie in system for machine learning, especially providing efficient and secure solutions for post-trained systems. For instance, I worked on LLM fine-tuning on commodity hardware through compressed offloading ([LSP-Offload, AAAI'25](https://gulang2019.github.io/files/LSP_Offload.pdf)), SLO-customized LLM serving ([SLOs-Serve, Preprint](https://arxiv.org/abs/2504.08784)), and defense against prompt injection attck in tool based agentic systems ([RTBAS, Preprint](https://arxiv.org/abs/2502.08966)).
 
Before PhD, I am engaged in machine learning compiler and runtime optimizations. I worked on optimizing the batching of dynamic neural networks ([ED-Batch, ICML23'](http://proceedings.mlr.press/v202/chen23g/chen23g.pdf)), performance modeling of data movement for tensor programs ([Chimera, HPCA'23](https://ieeexplore.ieee.org/abstract/document/10071018)), mapping mechanism from DNN to SoC ([COMB, DAC'23](https://ieeexplore.ieee.org/abstract/document/10247951?casa_token=fLfp6Z8nwmwAAAAA:-nK4CrF2-17mS-cAtI65oKTbAL3EGTMdjG2IRkgF5HkjZpoluFRQCTmQAiNTzkSSjfAvptWFXQ)), and analytical-based simulator for fused program on general hardware ([TileFlow, MICRO'23](https://gulang2019.github.io/files/tileflow-micro23.pdf)).

<h2>News</h2>

- <b>May 2025.</b> I am in SystemResearch@Google(SRG) this summer working on RL systems, hosted by Samira Khan.  

- <b>May 2025.</b> I am honored to be selected as the [ML commons ML and System Rising Stars](https://mlcommons.org/about-us/programs/#:~:text=Rising%20Stars,-The%20MLCommons%20ML%20and%20Systems), great thanks to the organizer and my advisors!

- <b>Apr. 2025.</b> A new paper [RTBAS](https://arxiv.org/abs/2502.08966) on Arxiv, where we develop a novel approach to reduce user fatigue in tool-based agentic system. 

- <b>Mar. 2025.</b> A new paper [SLOs-Serve](https://arxiv.org/abs/2504.08784) on Arxiv, where we develop a novel scheduling algorithm to support customized service level objectives in LLM Serving.

- <b>June 2024.</b> I begin the internship as student researcher in SystemResearch@Google (SRG) working on LLM serving, hosted by Samira Khan.  

- <b>Sept. 2023.</b> I am starting CS PhD at Carnegie Mellon University, co-advised by [Phil Gibbons](https://www.cs.cmu.edu/~gibbons/) and [Heather Miller](https://heather.miller.am/). Hope for a stimulating and fruitful journey at Pittsburgh! 
- Aug. 2023 [TileFlow](https://github.com/gulang2019/TileFlow) is publicly available! 
- Apr. 2023 [ED-Batch](http://proceedings.mlr.press/v202/chen23g/chen23g.pdf) is accepted to ICML23', thanks for the mentor and professors!

<h2>Publications</h2> (*Equal Contribution)

- <b>Practical Offloading for Fine-Tuning LLM on Commodity GPU
via Learned Sparse Projectors</b> <u>Siyuan Chen</u>, Zhuofeng Wang, Zelong Guan, Yudong Liu, Phillip B. Gibbons. AAAI 25. [Full Version](https://arxiv.org/html/2406.10181v1), [Code](https://github.com/gulang2019/LSP-Offload).

- <b>TileFlow: A Framework for Modeling Fusion Dataflow via Tree-based Analysis.</b> Size Zheng, <u>Siyuan Chen</u>, Siyuan Gao, Liancheng Jia, Guangyu Sun, Runsheng Wang, Yun Liang. MICRO 2023. [PDF](https://gulang2019.github.io/files/tileflow-micro23.pdf)

- <b>ED-Batch: Efficient Automatic Batching of Dynamic Deep Neural Networks via Finite State Machine.</b> <u>Siyuan Chen</u>, Pratik Fegade, Tianqi Chen, Phillip B. Gibbons, Todd C. Mowry. ICML 23'. [PDF](http://proceedings.mlr.press/v202/chen23g/chen23g.pdf) [Code](https://github.com/gulang2019/ED-Batch) [Poster](https://icml.cc/media/PosterPDFs/ICML%202023/23611.png?t=1687519227.3393173) [Video](https://icml.cc/virtual/2023/poster/23611).

- <b>Memory and Computation Coordinated Mapping of DNNs onto Complex Heterogeneous SoC.</b> Size Zheng, <u>Siyuan Chen</u>, Yun Liang. The 60th Design Automation Conference (DAC), July 2023. [PDF](https://ieeexplore.ieee.org/abstract/document/10247951?casa_token=fLfp6Z8nwmwAAAAA:-nK4CrF2-17mS-cAtI65oKTbAL3EGTMdjG2IRkgF5HkjZpoluFRQCTmQAiNTzkSSjfAvptWFXQ)

- <b>Chimera: An Analytical Optimizing Framework for Effective Compute-intensive Operators Fusion.</b> Size Zheng*, <u>Siyuan Chen*</u>, Pedi Song, Renze Chen, Xiuhong Li, Shengen Yan, Dahua Lin, Jingwen Leng, Yun Liang. 29th international symposium on High Performance Computer Architecture (HPCA), February 2023. [PDF](https://ieeexplore.ieee.org/abstract/document/10071018).

<h2> Preprint </h2>

- <b>SLOs-Serve: Optimized Serving of Multi-SLO LLMs. </b> <u>Siyuan Chen</u>, Zhipeng Jia, Samira Khan, Arvind Krishnamurthy, and Phillip B. Gibbons. [Arxiv Preprint](https://arxiv.org/abs/2504.08784)

- <b>RTBAS: Defending LLM Agents Against Prompt Injection and Privacy Leakage.</b> Peter Yong Zhong*, <u>Siyuan Chen*</u>, Ruiqi Wang, McKenna McCall, Ben L. Titzer, Heather Miller, Phillip B. Gibbons. [Arxiv Preprint](https://arxiv.org/abs/2502.08966)

<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
6. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
