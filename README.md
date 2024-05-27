# Zero-Shot Capabilities of Advanced Image Segmentation Models (Pushing SAM and CLIP to their limits)
This code was created as a part of my diploma thesis for the Master's program in *Data Science and Machine Learning* of the National Technical University of Athens (NTUA). 

# Abstract
The object of this work is to study image segmentation across various reference datasets, utilizing two state-of-the-art deep learning models, Segment Anything Model (SAM) and CLIPSeg. The aim is to explore the performance of these models for the task of image segmentation across multiple 
datasets, employing metrics such as Intersection over Union (IoU) and Dice Loss. Image segmentation has become a critical task in computer vision due to the exponential growth of image data volume and has numerous applications in various domains. 
Image segmentation involves dividing an image into multiple segments, where each segment represents a different object or region within the image.

# DataSets
The dataset used in this paper are:
* The *City Scapes Dataset*. A large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly
  annotated frames. (https://www.cityscapes-dataset.com/)
* The *Corsican Fire Database*. The “Fire” project conducted within the laboratory “Sciences Pour l’Environnement” UMR CNRS 6134 SPE - University of Corsica is dedicated to the modeling and experimentation of vegetation fires.As part of this research,
  a database has been developed. It contains wildfires pictures and image sequences acquired in the areas of visible and near-infrared. (https://cfdb.univ-corse.fr/index.php?newlang=english&menu=1)
* The *Electron Microscopy Dataset*. The dataset represents a 5x5x5µm section taken from the CA1 hippocampus region of the brain, corresponding to a 1065x2048x1536 volume. (https://www.epfl.ch/labs/cvlab/data/data-em/)
* The *COVID-QU-Ex Dataset*. The researchers of Qatar University have compiled the COVID-QU-Ex dataset, which consists of 33,920 chest X-ray (CXR) images. (https://www.kaggle.com/datasets/anasmohammedtahir/covidqu)

# Models
The models used in this paper are:
* The *Segment Anything Model* (SAM). SAM is a promptable segmentation system with zero-shot generalization to unfamiliar objects and images, without the need for additional training. (https://segment-anything.com/)
* The *Contrastive Language-Image Pre-training Segmentation Model* (CLIPSeg). The CLIPSeg model was proposed in Image Segmentation Using Text and Image Prompts by Timo Lüddecke and Alexander Ecker.
  CLIPSeg adds a minimal decoder on top of a frozen CLIP model for zero- and one-shot image segmentation.(https://huggingface.co/docs/transformers/en/model_doc/clipseg)
* The *Prompt Adapter SAM* (PA-SAM). A prompt-driven adapter into SAM, namely Prompt Adapter Segment Anything Model, aiming to enhance the segmentation mask quality of the original SAM.. (https://github.com/xzz2/pa-sam)
* The *Segment Anything in Medical Images Model* (Med-SAM).  A foundation model designed for bridging this gap by enabling universal medical image segmentation. (https://github.com/bowang-lab/MedSAM)
