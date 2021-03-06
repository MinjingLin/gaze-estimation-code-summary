# gaze-estimation-code-summary
## Data pre-processing code.
For 3D gaze estimation: [MPIIGaze](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#mpiigaze), [MPIIFaceGaze-gazehub](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#mpiifacegaze), [MPIIFaceGaze-swook](https://github.com/swook/faze_preprocess), [GazeCapture](https://github.com/swook/faze_preprocess), [Eyediap(eye)](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#eyediap-eye), [Eyediap(face)](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#eyediap-face), [UT-Multiview](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#ut-multiview),
[ETH-XGaze_xuchong](https://github.com/xucong-zhang/ETH-XGaze/blob/7803922ce0eb7015485e2a78e9f8afff0f9db7a6/normalization_example.py#L39),
[ETH-XGaze_gazehub](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#eth-xgaze), [Gaze360](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#gaze360), [Rt-Gene](http://phi-ai.buaa.edu.cn/Gazehub/3D-dataset/#rt-gene)

For 2D gaze estimation: [GazeCapture](http://phi-ai.buaa.edu.cn/Gazehub/2D-dataset/#gazecapture), [MPIIFaceGaze](http://phi-ai.buaa.edu.cn/Gazehub/2D-dataset/#mpiifacegaze), [EyeDiap](http://phi-ai.buaa.edu.cn/Gazehub/2D-dataset/#eyediap)

## Gaze estimation works
* L2CS-Net: Fine-Grained Gaze Estimation in Unconstrained Environments, ICIP2022"under review". ([official-code](https://github.com/ahmednull/l2cs-net))

![image](https://user-images.githubusercontent.com/26761880/174731320-ec233cce-8659-4202-a470-57902cda5952.png)

* Gaze Estimation using Transformer, ICPR 2022. ([official-code](https://github.com/yihuacheng/GazeTR))

![image](https://user-images.githubusercontent.com/26761880/174578497-040b633d-edd2-4b09-ac2a-1215f875fe85.png)

* Puregaze: Purifying gaze feature for generalizable gaze estimation, AAAI 2022. ([official-code](https://github.com/yihuacheng/PureGaze))

![image](https://user-images.githubusercontent.com/26761880/174579784-3a71b6ff-40b8-41e0-ba34-0ab9be7aea6d.png)

* Gaze Estimation with an Ensemble of Four Architectures, ETH-XGaze Competition 2021. ([official-code](https://github.com/VIPL-TAL-GAZE/GAZE2021))

![image](https://user-images.githubusercontent.com/26761880/174730323-2aa32f6c-a0a2-47ca-bbc3-d1622a9a1256.png)

* ETH-XGaze: A Large Scale Dataset for Gaze Estimation under Extreme Head Pose and Gaze Variation, ECCV2020. ([official-codel](https://github.com/xucong-zhang/ETH-XGaze))

![image](https://user-images.githubusercontent.com/26761880/174726434-db9c5db8-20a5-441d-a126-0c63cc83afae.png)

* FAZE: Few-Shot Adaptive Gaze Estimation, ICCV2019. ([official-code](https://github.com/NVlabs/few_shot_gaze))

![image](https://user-images.githubusercontent.com/26761880/174726747-b613a88e-6631-4e4a-acea-f33b6b1394ee.png)

* Gaze360: Physically Unconstrained Gaze Estimation in the Wild, ICCV 2019. ([official-code](https://github.com/erkil1452/gaze360), [code1](https://github.com/yihuacheng/Gaze360))

![image](https://user-images.githubusercontent.com/26761880/174583745-c46127a0-02e6-456f-9d9e-10b3f966ab1e.png)

* Appearance-Based Gaze Estimation Using Dilated-Convolutions, ACCV 2019. ([code1](https://github.com/yihuacheng/Dilated-Net))

![image](https://user-images.githubusercontent.com/26761880/174702356-d3dd3960-0abb-40c1-b12e-31012813b088.png)

* Learning to find eye region landmarks for remote gaze estimation in unconstrained settings, ETRA2018. ([official-code](https://github.com/swook/GazeML))

![image](https://user-images.githubusercontent.com/26761880/174728173-e4d1a08e-1bba-47b2-b5f1-a20fc3cf9299.png)

* Appearance-Based Gaze Estimation via Evaluation-Guided Asymmetric Regression, ECCV 2018. ([official-code](https://github.com/yihuacheng/ARE-GazeEstimation))

![image](https://user-images.githubusercontent.com/26761880/174580698-339e552f-39d9-43d4-a86b-f81d695934bf.png)

* RT-GENE: Real-Time Eye Gaze Estimation in Natural Environments, ECCV 2018. ([official-code](https://github.com/Tobias-Fischer/rt_gene), [code1](https://github.com/yihuacheng/RT-Gene))

![image](https://user-images.githubusercontent.com/26761880/174702999-4893ca77-5146-40d9-8f06-8cc84aedd5dc.png)

* Recurrent CNN for 3D Gaze Estimation using Appearance and Shape Cues, BMVC2018. ([official-code](https://github.com/crisie/RecurrentGaze))

![image](https://user-images.githubusercontent.com/26761880/174731642-14741890-5f49-4545-a733-4ef7e1cea0df.png)

* MPIIGaze: Real-World Dataset and Deep Appearance-Based Gaze Estimation, TPAMI 2017. ([code1](https://github.com/yihuacheng/Gaze-Net))

![image](https://user-images.githubusercontent.com/26761880/174710049-cd1dc398-45fa-45a6-98b7-d242b80e20b1.png)

* It's written all over your face: Full-face appearance-based gaze estimation, CVPRW 2017. ([code1](https://github.com/yihuacheng/Full-face))

![image](https://user-images.githubusercontent.com/26761880/174710734-952dfb7e-90a5-4f35-8243-2d1b1751fd52.png)

* Eye Tracking for Everyone, CVPR 2016. ([official-code](https://github.com/CSAILVision/GazeCapture), [code1](https://github.com/yihuacheng/Itracker))

![image](https://user-images.githubusercontent.com/26761880/174711314-ab202fe4-fa44-42c3-a745-e17eefc7bd41.png)

* Appearance-Based Gaze Estimation in the Wild, CVPR 2015. ([code1](https://github.com/yihuacheng/Mnist))

![image](https://user-images.githubusercontent.com/26761880/174712034-ebb4c2fc-8683-46a4-b67e-432a326a3747.png)







# Reference
[Gazehub](http://phi-ai.buaa.edu.cn/Gazehub/)

[GazeEstimation-Summary](https://github.com/yihuacheng/GazeEstimation-Summary)

[paperwithcode-gaze](https://paperswithcode.com/task/gaze-estimation)

[xuchong-zhang](https://github.com/xucong-zhang?tab=repositories)

[swook](https://github.com/swook)
