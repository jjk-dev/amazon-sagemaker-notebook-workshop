---
title: Pre-trained 모델 사용하기
weight: 44
pre: "<b>2-2. </b>"
---

본 실습에서는 pre-trained한 mobilenet으로 이미지 분류 모델을 불러옵니다.

---

## S3 bucket 이름 복사

앞서 생성한 **S3 bucket 이름**을 복사합니다.
![image](/images/20_notebook/20_pre-trained/s3.png)

---

## Jupyter notebook 실행하기

1. **sagemaker-notebook-examples 폴더** > **2. Image-classification-with-pre-trained-model.ipynb**을 클릭합니다.
![image](/images/20_notebook/20_pre-trained/pt-notebook.png)

2. 3번째 셀에 앞서 복사한 **S3 bucket 이름**과 **학번**을 입력합니다.
![image](/images/20_notebook/20_pre-trained/replace.png)

3. Jupyter notebook에서 **Shift+Enter**로 모든 셀을 실행하고, 모델이 import 된 것을 확인합니다.
![image](/images/20_notebook/20_pre-trained/result.png)

4. 본 실습에서는 hosting과 추론을 하지 않습니다. 만약 진행했다면 필히 마지막 셀의 주석처리를 제거하여 **Endpoint를 삭제**합니다.
![image](/images/20_notebook/20_pre-trained/delete-endpoint.png)

{{% notice warning %}}
**Important:** Hosting을 수행하셨다면, **Endpoint**를 꼭 삭제해 추가적인 과금이 발생하지 않도록 합니다.
{{% /notice %}}

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
