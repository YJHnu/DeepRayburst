BLSTM
  The morphology reconstruction (tracing) of neurons in 3D microscopy images is important to neuron science research. However, this task remains very challenging because of the low signal-to-noise ratio (SNR) and the discontinued segments of neurite patterns in the images. In this paper, we present a neuronal structure segmentation method based on the ray-shooting model and the Long Short-Term Memory (LSTM)-based network to enhance the weak-signal neuronal structures and remove background noise in 3D neuron microscopy images. Specifically,the ray-shooting model is used to extract the intensity distribution features within a local region of the image. And we design a neural network based on the dual channel bidirectional LSTM (DC-BLSTM) to detect the foreground voxels according to the voxel-intensity features and boundary-response features extracted by multiple ray-shooting models that are generated in the whole image. This way, we transform the 3D image segmentation task into multiple 1D ray/sequence segmentation tasks, which makes it much easier to label the training samples than many existing Convolutional Neural Network (CNN) based 3D neuron image segmentation methods.

If you find this project useful, we would be grateful if you cite the TensorLayer paper：
@article{jiang20203d,
  title={3D neuron microscopy image segmentation via the Ray-Shooting model and a DC-BLSTM network},
  author={Jiang, Yi and Chen, Weixun and Liu, Min and Wang, Yaonan and Meijering, Erik},
  journal={IEEE Transactions on Medical Imaging},
  volume={40},
  number={1},
  pages={26--37},
  year={2020},
  publisher={IEEE}
}

DeepRayburst

