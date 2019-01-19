# [Plant Disease Detection](https://which-crop-disease.app.render.com)
**Deployment: [Plant disease detector webApp](https://which-crop-disease.app.render.com/)** <br/>
Trained `resnet-34` for plant disease finegrained classification task using fastai. <br/>
Models are trained on the preprocessed dataset (total 39 classes) which can be downloaded [here](https://drive.google.com/open?id=0B_voCy5O5sXMTFByemhpZllYREU).<br/>
Dataset is consisted of **38** disease classes from [PlantVillage](https://plantvillage.org/) dataset and **1** background class from Stanford's open dataset of background images - [DAGS](http://dags.stanford.edu/projects/scenedataset.html).
<br/>
**80%** of the dataset is used for training and **20%** for validation.

**Citation:** If using any part of this repo, please cite:
1. [Plant Village Dataset Paper](`http://arxiv.org/abs/1511.08060`)
2. [Deep Learning for Plant Diseases: Detection and Saliency Map Visualisation](https://link.springer.com/chapter/10.1007/978-3-319-90403-0_6):
```
@Inbook{Brahimi2018,
  author     = "Brahimi, Mohammed and Arsenovic, Marko and Laraba, Sohaib and Sladojevic, Srdjan and Boukhalfa, Kamel and Moussaoui, Abdelouhab",
  editor     = "Zhou, Jianlong and Chen, Fang",
  title      = "Deep Learning for Plant Diseases: Detection and Saliency Map Visualisation",
  bookTitle  = "Human and Machine Learning: Visible, Explainable, Trustworthy and Transparent", year="2018",
  publisher  = "Springer International Publishing",
  address    = "Cham",
  pages      = "93--117",
  url        = "https://doi.org/10.1007/978-3-319-90403-0_6"
}
```
