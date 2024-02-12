---
title: "Comparing Statistical Models for Retrieval based Question-answering Dialogue: BERT vs Relevance Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anton Leuski
  - David Traum

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"

date: "2023-05-8T00:00:00Z"
doi: "10.32473/flairs.36.133386"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-8T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In the *36th Florida Artificial Intelligence Research Society Conference*
publication_short: In *FLAIRS*

abstract: In this paper, we compare the performance of four models in a retrieval based question answering dialogue task on two moderately sized corpora (~ 10,000 utterances). One model is a statistical model and uses cross language relevance while the others are deep neural networks utilizing the BERT architecture along with different retrieval methods. The statistical model has previously outperformed LSTM based neural networks in a similar task whereas BERT has been proven to perform well on a variety of NLP tasks, achieving state-of-the-art results in many of them. Results show that the statistical cross language relevance model outperforms the BERT based architectures in learning question-answer mappings. BERT achieves better results by mapping new questions to existing questions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Natural Language Processing, Relevance Modelling, Transformers, Natural Language Dialogue]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://journals.flvc.org/FLAIRS/article/view/133386"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - nl2sql

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
