# tensorflow-wheel-ubuntu-gtx1070

Tensorflow wheel package built for ubuntu 16.04, pascal gpu nvidia gtx 1070/1080 Cuda 8.0

After installing Nvidia drivers, cuda and cudnn.

Install tensorflow by cloning the repository.

```
git clone https://github.com/anandanand84/tensorflow-wheel-ubuntu-gtx1070.git
cd tensorflow-wheel-ubuntu-gtx1070
sudo pip install tensorflow-0.10.0rc0-py2-none-any.whl
```

# Build Parameters.


Nvidia driver      - 367.35
Tensorflow         - 0.6.0-6552-g83fe2a5 (https://github.com/tensorflow/tensorflow/commit/83fe2a5b7328e1b754b53cbbcf9b313450a2f863)
Ubuntu             - 16.04
Cuda               - 8.0.26
Compute capability - 6.1
bazel version      - 0.3.0
GCC Version        - 4.9.3


