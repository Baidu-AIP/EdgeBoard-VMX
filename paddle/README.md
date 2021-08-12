# PaddlePaddle Model Support

Currently, we can support deploy PaddlePaddle model by OpenVINO, the whole process can be summary as the following 2 steps

1. Get a PaddlePaddle model, which is exported as inference model, contains `mymodel.pdmodel` and `mymodel.pdiparams`
2. Export PaddlePaddle model to ONNX format by [Paddle2ONNX](https://github.com/PaddlePaddle/Paddle2ONNX.git)
3. Export ONNX model to OpenVINO IR

Refer to [Paddle2ONNX](https://github.com/PaddlePaddle/Paddle2ONNX.git) for more details.

Also, PaddleX has provided C++ codes support deploy PaddlePaddle model by OpenVINO, the following documents shows how to deploy PaddleX model

- [Deploy PaddleX by OpenVINO](https://paddlex.readthedocs.io/zh_CN/release-1.3/deploy/openvino/index.html)
