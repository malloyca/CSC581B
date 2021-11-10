# Plans for CSC581B project

## Four project parts:
1. Linear classfier
2. Convolutional Neural Net
3. Not sure yet...
   - Inception
   - ResNet 
4. Also not sure yet
   - Transformer
   - GAN
   - EfficientNet
   - Knowledge distillation

# To explore

- Add in standardization
  - data /= np.mean()
  - data /= np.std()
- Label smoothing
  - This is built into Torch's `CrossEntropyLoss` so it's easy to implement
- VGG-16
- Knowledge distillation
- Batch normalization
- Dropout
- LR scheduling
- Momentum?
- L2 reg
