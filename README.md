# ATP-Match-Prediction
ATP 데이터셋을 이용한 승자 예측 머신러닝

---
## ATP Tennis 데이터셋
- [ATP Dataset csv 다운로드](https://raw.githubusercontent.com/your_username/your_repository/master/ATP%20Dataset_2012-01_to_2017-07_Int_V4.csv)

- 컬럼 종류
  * ATP	: 년도별 대회순서
  * Tournament : 대회명
  * Tournament_Int : 대회번호
  * Date : 대회날짜 코드
  * Series : 대회 분류
  * Series_Int : 대회 분류번호
  * Court : 야외/실내 코트 여부
  * Court_Int : 야외/실내 코트 코드
  * Surface	: 코트 표면
  * Surface_Int : 코트 표면 코드
  * Round : 몇 강인지 여부
  * Round_Int : 라운드 코드
  * Best_of : 최대 세트 수
  * Winner : 승자 이름
  * Winner_Int : 승자 코드
  * Player1 : 선수1 이름
  * Player1_Int : 선수1 코드
  * Player2 : 선수2 이름
  * Player2_Int : 선수2 코드
  * Player1_Rank : 선수1 랭킹
  * Player2_Rank : 선수2 랭킹
  * Player1_Odds : 선수1 배당률
  * Player2_Odds : 선수2 배당
  * Player1_Implied_Prob : 선수1 승리 예측 확률
  * Player2_Implied_Prob : 선수2 승리 예측 확률
 
- 독립변수: 코트, 코트표면, 라운드, 최대 세트수, 선수1, 선수2, 랭킹, 배당률, 승리예측 확률
- 종속변수: 승리한 선수

---

- 목표: 독립변수를 주고 승리한 선수를 예측할 수 있는 머신러닝 학습시키기
