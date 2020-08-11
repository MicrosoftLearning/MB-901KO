﻿---
lab:
    title: '랩 01: Dynamics 365 Finance 알아보기'
    module: '모듈 07: Dynamics 365 Finance 소개'
---

# MB-901: Dynamics 365 기본사항 
## 모듈 7, 랩 1 - Dynamics 365 Finance 탐색 


**필수 구성 요소**: 이 랩의 단계를 수행하기 전에
다음 작업: 

**참고:** 이 랩을 수행하기 전에 데모 데이터가 있는 배포된 환경이 필요합니다
. Dynamics 365 Finance and Operations 앱 인스턴스는
LCS에서 또는 인스턴스의 URL로 직접 이동하여 시작합니다.

회사를 **USMF**로 변경해야 합니다. Dynamics 365 Finance and Operations 앱 인스턴스에 로그인하려면 **최고 경영자** 또는 **시스템 관리자** 보안 역할과 함께 사용자 이름과 암호가 있어야 합니다.

환경에 데모 데이터가 없는 경우, 아래 지침을 따릅니다
:

 **모듈>데모 데이터**로 이동하여 **데이터 생성**을 클릭한 다음,
    **확인을 클릭합니다.**

### 환율 가져오기

1.  회사를 **USMF**로 변경합니다.

2.   **총계정원장 > 통화 > 환율 유형**으로 이동합니다.

3.  **신규**를 클릭합니다.

4.  **환율 유형** 필드에 'GTL-EXCH'를 입력합니다.

5.  **이름** 필드에 'Seahorse 환율'을 입력합니다.

6.  **환율**을 클릭합니다.

7.  사용 가능한 환율은 없습니다.

8.  환율 양식 닫기

9.  환율 유형 양식 닫기

10.  **총계정원장 > 통화 > 환율 공급자 구성**으로 이동합니다.

11. **신규**를 클릭합니다.

12.  **러시아 연방 중앙은행** 선택

13. **확인**을 클릭합니다.

14. 페이지를 닫습니다.

15. **총계정원장 > 통화 > 통화 환율 가져오기**로 이동합니다.

16. **환율 유형** 필드에 GTL-EXCH를 입력하거나 선택합니다

17.  **러시아 연방 중앙은행** 선택

18. **환율 제공자** 필드에 **러시아 연방 중앙은행을 입력하거나 선택합니다
    러시아 **

19. **확인**을 클릭합니다.

20.  **총계정원장 > 통화 > 환율 유형**으로 이동합니다.

21.  **GTL-EXCH** 선택

22. **환율**을 클릭합니다.

23. 가져온 값 기록

24. 모든 양식 닫기

### 구매 주문서 만들기, 제품 영수증 게시

1.  **외상 매입금 > 구매 주문 > 모든 구매 주문**으로 이동합니다.

2.  **새로 만들기**를 클릭합니다.

3.  **공급업체 계정** 필드에서 **1001 Acme 사무용품**을 선택합니다.

4.  **창고** 필드에서 **11**을 선택합니다.

5.  **확인**을 클릭합니다.

6.  **항목 번호** 필드에서 **1000 Surface Pro 128GB** 항목을 선택합니다.

7.  작업 창에서 **구매**를 클릭합니다.

8.  **확인**을 클릭합니다.

9.  작업 창에서 **수신**을 클릭합니다.

10. **제품 영수증**을 클릭합니다.

11. **제품 영수증** 필드에 **GTL02020**을 입력합니다.

12. **확인**을 클릭합니다.

13. 모든 양식을 닫습니다.

### 무료 텍스트 송장 만들기

1.  **외상 매출금 > 송장 > 모든 무료 텍스트 송장**으로 이동합니다.

2.  **새로 만들기**를 선택합니다.

3.  **고객 계정** 필드에서 **US-003**을 선택합니다.

4.  **설명** 필드에 **무료 텍스트 송장 안내**를 입력합니다.
    대화 상자에서 **예**를 클릭합니다.

5.  **기본 계정** 필드에서 계정 번호 **110180**을 선택합니다.

6.  **수량** 필드에 **17**을 입력합니다.

7.  **단가** 필드에 **817.00**을 입력합니다. 금액은
    단가에 수량을 곱해 계산됩니다. 그러나 금액을 입력하여
    해당 계산을 조정할 수 있습니다.

8.  **요금**을 선택하여 송장에 요금을 추가합니다.

9.  **요금 코드** 필드에 **화물**을 입력합니다.

10. **요금 값** 필드에 **150**을 입력합니다.

11. 페이지를 닫습니다.

12. **합계**를 선택하여 송장 세부 정보 및 합계의 요약을 봅니다.

13. **닫기**를 선택합니다.

14. **게시**를 선택하여 송장을 게시합니다. 실제로 게시하기 전에
    여전히 취소할 기회가 있습니다.

    -  송장 인쇄 시기를 변경할 수 있습니다. **현재**를 선택하여
        각 송장이 업데이트되면 인쇄합니다. **이후**를 선택하여 모두 인쇄합니다. 
        송장이 업데이트되었습니다.

    -  송장이 게시되기 전에 고객의 신용 한도를 확인하는 방법을 변경하려면
         **신용 한도 유형** 필드에서 값을 변경합니다.

    -  송장을 인쇄하려면 옵션을 **예**로 설정합니다.

    -  송장을 게시하려면 옵션을 **예**로 설정합니다. 송장을 게시하지 않고
        인쇄할 수 있습니다.

15. **확인**을 선택합니다.