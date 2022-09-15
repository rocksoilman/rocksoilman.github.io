---
title: "Observability-based sensor placement improves contaminant tracing in river networks"
collection: publications
permalink: /publication/2021-06-26-observability
date: 2021-06-26
venue: 'Water Resources Research'
type: 'article'
paperurl: 'https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020WR029551'
file: 'https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2020WR029551'
filetype: 'Full text'
citation: '<b>Bartos, M.</b>, & Kerkez, B. (2021). Observability-based sensor placement improves contaminant tracing in river networks. <i>Water Resources Research</i>, 57(7), doi:10.1029/2020wr029551'
authors: "<b>Bartos, M.</b> & Kerkez, B."
journal_info: "<i>Water Resources Research</i>, 57(7), (2021)"
abstract_art: 'https://mdbartos.s3.us-east-2.amazonaws.com/img/abstract_art_12.png'
thumbnail: 'https://mdbartos.s3.us-east-2.amazonaws.com/img/sensor_placement_thumb.png'
abstract_art_caption: 'Visualization of sensor placements predicted by observability maximization. Sensor placement progression for trace- (left) and rank- (right) optimized strategies from N=2 to N=16 sensors.'
tags: ['state-estimation', 'networks', 'algorithms', 'water-quality']
---

## Abstract

This study presents a new methodology for identifying near-optimal sensor locations for contaminant source tracing in river networks. To establish a physical basis for the problem, we first derive a linear time-invariant (LTI) model for riverine contaminant transport using the one-dimensional advection-diffusion equation. We then formulate an optimization problem to find the sensor placement that maximizes the observability of the modeled system, and identify two heuristics for efficiently achieving this goal. Evaluating each sensor placement strategy on its ability to reconstruct initial contaminant loads from observed outputs, we find that the best sensor placement is obtained by greedily maximizing the rank of the LTI system's Observability Gramian. In addition to providing the best approximate reconstruction of internal states, this strategy makes it possible to perfectly recover any initial contaminant load while only monitoring a small subset of river branches (~14%). Our methodology will enable researchers to build sensor networks that better interpolate pollutant loads in ungaged locations, improve contaminant source identification, and inform more effective pollution control strategies.
