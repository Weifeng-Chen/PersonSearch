# Contrastive Transformer Learning with Proximity Data Generation for Text-Based Person Search

Official code for "Contrastive Transformer Learning with Proximity Data Generation for Text-Based Person Search"

## Pretrained Model
Put VIT `vit_base_patch16_384.pth` into `models/`.
Download from [Google Drive](https://drive.google.com/file/d/1b7p3SsG7L7LPFrChc1Jx8X94YnLIH00X/view?usp=sharing).

## Dataset
```
dataset/
└── CUHK-PEDES
    ├── annotations
    └── imgs
        ├── cam_a
        ├── cam_b
        ├── CUHK01
        ├── CUHK03
        ├── Market
        ├── test_query
        └── train_query
```
## Training + Testing 
```
bash run.sh
```

## Log
