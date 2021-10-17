---
title: Built-in 알고리즘 사용하기
weight: 21
pre: "<b>2-1. </b>"
---

본 실습에서는 Built-in 알고리즘은 XGBoost를 이용해 은행 사기 탐지 모델을 train, tune 그리고 deploy를 합니다.

---

## Jupyter notebook 실행하기

1. **sagemaker-notebook-examples-kr 폴더** > **1. Banking-fraud-with-XGBoost.ipynb**을 클릭합니다.
![image](/images/20_notebook/10_xgboost/xgb-notebook.png)

2. **S3 bucket 이름**을 `sagemaker-workshop`으로 입력합니다. 
![image](/images/20_notebook/10_xgboost/replace.png)

3. Jupyter notebook에서 **Shift+Enter**로 모든 셀을 실행합니다. Endpoint을 생성하는 Hosting 부분은 5-10 분 정도 소요됩니다. 
![image](/images/20_notebook/10_xgboost/hosting.png)

4. Hosting이 완료되면 추론을 통해 모델의 성능을 확인합니다.
![image](/images/20_notebook/10_xgboost/result.png)

5. 마지막 셀의 주석처리를 제거하여 **Endpoint를 삭제**합니다.
![image](/images/20_notebook/10_xgboost/delete-endpoint.png)
 
{{% notice warning %}}
**Important:** Hosting을 수행하셨다면, **Endpoint**를 꼭 삭제해 추가적인 과금이 발생하지 않도록 합니다.
{{% /notice %}}

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.

