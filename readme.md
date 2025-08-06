### 🐱 Purr Price Prediction

A deep learning project that predicts the price of a virtual cat (CryptoKitty) from its image and metadata. Developed for the blog post [**Cryptokitties Price Prediction**](https://medium.com/intuition/cryptokitties-price-prediction-51e1b3a9eb09).

The method used is regression on images.

The dataset is from [here](https://www.kaggle.com/competitions/how-much-would-you-pay-for-a-fake-cat/overview).


### Model

- **Library**: [FastAI](https://docs.fast.ai/)
- **NN** used: `resnet34` or `densenet121`
- **Loss Function**: `MSELossFlat`
- **Metric**: Root Mean Squared Error (`rmse`)
- **Transforms**:
  - Resize to `224x224`
  - Mixed precision training
  - Gradient clipping
- **Batch Size**: 16
