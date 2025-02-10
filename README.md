# Generative Machine Learning in Atmospheric Models
## Abstract
This project investigates the use of generative machine learning in atmospheric
modelling to improve the representation of uncertainties associated with sub-grid scale
processes in its vertical structure. Atmospheric models, essential for accurate weather
predictions, often struggle to detail the complex physical processes that occur at scales
smaller than the model grid resolution. Traditional parameterisation methods assume a
uniform distribution in its vertical structure that may not accurately reflect the
stochastic nature of these processes across different vertical levels. In this research,
denoising diffusion probabilistic models (DDPMs) are applied to learn atmospheric
profiles in its vertical structure . By training with historical data from the Met Office, the
models learn to generate plausible outcomes for sub-grid processes based on observed
conditions in the larger-scale data. The results indicate that diffusion models perform
well in learning the probabilistic nature of sub-grid processes. However, the substantial
computational requirements for training and deploying these models pose challenges,
particularly for operational uses where rapid processing is essential. This work could
potentially contribute to the integration of generative machine learning into existing
paramaterisation schemes. Future research will aim to optimise the computational
efficiency of these models and assess their practical application. The full report can be found [here] (https://github.com/Varsh-t/generative-ml-atmospheric-models/blob/main/Generative%20ML%20in%20Atmospheric%20Models.pdf). 
Note that the code can be used to explore methods but does not contain any real data as this confidential.



