---
title: 실습 리소스 정리
weight: 40
pre: "<b>3. </b>"
---

{{% notice warning %}}
**Important:** 본 실습을 마치면 사용한 AWS 계정에 비용이 추가로 발생하지 않도록 사용한 리소스를 삭제해야 합니다.
{{% /notice %}}

---

## Instances 중지
실행중인 instance의 라디오 버튼을 클릭한 후, **Actions 버튼**을 누릅니다. 드롭다운 메뉴에 있는 **Stop**을 클릭해 instance를 중지합니다.

![image](/images/99_cleanup/stop.png)

---

## Endpoint 삭제
생성한 Endpoint가 남아있지는 않는지 확인합니다. Endpoint가 남아있다면 삭제합니다. 좌측 패널의 **Inference > Endpoints** 탭을 클릭한 후, **InService** 상태의 endpoint를 클릭합니다. 그 다음 **Action 버튼**을 누르고 **Delete**를 선택합니다. 

![image](/images/99_cleanup/remove-endpoint.png)

---
© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.

