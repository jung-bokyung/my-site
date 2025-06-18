# my-site.
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>추천템 블로그</title>
  <style>
    body {
      font-family: 'Pretendard', sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
      color: #333;
      display: flex;
    }
    aside {
      width: 240px;
      background-color: #ffffff;
      padding: 20px;
      box-shadow: 2px 0 4px rgba(0,0,0,0.05);
      height: 100vh;
      box-sizing: border-box;
      position: sticky;
      top: 0;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    aside img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 16px;
    }
    aside h2 {
      font-size: 1.2rem;
      margin: 0 0 8px;
    }
    aside p {
      font-size: 0.9rem;
      color: #666;
    }
    aside nav ul {
      list-style: none;
      padding: 0;
      margin-top: 24px;
    }
    aside nav ul li {
      margin-bottom: 10px;
    }
    aside nav ul li a {
      text-decoration: none;
      color: #3478ff;
      font-weight: 500;
    }
    .extras {
      margin-top: 30px;
      font-size: 0.85rem;
    }
    .extras a.instagram {
      display: inline-block;
      background-color: #E1306C;
      color: #fff;
      padding: 6px 10px;
      border-radius: 6px;
      text-decoration: none;
      margin-bottom: 10px;
    }
    .extras .counter, .extras .recent-posts {
      margin-top: 10px;
    }
    .extras .recent-posts ul {
      padding-left: 16px;
      margin-top: 6px;
    }
    .main {
      flex-grow: 1;
    }
    header {
      background-color: #ffffff;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    .section {
      max-width: 960px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .section-title {
      font-size: 1.5rem;
      margin-bottom: 20px;
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }
    .product-card {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      padding: 16px;
      text-align: center;
    }
    .product-card img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .product-card h3 {
      font-size: 1.1rem;
      margin: 12px 0 6px;
    }
    .product-card p {
      font-size: 0.9rem;
      color: #666;
      margin-bottom: 10px;
    }
    .product-card a {
      display: inline-block;
      padding: 8px 14px;
      background-color: #3478ff;
      color: #fff;
      border-radius: 8px;
      text-decoration: none;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <aside>
    <div>
      <img src="https://blogpfthumb-phinf.pstatic.net/MjAyNTA0MjBfOCAg/MDAxNzQ1MTU5OTY4ODEy.-RqflIGUkPhuVodvhqvCmHB8yHFiZui9wco7WghDKS0g.c7KXV_LphznzkBwQ-mzEyLimwh9p5WcuIx2bsFBNV9wg.JPEG/profileImage.jpg?type=s2" alt="프로필 이미지">
      <h2>벼리네</h2>
      <p>쿠팡 추천템을 소개하는 블로그에 오신 걸 환영합니다!</p>
      <nav>
        <ul>
          <li><a href="#kitchen">🍳 주방 추천템</a></li>
          <li><a href="#pet">🐶 반려동물 소품</a></li>
          <li><a href="#camera">📸 촬영용 소품</a></li>
        </ul>
      </nav>
         <div class="recent-posts">
        <strong>📝 최근 글</strong>
        <ul>
          <li>주방 캐릭터 쓰레기통 리뷰</li>
          <li>강아지 코스튬 모음</li>
          <li>촬영 소품 추천 TOP3</li>
        </ul>
      </div>
    </div>
  </aside>

  <div class="main">
    <header>
      <h1>벼리네❤️쿠팡 추천템 블로그✨️</h1>
    </header>

    <div class="section" id="kitchen">
      <h2 class="section-title">🍳 주방 추천템 리스트</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01Uh6Dn91SmPb1liGxm_!!2217292992289-0-cib.jpg" alt="캐릭터 쓰레기통">
          <h3>유포유 주방용 걸이형 캐릭터 쓰레기통</h3>
          <p>실용성 끝판왕 휴지통 등장!</p>
          <a href="https://link.coupang.com/a/czNPb8" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01v2CQIe1oWldgqxj5L_!!2219051035233-0-cib.jpg" alt="세척 바구니">
          <h3>스피세프 다용도 세척 바구니</h3>
          <p>세척 끝 보관까지 직행! ✨</p>
          <a href="https://link.coupang.com/a/czWGQr" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01pzUrNm1c7mbBrQZo8_!!2212864683554-0-cib.jpg" alt="스누피 그릇">
          <h3>스누피 밀폐용기 밥공기 4개입</h3>
          <p>스누피 덕후들 난리남🔥 밥공기가 이렇게 귀여워도 돼?🍚</p>
          <a href="https://link.coupang.com/a/czWP92" target="_blank">쿠팡에서 보기</a>
        </div>
      </div>
    </div>
    <div class="section" id="pet">
      <h2 class="section-title">🐶 반려동물 소품템</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01Kj4ddV1xh9BS13GNY_!!2217755866474-0-cib.jpg" alt="바퀴벌레 코스튬">
          <h3>반려동물 바퀴벌레 코스튬</h3>
          <p>웃음보장! 귀여운 코스튬 🪳</p>
          <a href="https://link.coupang.com/a/czNQrl" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01gvK9dk1QS8nk30YXr_!!2206811161974-0-cib.jpg" alt="장마철 우비">
          <h3>반려동물 우비</h3>
          <p>방수 올인클루시브 우비 🐾</p>
          <a href="https://link.coupang.com/a/czWgIv" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01Ijlqqi1QS8eDYNuFb_!!2206811161974-0-cib.jpg" alt="반려동물 이동가방">
          <h3>귀여운 이동 산책 가방</h3>
          <p>나들이 가방으로 제격 🐾</p>
          <a href="https://link.coupang.com/a/czWiin" target="_blank">쿠팡에서 보기</a>
        </div>
      </div>
    </div>

    <div class="section" id="camera">
      <h2 class="section-title">📸 촬영용 소품 베스트</h2>
      <div class="product-grid">
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01BuKOjn1VJ2yR03fVH_!!2215888902631-0-cib.jpg" alt="오즈모포켓3 필수아이템">
          <h3>마그네틱 확장마운트+스탠드</h3>
          <p>언제 어디서나 촬영 필수템 🎥</p>
          <a href="https://link.coupang.com/a/czNRrG" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01CsIm2P22rkAjezZX0_!!2172337174-0-cib.jpg" alt="스마트폰 거치대">
          <h3>360도 AI센서 인물추적 스마트폰 거치대</h3>
          <p>밝고 환하게 얼굴을 살려주는 필수템 💡</p>
          <a href="https://link.coupang.com/a/czWt3h" target="_blank">쿠팡에서 보기</a>
        </div>
        <div class="product-card">
          <img src="https://cbu01.alicdn.com/img/ibank/O1CN01xGTp511HKxvoy0ySY_!!955000740-0-cib.jpg" alt="카드지갑 케이스">
          <h3>아이폰 14 13 12 11 프로 맥스 플러스</h3>
          <p>이 케이스 하나면 외출 준비 끝! 👜</p>
          <a href="https://link.coupang.com/a/czWy7g" target="_blank">쿠팡에서 보기</a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
