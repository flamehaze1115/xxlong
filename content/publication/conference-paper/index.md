---
title: "Occlusion-aware depth estimation with adaptive normal constraints"
authors:
- admin
- Lingjie Liu, Christian Theobalt, Wenping Wang
date: "2020-11-05T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-58545-7_37"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision*
publication_short: In *ECCV 2020*

abstract: We present a new learning-based method for multi-frame depth estimation from a color video, which is a fundamental problem in scene understanding, robot navigation or handheld 3D reconstruction. While recent learning-based methods estimate depth at high accuracy, 3D point clouds exported from their depth maps often fail to preserve important geometric feature (e.g., corners, edges, planes) of man-made scenes. Widely-used pixel-wise depth errors do not specifically penalize inconsistency on these features. These inaccuracies are particularly severe when subsequent depth reconstructions are accumulated in an attempt to scan a full environment with man-made objects with this kind of features. Our depth estimation algorithm therefore introduces a Combined Normal Map (CNM) constraint, which is designed to better preserve high-curvature features and global planar regions. In order to further improve the depth estimation accuracy, we introduce a new occlusion-aware strategy that aggregates initial depth predictions from multiple adjacent views into one final depth map and one occlusion probability map for the current reference view. 

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Project page
  url: https://xxlong0.github.io/CNMNet/
url_pdf: https://arxiv.org/pdf/2004.00845
url_code: 'https://github.com/xxlong0/CNMNet'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](featured.png)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}
