---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a final Ph.D. Student at Northeastern University, Boston, advised by [Prof. Yanzhi Wang](https://web.northeastern.edu/yanzhiwang/).

**<font color=red> I’m on academic job market this year, please reach out for any opportunities! </font>**

My research area is the intersection of Software-Hardware Co-design, Efficient AI, Hardware Architecture, SuperConducting Logic:

+ Hardware and Software Co-design for DNN Architecture
+ Inference-Efficient/Energy-Efficient Artificial Intelligence Systems
+ Efficient Deep Learning on Superconducting Devices
+ Emerging Deep Learning Systems


News
------
+ September 2023, two papers get accepted at Neurips 2023.
+ To be honored, I was selected as a Rising Star in EECS 2023.
+ August 2023, one paper gets accepted at ICCAD 2023.
+ July 2023, I gave a talk on "Software-Hardware Co-Design: Towards Ultimate Efficiency in Deep Learning Acceleration" at the 4TH ROAD4NN WORKSHOP, DAC 2023, San Francisco, CA, USA.
+ July 2023, I gave a talk on "Algorithm-Software-Hardware Co-Design for AI Acceleration" at the Session - TINYML: BRING DEEP LEARNING MODELS TO TINY DEVICES, DAC 2023, San Francisco, CA, USA


Publications ([Full list](https://peiyanflying.github.io/Peggy_Peiyan.github.io/publications/))
------
+ ***<font color=red> HPCA 2023  </font>*** [HeatViT: Hardware-Efficient Adaptive Token Pruning for Vision Transformers](https://ieeexplore.ieee.org/abstract/document/10071047)
  
  **Peiyan Dong**, Mengshu Sun, Alec Lu, Yanyue Xie, Kenneth Liu, Xue Lin, Zhenman Fang, Yanzhi Wang
+ [TAAS: A Timing-Aware Analytical Strategy for AQFP-Capable Placement Automation](https://dl.acm.org/doi/abs/10.1145/3489517.3530487)
  **Peiyan Dong**, Yanyue Xie, Hongjia Li, Olivia Chen, Mengshu Sun, Nobuyuki Yoshikawa, Yanzhi Wang
+ [Rtmobile: Beyond real-time mobile acceleration of rnns for speech recognition](https://dl.acm.org/doi/10.5555/3437539.3437579)
  **Peiyan Dong**, Siyue Wang, Wei Niu, Chengming Zhang, Sheng Lin, Zhengang Li, Yifan Gong, Bin Ren, Xue Lin, Dingwen Tao
+ [FF-Medical: Fast and Fair Medical AI on the Edge through Hardware-oriented Search for Hybrid Vision Models](https://dl.acm.org/doi/10.5555/3437539.3437579)
  **Peiyan Dong**, Changdi Yang, Yi Sheng, Yanyu Li, Lei Yang, Xue Lin, Yanzhi Wan
+ [HotBEV: Hardware-oriented Transformer-based Multi-View 3D Detector for BEV Perception](https://dl.acm.org/doi/10.5555/3437539.3437579)
  **Peiyan Dong**, Zhenglun Kong, Xin Meng, Pinrui Yu, Yanyue Xie, Yifan Gong, Geng Yuan, Fei Sun, Hao Tang, Yanzhi Wang
+ [PackQViT:Faster Sub-8-bit Vision Transformers via Full and Packed Quantization on the Mobile](https://dl.acm.org/doi/10.5555/3437539.3437579)
  **Peiyan Dong**, Lei Lu, Chao Wu, Cheng Lyu, Geng Yuan, Hao Tang, Yanzhi Wang
+ [SpeedDETR: Speed-aware Transformers for End-to-end Object Detection](https://proceedings.mlr.press/v202/dong23b/dong23b.pdf)
  **Peiyan Dong**, Zhenglun Kong, Xin Meng, Peng Zhang, Hao Tang, Yanzhi Wang, Chih-Hsien Chou

Honors
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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
