---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

# The following 3 lines should be put under "{% include base_path %}"
#{% for post in site.publications reversed %}
#  {% include archive-single.html %}
#{% endfor %} [NASA/ADS](https://ui.adsabs.harvard.edu/search/p_=0&q=orcid%3A0000-0002-3033-6491&sort=date%20desc%2C%20bibcode%20desc), [Google Scholar](https://scholar.google.com/citations?user=FW2tQSwAAAAJ&hl=en)
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Full publication list including collaboration papers can be found at: [INSPIRE-HEP](https://inspirehep.net/authors/2086345?ui-citation-summary=true) and [Google Scholar](https://scholar.google.com/citations?user=FW2tQSwAAAAJ&hl=en). 

## 2025
* **Qian Hu**, Harsh Narola, Jef Heynen, Mick Wright, John Veitch, Justin Janquart, Chris Van Den Broeck, GW231123: Overlapping Gravitational Wave Signals? [arXiv:2512.17550](https://arxiv.org/abs/2512.17550), [Astrophys.J. 1003 (2026) 2, 187](https://doi.org/10.3847/1538-4357/ae6811).
    * An overlapping-signal model is favored over an isolated signal for GW231123 and largely mitigates waveform-dependent parameter discrepancies.
    * Astrophysical rate estimates disfavor a chance overlap; gravitational lensing remains a possible explanation.

* **Qian Hu**, Hierarchical Subtraction with Neural Density Estimators as a General Solution to Overlapping Gravitational Wave Signals. [arXiv:2507.05209](https://arxiv.org/abs/2507.05209). 
    * Parameter estimation models for non-overlapping signals can be used for overlapping signals. 

### 2024
* **Qian Hu**, Jessica Irwin, Qi Sun, Chris Messenger, Lami Suleiman, Ik Siong Heng, John Veitch, Decoding long-duration GW from BNS with machine learning: Parameter estimation and equations of state. [arXiv: 2412.03454](https://arxiv.org/abs/2412.03454), [Astrophys.J.Lett. 987 (2025) 1, L17 ](https://iopscience.iop.org/article/10.3847/2041-8213/ade42f). 
    * Machine learning approaches for fast parameter estimation and equation of state inference for long-duration GW signals. O(1000) CPU hours -> O(1) seconds. 
  
* **Qian Hu**, John Veitch, Costs of Bayesian Parameter Estimation in Third-Generation Gravitational Wave Detectors: a Review of Acceleration Methods. [arXiv: 2412.02651](https://arxiv.org/abs/2412.02651), [Phys.Rev.D 112 (2025) 8, 084039 ](https://doi.org/10.1103/dj7k-tk37).
    * How will current parameter estimation methods scale in 3G detectors? Keywords: millions, billions, .... 


### 2023
* **Qian Hu**, John Veitch, Rapid pre-merger localization of binary neutron stars in third generation gravitational wave detectors. [arXiv:2309.00970](https://arxiv.org/abs/2309.00970), [Astrophys.J.Lett. 958 (2023) 2, L43 ](https://iopscience.iop.org/article/10.3847/2041-8213/ad0ed4). 
    * SealGW x Multi-banding: A demonstration of localizing long signals in 3G detectors.

### 2022
* **Qian Hu**, John Veitch, Accumulating errors in tests of general relativity with gravitational waves: overlapping signals and inaccurate waveforms. [arXiv:2210.04769](https://arxiv.org/abs/2210.04769), [Astrophys.J. 945 (2023) 2, 103](https://iopscience.iop.org/article/10.3847/1538-4357/acbc18). 
    * Systematic error can accumulate in a CBC catalog and lead to a false deviation of GR.
    * Inaccurate waveforms contribute to most of the error, and overlapping signals magnify the impact of waveform systematics.
    * "Golden events" are more vulnerable to systematic errors. 

* **Qian Hu**, John Veitch, Assessing the model waveform accuracy of gravitational waves. [arXiv:2205.08448](https://arxiv.org/abs/2205.08448), [PRD 106, 044042 (2022)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.106.044042).
    * Evaluating GW waveform accuracy by looking into difference between two waveform models. It's free from the unknown true waveform or numerical relativity simulations.
    * Applied to GWTC posterior samples to evaluate waveform model accuracy: with current detector sensitivity we can make loud detections in which waveform models are not accurate enough. This may have some impacts on parameter estimation. 
    * Applied to simulations: high spin, low mass ratio and edge-on inclination are the "bad" regions in the parameter space.


### 2021
* **Qian Hu**, Mingzheng Li, Rui Niu, and Wen Zhao. Joint Observations of Space-based Gravitational-wave Detectors: Source Localization and Implication for Parity-violating Gravity. [arXiv:2006.05670](https://arxiv.org/abs/2006.05670), [PRD 103, 064057 (2021)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.103.064057). 
    * Bayesian parameter estimation on space-borne GW detectors. We investigated the improvements of GW source localization and constraint on parity-violating gravity given by space-borne GW detector networks. 
  
* **Qian Hu**, Cong Zhou, Jhao-Hong Peng, Linqing Wen, Qi Chu, Manoj Kovalam. Semianalytical Approach for Sky Localization of Gravitational Waves. [arXiv:2110.01874](https://arxiv.org/abs/2110.01874), [PRD 104, 104008 (2021)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.104.104008).
    * A fast GW source localization method for compact binary coalescences, and is implemented into online detection pipeline SPIIR.
    * Check out [SealGW](https://git.ligo.org/spiir-group/SealGW)! 

