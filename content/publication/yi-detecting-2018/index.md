---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Detecting hidden batch factors through data-adaptive adjustment for biological
  effects
subtitle: ''
summary: ''
authors:
- Haidong Yi
- Ayush T. Raman
- Han Zhang
- Genevera I. Allen
- Zhandong Liu
tags:
- '"Algorithms"'
- '"Gene Expression Profiling"'
- '"Glioblastoma"'
- '"Humans"'
- '"Quality Control"'
- '"Research Design"'
- '"Sequence Analysis"'
- '"RNA"'
- '"Topotecan"'
categories: []
date: '2018-04-01'
lastmod: 2021-01-21T18:54:56-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-01-21T23:54:56.316689Z'
publication_types:
- '2'
abstract: 'Motivation: Batch effects are one of the major source of technical variations
  that affect the measurements in high-throughput studies such as RNA sequencing.
  It has been well established that batch effects can be caused by different experimental
  platforms, laboratory conditions, different sources of samples and personnel differences.
  These differences can confound the outcomes of interest and lead to spurious results.
  A critical input for batch correction algorithms is the knowledge of batch factors,
  which in many cases are unknown or inaccurate. Hence, the primary motivation of
  our paper is to detect hidden batch factors that can be used in standard techniques
  to accurately capture the relationship between gene expression and other modeled
  variables of interest. Results: We introduce a new algorithm based on data-adaptive
  shrinkage and semi-Non-negative Matrix Factorization for the detection of unknown
  batch effects. We test our algorithm on three different datasets: (i) Sequencing
  Quality Control, (ii) Topotecan RNA-Seq and (iii) Single-cell RNA sequencing (scRNA-Seq)
  on Glioblastoma Multiforme. We have demonstrated a superior performance in identifying
  hidden batch effects as compared to existing algorithms for batch detection in all
  three datasets. In the Topotecan study, we were able to identify a new batch factor
  that has been missed by the original study, leading to under-representation of differentially
  expressed genes. For scRNA-Seq, we demonstrated the power of our method in detecting
  subtle batch effects. Availability and implementation: DASC R package is available
  via Bioconductor or at https://github.com/zhanglabNKU/DASC. Contact: zhanghan@nankai.edu.cn
  or zhandonl@bcm.edu. Supplementary information: Supplementary data are available
  at Bioinformatics online.'
publication: '*Bioinformatics (Oxford, England)*'
doi: 10.1093/bioinformatics/btx635
---
