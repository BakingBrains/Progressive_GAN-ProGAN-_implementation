# Progressive_GAN-ProGAN-_implementation
ProGAN implementation</br>

Dataset: celeb-HQ (https://www.kaggle.com/lamsimon/celebahq)</br>
- Dowload the dataset and extract it to a folder and change the training dataset path in <i>config.py</i></br>

Edit the configurations according to your specification in <i>config.py</i></br>
Run the *train.py* file to start the training

A log folder will be created to trace the training of ProGAN. You can check using tensorboard</br>

```
tensorboard --logdir logs
```

ProGAN paper: https://arxiv.org/abs/1710.10196 </br>

*@misc{karras2018progressive,</br>
      title={Progressive Growing of GANs for Improved Quality, Stability, and Variation}, </br>
      author={Tero Karras and Timo Aila and Samuli Laine and Jaakko Lehtinen},</br>
      year={2018},</br>
      eprint={1710.10196},</br>
      archivePrefix={arXiv},</br>
      primaryClass={cs.NE}</br>
}*</br>
