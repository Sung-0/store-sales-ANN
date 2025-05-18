매장의 세일데이터를 활용한 세일 예측![image](https://github.com/user-attachments/assets/48608e6b-e7a3-4114-83b6-05f1108694a5)

﻿1. 프로젝트 개요
본 프로젝트는 매장의 세일데이터를 활용하여 세일 여부를 예측하는 인공신경망(ANN)모델을 개발하는 것을 목표로 합니다. 본 모델은 판매 데이터에 기반하여 향후 세일 여부를 예측함으로써 매출 관리 및 마케팅 전략 수립에 도움을 주고자 합니다. 모델은 Jupyter Notebook 환경에서 개발되었으며, 은닉층 2개, 활성화 함수 ReLU, 출력층 회귀 모델로 구성되었습니다.
또한, 모델의 성능을 향상시키기 위해 다음 다섯 가지 옵티마이저를 적용하여 비교 분석 하였습니다.
◆  SDG
◆ Momentum
◆ AdaGrad
◆ RMSProp
◆ Adam![image](https://github.com/user-attachments/assets/0b0b63b9-4207-46de-8d35-9234f56d859c)

﻿각 옵티마이저에 대해 **정확도(Accuracy)**와 **손실율(Loss)**을 측정하여 엑셀 시트로 정리, 성능 비교를 수행하였습니다. 이를 통해 최적의 하이퍼파라미터 조합을 도출하고, ANN 기반의 세일 예측 모델을 구축하는 것이 본 프로젝트의 핵심입니다. ![image](https://github.com/user-attachments/assets/d4552268-5582-4c63-992e-8eee41bebd37)

﻿7. 하이퍼파라미터 실험 결과
다양한 옵티마이저와 하이퍼파라미터를 실험하여 최적의 조합을 찾았습니다. 각 옵티마이저 및 하이퍼파라미터에 대한 실험 결과를 표로 정리합니다.
Optimizer	Loss	val_Loss	R² Score
Momentum	1178834.12	1241083.50	0.6205
AdaGrad	1174628.88	1244086.88	0.6191
SGD	1194352.50	1249653.62	0.6144
Adam	1198483.12	1261931.50	0.6137
RMSProp	1199018.62	1262615.62	0.6131
8. 예측 성능 비교 및 시각화![image](https://github.com/user-attachments/assets/dc6d3938-c40e-40f8-97a8-98e2932b9918)
