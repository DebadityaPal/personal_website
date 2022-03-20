---
title: "Data Agnostic RoBERTa-based Natural Language to SQL Query Generation"
summary: "A novel data blind approach to the popular NL2SQL semantic parsing task keeping data privacy at its core."
tags:
  - Deep Learning
  - Natural Language Processing
  - Semantic Parsing
date: "2021-03-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Model Description
  focal_point: Smart

url_code: https://github.com/DebadityaPal/RoBERTa-NL2SQL
url_pdf: https://arxiv.org/pdf/2010.05243.pdf
url_slides: https://docs.google.com/presentation/d/1rQSOpK3mm2FYhwl1pThADCXzFIPCOICBfspEMWfaV8M/edit?usp=sharing
url_video: https://youtu.be/k867X3Qv06s
---

Relational databases are among the most widely used architectures to store massive amounts of data in the modern world. However, there is a barrier between these databases and the average user. The user often lacks the knowledge of a query language such as SQL required to interact with the database. The NL2SQL task aims at finding deep learning approaches to solve this problem by converting natural language questions into valid SQL queries. Given the sensitive nature of some databases and the growing need for data privacy, we have presented an approach with data privacy at its core. We have passed RoBERTa embeddings and data-agnostic knowledge vectors into LSTM based submodels to predict the final query. Although we have not achieved state of the art results, we have eliminated the need for the table data, right from the training of the model, and have achieved a test set execution accuracy of 76.7%. By eliminating the table data dependency while training we have created a model capable of zero shot learning based on the natural language question and table schema alone.
