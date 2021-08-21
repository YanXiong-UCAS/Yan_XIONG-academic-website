---
title: "Application of Deep Reinforcement Learning to Thermal Control of Space Telescope"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liang Guo
- Defu Tian


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"

date: "2020-01-01T00:00:00Z"
doi: "10.1115/1.4051072"

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

abstract: With the development of deep space exploration technology, thermal control systems for space telescopes are becoming increasingly complex, leading to the key parameters of conventional thermal control systems are difficult to adjust online automatically. To achieve these adjustments, this paper provided detailed verification of the application of deep reinforcement learning to space telescope thermal control from three perspectives: thermophysical modelling, intelligent sensing-based radiator, and online self-tuning of thermal control parameters. The paper presents a high-speed and high-precision thermophysical modelling strategy in MATLAB/SIMULINK with better computational efficiency than conventional approaches. And an intelligent sensing-based radiator is proposed that can realize autonomous regulation of the radiating cold plate by sensing the external space environment and the thermal load inside the spacecraft. A strategy for online self-tuning of the thermal control parameters based on deep reinforcement learning is also proposed. Theoretical and experimental results show that deep reinforcement learning thermal control (DRLPID) can achieve temperature control accuracy of 0.05°C. The steady-state errors in the simulations were reduced by 22.7%, 37.4%, and 47.4% when compared with the reinforcement learning proportional-integral-derivative (PID), the neural network PID and the fuzzy PID, respectively. The experimental steady-state errors were reduced by 20.4%, 32.5% and 42.7%, respectively.

# Summary. An optional shortened abstract.
summary: This paper provided detailed verification of the application of deep reinforcement learning to space telescope thermal control from three perspectives: thermophysical modelling, intelligent sensing-based radiator, and online self-tuning of thermal control parameters.

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
  caption: 'Diagram: [**PID based on DDPG**](featured.jpg)'
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
