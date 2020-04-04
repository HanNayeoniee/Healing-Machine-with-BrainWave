# 뇌파 힐링기
# Healing Machine with BrainWave
![image](https://img.shields.io/badge/license-Apache--2.0-green)

[요약](#요약)  
[기획 배경](#기획-배경)  
[개발 기간](#개발-기간)  
[개발자](#개발자)  
[사용 하드웨어](#사용-하드웨어)  
[사용 프로그램](#사용-프로그램)  
[알고리즘](#알고리즘)  
[결과](#결과)  

---


## 요약 

  - 뇌파를 이용하여 사용자의 감정(+/-)을 판단한다.
  
  - 사용자의 감정이 좋지 않을 때에는 이를 개선하기 위한 __자연 영상__을 재생한다.
  
  - 사용자의 감정이 좋을 때에는 좋은 기분을 유지시킬수 있도록 사용자가 평소 좋아하는 노래를 재생한다.
  
  - __Projection mapping__ 을 이용하여 3면에 화면을 띄워 몰입도를 높였다. 

---
## 기획 배경
- 현대인의 스트레스를 완화시켜 주고 싶다.

- 스트레스를 받는 현대인이 점점 증가하고 있는 추세이다.
- 자연 영상을 보는 것만으로도 우울이나 불안감이 감소하고, 기분이 좋아졌다는 연구 결과가 있다.
- 특히 청색과 녹색이 스트레스의 완화에 효과적이며, 자연 소리는 마음을 편안하게 해준다.  

__-->자연 경관을 보여줌으로써 현대인의 스트레스를 완화시켜주는 프로그램을 기획하게 되었다.__

---
## 개발 기간
- 2018/08/24~2018/09/10
---

## 개발자
- [김나혜(nahye03)](https://github.com/nahye03), [정민지(minji-o-j)](https://github.com/minji-o-j/), [한나연(HanNayeoniee)](https://github.com/HanNayeoniee/)
---
## 사용 하드웨어

- [MindWave Mobile 2: Brainwave Starter Kit](https://store.neurosky.com/pages/mindwave)

  ![image](https://user-images.githubusercontent.com/45448731/78454346-7e284700-76d2-11ea-91e0-2a6d09180e74.png)

  - EEG power spectrums, 12bit Raw-Brainwaves
  - 뇌파의 품질 분석 기능
- 빔 프로젝터

---
## 사용 프로그램

- __Visual Studio__: 프로그래밍, 뇌파 관련 데이터 처리, 상태 그래프  

- __Resolume Arena 4__: Projection mapping, 사용자 기분에 맞는 화면 전환  

- __Adobe After Effects CS6__: 노래에 따른 시각 효과  

---
## 알고리즘
![image](https://user-images.githubusercontent.com/45448731/78454999-c34e7800-76d6-11ea-870c-725ff5c55443.png)  
<br>

### 긍/부정도 판단 방법

![image](https://user-images.githubusercontent.com/45448731/78456092-b6348780-76dc-11ea-87fa-1cab000c4e2f.png)  
> 스트레스를 받을 때 나오는 `“high beta”파`를 측정하여 기분의 좋음과 나쁨을 판단하였다.
<br>


![image](https://user-images.githubusercontent.com/45448731/78455108-5b4c6180-76d7-11ea-9cdf-87b660785cd5.png)
![image](https://user-images.githubusercontent.com/45448731/78455111-5e475200-76d7-11ea-957c-ef475c8baf6d.png)
> 13명x2번의 실험을 통해 얻어진 데이터를 분석하여 긍/부정의 기준 지표를 정하였다.
---
  
## 결과
- 본 프로젝트의 전시를 위하여 프로그램을 `사용자의 중립 데이터 측정`-`기분을 나쁘게or좋게 만드는 영상`-`결과에 따른 랜덤 영상 시청` 으로 구성하였다.  
<br>

![image](https://user-images.githubusercontent.com/45448731/78456274-ac5f5400-76dd-11ea-96c1-c8e612cbc692.png)
> 중립 데이터 측정 화면
- 사용자의 중립 뇌파를 받는다.
- 이 화면은 실제로 35초정도 띄워지지만 노이즈를 줄이기 위해 실제로 중간의 30초만 측정한다.(안내 문구 후 30초 countdown을 실행)
<br>

![image](https://user-images.githubusercontent.com/45448731/78456277-b08b7180-76dd-11ea-8d22-5c6752593c4d.png)  
> 기분을 좋게/나쁘게 만들어주는 영상 시청 화면  
- 사용자의 기분을 단시간에 좋게/나쁘게 만들어주는 영상을 재생한다.
<br>

![image](https://user-images.githubusercontent.com/45448731/78456281-b2edcb80-76dd-11ea-84a4-04f6a4113f6e.png)  
> 기분이 나빠졌을 때 나오는 화면  
- 기분 개선에 도움이 되는 자연 영상을 재생한다.
<br>

![image](https://user-images.githubusercontent.com/45448731/78456284-b5502580-76dd-11ea-90f5-145e3bd0456a.png)
> 기분이 좋아졌을 때 나오는 화면
- 사용자의 좋은 기분을 계속 유지할 수 있도록 사용자가 좋아하는 노래 + 자연 영상을 재생한다.
<br>

![image](https://user-images.githubusercontent.com/45448731/78456291-ba14d980-76dd-11ea-8514-cf5f33fcc1d8.png)  
> 사용자가 감정을 측정하는 동안 뜨는 그래프
- 사용자는 모니터를 통하여 자신의 감정이 변화하고 있는 것을 실시간으로 확인할 수 있다.  
<br>

![image](https://user-images.githubusercontent.com/45448731/78456288-b719e900-76dd-11ea-8d83-5e1459b6ead6.png)  
> 사용자의 기분이 개선되었음을 알리는 문구
- 기분이 나빠졌을 때 자연을 보고 기분이 개선되었다고 판단된 경우 문구가 나온다.
- 기분이 좋을 때 일정 시간 후에도 계속 좋은 기분이 유지되는 경우 문구가 나온다.

---
