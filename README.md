#군산대학교 캡스톤 디자인
### TEAM S.F.suffer

# Multiple-pest-detection-object-models


### 해충 카운팅을 하기 위해서 기존의 군중 카운팅에 특화 되어있는 딥러닝 모델 사용

기존의 군중 카운팅을 객체 탐지 기법과 밀도맵 추정 기법이 존재한다. 
밀도맵 추정 기법에는 KDMG, ICCNet, DM-Count, MCNN, SANet 등이 대표적으로 있는데
5가지 모델을 해충 데이터로 학습을 시켜 실험을 하였을때 가장 성능이 좋은것은 Staced KDMG 였다. 
따라서 밀도맵 기반 카운팅을 위한 모델로는 Stacked KDMG를 사용하여서 해충 카운팅을 진행한다.





Flask(플라스크) 




