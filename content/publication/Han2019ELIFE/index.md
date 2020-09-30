---
title: "Deciphering anomalous heterogeneous intracellular transport with neural networks"
authors:
- Daniel S. Han
- Nickolay Korabel
- Runze Chen
- Mark Johnston
- Viki J. Allan
- Sergei Fedotov
- Thomas A. Waigh


date: "2019-09-23T00:00:00Z"
doi: "10.1101/777615"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: bioRxiv
publication_short: bioRxiv

abstract: Biological intracellular transport is predominantly heterogeneous in both time and space, exhibiting varying non-Brownian behaviour. Characterisation of this movement through averaging methods over an ensemble of trajectories or over the course of a single trajectory often fails to capture this heterogeneity adequately. Here, we have developed a deep learning feedforward neural network trained on fractional Brownian motion, which provides a novel, accurate and efficient characterization method for resolving heterogeneous behaviour of intracellular transport both in space and time. Importantly, the neural network requires significantly fewer data points compared to established methods, such as mean square displacements, rescaled range analysis and sequential range analysis. This enables robust estimation of Hurst exponents for very short time series data, making possible direct, dynamic segmentation and analysis of experimental tracks of rapidly moving cellular structures such as endosomes and lysosomes. By using this analysis, we were able to interpret anomalous intracellular dynamics as fractional Brownian motion with a stochastic Hurst exponent.

# Summary. An optional shortened abstract.
summary: Biological intracellular transport is predominantly heterogeneous in both time and space, exhibiting varying non-Brownian behaviour. Characterisation of this movement through averaging methods over an ensemble of trajectories or over the course of a single trajectory often fails to capture this heterogeneity adequately. Here, we have developed a deep learning feedforward neural network trained on fractional Brownian motion, which provides a novel, accurate and efficient characterization method for resolving heterogeneous behaviour of intracellular transport both in space and time. Importantly, the neural network requires significantly fewer data points compared to established methods, such as mean square displacements, rescaled range analysis and sequential range analysis. This enables robust estimation of Hurst exponents for very short time series data, making possible direct, dynamic segmentation and analysis of experimental tracks of rapidly moving cellular structures such as endosomes and lysosomes. By using this analysis, we were able to interpret anomalous intracellular dynamics as fractional Brownian motion with a stochastic Hurst exponent.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://www.biorxiv.org/content/early/2019/09/23/777615.full.pdf
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
  caption: 'Plots of the neural network estimating the Hurst exponentwith a moving window to detect and segment persistent and anti-persistentbehaviour in experimental trajectories.'
  focal_point: ""
  preview_only: false
---

