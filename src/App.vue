<template>
  <header class="site-header">
    <a class="brand" href="#top" aria-label="栖味餐馆首页">
      <span class="brand-mark">栖</span>
      <span>栖味餐馆</span>
    </a>
    <nav class="nav" aria-label="主导航">
      <a href="#menu">菜单</a>
      <a href="#experience">套餐</a>
      <a href="#booking">到店</a>
      <a class="nav-cta" href="#booking">预订座位</a>
    </nav>
  </header>

  <main id="top">
    <section class="hero">
      <div class="hero-content">
        <div class="eyebrow">当季食材 · 炭火料理 · 城市晚餐</div>
        <h1>把一顿饭，做成今天最值得停留的时刻。</h1>
        <p class="hero-copy">
          栖味餐馆用本地鲜蔬、海鲜与慢火酱汁呈现轻松而细致的晚餐体验。适合约会、朋友小聚，也适合一个人安静吃好。
        </p>
        <div class="actions">
          <a class="button primary" href="#booking">今晚订位</a>
          <a class="button secondary" href="#menu">查看招牌菜</a>
        </div>
      </div>
    </section>

    <section class="section intro">
      <div>
        <span class="section-kicker">OUR TABLE</span>
        <h2>从市场到餐桌，每一口都有清楚的来处。</h2>
        <p class="lead">
          每天上午主厨会根据当天送达的食材调整菜单。我们保留食物原本的香气，用炭火、发酵、慢煮和手工面包，让风味更有层次但不过度打扰。
        </p>
        <div class="stats" aria-label="餐厅亮点">
          <div class="stat">
            <strong>26</strong>
            <span>个晚餐座位</span>
          </div>
          <div class="stat">
            <strong>7</strong>
            <span>道季节套餐</span>
          </div>
          <div class="stat">
            <strong>18:00</strong>
            <span>每日开餐</span>
          </div>
        </div>
      </div>
      <div class="intro-photo">
        <img
          src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&w=1200&q=85"
          alt="餐厅餐桌与晚餐氛围"
        />
      </div>
    </section>

    <section class="band" id="menu">
      <div class="section">
        <div class="menu-head">
          <div>
            <span class="section-kicker">SIGNATURES</span>
            <h2>今日推荐</h2>
          </div>
          <p>
            菜单会随季节微调。以下是近期最受欢迎的三道菜，适合作为第一次到店的起点。
          </p>
        </div>

        <div class="dish-grid">
          <article class="dish">
            <div class="dish-image">
              <img
                src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=900&q=85"
                alt="炭烤牛排"
              />
            </div>
            <div class="dish-body">
              <div class="dish-title">
                <h3>炭烤谷饲牛排</h3>
                <span class="price">¥188</span>
              </div>
              <p>迷迭香黄油、烟熏海盐、烤小胡萝卜，肉汁干净浓郁。</p>
            </div>
          </article>

          <article class="dish">
            <div class="dish-image">
              <img
                src="https://images.unsplash.com/photo-1473093295043-cdd812d0e601?auto=format&fit=crop&w=900&q=85"
                alt="手工意面"
              />
            </div>
            <div class="dish-body">
              <div class="dish-title">
                <h3>手工宽面</h3>
                <span class="price">¥96</span>
              </div>
              <p>慢炖番茄、罗勒、帕玛森芝士，口感柔韧，酱汁明亮。</p>
            </div>
          </article>

          <article class="dish">
            <div class="dish-image">
              <img
                src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?auto=format&fit=crop&w=900&q=85"
                alt="当季沙拉"
              />
            </div>
            <div class="dish-body">
              <div class="dish-title">
                <h3>市场鲜蔬沙拉</h3>
                <span class="price">¥68</span>
              </div>
              <p>烤南瓜籽、柑橘醋汁、嫩叶菜与当日鲜果，清爽开胃。</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section class="section experience" id="experience">
      <div>
        <span class="section-kicker">SEAFOOD SET</span>
        <h2>海鲜套餐，把当天的鲜味集中上桌。</h2>
        <p class="lead">
          主厨按当日到港海鲜搭配前菜、主菜与甜点。适合两人晚餐或小型聚餐，口味清爽，保留海鲜本身的鲜甜。
        </p>
        <div class="experience-note">双人套餐 ¥198 · 每日限量 12 份</div>
      </div>
      <div class="room-showcase">
        <div class="room-photo">
          <img
            src="https://images.unsplash.com/photo-1559737558-2f5a35f4523b?auto=format&fit=crop&w=1200&q=85"
            alt="海鲜套餐"
          />
        </div>
        <div class="room-details">
          <div class="room-detail">
            <b>冷前菜</b>
            <p>柑橘油醋虾、炙烤扇贝、海盐番茄，先用清亮酸度打开味觉。</p>
          </div>
          <div class="room-detail">
            <b>主菜</b>
            <p>香草黄油烤鱼配时蔬，搭配蛤蜊白酒汁和手工酸面包。</p>
          </div>
          <div class="room-detail">
            <b>收尾</b>
            <p>青柠奶冻与季节水果，另可加配清爽白葡萄酒。</p>
          </div>
        </div>
      </div>
    </section>

    <section class="booking" id="booking">
      <div class="booking-photo">
        <img
          src="https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=1200&q=85"
          alt="餐厅吧台与灯光"
        />
      </div>
      <div class="booking-panel">
        <span class="section-kicker">VISIT US</span>
        <h2>今晚留一张桌。</h2>
        <p>
          欢迎提前预订。临时到店也可以，我们会按现场空位安排。生日、纪念日或忌口需求可以在预订时备注。
        </p>
        <div class="info-list">
          <div class="info-row">
            <span>地址</span>
            <strong>上海市梧桐路 128 号</strong>
          </div>
          <div class="info-row">
            <span>营业</span>
            <strong>周二至周日 18:00-23:00</strong>
          </div>
          <div class="info-row">
            <span>电话</span>
            <strong>021-8877-1024</strong>
          </div>
        </div>
        <a class="button primary" href="tel:02188771024">电话订位</a>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <span>© 2026 栖味餐馆</span>
    <span>当季菜单 · 私人聚餐 · 周末早午餐</span>
  </footer>
