# BLSTM

  The morphology reconstruction (tracing) of neurons in 3D microscopy images is important to neuron science research. However, this task remains very challenging because of the low signal-to-noise ratio (SNR) and the discontinued segments of neurite patterns in the images. In this paper, we present a neuronal structure segmentation method based on the ray-shooting model and the Long Short-Term Memory (LSTM)-based network to enhance the weak-signal neuronal structures and remove background noise in 3D neuron microscopy images. Specifically,the ray-shooting model is used to extract the intensity distribution features within a local region of the image. And we design a neural network based on the dual channel bidirectional LSTM (DC-BLSTM) to detect the foreground voxels according to the voxel-intensity features and boundary-response features extracted by multiple ray-shooting models that are generated in the whole image. This way, we transform the 3D image segmentation task into multiple 1D ray/sequence segmentation tasks, which makes it much easier to label the training samples than many existing Convolutional Neural Network (CNN) based 3D neuron image segmentation methods.
## Diagram of the proposed neuron segmentation method
![image](https://user-images.githubusercontent.com/44941820/139392323-b20ff58c-12b1-4cfa-a684-67c60dd79c59.png)

If you find this project useful, we would be grateful if you cite the TensorLayer paper：
Y. Jiang, W. Chen, M. Liu, Y. Wang, and E. Meijering, "3D neuron microscopy image segmentation via the Ray-Shooting model and a DC-BLSTM network", IEEE Transactions on Medical Imaging, vol. 40, no. 1, pp. 26-37, 2020.


# Multi-class segmentation of vertebrae and intervertebral discs

  A multi-class segmentation algorithm is proposed to achieve automated spine parsing for volumetric MR images based on DeepLabv3+ and deformable Transformer. First, we use the DeepLabv3+ to extract the local spatial semantic information and build a deformable Transformer module to model global context information, and then use the proposed feature fusion module to combine global context information and local semantic information. The output of the feature fusion module is feed into a decoder layer to generate the final segmentation result.
## The framework of the proposed method
![image](https://user-images.githubusercontent.com/44941820/139396755-9febb8f4-0315-446b-a0da-0d21b1515091.png)


# DeepRayburst
