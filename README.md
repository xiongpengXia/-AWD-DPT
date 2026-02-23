AWD-DPT is a novel deep learning model for multivariate time series forecasting that combines adaptive wavelet decomposition with a dual-path Transformer architecture. 
The model explicitly separates time series into high-frequency (spike) and low-frequency (trend/cycle) components and processes them through dedicated attention mechanisms: Spike Attention for transient patterns and Cycle Attention for periodic dependencies. 
The framework also incorporates RevIN (Reversible Instance Normalization) and a Dimension-Wise Fusion layer to achieve state-of-the-art performance on benchmark datasets.
