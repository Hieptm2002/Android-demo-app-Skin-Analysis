# Android-demo-app-Facial-Skin-Analysis

# Data preparation

1. Collected data.
* Self-collected dataset comprises frontal face images without makeup, clearly displaying various skin problems, collected from diverse sources such as the renowned [CelebAMask-HQ](https://github.com/switchablenorms/CelebAMask-HQ?tab=readme-ov-file) and [FFHQ](https://github.com/NVlabs/ffhq-dataset) datasets, as well as publicly available facial image repositories like Google, Istock, and Roboflow.
2. Generating Dataset use StyleGAN 3.
* We utilized the pre-trained StyleGAN3 model on the FFHQ dataset for initial training. We fine-tuned the model and generated a large set of high-quality images. After careful curation to ensure diversity and clarity, we compiled these into the Self-collected dataset.
   
# Facial Skin Diseases Classification

* Built using [dlib](http://dlib.net/)'s state-of-the-art face recognition
built with deep learning. The model has an accuracy of 99.38% on the
[Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) benchmark.

# Facial Skin Diseases Segmentaton 

# Reference

https://github.com/switchablenorms/CelebAMask-HQ

https://github.com/NVlabs/ffhq-dataset

https://pytorch.org/.

https://github.com/deepcam-cn/yolov5-face.

https://github.com/davisking.

https://github.com/ultralytics/ultralytics.

https://github.com/Tencent/ncnn. 
