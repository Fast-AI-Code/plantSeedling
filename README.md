## Plant seedling Classification

## Networks (Results)
- resnet34 pretrained + adamW+ wd = 1e-3
    - 88.1 % but overfit
- vgg16bn pretrained + adamW+ wd = 1e-3
    - 94 % but underfit
- vgg19bn pretrained + adamW+ wd = 1e-3 + oversample +mixup
    - 95%+ but underfit a bit

## Conclusion
- oversampling helps
- mixup is beauty