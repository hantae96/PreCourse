# 로또 시뮬레이션

## 기능 목록
- [x] 구입 금액에 해당하는 로또만큼 발행하는 기능 - makeRandomNumber()

InputOutput 클래스 내에서
- 입력 받은 번호의 유효성 검사 기능
    - [x] 길이 검사 기능 - validateLength()
    - [x] 중복 검사 기능 - validateRange()
    - [x] 문자열 입력시 오류 출력
- [x] 로또 구입 금액 을 입력받는 기능 - setMoney()
- [x] 당첨 번호를 입력 받는 기능 - setUserInputNumber()
- [x] 보너스 번호를 입력 받는 기능 - setUserBonusNumber()
Calculate 클래스 내에서
- [x] 발행된 로또 번호와 당첨 번호 + 보너스 번호를 조합해 비교하는 기능 - compareNumber()
- [x] 당첨내역을 출력하는 기능 - InputOutput.printResult()
- [x] 수익률을 계산하는 기능 -rateOfReturn()

## 기능 요구 사항
로또 게임 기능을 구현해야 한다. 로또 게임은 아래와 같은 규칙으로 적용된다.
로또 번호의 숫자 범위는 1~45까지이다.
- 1개의 로또를 발행할 때 중복되지 않는 6개의 숫자를 뽑는다.
- 당첨 번호 추첨 시 중복되지 않는 숫자 6개와 보너스 번호 1개를 뽑는다.
- 당첨은 1등부터 5등까지 있다. 당첨 기준과 금액은 아래와 같다.

```
1등: 6개 번호 일치 / 2,000,000,000원
    - 2등: 5개 번호 + 보너스 번호 일치 / 30,000,000원
    - 3등: 5개 번호 일치 / 1,500,000원
    - 4등: 4개 번호 일치 / 50,000원
    - 5등: 3개 번호 일치 / 5,000원
```

### 세부 기능 요구 사항
- 로또 구입 금액을 입력하면 구입 금액에 해당하는 만큼 로또를 발행해야 한다.
- 로또 1장의 가격은 1,000원이다.
- 당첨 번호와 보너스 번호를 입력받는다.
- 사용자가 구매한 로또 번호와 당첨 번호를 비교하여 당첨 내역 및 수익률을 출력하고 로또 게임을 종료한다.
- 사용자가 잘못된 값을 입력할 경우 IllegalArgumentException를 발생시키고, "[ERROR]"로 시작하는 에러 메시지를 출력 후 종료한다.



