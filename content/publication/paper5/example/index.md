---
title: "Intelligent sensitivity analysis framework based on machine learning for spacecraft thermal design"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Guo
- Yuting Yang
- Hongliang Wang


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"
- "Co-Author"

date: "2021-07-05T00:00:00Z"
doi: "10.1016/j.ast.2021.106927"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Aerospace Science and Technology
publication_short: In *AST*

abstract: The variance-based method of global sensitivity analysis (GSA) has been widely applied in spacecraft thermal design, which is typically calculated using Monte Carlo estimations. However, such estimations require a large number of samples to ensure sufficient accuracy, which makes GSA expensive to perform when modeling is difficult. Moreover, multimodal or highly skewed output distributions may result in the use of variance as an uncertain agent that generates contradictory results. Therefore, an intelligent density-based GSA framework based on machine learning and multi-fidelity metamodels called IDGSA-3M is proposed. An intelligent batch processing system based on a real-time data interaction between MATLAB and NX/TMG was designed that uses many cheap low-fidelity sample points to reduce the cost of model evaluation while using a small number of expensive high-fidelity sample points to maintain high accuracy, thus achieving trade-offs between high accuracy and low computational cost. A radial basis function (RBF) neural network based on an improved mind evolutionary algorithm was applied to approximate the multi-fidelity metamodel of a spacecraft thermophysical model calculated using a batch processing system, which had a computational speed that was 1000+ times faster than that of the traditional thermophysical model and a high computational accuracy of 99%+. The output distributions of the RBF were then characterized by its cumulative distribution functions to obtain density-based sensitivity indices. Both the theoretical and experimental results of GSA for the thermal design parameters of the extreme ultraviolet radiation detector on the space-based Lyman-Alpha Solar Telescope, developed in China, demonstrated that the convergence rate of IDGSA-3M can be improved up to 10-fold for a fixed convergence level in comparison with two other GSA methods, thereby verifying its superiority.

# Summary. An optional shortened abstract.
summary: Aerospace Science and Technology (AST), 2021

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Architecture: [**RL PID**](featured.jpg)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
