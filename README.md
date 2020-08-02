# Chapter-4-Working-with-Keras
Source code for the case studies in Springer Book Chapter 4. Working with Keras

A GPU version of tensorflow has to be installed. Install the CUDA toolkit downloaded from https://developer.nvidia.com/cuda-toolkit. 
After installing the CUDA toolkit, download the CUDA deep learning toolkit from https://developer.nvidia.com/rdp/cudnn-archive/a-collapse714-9 .

The cuDNN library has three files: \bin\cudnn65_7.dll (version number may be different), \include\cudnn.h\ and \lib\x64\cudnn.lib\ . These files should be copied to the following locations 
%CUDA installation directory%\bin\cudnn65_7.dll
%CUDA installation directory%\include\cudnn.h\
%CUDA installation directory%\lib\x64\cudnn.lib\

By default %CUDA installation directory% points to C:\Program Files\NIVIDIA GPU Computing Toolkit\CUDA\v9.0

Add the following entries in Environment Variables > System variables > Path:

C:\Program Files\NIVIDIA GPU Computing Toolkit\CUDA\v9.0\libnvvp
C:\Program Files\NIVIDIA GPU Computing Toolkit\CUDA\v9.0\bin
C:\Program Files\NIVIDIA GPU Computing Toolkit\CUDA\v9.0\lib\x64

The demonstration of case studies given in the chapter 4. Working with Keras are provided in this repository as Jupyter Notebooks. These source codes are executable in any platform like Google Colab, Kaggle Notebooks and Jupyter Lab in Conda platforms.
