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
>(기획서 링크 : https://www.canva.com/design/DAFomO-biC8/voGdCpyZnkdjIOH70MxMlQ/view?utm_content=DAFomO-biC8&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink )<br>
> 07.22 ~ 07.29 : 각 *분담한 페이지 코딩<br>
> *분담한 페이지: '제품', 'About설화수'<br>
> 사용 툴: VS Code, Figma, Canva, Git <br>
> 팀 프로젝트 깃허브 주소 : https://github.com/AumKyungSub/group-anyway.git

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

![127 0 0 1_5500_products html](https://github.com/judiking1/seolwhasoo/assets/110409369/39d74965-ae17-4235-8adc-af21b03eabf4)

<br><br>



>'About 설화수' 페이지

![127 0 0 1_5500_about html](https://github.com/judiking1/seolwhasoo/assets/110409369/8a992220-ec86-4f7b-9c63-a7541bbd4789)

<br>

![127 0 0 1_5500_about html (1)](https://github.com/judiking1/seolwhasoo/assets/110409369/ca30f1ad-420b-432a-b7e2-71a86b02cd4e)





