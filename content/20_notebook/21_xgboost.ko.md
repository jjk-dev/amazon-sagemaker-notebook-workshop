---
title: 오픈소스 알고리즘 사용하기
weight: 21
pre: "<b>2-1. </b>"
---

본 실습에서는 오픈소스 알고리즘인 XGBoost를 이용해 은행 사기 탐지 모델을 train, tune 그리고 deploy를 합니다.

---

## Jupyter notebook 실행하기

1. **sagemaker-notebook-examples-kr 폴더** > **wo-eda 폴더** > **1. Banking-fraud-with-XGBoost-wo-eda.ipynb**을 클릭합니다.
![image](/images/20_notebook/5_open-xgboost/open-xgb-notebook-wo-eda.png)

2. 본 실습 파일에는 결과가 포함되어 있습니다. 실행한 셀이 헷갈리지 않도록 상단의 탭에서 **Kernel** > **Restart & Clear Output** 을 클릭해 결과를 없애주세요.
![image](/images/20_notebook/5_open-xgboost/clear-output.png)

3. **S3 bucket 이름**을 S3를 생성할 때 사용하셨던 `sagemaker-workshop-성함`으로 변경합니다. 
![image](/images/20_notebook/10_xgboost/replace.png)

4. 그 후, Jupyter notebook에서 **Shift+Enter**로 모든 셀을 실행하셔 모델을 훈련해주세요. Notebook의 각 셀의 설명을 참고해주세요. 

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.

