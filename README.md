## 목차
- [1. 프로젝트 소개🙌](#1-프로젝트-소개)
    + [👉하이파이브 마켓?](#하이파이브-마켓)
    + [👉기술스택](#기술스택)
- [2. 프로젝트 진행과정👩🏻‍💻](#2-프로젝트-진행과정)
    + [👉구현기능](#구현기능)
- [3. 잘한 점과 아쉬운 점🎭](#3-잘한-점과-아쉬운-점)
    + [👉잘한 점](#잘한-점)
    + [👉아쉬운 점](#아쉬운-점)
- [4. 프로젝트를 마무리하면서..🎉](#4-프로젝트를-마무리하면서)

> 더 자세한 진행과정은 아래 벨로그에서 확인 가능합니다.<br>
> ➡️ [하이파이브 마켓 회고록](https://velog.io/@hyunzero0/HiFive-%EC%84%B8%EB%AF%B8%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%9A%8C%EA%B3%A0%EB%A1%9D)

<br>

# 1. 프로젝트 소개🙌
>__팀명__
HiFive(총 5명)<br>
__진행기간__
2023.06.15 ~ 2023.06.30 (약 2주)
>
>\* UI 및 DB설계는 모든 인원이 참여하였습니다.
<br>

### 👉하이파이브 마켓?
**내가 필요한 중고물품을 쉽고 빠르게 찾을 수 있는 중고 거래 사이트, 하이파이브 마켓**입니다!
<br>
카테고리 별, 가격 및 지역 별로 내가 필요한 물품을 쉽게 찾고, 쉽게 구매할 수 있습니다.
<br>
또한  구매자와 판매자, 서로의 매너온도를 통하여 거래에 대한 신뢰를 확인할 수 있어 더욱 안전한 중고 거래를 제공합니다!

<br>

### 👉기술스택
**`
backend
`**
Java, SQL, JSP, JSON, Ajax

**`
frontend
`**
HTML, CSS, JavaScript, JQuery, Bootstrap

**`
communication
`**
Git, Notion, Figma

**`
etc
`**
Eclipse, Oracle, VSCode, Tomcat

<br>

# 2. 프로젝트 진행과정👩🏻‍💻
### 👉구현기능
> - ✅ : 내가 담당한 기능
> - 제목 클릭 시 해당 페이지로 이동합니다.

<br>

[✅메인페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/main) : 메인 배너(슬라이드), 메인 카테고리 이동, 인기상품/최신상품, 헤더, 푸터

[회원관리](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/member) : 회원가입(이메일 인증), 로그인, 아이디 찾기, 비밀번호 찾기

[✅마이페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/mypage) : 마이페이지 메인, 구매내역, 판매내역, 찜 목록, 회원정보 관리, 회원탈퇴, 고객센터 이동

[고객센터](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/sc) : 공지사항, 자주하는 질문, 1:1문의, 신고하기

[상품등록 및 수정](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/productregist): 상품등록(이미지, 상품명, 카테고리, 지역(카카오 지역 API), 가격, 설명, 연관태그(해시태그)

[상품 검색 페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/search): 상품 검색, 실시간 인기 검색어, 최근 본 상품

[카테고리 검색 페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/productlist): 카테고리/가격/지역 별 상품 목록

[상품설명 페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/productpage): 상품소개, 소개 본문, 판매자 상점정보, 댓글

[상점 페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/shop): 판매자 프로필, 온도, 판매상품, 후기

[관리자 페이지](https://github.com/hyunzero0/HiFive_market/tree/dev/semi-hifive/src/main/java/com/semi/admin): 회원관리, 고객센터 관리(고객센터/신고하기),  상품관리

<br>

**`
마이페이지
`**

>![](https://velog.velcdn.com/images/hyunzero0/post/916b88e5-8ea0-4cd0-a773-5b0645eaf9e9/image.gif) 구매내역 후기남기기 실시간 온도 변경


>![](https://velog.velcdn.com/images/hyunzero0/post/a17a882c-1f31-4710-9c40-4ed8e647e1a5/image.gif) 실시간 판매상태 변경, 판매상태 별로 모아보기

>![](https://velog.velcdn.com/images/hyunzero0/post/92655abe-1abb-4ba7-bf62-5187a49710fd/image.gif) 판매완료로 상태 변경시 댓글목록에서 구매자 선택

>![](https://velog.velcdn.com/images/hyunzero0/post/3505b9ce-29ad-4c7d-a705-3b84d385f590/image.gif) 찜 취소 시 찜목록에서 삭제(잘못 누를 상황을 대비해 새로고침 시 반영)

>![](https://velog.velcdn.com/images/hyunzero0/post/2d41b815-1e9b-4013-b676-d8a9012b9b1f/image.gif) 프로필 사진 변경, 닉네임 중복확인, 상점 소개글 수정

>![](https://velog.velcdn.com/images/hyunzero0/post/c4547145-0530-4101-b7aa-110cd7cd913c/image.gif) 프로필 사진 삭제 및 변경 시 마이페이지 메인 반영




<br>
  

**`
메인페이지
`**
- 메인페이지 찜하기 기능(로그인 시에만 이용 가능)
- 상품정렬(인기순 - 조회순, 최신순 - 등록순)

> ![](https://velog.velcdn.com/images/hyunzero0/post/49c8ffaf-a9f3-4efb-a5a4-af80e795295d/image.gif) 1. 로그인 시 찜기능 활성화

>![](https://velog.velcdn.com/images/hyunzero0/post/a6404fa5-3fa1-4851-ab0f-6818331f7719/image.gif) 2. 메인페이지 찜 추가 시 마이페이지 찜목록에 추가

<br>

# 3. 잘한 점과 아쉬운 점🎭

### 👉잘한 점

- 팀원 모두 처음 팀 프로젝트를 진행하였음에도 **활발한 의사소통**이 이루어졌다.
의사소통이 팀 프로젝트에서 가장 중요한 부분이라고 생각하는데 팀원들은 적극적으로 본인의 생각을 말하고 들은 생각을 존중하여 답을 해주었다. 그 덕분에 프로젝트가 빠르게 진행될 수 있었다.

- 내가 맡은 기능을 구현하기 전 **자세히 설계하고 정리**를 해둔 덕에 생각한 대로 구현 할 수 있었고, 빠르게 구현할 수 있었다. 덕분에 메인페이지를 담당해 팀에 기여할 수 있어서 좋았다.

- Figma를 이용해 **화면설계**를 했는데 코드로 옮길 수 있을까? 걱정했었는데 걱정과는 다르게 120% 더 잘나온 것 같아서 뿌듯했다. 그리고 팀원들에게도 프론트엔드 부분에서 많은 도움을 줄 수 있었다.

- DB설계는 처음이었는데 조금 더 **효율적인 DB**가 무엇인지 끊임없이 생각했고 의견을 냈다. 내 의견이 정답은 아니더라도 의견을 내면서 많이 배우고 정답에 가까워질 수 있었다.

- 처음에 join문을 사용해서 DB에 있는 데이터를 어떻게 하면 가지고 올 수 있을까? 고민을 많이 했다. 대부분의 사람들이 join한 모든 컬럼명을 dto객체에 필드로 작성했고 나역시 처음엔 그렇게 데이터를 가져왔었다. 그러다가 **has-a 관계**를 알게 됐고 직접 사용하는 방법을 깨달아서 우리 팀원뿐만 아니라 다른 팀원들에게도 설명해줄 수 있었다.

- 프로젝트 하면서 **적극적으로 참여**한 덕분에 스스로 배운 점도 많고 팀에 도움이 되었다. 내가 부족한 부분이라고 부끄러워하고 모른 체 하고 넘어가기보다는 물어보고 스스로 깨닫는 것이 매우 중요하다고 생각했다.

<br>

### 👉아쉬운 점

- **github를 효과적으로 이용하지 못한 것**이 아쉽다. github 다루는 것에 모두 익숙하지 못해서 main브랜치 한 곳에서 작업을 했는데 git에 대한 이해가 필요한 것 같다.

- DB설계 단계에서 **데이터 삭제**에 대한 부분을 잊고있었고, 이미 기능구현 중간 단계에 왔는데 그때서야 생각이 나서 DB를 모두 초기화하고 다시 만들었었다. 대부분 **CASCADE** 설정이 필요한 테이블이라 조금 더 일찍 생각났으면 어땠을까 라는 생각이 들었다.

- **웹소켓을 이용한 실시간 알림 기능**을 구현하고 싶었는데 간단하다고 생각했던 부분들에서 많은 시간이 들었고, 웹소켓을 어떻게 사용해야 할지 감이 안잡혀서 기간 내에 구현할 수 없다고 생각했다. 그래서 아쉽게도 알림 기능은 구현하지 못했지만 팀에 더 기여를 하고자 메인페이지를 담당하였다. 

- 작업중에 하다가 막히면 다른 기능을 구현하고 또 막히면 다른 기능을 구현하곤 했다. 그러니까 다시 그 기능을 구현하려고 할 때 내가 어디까지 구현했었지? 라는 생각이 들었고 코드도 더 지저분해졌다. 그래서 많은 시간을 허비했고, 다음 프로젝트부터는 **우선순위**를 정해서 차례대로 확실하게 구현하고 넘어가면 좋을 것 같다.  

- 서버 배포를 하면 되던 기능도 안되고, 변수도 많은데 발표 전날과 당일에 기능구현을 마무리하느라 **배포 후 테스트**를 많이 하지 못했다. 그래서 모든 기능을 보여주진 못했는데 다음부터는 배포단계에 필요한 시간을 생각해서 작업해야겠다.

<br>
 
# 4. 프로젝트를 마무리하면서..🎉
첫 프로젝트를 시작하기 전에 내 스스로 많이 부족하다고 생각해서 과연 내가 해낼 수 있을까 걱정했다.<br>
역시나 많이 부족했고 나 자신에게 화도 많이 났지만 다 끝나고 보니 많이 성장했고 부족한 부분도 많이 채울 수 있었다!<br>
그렇기에 완벽하진 않더라도 완벽해지기 위한 시작 단계였다고 생각이 든다.<br>
시작 단계를 잘 마무리했으니 이번 프로젝트를 토대로 다음 프로젝트부터는 부족했던 점을 보완해서 성장한 모습으로 진행하고 싶다.<br>
첫 프로젝트 좋은 팀원들과 함께 해서 감사했고 모두 다 멋진 개발자가 되어서 만났으면 좋겠다! 파이팅!😎
