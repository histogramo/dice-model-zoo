# 🎲 [Histogramo](https://www.histogramo.com) Dice Model Zoo

A collection of TensorFlow Lite Object Detection models that recognize dice. All models are supported by the [Histogramo](https://www.histogramo.com) app and will collect dice statistics on the dice the models are trained to recognize. Model files are provided in the TensorFlow Lite FlatBuffers format (.tflite).

## Available Models

- [Histogramo Standard](https://github.com/histogramo/dice-model-zoo/tree/main/histogramo-standard)
- [Histogramo Cities and Knights](https://github.com/histogramo/dice-model-zoo/tree/main/histogramo-cities-and-knights)
- [Byler D6 Dice](https://github.com/histogramo/dice-model-zoo/tree/main/byler-d6-dice)

## Supported Labels

While [Histogramo](https://www.histogramo.com) can load any TensorFlow Lite object detection model, it only supports the following labels for recognizing dice:

- `one`
- `two`
- `three`
- `four`
- `five`
- `six`

For Cities and Knights, [Histogramo](https://www.histogramo.com) can distinguish red die and also the special "boat" die used for events:

- `red_one`
- `red_two`
- `red_three`
- `red_four`
- `red_five`
- `red_six`
- `boat`
- `green`
- `yellow`
- `blue`

# Contributions

We invite you to make and submit your own dice detection model. The model should be a TensorFlow Lite Object Detection model trained with the supported labels.

1. Fork the Repository: Fork the repository to your GitHub account so that you can make changes to it without affecting the original repository.

1. Clone the Repository: Clone the repository to your local machine using git clone https://github.com/your-username/dice-model-zoo.git

1. Create a New Branch: Create a new branch in which you will make your changes using git checkout -b branch-name.

1. Make Changes: Make changes to the code and/or documentation in the repository. Ensure that your changes follow the coding style and conventions used in the project.

1. Test Changes: Test your changes thoroughly to ensure they are functioning as expected.

1. Commit Changes: Commit your changes to your local repository using git commit -m "Your commit message here".

1. Push Changes: Push your changes to your forked repository using git push origin branch-name.

1. Create Pull Request: Navigate to the original repository and create a pull request from your forked repository's branch to the original repository's branch. Be sure to include a detailed description of the changes you made and why they are necessary.

1. Wait for Review: Wait for feedback from the repository maintainers and make any requested changes.

1. Merge Changes: Once your changes have been approved, they will be merged into the original repository.

Remember to be respectful and professional in your interactions with other contributors and maintainers. Happy contributing!

# License

Models in this repository are available for use under the [MIT license](https://github.com/histogramo/dice-model-zoo/blob/main/LICENSE).