</template>

<style>
:root {
  --ink: #171614;
  --muted: #625e56;
  --paper: #fffaf0;
  --soft: #f4ead8;
  --leaf: #2f5b45;
  --tomato: #b94a36;
  --gold: #c8923b;
  --line: rgba(23, 22, 20, 0.14);
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  color: var(--ink);
  font-family:
    Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
    "Segoe UI", "PingFang SC", "Microsoft YaHei", sans-serif;
  background: var(--paper);
}

a {
  color: inherit;
  text-decoration: none;
}

img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.site-header {
  position: fixed;
  z-index: 10;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 24px;
  padding: 18px clamp(18px, 4vw, 56px);
  color: #fffaf0;
  background: linear-gradient(
    to bottom,
    rgba(12, 12, 10, 0.58),
    rgba(12, 12, 10, 0)
  );
}

.brand {
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 20px;
  font-weight: 750;
  letter-spacing: 0;
}

.brand-mark {
  display: grid;
  width: 34px;
  height: 34px;
  place-items: center;
  border: 1px solid rgba(255, 250, 240, 0.65);
  border-radius: 50%;
  background: rgba(255, 250, 240, 0.13);
}

.nav {
  display: flex;
  align-items: center;
  gap: clamp(14px, 3vw, 34px);
  font-size: 14px;
  font-weight: 650;
}

.nav a {
  opacity: 0.88;
}

.nav a:hover {
  opacity: 1;
}

.nav-cta,
.button {
  display: inline-flex;
  min-height: 44px;
  align-items: center;
  justify-content: center;
  gap: 8px;
  border: 1px solid transparent;
  border-radius: 999px;
  font-weight: 750;
  line-height: 1;
  white-space: nowrap;
}

.nav-cta {
  padding: 0 18px;
  color: var(--ink);
  background: #fffaf0;
}

.hero {
  position: relative;
  min-height: 92vh;
  display: grid;
  align-items: end;
  overflow: hidden;
  color: #fffaf0;
  background:
    linear-gradient(
      90deg,
      rgba(16, 18, 15, 0.84) 0%,
      rgba(16, 18, 15, 0.58) 42%,
      rgba(16, 18, 15, 0.2) 100%
    ),
    url("https://images.unsplash.com/photo-1550966871-3ed3cdb5ed0c?auto=format&fit=crop&w=2200&q=85")
      center / cover;
}

.hero::after {
  content: "";
  position: absolute;
  inset: auto 0 0;
  height: 170px;
  background: linear-gradient(to bottom, rgba(255, 250, 240, 0), var(--paper));
}

.hero-content {
  position: relative;
  z-index: 1;
  width: min(1160px, calc(100% - 36px));
  margin: 0 auto;
  padding: 132px 0 118px;
}

.eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 18px;
  color: rgba(255, 250, 240, 0.86);
  font-size: 13px;
  font-weight: 760;
}

.eyebrow::before {
  content: "";
  width: 38px;
  height: 1px;
  background: var(--gold);
}

h1 {
  max-width: 760px;
  margin: 0;
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(48px, 8vw, 112px);
  font-weight: 500;
  line-height: 0.95;
  letter-spacing: 0;
}

