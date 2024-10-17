#Inference Times:
* PyTorch Inference Time: 0.011577 seconds
* ONNX Inference Time: 0.035591 seconds
* TensorRT Inference Time: 0.001370 seconds
#Max and Mean Differences in Outputs (compared to PyTorch):
ONNX Model:
* Max difference: 6.67572021484375e-06
* Mean difference: 1.3396246458796668e-06
* TensorRT Model:
* Max difference: 5.7220458984375e-06
* Mean difference: 1.3225153452367522e-06
#Performance:
TensorRT is the fastest, with an inference time of 0.001370 seconds, roughly 8.4 times faster than PyTorch and about 26 times faster than ONNX.
PyTorch is faster than ONNX, but still slower than TensorRT.
Accuracy:
The differences in output between the models are minimal, indicating that both ONNX and TensorRT models provide results very close to the original PyTorch model. The accuracy is well-preserved during conversion.
