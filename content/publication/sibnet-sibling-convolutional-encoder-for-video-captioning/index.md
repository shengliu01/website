---
title: "SibNet: Sibling Convolutional Encoder for Video Captioning"
publication_types:
  - "2"
authors:
  - admin
  - Zhou Ren
  - Junsong Yuan
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence* (TPAMI)
abstract: >-
  Visual captioning, the task of describing an image or a video using one or few
  sentences, is a challenging task owing to the complexity of understanding the
  copious visual information and describing it using natural language. Motivated
  by the success of applying neural networks for machine translation, previous
  work applies sequence to sequence learning to translate videos into sentences.
  In this work, different from previous work that encodes visual information
  using a single flow, we introduce a novel Sibling Convolutional Encoder
  (SibNet) for visual captioning, which employs a dual-branch architecture to
  collaboratively encode videos. The

  first content branch encodes visual content information of the video with an autoencoder, capturing the visual appearance information of the video as other networks often do. While the second semantic branch encodes semantic information of the video via visual-semantic joint embedding, which brings complementary representation by considering the semantics when extracting features from videos. Then both branches are effectively combined with soft-attention mechanism and finally fed into a RNN decoder to generate captions. With our SibNet explicitly capturing both content and semantic information, the proposed model can better

  represent the rich information in videos. To validate the advantages of the proposed model, we conduct experiments on two benchmarks for video captioning, YouTube2Text and MSR-VTT. Our results demonstrates that the proposed SibNet consistently outperforms existing methods across different evaluation metrics.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-09-04T19:05:43.335Z
---
