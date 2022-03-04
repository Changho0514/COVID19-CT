# COVID19 CT_Image Classification

주최 : 중소벤처기업진흥공단 / 주관 : 마인즈앤컴퍼니 (MNC)

## 대회 개요
- **대회 기간** : 2022년 02월 09일 12:00 PM ~ 2022년 02월 15일 12:00 PM
- **문제 정의** : 흉부 CT 이미지를 이용해 코로나19 감염 여부를 이진 분류
- **추진 배경**
	- 코로나 펜데믹 도래와 장기화에 따른 코로나 확진자 분류 필요성 증대
	- 의료 이미지 AI 기술 적용 가능성 확대

----------
- **평가 지표** 
	- **Accuracy (정확도)**
![image](https://github.com/Changho0514/COVID_CT/accuracy.png)

----------
## 문제 접근방법

### 주어진 train image가 645개밖에 되지 않아 deep learning이 불가능하다고 판단, Augmentation을 진행하였습니다.

## 1. Crop
![image](https://cdn.discordapp.com/attachments/940518751974080532/941562702407548958/unknown.png)

Crop하여 동일한 데이터 여러번 학습 시킬 수 있어 Train양이 많아집니다. 


## 2. Clahe

![image](https://cdn.discordapp.com/attachments/940518751974080532/941560175989489774/2022-02-11_2.03.52.png)

### 모델 선정
			
			
			
## 결론

