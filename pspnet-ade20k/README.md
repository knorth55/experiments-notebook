# PSPNet with ADE20K

I run PSPNet trained with ADE20K.

Class labels are choosen from deep photo style transfer.


## Requirement

- [chainer-pspnet](https://github.com/mitmul/chainer-pspnet)


## Results

### HDR image
| input | prediction result |
|:-----:|:-----------------:|
| ![in](./images/input/NorthBubble.png) |  ![pred](./images/seg_results/predict_NorthBubble.png) |
| ![in](./images/input/TunnelView.png) |  ![pred](./images/seg_results/predict_TunnelView.png) |
| ![in](./images/input/UpheavalDome.png) |  ![pred](./images/seg_results/predict_UpheavalDome.png) |


### ADE20K

| input | prediction result | ground truth |
|:-----:|:-----------------:|:------------:|
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in1.png) | ![pred](./images/seg_results/predict_in1.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in1.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in2.png) | ![pred](./images/seg_results/predict_in2.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in2.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in3.png) | ![pred](./images/seg_results/predict_in3.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in3.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in5.png) | ![pred](./images/seg_results/predict_in5.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in5.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in6.png) | ![pred](./images/seg_results/predict_in6.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in6.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in7.png) | ![pred](./images/seg_results/predict_in7.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in7.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in13.png) | ![pred](./images/seg_results/predict_in13.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in13.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in14.png) | ![pred](./images/seg_results/predict_in14.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in14.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in15.png) | ![pred](./images/seg_results/predict_in15.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in15.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in19.png) | ![pred](./images/seg_results/predict_in19.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in19.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in20.png) | ![pred](./images/seg_results/predict_in20.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in20.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in21.png) | ![pred](./images/seg_results/predict_in21.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in21.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in28.png) | ![pred](./images/seg_results/predict_in28.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in28.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in31.png) | ![pred](./images/seg_results/predict_in31.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in31.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in32.png) | ![pred](./images/seg_results/predict_in32.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in32.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in44.png) | ![pred](./images/seg_results/predict_in44.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in44.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in46.png) | ![pred](./images/seg_results/predict_in46.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in46.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in47.png) | ![pred](./images/seg_results/predict_in47.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in47.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in48.png) | ![pred](./images/seg_results/predict_in48.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in48.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in50.png) | ![pred](./images/seg_results/predict_in50.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in50.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in51.png) | ![pred](./images/seg_results/predict_in51.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in51.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in52.png) | ![pred](./images/seg_results/predict_in52.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in52.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in53.png) | ![pred](./images/seg_results/predict_in53.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in53.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in54.png) | ![pred](./images/seg_results/predict_in54.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in54.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in55.png) | ![pred](./images/seg_results/predict_in55.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in55.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in56.png) | ![pred](./images/seg_results/predict_in56.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in56.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in57.png) | ![pred](./images/seg_results/predict_in57.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in57.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in58.png) | ![pred](./images/seg_results/predict_in58.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in58.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in59.png) | ![pred](./images/seg_results/predict_in59.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in59.png) |
| ![in](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/input/in60.png) | ![pred](./images/seg_results/predict_in60.png) |  ![gt](https://raw.githubusercontent.com/luanfujun/deep-photo-styletransfer/master/examples/segmentation/in60.png) |

