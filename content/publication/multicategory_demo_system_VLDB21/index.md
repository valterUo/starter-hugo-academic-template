---
title: "MultiCategory: Multi-Model Query Processing Meets Category Theory and Functional Programming"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lu, Jiaheng
- Gawlick, Dieter
- Liu, Zhen Hua
- Das, Souripriya
- Pogossiants, Gregory

# Author notes (optional)
author_notes:
- "University of Helsinki"
- "University of Helsinki"
- "Oracle"
- "Oracle"
- "Oracle"
- "Oracle"

date: "2021-08-20T08:00:00Z"
doi: "https://doi.org/10.14778/3476311.3476314"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the VLDB Endowment*
publication_short: In *VLDB 2021*

abstract: The variety of data is one of the important issues in the era of Big Data. The data are naturally organized in different formats and models, including structured data, semi-structured data, and unstructured data. Prior research has envisioned an approach to abstract multi-model data with a schema category and an instance category by using category theory. In this paper, we demonstrate a system, called MultiCategory, which processes multi-model queries based on category theory and functional programming. This demo is centered around four main scenarios to show a tangible system. First, we show how to build a schema category and an instance category by loading different models of data, including relational, XML, key-value, and graph data. Second, we show a few examples of query processing by using the functional programming language Haskell. Third, we demo the flexible outputs with different models of data for the same input query. Fourth, to better understand the category theoretical structure behind the queries, we offer a variety of graphical hooks to explore and visualize queries as graphs with respect to the schema category, as well as the query processing procedure with Haskell.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["multi-model databases", "category theory", "functional programming"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: 'arxiv'
  url: 'https://arxiv.org/abs/2109.00929'

url_video: 'https://youtu.be/uceIi91AGsg'
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
