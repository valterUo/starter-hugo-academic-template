---
title: Quantum Circuit Learning Method for SQL Cardinality, Cost and Time Estimation

event: The Nordic AI young researcher symposium
event_url: https://nordicaimeet.com/

location: Oslo
# address: The Clarion Hotel
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

#summary: An example talk using Wowchemy's Markdown slides feature.
#abstract: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-11-14T08:00:00Z'
date_end: '2022-11-15T16:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-04-16T00:00:00Z"

authors: [Valter Uotila]
tags: ["quantum computing", "quantum natural language processing", "quantum machine learning", "estimating metrics for SQL"]

# Is this a featured talk? (true/false)
featured: false

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#- icon: twitter
#  icon_pack: fab
url_site: https://2022.nordicaimeet.com/oralpresentations
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#- example
---

Structured Query Language (SQL) is the most used relational database query language in the world. In modern applications, data volume, variety, and connectivity have increased. Querying data should not become a bottleneck in data-intensive applications.

Query processors in relational databases can assign SQL queries to various measurements, such as cardinality, cost, and execution time estimations [1]. The optimization of the query heavily depends on the estimates. Usually, the problem is solved with machine learning, dynamic programming, or integer programming.
Quantum computers are reaching the level where they can be part of various applications on a small scale. We believe that databases and quantum computers will be co-designed in the future so that combinatorically hard database optimization problems can be solved efficiently and with high quality on quantum computers. 
As far as we know, our work is the first attempt to apply quantum computing and quantum circuit learning as a part of the SQL query optimization pipeline. Even if we cannot beat the classical methods with the current quantum hardware, we can point out its limitations, understand quantum computing frameworks in a circuit learning context, and propose novel methods to model the problems with quantum computing algorithms. Especially quantum computing and machine learning are a promising combination because both are based on linear algebra and probability theory.

We utilize methods from quantum natural language processing (QNLP) [2] and quantum circuit learning [3]. First, we parse SQL queries and represent them using context-free grammar (CFG) diagrams. The CFG diagrams are functorially mapped to pregroup grammar diagrams. We perform a rewriting process for the pregroup grammar diagrams to optimize and reduce their size.  We functorially translated them into parameterized quantum circuits. We will optimize the circuit parameters using standard quantum circuit learning pipelines. A quantum computer or a simulator is used to evaluate the circuit, but the actual training happens on classical hardware.

This is still ongoing work. Currently, we are at the phase where we can represent SELECT-FROM-WHERE type of SQL queries with complex filtering and join expressions using pregroup grammar diagrams and parametrized circuits. The corresponding results from QNLP are promising. We are excited to be able to express complex SQL queries as parametrized circuits and utilize the quantum circuit learning methods.

[1] Lan, H., Bao, Z. & Peng, Y. A Survey on Advancing the DBMS Query Optimizer: Cardinality Estimation, Cost Model, and Plan Enumeration. Data Sci. Eng. 6, 86–101 (2021). https://doi.org/10.1007/s41019-020-00149-7
[2] Meichanetzidis, K., Gogioso, S., De Felice, G., Chiappori, N., Toumi, A., & Coecke, B. (2020). Quantum natural language processing on near-term quantum computers. arXiv preprint arXiv:2005.04147.
[3] Mitarai, K., Negoro, M., Kitagawa, M., & Fujii, K. (2018). Quantum circuit learning. Physical Review A, 98(3), 032309.
