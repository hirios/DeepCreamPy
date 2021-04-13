# DeepCreamPy
*Decensoring Images with Deep Neural Networks. Formerly named DeepMindBreak.*


I looked for the DeepCreamPy binary for windows and didn't find it. So I did a fork and decided to compile. Here is the result

https://drive.google.com/file/d/1cdisrH_QTsfyd9g_PwRzvONChjVwlMrC


Obs1: To use the script, I had to use Python 3.6
Obs2: This version include the model 

# INSTALL
```
pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.10.0-py3-none-any.whl
pip install -r requirements.exe
```
</br>

**CPUs that don’t support AVX instructions may experience this error when using the above install instructions:**

Download a version of tensorflow that does not support AVX instructions from (https://github.com/fo40225/tensorflow-windows-wheel/tree/master/1.10.0/py36/CPU/sse2). I assume you picked tensorflow-1.10.0-cp36-cp36m-win_amd64.whl for 64-bit and the other for 32-bit computers

Open the command line in the same directory as the file downloaded and run:

```
$ pip uninstall tensorflor 
$ pip install tensorflow-1.10.0-cp36-cp36m-win_amd64.whl

or

$ pip uninstall tensorflor 
$ pip install tensorflow-1.10.0-cp36-cp36m-win32.whl
```
