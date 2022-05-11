---
title: 리소스 정리
weight: 99
pre: "<b>99. </b>"
---

{{% notice warning %}}
**Important:** 본 실습을 마치면 사용한 AWS 계정에 비용이 추가로 발생하지 않도록 사용한 리소스를 삭제해야 합니다.
{{% /notice %}}

---

## Instances 정지
실행중인 instance의 라디오 버튼을 클릭한 후, **Actions 버튼**을 누릅니다. 드롭다운 메뉴에 있는 **Stop**을 클릭해 instance를 정지합니다.

![image](/images/99_cleanup/stop.png)

---

## Endpoint 삭제
생성한 Endpoint가 남아있지않는지 확인합니다. Endpoint가 남아있다면 **모두** 삭제합니다.

좌측 패널의 **Inference > Endpoints** 탭을 클릭한 후, **InService** 상태의 endpoint를 클릭합니다.
그 다음 **Action 버튼**을 누르고 **Delete**를 선택합니다. 

![image](/images/99_cleanup/remove-endpoint.png)

---

## SageMaker Canvas 앱 삭제
생성한 SageMaker Canvas 앱을 삭제합니다. 

SageMaker 콘솔에서 좌측 패널의 **Control panel** 탭을 클릭한 후 **Users** 섹션에서 **Name**을 클릭합니다.
   
![image](/images/99_cleanup/control-panel.png)

User Details의 Apps 목록에서 사용중인 **모든** App을 삭제합니다. **Action** 밑의 **Delete app** 
버튼을 클릭합니다.

![image](/images/99_cleanup/delete-canvas.png)

Delete app 창이 뜨면**Yes, delete app** 버튼을 클릭하고, 활성화된 빈칸에 `delete`를 입력합니다.
그 후, **Delete** 버튼을 클릭하면 됩니다.

![image](/images/99_cleanup/delete-app.png)

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
