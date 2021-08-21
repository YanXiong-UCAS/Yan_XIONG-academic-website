---
title: "Intelligent Thermal Control Strategy Based on Reinforcement Learning for Space Telescope"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Guo
- Yong Huang
- Liheng Chen


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"
- "Co-Author"

date: "2020-01-01T00:00:00Z"
doi: "10.2514/1.T5774"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Thermophysics and Heat Transfer
publication_short: In *JTHT*

abstract: In this study, a thermal model of a space telescope is established in Simulink. An intelligent autonomous thermal control strategy based on actor-critic reinforcement learning (RL) for proportional–integral–derivative (PID) parameter adaptive self-tuning, called RL PID, is proposed. This control strategy enables the PID thermal controller to adaptively tune the PID parameters to achieve stable and precise temperature control. A single radial basis function (RBF) neural network is applied to simultaneously approximate the strategy function of the actor and the value function of the critic. The actor maps the system state to PID parameters, and the critic evaluates the output of the actor and generates a temporal difference (TD) error. Based on the architecture of the actor-critic RL algorithm and the TD error performance index, a design flow chart of RL PID is made. Both theoretical and experimental results show that RL PID can achieve a temperature control precision of 0.01°C, and that the steady-state error is reduced by 50 and 75% in the simulation and 50 and 67% in the experiment compared with those of the traditional PID controller and the traditional switch controller, respectively. RL PID has better reliability, more robustness, and a faster response.

# Summary. An optional shortened abstract.
summary: Journal of Thermophysics and Heat Transfer (JTHT), 2020

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
