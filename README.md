# 24_2_BE_Beginner_Week2_team3
# 2주차 - 자바 활용하기

## **🌟 과제 개요**

---

2주차 과제는 팀 프로젝트로 진행되며, 각 팀원은 **“최소 하나의 클래스”**를 설계하고 구현하는 것이 목표입니다. 각자의 클래스는 다른 팀원의 클래스와 **“조합”** 또는 **“상속”**을 통해 상호작용해야 합니다. 

자바의 객체지향 개념을 기반으로 팀 내에서 협력하여 프로젝트를 완성해주시면 됩니다.

**📅 제출 기한**: 24일(화) 오전(12:00)까지

## **📝 과제 방식**

---

1. 팀 내에서 **공통점, 공통 관심사를 알아보고, 관련하여 주제를 선택**한다.
    - 공통 관심사가 도저히 없다면 팀내에서 원하는 주제를 정해도 됩니다!
2. 각 팀은 아래의 **“요구사항”에 맞게 자바 클래스들을 설계하고 구현**한다.
    - 팀 내에서 역할을 잘 분배하여 프로젝트를 완성해주세요.
3. **24일(화) 오전까지 프로젝트를 깃허브에 업로드**하며, **24일 19시 프로젝트에 대해 발표**를 진행한다.
    - 발표 자료는 자유이나 필수는 아닙니다.
    - 코드 설명과 함께, 회의, 개발 과정이나 어려웠던 점 등 자유롭게 공유해주세요.
4. 발표 후 각 팀은 **다른 팀의 레포지토리에 코드 리뷰**를 남긴다.
    - 궁금한점이나, 1주차에 받은 질문 중 스스로 공부한 부분을 질문으로 남겨도 괜찮습니다!

## **🛠️ 요구사항**

---

- 각 팀원은 **최소 하나의 클래스를 설계 및 구현**해야 합니다.
    
    <aside>
    
    - 각 클래스는 다른 팀원의 클래스와 **조합** 또는 **상속**을 통해 상호작용해야 합니다.
    - **조합은 팀내에서 최소 한번 이상 사용**되어야 하며, **생성자 주입 방식**을 사용하는 것을 권장합니다.
        
        [생성자 주입과 조합, 상속의 간단한 예시](https://www.notion.so/4a5e973c3d2f4bae9b1da4e7f77891ab?pvs=21)
        
    </aside>
    
- **팀 내 최소 1번은 다음의 자바 요소를 사용**해야합니다.(모두가 구현할 필요는 없습니다)
    
    <aside>
    
    - 조합(composition)
    - static
    - interface와 implements
    - java.util의 자료구조 중 하나
    - getter, setter
    - generic
    - optional
    - 커스텀 Exception
        - optional과 연계해도 좋습니다!
    - 포함되어 있지 않더라도, 학습한 내용을 자유롭게 활용해주시면 됩니다.
    </aside>
    
- **깃허브 관련 요구사항**
    
    <aside>
    
    - **레포지토리는 어디 올리나요?**
        - [GDSC 공식 깃허브 오가니제이션](https://github.com/GDSC-PKNU-Official)에 “24_2_BE_Beginner_Week2_team1” (팀 이름은 자유롭게)의 이름으로 레포지토리를 생성하면 됩니다.
        - 아직 [GDSC 공식 깃허브 오가니제이션](https://github.com/GDSC-PKNU-Official)에 초대 되지 않은 분들은 깃허브 아이디, 이메일과 함께 연락주세요.
    - **브랜치는 어떻게 작업하나요?**
        - 프로젝트는 각자의 브랜치를 생성하여 main으로 PR을 올리고 머지하는 방식으로 진행합니다.
        - 최대한 깃허브로 협업을 하되, 어렵다면 우선 하나의 PR로 올려도 괜찮습니다.
        - 이 과정에서 코드 리뷰는 자유입니다.
    - **이슈는 작성해주세요**
        - 각자의 클래스 요구사항은 이슈를 작성하여 올립니다.
        - 깃세션에서 배운 이슈 트래킹 방식을 사용해주세요
            - PR에는 #{이슈 번호}를 통해 트래킹해주세요.
    - **PR에는 팀원과 “coke98” 리뷰어 설정을 해주세요.**
    </aside>
    
- **권장 사항**
    
    <aside>
    
    - 각 클래스의 역할과 책임이 명확해야 하며, 객체지향의 **SOLID 원칙**을 준수하는 것을 권장합니다.
    - 클래스당 **하나의 역할만 다룰 수 있도록 최대한 여러개로 나누어서 작성**하면 좋습니다.
    - private과 public을 잘 활용하여 **필요한 경우만 public**으로 열어두도록 합니다.
    - 팀원들간에 코드를 리뷰할 경우, **컨벤션(네이밍, 개행, 띄어쓰기 등)도 확인**하면 좋습니다.
    - 깃허브 레포지토리 **readMe.md에 해당 노션 글 또는 소개글을 업로드**하는 것도 권장합니다!
    - **커밋에서도 컨벤션이나 이슈 트래킹을 활용**해보시면 좋습니다. 기회가 된다면 깃세션에서 사용해보았던 템플릿을 활용해보는 것도 좋습니다 :)
        
        [깃허브 템플릿(PR, ISSUE) 사용법](https://www.notion.so/PR-ISSUE-107a618a3efb80638091d2e29fba59b2?pvs=21)
        
        ```jsx
        // 예시 커밋 컨벤션(이슈 트래킹 포함)
        feat: 변경사항 메시지
        
        - 세부 사항(옵션)
        - 세부 사항(옵션)
        
        ref: #{이슈번호}
        ```
        
    </aside>
    

## **💡 예시 주제**

---

- **차량 만들기**: 엔진, 타이어, 핸들 등의 클래스를 구현하여 차량 객체를 구성
- **악기 만들기**: 기타, 드럼, 피아노 등의 클래스를 구현하여 악기 객체를 구성
- **자판기 만들기**: 자판기 클래스와 음료나 간식 등의 상품 클래스를 구현하여 상호작용
- **도서 시스템, 쇼핑, 카페** 등 자유로운 주제 중 하나를 선택해주시면 됩니다.

