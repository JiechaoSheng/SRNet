# SRNet
# SRNet: Sparse representation-based network for image denoising (SRNet)by Jiechao Sheng, Guoqiang Lv, Zi Wang, and Qibin Feng is publised in Digital Signal Processing , 2022. (https://www.sciencedirect.com/science/article/abs/pii/S1051200422003190) and it is implemented by Pytorch.


## Absract
Image denoising is a foundational but important task in image processing. Various traditional methods have been proposed to remove noise from noisy images. Sparse representation (SR) is a representative image denoising method. Although with good denoising effects, sparse representation suffers from
performance bottlenecks and large time consumption. Recently, deep learning has demonstrated excellent ability in image denoising. Therefore, we consider combining the sparse representation with deep learning to make this traditional model more effective and efficient. The sparse representation-based
network (SRNet) is proposed by embedding the convolutional neural network (CNN) into the sparse representation framework, in which all the parameters are learned by training. The iterative optimization process of sparse coding is unrolled into a network with several similar phases. In each phase, two
subnetworks are designed with the multiscale residual block (MSR-block) to model the updating of sparse coefficient and image, respectively. The experimental results show that compared with the traditional sparse representation denoising methods, the proposed method can significantly reduce time
consumption and improve denoising performance, especially in terms of reconstructing textures. The PyTorch code and models of the proposed SRNet can be released at https://github.com/JiechaoSheng/SRNet.

## Requirements (Pytorch)
### Pytorch 1.9.1 
### Numpy 
### Opencv 3
### Python 3.6.7
### Cuda 11.1
### Cudnn 7.5

### Training for gray noisy images
### Train_SRNet.py

### Test for gray noisy images
### Test_SRNet.py 

### Training for color noisy images
### Train_SRet_color.py

### Test for color noisy images
#### Test_SRNet_color.py

### Training datasets 
#### The training datasets of the gray noisy images and color noisy images are downloaded at https://pan.baidu.com/s/1dQ63Xf3VjEw74nVAcAz5Pw?pwd=atb5 

### If you want to cite this paper, please refer to the following format
#### Sheng J, Lv G, Wang Z, et al. SRNet: Sparse representation-based network for image denoising[J]. Digital Signal Processing, 2022, 130: 103702.
