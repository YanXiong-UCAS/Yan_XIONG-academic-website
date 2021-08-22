---
title: "Intelligent Thermal Control Algorithm Based on Deep Deterministic Policy Gradient for Spacecraft"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Guo
- Hongliang Wang
- Yong Huang
- Chunlong Liu


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"
- "Co-Author"
- "Co-Author"

date: "2020-05-11T00:00:00Z"
doi: "10.2514/1.T5951"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Thermophysics and Heat Transfer
publication_short: In *JTHT*

abstract: In practical applications, the control parameters of a proportional integral derivative (PID) thermal controller are difficult to self-tuning online. As the control object or environment changes, the control parameters are required to change accordingly. An intelligent thermal controller based on the deep deterministic policy gradient, called DRLTC, is proposed. Two types of reinforcement learning agents were designed in DRLTC, which can automatically adjust the control parameters of the thermal controllers and self-optimize online after training. Both theoretical and experimental results revealed that, when the control object was the main mirror support, the DRLTC achieved a control precision of 0.01 °C. Additionally, the steady-state error was reduced by 40.2%, 62.5%, and 33.3% in the simulation, and by 5.6%, 80.6%, and 85.7% in the experiment, compared with the reinforcement learning PID, neural network PID, and Fuzzy PID, respectively. When the control object was changed to the main mirror installation, the DRLTC achieved a control precision of 0.02 °C, and the steady-state error was reduced by 87.5%, 91.7%, and 90.9% in the simulation, and by 80.2%, 90.6%, and 85.7% in the experiment, compared with the above-mentioned thermal control strategies, respectively. Therefore, the DRLTC has better universality, stronger robustness, and achieve more energy saving.

# Summary. An optional shortened abstract.
summary: An intelligent thermal controller based on the deep deterministic policy gradient, called DRLTC, is proposed.

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
  caption: 'Architecture: [**DRLTC**](featured.jpg)'
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
