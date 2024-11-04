# Sionna 0.19.0

## Installation
**!!! Native Windows Does Not Support NVIDIA GPU Acceleration !!!**  
Sionna requires Tensorflow>=2.13. However, starting in TF 2.11, CUDA build is not supported for Windows.

Possible Solution:
* Use Linux (Most convenient and recommanded!)
* Docker container (You may choose [NVIDIA official Docker](https://developer.nvidia.com/blog/nvidia-docker-gpu-server-application-deployment-made-easy/))
* Use earlier version of TF, which is not recommanded because of known, unpatched CVEs.
* Use WSL2 (WSL2 has CUDA supports, follow [Windows official instructions] (https://learn.microsoft.com/en-us/windows/ai/directml/gpu-cuda-in-wsl))

**!!!Strictly use [tested environment configuration](https://www.tensorflow.org/install/source_windows)!!!**
> And mismatch versions of TF, Python, CUDA, cDNN may cause enviroment error
> DO NOT change the launguage on TF official websites, any other lauguages except English could be outdated!!!

