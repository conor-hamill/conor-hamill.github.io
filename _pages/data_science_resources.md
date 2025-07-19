---
layout: page
title: data science resources
permalink: /data_science_resources/
description: A short collection of resources I've found most useful for learning and revisiting python programming, machine learning, and data visualization.
nav: false
nav_order: 6
toc:
  sidebar: left
---

# Table of Contents

- [Python Programming](#python-programming)
  - [Books](#books)
  - [Online Resources](#online-resources)
  - [Podcasts](#podcasts)
- [Machine Learning](#machine-learning)
  - [Books](#books-1)
- [Machine Learning and AI News and Developments](#machine-learning-and-ai-news-and-developments)
  - [Online Resources](#online-resources)
  - [Podcasts](#podcasts-1)
- [Data Visualization](#data-visualization)
  - [Online Resources](#online-resources-2)
- [Computer science/software engineering](#computer-sciencesoftware-engineering)
  - [Online Resources](#online-resources-3)
- [Git](#git)
  - [Git undo flowchart](#git-undo-flowchart)

## Python Programming

### Books

- **Effective Python: 90 Specific Ways to Write Better Python, 2nd edition**; Brett Slatkin
  - Strongly recommend for all levels of Python ability
  - Breaking down of Python into different chapters, then with the takeaway for the section as the title of the section, makes it easy to locate what you want
  - Each section has a motivating narrative, with a scenario, a set of improving code implementations, and a summary of practical takeaway messages making the tips very impactful
- **Python Tricks: The Book**; Dan Bader
  - Closely behind Effective Python in my recommendations
  - Similarly, breaks down sections by themes, with code to emphasize the points

### Online Resources

- [**Real Python**](https://realpython.com/)
  - Pages on specific topics, for example, object-oriented programming, decorators, functional programming
  - Structure of pages means that you can often quickly find an example of what you want an answer to, but can hang around a bit longer to have a more in-depth look into the topic in question
  - Can subscribe to Real Python to get access to further materials, including courses consisting of different materials
- [**DataCamp**](https://www.datacamp.com/)
  - Has good courses, but have to pay for them or get access through employers
  - Combination of videos, text, and exercises makes courses stimulating
  - Covers Python programming, but also has data science-focused courses, for example, data visualization and machine learning
  - A good option for learning Python, but courses may not be what intermediate or advanced Python users are looking for, especially for topics around machine learning

### Podcasts

- [Python Bytes](https://pythonbytes.fm/)
  - Translating Python discussion into an audio medium is challenging, but this light-hearted podcast is a great listen for packages, techniques, and opinions on Python
  - Contains some information on web development that might not be of interest to data scientists, but does give a break from the oft-repeated pandas/numpy/sklearn guidance.

## Machine Learning

### Books

- **Machine Learning with PyTorch and Scikit-Learn**; Sebastian Raschka
  - Comprehensive guide to using sklearn and PyTorch, with derivation of techniques, in-depth code examples, and detailed justification
  - Most recent edition gives details of up-to-date techniques like reinforcement learning, GANs, and transformers
- **An Introduction to Statistical Learning, with Applications in Python**; Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, Jonathan Taylor
  - Version of previous book which only had examples in R
  - More in-depth focus on statistics than other books, definitely a good book for data scientists looking to strengthen their statistics knowledge

## Machine Learning and AI News and Developments

### Online Resources

- [**Ahead of AI**](https://magazine.sebastianraschka.com/); Sebastian Raschka
  - Articles distill key information and ideas from AI publications
  - Articles include monthly summaries of key publications, significant new ideas in machine learning, and practical tips for applying new developments

### Podcasts

- [**The AI Breakdown**](https://www.youtube.com/channel/UCKelCK4ZaO6HeEI1KQjqzWA); Nathaniel Whittemore
  - High-level podcast about latest stories and opinion pieces in AI

## Data Visualization

### Online Resources

- [**Matplotlib Quick Start Guide**](https://matplotlib.org/stable/users/explain/quick_start.html)
  - Guide to getting started with mpl, often skipped whenever visualizing with mpl
  - Describes usage of the two paradigms in mpl - the explicit object-oriented style and the functional pyplot style. The distinction and usage between these two is a very common source of confusion for users
- [**Python Graph Gallery**](https://python-graph-gallery.com/)
  - Want to make a plot in Python but can't remember which of matplotlib/seaborn/pyplot is best for this and how you get started? This is the website for you
  - Grouped by (many) types of plots, with code examples for all the libraries that provide options for this

## Computer science/software engineering

### Online Resources

- **The Missing Semester of Your CS Education**: [./missing-semester](https://missing.csail.mit.edu)
  - A course that covers the tools programmers will use the most "as fluid and frictionless as possible", including shell tools (bash), editors (Vim), and version control (Git)
  - I would recommend that anyone and everyone who programs takes the time out to do this course. This is the course I wish had been the first thing I had done at the start of my PhD

## Git

### Git undo flowchart

From repeated searching of the correct git command to undo some changes in a code repository, I have compiled a flowchart for finding the correct command that can be found [here](/data_science_resources/git_undo/).
