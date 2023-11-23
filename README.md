# MASK_RCNN BALLON

참고자료 : 

<https://hdongle.tistory.com/202>

<https://ultrakid.tistory.com/21>

수행순서 :


1. Anaconda 가상환경 생성 후 git clone으로 Mask rcnn 다운
2. 필요한 버전의 tensorflow, keras 등 설치
3. metterport에서 제공하는 ballon dataset과 모델을 이용하여 inference 실행
   ```
   python balloon.py --dataset ../../model/balloon/datasets --weights ../../mask_rcnn_balloon.h5 --logs ../../model/balloon/logs --image ../../model/balloon/datasets/val/원하는 이미지 splash
   ```
5. samples/ballon에 실행완료된 inference 이미지 확인


### Before

![3800636873_ace2c2795f_b](https://github.com/matterport/Mask_RCNN/assets/103041130/ef170ae3-ef90-45f6-bbc3-bce5851fa4fc)

![5555705118_3390d70abe_b](https://github.com/matterport/Mask_RCNN/assets/103041130/a152406e-71cf-4371-8363-73478207a57b)

### After

![splash_20231108T172747](https://github.com/matterport/Mask_RCNN/assets/103041130/1a9b8196-3471-4f6f-a487-79219c88692d)

![splash_20231123T204042](https://github.com/matterport/Mask_RCNN/assets/103041130/31fc6b4c-98d2-4f8d-9549-b9620f7cf700)
