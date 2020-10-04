# Dish_Classfication
한국 음식 이미지 분류기 입니다. 

분류할 수 있는 음식 30가지는 아래와 같습니다.

떡볶이, 된장찌개, 계란찜, 치킨, 갈비, 갈비탕, 갈치구이, 김밥, 김치, 김치찌개,

한과, 해물찜, 자장면, 찜닭, 족발, 깻잎, 꼬막, 콩자반, 만두, 물회,

피자, 감자, 삼계탕, 새우튀김, 식혜, 순대, 소시지볶음, 수정과, 약과, 육회

## environment

- python 3.6
- tensorflow 1.15.2
- keras 2.3.0
- opencv-python 4.4.0.44
- pandas 1.1.2
- matplotlib 3.3.2
- scikit-learn 0.23.2



## Model

- VGG16 모델



## Limit

- 로컬에서 훈련시 오랜 시간(No-GPU version 기준 약 8시간)이 걸립니다.
- VGG16 모델로 훈련이 안됩니다.



## ConClusion

-  구글 코랩에서 환경 설정 후 구글 드라이브를 데이터를 로딩하여 훈련할 수 있도록 코랩용 코드 작성합니다.
-  VGG16으로 훈련이 되지 않으므로 다른 Pretrained CNN을 사용합니다.

- Validation셋을 만들어서 하이퍼 파라미터를 튜닝할 예정입니다.




