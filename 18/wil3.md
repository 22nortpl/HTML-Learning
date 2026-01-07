브라우저와 관련된 객체
  window : 브라우저 창 열릴 때마다 생성
    프로퍼티
    document : 브라우저 창에 표시된 웹 문서에 접근
    frameElement : 현재 창이 다른 요소 안에 포함되면 그걸 반환, 없으면 null 변환
    innerHeight : 내용 영역의 높이
    innerWidth : 내용 영역의 너비
    localStorage : 웹 브라우저에서 데이터 저장하는 로컬 스토리지 반환
    location : window 객체의 위치 또는 현재 URL 표시
    name : 창의 이름을 가져오거나 수정
    outerHeight : 브라우저 창의 바깥 높이
    outerWidth : 브라우저 창의 바깥 너비
    pageXOffset : 스크롤 시 수평으로 이동하는 픽셀 수
    pageYOffset : 스크롤 시 수직으로 이동하는 픽셀 수
    parent : 현재 창이나 서브 프레임의 부모
    screenX : 브라우저 창의 왼쪽 테두리가 모니터 왼쪽 테두리에서 떨어진 정도
    screenY : 브라우저 창의 위쪽 테두리가 모니터 위쪽 테두리에서 떨어진 정도
    scrollX : 스크롤 시 수평으로 이동하는 픽셀 수
    scrollY : 스크롤 시 수직으로 이동하는 픽셀 수
    sessionStorage : 
    메소드
    alert() : 알림창 표시
    blur() : 현재 창에서 포커스 제거
    close() : 현재 창 닫음
    confirm() :확인 취소 창 표시
    focus() : 현재 창에 포커스 부여
    moveBy() : 현재 창 지정한 크기만큼 이동
    moveTo() : 현재 창을 지정한 좌표로 이동
    open() : 새로운 창
    postMessage() : 메시지를 다른 창으로 전달
    print() : 현재 문서 인쇄
    prompt() : 프롬프트 창에 입력한 텍스트 반환
    resizeBy() : 현재 창의 크기를 지정한 크기만큼 조절
    resizeTo() : 브라우저 창의 크기를 동적으로 조절
    scrollBy() : 저장한 크기만큼씩 스크롤
    scrollTo() : 지정한 위치까지 스크롤
    sizeToContent() : 창의 크기를 내용에 맞게 맞춤
    stop() : 로딩 중지
  document : 웹 문서마다 하나씩 존재 body 태그 만나면 생성
  navigator : 현재 사용하는 브라우저의 정보
  userAgent 프로퍼티 : 현재 브라우저 정보 담는 문자열
    Mozilla/x.x
    Windows NT x.x
    Win64; x64
    WOW 64
    이외에도 Safari, Firefox, Chrome 등이 존재
  주요 프로퍼티
    battery() : 배터리 충전 상태
    cookieEnabled : 쿠키 정보 허용 여부
    geolocation : 모바일 기기 이용 위치 정보
    language : 브라우저 UI의 언어 정보
    oscpu : 현재 운영체제 정보 표시
  history : 현재 창에서 사용자의 방문 기록 저장
    프로퍼티
      length : 현재 브라우저 창의 history 목록에 있는 항목의 개수 저장
    메서드
      back() : 이전 페이지 표시
      forward() : 다음 페이지 표시
      go() : 현재 페이지 기준 상대적 페이지 표시
  location : 현재 페이지의 URL 정보
    프로퍼티
      hash : 해시 부분 정보
      host : 호스트 이름, 포트 번호
      hostname : 호스트 이름
      href : 전체 URL
      pathname : URL 경러
      port : 포트 번호
      protocol : 프로토콜
      password : password 정보
      search : ?로 시작하는 검색 내용
      username : username 정보
    메서드
      assign() : 새 문서 주소 할당 및 가져옴
      reload() : 다시 불러옴
      replace() : 현재 URL 지우고 다른 거 교체
      toString() : URL을 문자열로
  screen : 현재 화면 정보
    프로퍼티
      availHeight : UI 영역 제외 높이
      availWidth : UI 영역 제외 너비
      colorDepth : 사용하는 색상 수
      height : UI 영역 포함 높이
      orientation : 화면의 현재 방향
      pixelDepth : 픽셀 렌더링 시 사용하는 비트 수
      width : UI 영역 포함 너비
    메서드
      lockOrientation() : 화면 방향 잠금
      unlockOrientation() : 화면 방향 잠금 해제