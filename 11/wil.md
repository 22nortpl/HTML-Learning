플렉스 박스 레이아웃 : 기본적으로 웹 요소를 가로 세로 중 하나를 정해 그 축으로 배치

사용 속성
  justify-content : 주축의 정렬 방법
  align-items : 교차축의 정렬 방법
  align-content : 교차축에 여러 줄 표시할 때 사용
  align-self : 플렉스 항목을 각각 따로 정렬

display 속성
  flex : 블록 레벨로
  inline-flex : 인라인 레벨로

flex-direction 속성
  row : 주축을 가로로 지정, 왼->오른
  column : 주축을 세로로 지정, 왼->오른
  -reverse 가 붙을 경우, 정렬 방향은 반대로!

줄바꿈
  nowrap : 한 줄로, 기본값
  wrap : 여러 줄로 표시
  wrap-reverse : 교차축의 시작점과 끝점 교체

방향+줄바꿈 -> flex-flow

justify-content : 플렉스 항목 간의 정렬 바법 지정
  flex-start : 주축의 시작점에 맞춰 정렬
  flex-end : 주축의 끝점에 맞춰서 정렬
  center : 주축의 중앙에 맞춰서 정렬
  space-around : 항목을 고르게 정렬
  space-between : 첫 번째 항목은 주축 시작점에, 마지막은 끝점에, 나머지는 같은 간격
  space-evenly : 항목을 고르게 정렬, 여백 동일
이는 margin과 함께 사용이 가능하다.

교차축 정렬 방법 지정
  flex-start : 교차축 시작점에 맞춰 정렬
  flext-end : 교차축 끝점에 맞춰 정렬
  center : 교차축 중앙에 정렬
  baseline : 교차축 문자 기준선에 맞춰 정렬
  stretch : 플렉스 항목 늘려 교차축에 가득 차게 정렬

특정 항목만 정렬
  auto : 부모 요소의 값 사용, 기본값
  normal : 브라우저에 따라 다름
  flex-start : 플렉스 컨테이너의 시작점에 맞춤
  flex-end : 플렉스 컨테이너의 끝점에 맞춤
  self-start : 본인의 시작 위치에 맞춤
  self-end : 본인의 끝에 맞춤
  baseline : 항목의 텍스트 기준선에 맞춰 정렬
  center : 컨테이너의 중앙에 정렬
  stretch : 컨테이너의 높이에 가득 차게 늘려서 정렬

여러 줄일 때는 align-content 사용
  flex-start : 교차축의 시작점에 맞춤
  flex-end : 교차축의 끝점에 맞춤
  center : 교차축의 중앙에 맞춤
  space-between : 시작점과 끝점에 맞추고 나머지는 같게 정렬
  space-around : 모든 항목을 교차축에 같은 간격으로 이동
  stretch : 플렉스 항목을 늘려 교차축에 가득 차게 정렬

플렉스 레이아웃을 활용하면 항상 중앙에 표시 가능

여백을 두는 gap 속성 존재