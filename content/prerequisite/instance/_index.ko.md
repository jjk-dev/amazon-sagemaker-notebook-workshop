---
title: SageMaker Notebook Instance 생성하기
weight: 24
pre: "<b>1-2. </b>"
---

AWS Management Console에서 [Amazon SageMaker](https://ap-northeast-2.console.aws.amazon.com/sagemaker/home?region=ap-northeast-2#/)를 검색합니다.
![snapshot](./images/sagemaker.png)

---

## Region 선택하기 

{{% notice tip %}}
Amazon SageMaker Notebook Instance와 S3 buckect이 동일한 리전에 있도록 생성합니다. 
{{% /notice %}}

본 실습에서는 **Asia Pacific (Seoul) ap-northeast-2** region을 선택합니다. 그 후, 좌측 패널에서 **Notebook > Notebook instances** 탭을 클릭합니다.
![snapshot](./images/select-region.png)

---

## SageMaker Notebook Instance 생성하기

1. 우측 상단의 **Create notebook instance** 버튼을 클릭합니다.
![snapshot](./images/create-instance.png)

2. Notebook instance 이름을 `sagemaker-notebook-workshop`으로 작성합니다.
![snapshot](./images/name.png)

3. Permissions and encryption 에 있는 **IAM role**에서는 **Create a new role** 을 선택합니다.
![snapshot](./images/create-role.png)

4. 모두 기본 설정으로 두고, **Create role** 버튼을 클릭합니다.
![snapshot](./images/role-s3.png)

5. IAM role이 생성된 것을 확인하고 **Create notebook instance** 버튼을 클릭합니다.
![snapshot](./images/submit.png)

6. Instance의 **Status**가 **InService**로 바뀔때까지 기다립니다. 대략 3-5 분이 소요됩니다.
![snapshot](./images/status1.png)
![snapshot](./images/status2.png)

7. **Open Jupyter** 버튼을 클릭합니다.
![snapshot](./images/start-notebook.png)

8. Notebook instance의 Jupyter 홈페이지로 이동합니다.                        
![snapshot](./images/notebook-main.png)
---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
