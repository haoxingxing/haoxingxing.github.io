---
permalink: /
title: "西北大学郝星星--个人简介"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

====
-联系方式：xingxing.hao@nwu.edu.cn  
-中共党员，西北大学信息科学与技术学院讲师，硕士生导师，CCF中国计算机学会会员、中国运筹学会会员。分别于2014年、2019年获得西安电子科技大学智能科学与技术专业学士学位和西安电子科技大学电路与系统专业博士学位，2018年于英国诺丁汉大学访学。主要研究领域为人工智能、智能信息处理、计算机视觉。发表论文30余篇，SCI检索论文20余篇。主持国家自然科学基金、陕西省教育厅专项科研计划项目等国家级、省部级科研课题各1项，参与文旅部国家重点研发计划、国家自然科学基金面上项目、陕西省重点研发计划等国家级、省部级项目近10项。指导学生获批多项大学生创新创业训练计划项目“国家级项目立项”、“省级项目立项”，以及指导学生在中国研究生电子设计、美国大学生数学建模、全国大学生光电设计等竞赛中获多项国家级、省级奖励。

教育经历
======
-2014-2019 西安电子科技大学｜人工智能学院｜电路与系统｜导师：[刘静](https://web.xidian.edu.cn/liujing/)教授   
-2018-2019 英国诺丁汉大学｜计算机学院｜访问学者｜导师：[屈嵘](https://people.cs.nott.ac.uk/pszrq/)教授  
-2010-2014 西安电子科技大学｜电子工程学院｜智能科学与技术

教授课程
======
-《程序设计基础》  
-《程序设计基础实验》  
-《程序设计综合实践》  
-《Web数据挖掘》  
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
