# Solar-Farm-detection
In this project, we propose, optimize, and validate a deep learning framework to detect and map solar farms using a state-of-the-art semantic segmentation convolutional neural network applied to satellite imagery. As a final step in the pipeline, we propose a model to estimate the energy generation capacity of the detected solar energy facilities. Objectively, the deep learning model achieved highly competitive performance indicators, including a mean accuracy of 96.87%, and a Jaccard Index (intersection over union of classified pixels) score of 95.5%. 
<br /> Code:
<br /> **train.ipynb:** to train the semantic segmentation model to map and locate pv panels 
<br /> **test.ipynb:** to assess the model's perdformance on unseen data 
<br /> **unet-model.py:** semantic segmentation model architecture 
<br /> **useful-patches.ipynb:** discard useless patches with no solar panels for data augmentation 
<br /><br /> ![remotesensing-15-00210-g004](https://github.com/elaugh9/Solar-Farm-detection/assets/39347481/f74d7a43-ec0c-4b97-99e7-9717dd9b0a82 " UNet architecture for solar farm detection")
<br /><br /> Dataset: https://drive.google.com/drive/folders/1TfgL3Jij2T_rd6s7P88VvGkmbmZQ3nf2?usp=sharing
<br /><br /> Paper: https://www.mdpi.com/2072-4292/15/1/210 
<br /><br /> Presentation: https://docs.google.com/presentation/d/1A__d8NzaZ3bVqa7w0185cYBPWmSm9ho0rucFb0tDpQ0/edit?usp=sharing
