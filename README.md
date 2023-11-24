# MaskRCNNTraining


1번 과제..

tensorflow-gpu, karas 등 버전 맞추는 게 제일 힘들었다.

실행하기 전 mask_rcnn_balloon.h5 설치가 필요하다. 
https://github.com/matterport/Mask_RCNN/releases/download/v2.1/mask_rcnn_balloon.h5

<br>

inspect_balloon_model.ipynb의 마지막 셀에서 

```
!python balloon.py --dataset ../../model/balloon/datasets --weights ../../mask_rcnn_balloon.h5 --logs ../../model/balloon/logs --image ../../model/balloon/datasets/val/5603212091_2dfe16ea72_b.jpg splash
```



실행하여 

Mask_RCNN/samples/balloon 경로에서 output 사진을 확인 가능 

<img src="https://github.com/ReadMyMemory/MaskRCNNTraining/assets/122192096/d86e6519-1d4e-4cf4-a507-77151a2dbace" width="192" height="256"/>

splash_20231123T231658.png

<Br><br><Br>

기본 실습의 경우 
```
!python balloon.py --dataset ../../model/balloon/datasets --weights ../../mask_rcnn_balloon.h5 --logs ../../model/balloon/logs --image ../../model/balloon/datasets/val/3800636873_ace2c2795f_b.jpg splash
```




실행하여

Mask_RCNN/samples/balloon 경로에서 output 사진을 확인 가능

<img src="https://github.com/ReadMyMemory/MaskRCNNTraining/assets/122192096/457b881f-c261-4a44-a8b3-91fb0897c070" width="172" height="256"/>

splash_20231123T230440.png
