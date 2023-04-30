# Histogramo Cities and Knights Model

Six-sided dice of different colors taken on different backgrounds (wood table, green felt craps mat, white conference table) from a variety of distances and angles (top-down and oblique). Each image contains only one die. Also includes the Cities and Knights Boat Die (`boat `, `green`, `yellow`, and `blue` labels).

## Model File

[https://github.com/histogramo/dice-model-zoo/blob/main/histogramo-cities-and-knights/histogramo-cities-and-knights.tflite](https://github.com/histogramo/dice-model-zoo/blob/main/histogramo-cities-and-knights/histogramo-cities-and-knights.tflite)

## Dataset

- **Target:** d6 dice, different colors (white, black, red, blue, yellow, green), cities and knights boat die
- **View:** top-down and oblique angles
- **Dataset:** Unavailable
- **Dataset Size**: 3009 images

## Labels

- `one`: 339
- `two`: 337
- `three`: 337
- `four`: 338
- `five`: 339
- `six`: 337
- `red_one`: 106
- `red_two`: 103
- `red_three`: 105
- `red_four`: 110
- `red_five`: 110
- `red_six`: 110
- `boat`: 140
- `green`: 65
- `yellow`: 66
- `blue`: 67

## Model

**Training Process:** Transfer Learning using [ssd_mobilenet_v1_quantized_300x300_coco14_sync_2018_07_18](http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v1_quantized_300x300_coco14_sync_2018_07_18.tar.gz), following the [Real-time dice detection and classification tutorial by Nell Byler](https://github.com/nell-byler/dice_detection)
