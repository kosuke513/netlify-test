<template>
  <div id="footer">
    <div class="link-container">
      <NuxtLink to="/link">リンク</NuxtLink>
      <NuxtLink to="/privacy">プライバシーポリシー</NuxtLink>
    </div>
    <div class="info-container">
      <div class="info-container-left">
        <div class="info-container-left-top">
          <div class="info-text-left">
            <span>お気軽にお問い合わせください！</span>
          </div>
          <div class="info-text-right">
            <p class="info-text-right-top">
              <span>〒671-1502</span>
              <span class="span-right">揖保郡太子町原白毛山921</span>
            </p>
            <p class="info-text-right-bottom">
              <span>Tel 079-277-1872</span>
              <span class="span-right">Fax 079-287-9216</span>
            </p>
          </div>
        </div>
        <div class="info-container-left-bottom">
          <p>
            ©︎&nbsp;Since&nbsp;2012&nbsp;
            <NuxtLink to="/">姫路YMCA</NuxtLink>
            &nbsp;All&nbsp;rights&nbsp;reserved.
          </p>
        </div>
      </div>
      <div class="info-container-right">
        <img src="~@/assets/footer.jpg" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.link-container {
  text-align: right;
  margin-bottom: 12px;
}

.link-container a {
  display: inline-block;
  margin-right: 35px;
  font-size: 14.4px;
}

.info-container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.info-container-left p {
  font-size: 14px;
}

.info-container-left-top {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.info-text-left {
  font-size: 16px;
  font-weight: bold;
  margin-left: 10px;
  margin-right: 70px;
}

.info-text-right-top .span-right {
  margin-left: 14px;
}

.info-text-right-bottom .span-right {
  margin-left: 28px;
}

.info-container-left-bottom p {
  margin-top: 30px;
  margin-left: 14px;
}

@media screen and (max-width: 480px) {
  .link-container {
    text-align: right;
    margin-bottom: 8px;
  }

  .link-container a {
    display: inline-block;
    margin-right: 20px;
    font-size: 16px;
  }

  .info-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .info-container-left p {
    font-size: 16px;
  }

  .info-container-left-top {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
  }

  .info-text-left {
    font-size: 18px;
    font-weight: bold;
    margin-left: 10px;
    margin-right: 70px;
  }

  .info-text-right {
    margin-left: 16px;
  }

  .info-text-right-top .span-right {
    margin-left: 14px;
  }

  .info-text-right-bottom .span-right {
    margin-left: 14px;
  }

  .info-container-left-bottom p {
    margin-top: 16px;
    margin-left: 10px;
    margin-bottom: 10px;
  }

  .info-container-right {
    display: none;
  }
}
</style>
