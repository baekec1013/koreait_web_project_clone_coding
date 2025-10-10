<div align="center">

<!-- logo -->
<img src="https://github.com/user-attachments/assets/9ab93557-d933-4244-a665-10a6316d9d87" width="400"/>

### 모나미 클론코딩

[<img src="https://img.shields.io/badge/프로젝트 기간-2025.9.5~2025.10.10-fab2ac?style=flat&logo=&logoColor=white" />]()

</div> 

## 💁‍♂️ 프로젝트 팀원
|FrontEnd|
|:---:|
| ![](https://github.com/yewon-Noh.png?size=120) |
|[백은찬](https://github.com/baekec1013)|

<br />

## 📝 소개
이 프로젝트는 모나미(MONAMI) 공식 웹사이트를 리디자인하고 구현한 웹페이지 제작 프로젝트입니다.
브랜드의 감성과 제품 이미지를 효과적으로 전달할 수 있도록 화면을 새롭게 구성했습니다
html과css만을 사용하여 동적인 기능부분에서 다소 아쉬운 부분이 조금 있긴하지만 JavaScript를 사용하지 않고도 transition과 oposity를 사용하여 동적인 기능을 어느정도 재현하여 표현한 모나미 클론 코딩 프로젝트입니다.

<br />

## ⚙ 기술 스택

### IDE
<div>
<img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white">
</div>

### Tools
<div>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">
</div>

<br />

### 화면 구성
|화면 명|
|:---:|
|<img src="https://github.com/user-attachments/assets/c9efe94d-5856-4784-bfde-fbd80262d65d" width="450"/>|
|전체 화면은 display: flex를 사용해 세로 방향으로 배치했고, 상단에는 fixed 헤더로 메뉴를 고정했습니다.
메인 이미지는 background-size: cover로 꽉 차게 설정했고, 글자는 position: absolute로 이미지 위에 올렸습니다.|

|화면 명|
|:---:|
|<img src="https://github.com/user-attachments/assets/059f0262-7d13-48e1-831e-f68268e54c13" width="450"/>|
|각 상품 박스는 border-radius를 적용해 부드럽고 깔끔한 느낌을 주었습니다.
또한 이미지에 hover 효과를 넣어 마우스를 올리면 안에서 빨간색의 div가 나오도록 설정했습니다.
전체적으로 여백을 넉넉히 두어 상품이 시원하게 보이도록 디자인했습니다.|

|화면 명|
|:---:|
|<img src="https://github.com/user-attachments/assets/8fa715cf-082f-41f9-ae4a-fc597c404dba" width="450"/>|
|메인 영역에는 “Best Product” 문구와 카테고리 버튼들을 flex 정렬로 중앙 배치했습니다.
상품 리스트는 gap을 사용해 한 행에 여러 상품이 균등하게 정렬되도록 구성했습니다.
각 상품 카드에는 border-radius를 적용해 깔끔하고 입체감 있는 디자인을 주었습니다.
배경에는 연한 회색(background-color: #f2f2f2)을 사용해 상품이 돋보이도록 했습니다.|

|화면 명|
|:---:|
|<img src="https://github.com/user-attachments/assets/794f2a92-401e-478e-b188-556ff7b5dd62" width="450"/>|
|동영상은 video 태그를 사용해 자동 재생(autoplay) 및 반복 재생(loop)되도록 설정했습니다.|



|화면 명|
|:---:|
|<img src="https://github.com/user-attachments/assets/b8f6806b-43b4-42d5-a61e-d44cff3c52d5" width="450"/>|
|왼쪽에는 MONAMI NEWS 영역을 flex로 배치하여 최신 소식을 보여주고,
오른쪽에는 문의(INQUIRY)와 브랜드 스토어(BUY NOW)를 보여줍니다.
버튼에는 hover 시 색상이 바뀌는 효과를 추가했습니다.
하단에는 회사 정보와 고객센터를 배치했으며,
배경색을 어두운 톤(background-color: #222)으로 설정하여 본문과 명확히 구분되도록 디자인했습니다.|

<br />

## 🤔 기술적 이슈와 해결 과정
- 1. 정밀한 UI 구현
    - 디자인 디테일부분의 어려움
    - 해결방안: 반복적인 수정과 디버깅을 통해 시각적으로 비슷한 느낌을 구현하였고 개발자 도구를 사용하여 기존 사이트의 css를 분석하여,
               내가 짠 코드와 기존 사이트의 코드가 어떤 부분이 다른지를 보고 수정해야 할 부분은 수정
- 2. 레이아웃 구성 
    - 구성 및 포지셔닝의 어려움
    - 해결방안: 각 레이아웃에 background-color를 주어 내가 짠 코드의 레이아웃을 한눈에 알아보기 쉽게 만들고 틀을 확인하여 튀어나오거나 위치가 잘못
               지정되어 있는 부분들을 수정
- 3. 동적인 기능 구현
    - html/css만의 사용의 어려움
    - 해결방안: Google이나 chat-gpt에 JavaScript를 사용하지 않고도 동적인 기능을 구현할 수 있는 방법을 모색하고 최대한 기존 사이트와 비슷하게 구현하기
               위해서 동적인 기능을 구현해 줄 수 있는 css 코드를 검색하여 참고
<br />



## 🤔 느낀 점
처음 모나미 클론 코딩 프로젝트를 하기 전 하던 템플릿 클론 코딩을 했었는데, 그때까지는 html/css의 지식이 부족하여 레이아웃 잡는 것에서부터 어려움을 겪고 힘들어했지만
모나미 클론 코딩 프로젝트를 하게 되면서 html/css에 대해서 더 자세히 알아보고 공부하게 된 거 같았고, 중간중간 어렵거나 막히는 부분들이 몇몇 있었는데 그럴때마다 인터넷에 검색하여
내가 모르는 html/css의 개념들을 찾아 문제들을 해결해나가는 과정에서 재미를 느끼게 되어 html/css에 더 열심히 하게되고 진지하게 이 프로젝트를 준비하게 되었고, 내가 html/css의 대한 지식이
처음 모나미 클론 코딩을 하기 전과 엄청난 차이가 있음을 느낌.

