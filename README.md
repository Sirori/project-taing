# <멋쟁이 사자처럼 프론트엔드 스쿨 - HTML, CSS 프로젝트>


## <Taing 클론코딩>
![Logo](https://github.com/Sirori/readme-/assets/116864776/9f95d96f-2d4d-48c2-af3a-963c7366bf82)

 -티빙(TVing)이라는 OTT 페이지를 기반한 페이지를 작업하였습니다.

## <능히할수있조 - 6조>
-서진만(조장), 권혜미, 양시연, 정민지 <br>
 개발기간: 2023.06.23 ~ 2023.06.28
<img width="518" alt="2023-06-28_2 32 38" src="https://github.com/GwonH/project-taing/assets/130988491/4a2bcd5f-7d4b-48a1-99b0-a0dc5f1d98b7">

## Stack
 <div>
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">   
 </div>

<br>

HTML과 CSS, SASS를 활용하여 페이지의 마크업과 스타일링을 구현하였고, git과 github를 사용하여 협업을 진행하였습니다.


### 프로젝트 조건
- 이미지의 경우, 대체 텍스트 제공이 필요합니다.
- 마우스로 조작할 수 있는 기능은 키보드로도 접근 및 조작이 가능해야 합니다.
- 폼 컨트롤은 식별 가능한 레이블이 필요합니다.
(시각적으로 표현되지 않더라도 스크린 리더가 읽을 수 있게 처리해야 합니다)
- 명도대비는 최소 4.5대 1을 준수해야 합니다.


=> 모든 이미지에 대체 텍스트 삽입, 마우스와 키보드의 접근성 일치, form 영역에 모두 label 혹은 legend 추가, 명도는 디자인 시안을 반영하였음

### 프로젝트 목표
☞ 개발자가 가져야하는 소통능력 키우기 <br>
☞ 서로 존중하는 마음으로 책임감을 가지고 작업 수행<br>
☞ 수업시간 이외의 시간을 통해 부족한점들은 소통을 통해 해결<br>
☞ 주어진 프로젝트와 디자인 시안에 부합하게 페이지 제작<br>
☞ 접근성을 준수하는 페이지 제작<br>
☞ git을 적극적으로 사용하여 팀 내 협업 진행<br>

## 프로젝트 사용법
★ 패키지설치
```
npm i 또는 npm install
```

★ 클라이언트 실행
```
npm start 또는 npm run start
```

```
git clone https://github.com/GwonH/project-taing.git
```

(출처: 슬비쌤 깃허브 https://github.com/seulbinim/project-template)
## 프로젝트 내용

디자인 시안 중 메인 페이지, 아이디 찾기, 비밀번호 찾기, 회원가입, 프로필 전환 및 편집 페이지를 작업하였습니다.
모든 페이지를 반응형으로 작업하였고, 각 기준점은 모바일 320-768px, 태블릿 768-1200px, 데스크탑 1200-1920px입니다.

### 메인 페이지(권혜미, 서진만, 양시연, 정민지)
<데스크탑>
![main_desktop](https://github.com/Sirori/readme-/assets/116864776/89312e38-a1a5-43b6-8eed-2f6fb4044034)
<태블릿>
![main_tablet](https://github.com/Sirori/readme-/assets/116864776/e69f2d97-e384-4e5b-8bbd-74418944ac47)
<모바일>
![main_mobile](https://github.com/Sirori/readme-/assets/116864776/27bdae09-3541-465d-95f7-39b91e9c6d3c)

각 구역을 4부분으로 나누어 작업하였습니다.
- header와 footer - 권혜미
- 메인 배너와 티빙에서 꼭 봐야하는 콘텐츠, Quick VOD - 서진만
- 실시간 인기 프로그램과 인기 LIVE 채널 - 양시연
- 오직 티빙에만 있어요와 SPORT 이벤트 배너, 이벤트 배너 - 정민지

각 구역마다 반응형으로 레이아웃을 조정하였고, 리스트 형식으로 되어있는 부분은 자바스크립트를 생략하기 때문에 넓이를 100이상의 vw를 주었습니다.

header와 footer 부분은 디바이스마다 각기 다른 디자인을 반영하여 스타일링 했습니다.

### 회원가입 페이지(서진만, 권혜미)
<데스크탑과 태블릿>
![sign-in_desktop-tablet](https://github.com/Sirori/readme-/assets/116864776/b25604f9-bd4b-477d-9ce4-eec8b9d96b91)

<모바일>
![sign-in_mobile](https://github.com/Sirori/readme-/assets/116864776/e56d0d6b-0d21-4a9b-97ea-4e74f5d1d039)

회원가입 페이지 부분에서는 모바일 화면에서 반응형으로 구현할때 원하는 디자인 시안대로 구현이 어려워 많은 시간을 할애하였습니다.

### 아이디 찾기 페이지(권혜미)
<데스크탑과 태블릿>
![fint-id_desktop](https://github.com/Sirori/readme-/assets/116864776/cec6543b-b942-478d-a91b-a0954c0b6b60)

<모바일>
![find-id_mobile](https://github.com/Sirori/readme-/assets/116864776/c19cf2c7-ef3c-47a6-a448-d001505b36a9)

fieldset을 이용하여 아이디 찾기 입력 폼을 구성하고 legend로 폼의 제목을 달아주었습니다.  width값이 커짐에 따라 폼은 최대 700px까지만 커지고 가운데에 위치하도록 스타일링 하였습니다. 


### 비밀번호 찾기 페이지(권혜미)
<데스크탑과 태블릿>
![find-pw_desktop-tablet](https://github.com/Sirori/readme-/assets/116864776/3991a948-4cbf-4c52-a3af-853bb8faabde)
<모바일>
![find-pw_mobile](https://github.com/Sirori/readme-/assets/116864776/f9140afa-ed0b-4fa2-be3a-60c8517c2192)

기기마다 달라지는 서브텍스트의 투명도를 transition을 이용하여 구현했습니다.


### 프로필 편집 페이지(양시연)
<데스크탑과 태블릿>
![profile-edit_desktop](https://github.com/Sirori/readme-/assets/116864776/943aae1b-3689-4db6-8d0f-6ddccab26e96)

<모바일>
![profile-edit_mobile](https://github.com/Sirori/readme-/assets/116864776/6abe17e5-d500-4781-918a-02de88a07483)
flex와 media-query mixin을 사용하여 작업하였습니다.

### 프로필 선택 페이지(양시연)
<데스크탑과 태블릿>
![profile-select_desktop-tablet](https://github.com/Sirori/readme-/assets/116864776/7622882f-5cc0-4144-890e-9fc56f4c93be)

<모바일>
![profile-select_mobile](https://github.com/Sirori/readme-/assets/116864776/37109999-8c71-4bfa-b48c-5fb6efa74435)

위 편집 페이지와 같은 마크업에서 가운데 아이콘과 버튼 디자인을 변경하였습니다.


## 작업 트리
```
src

┣ assets

┣ scss

┃ ┣ base

┃ ┃ ┣ _default.scss

┃ ┃ ┣ _index.scss

┃ ┃ ┣_normalize.scss

┃ ┃ ┗ _reset.scss

┃ ┣ layout

┃ ┃ ┣ _footer.scss

┃ ┃ ┣ _header.scss

┃ ┃ ┗ _index.scss

┃ ┣ pages

┃ ┃ ┣ _home.scss

┃ ┃ ┣ _index.scss

┃ ┃ ┗ _minjee.scss

┃ ┣ utils

┃ ┃ ┣ _a11y.scss

┃ ┃ ┣ _color.scss

┃ ┃ ┣ _flexbox.scss

┃ ┃ ┣ _index.scss

┃ ┃ ┣ _media-query.scss

┃ ┃ ┣ _mixin.scss

┃ ┃ ┗ _unit.scss

┃ ┗ index.scss

┣ style

┃ ┣ index.css

┃ ┗ index.css.map

┣ views

┃ ┣ profile-edit.html

┃ ┣ profile.html

┃ ┗ sign-in.html

┃ find-id.html

┃ find-pw.html

┃ header-footer.html

┗ index.html
```

## 배포사이트
candoit.netlify.app

## 한줄평

- 권혜미: 반응형으로 구현하는게 생각보다 너무 어려웠습니다. 첫 프로젝트인데 좋은 분들 만나서 평화롭게 작업할 수 있었습니다!
  
- 서진만: 프로젝트 기간동안 정말 모두모두 화기애애한 분위기 속에서 작업할 수 있어서 너무 감사했습니다. 위기를 극복하면서 같이 희열을 느낄 수 있어서 행복한 시간이었습니다. 수고하셨습니다.
  
- 양시연: 첫 프로젝트라 좌충우돌이 많았지만, 앞으로의 프로젝트를 할 때의 길잡이가 될 것 같았다. 소중한 팀원들과의 작업물이 잘 나와서 뿌듯하다.
  
- 정민지: 첫 프로젝트를 경험하면서 팀원과 협업하는 방법 등 배운 것이  많았습니다. 어려움도 팀원과 함께 해결해 나갈 수 있어 힘이 됐습니다. 그리고 컨디션 관리는 매우 중요한 것 같습니다.
