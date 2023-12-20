---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! Lovely to meet you. 🙂

I am a third-year Data Science and Economics major at the University of California, Berkeley.

At Berkeley, I am a behavioural economics researcher in the [Moore Accuracy Lab]("https://learnmoore.org/") under Professor Don Moore, where I study whether overconfidence in upward economic mobility undermines support for redistribution. Additionally, I am an Equity in Energy and Environmental Economics Research Fellow in the [UC Berkeley Opportunity Lab and Energy Institute at Haas]("https://www.olab.berkeley.edu/energyinstitute-sloan"), where I am using machine learning and Bayesian modelling to determine optimal locations for future air pollution monitors with a goal of minimizing public health impacts from pollution. To learn more about my research, visit the [research](https://a-leenwu.github.io/research/) tab.

Beyond research, I am a teaching assistant for Data 8, UC Berkeley's foundational data science course. Previously, I was a course tutor for Statistics 20, an equivalent introductory statistics and probability class that teaches R instead of Python. Read more about my teaching [here](https://a-leenwu.github.io/teaching/).

Coming from a social sciences and humanities background, I also love to write and was a News Reporter for The Daily Californian. You can read my news articles [here]("https://dailycal.org/author/aileenwu").

I am passionate about the intersection of technology, social justice, and environmental justice—from data and AI ethics to creating tools that make the world a better place.

[ignore this stuff, will delete later 🚧]

Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
