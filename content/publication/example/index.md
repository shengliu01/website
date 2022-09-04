---
abstract: "Existing approaches for Structure from Motion (SfM) produce
  impressive 3-D reconstruction results especially when using imagery captured
  with large parallax. However, to create engaging video-content in movies and
  TV shows, the amount by which a camera can be moved while filming a particular
  shot is often limited. The resulting small-motion parallax between video
  frames makes standard geometry-based SfM approaches not as effective for
  movies and TV shows. To address this challenge, we propose a simple yet
  effective approach that uses single-frame depth-prior obtained from a
  pretrained network to significantly improve geometry-based SfM for our
  small-parallax setting. To this end, we first use the depth-estimates of the
  detected keypoints to reconstruct the point cloud and camera-pose for initial
  two-view reconstruction. We then perform depth-regularized optimization to
  register new images and triangulate the new points during incremental
  reconstruction. To comprehensively evaluate our approach, we introduce a new
  dataset (StudioSfM) consisting of 130 shots with 21K frames from 15
  studio-produced videos that are manually annotated by a professional CG
  studio. We demonstrate that our approach: (a) significantly improves the
  quality of 3-D reconstruction for our small-parallax setting, (b) does not
  cause any degradation for data with large-parallax, and (c) maintains the
  generalizability and scalability of geometry-based sparse SfM. Our dataset can
  be obtained at
  https://github.com/amazon-research/small-baseline-camera-tracking."
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
  - Xiaohan Nie
  - Raffay Hamid
author_notes: []
publication: In *IEEE Conference on Computer Vision and Pattern Recognition*
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Depth-Guided Sparse Structure-from-Motion for Movies and TV Shows
doi: https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Depth-Guided_Sparse_Structure-From-Motion_for_Movies_and_TV_Shows_CVPR_2022_paper.pdf
featured: true
tags: []
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
