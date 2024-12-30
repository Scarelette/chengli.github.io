---
permalink: /
title: "Cheng Li"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Summary
======
My name is Cheng Li, and I am a Chinese girl with a deep fascination for advanced technologies that enhance our daily lives, such as artificial intelligence (AI) and computational linguistics. Over the past two years, I have conducted research exploring the cognitive mechanisms of LLMs (e.g., _EmotionPrompt_ and _NegativePrompt_), multicultural understanding of LLMs (_CultureLLM_ and _CulturePark_), and AI for healthcare (_MentalArena_). I was a research intern at UIUC advised by Prof. Heng Ji. And I have a long internship at Microsoft Research Asia advised by Prof. Xing Xie and Dr. Jindong Wang. Looking ahead, I aspire to contribute to more impactful and innovative work on large models.

Research Interests
======
- **AI for Social Science**: Unveiling Emotions in Generative AI (ICML 2024), NegativePrompt (IJCAI 2024), EmotionPrompt (LLM@IJCAI'23)
- **Cultural Problems in Large Models**: CultureLLM (NeurIPS 2024), CulturePark (NeurIPS 2024)
- **AI for Healthcare**: MentalArena (Submitted to ICLR 2025)

Publication
======
- [**ICML 2024**] The good, the bad, and why: Unveiling emotions in generative ai. **<u>Cheng Li<\u>**, Jindong Wang, Yixuan Zhang, Kaijie Zhu, Xinyi Wang, Wenxin Hou, Jianxun Lian, Fang Luo, Qiang Yang, Xing Xie. [pdf](https://arxiv.org/pdf/2312.11111) Implemented by [LlamaIndex](https://docs.llamaindex.ai/en/latest/examples/prompts/emotion_prompt.html) Media coverage: [1](https://techxplore.com/news/2023-08-exploring-effects-emotional-stimuli-large.html), [2](https://flowgpt.com/blog/emoGPT), [3](https://mp.weixin.qq.com/s/z-lg-yDibKoT_gO97HSK5Q), [4](https://www.godofprompt.ai/blog/getting-emotional-with-large-language-models-llms-can-increase-performance-by-115-case-study). [5](https://stackdiary.com/emotionprompts-ai-prompt-study/), [6](https://says.com/my/tech/chatgpt-emotional-intelligence), [7](https://www.prompthub.us/blog/getting-emotional-with-llms), [8](https://www.tradingview.com/news/benzinga:6720a9647094b:0-the-power-of-emotion-how-emotional-manipulation-elevates-chatgpt-s-performance/), [9](https://mp.weixin.qq.com/s?__biz=MzIwNzc2NTk0NQ%3D%3D&mid=2247565531&idx=2&sn=3ed8cc9e3b5be81cde8f0e0f99865852&ref=openi.cn). [10](https://webappia.com/investigating-the-impact-of-emotional-stimuli-on-language-models-emotionalai/?feed_id=13302&_unique_id=64cfac8201058) Reported by [**Forbes**](https://www.forbes.com/sites/lanceeliot/2023/11/11/the-answer-to-why-emotionally-worded-prompts-can-goose-generative-ai-into-better-answers-and-how-to-spur-a-decidedly-positive-rise-out-of-ai/?sh=5383b56e37e5) 

Experience
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
