## Computer Vision exam project A.Y. 2024/2025, Summer Session (July 23rd)
### Project 4: Car Plate Recognition and Reconstruction with Deep Learning

#### Authors:
Andrea D'Alessio (2208280), Karim Refaie Yehia Ellithy(2188256), Jamil Nassar(2224424).

#### Referenced works:
Tao, L., Hong, S., Lin, Y., Chen, Y., He, P. and Tie, Z. (2024). A Real-Time License Plate Detection and Recognition Model in Unconstrained Scenarios. Sensors, 24(9), 2791\

 N. P. Ap, T. Vigneshwaran, M. S. Arappradhan and R. Madhanraj, "Automatic Number Plate Detection in Vehicles using Faster R-CNN," 2020 International Conference on System, Computation, Automation and Networking (ICSCAN), Pondicherry,India, 2020, pp. 1-6, doi: 10.1109/ICSCAN49426.2020.9262400.\

V. D. Nandimandalam, Real-time car license plate detection using Single Shot MultiBox Detector (SSD), Master's thesis, National College of Ireland, 2020.\

#### About the models:
Baseline_SSD_MobileNetV3 is the first baseline implemented.\
FastRCNN+Recognition is the second baseline.\
All the files with "yolov8" in the beginning are test files with the separate training of YOLoO v8 by Ultralytics.\
"detection+pdl_pr" is the final implemented model as stated in the first paper.\
All models run on python 3.12 and require the CCPD-2019 dataset (whose link is found in the notebook themselves.\Kagglehub handles the download and install of it).\
Each model comes with its own set of trained weights, they are already assigned and ready to run for evaluation (make sure the dataset is correctly installed).\


