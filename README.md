# The UGC Live VQA database-*TaoLive*

This database aims at the quality assessment of UGC live videos. Please refer to our paper (MD-VQA: Multi-Dimensional Quality Assessment for UGC Live Videos, CVPR2023) for more details. The official repo can be accessed [here](https://tianchi.aliyun.com/dataset/148818?t=1679581936815).

## 1. Introduction

With the rapid development of social media applications and the advancement of video shooting and processing technologies, more and more ordinary people are willing to tell their stories, share their experiences, and have their voice heard on social media or streaming media platforms such as Twitch, Tiktok, Taobao, etc. However, due to the lack of photography skills and professional equipment, the visual quality of user-generated content (UGC) videos may be degraded by in-the-wild distortions.

What's more, in common live platforms, live videos are encoded and distributed to end-users with very low delay, where compression algorithms have a significant influence on the visual quality of live videos because they can greatly reduce transmission bandwidth. As illustrated in the figure below, video quality assessment (VQA) tools play an important role in monitoring, optimizing, and further improving the Quality of Experience (QoE) of end-users in UGC live streaming systems.

To address UGC Live VQA problems, we first construct a large-scale UGC Live VQA database named TaoLive, consisting 418 source UGC videos from the TaoBao live streaming platform, and the corresponding 3,762 compressed videos at various bit rates, and perform a subjective experiment in a well-controlled environment. 

**Unfortunately, we can only provide access for 3,348 videos since the other videos are bothered with sensitive information and copyright issues.**


## 2. Database Description

The **TaoLive** database contains 2 types of files:

A. Part1-18.zip (Videos)

B. TaoLive_label.csv (MOS)

The official downloadlink can be accessed [here](https://tianchi.aliyun.com/dataset/148818?t=1679581936815).
The onedrive downloadlink is [here](https://1drv.ms/f/s!AjaDoj_-yWgggTM604LJz1Z2QnXL?e=T3i8cy).
The baiduyunpan downloadlink is [here](https://pan.baidu.com/s/1j3RAAxtinYQsM1zu_WUPtg?pwd=bzto). Extraction code: bzto

## 3. Citation

If you find our work useful, please cite our paper as:
```
@inproceedings{zhang2023mdvqa,
  title={MD-VQA: Multi-Dimensional Quality Assessment for UGC Live Videos},
  author={Zhang, Zicheng and Wu, Wei and Sun, Wei and Tu, Dangyang and Lu, Wei and Min, Xiongkuo and Chen, Ying and Zhai, Guangtao},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2023}
}
```

## 4. License

The database is distributed under the CC BY-NC-SA 4.0 license.
