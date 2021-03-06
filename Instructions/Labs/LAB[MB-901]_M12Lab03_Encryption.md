---
lab:
    title: '랩 03: 데이터를 암호화하여 보안 강화'
    module: '모듈 12: Dynamics 365 보안 인식'
---

# MB-901: Dynamics 365 기본사항
## 모듈 12, 랩 3: 데이터 암호화를 통해 보안 강화

**시나리오:** 시스템 관리자로서 당신은 조직 암호화 키를 변경하고 복사해야 합니다.

**참고:**  이 랩에는 환경에 대한 관리자 액세스가 필요하므로 강사가 시연해야 합니다.

## 지침

1. Power Platform 관리 센터로 이동합니다.  
1. 이러한 설정은 **환경** > [환경 선택] > **설정** > **암호화** > **데이터 암호화**에서 찾을 수 있습니다.
1. **암호화 키 변경** 상자에서 새 암호화 키를 입력한 다음 **변경**을 선택합니다.
1. 확인 메시지에서 **확인**을 선택한 다음 **닫기**를 선택하여 **데이터 암호화** 페이지를 종료합니다.

데이터 암호화 키의 복사본을 만드는 것을 강력히 권합니다.

1. 1~4단계에서 사용한 것과 동일한 환경을 선택하고 **설정** > **암호화**로 이동합니다.
1. **데이터 암호화** 대화 상자에서 **암호화 키 표시**를 선택하고 **현재 암호화 키 상자**에서 암호화 키를 선택한 다음 클립보드에 복사합니다.
1. 암호화 키를 메모장과 같은 텍스트 편집기에 붙여 넣습니다.

**참고:** 기본적으로 Dynamics 365의 모델 기반 앱은 유니코드 문자의 임의 컬렉션인 암호를 생성합니다. 따라서 유니코드 문자를 지원하는 애플리케이션 및 파일을 사용하여 시스템에서 생성된 암호를 저장해야 합니다. 메모장과 같은 일부 텍스트 편집기는 기본적으로 ANSI 코딩을 사용합니다. 메모장을 사용하여 암호를 저장하기 전에 다른 이름으로 저장을 선택한 다음 인코딩 목록에서 유니코드를 선택합니다.

가장 좋은 방법은 컴퓨터에서 암호화된 하드 드라이브의 안전한 위치에 암호화 키가 포함된 텍스트 파일을 저장하는 것입니다.
