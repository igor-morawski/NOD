# NOD (Night Object Detection) Dataset
_NOD: Taking a Closer Look at Detection under Extreme Low-Light Conditions with Night Object Detection Dataset_, BMVC 2021

[Igor Morawski](https://igor-morawski.github.io/), Yu-An Chen, Yu-Sheng Lin, [Winston Hsu](https://winstonhsu.info/)

<sub>**Abstract**</sub>

<sup>Recent work indicates that, besides being a challenge in producing perceptually pleasing images, low light proves more difficult for machine cognition than previously thought. In our work, we take a closer look at object detection in low light. First, to support the development and evaluation of new methods in this domain, we present a high-quality large-scale Night Object Detection (NOD) dataset showing dynamic scenes captured on the streets at night. Next, we directly link the lighting conditions to perceptual difficulty and identify what makes low light problematic for machine cognition. Accordingly, we provide instance-level annotation for a subset of the dataset for an in-depth evaluation of future methods. We also present an analysis of the baseline model performance to highlight opportunities for future research and show that low light is a non-trivial problem that requires special attention from the researchers. Further, to address the issues caused by low light, we propose to incorporate an image enhancement module into the object detection framework and two novel data augmentation techniques. Our image enhancement module is trained under the guidance of the object detector to learn image representation optimal for machine cognition rather than for the human visual system.  Finally, experimental results confirm that the proposed method shows consistent improvement of the performance on low-light datasets.</sup>

### Dataset Introduction
We present a high-quality large-scale dataset of outdoor images targeting low-light object detection. The dataset contains more than 7K images and 46K annotated objects (with bounding boxes) that belong to classes: _person_, _bicycle_, and _car_. The photos were taken on the streets at evening hours, and thus all images present low-light conditions to a varying degree of severity. We used two DSLR cameras to capture the scenes: Sony RX100 VII and Nikon D750, and throughout the paper, we refer to the sets collected by these cameras as Sony and Nikon (data)set. We show the statistics of our dataset in the table below.

| Dataset | Camera | #classes | #annotated images | #instances | #unannotated images |
|--- |--- |--- |--- |--- |--- |
| Sony | Sony RX100 VII | 3 | 3.2k | 18.7k | 0.9k |
| Nikon | Nikon D750 | 3 | 4.0k | 28.0k | 0 |
| (in total) | Sony+Nikon | 3 | 7.2k | 46.7k | 0.9k |

## Please download the dataset using the [link](https://forms.gle/YhHYBofVjphosbeDA).

## Citation
If you find our dataset useful in your research or publication, please cite our work:
```
(to be provided)
```

### Contact
Igor Morawski: [e-mail](mailto:igor@cmlab.csie.ntu.edu.tw), [LinkedIn](https://www.linkedin.com/in/igor-morawski/).
