# Waste Detection on the browser using TFLite model
As an initiative to solve for environment, this project is an implementation of detecting various categories of waste in real-time by deploying a TF Lite model directly on the browser using the TFJS-TFLite API.

## Implementation details:
The object detection model was trained on a custom dataset of different categories of waste – **open litter**, **plastic waste**, **biodegradable waste**, **medical waste**, and **overflowing dustbin**.

## Steps to run:

1. Clone the repository on your local machine.
  
2. For static detection, navigate to the directory ```cd Static Detection```; for real-time detection, navigate to the directory ```cd Real-time Detection```.
 
3. Open your terminal/command prompt and enter the command ```py -m http.server``` (if you have Python installed) to create a local server.
   
4. Open your web browser, and go to ```localhost:8000```.

## Static Detection:
![GitHub Logo](static-detection.gif)

## Real-time Detection:
![GitHub Logo](real-time-waste-detection.gif)

- Try a [LIVE demo](https://3dvlnp.csb.app/) on CodeSandbox.
- Read the [Medium](https://tiwarinitin1999.medium.com/ml-story-machine-learning-on-the-browser-tf-lite-meets-tf-js-fafc391fed09) blog for technical details. 

## References:
- [TF Lite Model Maker tutorial](https://www.tensorflow.org/lite/models/modify/model_maker): To train a custom object detection TF Lite model.
- [TFJS-TFLite Task API](https://js.tensorflow.org/api_tflite/0.0.1-alpha.4/): To load the TF Lite model directly on the browser and do inferencing.
