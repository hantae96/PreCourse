# 기능 요구 사항

구분코드는 대분류에서 소분류로 진행할때 뒷자리를 하나씩 추가함

0. 하나의 게임 단위를 기준으로 요구 사항을 실행시키는 기능 메소드 구현 
1. 숫자 3개를 랜덤 추출 후 변수에 할당하는 기능(#1)
2. 사용자에게 서로 다른 수 3개를 입력하고 컴퓨터에 해당하는 변수와 비교하여 같을 떄까지 비교하는 기능(#2)
   2.1. 입력값이 서로 다른 수 인지 확인하는 기능(#21)
   2.1 입력값의 길이가 3인지 확인하는 기능(#22)
3. 스트라이크,볼,낫싱을 출력하는 기능(#3)
   3.1 같은 수가 같은 자리수에 있으면, 그 갯수만큼 스트라이크를 출력(#31)
   3.2 같은 수는 아니지만 다른 자리에 있다면, 다른 자리 수에 있으면 그 갯수만큼 볼 출력(#32)
   3.3 같은 수도 아니고 같은 자리수도 있지 않으면 낫싱 출력(#33)
4. 게임이 끝난 경우를 1(재시작) 2(종료)로 구분하는 기능(#4)
