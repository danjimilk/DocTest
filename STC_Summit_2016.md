class: center, middle

# STC Summit 2016 참관 후기

---
## 참관 후기 요약
* 좋았던 점
  * 다양한 주제, 다양한 직무 (라이터, 기술 지원, 마케터 등), 많은 참여
  * 이어지는 주제, 가늠할 수 있는 Content
  * 추후 Video Content 제공

* 아쉬운 점
  * 낚시성 제목, 알맹이 없는 세션들이 존재
  * 스포서쉽에 의거한 광고성 세션 (Web Works, Adobe 등)

### 결론
* Rest API는 대세임
* 저비용 고효율에 기민한 대응이 가능한 Documentation
* 오픈 소스, 진입이 쉬운 툴의 사용 확대: GitHub, Jekyll, Swagger, Markdown

---

## Openning Keynote

### 세션 정보
* 발표자: David Rose, CEO at Ditto Labs and Vitality
* 일정: 5/15(일) 오후 5시 30분

### 내용
#### Industry 4.0의 시작
* Terminal World: 스마트 기기의 홍수
* Prosthetics: 신체의 일부를 대체하는 인공 기관들
* Animism: 감성을 가진 로봇과 기기들
* Enchanted Objects: 강동을 주는 사물들

---
#### 사용자의 욕구
* Omni Science: The desire to know all.
* Telepathy: The desire for human connection.
* Safe Keeping: To protect and to be protected.
* Immortrality: To be healthy and vital.
* Teleportation: To move effortlessly

#### Enchanted Object의 등장 (ex. Ambient Umbrella)
 <iframe width="560" height="315" src="https://www.youtube.com/embed/teEZMLUXnSk" frameborder="0" allowfullscreen></iframe>

---
#### Ehchanted Objects의 요소
* glanceability
* gestureability
* affordability
* wearability
* indestructibility
* usability
* loveability

#### Ladder of Enchantment
* Augmentation: 무게를 저장하는 체중계 - Product Level
* Personalization: 누가 사용하고 있는지 파악하는 체중계
* Socialization: 사용자의 체중을 소셜 네트워크에 공유하는 체중계 - Service Level
* Gamification: 건강한 습관 또는 목표 체중을 위해 점수나 레벨을 주어 사용자를 독려하는 체중계
* Story-fication: 건강 및 피트니스와 같은 요소나 이야기의 일부가 되는 체중계 - Experience Level

---

#### 결론
* 항상 켜져 있지 않고 필요할 때만 사용할 수 있을 것이고, 생활을 방해하지 않고 필요할 때만 인지될 것이다.
* 인터페이스가 제공되기 때문에 변형되거나 예측못한 형태로 사용되어질 수 있을 것이며, 스스로 패턴을 인식하거나 학습하여 요구 사항을 미리 예측하여 동작할 것이다.
* 이 모든 것들이 클라우드 베이스의 서비스로 구현되고 IoT 기기들이 인터페이스를 열고 있고 정보를 서로 주고 받을 수 있기 때문에 가능할 것이다.

## So What?
<img style="margin:0px auto;display:block" width="60%" height="60%" src="http://danjimilk.github.io/DocTest/IoT_World.png" />

---
## Your Secret Weapon: The Documentation Handbook

### 세션 정보
* 발표자: Kate Schneider, Senior Technical Writer, Madcap Software
* 일정: 5/16(월) 오전 8시 30분

### 내용
#### 직면한 문제
* 선행 라이터로부터 얻을 수 없는 정보
* 1:1 트레이닝을 하기엔 부족한 시간
* 최신의 내용이 아닌 스타일 가이드
* 여러 버전의 스타일 가이드로 인해 정보의 충돌이 일어남

---
#### The Solution: Doc Handbook
* 중앙 저장소에서 유지됨
* 리뷰, 업데이트, 추가의 반복으로 최신의 정보가 유지
* 트레이닝 도구 및 레퍼런스 도구로 사용될 수 있음
* 문서의 스타일이나 표현이 같은 수준을 유지하도록 도움
* 업무 워크플로를 생성하는데 도움을 줌
* 인력의 고용 및 유출에 따른 정보 손실, 훈련 비용, 교육 자료의 중복을 없앰

