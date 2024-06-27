---
description: >-
  Resources related to HCTSA including talks/demos, workflow examples and
  related packages.
cover: >-
  https://images.unsplash.com/photo-1530811761207-8d9d22f0a141?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw0fHx0YWxrfGVufDB8fHx8MTcxNTU3MDc4Mnww&ixlib=rb-4.0.3&q=85
coverY: -139
---

# Related Time-Series Resources - collection of code and utilities that may be useful now or in the future

A collection of good resources for time-series analysis (including in other programming languages like python and R) are listed here. See also larger collections of time-series resources, by [Lukasz Mentel](https://github.com/lmmentel/awesome-time-series) and, focused on python: [Max Christ](https://github.com/MaxBenChrist/awesome\_time\_series\_in\_python).

### Time-Series Data - downloadable 'public' access data sources for time series work

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="http://www.comp-engine.org/"><code>CompEngine</code></a></td><td>Accompanying web resource that provides a self-organising database of time-series data. It allows users to upload, explore, and compare thousands of different types of time-series data. </td><td><a href="http://www.comp-engine.org/">http://www.comp-engine.org/</a></td></tr><tr><td align="center"><a href="https://github.com/DynamicsAndNeuralSystems/pyspi"><code>pyspi</code></a></td><td><em>pyspi</em> is a comprehensive python library for computing hundreds of statistics of pairwise interactions (SPIs) directly from multivariate time series (MTS) data.</td><td><a href="https://github.com/DynamicsAndNeuralSystems/pyspi">https://github.com/DynamicsAndNeuralSystems/pyspi</a></td></tr></tbody></table>

### Feature sets derived from hctsa

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="https://github.com/DynamicsAndNeuralSystems/catch22"><code>catch22</code></a></td><td>This reduced set of 22 features, determined through a combination of classification performance (across 93 problems) and mutual redundancy (as explained in <a href="https://doi.org/10.1007/s10618-019-00647-x">this 📗 paper</a>), is available <a href="https://github.com/DynamicsAndNeuralSystems/catch22">here</a> as an efficiently coded C implementation.</td><td><a href="https://github.com/DynamicsAndNeuralSystems/catch22">https://github.com/DynamicsAndNeuralSystems/catch22</a></td></tr><tr><td align="center"><a href="https://github.com/DynamicsAndNeuralSystems/catchaMouse16"><code>catchamouse16</code></a></td><td>A reduced set of 16 features (trained on mouse fMRI data), coded in C with wrappers for use in python, R, etc.</td><td><a href="https://github.com/DynamicsAndNeuralSystems/catchaMouse16">https://github.com/DynamicsAndNeuralSystems/catchaMouse16</a></td></tr></tbody></table>

### hctsa

<table data-view="cards"><thead><tr><th align="center"></th><th align="center"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="https://github.com/brendanjohnharris/Autohctsa"><code>autohctsa</code></a></td><td align="center">Provides code for setting a <em>hctsa</em> feature-extraction job running on a computing cluster without leaving your local machine (with associated Julia helper code).</td><td><a href="https://github.com/brendanjohnharris/Autohctsa">https://github.com/brendanjohnharris/Autohctsa</a></td></tr><tr><td align="center"><a href="https://github.com/benfulcher/distributed_hctsa"><code>distributedhctsa</code></a></td><td align="center">Provides MATLAB code for distributing <em>hctsa</em> calculations across nodes of a computing cluster (using pbs or slurm schedulers).</td><td><a href="https://github.com/benfulcher/distributed_hctsa">https://github.com/benfulcher/distributed_hctsa</a></td></tr><tr><td align="center"><a href="https://github.com/benfulcher/CandidateFeatureLab"><code>Candidate Feature Lab</code></a></td><td align="center">A repository for testing new time-series analysis algorithms for redundancy (and assessing whether to include into <em>hctsa</em>).</td><td><a href="https://github.com/benfulcher/CandidateFeatureLab">https://github.com/benfulcher/CandidateFeatureLab</a></td></tr><tr><td align="center"><a href="https://github.com/fairscape/hctsa-py"><code>hctsa-py</code></a></td><td align="center">A work in progress to recode many <em>hctsa</em> time-series analysis features into native python code.</td><td><a href="https://github.com/fairscape/hctsa-py">https://github.com/fairscape/hctsa-py</a></td></tr><tr><td align="center"><a href="https://github.com/strawlab/pyopy"><code>pyopy</code></a></td><td align="center">This excellent repository allows users to run <em>hctsa</em> software from within python.</td><td><a href="https://github.com/strawlab/pyopy">https://github.com/strawlab/pyopy</a></td></tr><tr><td align="center"><a href="https://github.com/benfulcher/hctsaAnalysisPython"><code>hctsaAnalysisPython</code></a></td><td align="center">Some preliminary python code for analyzing the results of <em>hctsa</em> calculations.</td><td><a href="https://github.com/benfulcher/hctsaAnalysisPython">https://github.com/benfulcher/hctsaAnalysisPython</a></td></tr></tbody></table>

### Feature-based time-series packages developed by others

There is a list of python-based packages for time-series analysis [here](https://github.com/MaxBenChrist/awesome\_time\_series\_in\_python) that is worth taking a look at, in addition to those packages highlighted below:

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="https://github.com/blue-yonder/tsfresh"><code>tsfresh</code></a></td><td>Native python time-series code to extract hundreds of time-series features, with in-built feature filtering. See the <a href="https://www.sciencedirect.com/science/article/pii/S0925231218304843">paper</a>.</td><td><a href="https://github.com/blue-yonder/tsfresh">https://github.com/blue-yonder/tsfresh</a></td></tr><tr><td align="center"><a href="https://github.com/facebookresearch/kats"><code>Kats</code></a></td><td><code>Kats</code> is a toolkit for analysing time-series data in python, and includes basic feature extraction functionality.</td><td><a href="https://github.com/facebookresearch/kats">https://github.com/facebookresearch/kats</a></td></tr><tr><td align="center"><a href="https://github.com/hendersontrent/theft"><code>theft</code></a></td><td><code>theft</code> (Tools for Handling Extraction of Features from Time series) allows users to compute various open time-series features sets and contains associated tools for visualising and analysing the results.</td><td><a href="https://github.com/hendersontrent/theft">https://github.com/hendersontrent/theft</a></td></tr><tr><td align="center"><a href="https://github.com/fraunhoferportugal/tsfel"><code>TSFEL</code></a></td><td><code>TSFEL</code>, 'Time Series Feature Extraction Library', is a python package with implementations of 60 simple time-series features (with unit tests).</td><td><a href="https://github.com/fraunhoferportugal/tsfel">https://github.com/fraunhoferportugal/tsfel</a></td></tr><tr><td align="center"><a href="https://github.com/predict-idlab/tsflex"><code>tsflex</code></a></td><td>A flexible and efficient toolkit for flexible time-series processing &#x26; feature extraction, that makes minimal assumptions about sequential data. Includes support for a range of feature sets, including tsfresh, catch22, TSFEL, and Kats.</td><td><a href="https://github.com/predict-idlab/tsflex">https://github.com/predict-idlab/tsflex</a></td></tr><tr><td align="center"><a href="https://github.com/neuropsychology/NeuroKit"><code>NeuroKit</code></a></td><td>Includes a wide range of useful signal processing tools (like power spectral densities, detrending and bandpass filtering, and empirical mode decomposition). It also includes estimation of complexity parameters (many entropies and correlation dimensions, see part of readme <a href="https://github.com/neuropsychology/NeuroKit#complexity-entropy-fractal-dimensions-">here</a>) as well as detrended fluctuation analysis.</td><td><a href="https://github.com/neuropsychology/NeuroKit">https://github.com/neuropsychology/NeuroKit</a></td></tr><tr><td align="center"><a href="https://github.com/robjhyndman/tscompdata"><code>tscompdata</code></a></td><td>Makes available existing collections of time-series data for analysis.</td><td><a href="https://github.com/robjhyndman/tscompdata">https://github.com/robjhyndman/tscompdata</a></td></tr><tr><td align="center"><a href="https://github.com/robjhyndman/tsfeatures"><code>tsfeatures</code></a></td><td>Includes implementations of a range of time-series features.</td><td><a href="https://github.com/robjhyndman/tsfeatures">https://github.com/robjhyndman/tsfeatures</a></td></tr><tr><td align="center"><a href="https://feasts.tidyverts.org/"><code>feasts</code></a></td><td>Provides a collection of tools for the analysis of tidy time-series data represented as a <a href="https://tsibble.tidyverts.org/">tsibble</a>.</td><td><a href="https://feasts.tidyverts.org/">https://feasts.tidyverts.org/</a></td></tr></tbody></table>

### Other packages and resources

<table data-view="cards"><thead><tr><th align="center"></th><th></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><a href="https://sktime.org/"><code>sktime</code></a></td><td>A unified framework for machine learning with time series.</td><td><a href="https://sktime.org">https://sktime.org</a></td></tr><tr><td align="center"><a href="https://github.com/shapelets/khiva"><code>Khiva</code></a></td><td>An open-source library of efficient algorithms to analyse time series using GPU and CPU.</td><td><a href="https://github.com/shapelets/khiva">https://github.com/shapelets/khiva</a></td></tr><tr><td align="center"><a href="https://github.com/pik-copan/pyunicorn"><code>pyunicorn</code></a></td><td>A python-based nonlinear time-series analysis and complex systems code package. See this <a href="http://scitation.aip.org/content/aip/journal/chaos/25/11/10.1063/1.4934554">publication</a>.</td><td><a href="https://github.com/pik-copan/pyunicorn">https://github.com/pik-copan/pyunicorn</a></td></tr><tr><td align="center"><a href="https://github.com/tslearn-team/tslearn"><code>tslearn</code></a></td><td>A python package for performing machine learning using time-series data, including loading datasets from the UCR/UAE repository.</td><td><a href="https://github.com/tslearn-team/tslearn">https://github.com/tslearn-team/tslearn</a></td></tr><tr><td align="center"><a href="https://github.com/arnedb/tsfuse"><code>TSFuse</code></a></td><td>A python package that can extract features from multivariate time series.</td><td><a href="https://github.com/arnedb/tsfuse">https://github.com/arnedb/tsfuse</a></td></tr></tbody></table>

***
