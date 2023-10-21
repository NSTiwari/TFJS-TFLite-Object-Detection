# Real-time Waste Detection on the browser using TFLite model
This repository is an implementation of object detection to detect waste in static and real-time directly on the browser using the TFJS-TFLite Web API.

## Implementation details:
The object detection model was trained on a custom dataset of different categories of waste – **open litter**, **plastic waste**, **biodegradable waste**, **medical waste**, and **overflowing dustbin**.

## Static Detection:


## Real-time Detection:
![GitHub Logo](real-time-waste-detection.gif)

Try a [LIVE demo](https://3dvlnp.csb.app/) on CodeSandbox.

## References:
[TF Lite Model Maker tutorial](https://www.tensorflow.org/lite/models/modify/model_maker): To train a custom object detection TF Lite model.
[TFJS-TFLite Task API](https://js.tensorflow.org/api_tflite/0.0.1-alpha.4/): To load the TF Lite model directly on the browser and do inferencing.
