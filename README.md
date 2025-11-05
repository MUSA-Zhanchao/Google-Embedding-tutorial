# Google Embedding tutorial
**Zhanchao Yang**


## GIS day lightning talk for the University of Pennsylvania
11.19.2025

### Topic
Satellite and Population Embeddings: Powerful GeoAI Tools or Overrated?
### Abstract

In recent years, Google has introduced two powerful embedding for spatial analysis: satellite imagery embeddings, which capture visual and environmental patterns from overhead imagery, and population embeddings, which encode demographic and mobility information at high spatial resolutions. These embeddings promise to make geospatial machine learning more scalable, flexible, and transferable, but do they deliver? This talk will begin with an introduction to both embedding types, representation, and the types of spatial signals they capture. A short live demo will walk through two practical use cases: land use classification and estimating housing prices using these embeddings as inputs. These examples will illustrate the potential of embedding-based GeoAI to outperform traditional feature engineering. However, the talk will also highlight critical limitations: the opacity of learned representations, challenges in interpretability and validation, and the risk of reinforcing spatial and social biases. By the end, attendees will gain a clear understanding of both the capabilities and caveats of these embeddings, and when (or whether) they should be trusted in decision-making contexts.

## Type of Embedding
- PDFM Embedding
- Google Earth Embedding

Credit:
- [Dr. Qiusheng Wu PDFM tutorial](https://github.com/opengeos/GeoAI-Tutorials)
- [Dr. Qiusheng Wu Google Earth Embedding tutorial](https://leafmap.org/maplibre/AlphaEarth)
- [Google official JavaScript Satellite Embedding tutorial](https://developers.google.com/earth-engine/tutorials/community/satellite-embedding-02-unsupervised-classification)
- [Google PDFM Embedding](https://github.com/google-research/population-dynamics)
- [Google Earth Satellite Embedding](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_SATELLITE_EMBEDDING_V1_ANNUAL)

**ALL Exert or modify from original Repo, all rights reserved to the original author!**

## Population Dynamics Foundation Model (PDFM) Embeddings
PDFM Embeddings are condensed vector representations designed to encapsulate the complex, multidimensional interactions among human behaviors, environmental factors, and local contexts at specific locations. These embeddings capture patterns in aggregated data such as search trends, busyness trends, and environmental conditions (maps, air quality, temperature), providing a rich, location-specific snapshot of how populations engage with their surroundings. Aggregated over space and time, these embeddings ensure privacy while enabling nuanced spatial analysis and prediction for applications ranging from public health to socioeconomic modeling.

## Application

PDFM Embeddings can be applied to a wide range of geospatial prediction tasks, similar to census and socioeconomic statistics. Example use cases include:

- Population Health Outcomes: Predicting health statistics like disease prevalence or population health risks.
- Socioeconomic Factors: Modeling economic indicators and living conditions.
- Retail: Identifying promising locations for new stores, market expansion, and demand forecasting.
- Marketing and Sales: Characterizing high-performance regions and identifying similar areas to optimize marketing and sales efforts.

By incorporating spatial relationships and diverse feature types, these embeddings serve as a powerful tool for geospatial predictions.

## Google Earth Satellite Embeddings
