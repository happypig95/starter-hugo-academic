---
title: 'Enlightened Debugging'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xiangyu Li
  - Shaowei Zhu
  - Marcelo d’Amorim
  - Alessandro Orso

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2018-05-27T00:00:00Z'
doi: 'https://doi.org/10.1145/3180155.3180242'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 40th International Conference on Software Engineering*
publication_short: In *ICSE 2018*

abstract: Numerous automated techniques have been proposed to reduce the cost of software debugging, a notoriously time-consuming and human-intensive activity. Among these techniques, Statistical Fault Localization (SFL) is particularly popular. One issue with SFL is that it is based on strong, often unrealistic assumptions on how developers behave when debugging. To address this problem, we propose Enlighten, an interactive, feedback-driven fault localization technique. Given a failing test, Enlighten (1) leverages SFL and dynamic dependence analysis to identify suspicious method invocations and corresponding data values, (2) presents the developer with a query about the most suspicious invocation expressed in terms of inputs and outputs, (3) encodes the developer feedback on the correctness of individual data values as extra program specifications, and (4) repeats these steps until the fault is found. We evaluated Enlighten in two ways. First, we applied Enlighten to 1,807 real and seeded faults in 3 open source programs using an automated oracle as a simulated user; for over 96% of these faults, Enlighten required less than 10 interactions with the simulated user to localize the fault, and a sensitivity analysis showed that the results were robust to erroneous responses. Second, we performed an actual user study on 4 faults with 24 participants and found that participants who used Enlighten performed significantly better than those not using our tool, in terms of both number of faults localized and time needed to localize the faults.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8453065'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
