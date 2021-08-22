---
title: "Intelligent Optimization Strategy Based on Statistical Machine Learning for Spacecraft Thermal Design"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Guo
- Defu Tian
- Yang Zhang
- Chunlong Liu


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"
- "Co-Author"
- "Co-Author"

date: "2020-11-06T00:00:00Z"
doi: "10.1109/ACCESS.2020.3036548"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Access
publication_short: In *IEEE Access*

abstract: The thermal design of spacecraft becomes increasingly complicated as various advanced technologies are continuously introduced to the spacecraft. Determining and optimizing the uncertainties of a spacecraft thermal control system through global sensitivity analysis has long been an essential task for thermal engineers. It is a difficult task that relies heavily on engineering experience and is a time-intensive, trial-and-error endeavor that may not even lead to global optimization. Hence, an intelligent optimization strategy based on statistical machine learning for spacecraft thermal design, called IOSML, is proposed. An intelligent batch processing system (IBPS) based on MATLAB, Python, and NX/TMG real-time data interaction is designed. The IBPS uses a surrogate model to reduce the computational cost of global sensitivity analysis while using a detailed thermal mathematical model to maintain accuracy. We combine a Bayesian inference framework with a neural network surrogate spacecraft-thermophysical model that is 100+ times faster than numerical solvers. This article first reports on a density-based global sensitivity analysis that evaluates the effect of design parameters on the temperature difference between the complementary metal–oxide–semiconductor and cold screen of the Lehman Alpha Solar Space Telescope detector. From 42 design parameters, the most sensitive four are selected for optimization, and the temperature difference and the boundary temperature are used as the objective function. Adopting IOSML, under no supervision, four design parameters are optimized through the IBPS, and the effectiveness of the algorithm is verified by comparison with traditional methods. Additionally, IOSML is versatile and can be used in various complex engineering applications to provide guidance for the better selection of appropriate parameters and optimization.

# Summary. An optional shortened abstract.
summary: An intelligent optimization strategy based on statistical machine learning for spacecraft thermal design, called IOSML, is proposed.

tags: []

# Display this page in the Featured widget?
featured: false

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
  caption: 'Performance: [**Bayesian**](featured.jpg)'
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
