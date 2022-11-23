# kaggle
Repository to share the pipelines created for datasets published on Kaggle from 2022

## Introduction

I release dataset on [my profile on Kaggle](https://kaggle.com/robertolofaro), but generally each dataset is created to support a publication or some webapp that is then released via [my portfolio website](https://robertolofaro.com).

My approach is first to explore potential open data sources that could deliver information useful for my purposes, then decice to either reuse existing ones or assemble new ones (if needed, by complementing with third-party data or data that I generate from my own or a mix of both).

Therefore, usually what is needed for my purposes is just a collection of Jupyter Notebooks.

In some cases, anyway, from October 2022 started updating ["one-off" datasets released in 2019, and new datasets that I shared online](https://robertolofaro.com/datasets).

Whenever I generate eventually a webapp, what initially was a set of Jupyter Notebooks (or R scripts) turns into a pipeline of steps.

My approach derives from 1980s experience on mainframe releases and scheduling, hence:
1. while obviously a Jupyter Notebook is generally sequential, and a set is a step at a time, each step delivers a "steady state"
2. hence, each step exports (to CSV) or dumps (to JSON) data
3. while the prototype goes sequentially, a pipeline could resume from the previous "steady state"- you can [see this approach here](https://github.com/robertolofaro/ai-organizational-scalability-sample-databook)
4. the concept is: in some cases, the execution of steps could start from successive steps (e.g. to augment or post-process data), and if resources are available could also be parellelized (as would have been on mainframe).

I have not yet released any ML model online, as I am just a novice who started building models in 2020 during COVID lockdowns, resurrecting 1980s experience on Decision Support Systems using basically multivariate linear regression and decision trees within a Rubik-cube kind of Excel with formulas readable by humans, not positional.

Anyway, as my focus and interest is in distributed decision-making support, I experimented with Raspberry, Edge AI (an interesting not-really-for-faint-hearted but with plenty of documentation updated up to 2022 and leads for further learning is available for free here](https://open.hpi.de/courses/edgeai2022), [pickle](https://docs.python.org/3/library/pickle.html), [onnx](https://onnx.ai/).

So, eventually, when I will have something worth sharing, will [post it here and on Kaggle something that actually started courtesy of Kaggle string of micro-training hands-on: followed all of them](https://www.kaggle.com/learn)

If you have suggestions, requests, etc, please [contact me on Linkedin](https://linkedin.com/in/robertolofaro)
