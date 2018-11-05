
# starUML

## 18.11.05 파일 최초 업로드

### Class 디자인 

*  User
	* 회원 ID (PK)
	* 성별
	* 누적 날씨 피드백
	* 나이
	* 선호 스타일 

* Weather
	* 관측 시간 (PK)
	* 지역 (PK)
	* 평균기온
	* 최저기온
	* 최고기온
	* 현재 체감기온
	* 평균습도
	* 평균풍속
	* 현재풍속
	* 강수량
	* 미세먼지
	* 초미세먼지

* Clothes
	* 명칭 (PK)
	* formal 적합도
	* casual 적합도
	* sporty 적합도
	* 상하의 구별
	* 성별
	* 추천 온도 구간

* Connection Log
	* 회원 ID (FK)
	* 접속시간
	* 접속위치

* FeedBack
	* 날짜 (PK)
	* 회원 ID (FK)
	* 추천 스타일
	* 사용자 선택 스타일
