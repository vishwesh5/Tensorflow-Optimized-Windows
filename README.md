# Tensorflow-Optimized-Windows
Installation instructions for optimized tensorflow for windows (GPU+AVX+AVX2)

## Requirements

- Install [MSYS2 Shell](http://repo.msys2.org/distrib/x86_64/msys2-x86_64-20180531.exe)
- MS VS 2015

## Install Package Dependencies

```
pip3 install six numpy wheel
pip3 install keras_applications==1.0.6 --no-deps
pip3 install keras_preprocessing==1.0.5 --no-deps
```

## Install Bazel

Download bazel from [https://github.com/bazelbuild/bazel/releases/download/0.24.1/bazel-0.24.1-windows-x86_64.exe](https://github.com/bazelbuild/bazel/releases/download/0.24.1/bazel-0.24.1-windows-x86_64.exe)

Rename this to **bazel.exe** and add it to `C:\bazel` 
