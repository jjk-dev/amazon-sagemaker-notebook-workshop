---
title: BYOM 사용하기
weight: 23
pre: "<b>2-3. </b>"
---

본 실습은 BYOM (Bring Your Own Model) 방식을 사용하며, Pre-trained한 mobilenet으로 이미지 분류 모델을 불러옵니다.

---

## Jupyter notebook 실행하기

1. **sagemaker-notebook-examples-kr 폴더** > **2. Image-classification-with-byom.ipynb**을 클릭합니다.
![image](/images/20_notebook/20_pre-trained/pt-notebook.png)

2. 본 실습 파일에는 결과가 포함되어 있습니다. 실행한 셀이 헷갈리지 않도록 상단의 탭에서 **Kernel** > **Restart & Clear Output** 을 클릭해 결과를 없애주세요.
![image](/images/20_notebook/5_open-xgboost/clear-output.png)

3. **S3 bucket 이름**을 S3를 생성할 때 사용하셨던 `sagemaker-workshop-성함`으로 변경합니다.
![image](/images/20_notebook/20_pre-trained/replace.png)

4. Jupyter notebook에서 각 셀의 설명을 참고해주시고, **Shift+Enter**로 모든 셀을 실행합니다. 모델이 import 된 것을 확인합니다.
![image](/images/20_notebook/20_pre-trained/result.png)

5. Deploy에서 **instance type**을 `'ml.c5.xlarge'`로 변경합니다. Endpoint을 생성하는 Hosting 부분은 3-5 분 정도 소요됩니다. 
![image](/images/20_notebook/20_pre-trained/deploy.png)

6. Hosting이 완료되면 추론을 통해 모델의 성능을 확인합니다.
![image](/images/20_notebook/20_pre-trained/hosting.png)

7. 마지막 셀의 주석처리를 제거하여 **Endpoint를 삭제**합니다.
![image](/images/20_notebook/20_pre-trained/delete-endpoint.png)

{{% notice warning %}}
**Important:** Hosting을 수행하셨다면, **Endpoint**를 꼭 삭제해 추가적인 과금이 발생하지 않도록 합니다.
{{% /notice %}}

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
