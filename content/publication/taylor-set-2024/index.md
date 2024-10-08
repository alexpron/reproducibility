---
title: 'A Set of FMRI Quality Control Tools in AFNI: Systematic, in-depth, and interactive
  QC with afni_proc.py and more'
authors:
- Paul A. Taylor
- Daniel R. Glen
- Gang Chen
- Robert W. Cox
- Taylor Hanayik
- Chris Rorden
- Dylan M. Nielson
- Justin K. Rajendra
- Richard C. Reynolds
date: '2024-08-01'
publishDate: '2024-08-12T09:30:40.842252Z'
publication_types:
- article-journal
publication: '*Imaging Neuroscience*'
doi: 10.1162/imag_a_00246
abstract: Abstract Quality control (QC) assessment is a vital part of FMRI processing
  and analysis, and a typically underdiscussed aspect of reproducibility. This includes
  checking datasets at their very earliest stages (acquisition and conversion) through
  their processing steps (e.g., alignment and motion correction) to regression modeling
  (correct stimuli, no collinearity, valid fits, enough degrees of freedom, etc.)
  for each subject. There are a wide variety of features to verify throughout any
  single-subject processing pipeline, both quantitatively and qualitatively. We present
  several FMRI preprocessing QC features available in the AFNI toolbox, many of which
  are automatically generated by the pipeline-creation tool, afni_proc.py. These items
  include a modular HTML document that covers full single-subject processing from
  the raw data through statistical modeling, several review scripts in the results
  directory of processed data, and command line tools for identifying subjects with
  one or more quantitative properties across a group (such as triaging warnings, making
  exclusion criteria, or creating informational tables). The HTML itself contains
  several buttons that efficiently facilitate interactive investigations into the
  data, when deeper checks are needed beyond the systematic images. The pages are
  linkable, so that users can evaluate individual items across a group, for increased
  sensitivity to differences (e.g., in alignment or regression modeling images). Finally,
  the QC document contains rating buttons for each “QC block,” as well as comment
  fields for each, to facilitate both saving and sharing the evaluations. This increases
  the specificity of QC, as well as its shareability, as these files can be shared
  with others and potentially uploaded into repositories, promoting transparency and
  open science. We describe the features and applications of these QC tools for FMRI.
tags:
- qc
- to read
links:
- name: URL
  url: 
    https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00246/123633/A-Set-of-FMRI-Quality-Control-Tools-in-AFNI
---
