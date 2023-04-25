# Parallel programming workshop

This workshop is an intro into parallel computing - more specifically computing on graphics processing units.

Framework that is used in this workshop is [OpenCL](https://en.wikipedia.org/wiki/OpenCL) and runtime part (code that is run on host system)</br>is demonstrated in Python using [PyOpenCL](https://documen.tician.de/pyopencl/) library which is a wrapper around runtime API.

Each Jupyter notebook is intended to be run on [Google Colab](https://colab.research.google.com/) or [Kaggle](https://www.kaggle.com/). These platforms should provide VM instance with GPU and out-of-the-box configured drivers. Notebooks have been tested and are guaranteed to work with **OpenCL 1.1** and **PyOpenCL 2022.3.1**

## Sources

- [PyOpenCL](https://documen.tician.de/pyopencl/)
- [OpenCL 1.1 Specification](https://registry.khronos.org/OpenCL/specs/opencl-1.1.pdf)