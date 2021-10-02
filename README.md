# 내일의 집

### 1. GNB
* 로그인을 하지 않은 경우
```html
<div class="button-group">
  <button class="lg-hidden is-search gnb-icon-button" type="button" aria-label="검색창 열기 버튼">
    <i class="ic-search"></i>
  </button>

  <a href="/" class="gnb-icon-button is-cart" aria-label="장바구니 페이지로 이동">
    <i class="ic-cart"></i>
    <!-- <strong class="badge">5</strong> -->
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">로그인</a>
    <a href="/">회원가입</a>
  </div>
</div>
```

* 로그인을 했을 경우
```html
<div class="button-group">
  <button class="lg-hidden is-search gnb-icon-button" type="button" aria-label="검색창 열기 버튼">
    <i class="ic-search"></i>
  </button>


  <a href="/" class="sm-hidden gnb-icon-button" aria-label="스크랩북 페이지로 이동">
    <i class="ic-bookmark"></i>
  </a>

  <a href="/" class="sm-hidden gnb-icon-button" aria-label="내 소식 페이지로 이동">
    <i class="ic-bell"></i>
  </a>

  <a href="/" class="gnb-icon-button is-cart" aria-label="장바구니 페이지로 이동">
    <i class="ic-cart"></i>
    <strong class="badge">5</strong>
  </a>

  <button type="button" class="sm-hidden gnb-avatar-button" aria-label="마이메뉴 열기 버튼">
    <div class="avartar-32">
      <img src="./assets/images/img-user-01.jpg" alt="4dallor">
    </div>
  </button>
</div>
```