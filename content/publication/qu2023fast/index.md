---
title: 'Fast Rolling Shutter Correction in the Wild'
authors:
  - dl.qu
  - by.liao
  - hq.zhang
  - Omar Ait-Aider
  - yz.lao
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  -
  -
  - 'Correspondence'
date: '2023-06-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'IEEE Transactions on Pattern Analysis and Machine Intelligence ( Volume: 45, Issue: 10, October 2023) '
publication_short: 'T-PAMI'

abstract: This paper addresses the problem of rolling shutter correction (RSC) in uncalibrated videos. Existing works remove rolling shutter (RS) distortion by explicitly computing the camera motion and depth as intermediate products, followed by motion compensation. In contrast, we first show that each distorted pixel can be implicitly rectified back to the corresponding global shutter (GS) projection by rescaling its optical flow. Such a point-wise RSC is feasible with both perspective and non-perspective cases without the pre-knowledge of the camera used. Besides, it allows a pixel-wise varying direct RS correction (DRSC) framework that handles locally varying distortion caused by various sources, such as camera motion, moving objects, and even highly varying depth scenes. More importantly, our approach is an efficient CPU-based solution that enables undistorting RS videos in real-time (40fps for 480p). We evaluate our approach across a broad range of cameras and video sequences, including fast motion, dynamic scenes, and non-perspective lenses, demonstrating the superiority of our proposed approach over state-of-the-art methods in both effectiveness and efficiency. We also evaluated the ability of the RSC results to serve for downstream 3D analysis, such as visual odometry and structure-from-motion, which verifies preference for the output of our algorithm over other existing RSC methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - SLAM
  - Rolling Shutter
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/DelinQu/rspy/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**3DXLab**](https://3dxlab.netlify.app/)'
  focal_point: ''
  preview_only: false

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
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
