미디어 쿼리 : 접속하는 장치에 따라 CSS 스타일을 사용하는 방법

@media [only|not] 미디어 유형 (and)*(and) 형태

미디어 유형의 종류
  all : 모든 미디어 유형에서 사용할 CSS 정의
  print : 인쇄 장치에서 사용
  screen : 컴퓨터/스마트폰 스크린
  tv : 음성 영상 동시 출력하는 TV
  aural : 음성 합성 장치
  braille : 점자 표시 장치
  handheld : 패드 등 손에 들고 다니는 장치
  projection : 프로젝터용
  tty : 디스플레이 기능이 제한된 장치에 맞음
  embossed : 점차 프린터에서 사용할 CSS 정의

웹 문서의 가로 너비와 세로 높이 측정
  width, height: 가로, 세로 높이 지정
  min이 붙으면 최소를 지정, max가 붙으면 최대를 지정

화면 회전 속성
  portrait : 단말기의 세로 모드를 지정
  landscape : 단말기의 가로 모드를 지정

적용 방법
기본형 : <link rel="stylesheet" media="미디어 쿼리 조건">
@import url(css 파일 경로) <미디어 쿼리 조건>