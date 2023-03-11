---
title: "Estimating categorical counterfactuals via deep twin networks"
authors:
- admin
- Bernhard Kainz
- Ciaran M. Gilligan-Lee
author_notes:

date: "2020-02-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Nature Machine Intelligence"
publication_short: "NMI"

abstract: Counterfactual inference is a powerful tool, capable of solving challenging problems in high-profile sectors. To perform counterfactual inference, we require knowledge of the underlying causal mechanisms. However, causal mechanisms cannot be uniquely determined from observations and interventions alone. This raises the question of how to choose the causal mechanisms so that the resulting counterfactual inference is trustworthy in a given domain. This question has been addressed in causal models with binary variables, but for the case of categorical variables, it remains unanswered. We address this challenge by introducing for causal models with categorical variables the notion of counterfactual ordering, a principle positing desirable properties that causal mechanisms should possess and prove that it is equivalent to specific functional constraints on the causal mechanisms. To learn causal mechanisms satisfying these constraints, and perform counterfactual inference with them, we introduce deep twin networks. These are deep neural networks that, when trained, are capable of twin network counterfactual inference—an alternative to the abduction–action–prediction method. We empirically test our approach on diverse real-world and semisynthetic data from medicine, epidemiology and finance, reporting accurate estimation of counterfactual probabilities while demonstrating the issues that arise with counterfactual reasoning when counterfactual ordering is not enforced

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Causal Inference
- Machine Learning
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s42256-023-00611-x
url_code: 'https://github.com/thanosvlo/Twin_Causal_Nets'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
