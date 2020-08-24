---
title: "Efficient Sample-based Neural Architecture Search with Learnable Predictor"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Neural Architecture Search (NAS) has shown great potentials in finding a better neural network design than human design.'
date: 2009-10-01
venue: 'Arkiv'
paperurl: 'https://pipilurj.github.io/files/bogcn1.pdf'
---
Neural Architecture Search (NAS) has shown great potentials in finding a better neural network design than human design. Sample-based NAS is the most fundamental method aiming at ex- ploring the search space and evaluating the most promising architecture. However, few works have focused on improving the sampling efficiency for NAS algorithm. For balancing exploitation and exploration, we propose BONAS (Bayesian Op- timized Neural Architecture Search), a sample- based NAS framework combined with Bayesian Optimization. The main components of BONAS are Sampler and Learnable Embedding Extrac- tor. Specifically, we apply Evolution Algorithm method as our sampler and apply Graph Convolu- tional Network predictor as a surrogate model to adaptively discover and incorporate nodes struc- ture to approximate the performance of the archi- tecture. For NAS-oriented tasks, we also design a weighted loss focusing on architectures with high performance. Extensive experiments are con- ducted to verify the effectiveness of our method over many competing methods, e.g. 123.7× more efficient than Random Search and 7.5× more ef- ficient than previous SOTA LaNAS for finding the best architecture on the largest NAS data set NAS-Bench-101.

[Download paper here](https://pipilurj.github.io/files/bogcn1.pdf)