#### Doc Handbook 사용 목적
* 트레이닝 도구: 업무 워크플로, 저작 도구
* 레퍼런스 도구: 스타일 가이드, How to 가이드
* Sandbox 도구: 새로운 도구, 스타일 등을 시험해볼 수 있는 테스트 자료
  
<img style="margin:0px auto;display:block" width="60%" height="60%" src="http://danjimilk.github.io/DocTest/Handbook.png" />

#### Doc Handbook Best Practice - Do
* 신입 라이터는 익숙해질 때까지 핸드북을 사용한다.
* 팀 멤버와 협업하여 핸드북을 저작/리뷰한다.
* 신입 라이터의 제안이나 리뷰를 반영한다.

#### Doc Handbook Best Practice - Do Not
* 핸드북을 방치하지 마라
* 하루 아침에 핸드북을 완성하려고 하지마라 (계속 추가하는 방식 사용)
* 기존의 문서를 재작성하지 마라

### 결론
* 우리의 핸드북(스타일 가이드)은 접근이 쉬운가?
* 우리의 핸드북은 계속 업데이트되고 업무 시 참조할 수 있는 것인가?
* 우리의 핸드북으로 멤버의 변화에 대응할 수 있는가?
* 우리의 핸드북이 위와 같은 특징을 가질 수 있도록 업데이트 및 재작성할 가치가 있음.

---
## Generating API Doc automatically

### 세션정보
* 발표자: Ed Marshall, Marshall Documentation Consulting
* 일정: 5/16(월) 오전 9시 45분
* 비고: 청강 중 다른 세션으로 이동

### 내용 및 소감
* TC에서 API/SDK 라이터의 비중이 커짐, 하지만 툴은? Robo Help를 많이 씀
* API 문서의 자동화를 위해 Doxygen, JavaDoc, Swagger 등을 소개함.
* API/SDK 라이터의 덕목으로 Code Reading 스킬을 강조함.
* API 사용 목적, API를 쓰게되는 맥락이나 사용 로직을 문서에서 제공하는 것도 중요
* 소스 코드에 문서화를 해야 하기 때문에 개발자와 협업할 때 협업 규칙을 잘 세우고 지키는 것이 중요.
* JavaDoc 위주의 코드 Notation 사용되기 시작될 때 쯤 다른 세션으로 이동

---
## Tech Comm and Tech Support Working Together
### 세션정보
* 발표자: Rick Lippincott, Senior Technical Writer, Blacktree Technology/Analogic
* 일정: 5/16(월) 오전 9시 45분

### 내용 및 소감
* Tech Comm은 내부 개발자와 커뮤니케이션 하며 이를 토대로 문서를 만든다.
* Tech Comm이 만든 문서로 유저 또는 외부 개발자와 커뮤니케이션한다.
* Tech Comm이 만든 문서의 문제점을 Tech Support가 잘 수집한다.
* 이런 상황에서 Tech Comm이 Tech Support에게 문서 리뷰를 부탁하는 방식 등으로 협업할 수 있음.
* 우리 조직의 입장에서 ID개발지원실이 Tech Support라고 할 수 있음.

---
## REST API Documentation Best Practice
### 세션정보
* 발표자: Marta Rauch, Sr. Principal Information Developer, Oracle
* 일정: 5/16(월) 오후 1시

### 내용
#### 다룬 주제
  * Intro and importance of REST APIs
  * Best practices for REST API content
  * How one company does this
  * Useful tools

---
#### Intro and importance of REST APIs
* REST API: ROA (Resource Oreinted Architecture)구조로 웹의 콘텐츠를 하나의 자원으로 보고 URI를 통해 CRUD의 작업을 HTTP의 GET, POST, PUT, DELETE를 사용하여 처리한다.
* 빠르게 성장하고 있고 산업 표준으로 자리 잡음.
* 소셜 네트워크, IoT, Cloud, 모바일, 웨어러블에 사용됨.
* 정확함, 내용의 신뢰성이 API 문서에 가장 크게 요구되는 요소임.

#### Best Practice for REST API Document
* 레퍼런스 성격의 내용 뿐만 아니라 Get Started, Task Oriented 설명을 함께 제공하라.
* Use Cases별 API 사용 가이드 제공 (레퍼런스보다 가이드 성격)
* Task Based Category로 API 레퍼런스를 필터링해서 접근할 수 있어야 함.
* API 이름(자워 URI, URL 구조), 지원 Methods, Overview, Method별 설명, 파라미터, Notes
* Response (Status Code)에 대한 설명 필요
* 다양항 방법으로 정보에 접근하도록 해야 함 (필터 기준: Task, Path, Method)
* 문서 콘텐트 자체도 자동화되어 산출될 수 있게 해당 언어 또는 언어가 지원하는 포맷으로 작성함.

