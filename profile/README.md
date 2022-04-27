# [CropMOSAIKS:](https://bren.ucsb.edu/projects/open-source-pipeline-remote-sensing-crop-yields-under-environmental-change-sub-saharan) An Open Source Pipeline for Remote Sensing of Crop Yields Under Environmental Change in Sub-Saharan Africa

## Purpose

This GitHub organization hosts the code and documentation used in a Capstone Project for the Masters of Environmental Data Science program at the Bren School of Environmental Science and Management, University of California Santa Barbara. This project intends to adapt, extend, and apply the MOSAIKS framework described in [Rolf et al. 2021](https://www.nature.com/articles/s41467-021-24638-z) to encode monthly imagery from the Landsat 8 and Sentinel 2 satellite missions through random convolutional features over the years 2013 - 2019. Because these features were produced using an _unsupervised_ machine learning approach, they are task-agnostic and therefore "random". This allows them to be geospatially joined to other data to answer a plethora of questions. In this environmental application of the MOSAIKS approach, these features are geospatially matched to crop yields in Zambia and a model is trained on this merged data using a _supervised_ machine learning approach. Our model is optimized for this specific task through systematically comparing model perfomance for various temporal subsetting by month, spectral band combinations, spatially masking for cropland, interpolation approaches, and statistical analysis. The optimized model is then applied to predict crop yields for this region for subsequent years in which Zambia lacks crop yield data: 2020 - 2021. This project is limited by data availability and is restricted to the country of Zambia.

## What is here?

This organization hosts several repositories including the main two, [Featurization](https://github.com/cropmosaiks/Featurization) and [Modeling](https://github.com/cropmosaiks/Modeling). Both repositories have independent README's that provide detailed explanations of their notebooks, data sources, and file organization. 

## Contributing

This project was completed on June 9th, 2022, but suggestions for improvements to the code or documentation is welcome and encouraged. Please submit questions, comments, or code via issues or pull requests on either of the repositories. To correspond with the data scientists who produced these materials, please see their personal GitHub accounts listed below and feel free to contact them via email:

[Grace Lewin](https://github.com/gracelewin)\
[Cullen Molitor](https://github.com/cullen-molitor)\
[Steven Cognac](https://github.com/cognack)\
[Juliet Cohen](https://github.com/julietcohen)

For rules and regulations for this organization, please see the [Code of Conduct](https://github.com/cropmosaiks/.github/blob/main/CODE_OF_CONDUCT.md)
