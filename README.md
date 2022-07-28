# netflexAiffel DataThon

1.	팀명 & 조원
A.	팀명: 넷플렉스
B.	조장 : 윤동환
C.	팀원: 윤동환, 김현정, 이유림
기간:   2022.07.26 ~ 2022.07.29
2.	3. 데이터 소개
- 넷플릭스에 업로드 되어있는 프로그램에 대한 제목, 감독, 국가, 배우, 평점, 프로그램 길이, 카테고리(다큐멘터리, tv쇼 등) 등의 칼럼들이 존재.
이름	설명	변수형
Type	영화 혹은 TV프로그램	object
Title	제목	Object
Director	감독	Object
Cast	출연 배우	Object
Date_added	업로드 된 날짜	Object
Release_year	출시된 연도	Int_64
Rating	관람 등급	Object
Duration	상영 길이 	Object
Listed_in	장르	object

3.	진행방향
EDA
-	위 데이터를 바탕으로 시각화를 통한 데이터 분석을 함. 
-	각 특성들에 대해 시각화를 한 후 각 특성들에 대한 상관관계를 분석하였음.
FE
-	Countplot, distplot, px.bar, pieplot


