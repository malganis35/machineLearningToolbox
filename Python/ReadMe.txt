General website : https://www.python.org/
Introduction to Python (French) : https://openclassrooms.com/courses/apprenez-a-programmer-en-python

Installing Python 3.6 (for windows):
https://www.python.org/downloads/ -> Python 3.6.0 (32-bit)

Make sure to check "Add to environment variables".

If it's installed correctly you shouuld be able to open a command prompt and type "python".

Installing Opencv:
To install Opencv with Python 3, we will use wheel files.
Download here: http://www.lfd.uci.edu/~gohlke/pythonlibs/ the numpy and opencv ".whl".

For example: numpy‑1.12.0rc2+mkl‑cp36‑cp36m‑win32.whl
The number after cp corresponds to the version of Python. Here, cp36 means Python 3.6.
win32 refers to the Python version, not Windows.

Open a command prompt at the location of the downloaded files and type:
pip install "numpy‑1.12.0rc2+mkl‑cp36‑cp36m‑win32.whl"

pip install "opencv_python..."

