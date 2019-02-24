# resnet-50

## meta

|                  |                                                 |
| ---------------- | ----------------------------------------------- |
| id               | 8abbcaef-6bcf-4f1f-9159-85c17c38bd00            |
| application_area | ImageNet                                        |
| task             | Classification                                  |
| task_extended    | ImageNet classification                         |
| data_type        | Image/Photo                                     |
| data_source      | http://www.image-net.org/challenges/LSVRC/2015/ |

## publication

|                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| title          | Deep Residual Learning for Image Recognition                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| source         | Proceedings of the IEEE conference on computer vision and pattern recognition                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| year           | 2016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| authors        | Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| abstract       | Deeper neural networks are more difficult to train. We present a residual learning framework to ease the training of networks that are substantially deeper than those used previously. We explicitly reformulate the layers as learning residual functions with reference to the layer inputs, instead of learning unreferenced functions. We provide comprehensive empirical evidence showing that these residual networks are easier to optimize, and can gain accuracy from considerably increased depth. On the ImageNet dataset we evaluate residual nets with a depth of up to 152 layers---8x deeper than VGG nets but still having lower complexity. An ensemble of these residual nets achieves 3.57% error on the ImageNet test set. This result won the 1st place on the ILSVRC 2015 classification task. We also present analysis on CIFAR-10 with 100 and 1000 layers. The depth of representations is of central importance for many visual recognition tasks. Solely due to our extremely deep representations, we obtain a 28% relative improvement on the COCO object detection dataset. Deep residual nets are foundations of our submissions to ILSVRC & COCO 2015 competitions, where we also won the 1st places on the tasks of ImageNet detection, ImageNet localization, COCO detection, and COCO segmentation. |
| google_scholar | https://scholar.google.com/scholar?cites=9281510746729853742&as_sdt=40000005&sciodt=0,22&hl=en                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| bibtex         | @inproceedings{he2016deep, title={Deep residual learning for image recognition}, author={He, Kaiming and Zhang, Xiangyu and Ren, Shaoqing and Sun, Jian}, booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition}, pages={770--778}, year={2016} }                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

## model

|               |                                                                                       |
| ------------- | ------------------------------------------------------------------------------------- |
| description   | ResNet-50 is a 50 layer Residual deep convolutional network for image classification. |
| architecture  | Convolutional Neural Network (CNN)                                                    |
| learning_type | Supervised learning                                                                   |
| format        | .onnx                                                                                 |
| I/O           | model I/O can be viewed [here](contrib_src/model/config.json)                         |
| license       | model licence can be viewed [here](contrib_src/license/model)                         |

## run

To run this model and view others in the collection, view the instructions on [modelhub](http://app.modelhub.ai/).

## contribute

To contribute models, visit the [modelhub docs](https://modelhub.readthedocs.io/en/latest/).
