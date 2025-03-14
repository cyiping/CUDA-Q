# Running CUDA-Q on [Colab](https://colab.research.google.com/)

**Learn more about [CUDA-Q](https://developer.nvidia.com/cuda-q) with NVIDIA official [GitHub](https://github.com/NVIDIA/cuda-quantum/), then follow the steps below to run cudaq with free NVIDIA T4 GPU on Colab:**
<br>
<br>
**Step 1. Make sure to select `Edit > Notebook settings > T4 GPU` as the backend for acceleration**
<br>
<br>
<img src="https://github.com/Squirtle007/CUDA-Q/assets/66664309/9d804b43-e56b-489f-a267-395411ed014c" width="800">
<br>
<br>
<img src="https://github.com/Squirtle007/CUDA-Q/assets/66664309/d00f3c60-960b-4ad1-a7d5-fc55d48e4fb4" width="450">
<br>
<br>
<br>
**Step 2. Install cudaq via [PyPI](https://pypi.org/project/cudaq/) at the very beginning to set up CUDA-Q in the Colab environment.**
<br>
<br>
Version `0.8.0` as an example: 
```
%pip install cudaq==0.9.1
```

For versions earlier than v0.9.0, use the package name `cuda-quantum`:
```
%pip install cuda-quantum==0.8.0
```
<br>
<br>

Note: Running the tutorials in the CUDA-Q container (download from [NGC](https://catalog.ngc.nvidia.com/)) with the corresponding version `X.X.X` or `latest` is highly recommended. Please follow the [instruction guide](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/quantum/containers/cuda-quantum).
