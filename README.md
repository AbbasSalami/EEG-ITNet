# EEG-ITNet
The implementation of EEG-ITNet and other comparison deep models investigated in 
"<em>EEG-ITNet: An Explainable Inception Temporal Convolutional Network for Motor Imagery Classification</em>".
The original paper can be found on <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9739771&isnumber=6514899/">IEEE Xplore</a>. 
If you find this work useful in your research, please cite:
<br><br>A. Salami, J. Andreu-Perez and H. Gillmeister, 
"EEG-ITNet: An Explainable Inception Temporal Convolutional Network for motor imagery classification," 
in <em>IEEE Access</em>, doi: 10.1109/ACCESS.2022.3161489.
## Prerequisites
<li>The code was initially run on <a href="https://www.nvidia.com/en-us/geforce/products/10series/titan-x-pascal/">NVIDIA TITAN X</a> (CUDA 10.1 and cuDNN 7.6.0).</li> 
<li>The code is based on Python 3.12.3 and TensorFlow 2.16.1.</li> 

## Usage
Code is provided as it is. Datases can be downloaded from their corresponding repositories. If you would like to use your own dataset, remember to reshape the data for each subject to the format of trial<span>&#215;</span>channel<span>&#215;</span>sample and modify the code accordingly. 

## License
Abbas Salami - University of Essex (C) ALL RIGHTS RESERVED - ATTRIBUTION IS REQUIRED. NON-COMMERCIAL USE, NO DERIVATIVES, NO REDISTRIBUTION WITHOUT EXPLICIT CONSENT OF THEIR AUTHOR (a.salami@essex.ac.uk)

## Disclaimer
IN NO EVENT SHALL THE AUTHOR OF THIS CODE BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE
