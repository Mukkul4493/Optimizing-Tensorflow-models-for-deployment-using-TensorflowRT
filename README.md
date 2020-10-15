# Optimizing-Tensorflow-models-for-deployment-using-TensorflowRT

Through this Python notebook, you will be able tounderstand how to optimize Tensorflow models using the TensorFlow integration of NVIDIA's TensorRT (TF-TRT), use TF-TRT to optimize several deep learning models at FP32, FP16, and INT8 precision, and observe how tuning TF-TRT parameters affects performance and inference throughput.

I learnt this project through Coursera and this is my version of the course project.
In this project we started out by looking at the benchmarking performances, throughput and latency for just an average tensorflow model that has not been quantized or opitmized, 
and then we went through the process of creating Tensorflow TensorRT Optimised Graph for various precision modes including FP32, FP16 and also INT8 
along with understanding how INT8 Quantization is performed and then understanding the implementation difference between FP16, FP32 and INT8 
which is if you're creating an INT8 Qauntized model you need to perform one additional step which is to feed it calibration data. 
We were able to quantify model speed and throughput increase singificance after quantization without affecting the model's accuracy much.

There are several links in the Python notebook that will help us understand how these optimizations work under the hood. 
But majorly, all the information required is present in the notebook and here: https://docs.nvidia.com/deeplearning/frameworks/tf-trt-user-guide/index.html