.hero-copy {
  max-width: 590px;
  margin: 24px 0 32px;
  color: rgba(255, 250, 240, 0.82);
  font-size: clamp(17px, 2vw, 21px);
  line-height: 1.7;
}

.actions {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
}

.button {
  padding: 0 22px;
}

.button.primary {
  color: #fffaf0;
  background: var(--tomato);
  box-shadow: 0 18px 38px rgba(75, 23, 14, 0.22);
}

.button.secondary {
  color: #fffaf0;
  border-color: rgba(255, 250, 240, 0.52);
  background: rgba(255, 250, 240, 0.08);
}

.section {
  width: min(1160px, calc(100% - 36px));
  margin: 0 auto;
  padding: 78px 0;
}

.intro {
  display: grid;
  grid-template-columns: 1.05fr 0.95fr;
  gap: clamp(28px, 6vw, 72px);
  align-items: center;
}

.section-kicker {
  color: var(--tomato);
  font-size: 13px;
  font-weight: 800;
}

h2 {
  margin: 10px 0 18px;
  font-family: Georgia, "Times New Roman", serif;
  font-size: clamp(34px, 5vw, 58px);
  font-weight: 500;
  line-height: 1.03;
  letter-spacing: 0;
}

.lead {
  color: var(--muted);
  font-size: 18px;
  line-height: 1.8;
}

.intro-photo {
  min-height: 520px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 28px 70px rgba(80, 54, 25, 0.16);
}

.stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
  margin-top: 34px;
}

.stat {
  border-top: 1px solid var(--line);
  padding-top: 18px;
}

.stat strong {
  display: block;
  font-family: Georgia, "Times New Roman", serif;
  font-size: 34px;
  font-weight: 500;
  color: var(--leaf);
}

.stat span {
  color: var(--muted);
  font-size: 14px;
}

.band {
  background: #223d31;
  color: #fffaf0;
}

.band .section {
  padding: 82px 0;
}

.menu-head {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 28px;
  margin-bottom: 34px;
}

.menu-head p {
  max-width: 480px;
  margin: 0;
  color: rgba(255, 250, 240, 0.72);
  line-height: 1.7;
}

.dish-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}

.dish {
  overflow: hidden;
  border: 1px solid rgba(255, 250, 240, 0.13);
  border-radius: 8px;
  background: rgba(255, 250, 240, 0.06);
}

.dish-image {
  aspect-ratio: 1.22;
}

.dish-body {
  padding: 20px;
}

.dish-title {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 10px;
}

.dish h3 {
  margin: 0;
  font-size: 20px;
}

.price {
  color: #f0c375;
  font-weight: 800;
}

.dish p {
  min-height: 54px;
  margin: 0;
  color: rgba(255, 250, 240, 0.72);
  line-height: 1.6;
}

.experience {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: clamp(28px, 6vw, 68px);
  align-items: center;
}

.experience-note {
  margin-top: 28px;
  padding: 22px 0 0;
  border-top: 1px solid var(--line);
  color: var(--leaf);
  font-size: 15px;
  font-weight: 760;
}

.room-showcase {
  display: grid;
  gap: 18px;
}

.room-photo {
  min-height: 360px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 24px 58px rgba(80, 54, 25, 0.14);
}

.room-details {
  display: grid;
  gap: 0;
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.room-detail {
  display: grid;
  grid-template-columns: 118px 1fr;
  gap: 20px;
  padding: 18px 0;
  border-top: 1px solid var(--line);
}

.room-detail:first-child {
  border-top: 0;
}

.room-detail b {
  color: var(--tomato);
  font-size: 18px;
}

.room-detail p {
  margin: 0;
  color: var(--muted);
  line-height: 1.65;
}

.booking {
  display: grid;
  grid-template-columns: 1fr 1fr;
  min-height: 520px;
  background: #171614;
  color: #fffaf0;
}

.booking-photo {
  min-height: 440px;
}

.booking-panel {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: clamp(34px, 6vw, 72px);
}

.booking-panel p {
  color: rgba(255, 250, 240, 0.75);
  line-height: 1.8;
}

.info-list {
  display: grid;
  gap: 15px;
  margin: 26px 0 30px;
}

.info-row {
  display: flex;
  justify-content: space-between;
  gap: 18px;
  padding-bottom: 14px;
  border-bottom: 1px solid rgba(255, 250, 240, 0.16);
}

.info-row span:first-child {
  color: rgba(255, 250, 240, 0.62);
}

.site-footer {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  width: min(1160px, calc(100% - 36px));
  margin: 0 auto;
  padding: 30px 0;
  color: var(--muted);
  font-size: 14px;
}
</style>