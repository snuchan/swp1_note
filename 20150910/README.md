혹 css에서 특정 부분의 특정 코드를 바꿀경우 (여러가지 a중에서 nav 안에 있는 a만 없앨 경우)
 > nav a {} > 부모 자식?



<img> 이미지 출력 시 사용 +src="주소"

리스트
리스트 전체 -> <ul> , <ol> >> ol은 순서 o ul은 순서 x
리스트 작성 > <li>

테이블 태그. <table> >> 표 작성.  th 제목 tr 행 td 내용

<form> 사용자와 상화작용 ex. 회원가입.
<input> 폼 태그 안에서 아이디 비번 란 처럼 여러 컨트롤 요소 생성.
 type= "text" ; 한 줄 정도의 텍스트 입력란.
 type= "password" 위와 같지만 다 *표시.
type= "radio" > 여러 항목 중 하나만 선택 가능. <~~radio. name=""(같은 경우 한 묶음으로)

<textarea> 여러 줄의 텍스트입력창. rows cols
<select> 카테고리 선택등 선택.
<submit>

background: url(주소)
             no-repeat.

hover > css에 추가 작성해서 뭐 마우스 지나면 빠방.
gitub.

c9 - 워크스페이스 형성

터미널 쪽에 명령어
git init > 깃을 사용하겠다 선언 
ls  > 디렉토리 상 이동?
git status > 빨간색 : 깃이 추적하지 않고 있는 파일.
              현 깃 상황?
git add 파일명 (중간에 탭을 누르면 자동완성) : 깃에 추가.

커밋 : 전체 상태를 세이브. (git commit )
-m 메시지
git log : 계정 날짜 전 메시지 등등이 나타남.

세이브 - 컨트롤 s  or file - save.

git diff - 변화한 부분을 알려줌. (- 삭제, +추가)

#제목1 : 페이지에 로드하면 변환되어 보임. <h1>
## --- : <h2>

[제목](주소)
