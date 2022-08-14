---
title: "Stability Index of Real Varieties – Theorem of Bröcker and Scheiderer"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "University of Helsinki"

date: "2022-02-23T00:00:00Z"
#doi: "https://doi.org/10.14778/3476311.3476314"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: In *Proceedings of the VLDB Endowment*
publication_short: Master's thesis

#abstract: 

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["stability index", "Theorem of Bröcker and Scheiderer", "real closed fields", "semi-algebraic geometry", "quadratic forms", "Pfister forms"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#links:
#- name: 'arxiv'
#  url: 'https://arxiv.org/abs/2109.00929'

url_video: ''
url_pdf: 'http://hdl.handle.net/10138/340827'
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

In this work, I prove the theorem of Bröcker and Scheiderer for basic open semi-algebraic sets. The theorem provides an upper bound for a stability index of a real variety. The theory is based on real closed fields which generalize real numbers. A real variety is a subset of a real closed field that is defined by polynomial equalities. Every semi-algebraic set is defined by a boolean combination of polynomial equations and inequalities of the sign conditions involving a finite number of polynomials. The basic semi-algebraic sets are those semi-algebraic sets that are defined solely by the sign conditions. In other words, we can construct semi-algebraic sets from the basic semi-algebraic sets by taking the finite unions, intersections, and complements of the basic semi-algebraic sets. 

Then the stability index of a real variety indicates the upper bound of numbers of polynomials that are required to express an arbitrary semi-algebraic subset of the variety. The theorem of Bröcker and Scheiderer shows that such upper bound exists and is finite for basic open semi-algebraic subsets of a real variety.

This work aims to be detailed in the proofs and represent sufficient prerequisites and references. The first chapter introduces the topic generally and motivates to study the theorem. The second chapter provides advanced prerequisites in algebra. One of such results is the factorial theorem of a total ring of fractions. Other advanced topics include radicals, prime ideals, associative algebras, a dimension of a ring, and various quotient structures.

The third chapter defines real closed fields and semi-algebraic sets that are the fundamental building blocks of the theory. The third chapter also develops the theory of quadratic forms. The main result of this chapter is Witt’s cancellation theorem. We also shortly describe the Tsen-Lang theorem.

The fourth chapter is about Pfister forms. Pfister forms are special kinds of quadratic forms that we extensively use in the proof of the main theorem. First, we define general Pfister forms over fields. Then we develop their theory over the fields of rational functions. Generally, Pfister forms share multiple similar properties as quadratic forms.

The fifth chapter represents one- and two-dimensional examples of the main theorem. These examples are based on research that is done on constructive approaches to the theorem of Bröcker and Scheiderer. The examples clarify and motivate the result from an algorithmic perspective. Finally, we prove the main theorem of the work. The proof is heavily based on Pfister forms.