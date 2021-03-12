<template>
  <div class="records-container">
    <img src="~@/assets/title_big_records.gif" />
    <ul>
      <li>
        <a href="/2019_business_report.pdf">2019年度事業報告書</a>
      </li>
      <li><a href="/2019_pl_sheet.pdf">2019年度活動計算書</a></li>
      <li><a href="/2019_balance_sheet.pdf">2019年度貸借対照表</a></li>
    </ul>
  </div>
</template>

<style scoped>
.records-container {
  padding: 0px 30px;
  margin-bottom: 50%;
  font-size: 14.4px;
  line-height: 28px;
}

.records-container img {
  margin-bottom: 40px;
}

@media screen and (max-width: 480px) {
  .records-container {
    padding: 0px 10px;
    margin-bottom: 50%;
    font-size: 16px;
    line-height: 32px;
  }

  .records-container img {
    margin-bottom: 25%;
  }
}
</style>
