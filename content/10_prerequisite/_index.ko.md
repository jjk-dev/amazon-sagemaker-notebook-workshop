---
title: 사전 준비사항
weight: 10
pre: "<b>1. </b>"
---

## 데이터셋 다운로드

매년 수십억 건의 은행 거래가 발생하고, 사기인 경우는 거의 없지만 거래를 제대로 탐지하지 않으면 그 피해가 엄청납니다. 피해 비용은 고객과 기업, 그리고 거래를 검증해야하는 금융 규제 당국에게도 막대합니다.

본 워크샵에서는 **은행 사기 감지** 데이터셋을 처리하여 사기 거래를 자동으로 감지하는 ML 모델을 만듭니다. 이 데이터셋은 아프리카 국가에서 구현한 모바일 거래 시뮬레이션으로 한달 간의 거래 로그에서 추출한 실제 거래 샘플을 기반으로 합니다. 데이터는 [kaggle](https://www.kaggle.com/)에서 다운로드 할 수 있습니다.

여기에서는 실습을 보다 쉽게 수행하도록 데이터셋을 가공했습니다. **다음 CSV 파일을 다운로드하면 됩니다.**

{{% attachments style="blue" pattern=".*(csv)" /%}}

---

## Header 설명

![image](/images/10_prerequisite/data-preview.png)

- type - 거래 유형 (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER)
- amount - 거래 금액
- nameOrig - 거래를 시작한 주체
- oldbalanceOrg - 거래 시작 주체의 거래 이전 잔고
- newbalanceOrig - 거래 시작 주체의 거래 이후 잔고
- nameDest - 거래 대상 주체
- oldbalanceDest - 거래 대상의 거래 이전 잔고
- newbalanceDest - 거래 대상의 거래 이후 잔고
- isFraud - 사기 여부

---

© 2021 Amazon Web Services, Inc. 또는 자회사, All rights reserved.
