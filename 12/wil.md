CSS 그리드 레이아웃 : 가로와 세로 모두 사용

display : 가장 먼저 그리드 적용하는 요소 묶는 컨테이너
  grid : 블록 레벨의 그리드 컨테이너
  inline-grid : 인라인 레벨의 그리드 컨테이너
  fr: 프랙션, 상대적인 크기 지정

repeat : 값이 반복될 때 사용
minmax : auto를 사용시 더 늘릴 수 있음.

auto-fit 과 auto-fill : 빈 공간 자동 채움
다만 auto-fit은 공간 확장도 가능
간격 원하면 gap 사용

그리드 라인 사용법
grid-column, grid-row 뒤에 start 와 end 속성 붙임
  grid-column-start : 열 시작번호
  grid-column-end : 열 끝번호
  grid-column : /을 이용해 시작 끝 함께!
이는 row에도 동일 적용!

