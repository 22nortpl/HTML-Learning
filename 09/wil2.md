background-image : url('이미지 파일 경로')
  repeat : 가로 세로 모두 반복(기본값)
  repeat-x : 가로만
  repeat-y : 세로만
  no-repeat : 반복 X

background-position : 위치 조절
  키워드 : 수평(left, center, right), 수직(top, center, bottom)
  백분율, 크기 : 이전처럼 사용

background-origin : 적용 범위 지정
  border-box : 박스 모델의 가장 외곽인 테두리까지 적용(기본값)
  padding-box : 박스 모델에서 테두리를 뺀 패딩 범위까지
  content-box : 박스 모델에서 내용 부분에만

background-attachment : 배경 이미지 고정
  scroll : 배경 이미지 같이 스크롤(기본값)
  fixed : 내용만 스크롤

참고 : 이들은 하나로 묶어서도 사용 가능

background-size: 배경 이미지 크기 조절
  auto : 원래 크기
  contain : 이미지 확대, 축소
  cover : 배경 이미지로 요소 모두 덮음
  크기, 백분율도 가능
