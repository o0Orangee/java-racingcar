# domain
- ## Car(자동차) ##
    - 이름
    - 전진 거리

- ## CarName(자동차 이름) ##
    - 미입력 or 5글자 초과 확인

- ## Distance(이동 거리) ##
    - 정지 or 거리 증가

- ## Cars(자동차 리스트) ##
    - 자동차들의 정보(중복 이름 X)
    - 우승자 판별

- ## TryConut(시도 횟수) ##
    - 음수 입력 X (횟수 상한은 없나??)

# ~~dto~~

# controller
- 이름 입력받아서 Cars로 저장
- 시도 횟수 입력받아 TryCount로 저장
- 레이스 진행
- 결과 출력

# utils
- ## Parser ##
    - 이름: 쉼표 기준으로 분리
    - 시도 횟수

- ## RandomNumberGenerator ##
    - 0~9 랜덤 숫자 생성기

# view
- ## InputView ##
    - 자동차 이름 입력
    - 시도 횟수 입력

- ## OutView ##
    - 실행 결과 출력
    - 우승자 출력