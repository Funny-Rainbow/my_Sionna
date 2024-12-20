# Sionna 0.19.0

## Installation
**!!! Native Windows Does Not Support NVIDIA GPU Acceleration !!!**  
Sionna requires Tensorflow>=2.13. However, starting in TF 2.11, CUDA build is not supported for Windows.
>If you want to use CPU environment on Windows, you need to install LLVM >= 11.0 (Latest version does not work for me, try 18.1.6)

Possible Solution:
* Use Linux (Most convenient and recommanded!)
* Use WSL2 (WSL2 has CUDA supports, follow [Windows official instructions](https://learn.microsoft.com/en-us/windows/ai/directml/gpu-cuda-in-wsl))
* Docker container (You may choose [NVIDIA official Docker](https://developer.nvidia.com/blog/nvidia-docker-gpu-server-application-deployment-made-easy/))
* Use earlier version of TF, which is not recommanded because of known, unpatched CVEs.

**!!!Strictly use [tested environment configuration](https://www.tensorflow.org/install/source_windows)!!!**
> Any mismatch versions of TF, Python, CUDA, cuDNN may cause enviroment error  
> DO NOT change the launguage on TF official websites, any other lauguages except English could be outdated!!!

(2024/Nov.)
