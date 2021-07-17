# rapberry_pi_wheel_aarch64

dlib
mxnet
tensorflow
scikit-learn
scikit-image
ncnn
tflite_runtime
h5py
numpy

wheel files for raspberry pi 64 bit (aarch64)


mxnet requires (sudo apt install libopenblas-dev libopencv-dev libomp-dev). You maybe should do (export LD_LIBRARY_PATH=/usr/local/mxnet) to run your python script. I do it in one line e.g: (pi@raspberrypi: LD_LIBRARY_PATH=/usr/local/mxnet python3 my_script.py)
