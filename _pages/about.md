---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I work as an Applied Scientist at Amazon. I completed my B.Sc. (Hons) degree from the Department of Electronic and Telecommunication Engineering, University of Moratuwa and completed my PhD at the Australian National University. My research interests include theoretical machine learning and computer vision. I am also a co-founder of ConscientAI and a research fellow at the University of Adelaide.

Career Highlights
======

* Applied scientist at Amazon
* Co-Founder/Director at ConscientAI
* Former software engineer at WSO2
* Former software engineer at Neurotechnology Lab
* Former computer vision engineer at Hitech Solutions


Recent News
======

* December, 2022: *A learnable radial-basis embedding for coordinate-MLPs* accepted to **AAAI (Oral)**, 2023
* September, 2022: *On the frequency bias of coordinate-MLPs* accepted to **NeurIPS**, 2022
* July, 2022: *Beyond Periodicity: Towards a unifying framework for activations in coordnate-MLPs* accepted to **ECCV (Oral)**, 2022
* July, 2022: *Trading Positional Complexity vs Deepness in Coordinate Networks* accepted to **ECCV**, 2022
* July, 2022: *Few-Shot Class-Incremental Learning for 3D Point Cloud Objects* accepted to **ECCV**, 2022
* July, 2022: *Gaussian activated neural radiance fields for high fidelity reconstruction and pose estimation* accepted to **ECCV**, 2022
* March, 2022: *Enabling equivariance for arbitrary Lie groups* accepted to **CVPR**, 2022


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
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
