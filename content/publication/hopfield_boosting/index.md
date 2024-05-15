---
title: "Energy-based Hopfield Boosting for Out-of-Distribution Detection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Simon Schmid
- Bernhard Lehner
- Daniel Klotz
- Sepp Hochreiter

date: "2024-05-15T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2405.08766"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-05-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In NeurIPS Associative Memory & Hopfield Networks in 2023 workshop
publication_short: In *AMHN2023*

abstract: Out-of-distribution (OOD) detection is critical when deploying machine learning models in the real world. Outlier exposure methods, which incorporate auxiliary outlier data in the training process, can drastically improve OOD detection performance compared to approaches without advanced training strategies. We introduce Hopfield Boosting, a boosting approach, which leverages modern Hopfield energy (MHE) to sharpen the decision boundary between the in-distribution and OOD data. Hopfield Boosting encourages the model to concentrate on hard-to-distinguish auxiliary outlier examples that lie close to the decision boundary between in-distribution and auxiliary outlier data. Our method achieves a new state-of-the-art in OOD detection with outlier exposure, improving the FPR95 metric from 2.28 to 0.92 on CIFAR-10 and from 11.76 to 7.94 on CIFAR-100.

# Summary. An optional shortened abstract.
summary: We present Hopfield Boosting, a boosting technique employing modern Hopfield energy for out-of-distribution (OOD) detection to refine the decision boundary between in-distribution and OOD data.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/ml-jku/hopfield-boosting'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=H5tGdL-0fok'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: Top
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
