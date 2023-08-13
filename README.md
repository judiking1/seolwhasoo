# seolwhasoo
설화수 클론코딩 프로젝트


<h1>
  설화수 클론코딩 프로젝트
  <br>
  (23.07.14 ~ 23.08.11)
</h1>

<h2>#1. 개요</h2>

> HTML, CSS, JS, 여러 플러그인들을 통해 페이지 내 기능들을 구현하였습니다.<br>
> 07.14 ~ 07.21 : 기획서 작성<br>
> 07.22 ~ 07.29 : 각 *분담한 페이지 코딩<br>
> *분담한 페이지: '제품', 'About설화수'<br>
> 사용 툴: VS Code, Figma, Canva, Git

<br><br>

<h2>#2. 구현 방법</h2>
<h3>'제품' 페이지(Products)</h3>

> 배너 이미지 : picture + source 태그 사용. media 속성으로 반응형 너비 설정 및 srcset 속성으로 개별 사진 설정<br>
> 메뉴 탭 : 스와이퍼 플러그인 사용. 제이쿼리로 각 select 태그 value에 맞는 id값의 스와이퍼 나타나도록 구현.<br>
> 제품 목록 : 제품마다 id값을 설정한 뒤, 제이쿼리로 선택된 스와이퍼 슬라이드의 id값에 맞는 제품이 나타나도록 구현.<br>
> 페이지네이션 : 순수 JS로 구현. 이전, 다음 기능은 함수 구현 뒤 onclick속성으로 버튼태그에 직접 적용<br>

<h3>'About 설화수' 페이지(about)</h3>

> 배너 애니메이션 : CSS의 키프레임, 애니메이션 기능 활용. <br>
> 섹션 애니메이션 : AOS(Animation On Scroll) 라이브러리 활용. (참고: https://github.com/michalsnik/aos)<br>
> 네비게이션(ScrollSpy) 기능 : 자바스크립트의 IntersectionObserver기능 활용.<br>
> 활성화된 요소만 active 클래스 추가. 클릭 시, event.target.hash로 scrollIntoView 되도록 구현<br>
(참고: https://wilsotobianco.hashnode.dev/scrollspying-made-easy-with-the-intersection-observer-api)<br>
> Journey 섹션 가로스크롤 : GSAP의 ScrollTrigger 플러그인 활용.<br>
(참고: https://greensock.com/forums/topic/29022-horizontal-scroll-pinsticky-location/)
<br>

<br><br>

<h2>#3. 구현 화면</h2>

>'제품' 페이지 

<h2>모바일</h2>
<p align="center">
<img src="https://github.com/judiking1/seolwhasoo/assets/110409369/34ed4213-4b5d-4581-9695-498e7227bf00" alt="제품 모바일" width="300" height="600">
</p>

<h2>태블릿</h2>
<p align="center">
<img src="https://github.com/judiking1/seolwhasoo/assets/110409369/5d3569c1-6860-411a-b59e-2fe479902c84" alt="제품 태블릿" width="800" height="800">
</p>

<h2>PC</h2>
<p align="center">
<img src="https://github.com/judiking1/seolwhasoo/assets/110409369/ee1e6ca0-e9e6-4ff3-82ca-5592b0f6777e" alt="제품 PC" width="1200" height="800">
</p>
<br><br>

>'About 설화수' 페이지

<h2>모바일</h2>
<p align="center">
<img src="https://github.com/judiking1/seolwhasoo/assets/110409369/c468afa4-2dc2-4381-b296-ea5f80d64c98" alt="About 모바일" width="300" height="600">
</p>

<h2>태블릿+PC</h2>
<p align="center">
<img src="https://github.com/judiking1/seolwhasoo/assets/110409369/5a352a03-834d-4757-a17e-2d137035f7b6" alt="About 태블릿" width="800" height="800">
</p>




