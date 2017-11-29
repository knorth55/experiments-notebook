# Photo Style Transfer by Deep Image Analogy

I run photo style transfer by [Deep Image Analogy](https://github.com/msracver/Deep-Image-Analogy).

## Requirement

- Caffe

## Results

### Photo style transfer Refinement

| A (input) | AP (output) | B (output) | BP (input) |
|:---------:|:-----------:|:-----------:|:---------:|
|![0_A](./images/0/A.png) | ![0_AB](./images/0/refineAB.png) | ![0_BA](./images/0/refineBA.png) | ![0_B](./images/0/B.png) |
|![1_A](./images/1/A.png) | ![1_AB](./images/1/refineAB.png) | ![1_BA](./images/1/refineBA.png) | ![1_B](./images/1/B.png) |
|![2_A](./images/2/A.png) | ![2_AB](./images/2/refineAB.png) | ![2_BA](./images/2/refineBA.png) | ![2_B](./images/2/B.png) |
|![3_A](./images/3/A.png) | ![3_AB](./images/3/refineAB.png) | ![3_BA](./images/3/refineBA.png) | ![3_B](./images/3/B.png) |
|![4_A](./images/4/A.png) | ![4_AB](./images/4/refineAB.png) | ![4_BA](./images/4/refineBA.png) | ![4_B](./images/4/B.png) |
|![5_A](./images/5/A.png) | ![5_AB](./images/5/refineAB.png) | ![5_BA](./images/5/refineBA.png) | ![5_B](./images/5/B.png) |
|![6_A](./images/6/A.png) | ![6_AB](./images/6/refineAB.png) | ![6_BA](./images/6/refineBA.png) | ![6_B](./images/6/B.png) |
|![7_A](./images/7/A.png) | ![7_AB](./images/7/refineAB.png) | ![7_BA](./images/7/refineBA.png) | ![7_B](./images/7/B.png) |


### Original Network Output

| A (input) | AP (output) | B (output) | BP (input) |
|:---------:|:-----------:|:-----------:|:---------:|
|![0_A](./images/0/A.png) | ![0_AB](./images/0/resultAB.png) | ![0_BA](./images/0/resultBA.png) | ![0_B](./images/0/B.png) |
|![1_A](./images/1/A.png) | ![1_AB](./images/1/resultAB.png) | ![1_BA](./images/1/resultBA.png) | ![1_B](./images/1/B.png) |
|![2_A](./images/2/A.png) | ![2_AB](./images/2/resultAB.png) | ![2_BA](./images/2/resultBA.png) | ![2_B](./images/2/B.png) |
|![3_A](./images/3/A.png) | ![3_AB](./images/3/resultAB.png) | ![3_BA](./images/3/resultBA.png) | ![3_B](./images/3/B.png) |
|![4_A](./images/4/A.png) | ![4_AB](./images/4/resultAB.png) | ![4_BA](./images/4/resultBA.png) | ![4_B](./images/4/B.png) |
|![5_A](./images/5/A.png) | ![5_AB](./images/5/resultAB.png) | ![5_BA](./images/5/resultBA.png) | ![5_B](./images/5/B.png) |
|![6_A](./images/6/A.png) | ![6_AB](./images/6/resultAB.png) | ![6_BA](./images/6/resultBA.png) | ![6_B](./images/6/B.png) |
|![7_A](./images/7/A.png) | ![7_AB](./images/7/resultAB.png) | ![7_BA](./images/7/resultBA.png) | ![7_B](./images/7/B.png) |

## Try it by yourself

### How to Install

```bash
git clone https://github.com/msracver/Deep-Image-Analogy.git
cd Deep-Image-Analogy/
git checkout linux
sh scripts/config_deep_image_analogy.sh

# modify Makefile.config.example
ln -sf Makefile.config.example Makefile.config
make all
sh scripts/make_deep_image_analogy.sh
```

### How to Run

***Caution***

For photo2photo style transfer, use config below.

- Blend Weight: `3`

- WLS Filter: `1`

```bash
export LD_LIBRARY_PATH="./build/lib" 
./demo deep_image_analogy/models/ /path/to/img/A.png /path/to/img/B.png /path/to/output/dir/ 0 0.5 3 1
```
