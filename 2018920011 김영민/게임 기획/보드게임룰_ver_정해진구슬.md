### 보드 게임 룰
---
|  <center></center> |  <center>A</center> |  <center>B</center> |<center>C</center> |
|:--------|:--------:|--------:|--------:|
|**TRUE** | <center>R </center> |<center>G </center> |<center>B </center> |
|**FALSE** | <center>G, B</center> |<center>R, B </center> |<center>R,G </center> |
---
* TRUE: 떨어뜨려야 되는 색깔
* FALSE: 흘려보내야 되는 색깔

+ 빨간 곳에 있는 FALSE 구슬 1개 당 -1점
+ 빨간 곳에 TRUE 구슬 1개 당 +1점
+ 단, 빨간 곳에 TRUE 구슬이 연속하여 쌓이면 + 알파 점수(콤보 개념)
	+ 예) n개 이상이 연속하여 쌓이면 +1.5점
+ 파란 곳에 있는 TRUE 구슬 1개 당 -1점
+ 모든 구슬이 내려왔을 때, 점수의 함계를 구한다.
___
<center> ![](https://lh3.googleusercontent.com/DVOvM3mo84vPtMcOIhuno2vRFnsraccJD6Jv5wcIN6ouM_aG-cbB0WzOsiB2IG5D1_JUX1-hnhIq "보드게임 룰 설명")
###### <center>그림: 보드 게임 룰 
 + 빨간색 얇은 관 = 빨간 곳
 + 파란색 상자 = 파란 곳
 + 파란 동그라미: 마이너스 점수
 + 검정색 사각형: +알파 점수
 + 빨간색 사각형: 마이너스 점수

