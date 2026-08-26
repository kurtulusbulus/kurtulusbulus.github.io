---
layout: page
title: Research
permalink: /research/
---

My research is centred on photon-limited biomedical imaging: how to design better measurements by combining detector physics, optical instrumentation and computational inference.

## SPAD-based imaging

Single-photon avalanche diode (SPAD) arrays offer a combination of single-photon sensitivity, high temporal resolution and massively parallel detection. My work investigates how these properties can be used in biological imaging, particularly when the signal is fast, weak or both.

Key topics include:

- high-speed neural imaging and photometry
- detector modelling and signal-to-noise analysis
- photon detection efficiency, dark counts and dynamic range
- ROI size and spatial binning
- single-bit versus multi-bit SPAD acquisition
- real-time camera acquisition and processing

A major practical output from this work is [pySPAD](https://github.com/MattNolanLab/pySPAD), an open-source Python framework for high-speed SPAD-camera acquisition and analysis.

## Time-resolved Raman spectroscopy

My current postdoctoral research at the University of Glasgow focuses on time-gated Raman spectroscopy and imaging. Raman measurements can be dominated by fluorescence, especially in biological samples. Temporal gating provides a route to preferentially detect the faster Raman response while rejecting longer-lived background emission.

My work in this area includes:

- optical-system and spectrometer design
- intensified-camera and SPAD-based detection
- temporal-gating characterisation
- fluorescence-background suppression
- time-of-flight and stand-off measurement concepts
- translation toward biomedical Raman imaging

The broader goal is to exploit fast photon-counting detectors to improve Raman measurements in challenging low-light and high-background conditions.

## Computational imaging

Hardware performance alone does not determine image quality. I am also interested in reconstruction methods that explicitly account for the measurement process.

Current directions include:

- self-supervised denoising for photon-limited images
- physics-informed neural networks
- Poisson and SPAD-specific noise models
- forward-model consistency during training
- signal reconstruction without clean ground-truth targets

This direction connects detector modelling with modern machine learning: rather than asking a network to learn an unconstrained mapping, the aim is to incorporate what is already known about photon statistics and sensor behaviour.

## Long-term direction

My long-term research goal is to build imaging systems in which sensor design, optics, acquisition electronics and computational reconstruction are developed together. I am particularly interested in tools that can enable faster or more sensitive measurements in neuroscience and biomedical imaging.