# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 강상현
- 리뷰어 : 김주아


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 네 test를 통해 계좌 생성, 입금·출금, 이자 지급, 거래 내역 출력 등
    과제 요구사항을 충족하는 것을 확인하였고 완성된 코드가 제출되었습니다.
    <img width="335" height="415" alt="Image" src="https://github.com/user-attachments/assets/c3b4b89b-dd6b-417f-835f-2856bb5a4a84" />
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 입금과 이자 지급이 함께 얽혀있는 deposit()메서드가 가장 핵심적인 코드블록으로 보입니다.
    입금 조건, 입금 횟수 관리, 이자 지급 조건에 대한 주석이 작성되어 있어 로직의 의도를 파악할 수 있었습니다.
    특히 입금 5회마다 이자가 발생하는 구조와 이를 위해 입금 횟수와 거래 횟수를 분리해 관리한 이유가
    주석으로 설명되어 있어 이해하는 데 큰 어려움은 없었습니다.
    <img width="581" height="273" alt="Image" src="https://github.com/user-attachments/assets/91003c10-812d-4eda-8c43-7a0a129daef1" />
        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 입금 횟수 기반 이자 지급 로직, 거래 횟수 분리 관리 등 조건 처리 과정을 고민한 흔적이 보였습니다.
    <img width="557" height="319" alt="Image" src="https://github.com/user-attachments/assets/9b9ce514-b1cb-4ce2-bf8f-23ecbd2295bd" />
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 계좌 생성부터 입·출금, 이자 지급, 거래 내역 출력까지 전체 코드 실행 흐름을 글로 정리하여 이해를 돕고 있습니다.
    <img width="458" height="41" alt="Image" src="https://github.com/user-attachments/assets/305bc0be-12c0-4b87-94a2-2224e839977d" />

- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 클래스와 메서드 단위로 기능을 분리하여 코드 중복을 줄이고 구조적으로 작성하였습니다.
    - 전반적으로 PEP8 스타일을 크게 벗어나지 않습니다.
    - 다만 일부 로직은 내장 함수나 자료구조를 활용하면 더 간결한 형태로 개선할 수 있을 것 같습니다.
    <img width="520" height="95" alt="Image" src="https://github.com/user-attachments/assets/88b3a939-4e5e-466d-a550-d415452b74d5" />
    

# 회고(참고 링크 및 코드 개선)
코드를 리뷰하며 클래스 설계와 기록 관리 방식을 좀 더 이해할 수 있었습니다. 
기능을 분리하여 과제 요그사랑을 전반적으로 잘 충족하였고 주석을 통해 흐름을 이해하기 좋았습니다.
다만 이자금액을 소수점으로 남아 출력시 표현이 다를 수 있는데 이부분은
저희 팀에서도 마지막에 수정한 부분이라 수정이 되었다면 더울 깔끔하게 출력될 수 있을 것 같습니다.
