# [Plant Disease Detection](https://which-crop-disease.app.render.com)
**Deployment: [Plant disease detector webApp](https://which-crop-disease.app.render.com/)** <br/>
Trained `resnet-34` for plant disease finegrained classification task using fastai. <br/>
Models are trained on the preprocessed dataset (total 39 classes) which can be downloaded [here](https://drive.google.com/open?id=0B_voCy5O5sXMTFByemhpZllYREU).<br/>
Dataset is consisted of **38** disease classes from [PlantVillage](https://plantvillage.org/) dataset and **1** background class from Stanford's open dataset of background images - [DAGS](http://dags.stanford.edu/projects/scenedataset.html).
<br/>
**80%** of the dataset is used for training and **20%** for validation.

**Citation:** <br/>
When using any part of this repo, please cite:
[`Plant Village Dataset Paper`](http://arxiv.org/abs/1511.08060)