# Kaggle Facial Keypoints Detection With Keras

https://www.kaggle.com/c/facial-keypoints-detection
## Introduction
CNN을 사용하여 눈, 코, 입 등과 같은 인간의 얼굴의 키포인트를 감지합니다.
교육 데이터 'training.csv'와 테스트 데이터 'test.csv'는 Kaggle https://www.kaggle.com/c/facial-keypoints-detection/data 에서 다운로드 할 수 있습니다.

| dataset  | num  | resolution | color | keypoints |
| :------- | :--- | :--------- | :---- | :-------- |
| Training | 7049 | 96x96      | gray  | 15        |
| Test     | 1783 | 96x96      | gray  | 15        |

* 15개 key points
> left_eye_center, right_eye_center, left_eye_inner_corner, left_eye_outer_corner, right_eye_inner_corner, right_eye_outer_corner, left_eyebrow_inner_end, left_eyebrow_outer_end, right_eyebrow_inner_end, right_eyebrow_outer_end, nose_tip, mouth_left_corner, mouth_right_corner, mouth_center_top_lip, mouth_center_bottom_lip

## Execution environment
- Window10 Education
- Ram : 16GB
- GPU : GeForce GTX 1080
- ANACONDA : 5.2.0
```
https://www.anaconda.com/download/
```
- python : 3.6.8
```
python -m pip install –upgrade pip
conda create -n tensorflow python=3.6
* 가상환경 : tensorflow
* 가상환경 접속 : activate tensorflow
* tensorflow : python 3.7 미지원.
```
- CUDA Toolkit : cuda_10.0.130_411.31_win10
```
https://developer.nvidia.com/cuda-downloads
* 설치 완료 및 재부팅, 환경변수 확인.
* 시스템 환경변수 편집 -> 고급 -> 환경변수 클릭
```
- cuDNN : 7.4
```
https://developer.nvidia.com/cudnn
* NVIDIA 계정 가입후 설치 진행.
* 다운로드 후 내부 디렉토리 파일 C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0 복사
```
- Tensorflow - GPU : 1.12.0
```
pip3 install --upgrade tensorflow-gpu
```

- Jupyter NoteBook : 5.7.4
```
pip install jupyter
실행 : jupyter notebook
```

- Keras : 2.2.4 
```
pip install keras
```
## Result
* Result
<p align="center"> 
<img src="https://github.com/yunhyuck/OpenSourceProject/blob/add-license-1/picture/20190118_190103.jpg?raw=true">
</p>


* Kaggle
<p align="center"> 
<img src="https://github.com/yunhyuck/OpenSourceProject/blob/add-license-1/picture/%EC%BA%A1%EC%B2%98.PNG?raw=true">
</p>

## Addition
<p align="center"> 
<img src="https://github.com/yunhyuck/OpenSourceProject/blob/add-license-1/picture/20190119_175616.jpg?raw=true">
</p>

<p align="center"> 
<img src="https://github.com/yunhyuck/OpenSourceProject/blob/add-license-1/picture/20190119_175628.jpg?raw=true">
</p>


# Final Source : Facial.ipynb
# Addition Aplication : Addition Aplication.ipynb
