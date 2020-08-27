# Publishing-Study
웹 표준과 접근성을 고려한 퍼블리싱 고찰

## 개설 목적
UI에서 HTML 의 비중이 점점 많이 차지하고있는 이 시점에, 잘 짜여진 마크업 즉, 접근성과 웹 표준을 준수한 마크업의 중요성은 나날이 커지고 있습니다. 하지만 실제 현장에서는 이러한 사항을 고민할 시간이 턱없이 부족합니다. 스타일, 기능, 인터렉션 구현 하기에도 바쁘기 때문입니다. 또한 시력이 있는 대다수에겐 시각적인 요건을 만족시키는 것에 개발시간 투자를 많이 해야 수익성과 직결되는 것도 사실입니다.

하지만 구조를 작성하고 컨텐츠를 작성하는 사람으로서, 모든 사람이 읽을 수 있는 컨텐츠를 작성할 의무 또한 존재합니다. 그리고 구조를 잘 작성하면 기술적인 이점이 높습니다(유지보수, SEO 최적화 등등...). 그렇다 하더라도 마크업 말고 다른 요인에 투자하는 시간 또한 매우 중요합니다. 따라서 우리는 정해진 시간 안에서만 순발력을 발휘하여 좋은 마크업을 생산해 내고 나머지 작업을 수행하도록 노력해야 합니다. 한 번 말할 때 잘 말하는 사람이 되고자 하는 것입니다.

그 순발력을 향상시키는 방법은 오직 일주일에 한 번 조금의 시간을 내어 천천히 트레이닝 해보는것 밖에는 없습니다. 업무시간엔 HTML을 리뷰하겠다는 생각을 갖기란 어렵습니다. 따라서, 일주일에 한 번 스터디모임을 가져, 여러사람과 함께 마크업을 고찰해보는 시간을 갖고자 합니다.

## 참여 요건
- 시멘틱 마크업에 대해 어느정도 학습하신 분
- HTML, CSS 기본 공부를 마치신 분
- 웹 표준문서를 참고하는 방법을 아시는 분
- (선택사항) React 의 `Styled Component`나 `Modular Style` 에 대한 관심이 있으신 분

## 지역 및 장소
- **오프라인** : 강남, 신림, 구로 등의 서울 남부, 서부지역. Google Campus 나 무중력지대에서 진행 예정
- **온라인** : Zoom 등의 회의 프로그램 이용

## 준비물
각자의 노트북 지참

## 진행 방식
### 1. 발표 진행
- 화면 공유 프로그램으로 본인의 소스 및 출력화면을 공유하여 진행
- 본인이 어떤 의도를 가지고 마크업과 스타일링을 했는지, 어떠하여 웹 표준과 접근성을 준수한 것인지, 어떠한 유지보수의 이점을 취했는지의 설명
- 피드백 및 토론 진행

### 2. 다음 숙제 선정
- 모임 시, 인터넷에서 공유되는 free web design psd 중 어느것을 공부할지 선정
- 난이도에 따라 마크업, 스타일링을 2주에 걸쳐서 나누어 진행할 지, 동시에 진행할지 결정

## 준비물
포토샵(선택사항), 제플린. 이 2가지 입니다. 포토샵을 보유하고 있지 않을 것을 고려하여 포토샵을 가지고 있는 분께서 제플린으로 전달하여 제플린으로 진행하고자 합니다.

## 중점사항
### HTML
- 반드시 [html validator](https://validator.w3.org/) 의 문법검사를 통과한 소스여야 할 것. 틀렸던 문법은 표준문서 및 에러메세지를 참고하여 공유하면 좋을듯.
- `role`, `WAI-ARIA` 속성등을 최대한 활용하기
- 표준문서를 참고하여 구문 콘텐츠 (`<abbr>`, `<b>`, `<strong>`, `<q>`, `<code>`, `<output>`, `<kbd>` ...) 등을 최대한 활용하기
- `<article>`, `<aside>`, `<nav>`, `<section>` 과 같은 구획 콘텐츠, header, footer 를 잘 활용하기
- 제목 콘텐츠 (`<h1>`, `<h2>` ...) 의 구조화 확실히 하기
### CSS
- CSS 파일은 최소 3개가 되어야함. `1. normalize.css(스터디 통일 예정)`, `2. common.css` `3. 페이지 스타일시트(1개 이상 가능)`
- common.css 는 평소에 하던 방식대로 다양한 셀렉터 적용 가능.
- (선택사항) 페이지 스타일시트 스타일링 시 가능한 class selector 만 활용할 것 (React의 Styled Component와 Modular Style 에 대비하기 위함).
### 토론
누구나 의문점을 제기하며 열린 토론 분위기를 형성하기. 공격적인 언행은 삼가하나 충분한 의견교환에 의한 토론은 언제나 환영.

## Questions
궁금하신 사항은 ISSUE에 질문주세요.
