# 기능 목록

## 미션 제출 방법
- [ ] 미션 구현 완료 후, GitHub을 통해 제출.
- [ ] 우아한테크코스 사이트에 제출.

## 과제 제출 전, 주의!!
- [ ] 요구사항에 명시된 출력 값 형식을 지켜야 함.
- [ ] 가이드에 따라 테스트를 실행(npm test)하고 모든 테스트가 성공하는지 확인.

## 기능 요구 사항
- [ ] 1에서 9 사이의 중복되지 않는 3자리 수를 랜덤 선정.
- [ ] 3자리 수를 입력받음.
    - [ ] 숫자가 아닌 경우 예외 출력. (* throw 문을 사용해 예외 발생, 종료 시킴.)
    - [ ] 3자리 자연수가 아닌 경우 예외 출력.
    - [ ] 중복된 숫자가 존재할 경우 예외 출력
- [ ] 랜덤 수와 입력받은 수를 비교하여 힌트 주고 반복함.
    - [ ] 숫자와 자릿수가 겹치는 경우 : 스트라이크
    - [ ] 숫자만 겹치는 경우 : 볼
    - [ ] 세 가지 숫자가 모두 겹치지 않는 경우 : 낫싱
    - [ ] 세 가지 숫자와 자릿수가 모두 겹치는 경우, 게임 종료.
- [ ] 게임 종료 시, 다시 시작할지 완전히 종료할지 선택.
    - [ ] 1을 입력 : 재시작
    - [ ] 2를 입력 : 종료
    - [ ] 1, 2 이외를 입력 : 예외 출력

## 추가적인 나 자신에게의 요구사항!!
- [ ] 반드시! 기능 하나 완성 할때마다 커밋하기.
- [ ] 코드 작성/커밋 메시지 컨벤션 읽어보기.
- [ ] 리팩토링 하기.