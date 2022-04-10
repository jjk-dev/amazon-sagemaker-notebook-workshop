---
title: SageMaker Notebook
weight: 20
pre: "<b>2. </b>"
---

본 실습에서는 Jupyter notebook을 실행해 SageMaker에서 어떻게 훈련하고 배포하는지 배웁니다.

---
## Jupyter notebook 다운로드

1. 우측 상단의 **New** 버튼을 클릭하고 가장 아래에 있는 **Terminal** 을 선택해 새 창을 띄웁니다.
![image](/images/20_notebook/start-terminal-1.png)
![image](/images/20_notebook/start-terminal-2.png)

2. 다음 명령어를 복사하여 Terminal에서 실행합니다.
```
cd SageMaker
git clone https://github.com/jjk-dev/sagemaker-notebook-examples-kr.git
```
![image](/images/20_notebook/git-clone.png)

3. 현재 실행중인 Terminal 창을 닫고 **Files 탭**으로 가면, **sagemaker-notebook-examples-kr** 폴더가 생성된 것을 볼 수 있습니다.
![image](/images/20_notebook/folder.png)

---
## Jupyter notebook 실행하기

1. **sagemaker-notebook-examples-kr 폴더** > **1-1. Banking-fraud-prepare-dataset.ipynb**을 클릭합니다.
![image](/images/20_notebook/eda-notebook.png)

2. 본 실습 파일에는 결과가 포함되어 있습니다. 실행한 셀이 헷갈리지 않도록 상단의 탭에서 **Kernel** > **Restart & Clear Output** 을 클릭해 결과를 없애주세요.
![image](/images/20_notebook/5_open-xgboost/clear-output.png)

3. **S3 bucket 이름**을 S3를 생성할 때 사용하셨던 `sagemaker-workshop-성함`으로 변경합니다.
![image](/images/20_notebook/10_xgboost/replace.png)

4. 그 후, Jupyter notebook에서 **Shift+Enter**로 모든 셀을 실행하셔 모델을 훈련해주세요. Notebook의 각 셀의 설명을 참고해주세요.

---
© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
