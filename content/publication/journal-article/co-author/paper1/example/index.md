---
title: "Global Sensitivity Analysis Based on BP Neural Network for Thermal Design Parameters"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuting Yang
- Liheng Chen
- admin
- Shijun Li
- Xu Meng


# Author notes (optional)
author_notes:
- "First Author"
- "Corresponding author"
- "Co-Author"
- "Co-Author"
- "Co-Author"

date: "2020-12-14T00:00:00Z"
doi: "10.2514/1.T5955"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Thermophysics and Heat Transfer
publication_short: In *JTHT*

abstract: In order to obtain the thermal design parameters that have a great influence on the temperature T of the spectrometer frame, the sensitivity of the thermal design parameters of a balloon-borne spectrometer system was analyzed and calculated by the global sensitivity analysis (GSA) method based on the backpropagation neural network (BPNN) surrogate model. Firstly, the BPNN with 12 selected thermal design parameters as input and temperature T as output was well trained. Then, two kinds of variance-based GSA methods, the Sobol’ method and the extended Fourier amplitude sensitivity test (EFAST), were used to calculate the values and ranking results of sensitivity indices of 12 parameters based on the established BPNN. Moreover, the GSA results were verified based on the finite element model of the balloon-borne spectrometer system built by I-DEAS/TMG (software developed by Structural Dynamics Research Corporation for space thermal analysis), which indicates that the BPNN surrogate-model-based GSA is reliable. Finally, the sensitivity calculation accuracy and speed of two methods, the Spearman rank correlation coefficient formula and the GSA method based on BPNN, were compared, and the EFAST method based on the BPNN surrogate model has been proved to have obvious advantages in the reliability and speed of calculation results. Also, the GSA method based on a surrogate model like BPNN is of great significance in the thermal analysis of an optical remote sensor.

# Summary. An optional shortened abstract.
summary: Journal of Thermophysics and Heat Transfer (JTHT), 2020

tags:
- Spacecraft Thermal control
- Space telescope
- Global Sensitivity Analysis
- NX/TMG
- Machine Learning
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
  caption: 'Convergence: [**GSA**](featured.jpg)'
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
