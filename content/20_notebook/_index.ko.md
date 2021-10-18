---
title: SageMaker Notebook
weight: 20
pre: "<b>2. </b>"
---

본 실습에서는 Jupyter notebook을 실행해 SageMaker에서 어떻게 훈련하고 배포하는지 배웁니다.

---
## Jupyter notebook 다운로드

1. 우측 상단의 **New** 버튼을 클릭하고 **conda_tensorflow2_p36** 커널을 선택해 notebook을 띄웁니다.
![image](/images/20_notebook/start-kernel.png)

2. 다음 명령어를 복사하여 셀에서 실행합니다. 셀을 실행하기 위해서는 상단의 **Run** 버튼을 클릭하거나 **Shift+Enter** 키를 누릅니다.
```
!git clone https://github.com/jjk-dev/sagemaker-notebook-examples-kr.git
```
![image](/images/20_notebook/git-clone.png)

3. Home으로 돌아가면 **sagemaker-notebook-examples-kr** 폴더가 생성된 것을 볼 수 있습니다.  
![image](/images/20_notebook/folder.png)

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
