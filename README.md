## Hands-on material to support teaching of AI Systems Engineering

#### Supported by the BMBF funded Artifical Intelligence Systems Engineering Laboratory (AISEL) project  <img src="pics/BMBF_gefoerdert_2017_en.jpg" width="120">



## Goal
This material supports teaching efforts at the master level for future AI System Engineers to build safe and certifiable systems. 
It covers basics on probability theory, probabilistic model-building, simulation, robust modules, uncertainty propagation, automatic differentation, deep probabilistic frameworks as well as privacy measures and basics for affective AI. It complements existing courses on machine learning and system and software engineering. 



## Contents
<!---
### Basics of probability theory and random variables

#### Experiments, Sample Spaces, and Events
#### Probability Axioms 
#### Computing Probabilities 
#### Conditional Probability
#### Rule of Bayes 
#### Discrete Random Variables 
#### Continuous Random Variables  
#### Expectiation Values
#### Common Discrete Distributions
#### Maximum likelihood estimation

### Uncertainty Propagation 

####	Covariance propagation
####	Statistical and systematic uncertainty estimates in probability theory
####	Aleatoric and epistemic uncertainty in statistical machine learning
####	A comparison of uncertainty on estimates vs uncertainty from data

###	Automatic differentiation

###	Probabilistic Programming Frameworks
--->

###	Privacy By Design
#### [General privacy measures](notebooks/privacy_metrics.ipynb)
#### [Differential privacy](notebooks/diffpriv.ipynb)
<!---
###	Affective AI / Human-AI interaction:
####	World modelling and Simulation in Human-AI Systems
####	Emotion estimation techniques
--->
###	Sensor Modelling
####	[Vision: Camera noise model](notebooks/NoiseModel.ipynb) 
####	[Vision: Statistical calibration of CCD imaging process](notebooks/ImageCalibration.ipynb) 

### Robust estimates example - Pedestrian Tracker
A pedestrian tracker example is used to demonstrates the workflow for robust change detection and quantitiave model-based performance measures. Especially the expected performance of a system and the assumptions that are made are highlighted.

1. [Intro & Illumination invariant measure](notebooks/PedestrianDetector-IlluminInvMeasure.ipynb)
2. [Background model in stationary environments and color based change detection](notebooks/PedestrianDetector-BackgroundModel.ipynb)
3. [Indexing function to prepare Hypothesis Testing](notebooks/PedestrianDetector-IndexingHypoGen.ipynb)
4. [Feature for Pedestrian Detection](notebooks/PedestrianDetector-FeatureGenPedEstimation.ipynb)
