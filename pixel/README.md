## Dependencies and Installation

- Following [Spa-GAN](https://github.com/Penn000/SpA-GAN_for_cloud_removal)

## Train

```bash
# run train_woGAN_2.py for dataset with sar
python train_woGAN_2.py

## Inference

Download the pixel models [[Baidu Drive](https://pan.baidu.com/s/1EsbT-3bQKbBug7LPshAnnw)] (code:1234) and run the inference code.

```bash
# for sar
python predict_2.py
```

## SAR-F

```bash
# SAR-Fusion
python mixup.py
```

