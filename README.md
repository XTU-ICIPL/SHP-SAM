# Scribble-guided Hierarchical Prompt for SAM-Based Weakly Supervised Salient Object Detection

---

## Overview

![SHP-SAM Framework](./figures/framework.png)

## Datasets

<https://pan.baidu.com/s/1oFJmarUSuLI4hB5obEOtOw?pwd=assy> (fetch code: assy)

## Predicted Saliency Map

we provide the predicted saliency maps datasets DUTS-TE, DUT-OMRON, HKU-IS, ECSSD and PASCAL-S

<https://pan.baidu.com/s/1b7MP8-L2eWYcbsoNTP2qIQ?pwd=979c> (fetch code: 979c)

## Evaluation Code

we use the evaluation code below to generate results:

<https://github.com/lartpang/PySODMetrics>

Following [MDSAM](https://github.com/BellyBeauty/MDSAM), we modify the calculation method of the max F-measure from selecting a unified highest threshold for all images to calculating the highest threshold for each individual image.
