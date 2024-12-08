# RFSR

Codes for RFSR: Improving ISR Diffusion Models via Reward Feedback Learning.

We release example Reward Feedback Learning training code in SeeSR.

## Installation

To install the necessary dependencies, run the following commands:

```bash
pip install pyiqa
pip install image-reward
pip install git+https://github.com/fbcotter/pytorch_wavelets.git
```

## Run SeeSR

```bash
bash SeeSR/train_seesr_kl_ema.sh
```
## Visualization

![Sample 1](asserts/vis_image.jpg)
![Sample 2](asserts/supp_img1.jpg)
![Sample 3](asserts/supp_img2.jpg)
![Sample 4](asserts/supp_img3.jpg)
![Sample 5](asserts/supp_img4.jpg)

## 🎓Citations
If our code helps your research or work, please consider citing our paper.
The following are BibTeX references:

```
@article{sun2024rfsr,
  title={RFSR: Improving ISR Diffusion Models via Reward Feedback Learning},
  author={Sun, Xiaopeng and Lin, Qinwei and Gao, Yu and Zhong, Yujie and Feng, Chengjian and Li, Dengjie and Zhao, Zheng and Hu, Jie and Ma, Lin},
  journal={arXiv preprint arXiv:2412.03268},
  year={2024}
}
```

## Acknowledgements

Visitor counter: ![Counter](https://counter.jerryz.com.cn/counter?name=rfsr)
