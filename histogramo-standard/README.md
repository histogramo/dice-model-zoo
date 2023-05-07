# [Histogramo](https://www.histogramo.com) Standard Model

Six-sided dice of different colors taken on different backgrounds (wood table, green felt craps mat, white conference table) from a variety of distances and angles (top-down and oblique). Each image contains only one die.

## Model File

[https://github.com/histogramo/dice-model-zoo/blob/main/histogramo-standard/histogramo-standard.tflite](https://github.com/histogramo/dice-model-zoo/blob/main/histogramo-standard/histogramo-standard.tflite)

## Dataset

- **Target:** d6 dice, different colors (white, black, red, blue, yellow, green)
- **View:** top-down and oblique angles
- **Dataset:** Unavailable
- **Dataset Size**: 2671 images

## Labels

- `one`: 445
- `two`: 447
- `three`: 442
- `four`: 441
- `five`: 449
- `six`: 447

## Model

**Training Process:** Transfer Learning using [ssd_mobilenet_v1_quantized_300x300_coco14_sync_2018_07_18](http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_quantized_300x300_coco14_sync_2018_07_18.tar.gz), following the [Real-time dice detection and classification tutorial by Nell Byler](https://github.com/nell-byler/dice_detection)
