# Develop-Debugging-error-20241029



241202
python -m venv mynew_venv

cd/ / activate




conda install opencv,
after
problem occur

(base) (mynew_venv) C:\Users\kimseonghyun\Downloads\241202wondetection\src\test_demo> python 241202pytorchimplementedfirstversion.py
Traceback (most recent call last):
  File "C:\Users\kimseonghyun\Downloads\241202wondetection\src\test_demo\241202pytorchimplementedfirstversion.py", line 1, in <module>
    import cv2
ModuleNotFoundError: No module named 'cv2'

(base) (mynew_venv) C:\Users\kimseonghyun\Downloads\241202wondetection\src\test_demo>pip install opencv-python
Collecting opencv-python
  Using cached opencv_python-4.10.0.84-cp37-abi3-win_amd64.whl.metadata (20 kB)
Collecting numpy>=1.21.2 (from opencv-python)
  Using cached numpy-2.1.3-cp312-cp312-win_amd64.whl.metadata (60 kB)
Using cached opencv_python-4.10.0.84-cp37-abi3-win_amd64.whl (38.8 MB)
Using cached numpy-2.1.3-cp312-cp312-win_amd64.whl (12.6 MB)
Installing collected packages: numpy, opencv-python
Successfully installed numpy-2.1.3 opencv-python-4.10.0.84


(base) (mynew_venv) C:\Users\kimseonghyun\Downloads\241202wondetection\src\test_demo>conda install pytorch torchvision torchaudio cpuonly -c pytorch
Channels:
 - pytorch
 - defaults
 - conda-forge
Platform: win-64
Collecting package metadata (repodata.json): /
