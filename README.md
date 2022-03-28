# EEG-ITNet
The implementation of EEG-ITNet and other comparison deep models investigated in 
"<em>EEG-ITNet: An Explainable Inception Temporal Convolutional Network for Motor Imagery Classification</em>".
The original paper can be found on <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9739771&isnumber=6514899/">IEEE Xplore</a>. 
If you find this work useful in your research, please cite:
<br><br>A. Salami, J. Andreu-Perez and H. Gillmeister, 
"EEG-ITNet: An Explainable Inception Temporal Convolutional Network for motor imagery classification," 
in <em>IEEE Access</em>, doi: 10.1109/ACCESS.2022.3161489.
## Prerequisites
<li>The code was run on <a href="https://www.nvidia.com/en-us/geforce/products/10series/titan-x-pascal/">NVIDIA TITAN X</a> (CUDA 10.1 and cuDNN 7.6.0).</li> 
<li>The code is based on Python 3.8 and TensorFlow 2.3.</li> 

## Usage
If you would like to use your own dataset, remember to reshape the data for each subject to the format of trial<span>&#215;</span>channel<span>&#215;</span>sample and modify the code accordingly. If you would like to access the BCI Competition IV dataset 2a and the OpenBMI motor imagery dataset used in the paper, please contact a.salami@essex.ac.uk. 


