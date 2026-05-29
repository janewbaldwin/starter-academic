---
title: Data-Driven Integration Kernels for Interpretable Nonlocal Operator Learning
abstract: Machine learning models can represent climate processes that are
  nonlocal in horizontal space, height, and time, often by combining information
  across these dimensions in highly nonlinear ways. While this can improve
  predictive skill, it makes learned relationships difficult to interpret and
  prone to overfitting as the extent of nonlocal information grows. We address
  this challenge by introducing data-driven integration kernels, a framework
  that adds structure to nonlocal operator learning by explicitly separating
  nonlocal information aggregation from local nonlinear prediction. Each
  spatiotemporal predictor field is first integrated using learnable kernels
  (defined as continuous weighting functions over horizontal space, height,
  and/or time), after which a local nonlinear mapping is applied only to the
  resulting kernel-integrated features and optional local inputs. This design
  confines nonlinear interactions to a small set of integrated features and
  makes each kernel directly interpretable as a weighting pattern that reveals
  which horizontal locations, vertical levels, and past timesteps contribute
  most to the prediction. We demonstrate the framework for South Asian monsoon
  precipitation using a hierarchy of neural network models with increasing
  structure, including baseline, nonparametric kernel, and parametric kernel
  models. Across this hierarchy, kernel models achieve near-baseline performance
  with far fewer trainable parameters, indicating that much of the relevant
  nonlocal information can be captured through a small set of interpretable
  integrations when appropriate structural constraints are imposed.
authors:
  - Savannah L. Ferretti
  - Jerry Lin
  - Sara Shamekh
  - Jane W. Baldwin
  - Michael S. Pritchard
  - Tom Beucler
date: 2026-03-11T20:30:45.245Z
publication_types:
  - "0"
publication: "*Cornell University*"
url_pdf: https://arxiv.org/pdf/2603.10305
draft: false
---
