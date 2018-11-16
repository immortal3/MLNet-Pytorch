# MLNet-Pytorch

Implementation of A Deep Multi-Level Network for Saliency Prediction in Pytorch

#### For Mobile Users: https://nbviewer.jupyter.org/github/immortal3/MLNet-Pytorch/blob/master/MLNet_Pytorch.ipynb

Notebook is directly runnable to Google colab.


#### Note : Due to Memory Limit, some layers were frozen and output saliency maps size was reduced by half during Training.

#### Result :

  
|	 |AUC|CC|KL|SAUC|IG|NSS|SIM|
|----|---|--|--|----|--|---|---|
|Ours|0.771|0.553|1.142|0.619|-0.380|1.014|0.573|

| | | | | |
|---|---|---|---|---|
| Original Image | ![1](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/1.png) | ![2](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/2.png)|![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/3.png) |![4](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/4.png) |
| Predicted Saliency Map| ![1](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/1_pred.png)| ![2](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/2_pred.png) |![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/3_pred.png) | ![4](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/4_pred.png) |
| Ground Truth| ![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/1_gt.png)| ![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/2_gt.png) |![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/3_gt.png) |![3](https://github.com/immortal3/MLNet-Pytorch/blob/master/readme-content/4_gt.png) |


#### References: 

#### [1] Cornia, Marcella, et al. "A deep multi-level network for saliency prediction." Pattern Recognition (ICPR), 2016 23rd International Conference on. IEEE, 2016.
#### [2] Jiang, Ming, et al. "Salicon: Saliency in context." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.