---
#### API Documentation Generation
* Oracle 제품에 대한 REST API 문서 작성
* Swagger을 사용하여 문서화를 자동화 했지만 표시하는 템플릿(Swagger UI)를 커스터마이징함.
* 심지어 문서를 배포하는 앱을 만들고 해당 앱에 문서를 배포할 수 있도록 REST API를 만듬.
* 문서 배포 앱이 Oracle 내부의 CMS에서 Content를 추출하여 REST API 문서를 배포함.

#### REST API 문서화를 위해 사용한 도구
* GitHub: Repository로 사용
* Postman (Chrome Extension): REST API를 테스트하기 위한 도구
* 브라우저 뿐만 아니라 Desk Top용 REST Client나 cURL 오픈 소스를 사용하기도 함.

#### References
* [Tom Johnson's API Doc posts](http://idratherbewriting.com/category/api-documentation/)
* [Tom Johnson podcast with Peter Gruenbaum on automating REST API Doc](http://idratherbewriting.com/2015/01/05/podcast-automating-rest-api-documentation-with-peter-gruenbaum/)
* [Sarah Maddox, API Technical writing](http://www.slideshare.net/sarahmaddox/api-technical-writing)

---
## Collaborating and Contributing in GitHub
### 세션정보
* 발표자: Nicky Bleiel, Watson Information Developer, IBM Watson
* 일정: 5/16(월) 오후 2시 15분

### 내용
#### GitHub란?
* Web-based respository for Software projects (31 million repositories)
* GitHub uses Git.
* Git: Distributed version control system for software development

---
#### 특징
* SNS 특징이 있음, 유명 프로젝트, 유명 개발자를 Follow할 수 있음.
* 문서 저작을 함께 할 수 있음
* 문서 또한 코드와 같은 파일로 취급
* 계정 생성은 무료, 단 Private Repository를 만들어야 할 경우 유료

#### GitHub 이해를 돕기 위한 레퍼런스
* [Guruble Blog](http://guruble.com/?p=116)
* [딤딤이 Blog](http://dimdim.tistory.com/entry/GIT%EC%97%90-%EB%8C%80%ED%95%9C-%EB%82%B4%EC%9A%A9%EC%A0%95%EB%A6%AC-%EC%A0%95%EB%A6%AC%EC%A4%91)

#### GitHub에서 문서화하는 방법
* Readmes 생성 (Markdown)
* GitHub Pages (gh-pages 브랜치 사용)
* Wikis (Markdown)

---
#### Markdown
* 가벼운 규칙으로 HTML 변환이 쉬운 문법 (Wiki Markup와 비슷)
* John Gruber에 의해 만들어짐.
* GitHub에서 문서화를 위해 Markdown을 사용
* Syntax Highlighting, Task List, Tables를 추가로 지원
* [Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)

### 소감
* GitHub의 특징을 활용하면서 문서화하는 스킬은 대부분 최근 TW에게 요구되는 Trendy한 스킬이라고 느낌
* Markdown이 문서에 요구되어지는 많은 사항들을 만족시키지 못하지만 빠른 대응이 필요할 때 적합
* Code와 문서의 경계를 크게 두지 않는 사고 방식을 확인함.

---
## Interactive Document and the IoT
### 세션정보
* 발표자: Vi Kellersohn, Chief Marketing Officer, Oberon Technologies
* 일정: 5/17(화) 오전 8시 30분

### 내용
* IoT 기기들은 필요한 정보를 인터넷을 통해 수집하여 기기 스스로를 제어하거나 정보를 디스플레이할 수 있다.
* 또는 반대로 IoT 기기의 상태 정보나 센서 정보를 인터넷을 통해 내보낼 수 있다.
* Interactive Content는 제품 상태 정보나 사용자의 진행 상태를 이용해 반응형 방식으로 정보를 전달하는 것
* 실제로 세션에서는 커피 머신 + 라즈베리 파이 + 센서 + Wireless Network를 조합하여 반응형 콘텐트 시연

---
<img width="70%" height="70%" src="http://danjimilk.github.io/DocTest/Interactive_Content.jpg">

### 소감
* Interactive Content가 무엇인지 가장 구체적으로 보여준 세션이었음. 
* 기존 독자 분석에 따라 Content를 작성했지만 이는 특정 독자 층의 예상이거나 표본이고 각 개별 독자층의 대응이 어렵기 때문에 범용적인 문서를 쓰는 경우가 많음.
* 실제 Personalized Content를 지향하려면 Connectivity를 통한 정보 수집과 이에 따른 Conditional Content는 필수임.
* 물론 Content는 계속 범용적이며 모든 것을 포괄할 수 있을 정도로 많은 정보를 들고 있어야 Personalized Content를 생성할 수 있음.

---
## Do More with Less and Increase your Return on Content(ROC)
### 세션정보
* 발표자: Abhishek Jain, Product Manager, Adobe
* 일정: 5월 17일(화) 오전 9시 45분

### 내용
#### 서론
* 회사는 Content 생산을 위해 많은 예산을 편성하지 않거나 예산을 깎고 있음.
* 예산은 줄었지만 요구하는 것들은 많아짐.
* 이 상황에서 집중해야 할 것, 줄여야 할 것이 무엇인지 고민해야 한다.

---
#### 필수적인 Content를 생산하고 프로세스를 효율화하라
* Content 전략
  * 처음부터 완변한 Content를 만들 필요없음. 소프트웨어의 Agile 방법론처럼 Content 생산/관리 필요(Lean).
  * 누가 이 문서를 필요로 하는지? 그들이 언제까지 어느 수준의 정보를 필요로 하는지?
  * 그리고 그 요구가 단계별로 진행될 수 있는지?
  * 문서 작성에 관해 필요없는 Content나 프로세스를 줄일 수 있는 부분은 없는지?
  * 계속적인 Content 개선을 쉽게 할 수 있는 방법은 무엇인지? 

* 프로세스 전략
  * 우리의 프로세스 중 가장 비용 개선이 쉽게 될 수 있는 부분은 리뷰 프로세스
  * 완벽한 리뷰는 불가능하며, 수시 순환 방식으로 계속적 리뷰를 하는 것이 좋음.
  * 리뷰의 결과물은 항상 최종 결과물에 비견되는 것으로 바로 배포가 가능할 정도여야 함.

---
#### 트래픽과 ROC의 측정
* 사용자를 이해함으로 측정해야 할 자료를 판단할 수 있음.
* 수집할만한 자료
  * 많이 읽는 Content
  * 많이 검색하는 Keyword
  * 소비하는 지역과 언어
  * 어떤 서비스를 통해 접속하는지? (Organic Search, Site Refer, Social)
  * 어떤 형태의 기기로 접속하는지?
  * 토픽을 읽는데 소비되는 시간
  * 토픽을 그냥 지나치는 비율
  * 멀티미디어 Content의 소비율이나 양

* 필요 Action
  * 검색 쿼리가 많거나 자주 소비되는 Content는 생성하거나 강화해야 함.
  * 사용자의 피드백은 바로 반영할 가치가 있음.
  * 고비용 대비 저효율의 콘텐트를 줄여야 함(미디어 Content, 단순히 조회수로 비디오 영상의 효용성을 판단할 수 없음)

---
#### Technical Content Workflow is becoming circular.
<img style="margin:0px auto;display:block" width="60%" height="60%" src="http://danjimilk.github.io/DocTest/Technical_Content_WorkFlow.png" />

#### 사용자 참여 전략
* 사용자에 의해 생성된 UGC, UCC Content를 활용할 것 (Community)
* 포럼 등을 통해 사용자에게 응대한 Content(Feedback)을 재사용 할 것
* 때로는 사용자에게 Content 저작 및 편집까지 맡기는 것도 좋은 방법 (Wiki 스타일)

---
### 소감
* 팀의 사이트 통계와 같은 것들이 왜 필요한지? 통계를 통해 우리는 어떤 결정을 해야 할 것인지 더 깊이 고민'만'하게 됨. 
* 제목에 이끌려 내용을 들었지만 이론적인 내용뿐 Practice가 없어서 많이 아쉬웠음.
* 동시간 대에 했던 Cut to the Core with Simplified Technical English 세션을 들어보지 못해 아쉬웠음.

---
## Writing Technical Docs like a Hacker with Jekyll
### 세션정보
* 발표자: Tom Johnson, Technical Writer, Amazon Lab 126
* 일정: 5월 17일(화) 오후 1시

### 내용
#### 서론
* Single Sourcing이나 Multi Channel Publishing을 지원하는 CMS는 진입 장벽이 높음.
* 고도로 모듈화된 문서 시스템을 쓰려면 Dita, DocBook 같은 XML 포맷을 사용해야 하고 패러다임도 알아야 함.
* 최근 Web Server나 Database로 Web Publishing하는 CMS도 사전에 준비해야 하는 Infrastructure가 있고 이를 이해해야 커스터마이징을 통해 활용도가 올라감.
* 이런 상황에서 Jekyll을 이용한 Documentation Practice를 공유

---
#### Jekyll 이용한 문서화 Practice
* Simple, Stable, Secure, Lightweight, Fast
* 사이트 생성: Jekeyll
* 파일 포맷: Text
* 저작 도구: Text Editor
* 협업 도구: Git, GitHub
* Versioning 도구: Git
* 그 외 필요도구 (Extensions): Server Hooks
* Site Design: [Bootstrap](http://getbootstrap.com/) (UI Framework)
* Content Re-use, Conditional Content: [Liquid](http://shopify.github.io/liquid/) (Template Lanugage)
* Multiple Output: Build Config 활용

#### 소감
Technical Wrtier가 누구보다 Content/Information 특성을 잘 알기 때문에 그 누구보다 그것을 저작하고 관리하는 툴이 어떠해야 하는지 잘 안다. 그런 의미에서 이미 나와있는 툴이 아니라 DIY로 정보 관리에 필요한 것들을 해결해가면서 실무를 연결해 나가는 Practice를 보면서 입이 떡벌어졌다. 필요한 것이 있으면 구하거나 만들거나 하면된다는 것이다. [Tom의 발표](http://idratherbewriting.com/files/jekyllwritetechdocslikehackerstc/#/27) 마지막 부분에 Jekyll이 자신을 매우 자유롭게 만들어줬다는 대목이 인상적이었다. 

---
## Up with Markdown
### 세션정보
* 발표자: Dave Gash, Freelancer (Tech Publisher, Conference Speaker) 
* 일정: 5월 17일(화) 오후 2시 15분

### 내용 및 소감
* Markdwon의 특징으로 Simple하고 빠름을 강조
* 많은 사람들이 Markdown을 쓰고 있고 많은 CMS가 Markdown을 지원
* Markdown 문법과 사용예를 제공함
* Markdown은 GitHub의 인기를 등에 업고 가벼운 Markup 언어의 주류가 되어가고 있음.
* 우리가 Web Publishing할 때 Rich Editor, HTML을 사용하지만 문서를 작성하는 비용과 시간을 단축하기 위해 Markdown과 같이 간단한 Markup 언어의 사용도 고려해야 한다.

---
## Automate Release Notes for Quick and Accurate Results
### 세션정보
* 발표자: Tanya Ivanova, Senior Manager, Technical Publications, Genesys
* 일정: 5월 18일(수) 오전 8시 30분

### 내용
* Release Notes 생성을 자동화하기 위해 Jira와 위키를 사용함.
* Jira에 Release Notes용 Jira Custom Issue Type을 생성하여 사용.
* Jira에서 Release Notes용 Issue를 필터로 걸러내고 플러그인을 이용하여 템플릿 텍스트를 생성
* 이를 MediaWiki의 Extension을 사용하여 배포할 위치에 옮기고 리뷰 과정을 거친 후 배포

---
<img style="margin:0px auto;display:block" width="60%" height="60%" src="http://danjimilk.github.io/DocTest/Auto-Generate_ReleaseNote.png" />

### 소감
* DB에 있는 정보를 쿼리하고 이를 이용하여 Dynamic Content를 생성하는 방법은 상당한 업무 효율을 갖는다.
* 이를 위해 사전에 정보의 설계와 툴의 조합 등을 깊이 고민해야 하는 전제가 따른다.
* Confluence를 쓰지 않고 왜 MediaWiki를 썼냐는 질문에 기존에 MediaWiki로 고객에게 Content를 배포했다는 간단한 대답이 돌아왔다.
