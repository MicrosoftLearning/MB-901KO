﻿---
lab:
    title: '랩: 랩 환경 유효성 검사'
    module: '모듈 0: 과정 소개'
---


모듈 0: 과정 소개
========================

## 실습 랩 - 고객 참여 랩 환경 검증 

시나리오
--------

이 모듈 0 랩에서는 고객 참여 교실 테넌트가 예상대로 작동하는지 확인해 보겠습니다. 개인 자격 증명에 액세스하고 "별칭"을 기록하며 과정 전반에 걸쳐 사용할 Dynamics 365 모델 기반 애플리케이션을 엽니다. 

**중요 참고 사항:** 이 랩에서는 이 과정에서 사용할 실제 Dynamics 365 테넌트와
Power Platform 애플리케이션 라이선스를
제공합니다. Power Platform이 항상 진화하고 있다는 점에 유의해 주세요. 이
문서의 지침은 실제 테넌트에서 경험할 내용과
다를 수 있습니다. 또한 랩을 시작하기 위해 가상 머신에
네트워크를 연결할 때까지 몇 분 정도 지연이 발생할 수 있습니다.

연습 1 - Dynamics 365 애플리케이션에 액세스
---------------------------------------------------

### 작업 1 – Power Platform 관리 센터에 로그인

1.  <https://admin.Powerplatform.microsoft.com>에 액세스하여 사용자 자격 증명으로 로그인합니다.

2. 사용자 자격 증명에서 **@** 기호까지 종이나 메모장에 기록합니다. 이것은 공유 Dynamics 365 조직 내에서 사용자가 만든 데이터를 구분하는 데 사용할 랩 별칭입니다. 

**중요:** 이 테넌트 및 Dynamics 365 조직은 교실의 다른 학생들과 공유됩니다. 이는 직원들이 조직 소유의 Dynamics 365 인스턴스를 사용할 때 테넌트를 공유하는 것과 같습니다. 레코드를 만들 때 PII(개인 식별이 가능한 정보)를 사용하지 마세요. 또한 만든 모든 레코드, 데이터, 앱, 흐름 등의 앞에 사용자 이름을 접두사(예: **mollyc**)로 붙이는 것도 좋습니다.

3. Power Platform 관리 센터를 자유롭게 탐색할 수 있지만 **변경하지는 마세요.**

### 작업 2 – Dynamics 365 애플리케이션에 액세스

1.  화면 왼쪽 상단에 있는 표 단추를 **Power Platform 관리 센터** 바로 왼쪽까지 펼칩니다. **Dynamics 365**를 선택합니다.

2.  **편집** 단추를 선택합니다. **Power Platform 관리 센터**에서 Contoso 환경을 엽니다.

4. 사용할 수 있는 Dynamics 365 앱 목록에서 **Sales**를 선택합니다.

5. 몇 분 간 애플리케이션을 살펴봅니다.